# Nephilim

DDoS tool

# Attacks
* DNS Amp

* NTP Amp

* SSDP Amp

* SNMP Amp

# Requirements
* Python 2.7

* [Pinject](https://github.com/Vexvain/Pinject/tree/master/)

# How to use	 
```  _   _ ______ _____  _    _ _____ _      _____ __  __ 
    | \ | |  ____|  __ \| |  | |_   _| |    |_   _|  \/  |
    |  \| | |__  | |__) | |__| | | | | |      | | | \  / |
    | . ` |  __| |  ___/|  __  | | | | |      | | | |\/| |
    | |\  | |____| |    | |  | |_| |_| |____ _| |_| |  | |
    |_| \_|______|_|    |_|  |_|_____|______|_____|_|  |_|
                                                       

Usage: 
Nephilim.py target.com [options]        # DDoS
Nephilim.py benchmark [options]         # Calculate AMPLIFICATION factor


Options:
  -h, --help            show this help message and exit
  -d FILE:FILE|DOMAIN, --dns=FILE:FILE|DOMAIN
                        DNS Amplification File and Domains to Resolve (e.g:
                        dns.txt:[evildomain.com|domains_file.txt]
  -n FILE, --ntp=FILE   NTP Amplification file
  -s FILE, --snmp=FILE  SNMP Amplification file
  -p FILE, --ssdp=FILE  SSDP Amplification file
  -t N, --threads=N     Number of threads (default=1)
