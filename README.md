# Debianization for the Erlang gen_leader Library

The repo contains so called DEBIAN directory with
scripts and configs needed to package the
[gen_leader](https://github.com/garret-smith/gen_leader_revival/)
library into a DEB package for the Debian Wheezy distro.

Implements a leader election behavior modeled after gen_server.
This is a project to revive and modernize the gen_leader library.
Numerous versions of this project exist, developed by disparate
groups with different aims. By collecting and integrating these
we hope to provide a new standard-library-quality module for the
Erlang runtime that provides leader-election functionality without
many of the difficulties traditionally associated with such.
