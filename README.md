# UFW application profiles

Application profiles for the [Uncomplicated Firewall](https://help.ubuntu.com/community/UFW)

## Usage

```bash
ufw allow from any to any app OpenSSH # or any other app

ufw default reject incoming
ufw default allow outgoing
ufw default deny routed

ufw enable
```

## Other useful commands

```bash
ufw show added
ufw show listening
```
