# WSO2-2021-1261: Multiple Cross-Site Scripting in WSO2 ESB

Due to improper output encoding, multiple Cross Site Scripting (XSS) attacks have been identified in WSO2 ESB.

### Vendor Disclosure:

The vendor's disclosure and fix for this vulnerability can be found [here](https://security.docs.wso2.com/en/latest/security-announcements/security-advisories/2021/WSO2-2021-1261/).

### Why no CVE?

Neither me nor the vendor requested a CVE for this vulnerability.

### Requirements:

This vulnerability requires:
<br/>
- Some XSSs require valid user credentials

### Proof Of Concept:

More details and the exploitation process can be found in this [PDF](https://github.com/mbadanoiu/WSO2-2021-1261/blob/main/WSO2%20ESB%20-%20WSO2-2021-1261.pdf).

