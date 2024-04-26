**Office Endpoints IP Addresses for PfSense URL Table (IP)**
============================================================

Welcome to this repository, which contains text files with IP addresses used by Microsoft Office endpoints. These IP addresses are essential for configuring firewalls and proxies to allow traffic to and from Office online services.

**Contents**
------------

This repository contains three text files:

* `ipv4.txt`: a list of IPv4 addresses used by Office endpoints
* `ipv6.txt`: a list of IPv6 addresses used by Office endpoints
* `fqdn.txt`: a list of Fully Qualified Domain Names (FQDNs) used by Office endpoints

**Source**
----------

The IP addresses listed in these files are obtained from the official Microsoft source: [https://endpoints.office.com](https://endpoints.office.com). This website provides a comprehensive list of IP addresses and FQDNs used by Office online services, ensuring that your firewall and proxy configurations are up-to-date and accurate.

**Usage with PfSense**
--------------------

These text files are intended to be used as a URL Table (IP) in PfSense, a popular open-source firewall and router platform. By importing inserting  the Github raw link of these text files into PfSense, you can easily configure your firewall to allow traffic to and from Office online services, ensuring uninterrupted access to Microsoft Office applications and services.

**How to use with PfSense**
-------------------------

To use these files with PfSense, follow these steps:

1. Download the latest version of the text files from this repository.
2. Log in to your PfSense web interface.
3. Navigate to **Firewall** > **URL Table**.
4. Click **+** to add a new URL Table.
5. Select **IP** as the table type.
6. insert the link to the raw text file.
7. Repeat the process for each text file (ipv6.txt and fqdn.txt).

**Important Notes**
-----------------

* These files are provided as-is, and you should verify their accuracy and suitability for your specific use case. In my experience, addiotional IPs are still needed to make OFFICE 365 work through Pfsense firewall, but these file are a good starting point.

**Contributing**
------------

If you'd like to contribute to this repository, please fork the repository, make your changes, and submit a pull request. Your contributions are welcome!
