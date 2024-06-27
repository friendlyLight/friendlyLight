
## Enable Privilege Execute Mode

```bash
enable
```

## Enable Global Configuration Mode

```bash
configure terminal
```

## Set Enable Password for Privilege Execute Mode

```bash
line console 0
password cisco
login
```

## Set Enable Password and Enable Secret for Global Configuration Mode

```bash
enable password cisco
enable secret cisco123
```

## Encrypt Passwords

```bash
service password-encryption
```

## Change Intermediary Device Name

```bash
hostname [name]
```

## Configure Banner

```bash
banner motd #Authorized Access Only#
```

## Show Startup Configuration

```bash
sw1# show startup-config
```

## Show Running Configuration

```bash
sw1# show running-config
```

## Save Configuration

```bash
write memory
```

or

```bash
copy running-config startup-config
```
