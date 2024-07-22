# opendoas-sudo

## About

The `base-devel` package (among others) depends on `sudo`, which is unfavorable
for `opendoas` users. `opendoas-sudo` mitigates that problem, allowing the use
of such packages and programs without `sudo` being installed on the system.

This package:
- Symlinks `sudo` to `doas`
- Replaces the `sudo` package

## Deletion from AUR

Removed from AUR on 26 January 2023.

- [Justification (Mailing List)](https://lists.archlinux.org/archives/list/aur-requests@lists.archlinux.org/message/PYBDANR5YXTILCNHDLVN2OIH3K32TWOI/)
- [Deletion (Mailing List)](https://lists.archlinux.org/archives/list/aur-requests@lists.archlinux.org/message/NLJ6VZII75TQS3YNDTMY6YAB7DAJKYAW/)
