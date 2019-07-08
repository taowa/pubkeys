# Public Keys

This repository contains my various public keys as well as related 
documents. All commits should be signed using my current PGP key.
Its validity can be verified [using the web of trust](https://pgp.cs.uu.nl/),
[my website](https://taowa.ca/key.asc) and the [Debian keyring](https://keyring.debian.org/).



Inspired by [Ximin Luo](https://github.com/infinity0/pubkeys).


# PGP / GPG Keys
`Taowa_Munene-Tardif.asc`


My master key lives offline and is manipulated using Tails running from
a CD-ROM. My subkeys live on a security token.


## Certification Policy
I will certify (sign) a User ID when I am reasonably certain that it is 
controlled by the person or organization named on it. This is generally
established by having met a person multiple times in public settings
and having been presented with identity documents at some point, but I
am willing to and have signed aliases when those using them are
recognized under them. The certification will be emailed (or sent by 
XMPP for Jabber addresses) to the email or JID on the User ID. I do not
certify User IDs that do not have an email or JID.


# SSH Keys
`ssh_keys.pub`

My primary SSH key is the same as my GPG subkey, and is thus on a
security token. You can also get it by running
`gpg --export-ssh-key (my gpg key fingerprint)`. It is the first line
of the file.

My backup SSH key is a traditional SSH key. It is stored offline. If
granting me any form of long-term access to a machine, please
add both to `authorized_keys`.


# OMEMO Fingerprints
My OMEMO fingerprints are:
```
C0BB186F 7C243139 852FCF56 3CDFE838 ADFF71C1 FD4580A1 BAC3FB1A A75BD10F
E555D42D 1CE1D5D8 202FF225 335442DE 4DA233D9 3BCFE1E8 650C2F98 736CA569
```

