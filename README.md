Install and configure Stirling PDF
=========

The role installs and configures Stirling PDF

Role Variables
--------------



Example Playbook
----------------

```yaml
    - hosts: all
      vars:

      roles:
         - { role: tychobrouwer.stirlingpdf }
         - { role: tychobrouwer.stirlingpdf, stirlingpdf_path: /opt/stirlingpdf, stirlingpdf_build_path: /root/stirlingpdf }
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
