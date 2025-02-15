# BETTER SAMPLE APEX CLASSES FOR HANDS-ON TRAINING

This folder includes the same 1 Apex Class and the 1 Apex test Class that significantly improve Apex Test results and PMD SCA results above and beyond the 2 lesser quality versions of CaseUpdateHandler. In fact, previous versions have the Test Class segmented into 5 individual Test Classes, while here the Tests are unified in a single Test Class.

The improvements were generated via interaction with CopadoAI, including iterative refinements of the business requirements and acceptance criteria

The improvements are so significant that the final versions have:
* 97% Apex Code Coverage
* No Apex Unit Test Failures
* No PMD Security Violations
* No PMD Code Style Violations

Files are stored in this Repository as lines of code only - these files are not stored here in Salesforce Metadata Format nor Salesforce Source Format Git structure.

The intended use is for a participant in instructor-led or self-paced Hands-on Training to simply copy/paste the lines of code directly into the Salesforce UI as net-new Apex Classes in an Org.

**Assumption** the following Case Queues already exist in all Salesforce Orgs:
1. Partner Escalation Queue
2. Copado Support Queue
