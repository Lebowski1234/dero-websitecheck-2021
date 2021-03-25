# Website Validation Smart Contract - 2021

This smart contract was originally written for the Dero Stargate Smart Contract competition in 2019. Re-released in 2021 for the dARCH — Decentralized Architecture Competition Series - Event 0!

This smart contract attempts to solve two problems for websites where security is a high priority:

1 - A website may fall victim to DNS highjacking, whereby the domain name is pointed to a malicious IP address. It may be possible for the user to detect the security breach by checking the SSL credentials (or lack thereof), however if the highjacker has created a self-signed SSL certificate, many users may not notice. 

2 - A website owner may wish to change the domain name. If the name change is unplanned (for example a torrent site has been closed down by the hosting service), how does the website owner communicate the new domain to the regular users of the website? How do the users know that a name change is legitimate, or whether the address of a phishing site is being circulated?

Some examples of where this smart contract may be particularly useful are:

* Cryptocurrency web wallets, which are prime targets for hackers as large sums of cryptocurrency are at stake. 
* Torrent sharing websites, which get taken offline regularly.
* Download sites for cryptocurrency node / wallet binaries, where there is an incentive for hackers to embed malicious code (e.g. key loggers. 


For a full description, refer to the original version readme at  
[https://github.com/Lebowski1234/dero-websitecheck](https://github.com/Lebowski1234/dero-websitecheck). Note that all curl commands in the original readme are no longer valid, and the referenced UI will not work either without major updates. 
