## Practice Exam 2 — Q2

**21. A characteristic of edge locations is that they:**

> 엣지 로케이션(edge location)의 특징은 무엇입니까?

- A. host Amazon EC2 instances closer to users.  
- B. help lower latency and improve performance for users.  
- C. cache frequently changing data without reaching the origin server.  
- D. refresh data changes daily.  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Edge locations help to improve performance for your users while lowering the operational burden and cost of scaling your origin resources.  
Edge Locations are endpoints used for caching content. They are located in most of the major cities around the world and are specifically used by CloudFront to distribute AWS content closer to end-users to reduce latency.  

**해설:**  
엣지 로케이션은 사용자 성능을 향상시키면서 원본 리소스의 확장에 따른 운영 부담과 비용을 줄여줍니다.  
엣지 로케이션은 콘텐츠 캐싱을 위한 엔드포인트로, 전 세계 주요 도시에 위치하며 CloudFront에서 사용되어 AWS 콘텐츠를 최종 사용자에게 더 가까이 배포하여 지연 시간을 줄이는 데 사용됩니다.

</details>


**22. Which of the following can limit Amazon Storage Service (Amazon S3) bucket access to specific users?**

> 다음 중 특정 사용자에게 Amazon S3 버킷 접근을 제한할 수 있는 것은 무엇입니까?

- A. A public and private key-pair  
- B. Amazon Inspector  
- C. AWS Identity and Access Management (IAM) policies  
- D. Security Groups  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
You manage access in AWS by creating policies and attaching them to IAM identities (users, groups of users, or roles) or AWS resources.  
A policy is an object in AWS that, when associated with an identity or resource, defines their permissions. AWS evaluates these policies when an IAM principal (user or role) makes a request.  
Permissions in the policies determine whether the request is allowed or denied. Most policies are stored in AWS as JSON documents.  

**해설:**  
AWS에서 접근 관리는 정책을 생성하고 이를 IAM 아이덴티티(사용자, 사용자 그룹, 역할) 또는 AWS 리소스에 연결함으로써 수행됩니다.  
정책은 AWS에서 객체이며, 아이덴티티나 리소스와 연결되면 권한을 정의합니다. AWS는 IAM 주체(사용자 또는 역할)가 요청을 할 때 이러한 정책을 평가합니다.  
정책에 정의된 권한은 요청이 허용될지 거부될지를 결정합니다. 대부분의 정책은 AWS에 JSON 문서로 저장됩니다.

</details>


**23. Which of the following security-related actions are available at no cost?**

> 다음 중 무료로 제공되는 보안 관련 작업은 무엇입니까?

- A. Calling AWS Support  
- B. Contacting AWS Professional Services to request a workshop  
- C. Accessing forums, blogs, and whitepapers  
- D. Attending AWS classes at a local university  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Free Basic support provides:  
- Customer Service and Communities: 24x7 access to customer service, documentation, whitepapers, and support forums.  
- AWS Trusted Advisor: Access to the <span style="color:red">🔴 7 core</span> Trusted Advisor checks and guidance to provision resources following best practices to increase performance and improve security.  
- AWS Personal Health Dashboard.  

**해설:**  
무료 기본 지원은 다음을 제공합니다:  
- 고객 서비스 및 커뮤니티: 연중무휴 고객 서비스, 문서, 백서, 지원 포럼 접근.  
- AWS Trusted Advisor: <span style="color:red">🔴 7가지 핵심</span> Trusted Advisor 점검 및 모범 사례에 따라 리소스를 프로비저닝하기 위한 가이드 제공으로 성능 향상과 보안 개선.  
- AWS Personal Health Dashboard.  

<span style="color:red">🔴 주의:</span> Trusted Advisor에서 무료로 제공되는 **“핵심(코어) 점검의 개수(예: 7개)**는 시점/계정 유형에 따라 정책이 변경된 이력이 있어 정확한 숫자는 달라질 수 있습니다. 복사본에 숫자를 고정하기보다 **“코어 점검(일부 점검)”**처럼 서술하는 것을 권장합니다.

</details>


**24. Which of the Reserved Instance (RI) pricing models can change the attributes of the RI as long as the exchange results in the creation of RIs of equal or greater value?**

> 동일하거나 더 큰 가치의 RI가 생성되는 교환이라면, RI 속성을 변경할 수 있는 예약 인스턴스(RI) 요금 모델은 무엇입니까?

