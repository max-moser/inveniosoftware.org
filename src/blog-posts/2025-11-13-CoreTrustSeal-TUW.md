---
title: "Can InvenioRDM be trusted?"
authors:
  - max-moser
date: 2025-11-13
doi: https://doi.org/10.5555/to-do
tags:
  - InvenioRDM
  - Showcase
  - Certification
permalink: "/blog/2025-11-13-CoreTrustSeal-TUW.md/"
---

TODO write news article

* is InvenioRDM trustworthy? according to CTS, yes!
* demonstrate competence in three key areas: organizational infrastructure, digital object management, and information technology & security
* TUWRD achieved certification in September 2025
* inveniordm provides a very solid basis for building a trusted repository, already checking a lot of boxes on its own
* notable customizations include the very secure storage, including multiple layers of backups
* authentication via the eduGAIN interfederation, allowing login via your organization's SSO (the flip side is that every user is vouched for by their institution)
* mandatory reviews before publication aiming to maximize reusability, via the `invenio-curations` package that's being developed in collaboration with TU Graz


[tudata@tuwien.ac.at](mailto:tudata@tuwien.ac.at)
[TU Wien news article](https://www.tuwien.at/en/tu-wien/news/news-articles/news/tu-wien-research-data-repository-erhaelt-coretrustseal-1)



One might wonder, can InvenioRDM be considered trustworthy?
At least according to the [CoreTrustSeal](https://www.coretrustseal.org/) (or CTS for short), the answer is yes!

The CTS is a certification for repositories that demonstrate competence in three key areas:
* Organisational infrastructure - organisational persistence and ability to handle legal and ethical questions
* Digital object management - quality assurance and long-term availability of content
* Information technology & security - soundness and security of the technical basis

Effectively, it shows that a repository is a better place to store data long-term than that USB drive in the bottom drawer.


In September 2025, the institutional repository TU Wien Research Data, finally achieved this certification.

InvenioRDM provides a solid basis for building a certified repository, already checking a lot of boxes from the get-go.
However, at TU Wien we know that customizations are the spice of life; and a few of ours are actually quite relevant for the CTS:

For one, we have attached a secure in-house storage system with location-redundant copies and multiple layers of backups on disks and magnetic tapes.
This ensures that data, once uploaded, does not get lost or become corrupted; especially in combination with the periodic fixity checks.

Also, we require mandatory reviews before publication of records to maximize reusability.
With them, we give our researchers feedback on their metadata, the structure of their datasets, and the file formats being used.
In our experience, it is much easier to ensure quality at ingest instead of fixing stuff up later on.
The curation reviews are implemented via the [`Invenio-Curations`](https://github.com/tu-graz-library/invenio-curations/) package that is developed in collaboration with TU Graz.

We also allow authentication via the eduGAIN interfederation, allowing users to log in via their home organization's SSO.
On the flip side, this also means that we only have users in our system who are vouched for by select organizations.


![The CTS core team at TU Wien: Tomasz Miksa, Christiane Stork, and Maximilian Moser (left to right)](/assets/images/blog-posts/tuw-cts.jpg)
