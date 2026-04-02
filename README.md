# Security-advisories
Independent vulnerability research and security advisories - responsibly disclosed

##LOGS##
4/26 S1/IDOR Vulnerability in Report Card Delivery System — Predictable S3 URL Structure Exposes Student PII  CVSS ~7.5
                | No authentication required — bucket is fully public
                  PII exposed — names, DOBs, parent names, grades
                  Scalable — not just one record, potentially thousands
                  Low attack complexity — sequential file IDs, predictable structure
                  Real harm — student data could be used for identity theft, social engineering


                