- A. Dedicated RIs  
- B. Scheduled RIs  
- C. Convertible RIs  
- D. Standard RIs  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Convertible RIs provide a discount and the capability to change the attributes of the RI as long as the exchange results in the creation of Reserved Instances of equal or greater value. Like Standard RIs, Convertible RIs are best suited for steady-state usage.  

**해설:**  
변환형 RI(Convertible RI)는 할인을 제공하며, 동일하거나 더 큰 가치의 예약 인스턴스를 생성하는 교환이라면 RI 속성을 변경할 수 있는 기능을 제공합니다. 표준 RI와 마찬가지로, 변환형 RI는 안정적인 사용(steady-state)에 가장 적합합니다.

</details>


**25. Which AWS feature will reduce the customer's total cost of ownership (TCO)?**

> 고객의 총 소유 비용(TCO)을 줄여주는 AWS 기능은 무엇입니까?

- A. Shared responsibility security model  
- B. Single tenancy  
- C. Elastic computing  
- D. Encryption  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
In cloud computing, elasticity is defined as "the degree to which a system is able to adapt to workload changes by provisioning and de-provisioning resources in an autonomic manner, such that at each point in time the available resources match the current demand as closely as possible."  
Some cloud solutions can also be automatically adjusted to meet these needs. This means you can set them up to scale up or down automatically based on certain conditions.  

**해설:**  
클라우드 컴퓨팅에서 탄력성(elasticity)은 “시스템이 리소스를 자동으로 프로비저닝 및 해제하여 워크로드 변화에 적응하는 정도로, 어느 시점에서든 가용 리소스가 현재 수요와 최대한 일치하도록 하는 것”으로 정의됩니다.  
일부 클라우드 솔루션은 이러한 필요를 충족하기 위해 자동으로 조정될 수도 있습니다. 이는 특정 조건에 따라 자동으로 확장 또는 축소되도록 설정할 수 있음을 의미합니다.

</details>

**26. Which of the following services will automatically scale with an expected increase in web traffic?**

> 예상되는 웹 트래픽 증가에 따라 자동으로 확장되는 서비스는 무엇입니까?

- A. AWS CodePipeline  
- B. Elastic Load Balancing  
- C. Amazon EBS  
- D. AWS Direct Connect  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, Lambda functions, and virtual appliances. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones. Elastic Load Balancing offers four types of load balancers that all feature the high availability, automatic scaling, and robust security necessary to make your applications fault tolerant.  
Incorrect answers:  
- A & C: have nothing to do with web traffic.  
- D: Direct Connect is a network connection, which is about enabling private network traffic between AWS and an on-premises location.  

**해설:**  
Elastic Load Balancing은 들어오는 애플리케이션 트래픽을 Amazon EC2 인스턴스, 컨테이너, IP 주소, Lambda 함수, 가상 어플라이언스 등 여러 대상에 자동으로 분산합니다. 이는 단일 가용 영역 또는 여러 가용 영역에서 애플리케이션 트래픽의 변화하는 부하를 처리할 수 있습니다. Elastic Load Balancing은 높은 가용성, 자동 확장, 강력한 보안을 제공하는 네 가지 유형의 로드 밸런서를 지원하여 애플리케이션을 장애 허용(fault tolerant)하도록 만듭니다.  
오답:  
- A와 C는 웹 트래픽과 관련이 없습니다.  
- D는 네트워크 연결로, AWS와 온프레미스 위치 간의 전용 네트워크 트래픽을 가능하게 하는 서비스입니다.

</details>


**27. Where are AWS compliance documents, such as an SOC 1 report, located?**

> SOC 1 보고서와 같은 AWS 규정 준수 문서는 어디에서 찾을 수 있습니까?

- A. Amazon Inspector  
- B. AWS CloudTrail  
- C. AWS Artifact  
- D. AWS Certificate Manager  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
AWS Artifact is your central resource for compliance-related information. It provides on-demand access to AWS security and compliance reports and select online agreements. Reports available in AWS Artifact include Service Organization Control (SOC) reports, Payment Card Industry (PCI) reports, and certifications from accreditation bodies across geographies and compliance verticals that validate the implementation and operating effectiveness of AWS security controls. Agreements available in AWS Artifact include the Business Associate Addendum (BAA) and the Nondisclosure Agreement (NDA).  

