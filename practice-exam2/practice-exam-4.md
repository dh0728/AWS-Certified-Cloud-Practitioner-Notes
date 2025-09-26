## Practice Exam 4 — Q4

**61. What is the benefit of using AWS managed services, such as Amazon ElastiCache and Amazon Relational Database Service (Amazon RDS)?**  
> Amazon ElastiCache와 Amazon RDS 같은 AWS 관리형 서비스를 사용할 때의 이점은 무엇입니까?

- A. They require the customer to monitor and replace failing instances.  
- B. They have better performance than customer-managed services.  
- C. They simplify patching and updating underlying OSs.  
- D. They do not require the customer to optimize instance type or size selections.  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
AWS Managed Services takes care of all of your patching and backup activities to help keep your resources current and secure. When updates or patches are released by OS vendors, AWS Managed Services applies them in a timely and consistent manner to minimize the impact on your business. Critical security patches are applied immediately, while others are applied based on the patch schedule you request. Backups of stacks are automated using Amazon Elastic Block Store (EBS) and RDS snapshots, and can be restored in the event of a failure or outage, ensuring business continuity.  

**해설:**  
AWS 관리형 서비스는 리소스를 최신 상태로 안전하게 유지하기 위해 모든 패치 및 백업 작업을 처리합니다. OS 공급업체에서 업데이트나 패치가 릴리스되면, AWS 관리형 서비스는 이를 신속하고 일관되게 적용하여 비즈니스에 미치는 영향을 최소화합니다. 중요한 보안 패치는 즉시 적용되며, 나머지는 요청한 패치 일정에 따라 적용됩니다. 또한 EBS와 RDS 스냅샷을 사용해 스택의 백업이 자동화되며, 장애나 중단 시 복구할 수 있어 비즈니스 연속성을 보장합니다.  

</details>


**62. Which service provides a virtually unlimited amount of online highly durable object storage?**  
> 사실상 무제한의 고내구성 온라인 객체 스토리지를 제공하는 서비스는 무엇입니까?

- A. Amazon Redshift  
- B. Amazon Elastic File System (Amazon EFS)  
- C. Amazon Elastic Container Service (Amazon ECS)  
- D. Amazon S3  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
Amazon S3 is object storage built to store and retrieve any amount of data from anywhere on the Internet. It’s a simple storage service that offers an extremely durable, highly available, and infinitely scalable data storage infrastructure at very low costs. The size limit applies only to individual items (5 TB), not to the total capacity of S3, which is unlimited.  

**해설:**  
Amazon S3는 인터넷 어디서든 원하는 양의 데이터를 저장하고 검색할 수 있도록 설계된 객체 스토리지입니다. 매우 낮은 비용으로 뛰어난 내구성, 높은 가용성, 사실상 무제한으로 확장 가능한 스토리지 인프라를 제공합니다. 단일 객체 크기는 5TB로 제한되지만, 전체 S3 용량에는 제한이 없습니다.  

</details>


**63. Which of the following Identity and Access Management (IAM) entities is associated with an access key ID and secret access key when using AWS Command Line Interface (AWS CLI)?**  
> AWS CLI를 사용할 때 액세스 키 ID와 비밀 액세스 키가 연결되는 IAM 엔터티는 무엇입니까?

- A. IAM group  
- B. IAM user  
- C. IAM role  
- D. IAM policy  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Access keys are long-term credentials for an IAM user or the AWS account root user. You can use access keys to sign programmatic requests to the AWS CLI or AWS API (directly or using the AWS SDK).  

**해설:**  
액세스 키는 IAM 사용자 또는 AWS 계정 루트 사용자에게 발급되는 장기 자격 증명입니다. 액세스 키를 사용하면 AWS CLI나 AWS API(직접 또는 SDK 사용)를 통해 프로그래매틱 요청에 서명할 수 있습니다.  

</details>


**64. Which of the following security-related services does AWS offer? (Choose two.)**  
> AWS가 제공하는 보안 관련 서비스는 무엇입니까? (2개 선택)

- A. Multi-factor authentication physical tokens  
- B. AWS Trusted Advisor security checks  
- C. Data encryption  
- D. Automated penetration testing  
- E. Amazon S3 copyrighted content detection  

<details><summary>Answer</summary>

