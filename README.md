This example shows a problem passing a string variable with spaces

Without passing any variable, it works.
```
$ ./debos.sh example.yaml
```

When we pass a variable, it fails.
```
$ ./debos.sh -t cmdline:"console=ttyS1,115200n8 root=/dev/sda3 ro" example.yaml
```