**해설:**  
AWS Artifact는 규정 준수 관련 정보를 위한 중앙 리소스입니다. AWS 보안 및 규정 준수 보고서와 일부 온라인 계약에 대한 온디맨드 접근을 제공합니다. Artifact에서 제공되는 보고서에는 SOC 보고서, PCI 보고서, AWS 보안 제어의 구현 및 운영 효과성을 검증하는 다양한 지역 및 규제 기관의 인증이 포함됩니다. Artifact에서 제공되는 계약에는 비즈니스 협력 계약(BAA)과 비밀유지계약(NDA)이 있습니다.

</details>


**28. Under the AWS shared responsibility model, which of the following activities are the customer's responsibility? (Choose two)**

> AWS 공유 책임 모델에서 고객의 책임에 해당하는 활동은 무엇입니까? (2개 선택)

- A. Patching operating system components for Amazon Relational Database Service (Amazon RDS)  
- B. Encrypting data on the client-side  
- C. Training the data center staff  
- D. Configuring Network Access Control Lists (ACL)  
- E. Maintaining environmental controls within a data center  

<details><summary>Answer</summary>

**Correct:** B, D  
**Explanation:**  
- B: Data configuration is the responsibility of the customer (e.g., encrypting data at rest and in transit).  
- D: A network access control list (ACL) is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets.  

**해설:**  
- B: 데이터 구성은 고객의 책임이며, 여기에는 정지 상태 및 전송 중 데이터 암호화가 포함됩니다.  
- D: 네트워크 ACL은 VPC의 선택적 보안 계층으로, 하나 이상의 서브넷으로 들어오고 나가는 트래픽을 제어하는 방화벽 역할을 합니다.

</details>


**29. Which is a recommended pattern for designing a highly available architecture on AWS?**

> AWS에서 고가용성 아키텍처를 설계할 때 권장되는 패턴은 무엇입니까?

- A. Ensure that components have low-latency network connectivity.  
- B. Run enough Amazon EC2 instances to operate at peak load.  
- C. Ensure that the application is designed to accommodate failure of any single component.  
- D. Use a monolithic application that handles all operations.  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Highly available systems are reliable in the sense that they continue operating even when critical components fail. They are also resilient, meaning that they are able to handle failure without service disruption or data loss, and seamlessly recover from such failure.  

**해설:**  
고가용성 시스템은 중요한 구성 요소가 실패하더라도 계속 운영될 수 있다는 점에서 신뢰성이 있습니다. 또한 탄력성이 있어 서비스 중단이나 데이터 손실 없이 장애를 처리하고, 그러한 장애로부터 원활하게 복구할 수 있습니다.

</details>


**30. According to best practices, how should an application be designed to run in the AWS Cloud?**

> 모범 사례에 따르면, 애플리케이션은 AWS 클라우드에서 실행되도록 어떻게 설계해야 합니까?

- A. Use tightly coupled components.  
- B. Use loosely coupled components.  
- C. Use infrequently coupled components.  
- D. Use frequently coupled components.  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Loose coupling: As application complexity increases, a desirable attribute of an IT system is that it can be broken into smaller, loosely coupled components. This means that IT systems should be designed in a way that reduces interdependencies—a change or a failure in one component should not cascade to other components.  

**해설:**  
느슨한 결합(loose coupling): 애플리케이션 복잡성이 증가함에 따라, IT 시스템을 더 작은 느슨하게 결합된 컴포넌트로 분할할 수 있는 것이 바람직한 특성입니다. 이는 IT 시스템이 상호 의존성을 줄이는 방식으로 설계되어야 함을 의미하며, 한 컴포넌트에서의 변경이나 실패가 다른 컴포넌트로 연쇄적으로 영향을 미치지 않도록 해야 합니다.

</details>


**31. AWS supports which of the following methods to add security to Identity and Access Management (IAM) users? (Choose two)**

> AWS는 IAM 사용자 보안을 강화하기 위해 다음 중 어떤 방법을 지원합니까? (2개 선택)

- A. Implementing Amazon Rekognition  
- B. Using AWS Shield-protected resources  
- C. Blocking access with Security Groups  
- D. Using Multi-Factor Authentication (MFA)  
- E. Enforcing password strength and expiration  

<details><summary>Answer</summary>

