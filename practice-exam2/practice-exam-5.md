## Practice Exam 5 — Q5

**81. Which service allows a company with multiple AWS accounts to combine its usage to obtain volume discounts?**  
> 여러 AWS 계정을 보유한 기업이 사용량을 결합하여 볼륨 할인을 받을 수 있도록 하는 서비스는 무엇입니까?

- A. AWS Server Migration Service  
- B. AWS Organizations  
- C. AWS Budgets  
- D. AWS Trusted Advisor  
- E. Amazon QuickSight  
- F. Amazon Forecast  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
AWS Organizations allows companies to consolidate billing and payments across multiple accounts. Consolidated billing provides one bill, easier cost tracking, and the ability to combine usage across accounts to receive volume pricing and Reserved Instance discounts.  

**해설:**  
**AWS Organizations**는 여러 계정을 하나로 통합 청구할 수 있게 하며, 한 장의 청구서, 손쉬운 비용 추적, 계정 전체 사용량 결합을 통한 **볼륨 및 예약 인스턴스 할인** 혜택을 제공합니다.  

</details>


**82. Which of the following services could be used to deploy an application to servers running on-premises? (Choose two)**  
> 온프레미스 서버에 애플리케이션을 배포하는 데 사용할 수 있는 서비스는 무엇입니까? (2개 선택)

- A. AWS Elastic Beanstalk  
- B. AWS OpsWorks  
- C. AWS CodeDeploy  
- D. AWS Batch  
- E. AWS X-Ray  

<details><summary>Answer</summary>

**Correct:** B, C  
**Explanation:**  
- **AWS OpsWorks**: lets you use Chef and Puppet to automate how servers are configured, deployed, and managed across both EC2 and on-premises servers.  
- **AWS CodeDeploy**: automates software deployments to EC2, Lambda, Fargate, and on-premises servers.  

**해설:**  
- **AWS OpsWorks**: Chef와 Puppet을 사용하여 EC2와 온프레미스 서버 전반에서 서버의 구성, 배포, 관리를 자동화할 수 있습니다.  
- **AWS CodeDeploy**: EC2, Lambda, Fargate뿐만 아니라 **온프레미스 서버에도 소프트웨어 배포를 자동화**합니다.  

</details>


**83. Which Amazon EC2 pricing model adjusts based on supply and demand of EC2 instances?**  
> EC2 인스턴스의 수요와 공급에 따라 가격이 변동되는 Amazon EC2 요금제는 무엇입니까?

- A. On-Demand Instances  
- B. Reserved Instances  
- C. Spot Instances  
- D. Convertible Reserved Instances  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Spot Instances let you pay the Spot price in effect while instances run. Prices adjust gradually based on long-term supply and demand trends. Spot Instances provide discounts of up to 90% compared to On-Demand pricing.  

**해설:**  
**Spot 인스턴스**는 수요·공급 상황에 따라 가격이 조정되며, 실행되는 동안 해당 시점의 스팟 가격을 지불합니다. 온디맨드 대비 최대 **90% 저렴한 비용**으로 사용할 수 있습니다.  

</details>


**84. Which design principles for cloud architecture are recommended when re-architecting a large monolithic application? (Choose two)**  
> 대규모 모놀리식 애플리케이션을 재설계할 때 권장되는 클라우드 아키텍처 설계 원칙은 무엇입니까? (2개 선택)

- A. Use manual monitoring  
- B. Use fixed servers  
- C. Implement loose coupling  
- D. Rely on individual components  
- E. Design for scalability  

<details><summary>Answer</summary>

**Correct:** C, E  
**Explanation:**  
Cloud-native design emphasizes building scalable apps in dynamic environments using techniques like containers, microservices, and declarative APIs. These enable loosely coupled, resilient, and observable systems. Scalability ensures systems can handle growth efficiently.  

**해설:**  
클라우드 네이티브 설계는 컨테이너, 마이크로서비스, 선언적 API 등을 활용하여 **확장 가능하고 동적으로 운영 가능한 애플리케이션**을 구축하는 것을 강조합니다. 이를 통해 **느슨한 결합(loose coupling)**을 구현하여 탄력적이고 관리 가능한 시스템을 만들 수 있으며, **확장성(Scalability)**을 통해 증가하는 수요에도 효율적으로 대응할 수 있습니다.  

</details>


**85. Which is the MINIMUM AWS Support plan that allows for one-hour target response time for support cases?**  
> 지원 케이스에서 **1시간 응답 시간**을 보장하는 최소 AWS 지원 플랜은 무엇입니까?

