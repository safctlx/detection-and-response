**Author:** Safal

**Date:** 2025-11-10

**Tools:**

Tools Used: Detect It Easy, Virustotal, Timeline Viewer, Wireshark, Powershell, Sysinternals
suite

Challenge URL: https://blueteamlabs.online/home/investigation/anakus
dfea6f86e0

**Summary**

1. Analysis of malware to find the entropy, hash and check its reputation. Run the malware in isolated sandbox environment and check the network analysis tool like wireshark to see network pattern and find out the network information.
2. Endpoint analysis, how to know process and parent process.
3. Analysis of Log file to zoom out the finding with the tools like Timeline Viewer.

**Takeways**

1. Use of DIE tool to find about the file information.
2. Entropy means how random or unstructured the data inside a file is. Low entropy
   means data is very organized and predictable, not packed or encrypted. High entropy,
   closes to 8 means that file is packed, compressed, encrypted to hide its real contents.
3. Use of timeline explorer to read the csv log.
4. Mapping to MITRE to find technique and tactics.
