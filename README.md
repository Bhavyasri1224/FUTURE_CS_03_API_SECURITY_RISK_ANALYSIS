# API Security Risk Analysis

## Overview

This project demonstrates a read-only API Security Risk Analysis performed on the JSONPlaceholder Test API. The objective was to identify common API security risks, assess their impact, and provide remediation recommendations based on industry best practices.


## Objective

* Analyze a public API safely and ethically.
* Inspect API responses and endpoint behavior.
* Identify common API security risks.
* Assess risk severity and business impact.
* Suggest remediation measures.


## API Tested

**JSONPlaceholder Test API**

Base URL:

https://jsonplaceholder.typicode.com


## Tools Used

* Postman
* Browser Developer Tools
* GitHub
* MS Word / LibreOffice Writer


## Endpoints Tested

* GET /posts
* GET /users
* GET /comments

## Methodology

1. Reviewed API documentation.
2. Performed read-only GET requests using Postman.
3. Inspected response data and headers.
4. Identified potential security risks.
5. Classified risks according to severity.
6. Suggested mitigation strategies.



## Security Findings

| Risk                    | Severity |
| ----------------------- | -------- |
| Missing Authentication  | Medium   |
| Excessive Data Exposure | Medium   |
| Missing Rate Limiting   | High     |
| Input Validation Issues | Low      |



## Repository Structure

```text
FUTURE_CS_03_API_SECURITY_RISK_ANALYSIS
│
├── README.md
├── Report
│     └── API_Security_Risk_Analysis_Report.pdf
│
└── Screenshots
      ├── request1_posts.png
      ├── request2_users.png
      └── request3_comments.png


## Conclusion

This assessment demonstrates common API security risks found in modern applications and highlights best practices for protecting APIs against unauthorized access, excessive data exposure, and abuse.


## Author

Cyber Security Intern – Future Interns