- A. Enterprise  
- B. Business  
- C. Developer  
- D. Basic  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
The Business Support plan provides a 1-hour response time for urgent support cases. Enterprise Support reduces this further to 15 minutes. Developer Support has a 12-hour response time, while Basic Support offers only community and documentation access.  

**해설:**  
**Business Support** 플랜은 긴급 지원 케이스에 대해 **최대 1시간 응답 시간**을 제공합니다. Enterprise Support는 15분까지 단축되며, Developer Support는 12시간, Basic Support는 커뮤니티 및 문서 지원만 제공합니다.  

</details>

**86. Where can AWS compliance and certification reports be downloaded?**  
> AWS 컴플라이언스 및 인증 보고서를 다운로드할 수 있는 곳은 어디입니까?

- A. AWS Artifact  
- B. AWS Concierge  
- C. AWS Certificate Manager  
- D. AWS Trusted Advisor  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
AWS Artifact is the central resource for compliance-related information. It provides on-demand access to AWS security and compliance reports and certain online agreements.  

**해설:**  
**AWS Artifact**는 AWS의 보안 및 규정 준수 보고서, 특정 온라인 계약에 **온디맨드 방식으로 접근할 수 있는 중앙 리소스**입니다.  

</details>


**87. Which AWS service provides a customized view of the health of specific AWS services that power a customer's workloads running on AWS?**  
> 고객의 워크로드를 실행하는 특정 AWS 서비스의 상태를 맞춤형으로 보여주는 AWS 서비스는 무엇입니까?

- A. AWS Service Health Dashboard  
- B. AWS X-Ray  
- C. AWS Personal Health Dashboard  
- D. Amazon CloudWatch  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
The Service Health Dashboard shows general AWS service status. The Personal Health Dashboard provides a **personalized view** of the health and availability of AWS services affecting your resources, including alerts and remediation guidance.  

**해설:**  
**AWS Personal Health Dashboard**는 사용자의 AWS 리소스에 영향을 주는 서비스의 **맞춤형 상태 뷰**를 제공합니다. 일반 현황만 제공하는 Service Health Dashboard와 달리, **알림과 해결 방법 가이드**까지 포함합니다.  

</details>


**88. Which of the following is an advantage of consolidated billing on AWS?**  
> AWS에서 통합 청구(Consolidated Billing)의 장점은 무엇입니까?

- A. Volume pricing qualification  
- B. Shared access permissions  
- C. Multiple bills per account  
- D. Eliminates the need for tagging  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
Consolidated billing combines usage from all accounts in an organization, qualifying the organization for **volume pricing discounts**.  

**해설:**  
통합 청구를 사용하면 조직 내 모든 계정의 사용량을 합산하여 **볼륨 요금제 할인 혜택**을 받을 수 있습니다.  

</details>


**89. Which of the following steps should be taken by a customer when conducting penetration testing on AWS?**  
> AWS에서 모의 해킹(Penetration Testing)을 수행할 때 고객이 취해야 할 단계는 무엇입니까?

- A. Conduct penetration testing using Amazon Inspector, and then notify AWS support.  
- B. Request and wait for approval from the customer's internal security team, and then conduct testing.  
- C. Notify AWS support, and then conduct testing immediately.  
- D. Request and wait for approval from AWS support, and then conduct testing.  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
AWS no longer requires prior approval for penetration testing on certain services (e.g., EC2, RDS, ELB, NAT Gateway). Customers only need to obtain approval from their **internal security team** before conducting the test.  

**해설:**  
AWS는 일부 서비스(예: **EC2, RDS, ELB, NAT Gateway**)에 대해 모의 해킹 사전 승인을 더 이상 요구하지 않습니다. 고객은 **내부 보안팀의 승인만 받은 후** 테스트를 진행하면 됩니다.  

</details>


**90. Which of the following AWS features enables a user to launch a pre-configured Amazon Elastic Compute Cloud (Amazon EC2) instance?**  
> 사전 구성된 Amazon EC2 인스턴스를 실행할 수 있게 해주는 AWS 기능은 무엇입니까?

- A. Amazon Elastic Block Store (Amazon EBS)  
- B. Amazon Machine Image  
- C. Amazon EC2 Systems Manager  
- D. Amazon AppStream 2.0  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
An Amazon Machine Image (AMI) provides the information required to launch an EC2 instance. Multiple instances with the same configuration can be launched from a single AMI.  

**해설:**  
**Amazon Machine Image (AMI)**는 EC2 인스턴스를 실행하는 데 필요한 정보를 포함한 **기본 배포 단위**입니다. 하나의 AMI를 통해 동일한 구성을 가진 인스턴스를 여러 개 실행할 수 있습니다.  

</details>

