## Practice Exam 3 — Q3

**41. Which of the following is a fast and reliable NoSQL database service?**

> 다음 중 빠르고 신뢰할 수 있는 NoSQL 데이터베이스 서비스는 무엇입니까?

- A. Amazon Redshift  
- B. Amazon RDS  
- C. Amazon DynamoDB  
- D. Amazon S3  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Amazon DynamoDB is a fast and flexible NoSQL database service for any scale. It is a key-value and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multi-region, multi-master, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications.  

**해설:**  
Amazon DynamoDB는 어떤 규모에서도 빠르고 유연한 NoSQL 데이터베이스 서비스입니다. 키-값 및 문서 데이터베이스로, 어떤 규모에서도 한 자릿수 밀리초 성능을 제공합니다. 완전 관리형 서비스이며, 다중 리전·다중 마스터 구조, 내구성, 내장 보안, 백업 및 복구, 인터넷 규모 애플리케이션을 위한 인메모리 캐싱을 지원합니다.  

</details>


**42. What is an example of agility in the AWS Cloud?**

> AWS 클라우드에서 민첩성(agility)의 예는 무엇입니까?

- A. Access to multiple instance types  
- B. Access to managed services  
- C. Using Consolidated Billing to produce one bill  
- D. Decreased acquisition time for new compute resources  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
Agility is the practice of “building in” the ability to change quickly and inexpensively. The cloud not only makes these other practices practical but provides agility on its own. Infrastructure can be provisioned in minutes instead of months, and de-provisioned or changed just as quickly.  

**해설:**  
민첩성이란 빠르고 저렴하게 변화를 수용할 수 있는 능력을 내재화하는 것을 의미합니다. 클라우드는 이러한 관행들을 가능하게 할 뿐만 아니라 자체적으로 민첩성을 제공합니다. 인프라는 몇 달이 아니라 몇 분 만에 프로비저닝될 수 있으며, 해제되거나 변경되는 것도 동일하게 빠르게 가능합니다.  

</details>


**43. Which service should a customer use to consolidate and centrally manage multiple AWS accounts?**

> 여러 AWS 계정을 통합하고 중앙에서 관리하기 위해 고객이 사용해야 하는 서비스는 무엇입니까?

- A. AWS IAM  
- B. AWS Organizations  
- C. AWS Schema Conversion Tool  
- D. AWS Config  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
AWS Organizations helps you centrally manage and govern your environment as you grow and scale your AWS resources. As an administrator of an organization, you can create accounts in your organization and invite existing accounts to join the organization.  
It allows you to:  
- Programmatically create new AWS accounts and allocate resources  
- Group accounts to organize your workflows  
- Apply policies to accounts or groups for governance  
- Define central configurations and audit requirements  
- Simplify billing by centralizing it and using a single payment method for all of your accounts.  
These account management and consolidated billing capabilities enable you to better meet the budgetary, security, and compliance needs of your business.  
- Control access, manage compliance, and coordinate security mechanisms (including restricting the AWS services).  

**해설:**  
AWS Organizations는 AWS 리소스를 확장하고 성장시키면서 환경을 중앙에서 관리하고 거버넌스를 적용할 수 있도록 돕습니다. 관리자는 조직 내에서 계정을 생성하거나 기존 계정을 초대할 수 있습니다.  
Organizations로 할 수 있는 일:  
- 새 AWS 계정을 프로그래밍 방식으로 생성하고 리소스 할당  
- 계정을 그룹화하여 워크플로우 조직  
- 계정 또는 그룹에 정책을 적용하여 거버넌스 실행  
- 중앙 구성을 정의하고 감사 요구 사항 충족  
- 모든 계정을 하나의 결제 방식으로 통합하여 청구 단순화  
이러한 계정 관리 및 통합 청구 기능은 예산, 보안, 규정 준수 요구를 더 잘 충족할 수 있도록 지원합니다.  
또한 접근 제어, 규정 준수 관리, 보안 메커니즘(특정 AWS 서비스 제한 포함)을 조율할 수 있습니다.  

</details>


**44. What approach to transcoding a large number of individual video files adheres to AWS architecture principles?**

> 다수의 개별 비디오 파일을 트랜스코딩할 때 AWS 아키텍처 원칙에 부합하는 접근 방식은 무엇입니까?

