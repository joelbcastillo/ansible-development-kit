---
layout: default
title: NYC Records Ansible Development Kit
nav_order: 1
---

# Ansible Development Kit
{: .no_toc }

The NYC Records Ansible Development Kit is a collection of tools, libraries, and templates are based on Lean Delivery approach and community best practices for roles and playbooks development.

It is based off of the [Lean Delivery Ansible Development Kit](https://github.com/lean-delivery/ansible-development-kit).

## Why this product?

Ansible Development Kit defines a common workflow for Ansible roles and playbooks development:

- This a comprehensive framework for roles and playbooks development.
- You do not need to reinvent a wheel and start deep diving in best practice from scratch. Just take for a minute and use predefined framework and deliver high quality automated solution in hours.
- You can avoid pitfalls one the way of becoming true Ansible developer. Framework is hands-on engineering excellence.
- Ansible Development Kit is Software Development Life Cycle compliance. 
- Suitable for delivery open source and private solutions.
- Continuous Integration components are already included using reconfigured templates. Just adopt and get value.
- Broad set of open source tools. It is equal to internal licensed products.

## What product provides?

Ansible Development Kit provides:

- All stages described in accordance with SDLC stages such as Development and Implementation, Testing and Integration, Release Management, Feedback and Analysis.
- Preconfigured assets for integration with required components ex. Version Control System, Continuous Integration, Testing, Release Management.
- Broad set of tools and services on each stage of life cycle including GitHub, Travis CI, Molecule, TestInfra, Ansible Galaxy.
- Integration with Amazon, Azure public clouds (coming soon)
- Public and private hosting of CI process.
- Template based on Cookiecutter framework which represents independent repository with logical and hierarchical structure, contains configuration and test assets to avoid starting development from scratch.

## How to make your own?
{: .no_toc }
To organize your own solution based on Ansible Development Kit you need to perform the following:

1.  Make new organization on GitHub or use already existing to store your repositories:
[https://github.com/organizations/new](https://github.com/organizations/new)
2.  Setup Ansible Galaxy integration with GitHub:
[https://galaxy.ansible.com/docs/contributing/importing.html](https://galaxy.ansible.com/docs/contributing/importing.html)
3.  Setup Travis CI accordingly:
[https://docs.travis-ci.com/user/tutorial/](https://docs.travis-ci.com/user/tutorial/)
1.  Organize service accounts for your cloud tests.
2.  Create you Cookiecutter templates:
See [our one](https://github.com/lean-delivery/ansible-development-kit) for example.
8.  Add Lint tests according to documentation:   
[Yamllint](https://yamllint.readthedocs.io/en/stable/)   
[Ansible Lint](https://docs.ansible.com/ansible-lint/)   
9.  Add Molecule and Testinfra tests according to documentation:   
[Molecule](https://molecule.readthedocs.io/en/stable/)   
[Testinfra](https://testinfra.readthedocs.io/en/latest/)   
10.  Start contributing.