**91. How would an AWS customer easily apply common access controls to a large set of users?**  
> AWS 고객이 많은 사용자 집합에 공통 액세스 제어를 쉽게 적용하는 방법은 무엇입니까?

- A. Apply an IAM policy to an IAM group.  
- B. Apply an IAM policy to an IAM role.  
- C. Apply the same IAM policy to all IAM users with access to the same workload.  
- D. Apply an IAM policy to an Amazon Cognito user pool.  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
Instead of assigning permissions to individual IAM users, it is more convenient to create IAM groups based on job functions (e.g., administrators, developers). Then attach policies to the groups, and IAM users will inherit those permissions.  

**해설:**  
IAM 그룹을 직무(예: 관리자, 개발자) 단위로 만든 후 정책을 그룹에 연결하면, 그룹에 속한 모든 사용자가 동일한 권한을 상속받습니다. 따라서 개별 사용자마다 정책을 붙이지 않고, **그룹 단위로 중앙 관리**가 가능합니다.  

</details>


**92. What technology enables compute capacity to adjust as loads change?**  
> 부하(load)가 변할 때 컴퓨팅 용량을 자동으로 조정할 수 있게 해주는 기술은 무엇입니까?

- A. Load balancing  
- B. Automatic failover  
- C. Round robin  
- D. Auto Scaling  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
Load balancers only distribute traffic across existing instances. Auto Scaling automatically adds or removes instances as traffic changes, ensuring the right capacity at all times.  

**해설:**  
로드 밸런서는 단순히 **기존 인스턴스에 트래픽을 분산**할 뿐이고, **Auto Scaling**은 트래픽 증가 시 인스턴스를 자동으로 추가하고 감소 시 제거하여 **수요에 맞춰 컴퓨팅 용량을 조절**합니다.  

</details>


**93. Which AWS services are defined as global instead of regional? (Choose two.)**  
> 리전 단위가 아니라 전역(Global) 단위로 정의되는 AWS 서비스는 무엇입니까? (2개 선택)

- A. Amazon Route 53  
- B. Amazon EC2  
- C. Amazon S3  
- D. Amazon CloudFront  
- E. Amazon DynamoDB  

<details><summary>Answer</summary>

**Correct:** A, D  
**Explanation:**  
- **Amazon Route 53** is a global DNS service that uses a worldwide anycast network to route users to the optimal endpoint.  
- **Amazon CloudFront** is a global CDN that securely delivers data, video, and applications with low latency.  

**해설:**  
- **Amazon Route 53** → 전 세계 DNS 서버 네트워크를 활용하여 사용자를 최적의 위치로 라우팅하는 글로벌 서비스입니다.  
- **Amazon CloudFront** → 전 세계 엣지 로케이션을 통해 **데이터·영상·애플리케이션을 낮은 지연 시간으로 제공**하는 글로벌 CDN 서비스입니다.  

</details>


**94. Under the shared responsibility model, which of the following tasks are the responsibility of the AWS customer? (Choose two.)**  
> 공유 책임 모델에서, 다음 중 AWS 고객의 책임에 해당하는 작업은 무엇입니까? (2개 선택)

- A. Ensuring that application data is encrypted at rest  
- B. Ensuring that AWS NTP servers are set to the correct time  
- C. Ensuring that users have received security training in the use of AWS services  
- D. Ensuring that access to data centers is restricted  
- E. Ensuring that hardware is disposed of properly  

<details><summary>Answer</summary>

**Correct:** A, C  
**Explanation:**  
Customers are responsible for protecting their data, including encrypting data at rest and in transit. Customers are also responsible for organizational measures such as training users in secure AWS usage.  

**해설:**  
- **A. 데이터 암호화** → 고객은 애플리케이션 데이터의 **저장 시(encryption at rest)** 및 전송 시 암호화를 책임집니다.  
- **C. 사용자 보안 교육** → 고객은 직원이나 사용자가 AWS 서비스를 안전하게 사용할 수 있도록 **보안 교육**을 제공할 책임이 있습니다.  

</details>


**95. Which AWS service can be used to manually launch instances based on resource requirements?**  
> 리소스 요구 사항에 따라 수동으로 인스턴스를 실행할 수 있는 AWS 서비스는 무엇입니까?

- A. Amazon EBS  
- B. Amazon S3  
- C. Amazon EC2  
- D. Amazon ECS  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Amazon EC2 allows customers to launch instances of various types manually, depending on OS, CPU, memory, and storage requirements.  

**해설:**  
**Amazon EC2**는 운영체제, CPU, 메모리, 스토리지 등 요구사항에 따라 **원하는 인스턴스 유형을 직접 선택해 수동으로 실행**할 수 있습니다.  

</details>