- A. Using many instances in parallel  
- B. Using a single large instance during off-peak hours  
- C. Using dedicated hardware  
- D. Using a large GPU instance type  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
A is correct because it is aligned with the Reliability Design Principles and Best Practices of scaling horizontally.  
Reliability Design Principles and Best Practices include:  
- Scale horizontally to increase aggregate workload availability.  
- Replace one large resource with multiple small resources to reduce the impact of a single failure on the overall workload.  
- Distribute requests across multiple resources.  

**해설:**  
정답 A는 수평 확장(horizontal scaling)을 통한 신뢰성 설계 원칙 및 모범 사례와 일치합니다.  
신뢰성 설계 원칙 및 모범 사례에는 다음이 포함됩니다:  
- 수평 확장을 통해 전체 워크로드의 가용성을 높이기  
- 하나의 큰 리소스를 여러 개의 작은 리소스로 대체하여 단일 장애가 전체 워크로드에 미치는 영향을 줄이기  
- 요청을 여러 리소스에 분산하기  

</details>


**45. For which auditing process does AWS have sole responsibility?**

> AWS가 단독으로 책임지는 감사 프로세스는 무엇입니까?

- A. AWS IAM policies  
- B. Physical security  
- C. Amazon S3 bucket policies  
- D. AWS CloudTrail Logs  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
AWS responsibility “Security of the Cloud” – AWS is responsible for protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the physical hardware, software, networking, and facilities that run AWS Cloud services.  

**해설:**  
AWS의 "클라우드 보안(Security of the Cloud)" 책임에 따라, AWS는 AWS 클라우드 서비스가 실행되는 인프라를 보호할 책임이 있습니다. 이 인프라는 물리적 하드웨어, 소프트웨어, 네트워킹, 그리고 AWS 클라우드 서비스를 운영하는 시설로 구성됩니다.  

</details>

**46. Which feature of the AWS Cloud will support an international company's requirement for low latency to all of its customers?**

> 전 세계 고객에게 낮은 지연 시간을 제공하려는 국제 기업의 요구를 지원하는 AWS 클라우드의 기능은 무엇입니까?

- A. Fault tolerance  
- B. Global reach  
- C. Pay-as-you-go pricing  
- D. High availability  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
The AWS Global Infrastructure is built for performance. AWS Regions offer low latency, low packet loss, and high overall network quality. This is achieved with a fully redundant 100 GbE fiber network backbone, often providing many terabits of capacity between Regions. AWS Local Zones and AWS Wavelength, with our telco providers, provide performance for applications that require single-digit millisecond latencies by delivering AWS infrastructure and services closer to end-users and 5G connected devices. Whatever your application needs, you can quickly spin up resources as you need them, deploying hundreds or even thousands of servers in minutes.  

**해설:**  
AWS 글로벌 인프라는 성능을 위해 구축되었습니다. AWS 리전은 낮은 지연 시간, 낮은 패킷 손실, 높은 네트워크 품질을 제공합니다. 이는 완전 이중화된 100GbE 광섬유 백본 네트워크를 통해 달성되며, 리전 간에 수 테라비트의 용량을 제공합니다. AWS Local Zones와 Wavelength는 통신사와 함께, AWS 인프라 및 서비스를 최종 사용자와 5G 연결 장치에 더 가까이 제공하여 한 자릿수 밀리초 지연이 필요한 애플리케이션 성능을 보장합니다. 어떤 애플리케이션이든 필요할 때 몇 분 만에 수백 대에서 수천 대의 서버를 배포할 수 있습니다.  

</details>


**47. Which of the following is the customer's responsibility under the AWS shared responsibility model?**

> AWS 공유 책임 모델에서 고객의 책임에 해당하는 것은 무엇입니까?

- A. Patching underlying infrastructure  
- B. Physical security  
- C. Patching Amazon EC2 instances  
- D. Patching network infrastructure  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Customer responsibility will be determined by the AWS Cloud services that a customer selects. This determines the amount of configuration work the customer must perform as part of their security responsibilities. For example, a service such as Amazon Elastic Compute Cloud (Amazon EC2) is categorized as Infrastructure as a Service (IaaS) and, as such, requires the customer to perform all of the necessary security configuration and management tasks. Customers that deploy an Amazon EC2 instance are responsible for management of the guest operating system.  

