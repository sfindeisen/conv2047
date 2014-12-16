conv2047
========

A very simple RFC 2047 Unicode e-mail header field converter. It is based on Encode Perl module.

    Usage:
      ./conv2047.pl [-c] -d
      ./conv2047.pl -e

    The program reads header lines from standard input and tries
    to decode or encode them.

    Operation modes:
      -d decode (MIME-Header --> UTF-8)
      -e encode (UTF-8 --> MIME-Header)

    Options:
      -c concatenate multiple output lines into 1
