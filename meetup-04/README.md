# Wireshark Users NL - Meetup #3 - 6 mar 2025

Please join us for the fourth (yearly?) Wireshark Users NL get together. This evening will take place at the SSC-ICT office in The Hague. Food and drinks will be provided by SSC-ICT. Please let us know if you have special diet requests.

The program we have put together for you is:

    17:30 - Meetup with Drinks
    18:00 - Pizza
    18:30 - Kickoff by SSC-ICT
    18:45 - TLS decryption with session keys
    19:30 - Break
    19:45 - New kid on the block: Stratoshark
    20:30 - Drinks

## TLS decryption with session keys
### By Richard Koene, network specialist at Rijksoverheid/SSC-ICT

Decrypting TLS traffic is often necessary or at least very handy. But it might be a difficult task to fulfill, The old method of using the servers private key does not work with modern DH based ciphersuites (mandatory in TLSv1.3), The new method is based on using TLS session keys, logged at either one of the endpoints. This can be done by most common browsers (did you know you can do this easy from within Wireshark since Wireshark version 4.4?) or by using devices like F5 BIG-IPs. In this session I will show you how to collect the keys in both scenarios, how to decrypt traffic with them and how to inject the keys into a pcapng file for convenience.

*Bio: My IT adventure began at the age of twelve with programming in Basic. At sixteen, I switched to Turbo Pascal and wrote a planning package for Siemens and at eighteen a cash register program for my local bar.
I started working on a contract basis in process automation. In the late 1990s, I turned my hobby into my profession and switched to IT. I started at American staffing agency Kelly Services, then worked on the implementation of the OV-chipcard network for, among others, Connexion and HTM.
Currently, I have been working at SSC-ICT for seven years. I started here as an F5 specialist. In the meantime, I have taken on the role of coordinator for the team responsible for managing proxies, ADCs, DNS/DHCP/NTP, and MFA.*

## New kid on the block: Stratoshark
### By Sake Blok, protocol analyst at SYN-bit

Gerald, the creator of Wireshark, has been working on a new tool that has just been released to the public: Stratoshark. It has the same look and feel of Wireshark (as it shares quite a bit of common code), but you can analyze (linux) system calls and (cloud) logs with it.

As per www.stratoshark.org:
Stratoshark lets you explore and investigate the application-level behavior of your systems. You can capture system call and log activity and use a variety of advanced features to troubleshoot and analyze that activity. If you've ever used Wireshark, Stratoshark will look very familiar! It's a sibling application that shares the same dissection and filtering engine and much of the same user interface. It supports the same file format as Falco and Sysdig CLI, which lets you pivot seamlessly between each tool. As an added bonus, it's open source, just like Wireshark and Falco.

This talk will give you an introduction to Stratoshark and some hints to get started your Stratoshark journey.

*Bio: Sake has been analyzing packets for over 20 years. During his work, Sake started developing functionality for Wireshark while working with the analyzer in his day-to-day job. He also enhanced multiple protocol dissectors. In 2007, Sake joined the Wireshark Core Development team. In 2009, After working for a reseller of networking equipment for 8 years, he started the company SYN-bit to provide network analysis and training services to enterprises across Europe.*

See you in The Hague on March 6th, 2025!
