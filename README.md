# Comprehensive Evergreen Ansible Installer Playbook

A fully configurable Ansible playbook for installing and configuring a complete Evergreen ILS environment on Ubuntu systems.

This playbook has the ability to install and configure:

- Apache
- nginx
- PostgreSQL
- Redis
- OpenSRF
- Evergreen
- All required system prerequisites

Services can be selectively installed or skipped using variables defined in `settings.yml`.

---

## Features

- Automated Evergreen environment deployment
- Modular service installation (skip any component)
- Fully configurable via `settings.yml`; the `settings.yml` file is commented to help walk you through
- Designed for Ubuntu systems
- Idempotent Ansible-based deployment
- GNU licensed

---

## Supported Platform

- Ubuntu (tested on supported LTS releases)

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/EmeraldData/ansible-evergreen.git
cd ansible-evergreen




