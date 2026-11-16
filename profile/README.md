# Cyber ICE Box

A cyber range for training and CTF competitions: auto-checked challenges, isolated labs and a live scoreboard in one place.
The code is open, so you can run it on your own servers.

**Site:** [cybericebox.com](https://cybericebox.com)

## What it gives you

- **A separate lab for every challenge.** Each challenge runs in its own isolated network with its own hosts, switches and
  routers. In a competition it is a network to attack; in a class it is a server to set up.
- **Two ways into a lab.** A one-click WireGuard profile, or a single host right in the browser: its web page or its console.
- **Automatic checking.** Simple challenges are verified with a flag. Training challenges are checked step by step, with no
  flags and no scoreboard.
- **Events you run yourself.** Format, registration, challenges from the catalog, pages and a live screen for the venue.
- **Fair play.** Flags are checked on the server, labs are isolated from each other, and the organizer sees every attempt.

## Repositories

Cyber ICE Box is two products. Each works without the other.

### Laboratory

| Repository | What it is |
|---|---|
| [laboratory](https://github.com/cybericebox/laboratory) | Isolated training networks on Kubernetes: devices, VPN, browser access, filtered internet, checks. Any platform can drive it through one API |

### Platform

| Repository | What it is |
|---|---|
| [daemon](https://github.com/cybericebox/daemon) | The backend: users, events, tasks, the catalog |
| [main-frontend](https://github.com/cybericebox/main-frontend) | The landing site |
| [id-frontend](https://github.com/cybericebox/id-frontend) | Sign-in, registration and account settings |
| [admin-frontend](https://github.com/cybericebox/admin-frontend) | The platform panel |
| [exercises-frontend](https://github.com/cybericebox/exercises-frontend) | The task catalog |
| [event-frontend](https://github.com/cybericebox/event-frontend) | The event site: public pages, the participant area, the event panel |

### Tasks and documentation

| Repository | What it is |
|---|---|
| [test-exercises](https://github.com/cybericebox/test-exercises) | Example tasks, ready to import |
| [docs](https://github.com/cybericebox/docs) | Documentation: the laboratory, the platform and how to install them |

Deployment tooling, the task collection and some newer components are developed in private repositories.

## Contact

| | |
|---|---|
| Questions | contact@cybericebox.com |
| Vulnerabilities | security@cybericebox.com, see the [security policy](https://github.com/cybericebox/.github/blob/main/SECURITY.md) |

Created at the V. V. Popovskyy Department of Infocommunication Engineering, Kharkiv National University of Radio
Electronics. Licensed under Apache-2.0.
