# Discovery Checks

This project contains examples of service discovery checks for linux systems.
These examples are intended for learning purposes only. USE AT YOUR OWN RISK.

## Examples

- Check for available commands on `$PATH`:

  ```
  $ check_path node
  -----> Looking for node on $PATH:
         node is installed at /usr/bin/node

  -----> Version:
         v6.17.1

  -----> Accessors:
         COMMAND   PID   USER  FD   TYPE DEVICE SIZE/OFF     NODE NAME
         node    29287 centos txt    REG  202,1 16883856 13283972 /usr/bin/node
  ```
