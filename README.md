# packer-rhel9
An example of generating RHEL 9.4 minimal install using HashiCorp Packer for a VMware environment.


You just need to download this repo, the Red Hat 9.4 DVD, and run the following command:


```console
$ packer build esx19-rhel-9_4.json 
```

 Tested with the following software versions:

- Packer v1.11.0
- VMware ovftool 4.6.0 (build-21452615)
- VMware ESXi 7.0 update3