**Correct:** D, E  
**Explanation:**  
IAM Best Practices – To help secure your AWS resources, follow these recommendations for the AWS Identity and Access Management (IAM) service:  
- Lock away your AWS account root user access keys  
- Create individual IAM users  
- Use groups to assign permissions to IAM users  
- Grant least privilege  
- Get started using permissions with AWS managed policies  
- Use customer managed policies instead of inline policies  
- Use access levels to review IAM permissions  
- Configure a strong password policy for your users  
- Enable MFA (these are not typically physical tokens)  
- Use roles for applications that run on Amazon EC2 instances  
- Use roles to delegate permissions  
- Do not share access keys  
- Rotate credentials regularly  
- Remove unnecessary credentials  
- Use policy conditions for extra security  
- Monitor activity in your AWS account  

**해설:**  
IAM 모범 사례 – AWS 리소스를 안전하게 보호하기 위해 다음 권장 사항을 따르는 것이 좋습니다:  
- AWS 계정 루트 사용자 액세스 키를 안전하게 보관  
- 개별 IAM 사용자 생성  
- 그룹을 사용하여 IAM 사용자에게 권한 부여  
- 최소 권한 원칙 적용  
- AWS 관리형 정책을 활용해 권한 시작  
- 인라인 정책 대신 고객 관리형 정책 사용  
- IAM 권한 검토를 위해 액세스 수준 사용  
- 사용자에 대해 강력한 암호 정책 구성  
- MFA 활성화(물리적 토큰일 필요는 없음)  
- Amazon EC2 인스턴스에서 실행되는 애플리케이션에는 역할 사용  
- 권한 위임을 위해 역할 사용  
- 액세스 키 공유 금지  
- 자격 증명 정기적으로 교체  
- 불필요한 자격 증명 제거  
- 추가 보안을 위해 정책 조건 사용  
- AWS 계정 내 활동 모니터링  

</details>


**32. Which AWS services should be used for read/write of constantly changing data? (Choose two)**

> 지속적으로 변경되는 데이터를 읽고 쓰기 위해 사용해야 하는 AWS 서비스는 무엇입니까? (2개 선택)

- A. Amazon Glacier  
- B. Amazon RDS  
- C. AWS Snowball  
- D. Amazon Redshift  
- E. Amazon EFS  

<details><summary>Answer</summary>

**Correct:** B, E  
**Explanation:**  
Data that must be updated very frequently might be best served by a storage solution with lower read/write latencies, such as Amazon EBS, Amazon RDS, Amazon EFS, Amazon DynamoDB, or relational databases running on Amazon EC2.  
- RDS is a managed service for relational databases like MySQL and MariaDB. Simple and fast to set up and scale.  
- EFS provides a managed network file system that scales automatically as files are added or removed.  

**해설:**  
매우 자주 업데이트되어야 하는 데이터는 Amazon EBS, Amazon RDS, Amazon EFS, Amazon DynamoDB 또는 EC2에서 실행되는 관계형 데이터베이스와 같이 낮은 읽기/쓰기 지연을 가진 스토리지 솔루션이 가장 적합합니다.  
- RDS는 MySQL 및 MariaDB 같은 관계형 데이터베이스를 위한 관리형 서비스로, 설정 및 확장이 간단하고 빠릅니다.  
- EFS는 파일이 추가되거나 삭제될 때 자동으로 확장되는 관리형 네트워크 파일 시스템을 제공합니다.  

</details>


**33. What is one of the advantages of the Amazon Relational Database Service (Amazon RDS)? (Choose three)**

> Amazon RDS의 장점 중 하나는 무엇입니까? (3개 선택)

- A. It simplifies relational database administration tasks.  
- B. It provides 99.99999999999% reliability and durability.  
- C. It automatically scales databases for loads.  
- D. It enables users to dynamically adjust CPU and RAM resources.  

<details><summary>Answer</summary>

**Correct:** A, C, D  
**Explanation:**  
- A: RDS makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks, such as hardware provisioning, database setup, patching, and backups.  
- C: Amazon RDS supports Storage Auto Scaling.  
- D: You can scale the compute and memory resources powering your deployment up or down.  

<span style="color:red">🔴 B: 잘못된 보기 – 11 9’s (99.99999999999%) 내구성은 Amazon S3의 특성입니다. RDS는 해당 수치를 보장하지 않습니다.</span>  

