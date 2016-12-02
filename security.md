# Security

CyTube takes the privacy and security of its users seriously.  In this policy,
you will find an explanation of the precautions that are taken to protect
security and privacy of user data, as well as guidelins for reporting exploits.

## Reporting a Security Issue

**Please do not report security issues on the public GitHub issue tracker.**
This puts users at risk because any malicious user can find the vulnerability on
GitHub and exploit it.  Instead, please send an email to cyzon@cytu.be and
indicate in the subject line that it is a security issue.  I strive to answer
emails within 24 hours, however, please allow up to 7 days for me to respond in
case I am on vacation or otherwise unable to reach my computer.

In addition, **do not purposefully exploit vulnerabilities in the live
website**.  There is a public beta server available at http://beta.synchtube.me,
or you can install the software yourself and play around with it.  I appreciate
reports of security issues, but I believe it is wrong to exploit them on the
live website since it impacts real users.

## Server Security

  * Shell access to CyTube's servers is only available through SSH public-key
    authentication, authorizing only the keys of CyTube administrators.
    Password-based authentication is disabled.

## Database Security

  * Access to the database is guarded by a TLS-encrypted tunnel with client
    certificate authentication.  Only connections from authorized hosts are
    permitted.
  * Database backups are encrypted with GPG.  Decryption is only possible with
    possession of the GPG private key, and knowledge of the key's passphrase.

## Password Security

  * User passwords are securely hashed using
    [bcrypt](https://github.com/kelektiv/node.bcrypt.js).  The plaintext
    password is not stored anywhere.