**Correct:** B, C  
**Explanation:**  
- **B** — Trusted Advisor gives recommendations on performance, service quotas, cost optimization, security, and fault tolerance.  
- **C** — AWS offers you the ability to add a layer of security to your data at rest in the cloud, providing scalable and efficient encryption features.  

**해설:**  
- **B** — Trusted Advisor는 성능, 서비스 할당량, 비용 최적화, 보안, 내결함성에 대한 권장 사항을 제공합니다.  
- **C** — AWS는 클라우드 내 저장 데이터에 대해 확장 가능하고 효율적인 암호화 기능을 제공하여 추가적인 보안 계층을 구현할 수 있게 합니다.  

</details>


**65. Which AWS managed service is used to host databases?**  
> 데이터베이스를 호스팅하는 데 사용되는 AWS 관리형 서비스는 무엇입니까?

- A. AWS Batch  
- B. AWS Artifact  
- C. AWS Data Pipeline  
- D. Amazon RDS  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching, and backups. It frees you to focus on your applications so you can give them the fast performance, high availability, security, and compatibility they need.  

**해설:**  
Amazon RDS는 클라우드에서 관계형 데이터베이스를 손쉽게 설정, 운영, 확장할 수 있게 해줍니다. 하드웨어 프로비저닝, 데이터베이스 설정, 패치, 백업과 같은 시간이 많이 소요되는 관리 작업을 자동화하면서 비용 효율적이고 크기 조정 가능한 용량을 제공합니다. 이를 통해 애플리케이션 성능, 고가용성, 보안, 호환성에 집중할 수 있습니다.  

</details>

**66. Which AWS service provides a simple and scalable shared file storage solution for use with Linux-based AWS and on-premises servers?**  
> 리눅스 기반 AWS 및 온프레미스 서버에서 사용할 수 있는 단순하고 확장 가능한 공유 파일 스토리지를 제공하는 AWS 서비스는 무엇입니까?

- A. Amazon S3  
- B. Amazon Glacier  
- C. Amazon EBS  
- D. Amazon EFS  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It scales on demand to petabytes without disrupting applications, growing and shrinking automatically as files are added and removed, eliminating the need to provision and manage capacity. EFS provides the throughput, IOPS, and low latency needed for Linux workloads, and can burst to higher throughput levels when required.  

**해설:**  
Amazon EFS는 AWS 클라우드 서비스와 온프레미스 리소스에서 사용할 수 있는 단순하고 확장 가능한 관리형 NFS 파일 시스템입니다. 파일이 추가되거나 제거될 때 자동으로 확장 및 축소되며, 애플리케이션 중단 없이 페타바이트 규모로 확장할 수 있습니다. 또한 Linux 워크로드에 필요한 처리량, IOPS, 낮은 지연 시간을 제공하며, 필요 시 단기간 높은 처리량으로 버스트할 수 있습니다.  

</details>


**67. When architecting cloud applications, which of the following are a key design principle?**  
> 클라우드 애플리케이션을 설계할 때 중요한 설계 원칙은 무엇입니까?

- A. Use the largest instance possible  
- B. Provision capacity for peak load  
- C. Use the Scrum development process  
- D. Implement elasticity  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
AWS encourages elasticity rather than specifically provisioning for peak traffic. Elasticity means the ability to stop guessing about capacity and to scale resources up or down based on demand.  

**해설:**  
AWS는 최대 트래픽을 기준으로 용량을 미리 고정하는 대신, **탄력성(Elasticity)**을 구현할 것을 권장합니다. 탄력성은 수요에 따라 리소스를 자동으로 확장 또는 축소하여 용량을 추측할 필요를 없애줍니다.  

</details>


**68. Which AWS service should be used for long-term, low-cost storage of data backups?**  
> 장기적이고 저비용의 데이터 백업 저장을 위해 사용해야 하는 AWS 서비스는 무엇입니까?

- A. Amazon RDS  
- B. Amazon Glacier  
- C. AWS Snowball  
- D. Amazon EBS  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Amazon S3 Glacier is a secure, durable, and low-cost storage class of Amazon S3 designed for data archiving and long-term backup. Customers can store large or small amounts of data for as little as $0.004 per gigabyte per month. Glacier is ideal for archives where data is not frequently accessed, but some of it may be retrieved within minutes.  

