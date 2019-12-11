# Forensics-Toolkit

Hardware Tools

- SATA Write Blocker - Able to block the write functions of a drive, prevents modification of evidence, and ensures archive integrity.

Software Tools

- Imaging
 - OSXPMem - Memory Aquisition tool for mac, pulls memory and throws into a readable file.
 - Volatility - Memory aquisition tool, using profiles it can show interesting an useful information

- Aquisition
 - Autopsy - Free data aquisition tool, useable on hard drive images. Allows analysis and retrival of data from imaged sources.
 - FTK - Not free data aquisition tool, I see no reason to use it over FTK, but it may have features that are unavailable in the free software.
 - Wireshark - Captures and anaylzes network traffic, useful for looking at specifics of traffic and the contents of the packets.

- Security/Search
 - Snort - Intrusion Prevention that monitors traffic, it can also analyze captured packets.
 - Suricata - Threat detection engine, analyzes captured traffic and shows the results.
 - Grep - Search anything for anything. Pulls out the valid matches.
 - TCPDump
 - Yara - Finds malware using regex. Using a signature, you can search and quickly identify bad actor software.

- Remote
 - Netcat - Networking tool that allows for commands to be send remotely.

- Operating Systems
 - Caine - Analysis distro with included forensics tools, gui based.
 - Paladin - Linux distro that is good for reverse engineering malware
