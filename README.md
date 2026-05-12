# IP Calculator

An IPv4 subnet calculator — single-file HTML/JS tool. No server, no dependencies, just open in a browser.

## Features

- **Network info** — network address, broadcast, subnet mask, wildcard mask
- **Usable hosts** — first/last host and total count
- **CIDR support** — any prefix from `/0` to `/32`
- **IP classification** — class (A–E), private/public scope (RFC 1918)
- **Binary views** — bit-by-bit breakdown with network vs host bits colour-coded
- **Keyboard friendly** — Enter to calculate, example buttons for quick testing

## Usage

```
Open ipcalc.html in any browser
Type an IP/CIDR (e.g. 192.168.1.0/24)
Press Enter or click Calculate
```

Or click one of the example buttons below the input field.

## Examples

| Input | Network | Broadcast | Hosts |
|---|---|---|---|
| `10.0.0.0/8` | 10.0.0.0 | 10.255.255.255 | 16,777,214 |
| `172.16.0.0/12` | 172.16.0.0 | 172.31.255.255 | 1,048,574 |
| `192.168.1.0/24` | 192.168.1.0 | 192.168.1.255 | 254 |
| `192.168.1.15/28` | 192.168.1.0 | 192.168.1.15 | 14 |
| `10.0.0.1/32` | 10.0.0.1 | 10.0.0.1 | 1 |

## Tech

Plain HTML + CSS + JavaScript. Zero dependencies. Works offline.
