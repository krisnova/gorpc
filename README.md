# GoRPC

Gorpsy. Remote procedure call for local linux hosts written in Go.

GoRPC is built with the filesystem in mind. 

The use case is to have two `ELF Executable` programs.

The `host` program can be started by the `remote`.

When the host `pid` starts, the `remote` can find the `host` and connect to it.

The `remote` now has access to the exposed `RPC` methods on the `host`.