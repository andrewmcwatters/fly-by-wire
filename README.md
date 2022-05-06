# fly-by-wire(1)
Automatic pipelines for Concourse CI

## NAME
fbw - automatic pipelines for Concourse CI (**DEVELOPMENT**)

## SYNOPSIS
```sh
fbw [-c config]
```

## DESCRIPTION
The _fly-by-wire_ utility shall automatically set pipelines in Concourse based
on directory structures referred to in Concourse documentation.

The _fly-by-wire_ utility is intended to remove as many manual steps as possible
related to using _fly_ for setting pipelines in order to perform tasks such as
deploy to a wide number of environments without having to run _set-pipeline_
manually across many var files.

## License
GNU General Public License v2.0
