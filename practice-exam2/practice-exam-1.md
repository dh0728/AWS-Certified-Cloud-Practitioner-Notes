## Practice Exam 1 — Q1

**1. Under the shared responsibility model, which of the following is the customer responsible for?**

> 다음 중 공유 책임 모델에서 고객이 책임지는 것은 무엇입니까?

- A. Ensuring that disk drives are wiped after use. 
- B. Ensuring that firmware is updated on hardware devices. 
- C. Ensuring that data is encrypted at rest. 
- D. Ensuring that network cables are category six or higher. 


<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
Data configuration (e.g., encrypting data at rest and in transit) is the customer’s responsibility.  

**해설:**  
데이터 구성(예: 정지 상태 데이터 및 전송 중 데이터 암호화)은 고객의 책임입니다.

</details>


**2. Which allows companies to track and categorize spending on a detailed level?**

> 어떤 기능을 사용하면 기업이 비용을 상세 수준에서 추적하고 분류할 수 있습니까?

- A. Cost allocation tags  
- B. Consolidated billing  
- C. AWS Budgets  
- D. AWS Marketplace  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
After you activate cost allocation tags, AWS uses them to organize your resource costs on the cost allocation report, making it easier to categorize and track costs.  

**해설:**  
비용 할당 태그를 활성화하면 AWS는 이를 사용하여 리소스 비용을 비용 할당 보고서에서 정리하며, 이로 인해 비용을 더 쉽게 분류하고 추적할 수 있습니다.

</details>


**3. Stores objects, provides real-time access to those objects, and offers versioning and lifecycle capabilities**

> 객체를 저장하고, 객체에 실시간으로 접근할 수 있으며, 버전 관리와 수명 주기 기능을 제공하는 것은 무엇입니까?

- A. Amazon Glacier  
- B. AWS Storage Gateway  
- C. Amazon S3  
- D. Amazon EBS  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Amazon S3 is object storage with metadata tags, versioning, and lifecycle features. Unlike block storage (EBS), S3 stores objects and supports versioning to preserve multiple object variants.  

**해설:**  
Amazon S3는 메타데이터 태그, 버전 관리, 수명 주기 기능을 갖춘 객체 스토리지입니다. 블록 스토리지(EBS)와 달리, S3는 객체를 저장하고 여러 객체 변형을 보존하기 위한 버전 관리를 지원합니다.

</details>


**4. What AWS team assists customers with accelerating cloud adoption through paid engagements in any of several specialty practice areas?**

> 다양한 전문 분야에서 유료 참여를 통해 고객의 클라우드 도입을 가속화하도록 지원하는 AWS 팀은 무엇입니까?

- A. AWS Enterprise Support  
- B. AWS Solutions Architects  
- C. AWS Professional Services  
- D. AWS Account Managers  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
AWS Professional Services is a global team that helps enterprises adopt AWS Cloud by working with internal teams and AWS Partners.  

**해설:**  
AWS Professional Services는 내부 팀과 AWS 파트너와 협력하여 기업이 AWS 클라우드를 도입할 수 있도록 돕는 글로벌 팀입니다.

</details>


**5. A customer would like to design and build a new workload on AWS Cloud but does not have the AWS-related software technical expertise in-house. Which of the following AWS programs can a customer take advantage of to achieve that outcome?**

> 고객이 AWS 클라우드에서 새로운 워크로드를 설계·구축하려 하지만 사내에 관련 전문 기술이 없을 경우, 어떤 AWS 프로그램을 활용할 수 있습니까?

- A. AWS Partner Network Technology Partners  
- B. AWS Marketplace  
- C. AWS Partner Network Consulting Partners  
- D. AWS Service Catalogue  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
APN Consulting Partners are professional service firms that help customers design, build, migrate, and manage workloads on AWS.  

**해설:**  
APN Consulting Partners는 고객이 AWS에서 워크로드를 설계, 구축, 마이그레이션 및 관리할 수 있도록 지원하는 전문 서비스 회사들입니다.

</details>


**6. Distributing workloads across multiple Availability Zones supports which cloud architecture design principle?**

> 여러 가용 영역(Availability Zone)에 워크로드를 분산하는 것은 어떤 클라우드 아키텍처 설계 원칙을 지원합니까?

