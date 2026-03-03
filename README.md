# Comprehensive Evergreen Ansible Installer Playbook

A fully configurable Ansible playbook for installing and configuring a complete Evergreen ILS environment on Ubuntu systems.

This playbook installs and configures:

- OpenSRF
- Apache
- nginx
- PostgreSQL
- Redis
- Evergreen
- All required system prerequisites

Services can be selectively enabled or skipped using variables defined in `settings.yml`.

---

## Features

- Automated Evergreen environment deployment
- Modular service installation (skip any component)
- Fully configurable via `settings.yml`
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
git clone https://github.com/yourusername/your-repository.git
cd your-repository
