OpenSourceCorp
===============

[ In Progress ]

Welcome to OpenSourceCorp -- the free and open-source enterprise.

Here at OpenSourceCorp, we write the best code for the best software, deployed
via the best CI/CD pipelines, onto the best infrastructure, secured via industry
best-practices, and supported by the best documentation.

We do this because we have developed a general frustration with ***how*** modern
teams are expected to learn different things -- especially how so many tools,
technologies, and processes are used in concert with each other in a broader
enterprise ecosystem. There are plenty of tutorials and "getting started" guides
for any number of tools or topics, but while many of these have supplements for
their use in a larger ecosystem, they never feel like quite enough to document
the holistic lifecycle of a use case. The most valuable learning material for
*real* use cases happens within company walls with propietary software -- where
if you're not an employee, you don't get to learn.

Take a secrets manager like [HashiCorp Vault](https://www.vaultproject.io/docs).
Its documentation is very comprehensive, and it provides a wealth of use cases,
simple & complex configurations, and more -- but what if you're self-hosting a
Vault cluster at your company? How do you *actually* deploy that cluster, and
not rely on manually launching it via the (very good) installation instructions?
Do you bootstrap some EC2 machines in a CloudFormation template for an AWS
deployment? Do you do that with raw shell code,
[Ansible](https://docs.ansible.com/), or something else? Or maybe you stuff
Vault containers into [Kubernetes](https://kubernetes.io/docs/)? Their docs have
a [Helm chart](https://www.vaultproject.io/docs/platform/k8s/helm), sure, but
what if your team/company doesn't use Helm? Isn't *allowed* to use Helm?

Which all begs the same question again -- ***how do you actually deploy it in
real life?***

This, and ever more questions, are what OpenSourceCorp aims to provide. Real,
*holistic* code, real discussions, for enterprise solutions.

***All 100% in the open.***

---

Roadmap
-------

- Core values
- Contribution model
- Sample code
- Text-based Wiki solution, NOT a Github wiki
- Target platform commentary -- "why not (strictly) Kubernetes/AWS/etc.", etc.

More
----

- [About Us](./docs/about.md)
- [Core Values](./docs/core-values.md)
