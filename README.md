## `wasmer-capi-headers`

Automatically updated header files of Wasmer C API.

### How it works

An automated workflow periodically checks the [`wasmio/wasmer`](https://github.com/wasmerio/wasmer) repository for the latest release. If a new release is presented, we build `wasmer-capi` crate, extract the header files and release it under the same tag,
as the Wasmer main release.

I suppose this repository will be archived and considered deprecated once Wasmer will start publishing headers alongside other release articats. 
