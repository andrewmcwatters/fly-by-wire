# fly-by-wire(1)
Automatic pipelines for Concourse CI

**fly-by-wire(1)** is a POSIX sh utility for automatically setting pipelines in
Concourse based on directory structures referred to in Concourse documentation.

It is intended to remove as many manual steps as possible related to using
`fly(1)` for setting pipelines in order to do things like deploy to a wide
number of environments without having to run `set-pipeline` manually across many
var files.

## Usage
```sh
cd <directory>
./fbw
```

## License
GNU General Public License v2.0
