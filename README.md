# Pop!\_OS Free Software Repo

APT repository configuration for building an apt repository with only free software.

> The apt repo is built by running `debrep build` in the root directory of this repo.
On a successful build, the GPG key from the provided email will be requested for
signing each defined repo. The generated `repo/` directory can be hosted on a web
server for other systems to fetch packages from.
