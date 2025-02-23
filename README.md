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
    - role: tychobrouwer.stirlingpdf
    
    - role: tychobrouwer.stirlingpdf
      stirlingpdf_path: /opt/stirlingpdf
      stirlingpdf_build_path: /root/stirlingpdf
      stirlingpdf_jbig2enc_path: /opt/jbig2enc
      stirlingpdf_java_deb_key: https://apt.corretto.aws/corretto.key
      stirlingpdf_java_deb_repo: deb https://apt.corretto.aws stable main
      stirlingpdf_java_package: java-21-amazon-corretto-jdk
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