- A. Implement automation  
- B. Design for agility  
- C. Design for failure  
- D. Implement elasticity  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Using multiple AZs removes single points of failure, which is part of “Design for failure” (a Reliability Design Principle).  
Each AZ is engineered to be independent from failures in other AZs.  
Example: a fleet of application servers distributed across multiple AZs attached to ELB. If instances in one AZ fail health checks, ELB stops sending traffic there.  

**해설:**  
여러 AZ를 사용하면 단일 장애 지점을 제거할 수 있으며, 이는 “장애를 고려한 설계(Design for failure)”(신뢰성 설계 원칙)의 일부입니다.  
각 AZ는 다른 AZ의 장애로부터 독립되도록 설계되어 있습니다.  
예시: 여러 AZ에 분산된 애플리케이션 서버 집합이 ELB에 연결된 경우, 특정 AZ의 인스턴스가 상태 확인에 실패하면 ELB는 해당 노드로 트래픽을 보내는 것을 중단합니다.

</details>


**7. Which AWS services can host a Microsoft SQL Server database? (Choose two)**

> Microsoft SQL Server 데이터베이스를 호스팅할 수 있는 AWS 서비스는 무엇입니까? (2개 선택)

- A. Amazon EC2  
- B. Amazon Relational Database Service (Amazon RDS)  
- C. Amazon Aurora  
- D. Amazon Redshift  
- E. Amazon S3  

<details><summary>Answer</summary>

**Correct:** A, B  
**Explanation:**  
- **Amazon EC2** can run any database, including SQL Server.  
- **Amazon RDS** supports SQL Server as one of its managed engines.  

Incorrect answers:  
- Aurora only supports MySQL and PostgreSQL.  
- Redshift is for data warehousing, not SQL Server.  
- S3 is object storage, not a database.  

**해설:**  
- **Amazon EC2**는 SQL Server를 포함한 모든 데이터베이스를 실행할 수 있습니다.  
- **Amazon RDS**는 관리형 엔진 중 하나로 SQL Server를 지원합니다.  

오답 해설:  
- Aurora는 MySQL과 PostgreSQL만 지원합니다.  
- Redshift는 SQL Server가 아닌 데이터 웨어하우스를 위한 서비스입니다.  
- S3는 데이터베이스가 아니라 객체 스토리지입니다.

</details>


**8. Which of the following inspects AWS environments to find opportunities that can save money for users and also improve system performance?**

> AWS 환경을 점검하여 비용 절감 및 성능 개선 기회를 찾아주는 서비스는 무엇입니까?

- A. AWS Cost Explorer  
- B. AWS Trusted Advisor  
- C. Consolidated billing  
- D. Detailed billing  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
AWS Trusted Advisor draws upon best practices from AWS’s operational history. It inspects environments and makes recommendations to save money, improve performance, and close security gaps.  

**해설:**  
AWS Trusted Advisor는 AWS의 운영 기록에서 학습한 모범 사례를 기반으로 합니다. 환경을 점검하고 비용 절감, 성능 향상, 보안 취약점 해소를 위한 권장 사항을 제공합니다.

</details>


**9. Which of the following Amazon EC2 pricing models allow customers to use existing server-bound software licenses?**

> 기존 서버 종속 소프트웨어 라이선스를 사용할 수 있도록 지원하는 Amazon EC2 요금 모델은 무엇입니까?

- A. Spot Instances  
- B. Reserved Instances  
- C. Dedicated Hosts  
- D. On-Demand Instances  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
A Dedicated Host is a physical EC2 server dedicated to a single customer. It allows use of existing server-bound software licenses (e.g., Windows Server, SQL Server, SUSE Linux Enterprise), depending on license terms, and can help with compliance requirements.  

**해설:**  
Dedicated Host는 단일 고객에게 전용으로 제공되는 물리적 EC2 서버입니다. 이는 기존 서버 종속 소프트웨어 라이선스(예: Windows Server, SQL Server, SUSE Linux Enterprise)를 라이선스 조건에 따라 사용할 수 있도록 하며, 규정 준수를 충족하는 데에도 도움이 됩니다.

</details>


**10. Which AWS characteristics make AWS cost effective for a workload with dynamic user demand? (Choose two)**

> 사용자 수요가 동적으로 변하는 워크로드에서 AWS를 비용 효율적으로 만드는 특성은 무엇입니까? (2개 선택)

- A. High availability  
- B. Shared security model  
- C. Elasticity  
- D. Pay-as-you-go pricing  
- E. Reliability  