**해설:**  
고객의 책임은 고객이 선택한 AWS 클라우드 서비스에 따라 결정됩니다. 이는 보안 책임의 일부로 고객이 수행해야 하는 구성 작업의 양을 의미합니다. 예를 들어 Amazon EC2와 같은 서비스는 IaaS(서비스형 인프라)로 분류되며, 고객은 모든 필요한 보안 구성 및 관리 작업을 직접 수행해야 합니다. Amazon EC2 인스턴스를 배포하는 고객은 게스트 운영체제 관리를 책임집니다.  

</details>


**48. A customer is using multiple AWS accounts with separate billing. How can the customer take advantage of volume discounts with minimal impact to the AWS resources?**

> 여러 AWS 계정을 개별적으로 청구받는 고객이 리소스에 미치는 영향을 최소화하면서 볼륨 할인 혜택을 얻는 방법은 무엇입니까?

- A. Create one global AWS account and move all AWS resources to that account.  
- B. Sign up for three years of Reserved Instance pricing up front.  
- C. Use the consolidated billing feature from AWS Organizations.  
- D. Sign up for the AWS Enterprise support plan to get volume discounts.  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
AWS Organizations helps you centrally manage and govern your environment as you grow and scale your AWS resources. As an administrator of an organization, you can create accounts in your organization and invite existing accounts to join the organization.  
It allows you to:  
- Programmatically create new AWS accounts and allocate resources  
- Group accounts to organize your workflows  
- Apply policies to accounts or groups for governance  
- Define central configurations and audit requirements  
- Simplify billing by centralizing it and using a single payment method for all of your accounts.  

**해설:**  
AWS Organizations는 AWS 리소스를 확장하면서 환경을 중앙에서 관리하고 거버넌스를 적용할 수 있도록 돕습니다. 관리자는 조직 내 계정을 생성하거나 기존 계정을 초대할 수 있습니다.  
이를 통해 다음이 가능합니다:  
- 프로그래밍 방식으로 새 계정 생성 및 리소스 할당  
- 계정을 그룹화하여 워크플로우 구성  
- 계정 또는 그룹에 정책을 적용하여 거버넌스 수행  
- 중앙 구성을 정의하고 감사 요구 사항 충족  
- 청구를 중앙화하여 모든 계정을 단일 결제 방식으로 처리, 비용 절감 및 볼륨 할인 활용  

</details>


**49. Which of the following is an AWS managed Domain Name System (DNS) web service?**

> 다음 중 AWS에서 관리되는 도메인 이름 시스템(DNS) 웹 서비스는 무엇입니까?

- A. Amazon Route 53  
- B. Amazon Neptune  
- C. Amazon SageMaker  
- D. Amazon Lightsail  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other.  

**해설:**  
Amazon Route 53은 고가용성과 확장성을 제공하는 클라우드 기반 도메인 이름 시스템(DNS) 웹 서비스입니다. 이 서비스는 www.example.com 같은 이름을 컴퓨터가 서로 연결하는 데 사용하는 192.0.2.1과 같은 숫자 IP 주소로 변환하여, 개발자와 기업이 최종 사용자를 인터넷 애플리케이션으로 라우팅할 수 있는 매우 안정적이고 비용 효율적인 방법을 제공합니다.  

</details>


**50. A customer is deploying a new application and needs to choose an AWS Region. Which of the following factors could influence the customer's decision? (Choose two)**

> 고객이 새 애플리케이션을 배포하면서 AWS 리전을 선택할 때 의사결정에 영향을 줄 수 있는 요인은 무엇입니까? (2개 선택)

- A. Reduced latency to users  
- B. The application's presentation in the local language  
- C. Data sovereignty compliance  
- D. Cooling costs in hotter climates  
- E. Proximity to the customer's office for on-site visits  

<details><summary>Answer</summary>

**Correct:** A, C  
**Explanation:**  
- Costs of the AWS services can be different for each region because the cost, taxes, manpower, etc. for the physical infrastructure and data centers are different from Region to Region.  
- Latency depends on physical location. When your application is being accessed by your users, it should be blazing fast. So you need to identify the locations of your target audience and choose the region having a smaller latency for your customers.  
- Data sovereignty and compliance requirements may dictate that data must remain within specific jurisdictions, influencing region choice.  