**해설:**  
Amazon S3 Glacier는 데이터 아카이빙 및 장기 백업을 위해 설계된 안전하고 내구성이 뛰어난 저비용 스토리지 클래스입니다. 기가바이트당 월 $0.004 수준의 비용으로 데이터를 저장할 수 있으며, 자주 접근하지는 않지만 몇 분 내 검색이 필요한 백업 데이터에 적합합니다.  

</details>


**69. Under the shared responsibility model, which of the following is a shared control between a customer and AWS?**  
> 공유 책임 모델에서 고객과 AWS가 함께 책임지는 공유 제어 항목은 무엇입니까?

- A. Physical controls  
- B. Patch management  
- C. Zone security  
- D. Data center auditing  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Shared controls apply to both the infrastructure layer and the customer layer, but in separate contexts. In a shared control, AWS provides requirements for the infrastructure, while customers provide their own implementation within their use of AWS services. Patch management is an example of a shared control: AWS manages patches for the underlying infrastructure, while the customer is responsible for patching their guest operating systems and applications.  

**해설:**  
공유 제어는 인프라 계층과 고객 계층 모두에 적용되지만, 서로 다른 맥락에서 이루어집니다. AWS는 인프라 요구 사항을 제공하고, 고객은 자신이 사용하는 AWS 서비스 내에서 이를 구현합니다. 예를 들어, **패치 관리(Patch Management)**는 공유 제어에 해당하며, AWS는 인프라 패치를 담당하고, 고객은 게스트 운영체제 및 애플리케이션 패치를 책임집니다.  

</details>


**70. Which AWS service allows companies to connect an Amazon VPC to an on-premises data center?**  
> Amazon VPC를 온프레미스 데이터 센터와 연결할 수 있게 하는 AWS 서비스는 무엇입니까?

- A. AWS VPN  
- B. Amazon Redshift  
- C. API Gateway  
- D. Amazon Connect  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
AWS Virtual Private Network (VPN) establishes secure connections via the public internet between on-premises networks, remote offices, client devices, and the AWS global network. Companies can use VPN to connect their Amazon VPC with their data centers.  

**해설:**  
AWS VPN은 공용 인터넷을 통해 온프레미스 네트워크, 원격 사무실, 클라이언트 장치와 AWS 글로벌 네트워크 간의 보안 연결을 제공합니다. 이를 통해 기업은 Amazon VPC와 온프레미스 데이터 센터를 안전하게 연결할 수 있습니다.  

</details>

**71. A company wants to reduce the physical compute footprint that developers use to run code. Which service would meet that need by enabling serverless architectures?**  
> 한 기업이 개발자가 코드를 실행하는 데 사용하는 물리적 컴퓨팅 자원을 줄이고자 합니다. 서버리스 아키텍처를 가능하게 하여 이를 충족할 수 있는 서비스는 무엇입니까?

- A. Amazon Elastic Compute Cloud (Amazon EC2)  
- B. AWS Lambda  
- C. Amazon DynamoDB  
- D. AWS CodeCommit  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
AWS Lambda is a compute service that lets you run code without provisioning or managing servers. It runs code only when needed and scales automatically from a few requests per day to thousands per second. You only pay for compute time consumed. Lambda performs all the administration of compute resources, including OS maintenance, capacity provisioning, scaling, monitoring, and logging.  

**해설:**  
AWS Lambda는 서버를 프로비저닝하거나 관리하지 않고도 코드를 실행할 수 있는 서비스입니다. 요청이 있을 때만 실행되며, 하루 몇 건에서 초당 수천 건까지 자동으로 확장됩니다. 실행 시간에 대해서만 비용이 부과됩니다. 또한 OS 유지 관리, 용량 프로비저닝, 확장, 모니터링, 로깅 등 모든 관리 작업을 AWS가 처리합니다.  

</details>


**72. Which AWS service provides alerts when an AWS event may impact a company's AWS resources?**  
> AWS 이벤트가 기업의 리소스에 영향을 미칠 수 있을 때 알림을 제공하는 서비스는 무엇입니까?

