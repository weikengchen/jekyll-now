---
layout: post
title: Bibtex Template for NDSS Symposium
---

NDSS website does not offer official bibtex, which adds extra overhead for people who want to cite.

Following the USENIX Security bibtex style, I use the following template for NDSS citation.

<!--more-->

```@inproceedings{**IKK-NDSS12-Mohammad-Islam**,

   author = {**Mohammad Islam and Mehmet Kuzu and Murat Kantarcioglu**},

   title = {**Access Pattern disclosure on Searchable Encryption: Ramification, Attack and Mitigation**},

   booktitle = {The Network and Distributed System Security Symposium **2012** ({NDSS} **12**)},

   year = {**2012**},

   url = {**http://www.internetsociety.org/access-pattern-disclosure-searchable-encryption-ramification-attack-and-mitigation**},

   publisher = {Internet Society},

}```

Note that the author names should be split by "and" instead of ",". Otherwise, it makes the bibliography program misfunction.