<details><summary>Answer</summary>

**Correct:** C, D  
**Explanation:**  
- **Elasticity**: stop guessing about capacity; scale resources up or down as needed.  
- **Pay-as-you-go pricing**: trade capital expense for variable expense, only pay for what you use.  

**해설:**  
- **탄력성(Elasticity)**: 용량을 추측하지 않고 필요에 따라 리소스를 확장하거나 축소할 수 있습니다.  
- **사용량 기반 요금제(Pay-as-you-go)**: 자본 지출을 변동 지출로 전환하며, 사용한 만큼만 비용을 지불합니다.

</details>


**11. Which service enables risk auditing by continuously monitoring and logging account activity, including user actions in the AWS Management Console and AWS SDKs?**

> AWS Management Console과 AWS SDK에서의 사용자 작업을 포함하여 계정 활동을 지속적으로 모니터링하고 로깅하여 위험 감사를 가능하게 하는 서비스는 무엇입니까?

- A. Amazon CloudWatch  
- B. AWS CloudTrail  
- C. AWS Config  
- D. AWS Health  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
CloudTrail tracks user activity and API usage. It helps enable governance, compliance, and operational and risk auditing of your AWS account. Actions taken by a user, role, or an AWS service are recorded as events in CloudTrail. Events include actions taken in the AWS Management Console, AWS Command Line Interface, and AWS SDKs and APIs.  

**해설:**  
CloudTrail은 사용자 활동과 API 사용을 추적합니다. 이는 AWS 계정의 거버넌스, 규정 준수, 운영 및 위험 감사를 가능하게 합니다. 사용자, 역할 또는 AWS 서비스가 수행한 작업은 CloudTrail에 이벤트로 기록됩니다. 이벤트에는 AWS Management Console, AWS CLI, AWS SDK 및 API에서 수행된 작업이 포함됩니다.

</details>


**12. Which of the following are characteristics of Amazon S3? (Choose two.)**

> 다음 중 Amazon S3의 특징은 무엇입니까? (2개 선택)

- A. A global file system  
- B. An object store  
- C. A local file store  
- D. A network file system  
- E. A durable storage system  

<details><summary>Answer</summary>

**Correct:** B, E  
**Explanation:**  
S3 provides developers and IT teams with secure, durable, highly scalable object storage. While it is a “global” service, S3 objects by default reside in one region but are stored redundantly across multiple devices in multiple Availability Zones.  

**해설:**  
S3는 개발자와 IT 팀에게 안전하고, 내구성이 있으며, 매우 확장 가능한 객체 스토리지를 제공합니다. “글로벌” 서비스로 제공되지만, 기본적으로 S3 객체는 하나의 리전에 존재하며, 여러 가용 영역 내의 여러 장치에 중복 저장됩니다.

</details>


**13. Which services can be used across hybrid AWS Cloud architectures? (Choose two)**

> 하이브리드 AWS 클라우드 아키텍처에서 사용할 수 있는 서비스는 무엇입니까? (2개 선택)

- A. Amazon Route 53  
- B. Virtual Private Gateway  
- C. Classic Load Balancer  
- D. Auto Scaling  
- E. Amazon CloudWatch default metrics  

<details><summary>Answer</summary>

**Correct:** A, B  
**Explanation:**  
- **Route 53**: Route 53 Resolver Endpoints provide inbound query capability, allowing DNS queries that originate on-premises to resolve AWS hosted domains.  
- **Virtual Private Gateway**: This is the AWS-side anchor of a VPN connection, enabling a VPN between AWS and on-premises.  

**해설:**  
- **Route 53**: Route 53 Resolver Endpoints는 인바운드 쿼리 기능을 제공하여 온프레미스에서 발생한 DNS 쿼리가 AWS에 호스팅된 도메인을 확인할 수 있도록 합니다.  
- **Virtual Private Gateway**: AWS 측의 VPN 연결 지점으로, AWS와 온프레미스 간에 VPN 연결을 가능하게 합니다.

</details>


**14. What costs are included when comparing AWS Total Cost of Ownership (TCO) with on-premises TCO?**

> AWS 총 소유 비용(TCO)을 온프레미스 TCO와 비교할 때 포함되는 비용은 무엇입니까?

- A. Project management  
- B. Antivirus software licensing  
- C. Data center security  
- D. Software development  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Security and compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages, and controls components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates.  