**해설:**  
- AWS 서비스 비용은 리전마다 물리적 인프라와 데이터 센터의 비용, 세금, 인력 등 차이로 인해 다를 수 있습니다.  
- 지연 시간은 물리적 위치에 따라 달라지며, 애플리케이션은 사용자 접근 시 매우 빠르게 응답해야 합니다. 따라서 대상 고객의 위치를 파악하고 지연 시간이 더 짧은 리전을 선택해야 합니다.  
- 데이터 주권 및 규정 준수 요건에 따라 데이터가 특정 관할 구역 내에 유지되어야 할 수도 있으며, 이는 리전 선택에 영향을 줍니다.  

</details>


**51. Which storage service can be used as a low-cost option for hosting static websites?**  
> 정적 웹사이트를 호스팅하는 저비용 옵션으로 사용할 수 있는 스토리지 서비스는 무엇입니까?

- A. Amazon Glacier  
- B. Amazon DynamoDB  
- C. Amazon Elastic File System (Amazon EFS)  
- D. Amazon Simple Storage Service (Amazon S3)  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
You can use Amazon S3 to host a static website. On a static website, individual webpages include static content. They might also contain client-side scripts.  
By contrast, a dynamic website relies on server-side processing, including server-side scripts such as PHP, JSP, or ASP.NET. Amazon S3 does not support server-side scripting, but AWS has other resources for hosting dynamic websites.  

**해설:**  
Amazon S3를 사용하여 정적 웹사이트를 호스팅할 수 있습니다. 정적 웹사이트의 개별 웹페이지에는 정적 콘텐츠가 포함되며, 클라이언트 측 스크립트도 포함될 수 있습니다.  
반대로 동적 웹사이트는 PHP, JSP, ASP.NET과 같은 서버 측 스크립트를 포함한 서버 측 처리에 의존합니다. Amazon S3는 서버 측 스크립트를 지원하지 않지만, AWS는 동적 웹사이트를 호스팅하기 위한 다른 리소스를 제공합니다.  

</details>


**52. Which Amazon EC2 instance pricing model can provide discounts of up to 90%?**  
> Amazon EC2 인스턴스 요금제 중 최대 90%까지 할인을 제공할 수 있는 것은 무엇입니까?

- A. Reserved Instances  
- B. On-Demand  
- C. Dedicated Hosts  
- D. Spot Instances  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
- Spot: Up to 90% discount  
- Reserved: Up to 75% discount  
- On-demand: Full price  
- Dedicated hosts: Higher cost than on-demand  

**해설:**  
- 스팟 인스턴스: 최대 90% 할인  
- 예약 인스턴스: 최대 75% 할인  
- 온디맨드: 정가  
- 전용 호스트: 온디맨드보다 높은 비용  

</details>


**53. What is the AWS customer responsible for according to the AWS shared responsibility model?**  
> AWS 공유 책임 모델에 따르면 고객이 책임지는 것은 무엇입니까?

- A. Physical access controls  
- B. Data encryption  
- C. Secure disposal of storage devices  
- D. Environmental risk management  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
The customer:  
- Assumes responsibility and management of the guest operating system (including updates and security patches), other associated application software as well as the configuration of the AWS provided security group firewall.  
- Should carefully consider the services they choose as their responsibilities vary depending on the services used, the integration of those services into their IT environment, and applicable laws and regulations.  
- Is responsible for data configuration (i.e. encrypting data at rest and in transit).  

**해설:**  
고객은 다음을 책임집니다:  
- 게스트 운영체제(업데이트 및 보안 패치 포함), 관련 애플리케이션 소프트웨어, AWS에서 제공하는 보안 그룹 방화벽의 구성 관리  
- 사용하는 서비스, IT 환경과의 통합 방식, 적용되는 법률과 규정에 따라 책임이 달라지므로 서비스 선택을 신중히 고려해야 합니다  
- 데이터 구성(즉, 정지 상태 및 전송 중 데이터 암호화)  

</details>


**54. Which of the following AWS Cloud services can be used to run a customer-managed relational database?**  
> 고객이 직접 관리하는 관계형 데이터베이스를 실행할 수 있는 AWS 클라우드 서비스는 무엇입니까?

- A. Amazon EC2  
- B. Amazon Route 53  
- C. Amazon ElastiCache  
- D. Amazon DynamoDB  

