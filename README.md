# AWSCertifiedSolutionsArchitect
AWS Certified Solutions Architect - Associate(SAA-C03)

![image](https://user-images.githubusercontent.com/67995592/198538074-d6805f29-5c40-4d6b-9693-ff9d04bd2b41.png)



## 시험 범위에 해당되는 AWS공식문서들

### 전체
- [AWS 한국어 설명서 목록](https://aws.amazon.com/ko/blogs/korea/ko-documentation/)
- [AWS 백서](https://aws.amazon.com/ko/whitepapers/)
  - [Amazon Web Services 개요](https://d1.awsstatic.com/International/ko_KR/whitepapers/aws-overview.pdf)
  - [Architecting for the Cloud](https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf)
  - [AWS 보안 모범 사례](https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf)
  - [AWS 스토리지 서비스 개요](https://d1.awsstatic.com/whitepapers/Storage/AWS%20Storage%20Services%20Whitepaper-v9.pdf)
  - [AWS Well-Architected Framework](https://aws.amazon.com/ko/architecture/well-architected/)
  - [클라우드를 위한 아키텍처 설계: AWS 모범 사례](https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf)
  - [AWS Lambda를 사용한 서버리스 아키텍처](https://d1.awsstatic.com/whitepapers/serverless-architectures-with-aws-lambda.pdf)
- [AWS 아키텍처 센터](https://aws.amazon.com/ko/architecture/)


### 영역 1: 복원력을 갖춘 아키텍처 설계
- AWS 글로벌 인프라의 이해
  - [AWS 글로벌 인프라](https://aws.amazon.com/ko/about-aws/global-infrastructure/)
  - [EC2의 지역 및 가용영역 선택](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)
  - [Amazon CloudFront 글로벌 엣지 네트워크](https://aws.amazon.com/ko/cloudfront/details/)
- 클라우드 서비스를 설계하는 방법
  - [AWS 고급 아키텍처 방법론](http://www.slideshare.net/awskorea/aws-cloud-track-2-advanced)
  - [AWS 기반의 마이크로 서비스 아키텍쳐 구현 방안](http://www.slideshare.net/awskorea/micro-service-oriented-architecture-on-aws-piljoong-kim)
- 느슨한 결합을 구현하기 위한 서비스들
  - [ELB](https://aws.amazon.com/ko/elasticloadbalancing/faqs/)
  - [Auto Scaling](https://aws.amazon.com/ko/autoscaling/faqs/)
    - [동적 조정](https://docs.aws.amazon.com/ko_kr/autoscaling/ec2/userguide/as-scale-based-on-demand.html)
    - [예약된 조정](https://docs.aws.amazon.com/ko_kr/autoscaling/ec2/userguide/schedule_time.html)
  - [SQS](https://aws.amazon.com/ko/sqs/faqs/)
  - [SNS](https://aws.amazon.com/ko/sns/faqs/)
- 계획 및 설계
  - [클라우드를 위한 아키텍처 설계 - 모범 사례](https://amz.kr/pdf/Architecture_Best_Practices_draft-KR.pdf)
  - [AWS 고객 사례 모음](https://www.awsseoul.kr/images/content/aws-korea-customer-cases-2016.pdf) 
- 안정적이고 복원력을 갖춘 스토리지 선택하기
  - [EC2 스토리지](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/Storage.html)
  - [EC2 인스턴스 스토어](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/InstanceStorage.html)
  - [EBS FAQ](https://aws.amazon.com/ko/ebs/faqs/)
  - [EFS FAQ](https://aws.amazon.com/ko/efs/faq/)
  - [S3 FAQ](https://aws.amazon.com/ko/s3/faqs/)
  - [Galcier FAQ](https://aws.amazon.com/ko/glacier/faqs/)
  - [Storage Gateway FAQ](https://aws.amazon.com/ko/storagegateway/faqs/)

- 모범 사례
  - [EC2 모범사례](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-best-practices.html)
  - [RDS 모범사례](http://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/CHAP_BestPractices.html)
- 가격/비용을 비롯한 클라이언트 사양 개발(예: 온디맨드 vs. 예약 vs. 스폿, RT  - 및 RP  - DR디자인)
  - [Amazon EC2 요금](https://aws.amazon.com/ko/ec2/pricing/)
- 아키텍처적 트레이드오프(고가용성과 비용 간 트레이드오프, Amazon Relational Database Service(RDS)를 사용하는 것과 Amazon Elastic Compute Cloud(EC2)에 자체 데이터베이스를 설치하는 것 간의 트레이드오프)
  - [Amazon Relational Database Service(Amazon RDS)는 무엇인가?](http://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Welcome.html)
- 기존 개발 환경과의 통합 및 확장형 아키텍처 구축
  - [AWS Enterprise Summit: 하이브리드 클라우드 인프라를 통한 데이터센터 확장과 마이그레이션 방안](http://www.slideshare.net/awskorea/aws-enterprise-summit-67243885)
- 탄력성 및 확장성
  - [AWS 클라우드에서의 웹 애플리케이션 호스팅](http://d0.awsstatic.com/whitepapers/International/ko/AWS_Web_Hosting_Best_Practices_05252010.pdf)
  - [RDS의 고가용성(다중 AZ)](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html)
  - [Amazon CloudWatch를 사용하여 Auto Scaling 인스턴스 및 그룹 모니터링](http://docs.aws.amazon.com/ko_kr/autoscaling/latest/userguide/as-instance-monitoring.html)
  - [Auto Scaling 그룹에 로드 밸런서 사용](http://docs.aws.amazon.com/ko_kr/autoscaling/latest/userguide/autoscaling-load-balancer.html)

### 영역 2: 성능이 뛰어난 아키텍처 정의
- 캐시 사용하기
  - [ElastCache FAQ](https://aws.amazon.com/ko/elasticache/faqs/)
  - [Amazon CloudFront – 제품 세부 정보](https://aws.amazon.com/ko/cloudfront/details/)
- [Amazon Machine Image:AMI](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/AMIs.html)
- 탄력성과 확장성
  - [자동화된 탄력성](https://docs.aws.amazon.com/ko_kr/aws-technical-content/latest/cost-optimization-automating-elasticity/introduction.html)
  - [적절한 크기 조정: 워크로드에 맞춰 인스턴스를 프로비저닝](https://docs.aws.amazon.com/ko_kr/aws-technical-content/latest/cost-optimization-right-sizing/introduction.html)
  - [천만 사용자를 위한 AWS 클라우드 아키텍처 진화하기 - 이창수 솔루션즈 아키텍트](https://www.youtube.com/watch?v=HI0fPiZpniY)
  - [RDBMS의 수평적 확장 - RDS 읽기 전용 복제본](https://aws.amazon.com/ko/rds/features/read-replicas/)

### 영역 3: 안전한 애플리케이션 및 아키텍처
- [클라우드 보안 모범 사례](https://d0.awsstatic.com/International/ko_KR/whitepapers/AWS_Security_Best_Practices_11052013.pdf)
- [AWS 한글 보안 기술 백서](https://aws.amazon.com/ko/blogs/korea/aws-security-whitepapers/)
- [보안 프로세스의 개요](http://d0.awsstatic.com/International/ko_KR/whitepapers/AWS_Security_Whitepaper_Overview.pdf)
- [AWS Security by Design](http://d0.awsstatic.com/International/ko_KR/whitepapers/Compliance/Intro_to_Security_by_Design.pdf)
- [AWS IAM 모범사례](http://docs.aws.amazon.com/ko_kr/IAM/latest/UserGuide/best-practices.html)
  - 책임 분담 보안 모델 ([클라우드 보안 모범 사례](https://d0.awsstatic.com/International/ko_KR/whitepapers/AWS_Security_Best_Practices_11052013.pdf) 안에 포함되어 있음)
  - AWS 플랫폼 규정 준수
    - [AWS 클라우드 규정 준수](https://aws.amazon.com/ko/compliance/)
  - AWS 보안 속성(고객 워크로드부터 물리적 계층까지)
    - [규모별 보안: AWS 기반 거버넌스](http://d0.awsstatic.com/International/ko_KR/whitepapers/Compliance/AWS_Security_at_Scale_Governance_in_AWS_Whitepaper.pdf)
    - [규모별 보안: AWS에서 로깅하기](http://d0.awsstatic.com/International/ko_KR/whitepapers/Compliance/AWS_Security_at_Scale_Logging_in_AWS_Whitepaper.pdf)
  - 보안 서비스
    - [AWS Identity and Access Management(IAM)](http://docs.aws.amazon.com/ko_kr/IAM/latest/UserGuide/introduction.html)
    - [Amazon Virtual Private Cloud(VPC)](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/UserGuide/VPC_Introduction.html)
  - CIA 및 AAA 모델, 인바운드 및 아웃바운드 필터링 그리고 이에 맞는 AWS 서비스 및 기능
  - ‘핵심’ Amazon EC2 및 S3 보안 기능 집합
    - [Amazon S3 리소스에 대한 액세스 권한 관리](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/s3-access-control.html)
  - 공통적인 일반 보안 제품 통합(방화벽, IDS:HIDS/NIDS, SIEM, VPN)
  - 디자인 패턴
    - [AWS Cloud Design Patterns](http://en.clouddesignpattern.org/index.php/Main_Page)
    - [Monitoring Integration Pattern](http://en.clouddesignpattern.org/index.php/CDP:Monitoring_Integration_Pattern)
  - DDos 완화
    - [DDoS 대응을 위한 AWS 모범사례](https://d0.awsstatic.com/International/ko_KR/whitepapers/DDoS_White_Paper.pdf)
  - [암호화 솔루션](http://d0.awsstatic.com/International/ko_KR/whitepapers/Compliance/AWS_Securing_Data_at_Rest_with_Encryption.pdf)
  - 정교한 액세스 제어(세밀한 보안 그룹, ACL 등 구축)
    - [VPC의 보안그룹](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/UserGuide/VPC_SecurityGroups.html)
    - [네트워크 ACL](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/UserGuide/VPC_ACLs.html)
  - [보안 아키텍트를 위한 Amazon CloudWatch](https://aws.amazon.com/ko/cloudwatch/details/)
- [AWS를 사용하는 백업 및 복구 접근 방식](https://d0.awsstatic.com/whitepapers/Storage/LocalizedBR/Backup_and_Recovery_Approaches_Using_AWS_whitepaper_KR.pdf)

- [Amazon S3에서 CloudFront 사용](http://docs.aws.amazon.com/ko_kr/AmazonCloudFront/latest/DeveloperGuide/MigrateS3ToCloudFront.html)
- [Aurora 글로벌 데이터베이스](https://aws.amazon.com/ko/rds/aurora/global-database/)
- [RDS DB인스턴스의 암호화 활성화](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Overview.Encryption.html#Overview.Encryption.Enabling)

- 운영 관련 서비스들
  - [AWS Config](https://aws.amazon.com/ko/config/faq/)
  - [AWS CloudFormation](https://aws.amazon.com/ko/cloudformation/faqs/)
  - [AWS Trusted Advisor](https://aws.amazon.com/ko/premiumsupport/ta-faqs/)
  - [Amazon Inspector](https://aws.amazon.com/ko/inspector/faqs/)
  - [VPC Flow Logs](https://docs.aws.amazon.com/ko_kr/vpc/latest/userguide/flow-logs.html)
  - [Amazon Cloudwatch](https://aws.amazon.com/ko/cloudwatch/faqs/)
    - [Amazon CloudWatch Logs](https://docs.aws.amazon.com/ko_kr/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html)
  - [AWS CloudTrail](https://aws.amazon.com/ko/cloudtrail/faqs/)
  - [AWS Trusted Advisor](https://aws.amazon.com/ko/premiumsupport/trustedadvisor/)
- [모니터링 모범사례](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/monitoring_best_practices.html)
- [AWS 운영을 위한 체크리스트](https://d1.awsstatic.com/whitepapers/aws-operational-checklists.pdf)
- 일반적인 문제 해결 정보 및 질문
  - [인스턴스 연결 중 오류 발생: 연결시간 초과](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/TroubleshootingInstancesConnecting.html#TroubleshootingInstancesConnectionTimeout)
  - [인스턴스 문제 해결](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-instance-troubleshoot.html)
  - [IAM 문제 해결](http://docs.aws.amazon.com/ko_kr/IAM/latest/UserGuide/troubleshoot.html)
- [AWS Service Limits](http://docs.aws.amazon.com/ko_kr/general/latest/gr/aws_service_limits.html): AWS에는 요청으로 변경 가능한 제한(Soft Limits)과 변경이 불가능한 제한(Hard Limits)이 있습니다.
  - [Amazon EC2 서비스 제한](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-resource-limits.html) 
- [Amazon EC2 인스턴스 FAQ](https://aws.amazon.com/ko/instance-help/)

### 영역4. 비용에 최적화된 아키텍처 설계
- [비용 최적화](https://aws.amazon.com/ko/pricing/cost-optimization/)
- AWS 클라우드 비용 최적화를 위한 모범 사례-AWS Summit Seoul 2017
  - [장표](https://www.slideshare.net/awskorea/2-good-cases-of-aws-cloud-cost-optimization)
  - [세션영상](https://www.youtube.com/watch?v=Ks0hJ2CTFsA)
- [AWS 총 소유 비용(TCO) 계산기](https://aws.amazon.com/ko/tco-calculator/)
- [AWS 월 비용 계산기](https://calculator.s3.amazonaws.com/index.html)
- [적절한 크기 조정: 워크로드에 맞춰 인스턴스를 프로비저닝](https://docs.aws.amazon.com/ko_kr/aws-technical-content/latest/cost-optimization-right-sizing/introduction.html)


## 부록
### 부록1. AWS 공인 솔루션스 아키텍트 – 어소시에이트 : 시험준비 워크샵에서 소개된 링크들
- [EBS FAQ](https://aws.amazon.com/ebs/faqs/)
- [백서 – AWS 스토리지 서비스 개요](https://d0.awsstatic.com/whitepapers/Storage/AWS%20Storage%20Services%20Whitepaper-v9.pdf)
- [실습 – Amazon Elastic Block Store 소개](https://amazon.qwiklabs.com/focuses/3458?locale=en)
- [Amazon EC2 인스턴스 스토어](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html)

- [ELB FAQ](https://aws.amazon.com/ko/elasticloadbalancing/faqs/)
- [CloudWatch FAQ](https://aws.amazon.com/ko/cloudwatch/faqs/)
- [Auto Scaling FAQ](https://aws.amazon.com/ko/ec2/autoscaling/faqs/)

- [SQS FAQ](https://aws.amazon.com/sqs/faqs/)
- [ELB FAQ](https://aws.amazon.com/elasticloadbalancing/faqs/)
- [ELB 설명서](https://aws.amazon.com/documentation/elastic-load-balancing/)
- [EIP FAQ](https://aws.amazon.com/ec2/faqs/)
- [Route 53 설명서](https://aws.amazon.com/documentation/route53/)

- [AWS Well Architected 프레임워크](https://aws.amazon.com/architecture/well-architected/)

- [Amazon Web Services: 보안 프로세스의 개요](https://d0.awsstatic.com/whitepapers/Security/AWS_Security_Whitepaper.pdf)
- [AWS 보안 모범 사례 백서](https://d0.awsstatic.com/whitepapers/aws-security-best-practices.pdf)
- [IAM 모범 사례](http://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)
- [AWS 액세스 키를 관리하기 위한 모범 사례](http://docs.aws.amazon.com/general/latest/gr/aws-access-keys-best-practices.html)

- [AWS 리인벤트 2015: VPC 기본 사항 및 연결 옵션](https://www.youtube.com/watch?v=5_bQ6Dgk6k8)
- [AWS 클라우드의 Linux 배스천 호스트](https://s3.amazonaws.com/quickstart-reference/linux/bastion/latest/doc/linux-bastion-hosts-on-the-aws-cloud.pdf)
- [Amazon VPC는 무엇입니까?](http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Introduction.html)

- [AWS에서 데이터 보호 동영상](https://www.youtube.com/watch?v=Tb_W1w_TwLk)

- [저장 데이터 보호 백서](https://d0.awsstatic.com/whitepapers/AWS_Securing_Data_at_Rest_with_Encryption.pdf)

- [Amazon S3 개발자 안내서의 “암호화를 사용한 데이터 보호”](http://docs.aws.amazon.com/AmazonS3/latest/dev/UsingEncryption.html)

- [Amazon Web Services: 보안 프로세스 개요 백서](https://d0.awsstatic.com/whitepapers/Security/AWS_Security_Whitepaper.pdf)

- [IAM Policies and Bucket Policies and ACLs! Oh, My! (Controlling Access to S3 Resources) - Amazon 보안 블로그](http://blogs.aws.amazon.com/security/post/TxPOJBY6FE360K/IAM-policies-and-Bucket-Policies-and-ACLs-Oh-My-Controlling-Access-to-S3-Resourc)

### 부록2. 시험에 자주 나오는 서비스들
- [EC2](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/concepts.html) : AWS의 핵심서비스인 만큼 EC2에 대한 내용은 무척 비중있게 다루어집니다.
  - [인스턴스 및 AMI](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-instances-and-amis.html)
  - [인스턴스 유형](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/instance-types.html)
  - [인스턴스 구입 옵션](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/instance-purchasing-options.html)
  - [리전 및 가용 영역](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)
  - [Amazon EC2 루트 디바이스 볼륨](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/RootDeviceStorage.html)
  - [Amazon EC2 모니터링](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/monitoring_ec2.html)
  - [네트워크 및 보안](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EC2_Network_and_Security.html)
  - [스토리지](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/Storage.html)
  - [Amazon EC2 인스턴스 스토어](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/InstanceStorage.html)
  - [Auto Scaling 설명서](http://docs.aws.amazon.com/ko_kr/autoscaling/latest/userguide/WhatIsAutoScaling.html)
  - [탄력적 네트워크 인터페이스(ENI:Elastic Network Interface)](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/using-eni.html)
  - [EIP](https://aws.amazon.com/ec2/faqs/)
  - [인스턴스 메타데이터 및 사용자 데이터](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-instance-metadata.html)
- [VPC](https://aws.amazon.com/ko/vpc/faqs/)
  - [VPC 사용자 가이드](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/UserGuide/VPC_Introduction.html)
  - [VPC 피어링이란?](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/PeeringGuide/Welcome.html)
  - [Amazon Virtual Private Cloud 를 이용한 IT 인프라의 확장](http://d0.awsstatic.com/International/ko_KR/whitepapers/Extend%20your%20IT%20infrastructure%20with%20Amaon%20VPC.pdf)
- [ELB](https://aws.amazon.com/ko/elasticloadbalancing/faqs/)
- [EBS](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSVolumes.html)
  - [EBS FAQ](https://aws.amazon.com/ko/ebs/faqs/)
  - [EBS 볼륨 유형](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSVolumeTypes.html)
  - [EBS 스냅샷](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSSnapshots.html)
  - [EBS 암호화](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSEncryption.html)
  - [Linux 인스턴스의 Amazon EBS 볼륨 성능](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSPerformance.html)
- [EFS](https://aws.amazon.com/ko/efs/faq/)
- S3
  - [Amazon S3 FAQ](https://aws.amazon.com/ko/s3/faqs/)
  - [Amazon S3 리소스에 대한 액세스 권한 관리](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/s3-access-control.html)
  - [S3 스토리지 클래스](https://aws.amazon.com/ko/s3/storage-classes/)
  - [S3 Reduced Redundancy Storage](https://aws.amazon.com/ko/s3/reduced-redundancy/)
- [CloudFormation](https://aws.amazon.com/ko/cloudformation/faqs/)
- [AWS Lambda](https://aws.amazon.com/ko/lambda/faqs/)
- [AWS Step Functions](https://aws.amazon.com/ko/step-functions/faqs/)
- [Amazon Route53](https://aws.amazon.com/ko/route53/details/)
- [Amazon CloudFront](https://docs.aws.amazon.com/ko_kr/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
- [AWS ECS](https://aws.amazon.com/ko/ecs/faqs/)
  - [AWS ECR](https://aws.amazon.com/ko/ecr/faqs/)
- [AWS KMS](https://aws.amazon.com/ko/kms/faqs/)
- [Amazon DynamoDB](https://aws.amazon.com/ko/dynamodb/faqs/)
  - [SQL에서 NoSQL로](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/SQLtoNoSQL.html)
  - [프로비저닝된 처리량](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/HowItWorks.ProvisionedThroughput.html)
  - [DynamoDB의 쿼리 및 스캔 작업](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/QueryAndScan.html)
  - [파티션 및 데이터 배포](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/HowItWorks.Partitions.html)
- [Elastic Beanstalk](https://aws.amazon.com/ko/elasticbeanstalk/faqs/)
  - [Elastic Beanstalk를 이용한 웹 앱 배포](http://docs.aws.amazon.com/ko_kr/gettingstarted/latest/deploy/overview.html)
- [Amazon SNS](https://aws.amazon.com/ko/sns/faqs/)
- [Amazon SQS](https://aws.amazon.com/ko/sqs/faqs/)
- [AWS Storage Gateway](https://aws.amazon.com/ko/storagegateway/faqs/)
- [Amazon Kinesis](https://aws.amazon.com/ko/kinesis/streams/faqs/)
- [Amazon EMR](https://aws.amazon.com/ko/emr/faqs/)
- [AWS Direct Connect](https://aws.amazon.com/ko/directconnect/)
- [AWS Import/Export](https://aws.amazon.com/ko/documentation/importexport/?nc1=h_ls)
- [AWS Directory Service](https://aws.amazon.com/ko/directoryservice/faqs/)
- [OpsWorks](https://aws.amazon.com/ko/opsworks/faqs/)
- [Amazon MQ](https://aws.amazon.com/ko/amazon-mq/faqs/)

### 부록3. 시험관련 공식문서 요약&정리

> 시험준비에 들어가는 시간과 노력을 줄일 수 있도록 요약&정리해 놓은 문서입니다.

- [AWS Solutions Architect — Associate certificate Study — 공식 문서 정리 Part 1](https://medium.com/@tkdgy0801/aws-solutions-architect-certificate-%EA%B3%B5%EB%B6%80-%EC%98%81%EC%97%AD-1-7abd91cd91a8)
- [AWS Solutions Architect — Associate certificate Study — 공식 문서 정리 Part 2](https://medium.com/@tkdgy0801/aws-solutions-architect-associate-certificate-study-%EA%B3%B5%EC%8B%9D-%EB%AC%B8%EC%84%9C-%EC%A0%95%EB%A6%AC-part-2-3775eb75230e)
- [AWS Solutions Architect — Associate certificate Study — 공식 문서 정리 Part 3](https://medium.com/@tkdgy0801/aws-solutions-architect-associate-certificate-study-%EA%B3%B5%EC%8B%9D-%EB%AC%B8%EC%84%9C-%EC%A0%95%EB%A6%AC-part-3-b14f3e4005b)

