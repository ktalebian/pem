pem
===
Create private keys and certificates with node.js

[![Build Status](https://secure.travis-ci.org/andris9/pem.png)](http://travis-ci.org/andris9/pem)

**Forked** from [Andris9's PEM](https://github.com/andris9/pem). 

## Difference from Andris9's PEM

The only difference here is an optional option for `createCertificate`. You may now pass in `{serviceKeyPasssword}` to skip the prompt for password when you create and sign you certification using your CA key.
