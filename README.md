# Public Keys

This repository contains my various public keys as well as related
documents. All commits should be signed using my current PGP key.
Its validity can be verified [using the web of trust](https://pgp.cs.uu.nl/),
[my website](https://taowa.ca/key.asc) and the
[Debian keyring](https://keyring.debian.org/).



Inspired by [Ximin Luo](https://github.com/infinity0/pubkeys).


# PGP / GPG Keys
`Taowa_Munene-Tardif.asc`
`Phone.asc`
`Windows.asc`
`travelphone.asc`

The master key for my main key (`Taowa_Munene-Tardif.asc`) lives
offline and is manipulated using Tails running from a CD-ROM.
My subkeys live on a security token.

**Please avoid sending me encrypted mail. If you must communicate
securely with me, Signal or XMPP is much more likely to get you a 
prompt response.**

You'll also find `Phone.asc` and `Windows.asc`, which live online on my
phone and Windows machines. Note that these keys should **never**
certify keys that aren't my main key. If they do, please let me know.

On occasion you may find a `travelphone.asc`. This is the key for my
phone while I'm travelling. If it's there, I probably won't be able to
reply to you if messages are encrypted to `Phone.asc`.

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
213FA6A5 88BAF314 C5887648 13BFCA49 C6D3DF0C 3E35424F AC8512D9 0E7C7713
E555D42D 1CE1D5D8 202FF225 335442DE 4DA233D9 3BCFE1E8 650C2F98 736CA569
9E44A1DA 9291804F F2926645 AF74484E E90530D2 E86AFE3F 8A7310AC A4007642
C95D3570 0C9A1D61 E355F6B2 680751B5 7F769D3B F91B9F83 600756EC D08A6362
```

