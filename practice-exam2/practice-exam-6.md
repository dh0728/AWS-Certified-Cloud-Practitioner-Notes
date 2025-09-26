## Practice Exam 6 — Q6

## Practice Exam 6 — Q6
**101. Which of the following security measures protect access to an AWS account? (Choose two.)**  
> AWS 계정 접근을 보호하는 보안 조치는 무엇입니까? (2개 선택)

- A. Enable AWS CloudTrail.  
- B. Grant least privilege access to IAM users.  
- C. Create one IAM user and share with many developers and users.  
- D. Enable Amazon CloudFront.  
- E. Activate multi-factor authentication (MFA) for privileged users.  

<details><summary>Answer</summary>

**Correct:** B, E  
**Explanation (English):**  
If you decide to create service accounts (for applications running outside AWS that need programmatic access), you should create a dedicated service account for each use case. This allows you to restrict the associated policy to only the necessary permissions, minimizing risk if credentials are compromised. For example, if a monitoring tool and a release management tool both require AWS access, you should create two separate service accounts with distinct policies that grant only the minimum permissions needed.  

AWS Multi-Factor Authentication (MFA) is a best practice that adds an additional security layer beyond username and password. With MFA enabled, when a user signs in to the AWS Management Console, they must provide their username and password (first factor — what they know) and an authentication code from an MFA device (second factor — what they have). Together, these multiple factors significantly strengthen account security.  

**해설 (Korean):**  
- **최소 권한 원칙 적용** → 각 서비스 계정은 필요한 권한만 부여해야 하며, 별도 계정을 만들어야 합니다.  
- **MFA 활성화** → 사용자 이름·비밀번호 외에 MFA 장치 인증 코드까지 요구하여 보안을 강화합니다.  

</details>

---

**102. Which service provides a hybrid storage service that enables on-premises applications to seamlessly use cloud storage?**  
> 온프레미스 애플리케이션이 클라우드 스토리지를 원활하게 사용할 수 있도록 하는 하이브리드 스토리지 서비스를 제공하는 것은 무엇입니까?

- A. Amazon Glacier  
- B. AWS Snowball  
- C. AWS Storage Gateway  
- D. Amazon Elastic Block Storage (Amazon EBS)  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation (English):**  
AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. Customers use Storage Gateway to simplify storage management and reduce costs for key hybrid cloud storage use cases.  

**해설 (Korean):**  
AWS Storage Gateway는 온프레미스 환경에서 클라우드 스토리지를 활용할 수 있게 해주는 하이브리드 서비스입니다. 이를 통해 테이프 백업을 클라우드로 이전하거나, 클라우드 기반 파일 공유로 비용을 절감할 수 있습니다.  

</details>

---

**103. Which of the following services falls under the responsibility of the customer to maintain operating system configuration, security patching, and networking?**  
> 운영체제 구성, 보안 패치, 네트워킹을 고객이 직접 유지 관리해야 하는 서비스는 무엇입니까?

- A. Amazon RDS  
- B. Amazon EC2  
- C. Amazon ElastiCache  
- D. AWS Fargate  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation (English):**  
The customer is responsible for managing, supporting, patching, and controlling the guest operating system and related aspects for Amazon EC2.  

**해설 (Korean):**  
Amazon EC2는 운영체제 구성, 보안 패치, 네트워크 관리 등 OS 레벨 작업은 고객이 책임져야 합니다.  

</details>

---

**104. Which of the following is an important architectural design principle when designing cloud applications?**  
> 클라우드 애플리케이션 설계 시 중요한 아키텍처 설계 원칙은 무엇입니까?

- A. Use multiple Availability Zones.  
- B. Use tightly coupled components.  
- C. Use open source software.  
- D. Provision extra capacity.  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation (English):**  
This relates to “Reliability Design Principles and Best Practices.” Each availability zone runs on physically distinct, independent infrastructure engineered for high reliability.  

**해설 (Korean):**  
멀티 AZ 아키텍처는 가용성과 안정성을 보장하기 위한 핵심 설계 원칙입니다. 한 AZ에 장애가 발생해도 다른 AZ가 영향을 최소화할 수 있습니다.  

</details>

---

**105. Amazon Relational Database Service (Amazon RDS) offers which of the following benefits over traditional database management?**  
> Amazon RDS가 기존 데이터베이스 관리에 비해 제공하는 이점은 무엇입니까?

- A. AWS manages the data stored in Amazon RDS tables.  
- B. AWS manages the maintenance of the operating system.  
- C. AWS automatically scales up instance types on demand.  
- D. AWS manages the database type.  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation (English):**  
AWS Managed Services such as RDS automate administrative tasks like monitoring, patch management, security, and backup services. AWS manages OS maintenance.  

**해설 (Korean):**  
Amazon RDS는 운영체제 유지 관리와 보안 패치, 백업 등을 AWS가 대신 처리해주므로 사용자는 데이터와 애플리케이션에 집중할 수 있습니다.  

</details>