**96. A company is migrating an application that is running non-interruptible workloads for a three-year time frame. Which pricing construct would provide the MOST cost-effective solution?**  
> 한 회사가 3년 동안 중단할 수 없는 워크로드를 실행하는 애플리케이션을 마이그레이션하려고 합니다. 가장 비용 효율적인 요금제는 무엇입니까?

- A. Amazon EC2 Spot Instances  
- B. Amazon EC2 Dedicated Instances  
- C. Amazon EC2 On-Demand Instances  
- D. Amazon EC2 Reserved Instances  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
Reserved Instances provide reservations of resources and capacity for 1 or 3 years, with significant discounts (up to 72%) compared to On-Demand pricing. They are ideal for long-term, steady workloads.  

**해설:**  
리저브드 인스턴스(Reserved Instances)는 **1년 또는 3년 동안 리소스를 예약**하며, 온디맨드 대비 **최대 72%까지 할인**을 제공합니다. 따라서 **장기간 지속적이고 중단이 불가능한 워크로드**에 가장 적합한 비용 효율적인 선택입니다.  

</details>

**97. The financial benefits of using AWS are: (Choose two.)**  
> AWS를 사용할 때 얻을 수 있는 재무적 이점은 무엇입니까? (2개 선택)

- A. reduced Total Cost of Ownership (TCO).  
- B. increased capital expenditure (capex).  
- C. reduced operational expenditure (opex).  
- D. deferred payment plans for startups.  
- E. business credit lines for startups.  

<details><summary>Answer</summary>

**Correct:** A, C  
**Explanation:**  
AWS reduces Total Cost of Ownership (TCO) by avoiding large upfront investments in hardware (CapEx). It also reduces ongoing operational expenditures (OpEx) since AWS manages infrastructure, patching, and scaling.  

**해설:**  
- **TCO 절감** → AWS는 서버·데이터센터 같은 하드웨어 구매(자본 지출)를 피하게 해주므로 **총 소유 비용을 낮출 수 있습니다.**  
- **운영비 절감** → AWS가 인프라 관리·패치·스케일링 등을 대신하므로, 고객은 **운영 지출(OpEx)을 줄일 수 있습니다.**  

</details>


**98. Which AWS Cost Management tool allows you to view the most granular data about your AWS bill?**  
> AWS 비용 관리 도구 중, 청구서에 대한 가장 세분화된 데이터를 볼 수 있는 것은 무엇입니까?

- A. AWS Cost Explorer  
- B. AWS Budgets  
- C. AWS Cost and Usage Report  
- D. AWS Billing dashboard  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
The AWS Cost and Usage Report provides the most detailed and granular data about AWS costs and usage, which can also be analyzed with Athena, Redshift, or QuickSight.  

**해설:**  
**AWS Cost and Usage Report**는 **가장 상세하고 세분화된 비용·사용량 데이터를 제공**합니다. 또한 Amazon Athena, Redshift, QuickSight 등과 연동해 분석할 수도 있습니다.  

</details>


**99. Which of the following can an AWS customer use to launch a new Amazon Relational Database Service (Amazon RDS) cluster? (Choose two.)**  
> 고객이 새로운 Amazon RDS 클러스터를 시작할 때 사용할 수 있는 것은 무엇입니까? (2개 선택)

- A. AWS Concierge  
- B. AWS CloudFormation  
- C. Amazon S3  
- D. Amazon EC2 Auto Scaling  
- E. AWS Management Console  

<details><summary>Answer</summary>

**Correct:** B, E  
**Explanation:**  
- **CloudFormation** enables you to launch an RDS cluster as part of Infrastructure as Code (IaC).  
- **AWS Management Console** provides a graphical interface to manually launch and configure an RDS cluster.  

**해설:**  
- **CloudFormation** → 코드 기반으로 RDS 클러스터를 배포할 수 있습니다.  
- **Management Console** → 콘솔 UI를 통해 직접 **RDS 클러스터를 실행·설정**할 수 있습니다.  

</details>


**100. Which of the following is an AWS Cloud architecture design principle?**  
> 다음 중 AWS 클라우드 아키텍처 설계 원칙은 무엇입니까?

- A. Implement single points of failure.  
- B. Implement loose coupling.  
- C. Implement monolithic design.  
- D. Implement vertical scaling.  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Loose coupling means designing systems where components interact with minimal dependencies. This increases reliability, flexibility, and fault tolerance.  

**해설:**  
**느슨한 결합(Loose coupling)**은 **컴포넌트 간 의존성을 최소화**하여 유연성과 내결함성을 높이는 설계 원칙입니다. AWS는 이를 통해 **신뢰성, 확장성, 가용성**을 강화할 것을 권장합니다.  

</details>





