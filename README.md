Dockerfile.nanorc
=================

Dockerfile syntax highlighting for nano

## Installation

1. Create a `nano` directory in `/usr/local/share/`
 * `mkdir /usr/local/share/nano`

2. Copy `Dockerfile.nanorc` to` /usr/local/share/nano`
 * `cp Dockerfile.nanorc /usr/local/share/nano/`

3. Add the following to your `~/.nanorc` to tell nano where to find the `Dockerfile.nanorc` file
  ```
## Dockerfile files
include "/usr/local/share/nano/Dockerfile.nanorc"
  ```
