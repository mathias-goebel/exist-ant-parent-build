# eXist-ant-buid bug
This repo contains the ant build scripts to reproduce a build error when using
a parent task.

## Configuration
in `build.properties` set exist.version to something lower 3.6.1 and the build
will succeed. For 3.6.1 there will be a error at `junit.xml`.

## Usage
`ant`