- A. AWS Personal Health Dashboard  
- B. AWS Service Health Dashboard  
- C. AWS Trusted Advisor  
- D. AWS Infrastructure Event Management  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
AWS Personal Health Dashboard provides alerts and remediation guidance when AWS is experiencing events that may impact you. Unlike the Service Health Dashboard, which shows general service status, the Personal Health Dashboard gives you a personalized view of AWS events and how they affect your resources.  

**해설:**  
**AWS Personal Health Dashboard**는 AWS 이벤트가 특정 고객의 리소스에 영향을 줄 수 있을 때 알림과 대응 가이드를 제공합니다. Service Health Dashboard가 전체 서비스 상태를 보여주는 것과 달리, Personal Health Dashboard는 고객 환경에 맞춘 맞춤형 상태를 제공합니다.  

</details>


**73. Which of the following are categories of AWS Trusted Advisor? (Choose two.)**  
> AWS Trusted Advisor의 권장 사항이 제공되는 카테고리에는 다음 중 어떤 것들이 있습니까? (2개 선택)

- A. Fault Tolerance  
- B. Instance Usage  
- C. Infrastructure  
- D. Performance  
- E. Storage Capacity  

<details><summary>Answer</summary>

**Correct:** A, D  
**Explanation:**  
AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations in five categories: cost optimization, performance, security, fault tolerance, and service limits.  

**해설:**  
AWS Trusted Advisor는 고객의 환경을 분석하여 **비용 최적화, 성능, 보안, 장애 허용(Fault Tolerance), 서비스 한도**의 다섯 가지 카테고리에서 모범 사례 기반 권장 사항을 제공합니다.  

</details>


**74. Which task is AWS responsible for in the shared responsibility model for security and compliance?**  
> 보안 및 규정 준수를 위한 공유 책임 모델에서 AWS가 책임지는 작업은 무엇입니까?

- A. Granting access to individuals and services  
- B. Encrypting data in transit  
- C. Updating Amazon EC2 host firmware  
- D. Updating operating systems  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Host firmware is fully managed by AWS as part of the infrastructure. In the shared responsibility model, AWS is responsible for the "security of the cloud" (including host OS, virtualization layer, and physical security), while customers are responsible for "security in the cloud".  

**해설:**  
**EC2 호스트 펌웨어 업데이트**는 AWS의 책임입니다. 공유 책임 모델에서 AWS는 **클라우드의 보안(Security of the Cloud)**, 즉 호스트 OS, 가상화 계층, 물리적 보안을 관리합니다. 고객은 **클라우드 내 보안(Security in the Cloud)**을 담당합니다.  

</details>


**75. Where should a company go to search software listings from independent software vendors to find, test, buy and deploy software that runs on AWS?**  
> 기업이 AWS에서 실행되는 소프트웨어를 찾아보고, 테스트하고, 구매 및 배포하기 위해 독립 소프트웨어 벤더(ISV)의 소프트웨어 목록을 검색할 수 있는 곳은 어디입니까?

- A. AWS Marketplace  
- B. Amazon Lumberyard  
- C. AWS Artifact  
- D. Amazon CloudSearch  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
AWS Marketplace is an online software store that helps customers find, buy, and immediately use software and services running on AWS. It is designed for ISVs, VARs, and SIs who want to sell software products to AWS customers.  

**해설:**  
**AWS Marketplace**는 고객이 AWS에서 실행되는 소프트웨어와 서비스를 찾아보고, 구매하고, 즉시 사용할 수 있도록 지원하는 온라인 스토어입니다. 독립 소프트웨어 벤더(ISV), 부가가치 재판매업체(VAR), 시스템 통합업체(SI)가 자신들의 소프트웨어를 고객에게 제공할 수 있도록 설계되었습니다.  

</details>

**76. Which of the following is a benefit of using the AWS Cloud?**  
> AWS 클라우드를 사용할 때 얻을 수 있는 이점은 무엇입니까?

- A. Permissive security removes the administrative burden.  
- B. Ability to focus on revenue-generating activities.  
- C. Control over cloud network hardware.  
- D. Choice of specific cloud hardware vendors.  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
AWS handles the heavy lifting of data center operations like racking, stacking, and powering servers. It also removes the burden of managing OSs and applications with managed services. This allows you to focus on customers and business projects rather than IT infrastructure.  

