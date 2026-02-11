# 📦 Packet by Packet

Interactive visual explainers for IT protocols — learn by seeing them in action.

🌐 **Live demo:** [https://nineunderground.github.io/how-to-it-protocols/](https://nineunderground.github.io/how-to-it-protocols/)

🎬 **YouTube:** [@PacketbyPacket](https://www.youtube.com/@PacketbyPacket)

## Protocols

| Protocol | Layer | Description |
|----------|-------|-------------|
| [ARP](./arp/) | L2/L3 | Address Resolution — how devices find MAC addresses on a LAN |
| [DHCP](./dhcp/) | L7 | Dynamic Host Configuration — DORA sequence for auto IP assignment |
| [ICMP / Ping](./icmp-ping/) | L3 | Echo Request/Reply and traceroute visualization |
| [TCP 3-Way Handshake](./tcp-handshake/) | L4 | SYN → SYN-ACK → ACK connection establishment |
| [DNS Resolution](./dns-resolution/) | L7 | Recursive lookup: root → TLD → authoritative nameserver |
| [TLS Handshake](./tls-handshake/) | L5/L6 | TLS 1.3 — certificates, key exchange, encrypted session |
| [HTTP Request/Response](./http-request/) | L7 | GET/POST, headers, status codes, cookies |
| [WebSocket](./websocket/) | L7 | HTTP upgrade to persistent bidirectional connection |
| [BGP Peering](./bgp-peering/) | L3 | How ISPs exchange routing tables |
| [OAuth 2.0](./oauth2/) | L7 | Authorization Code Flow — "Login with Google" |

## About

Each protocol gets its own interactive web visualization — no server needed, pure HTML/CSS/JS. Built for learning, teaching, and YouTube content.

## Contributing

PRs welcome! Each protocol lives in its own folder with a standalone `index.html`.

## License

MIT
