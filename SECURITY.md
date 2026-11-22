# Security policy

## Reporting a vulnerability

Write to **security@cybericebox.com**, or use private vulnerability reporting: the **Security** tab of the affected repository, then **Report a vulnerability**. Please do not open a public issue.

Tell us:

- the repository and the version or commit;
- what an attacker can do;
- how to reproduce it.

The full policy is on the site: [cybericebox.com/security](https://cybericebox.com/security/) (in Ukrainian).

## What counts

- The code of the repositories of this organization and the service at cybericebox.com.
- Anything that reaches beyond your own lab: another team's lab, a cluster node, the platform itself.

Tasks are vulnerable on purpose. A task that can be solved in a way its author did not intend is a task bug, not a
vulnerability: write to contact@cybericebox.com.

## Supported versions

Security fixes are released as patch versions on the three newest minor release lines of each product (the laboratory and the platform each have their own lines). For example, if the newest line is 2.22, then 2.22.x, 2.21.x and 2.20.x are supported. Older lines are not patched: upgrade to a supported line.

The window counts from the first release lines cut under the current release process: laboratory 1.10 and platform 2.20. Earlier releases are not patched.