<details><summary>Answer</summary>

**Correct:** A  
**Explanation:**  
Key phrase is "customer-managed".  
EC2 can be used to run a relational database on whatever operating system the EC2 instance is using (e.g., Microsoft SQL Server running on Microsoft Windows Server 2016).  

Incorrect Answers:  
- DynamoDB is NoSQL type, not a relational database.  
- Route 53 is a DNS service, unrelated to databases.  

**해설:**  
핵심은 "고객이 직접 관리"한다는 점입니다.  
EC2에서는 인스턴스 운영체제 위에 관계형 데이터베이스를 설치하여 실행할 수 있습니다. (예: Microsoft Windows Server 2016에서 실행되는 Microsoft SQL Server)  

오답:  
- DynamoDB는 NoSQL 데이터베이스이므로 관계형 DB가 아님  
- Route 53은 DNS 서비스이므로 데이터베이스와 관련 없음  

</details>


**55. A company is looking for a scalable data warehouse solution. Which of the following AWS solutions would meet the company's needs?**  
> 한 회사가 확장 가능한 데이터 웨어하우스 솔루션을 찾고 있습니다. 다음 중 회사의 요구를 충족할 수 있는 AWS 솔루션은 무엇입니까?

- A. Amazon Simple Storage Service (Amazon S3)  
- B. Amazon DynamoDB  
- C. Amazon Kinesis  
- D. Amazon Redshift  

<details><summary>Answer</summary>

**Correct:** D  
**Explanation:**  
With Redshift, you can query and combine exabytes of structured and semi-structured data across your data warehouse, operational database, and data lake using standard SQL.  
Redshift lets you easily save the results of your queries back to your S3 data lake using open formats, like Apache Parquet, so that you can do additional analytics from other analytics services like Amazon EMR, Amazon Athena, and Amazon SageMaker.  

**해설:**  
Redshift를 사용하면 데이터 웨어하우스, 운영 데이터베이스, 데이터 레이크 전반에 걸쳐 구조적 및 반구조적 데이터를 표준 SQL로 조회하고 결합할 수 있습니다.  
또한 쿼리 결과를 Apache Parquet 같은 오픈 포맷으로 S3 데이터 레이크에 쉽게 저장할 수 있으며, 이를 통해 Amazon EMR, Amazon Athena, Amazon SageMaker와 같은 다른 분석 서비스에서 추가 분석을 수행할 수 있습니다.  

</details>


**56. Which statement best describes Elastic Load Balancing?**  
> Elastic Load Balancing을 가장 잘 설명하는 문장은 무엇입니까?

- A. It translates a domain name into an IP address using DNS.  
- B. It distributes incoming application traffic across one or more Amazon EC2 instances.  
- C. It collects metrics on connected Amazon EC2 instances.  
- D. It automatically adjusts the number of Amazon EC2 instances to support incoming traffic.  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, Lambda functions, and virtual appliances. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones. Elastic Load Balancing offers four types of load balancers that all feature the high availability, automatic scaling, and robust security necessary to make your applications fault tolerant. Elastic Load Balancing scales with web traffic.  

Incorrect answers:  
- **D** — This is related to Auto Scaling and not Load Balancing.  

**해설:**  
Elastic Load Balancing은 들어오는 애플리케이션 트래픽을 Amazon EC2 인스턴스, 컨테이너, IP 주소, Lambda 함수, 가상 어플라이언스와 같은 여러 대상에 자동으로 분산시킵니다. 단일 가용 영역(AZ) 내에서든 여러 가용 영역에 걸쳐서든 애플리케이션 트래픽의 다양한 부하를 처리할 수 있습니다. Elastic Load Balancing은 4가지 유형의 로드 밸런서를 제공하며, 모두 높은 가용성, 자동 확장, 강력한 보안을 제공하여 애플리케이션의 내결함성을 보장합니다. Elastic Load Balancing은 웹 트래픽에 따라 확장됩니다.  

오답:  
- **D** — 이는 로드 밸런싱이 아니라 오토 스케일링과 관련이 있습니다.  

</details>


**57. Which of the following are valid ways for a customer to interact with AWS services? (Choose two.)**  
> 고객이 AWS 서비스와 상호 작용할 수 있는 유효한 방법은 무엇입니까? (2개 선택)

