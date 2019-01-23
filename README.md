# cybersecurity-tools



- wireshark - powerfull sniffer which can decode lots of protocols, lots of filters.
- tshark - command line version of wireshark
- dumpcap (part of wireshark) - can only capture traffic and can be used by wireshark / tshark
- tcpdump - limited protocol decoding but available on most *NIX platforms
- ettercap - used for injecting traffic not sniffing

All tools use libpcap (on windows winpcap) for sniffing. Wireshark/tshark /dumpcap can use tcpdump filter syntax as capture filter.

As tcpdump is available on most \*NIX system I usually use tcpdump. Depending on the problem I sometimes use tcpdump to capture traffic and write it to a file, and then later use wireshark to analyze it. If available, I use tshark but if the problem gets more complicated I still like to write the data to a file and then use Wireshark for analysis.
[src](https://networkengineering.stackexchange.com/questions/10073/difference-between-sniffer-tools)


### Hacking, PCAPs, and Network Analysis
- [Sublist3r](https://github.com/aboul3la/Sublist3r) - Fast subdomains enumeration tool for penetration testers
- [scapy](https://github.com/secdev/scapy) - Scapy: the Python-based interactive packet manipulation program & library. Supports Python 2 & Python 3.
- [knock](https://github.com/guelfoweb/knock) - subdomain scanner
- [scapy-http](https://github.com/invernizzi/scapy-http) - Support for HTTP in Scapy
- [dpkt](https://github.com/kbandla/dpkt) - fast, simple packet creation / parsing, with definitions for the basic TCP/IP protocols
- [kamene](https://github.com/phaethon/kamene) - Network packet and pcap file crafting/sniffing/manipulation/visualization security tool. Originally forked from scapy in 2015 and providing python3 compatibility since then.
- [pcapy](https://github.com/SecureAuthCorp/pcapy) - Pcapy is a Python extension module that interfaces with the libpcap packet capture library.
- [pyshark](https://github.com/KimiNewt/pyshark) - Python wrapper for tshark, allowing python packet parsing using wireshark dissectors
- [PyPCAPKit](https://github.com/JarryShaw/PyPCAPKit) - Python multi-engine PCAP analyse kit.
- [fsociety](https://github.com/Manisso/fsociety) - fsociety Hacking Tools Pack – A Penetration Testing Framework
- [impacket](https://github.com/SecureAuthCorp/impacket) - Impacket is a collection of Python classes for working with network protocols.


### Networking Tools
- [uvloop](https://github.com/MagicStack/uvloop) ([article](https://magic.io/blog/uvloop-blazing-fast-python-networking/)) - Ultra fast asyncio event loop (faster than NodeJS, close to Go speed)
