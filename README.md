# HeiChips 2026 LibreLane Workshop

This is the repository for the LibreLane workshop during HeiChips 2026.

You will learn how to use and configure LibreLane, debug your design, integrate macros, and implement a full chip.

- LibreLane website: https://librelane.org
- LibreLane repository: https://github.com/librelane/librelane
- LibreLane documentation: https://librelane.readthedocs.io

## Prerequisites

If you haven't installed Nix yet, please follow LibreLane's documentation: [Nix-based Installation](https://librelane.readthedocs.io/en/latest/installation/nix_installation/index.html).

Now, simply execute `nix-shell` from the root directory of this repository to enable all of the required tools. This must be done every time you open a new shell.

The Nix flake of this repository provides the `dev` branch of LibreLane.

> [!NOTE]
> The HeiChips VM has Nix already pre-installed.

## Exercises

- [Exercise 1](exercise_1/README.md): Let's Implement a Counter
- [Exercise 2](exercise_2/README.md): All About Configuration Variables
- [Exercise 3](exercise_3/README.md): Controlling the Flow
- [Exercise 4](exercise_4/README.md): Using Macros
- [Exercise 5](exercise_5/README.md): The LibreLane API
- [Bonus](bonus/README.md): Full Chip Design

### License

The code is licensed under Apache 2.0

Workshop: CC-BY-SA-4.0 Leo Moser