- A. Command line interface  
- B. On-premises  
- C. Software Development Kits  
- D. Software-as-a-service  
- E. Hybrid  

<details><summary>Answer</summary>

**Correct:** A, C  
**Explanation:**  
There are three ways to interact with AWS Services:  
- AWS Management Console – Graphical interface to access AWS features  
- Command Line Interface (CLI) – Lets you control AWS services from the command line  
- Software Development Kits (SDK) – Enable you to access AWS using a variety of popular programming languages  

**해설:**  
AWS 서비스와 상호 작용하는 방법은 3가지입니다:  
- AWS Management Console – AWS 기능에 접근할 수 있는 그래픽 인터페이스  
- CLI(Command Line Interface) – 명령줄에서 AWS 서비스를 제어할 수 있음  
- SDK(Software Development Kits) – 다양한 인기 프로그래밍 언어를 사용하여 AWS에 접근 가능  

</details>


**58. The AWS Cloud's multiple Regions are an example of:**  
> AWS 클라우드의 다수의 리전은 무엇의 예입니까?

- A. agility  
- B. global infrastructure  
- C. elasticity  
- D. pay-as-you-go pricing  

<details><summary>Answer</summary>

**Correct:** B  
**Explanation:**  
Global infrastructure > Regions > Availability Zones.  
The AWS Global Cloud Infrastructure is the most secure, extensive, and reliable cloud platform, offering over 200 fully featured services from data centers globally. Whether you need to deploy your application workloads across the globe in a single click, or you want to build and deploy specific applications closer to your end-users with single-digit millisecond latency, AWS provides you the cloud infrastructure where and when you need it.  

**해설:**  
글로벌 인프라 → 리전 → 가용 영역.  
AWS 글로벌 클라우드 인프라는 전 세계 데이터 센터에서 200개 이상의 완전한 기능의 서비스를 제공하는 가장 안전하고 광범위하며 신뢰할 수 있는 클라우드 플랫폼입니다. 단 한 번의 클릭으로 전 세계에 애플리케이션 워크로드를 배포하거나, 단일 밀리초 지연 시간으로 엔드 유저에 더 가까운 곳에 특정 애플리케이션을 구축 및 배포해야 할 때 AWS는 필요한 곳과 시기에 클라우드 인프라를 제공합니다.  

</details>


**59. Which of the following AWS services can be used to serve large amounts of online video content with the lowest possible latency? (Choose two.)**  
> 대량의 온라인 비디오 콘텐츠를 가능한 낮은 지연 시간으로 제공할 수 있는 AWS 서비스는 무엇입니까? (2개 선택)

- A. AWS Storage Gateway  
- B. Amazon S3  
- C. Amazon Elastic File System (EFS)  
- D. Amazon Glacier  
- E. Amazon CloudFront  

<details><summary>Answer</summary>

**Correct:** B, E  
**Explanation:**  
Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment. CloudFront offers the most advanced security capabilities, including field-level encryption and HTTPS support, seamlessly integrated with AWS Shield, AWS Web Application Firewall, and Route 53 to protect against attacks.  

**해설:**  
Amazon CloudFront는 빠른 콘텐츠 전송 네트워크(CDN) 서비스로, 전 세계 고객에게 데이터, 비디오, 애플리케이션, API를 낮은 지연 시간과 높은 전송 속도로 안전하게 제공합니다. CloudFront는 필드 수준 암호화 및 HTTPS 지원을 포함한 가장 발전된 보안 기능을 제공하며, AWS Shield, AWS WAF, Route 53과 원활히 통합되어 공격으로부터 보호합니다.  

</details>


**60. Web servers running on Amazon EC2 access a legacy application running in a corporate data center. What term would describe this model?**  
> Amazon EC2에서 실행 중인 웹 서버가 기업 데이터 센터에서 실행되는 레거시 애플리케이션에 접근할 때, 이 모델을 설명하는 용어는 무엇입니까?

- A. Cloud-native  
- B. Partner network  
- C. Hybrid architecture  
- D. Infrastructure as a service  

<details><summary>Answer</summary>

**Correct:** C  
**Explanation:**  
Hybrid cloud – Mix of public and private cloud.  

**해설:**  
하이브리드 클라우드 – 퍼블릭 클라우드와 프라이빗 클라우드의 혼합 모델입니다.  

</details>

