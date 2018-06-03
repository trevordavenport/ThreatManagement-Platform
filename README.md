# ThreatManagement-Platform Tool
Threat Management Data and Metrics Tool

> A searchable platform for managing product vulnerabilities

```
Author: Trevor Davenport
```

#### Background ####
```
  Vulnerability Data: Pulled from multiple sources (including private repos)
  
  Python Dependencies: Requests (http://www.python-requests.org/en/latest/)
                       BeautifulSoup (http://www.crummy.com/software/BeautifulSoup/)
                       OpenPYXL (https://openpyxl.readthedocs.io/en/stable/)
```
___

#### Overview ####
```
 1  [*] Vulnerability Metrics pulled from multiple sources
 2   [*] Findings Organized by Product, Severity, Date, etc.
 3    [*] Users Query Data for Specific Subsets of Data.
 4     [*] Data Analysis Reported for Security/Vulnerability Management Tools
```
___

#### Usage ####
**Data can be querired by:**
* Severity (low -> Critical)
* CVE ("CVE-####-####")
* AccessComplexity (Low -> High)
* VulnerabilityType (InputValidation, DesignError, Other, BufferOverflow, AccessValidation, RaceCondition)
* SourcesAvailable (i.e. ExploitDB, ICS-Cert, NIST, etc.)
* PublishedDate

This will search for **High** Vulnerabilities in **Chrome** starting Year **2018** with **Sources** and output report in **XML**
![](https://i.imgur.com/wpxQ2VH.png)

___

### Vulnerability Platform ###
#### Threat Data Example ####
 *Data Available by the platform*

![](https://i.imgur.com/KORZnuk.png)


 *Verbose Vulnerability Data*
![](https://i.imgur.com/HWFL0Ji.png)

 *CVSS Data Imports*
![](https://i.imgur.com/B46XBKU.png)

### Summary of Threat Data ###
 *Data Organized by Title, Abstract, Severity, and Published Date*
![](https://i.imgur.com/cuqX1q9.png)


### Verbose Vulnerability Data ###
 *Verbose Queryable fields*
> Published Date, First Published, Severity, Priority, Title, CVE(s), Exploitability, Access Vector, Access Complexity, Authentication, Vulnerbility Type, CPE URi, Abstract, Version Summary, Sources name, Sources Date, Sources Last Updated, Sources URL
![](https://i.imgur.com/fsIWZhr.png)
 
