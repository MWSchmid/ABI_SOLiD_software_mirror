# Inofficial mirror/repo for SOLiD legacy software

It seems like several SOLiD software tools are not available anymore. I still have some of them and I will mirror them here. However, I protected the archives with a password because there are some license restrictions. You can request the password by private message.

I have copies of the following SOLiD software tools:

SOLiD accuracy enhancement tools 2.2 (SAET 2.2):
    - binary
    - user manual
    - license agreement

DenovoTools (denovo2), contains:
    - asid 1.0
    - MUMmer 3.22
    - utils
    - NOTE: you will need to modify assemble.pl (paths for executables)

Pre- and postprocessor:
    - denovo_preprocessor_solid_v2.2.1.pl
    - denovo_postprocessor_solid_v1.6.pl
    - manuals for both of them

```SH
# that's how I compressed them
gpg-zip -c -o denovo2.gpg denovo2
gpg-zip -c -o prePostProcessors.gpg prePostProcessors
gpg-zip -c -o saet2.2.gpg saet2.2

# this is how you can decrypt and uncompress them
gpg-zip -d denovo2.gpg
gpg-zip -d prePostProcessors.gpg
gpg-zip -d saet2.2.gpg
```

@ABI/Lifetech/Software developer/author/owner: I will remove this repository immediately if you request me to do so.
