# Home Lab & Self-Hosting Stack

This repository documents my personal self-hosting and home automation environment.

It is meant as a portfolio artifact that shows how I design and operate a small but fairly complete homelab: virtualization, storage, secure remote access, reverse proxying, identity-aware access, observability, media and productivity services, backups, and home automation.

The architecture diagram included in this repository gives a high-level view of the platform rather than step-by-step deployment instructions.

## Why this repository exists

This project is here to demonstrate practical systems thinking across several areas:

- Linux-based self-hosting and service operations.
- KVM-based virtualization and separation of workloads.
- Reverse proxy and remote access patterns.
- Identity and access management for internal services.
- Home automation with Home Assistant and related components.
- Monitoring, dashboards, and service reliability.
- Storage design and backup strategy.
- Documentation of a real-world personal platform.

For a portfolio website, this kind of project can be a strong signal because it shows architecture thinking, breadth across infrastructure and applications, and long-term ownership rather than a toy demo.

## Scope

The stack shown in the diagram includes several categories of systems:

- Network edge and ingress.
- Remote access and secure publishing.
- Virtual machines and service hosting.
- Home automation and telemetry.
- Personal productivity and media services.
- Monitoring and administration.
- Primary storage and off-site backup.

The exact services may evolve over time as the lab changes.

## What the diagram highlights

The diagram is intended to show:

- How traffic reaches the environment.
- Which systems act as gateways, proxies, or access control layers.
- How service hosting is distributed across nodes and virtual machines.
- Which components support home automation.
- How storage and backup are separated.

## Architecture diagram

![Home lab architecture](docs/homelab-diagram.jpg)


## Technologies represented

Examples of technologies visible in the diagram include:

- Ubuntu and Linux-based self-hosting.
- KVM virtualization.
- ZFS storage and backup.
- WireGuard remote access.
- Nginx Proxy Manager.
- Home Assistant ecosystem components.
- Grafana and monitoring tools.
- Containerized self-hosted applications.

## Design principles

A few principles shape this lab:

- Separate infrastructure concerns from application services.
- Prefer reproducible, understandable building blocks.
- Keep remote access controlled and observable.
- Maintain backups outside the main host.
- Use the lab as a place to learn, document, and iterate.

## Disclaimer

This repository is a documentation snapshot of a personal environment.

It does not include secrets, credentials, private configuration, or deployment instructions for internet exposure. Some labels or implementation details may be generalized for safety.