**해설:**  
- A: RDS는 클라우드에서 관계형 데이터베이스를 손쉽게 설정, 운영 및 확장할 수 있습니다. 하드웨어 프로비저닝, 데이터베이스 설정, 패치, 백업과 같은 시간 소모적인 관리 작업을 자동화하면서 비용 효율적이고 조정 가능한 용량을 제공합니다.  
- C: Amazon RDS는 스토리지 자동 확장을 지원합니다.  
- D: 배포를 지원하는 컴퓨팅 및 메모리 리소스를 상향 또는 하향으로 조정할 수 있습니다.  

<span style="color:red">🔴 B: 오답 – 11 9’s(99.99999999999%) 내구성은 Amazon S3의 특성입니다.</span>  

</details>


**34. A customer needs to run a MySQL database that easily scales. Which AWS service should they use?**

> 손쉽게 확장 가능한 MySQL 데이터베이스를 실행해야 하는 고객이 사용할 AWS 서비스는 무엇입니까?

- A. Amazon Aurora  
- B. Amazon Redshift  
- C. Amazon DynamoDB  
- D. Amazon ElastiCache  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
Amazon Aurora supports MySQL and will automatically grow the size of your database volume as your database storage needs grow, up to a maximum of 64 TB or a maximum you define.  

**해설:**  
Amazon Aurora는 MySQL을 지원하며, 데이터베이스 스토리지 요구가 증가함에 따라 최대 64TB(또는 사용자가 정의한 한도)까지 자동으로 데이터베이스 볼륨 크기를 확장합니다.  

</details>


**35. Which of the following components of the AWS Global Infrastructure consists of one or more discrete data centers interconnected through low latency links?**

> AWS 글로벌 인프라의 구성 요소 중 저지연 링크로 상호 연결된 하나 이상의 개별 데이터 센터로 구성된 것은 무엇입니까?

- A. Availability Zone  
- B. Edge location  
- C. Region  
- D. Private networking  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
An Availability Zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity in an AWS Region.  

**해설:**  
가용 영역(Availability Zone, AZ)은 AWS 리전에 있는 하나 이상의 개별 데이터 센터로 구성되며, 전력, 네트워킹, 연결성이 중복으로 제공됩니다.  

</details>


**36. Which of the following is a shared control between the customer and AWS?**

> 다음 중 고객과 AWS 간의 공유 책임에 해당하는 것은 무엇입니까?

- A. Providing a key for Amazon S3 client-side encryption  
- B. Configuration of an Amazon EC2 instance  
- C. Environmental controls of physical AWS data centers  
- D. Awareness and training  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
AWS trains AWS employees, but a customer must train their own employees.  

**해설:**  
AWS는 자사 직원들을 교육하지만, 고객은 자신의 직원을 교육해야 합니다.  

</details>


**37. How many Availability Zones should compute resources be provisioned across to achieve high availability?**

> 고가용성을 달성하기 위해 컴퓨팅 리소스는 몇 개의 가용 영역에 걸쳐 프로비저닝되어야 합니까?

- A. A minimum of one  
- B. A minimum of two  
- C. A minimum of three  
- D. A minimum of four or more  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Most providers of real-time communications align with service levels that provide availability from 99.9% to 99.999%. Depending on the degree of high availability (HA) that you want, you must take increasingly sophisticated measures along the full lifecycle of the application.  
We recommend following these guidelines to achieve a robust degree of high availability:  
- Design the system to have no single point of failure. Use automated monitoring, failure detection, and failover mechanisms for both stateless and stateful components.  
- Single points of failure (SPOF) are commonly eliminated with an N+1 or 2N redundancy configuration, where N+1 is achieved via load balancing among active–active nodes, and 2N is achieved by a pair of nodes in active–standby configuration.  
- AWS has several methods for achieving HA through both approaches, such as through a scalable, load balanced cluster or assuming an active–standby pair.  
- Correctly instrument and test system availability.  
- Prepare operating procedures for manual mechanisms to respond to, mitigate, and recover from the failure.  

