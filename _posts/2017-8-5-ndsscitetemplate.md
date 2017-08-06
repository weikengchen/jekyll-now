---
layout: post
title: Bibtex Template for NDSS Symposium and CIDR
---

NDSS website does not offer official bibtex, which adds extra overhead for people who want to cite.

Following the USENIX Security bibtex style, I use the following template for NDSS citation.

<!--more-->

```
@inproceedings{**IKK-NDSS12-Mohammad-Islam**,
  author = {**Mohammad Islam and Mehmet Kuzu and Murat Kantarcioglu**},
  title = {**Access Pattern disclosure on Searchable Encryption: Ramification, Attack and Mitigation**},
  booktitle = {The Network and Distributed System Security Symposium **2012** ({NDSS} **12**)},
  year = {**2012**},
  url = {**http://www.internetsociety.org/access-pattern-disclosure-searchable-encryption-ramification-attack-and-mitigation**},
  publisher = {Internet Society},
}
```

I also find that CIDR does not provide bibtex, too. Their papers should be downloaded on CIDR official website (in a zip file).

```
@inproceedings{**ABGGKMSTX-CIDR05-Gagan-Aggarwal**,
  author = {**Gagan Aggarwal and Mayank Bawa and Prasanna Ganesan and Hector Garcia-Molina and Krishnaram Kenthapadi and Rajeev Motwani and Utkarsh Srivastava and Dilys Thomas and Ying Xu**},
  title = {**Two Can Keep a Secret: A Distributed Architecture for Secure Database Services**},
  booktitle = {The Conference on Innovative Data Systems Research **2005** ({CIDR} **05**)},
  year = {**2005**},
  url = {**http://cidrdb.org/cidr2005/program.html**},
  publisher = {CIDR},
}
```




Note that the author names should be split by "and" instead of ",". Otherwise, it makes the bibliography program misfunction.
