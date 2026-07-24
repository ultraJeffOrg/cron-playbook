# Cron Playbook

Ansible playbook project for scheduled automation tasks.

## Overview

This project was scaffolded using the Ansible automation portal in Red Hat Developer Hub. It contains a playbook project with a collection skeleton preconfigured with Ansible best practices.

## Project Structure

- `collections/` — Custom Ansible collection with roles and modules
- `playbooks/` — Ansible playbooks for automation tasks
- `inventory/` — Inventory files for target hosts
- `devfile.yaml` — Dev Spaces configuration for browser-based development

## Getting Started

1. Open this project in Dev Spaces for a pre-configured development environment
2. Edit playbooks in `playbooks/` or add roles to the collection
3. Test locally with `ansible-lint` and `molecule`
4. Push changes to trigger CI/CD pipeline
