## Release notes

### 0.3.0

- (@bmeck) Added support for `iptables.dump` command.

- (@bmeck) Added support for `iptables.check` command.

- (@bmeck) Added a `process-queue` to avoid **XTables** lock errors when using the commands
  in a concurrent environment.

- Added some tests for `iptables` commands.

### 0.2.0

- Added `ipset` support.

### 0.1.0

- Added `iptables` & `ip6tables` support.