**해설:**  
보안과 규정 준수는 AWS와 고객 간의 공동 책임입니다. 이 공유 모델은 AWS가 호스트 운영 체제와 가상화 계층부터 서비스가 운영되는 시설의 물리적 보안까지의 구성 요소를 운영, 관리, 제어하기 때문에 고객의 운영 부담을 줄이는 데 도움이 됩니다.

</details>



**15. A company is considering using AWS for a self-hosted database that requires a nightly shutdown for maintenance and cost-saving purposes. Which service should the company use?**

> 한 회사가 유지 관리 및 비용 절감을 위해 매일 밤 종료가 필요한 자체 호스팅 데이터베이스를 AWS에서 사용하려고 합니다. 이 경우 어떤 서비스를 사용해야 합니까?

- A. Amazon Redshift  
- B. Amazon DynamoDB  
- C. Amazon Elastic Compute Cloud (Amazon EC2) with Amazon EC2 instance store  
- D. Amazon EC2 with Amazon Elastic Block Store (Amazon EBS)  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
Amazon Elastic Block Store (EBS) is a high-performance block storage service designed for use with Amazon EC2 for both throughput and transaction-intensive workloads at any scale. A broad range of workloads, such as relational and non-relational databases, enterprise applications, containerized applications, big data analytics engines, file systems, and media workflows, are widely deployed on Amazon EBS.  

**해설:**  
Amazon Elastic Block Store(EBS)는 Amazon EC2와 함께 사용하도록 설계된 고성능 블록 스토리지 서비스로, 모든 규모에서 처리량 중심 및 트랜잭션 집약적인 워크로드에 적합합니다. 관계형 및 비관계형 데이터베이스, 엔터프라이즈 애플리케이션, 컨테이너화된 애플리케이션, 빅데이터 분석 엔진, 파일 시스템 및 미디어 워크플로우와 같은 다양한 워크로드가 Amazon EBS에 널리 배포됩니다.

</details>

**16. Which of the following is a correct relationship between regions, Availability Zones, and edge locations?**

> 다음 중 리전(Region), 가용 영역(Availability Zone), 엣지 로케이션(edge location) 간의 올바른 관계는 무엇입니까?

- A. Data centers contain regions.  
- B. Regions contain Availability Zones.  
- C. Availability Zones contain edge locations.  
- D. Edge locations contain regions.  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
A Region is a geographical area that has two or more Availability Zones. Each Region is completely independent.  
An Availability Zone (AZ) is an area with one or more discrete data centers, each with redundant power, networking, and connectivity, housed in separate facilities. If there is more than one data center, they are counted as one AZ if they are located close together. Each AZ is isolated, but the AZs in a Region are connected through low-latency links.  
Edge locations are endpoints used for caching content. They are located in most of the major cities around the world.  

**해설:**  
리전은 두 개 이상의 가용 영역을 포함하는 지리적 영역이며, 각 리전은 완전히 독립적입니다.  
가용 영역(AZ)은 별도의 시설에 위치한 하나 이상의 데이터 센터로 구성되며, 각 센터는 전원, 네트워킹, 연결이 중복으로 제공됩니다. 데이터 센터가 여러 개 있더라도 가까이 위치하면 하나의 AZ로 간주됩니다. 각 AZ는 독립적이지만, 동일한 리전 내 AZ들은 저지연 링크로 연결됩니다.  
엣지 로케이션은 콘텐츠 캐싱을 위한 엔드포인트로, 전 세계 주요 도시에 위치해 있습니다.

</details>


**17. Which AWS tools assist with estimating costs? (Choose three)**

> AWS 비용을 추정하는 데 도움이 되는 도구는 무엇입니까? (3개 선택)

- A. Detailed billing report  
- B. Cost allocation tags  
- C. AWS Pricing Calculator  
- D. AWS Total Cost of Ownership (TCO) Calculator  
- E. Cost Estimator  

<details><summary>Answer</summary>

**Correct:** B, C, D  
**Explanation:**  
- **Cost allocation tags**: Divide your resources into groups, and then estimate the costs for each group.  
- **AWS Pricing Calculator**: Estimate your AWS bill (formerly AWS Simple Monthly Calculator).  
- **TCO Calculator**: Compare the cost of running applications in AWS vs. on-premises.  

