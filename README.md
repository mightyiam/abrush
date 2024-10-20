A nix-community powered Neovim

## Background

Us, software developers with a desire to increase the throughput of our code editing
turn towards the most popular keyboard-centric code editor: Neovim.
And then we spend outrageous durations configuring it,
adding pretty much the same features that everyone needs:
VCS, language support, completion, linting, filesystem navigation, auto-save,
various UI elements, debugging, session persistence and more.
Alternatively, we use a Neovim distribution, such as LazyVim, LunarVim and AstroNvim.
Those provide immense value.
The difference between using them and configuring Neovim ourselves is measured in weeks of work.

Nix users, however, are reluctant to use such Neovim distributions,
because they are distributed in ways that are incompatible with the principles of Nix.
Specifically, these distros typically include their own dependency management,
which is in contrast with the Nix user's intention to manage all dependencies using Nix.
In addition to this principle misalignment,
On NixOS, a distro's attempt at dependency management is likely to fail
when a downloaded ELF executable (e.g. an LSP server) attempts to dynamically load a library.

## The idea

A Nix-powered Neovim distribution is likely to provide immeasureable time savings
to keyboard-centric software developers who use Nix.
Our time would be better spent progressing in our careers and entrepreneurial endeavors,
contributing to the Nix open source ecosystem and maintaining our wellbeing.

The NixVim project provides a solid layer of Nix-powered Neovim configurability.
It is already in use by Nix users, saving them considerable time and effort.
A Nix-powered Neovim distribution is likely to leverage NixVim extensively.