**해설:**  
대부분의 실시간 통신 제공자는 99.9%에서 99.999%의 가용성을 제공하는 SLA(Service Level Agreement)에 맞춥니다. 원하는 고가용성 수준에 따라 애플리케이션 전체 수명 주기에서 점점 더 정교한 조치를 취해야 합니다.  
권장 지침은 다음과 같습니다:  
- 단일 장애 지점(SPOF)이 없도록 시스템 설계, 무상태·유상태 컴포넌트 모두에 대해 자동화된 모니터링, 장애 감지, 장애 조치 메커니즘 사용  
- SPOF는 일반적으로 N+1 또는 2N 중복 구성으로 제거되며, N+1은 활성 노드 간 로드 밸런싱을 통해, 2N은 활성-대기(active–standby) 쌍으로 달성  
- AWS는 확장 가능한 로드 밸런싱 클러스터나 활성-대기 쌍을 통한 여러 HA 방법 제공  
- 시스템 가용성을 올바르게 계측하고 테스트  
- 장애에 대응, 완화, 복구하기 위한 운영 절차 준비  

</details>


**38. One of the advantages to moving infrastructure from an on-premises data center to the AWS Cloud is:**

> 온프레미스 데이터 센터에서 AWS 클라우드로 인프라를 이전하는 장점 중 하나는 무엇입니까?

- A. it allows the business to eliminate IT bills.  
- B. it allows the business to put a server in each customer's data center.  
- C. it allows the business to focus on business activities.  
- D. it allows the business to leave servers unpatched.  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Stop spending money running and maintaining data centers – Focus on projects that differentiate your business, not the infrastructure. Cloud computing lets you focus on your own customers, rather than on the heavy lifting of racking, stacking, and powering servers.  

**해설:**  
데이터 센터 운영과 유지 관리에 비용을 쓰지 않고, 비즈니스를 차별화하는 프로젝트에 집중할 수 있습니다. 클라우드 컴퓨팅은 서버 설치·전원 관리와 같은 무거운 작업 대신, 고객에게 집중할 수 있도록 합니다.  

</details>


**39. What is the lowest-cost, durable storage option for retaining database backups for immediate retrieval?**

> 즉시 검색을 위해 데이터베이스 백업을 보관하는 데 있어 가장 저렴하면서도 내구성이 뛰어난 스토리지 옵션은 무엇입니까?

- A. Amazon S3  
- B. Amazon Glacier  
- C. Amazon EBS  
- D. Amazon EC2 Instance Store  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
Amazon Simple Storage Service (Amazon S3) provides developers and IT teams secure, durable, highly scalable object storage at a very low cost. You can store and retrieve any amount of data, at any time, from anywhere on the web through a simple web service interface. You can write, read, and delete objects containing from zero to 5 TB of data. Amazon S3 is highly scalable, allowing concurrent read or write access to data by many separate clients or application threads.  

**해설:**  
Amazon S3는 개발자와 IT 팀에게 보안성, 내구성, 확장성이 뛰어난 객체 스토리지를 매우 저렴한 비용으로 제공합니다. 단순한 웹 서비스 인터페이스를 통해 언제 어디서나 원하는 양의 데이터를 저장하고 검색할 수 있습니다. 0바이트에서 5TB까지의 객체를 쓰기, 읽기, 삭제할 수 있습니다. Amazon S3는 매우 확장 가능하여 다수의 클라이언트나 애플리케이션 스레드가 동시에 데이터에 접근할 수 있습니다.  

</details>


**40. Which AWS IAM feature allows developers to access AWS services through the AWS CLI?**

> AWS IAM 기능 중 개발자가 AWS CLI를 통해 AWS 서비스에 접근할 수 있도록 하는 것은 무엇입니까?

- A. API keys  
- B. Access keys  
- C. User names/Passwords  
- D. SSH keys  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
IAM users can be assigned an access key ID and secret access key for programmatic access to the AWS API (Application Programming Interface), CLI (Command Line Interface), SDK (Software Development Kit), and other development tools.  
Access keys consist of an access key ID and secret access key, which are used to sign programmatic requests that you make to AWS. If you don't have access keys, you can create them from the AWS Management Console.  

**해설:**  
IAM 사용자는 프로그래밍 방식으로 AWS API, CLI, SDK 및 기타 개발 도구에 접근하기 위해 액세스 키 ID와 비밀 액세스 키를 부여받을 수 있습니다.  
액세스 키는 액세스 키 ID와 비밀 액세스 키로 구성되며, 사용자가 AWS에 보내는 프로그래밍 요청을 서명하는 데 사용됩니다. 액세스 키가 없다면 AWS Management Console에서 생성할 수 있습니다.  

</details>