**해설:**  
AWS는 서버 랙 설치, 전원 관리 등 데이터센터 운영을 대신 처리하며, 운영체제와 애플리케이션 관리를 관리형 서비스로 제공하여 부담을 줄여줍니다. 따라서 기업은 **IT 인프라 관리가 아닌 고객 및 비즈니스 활동**에 집중할 수 있습니다.  

</details>


**77. When performing a cost analysis that supports physical isolation of a customer workload, which compute hosting model should be accounted for in the Total Cost of Ownership (TCO)?**  
> 고객 워크로드의 물리적 격리를 지원하는 비용 분석을 수행할 때, 총소유비용(TCO)에 포함해야 할 컴퓨팅 호스팅 모델은 무엇입니까?

- A. Dedicated Hosts  
- B. Reserved Instances  
- C. On-Demand Instances  
- D. No Upfront Reserved Instances  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
Dedicated Hosts allow you to launch EC2 instances on physical servers that are dedicated to you. They provide visibility and control over instance placement, enable the reuse of server-bound software licenses, and address compliance and regulatory requirements.  

**해설:**  
**Dedicated Hosts**는 고객 전용 물리 서버에서 EC2 인스턴스를 실행할 수 있도록 하며, 인스턴스 배치에 대한 가시성과 제어를 제공합니다. 또한 서버 종속 소프트웨어 라이선스를 재사용할 수 있고, 규정 준수 및 보안 요구사항을 충족할 수 있습니다.  

</details>


**78. Which AWS service provides the ability to manage infrastructure as code?**  
> 인프라를 코드로 관리할 수 있는 기능을 제공하는 AWS 서비스는 무엇입니까?

- A. AWS CodePipeline  
- B. AWS CodeDeploy  
- C. AWS Direct Connect  
- D. AWS CloudFormation  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
AWS CloudFormation provides a common language to describe and provision infrastructure resources. Using a simple text file, you can model and provision all needed resources across regions and accounts in an automated and secure way. The file serves as the single source of truth for your cloud environment.  

**해설:**  
**AWS CloudFormation**은 인프라 리소스를 코드로 정의하고 프로비저닝할 수 있는 서비스입니다. 단순한 텍스트 파일을 통해 여러 리전과 계정에 걸쳐 자동화되고 안전하게 리소스를 배포할 수 있으며, 이 파일은 클라우드 환경의 **단일 진실 원본(single source of truth)** 역할을 합니다.  

</details>


**79. If a customer needs to audit the change management of AWS resources, which of the following AWS services should the customer use?**  
> 고객이 AWS 리소스의 변경 관리(Change Management)를 감사하려 할 때 사용해야 하는 서비스는 무엇입니까?

- A. AWS Config  
- B. AWS Trusted Advisor  
- C. Amazon CloudWatch  
- D. Amazon Inspector  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
AWS Config enables you to assess, audit, and evaluate the configurations of AWS resources. It continuously monitors and records resource configurations and allows you to automate compliance checks. Config provides detailed histories of configuration changes, resource relationships, and compliance status, simplifying audits, security analysis, and troubleshooting.  

**해설:**  
**AWS Config**는 리소스 구성을 평가, 감사, 검증할 수 있는 서비스입니다. 리소스 구성을 지속적으로 모니터링하고 기록하며, 원하는 정책과 비교하여 자동으로 규정 준수를 검사할 수 있습니다. 또한 변경 내역과 리소스 간 관계를 추적할 수 있어 **감사, 보안 분석, 문제 해결**을 단순화합니다.  

</details>


**80. What is Amazon CloudWatch?**  
> Amazon CloudWatch는 무엇입니까?

- A. A code repository with customizable build and team commit features.  
- B. A metrics repository with customizable notification thresholds and channels.  
- C. A security configuration repository with threat analytics.  
- D. A rule repository of a web application firewall with automated vulnerability prevention features.  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Amazon CloudWatch is a monitoring and observability service. It provides data and insights to monitor applications, respond to performance changes, optimize resources, and get a unified view of operational health.  

**해설:**  
**Amazon CloudWatch**는 모니터링 및 가시성(observability) 서비스입니다. 애플리케이션을 모니터링하고 성능 변화를 감지하며, 리소스 사용 최적화와 운영 상태에 대한 통합된 뷰를 제공합니다.  

</details>
