# Pop!\_OS Free Software Repo

APT repository configuration for building an apt repository with only free software.

> This repo is built by running `debrep build` in the directory of the provided
`sources.toml` file. On a successful build, the GPG key from the provided email
will be requested for signing the repo. The generated `repo/` directory can be
hosted on a web server for other systems to fetch packages from.