**해설:**  
- **비용 할당 태그**: 리소스를 그룹으로 나누어 각 그룹의 비용을 추정할 수 있습니다.  
- **AWS Pricing Calculator**: AWS 요금을 추정하는 데 사용됩니다(이전 이름: AWS Simple Monthly Calculator).  
- **TCO Calculator**: AWS에서 애플리케이션을 운영하는 비용과 온프레미스 비용을 비교할 수 있습니다.

</details>


**18. Which of the following are advantages of AWS consolidated billing? (Choose two)**

> AWS 통합 결제(Consolidated Billing)의 장점은 무엇입니까? (2개 선택)

- A. The ability to receive one bill for multiple accounts  
- B. Service limits increasing by default in all accounts  
- C. A fixed discount on the monthly bill  
- D. Potential volume discounts, as usage in all accounts is combined  
- E. The automatic extension of the master account's AWS support plan to all accounts  

<details><summary>Answer</summary>

**Correct:** A, D  
**Explanation:**  
AWS Organizations allows you to consolidate multiple AWS accounts into a single organization that you centrally manage. This enables:  
- Receiving one bill for multiple accounts.  
- Combining usage across accounts to potentially receive volume discounts.  
Other benefits include programmatically creating accounts, grouping accounts, applying policies, and defining central configurations and audit requirements.  

**해설:**  
AWS Organizations를 사용하면 여러 AWS 계정을 하나의 조직으로 통합하여 중앙에서 관리할 수 있습니다. 이를 통해:  
- 여러 계정에 대한 단일 청구서를 받을 수 있습니다.  
- 계정 전체 사용량을 합산하여 볼륨 할인 혜택을 받을 수 있습니다.  
추가적으로, 계정을 프로그래밍 방식으로 생성하거나 그룹화하고, 정책을 적용하며, 중앙 구성 및 감사 요구사항을 정의할 수 있습니다.

</details>


**19. Which of the following Reserved Instance (RI) pricing models provides the highest average savings compared to On-Demand pricing?**

> 다음 중 어떤 예약 인스턴스(RI) 요금 모델이 온디맨드(On-Demand) 요금 대비 가장 높은 평균 절감을 제공합니까?

- A. One-year, No Upfront, Standard RI pricing  
- B. One-year, All Upfront, Convertible RI pricing  
- C. Three-year, All Upfront, Standard RI pricing  
- D. Three-year, No Upfront, Convertible RI pricing  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Standard Reserved Instances provide significant discounts compared to On-Demand pricing and can be purchased for a 1-year or 3-year term. The greatest average savings are achieved with a 3-year, All Upfront, Standard RI. Customers can change the Availability Zone, instance size, and networking type of their Standard RIs. Convertible RIs provide more flexibility but lower discounts compared to Standard RIs.  

**해설:**  
표준 예약 인스턴스(Standard RI)는 온디맨드 요금에 비해 상당한 할인을 제공하며, 1년 또는 3년 기간으로 구매할 수 있습니다. 가장 큰 평균 절감 효과는 **3년, 선결제(All Upfront), 표준 RI**에서 얻을 수 있습니다. 고객은 표준 RI의 가용 영역, 인스턴스 크기, 네트워킹 유형을 변경할 수 있습니다. 변환형 RI(Convertible RI)는 더 큰 유연성을 제공하지만 표준 RI보다 할인율이 낮습니다.

</details>


**20. Compared with costs in traditional and virtualized data centers, AWS has:**

> 기존 및 가상화된 데이터 센터 비용과 비교했을 때, AWS의 특성은 무엇입니까?

- A. greater variable costs and greater upfront costs.  
- B. fixed usage costs and lower upfront costs.  
- C. lower variable costs and greater upfront costs.  
- D. lower variable costs and lower upfront costs.  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
The cloud allows you to trade high initial capital expenditures (such as data centers and physical servers) for a variable operational expense model, and only pay for IT as you consume it. Variable OpEx expenses are much lower than what you would pay to do it yourself, due to the massive economies of scale created by AWS.  

**해설:**  
클라우드는 데이터 센터 및 물리적 서버와 같은 높은 초기 자본 지출을 변동 운영 비용 모델로 전환할 수 있게 해줍니다. 또한 IT를 사용한 만큼만 비용을 지불합니다. AWS가 창출한 대규모 규모의 경제 덕분에 변동 운영 비용은 직접 구축했을 때보다 훨씬 낮습니다.

</details>
