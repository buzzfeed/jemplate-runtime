# jemplate-runtime

Jemplate runtime as a node module (without Ajax or JSON support).

## Background

Generated from the fork of Jemplate at <https://github.com/buzzfeed/jemplate>.

This fork slightly modifies the generated JavaScript from the original Jemplate
at <https://metacpan.org/pod/Jemplate> to make it easier to export and
integrate the runtime with other JS code.

## Runtime

The `index.js` file is a packaged version of the Jemplate runtime for ease of
use with node and npm. It is generated with the command:

    jemplate --runtime --ajax=none --json=none > index.js
