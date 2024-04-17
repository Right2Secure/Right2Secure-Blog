Date Posted: April 17


While browsing today my news feeds. I read a post from the FBI summarizing their 2023 Internet Crime Report[^1], which is based off submissions to the Internet Crime Complaint Center (IC3). 

What struck me the most were the statistics regarding Healthcare and Public Health services attacks.  "The IC3 received 1,193 complaints from organizations belonging to a critical infrastructure sector that were affected by a ransomware attack." [^1] Pg.13. According to the report 249 complaints from critical infrastructure sector were Healthcare and Public health services.  It's important to note that these are just ransomware attacks reported to the FBI from 2023.  The Health Insurance Portability and Accountability Act (HIPAA)[^2] says "A covered entity must notify the Secretary if it discovers a breach of unsecured protected health information. See [45 C.F.R. § 164.408](https://www.gpo.gov/fdsys/granule/CFR-2011-title45-vol1/CFR-2011-title45-vol1-sec164-408)"[^3]. In order to remain HIPAA compliant a company must report a breach of 500+ records within 60 days of discovery to HIPAA per HIPAA regulation, and by the end of the year if under 500 records were breached.  The HIPAA Journal, a website that is self-described as "the leading provider of news, updates, and independent advice for HIPAA compliance" states that "Healthcare Date Breaches of 500+ Records"  725 times in 2023[^4]. I compared and verified these numbers with the [U.S. Department of Health and Human Services-Office for Civil Rights](https://ocrportal.hhs.gov/ocr/breach/breach_report.jsf)(DHHS)[^5].  Based of these two sets of data there were at least 725 breaches.  Assuming there is no redundancy between these two reports, and not accounting for the breaches of 500- records, there is a strong possibility of a much larger number.

Lets take a step back; HIPAA was created in 1996 to protect our Personal Health Information (PHI), and create regulations for companies to follow:
>- "The focus of the statute is to create confidentiality systems within and beyond healthcare facilities.
>- The goal of keeping protected health information private."
\- [Health Insurance Portability and Accountability Act](https://www.ncbi.nlm.nih.gov/books/NBK500019/)[^6]

The HIPAA statute further defines patient private information:
>"Any health care information with an identifier that links a specific patient to healthcare information (name, social security number, telephone number, email address, street address, among others)".[^6]

This is vitally important and sensitive information that HIPAA intends to protect. However, part of the conclusion of a 2017 report [Cyber security in healthcare](https://pubmed.ncbi.nlm.nih.gov/27689562/) states "The healthcare industry is a prime target for medical information theft as it lags behind other leading industries in securing vital data."[^7]   Based off the results from the most recent FBI Crime Report, healthcare services had the most reported number of ransomware attacks of all critical infrastructure. Combined with the reported HIPAA breaches it is evident their is still room for significant change.  HIPAA lays out a [Technical Safeguards - PDF](https://www.hhs.gov/sites/default/files/ocr/privacy/hipaa/administrative/securityrule/techsafeguards.pdf) [^9], which has not been updated since 2007.  Within that PDF and posted on HIPAA's website they define encryption[^10].

>"Encryption is a method of converting an original message of regular text into encoded text. The text is encrypted by means of an algorithm (type of formula). If information is encrypted, there would be a low probability that anyone other than the receiving party who has the key to the code or access to another confidential process would be able to decrypt (translate) the text and convert it into plain, comprehensible text" [^9] [^10]


The HIPAA Journal states that "One of the most effective methods of preventing data breaches is to encrypt PHI"[^11]. However, in the same paragraph The HIPAA Journal also states "Encryption is not mandatory under HIPAA Rules"[^11]. Although I disagree that encryption would not necessarily prevent a breach, it will prevent attackers from getting usable information as stated above. Knowing the intended purpose of HIPAA and the threats posed to PHI, it would be assumed encryption is mandatory. Upon further review of the [National Archives Code of Federal Regulations](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-C)[^12] encryption is listed as "addressable" instead of the other option "required" which has not been revised since its initialization in 2001. On HIPAA's own website the [NIST Guide to Storage Encryption Technologies for End User Devices](https://www.hhs.gov/sites/default/files/ocr/privacy/hipaa/administrative/securityrule/nist800111.pdf)[^13] is listed but states "The following special publications are provided as an informational resource and are not legally binding guidance for covered entities."[^14]  The HIPAA Journal claims that new regulations are on the way for 2024[^15] which is great to hear and we will see what gets changed when it is released.

### My  Conclusion
The fact that HIPAA's last encryption standard was from 2001 is appalling. The digital world is ever evolving, but this a muti-billion dollar industry[^8] and the security of PHI needs to be more highly prioritized.  I believe that encryption of PHI should be mandatory for an entity to become HIPAA compliant along with fines for such violations. HIPAA clearly knows the significance of encryption and still fails to adequately protect PHI.  As the standards are now, healthcare providers that store PHI in an unprotected manner are technically HIPAA compliant. HIPAA needs to raise the bar and accomplish it's goal of protecting PHI from cyber threats.


[^1]: [FBI News Report](https://www.fbi.gov/contact-us/field-offices/sanfrancisco/news/fbi-releases-internet-crime-report),[Direct PDF Link](https://www.ic3.gov/Media/PDF/AnnualReport/2023_IC3Report.pdf)
[^2]: [HIPAA Wikipedia](https://en.wikipedia.org/wiki/Health_Insurance_Portability_and_Accountability_Act)
[^3]: [HIPAA Breach Reporting](https://www.hhs.gov/hipaa/for-professionals/breach-notification/breach-reporting/index.html)
[^4]: [The HIPAA Journal Health Care Data Breach Statistics](https://www.hipaajournal.com/healthcare-data-breach-statistics/)
[^5]: [U.S. Department of Health and Human Services-Office for Civil Rights](https://ocrportal.hhs.gov/ocr/breach/breach_report.jsf)
[^6]: [Health Insurance Portability and Accountability Act](https://www.ncbi.nlm.nih.gov/books/NBK500019/)
[^7]: [Cyber security in healthcare](https://pubmed.ncbi.nlm.nih.gov/27689562/)
[^8]: [National Health Expenditure Data](https://www.cms.gov/data-research/statistics-trends-and-reports/national-health-expenditure-data/nhe-fact-sheet)
[^9]:  [Technical Safeguards - PDF](https://www.hhs.gov/sites/default/files/ocr/privacy/hipaa/administrative/securityrule/techsafeguards.pdf)
[^10]: [HIPAA Definition of Encryption](https://www.hhs.gov/hipaa/for-professionals/faq/2021/what-is-encryption/index.html)
[^11]: [The HIPAA Journal Common Violations](https://www.hipaajournal.com/common-hipaa-violations/)
[^12]: [National Archives Code of Federal Regulations](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-C)
[^13]: [NIST Special Publication 800-111: Guide to Storage Encryption Technologies for End User Devices - PDF](https://www.hhs.gov/sites/default/files/ocr/privacy/hipaa/administrative/securityrule/nist800111.pdf)
[^14]: [Security Rule Guidance Material](https://www.hhs.gov/hipaa/for-professionals/security/guidance/index.html)
[^15]: [New HIPAA Regulations in 2024](https://www.hipaajournal.com/new-hipaa-regulations/#newhipaaregulationsin2023)
