# AWS Cloud Practitioner

1.<br/>**회사는 AWS 클라우드에서 글로벌 마케팅 애플리케이션을 실행할 계획입니다. 이 애플리케이션은 사용자가 볼 수 있는 비디오를 특징으로 합니다. 회사는 모든 사용자가 낮은 지연 시간으로 이 비디오를 볼 수 있도록 해야 합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스를 사용해야 합니까?**
- A. AWS Auto Scaling
- B. Amazon Kinesis Video Streams
- C. Elastic Load Balancing
- D. Amazon CloudFront

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. Amazon CloudFront - Amazon CloudFront는 전 세계적으로 콘텐츠를 배포하여 사용자에게 낮은 지연 시간으로 비디오를 제공할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Auto Scaling - AWS Auto Scaling은 애플리케이션의 컴퓨팅 리소스를 자동으로 조정하지만, 콘텐츠 배포와는 관련이 없습니다.</p>
        <p>B. Amazon Kinesis Video Streams - Amazon Kinesis Video Streams는 비디오 스트리밍 데이터를 실시간으로 처리하는 데 사용되지만, 콘텐츠 배포와는 관련이 없습니다.</p>
        <p>C. Elastic Load Balancing - Elastic Load Balancing은 트래픽을 여러 인스턴스로 분산시키지만, 콘텐츠 배포와는 관련이 없습니다.</p>
    </def>
</deflist>

2.<br/>**AWS Well-Architected Framework의 어떤 기둥이 시스템이 인프라 또는 서비스 중단에서 복구하고 수요를 충족하기 위해 컴퓨팅 리소스를 동적으로 확보하는 능력을 나타냅니까?**
- A. 보안
- B. 신뢰성
- C. 성능 효율성
- D. 비용 최적화

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 신뢰성 - 신뢰성 기둥은 시스템이 인프라 또는 서비스 중단에서 복구하고 수요를 충족하기 위해 컴퓨팅 리소스를 동적으로 확보하는 능력을 나타냅니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 보안 - 보안 기둥은 데이터 보호 및 시스템 보안을 다룹니다.</p>
        <p>C. 성능 효율성 - 성능 효율성 기둥은 리소스 사용을 최적화하여 시스템 성능을 향상시키는 것을 다룹니다.</p>
        <p>D. 비용 최적화 - 비용 최적화 기둥은 비용을 절감하고 효율적으로 리소스를 사용하는 것을 다룹니다.</p>
    </def>
</deflist>

3.<br/>**다음 중 AWS 클라우드로의 마이그레이션의 이점은 무엇입니까? (두 가지 선택)**
- A. 운영 탄력성
- B. Amazon.com 제품 할인
- C. 비즈니스 민첩성
- D. 비즈니스 우수성
- E. 직원 유지 증가

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 운영 탄력성 - AWS 클라우드는 인프라의 가용성과 복원력을 높여 운영 탄력성을 제공합니다.
        C. 비즈니스 민첩성 - AWS 클라우드는 리소스를 빠르게 확장하거나 축소할 수 있어 비즈니스 민첩성을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. Amazon.com 제품 할인 - AWS 클라우드로의 마이그레이션은 Amazon.com 제품 할인과 관련이 없습니다.</p>
        <p>D. 비즈니스 우수성 - 비즈니스 우수성은 AWS 클라우드로의 마이그레이션의 직접적인 이점이 아닙니다.</p>
        <p>E. 직원 유지 증가 - AWS 클라우드로의 마이그레이션은 직원 유지 증가와 직접적인 관련이 없습니다.</p>
    </def>
</deflist>

4.<br/>**회사는 물리적 온프레미스 컴퓨팅 서버를 AWS 서버리스 컴퓨팅 서비스로 교체할 계획입니다. 회사는 마이그레이션 후 고급 기술을 빠르게 활용할 수 있기를 원합니다. 이 계획은 AWS Well-Architected Framework의 어떤 기둥을 나타냅니까?**
- A. 보안
- B. 성능 효율성
- C. 운영 우수성
- D. 신뢰성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 성능 효율성 - 성능 효율성 기둥은 최신 기술을 빠르게 채택하고 리소스를 효율적으로 사용하는 것을 다룹니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 보안 - 보안 기둥은 데이터 보호 및 시스템 보안을 다룹니다.</p>
        <p>C. 운영 우수성 - 운영 우수성 기둥은 운영 프로세스의 최적화를 다룹니다.</p>
        <p>D. 신뢰성 - 신뢰성 기둥은 시스템의 가용성과 복원력을 다룹니다.</p>
    </def>
</deflist>

5.<br/>**대기업은 여러 부서를 가지고 있습니다. 각 부서는 자체 AWS 계정을 가지고 있습니다. 각 부서는 Amazon EC2 예약 인스턴스를 구매했습니다. 일부 부서는 구매한 예약 인스턴스를 모두 사용하지 않으며, 다른 부서는 구매한 예약 인스턴스보다 더 많은 예약 인스턴스가 필요합니다. 회사는 모든 부서가 예약 인스턴스를 공유할 수 있도록 AWS 계정을 관리해야 합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스 또는 도구를 사용해야 합니까?**
- A. AWS Systems Manager
- B. Cost Explorer
- C. AWS Trusted Advisor
- D. AWS Organizations

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS Organizations - AWS Organizations는 여러 AWS 계정을 중앙에서 관리하고 리소스를 공유할 수 있는 기능을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Systems Manager - AWS Systems Manager는 인프라 관리를 돕지만, 예약 인스턴스 공유와는 관련이 없습니다.</p>
        <p>B. Cost Explorer - Cost Explorer는 비용 분석 도구로, 예약 인스턴스 공유와는 관련이 없습니다.</p>
        <p>C. AWS Trusted Advisor - AWS Trusted Advisor는 AWS 환경을 최적화하는 데 도움을 주지만, 예약 인스턴스 공유와는 관련이 없습니다.</p>
    </def>
</deflist>

6.<br/>**AWS 글로벌 인프라의 어떤 구성 요소는 중복 전원, 네트워킹 및 연결성을 갖춘 하나 이상의 개별 데이터 센터로 구성되어 있습니까?**
- A. AWS 리전
- B. 가용 영역
- C. 엣지 로케이션
- D. AWS Outposts

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 가용 영역 - 가용 영역은 중복 전원, 네트워킹 및 연결성을 갖춘 하나 이상의 개별 데이터 센터로 구성되어 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS 리전 - AWS 리전은 여러 가용 영역으로 구성된 지리적 영역입니다.</p>
        <p>C. 엣지 로케이션 - 엣지 로케이션은 콘텐츠를 사용자에게 더 가깝게 제공하기 위한 데이터 센터입니다.</p>
        <p>D. AWS Outposts - AWS Outposts는 온프레미스에서 AWS 인프라를 제공하는 서비스입니다.</p>
    </def>
</deflist>

7.<br/>**AWS Lambda를 사용하는 회사의 책임은 무엇입니까? (두 가지 선택)**
- A. 코드 내부의 보안
- B. CPU 리소스 선택
- C. 운영 체제 패치
- D. 코드 작성 및 업데이트
- E. 기본 인프라의 보안

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 코드 내부의 보안 - 회사는 코드 내부의 보안을 책임져야 합니다.
        D. 코드 작성 및 업데이트 - 회사는 Lambda 함수의 코드 작성 및 업데이트를 책임져야 합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. CPU 리소스 선택 - AWS Lambda는 CPU 리소스를 자동으로 관리합니다.</p>
        <p>C. 운영 체제 패치 - AWS Lambda는 운영 체제 패치를 자동으로 관리합니다.</p>
        <p>E. 기본 인프라의 보안 - AWS는 기본 인프라의 보안을 책임집니다.</p>
    </def>
</deflist>

8.<br/>**Amazon EC2 인스턴스를 위한 재해 복구 솔루션을 제공하는 AWS 서비스 또는 기능은 무엇입니까? (두 가지 선택)**
- A. EC2 예약 인스턴스
- B. EC2 Amazon Machine Images (AMIs)
- C. Amazon Elastic Block Store (Amazon EBS) 스냅샷
- D. AWS Shield
- E. Amazon GuardDuty

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. EC2 Amazon Machine Images (AMIs) - AMI는 EC2 인스턴스의 템플릿으로, 재해 복구 시 인스턴스를 빠르게 복원할 수 있습니다.
        C. Amazon Elastic Block Store (Amazon EBS) 스냅샷 - EBS 스냅샷은 데이터 백업을 제공하여 재해 복구 시 데이터를 복원할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. EC2 예약 인스턴스 - 예약 인스턴스는 비용 절감에 도움이 되지만, 재해 복구 솔루션과는 관련이 없습니다.</p>
        <p>D. AWS Shield - AWS Shield는 DDoS 공격으로부터 보호하지만, 재해 복구 솔루션과는 관련이 없습니다.</p>
        <p>E. Amazon GuardDuty - GuardDuty는 위협 탐지 서비스로, 재해 복구 솔루션과는 관련이 없습니다.</p>
    </def>
</deflist>

9.<br/>**회사가 온프레미스 인프라 대신 AWS 클라우드로 마이그레이션하고 있습니다. 이 마이그레이션의 장점은 무엇입니까? (두 가지 선택)**
- A. 보안 감사 수행 필요성 제거
- B. 글로벌 도달 범위 및 민첩성 증가
- C. 몇 분 안에 글로벌 배포 가능
- D. IT 직원 비용 제거
- E. 모든 컴퓨팅 서비스에 대한 기본 중복성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 글로벌 도달 범위 및 민첩성 증가 - AWS 클라우드는 전 세계적으로 리소스를 빠르게 확장하거나 축소할 수 있어 글로벌 도달 범위 및 민첩성을 제공합니다.
        C. 몇 분 안에 글로벌 배포 가능 - AWS 클라우드는 몇 분 안에 글로벌 배포가 가능하여 빠른 확장을 지원합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 보안 감사 수행 필요성 제거 - AWS 클라우드로의 마이그레이션은 보안 감사 수행 필요성을 제거하지 않습니다.</p>
        <p>D. IT 직원 비용 제거 - AWS 클라우드로의 마이그레이션은 IT 직원 비용을 완전히 제거하지 않습니다.</p>
        <p>E. 모든 컴퓨팅 서비스에 대한 기본 중복성 - 모든 컴퓨팅 서비스에 대한 기본 중복성을 제공하지 않습니다.</p>
    </def>
</deflist>

10.<br/>**사용자가 Amazon EC2 및 Amazon RDS에서 실행되는 애플리케이션의 구매 옵션을 비교하고 있습니다. 애플리케이션은 중단을 견딜 수 없습니다. 애플리케이션은 예측 가능한 사용량을 경험하며, 몇 주 동안만 지속되는 계절적 급증이 있습니다. 애플리케이션을 수정할 수 없습니다. 이 요구 사항을 가장 비용 효율적으로 충족하는 구매 옵션은 무엇입니까?**
- A. AWS Marketplace를 검토하고 예측된 및 계절적 부하를 충당하기 위해 부분 선불 예약 인스턴스를 구매하십시오.
- B. 연중 예측된 사용량을 충당하기 위해 예약 인스턴스를 구매하십시오. 계절적 사용량은 스팟 인스턴스로 실행하십시오.
- C. 연중 예측된 사용량을 충당하기 위해 예약 인스턴스를 구매하십시오. 계절적 사용량은 온디맨드 요금으로 실행하십시오.
- D. 계절적 사용량으로 인한 모든 잠재적 사용량을 충당하기 위해 예약 인스턴스를 구매하십시오.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 연중 예측된 사용량을 충당하기 위해 예약 인스턴스를 구매하십시오. 계절적 사용량은 온디맨드 요금으로 실행하십시오. - 예측 가능한 사용량을 예약 인스턴스로 커버하고, 계절적 급증은 온디맨드 요금으로 처리하는 것이 가장 비용 효율적입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Marketplace를 검토하고 예측된 및 계절적 부하를 충당하기 위해 부분 선불 예약 인스턴스를 구매하십시오. - AWS Marketplace에서 부분 선불 예약 인스턴스를 구매하는 것은 예측된 사용량과 계절적 부하를 모두 충당하기에는 비효율적일 수 있습니다.</p>
        <p>B. 연중 예측된 사용량을 충당하기 위해 예약 인스턴스를 구매하십시오. 계절적 사용량은 스팟 인스턴스로 실행하십시오. - 스팟 인스턴스는 중단을 견딜 수 없는 애플리케이션에 적합하지 않습니다.</p>
        <p>D. 계절적 사용량으로 인한 모든 잠재적 사용량을 충당하기 위해 예약 인스턴스를 구매하십시오. - 모든 잠재적 사용량을 예약 인스턴스로 커버하는 것은 비용 효율적이지 않습니다.</p>
    </def>
</deflist>

11.<br/>**회사는 지난 1년 동안 Amazon EC2 및 Amazon RDS 사용에 대한 월별 비용을 검토하고 싶습니다. 이 정보를 제공하는 AWS 서비스 또는 도구는 무엇입니까?**
- A. AWS Trusted Advisor
- B. Cost Explorer
- C. Amazon Forecast
- D. Amazon CloudWatch

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Cost Explorer - Cost Explorer는 지난 1년 동안의 월별 비용을 포함하여 AWS 서비스 사용 비용을 분석하고 시각화할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Trusted Advisor - AWS Trusted Advisor는 비용 최적화, 보안, 성능 및 장애 복구에 대한 권장 사항을 제공하지만, 월별 비용 검토 도구는 아닙니다.</p>
        <p>C. Amazon Forecast - Amazon Forecast는 시계열 데이터를 사용하여 미래의 비즈니스 결과를 예측하는 데 사용됩니다.</p>
        <p>D. Amazon CloudWatch - Amazon CloudWatch는 모니터링 및 로그 관리 도구로, 비용 분석 도구는 아닙니다.</p>
    </def>
</deflist>

12.<br/>**회사는 중요한 애플리케이션을 AWS로 마이그레이션하려고 합니다. 이 애플리케이션은 짧은 실행 시간을 가지며 데이터 변경 또는 시스템 상태 변화에 의해 호출됩니다. 회사는 운영 효율성을 극대화하고 애플리케이션 실행 비용을 최소화하는 컴퓨팅 솔루션이 필요합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 솔루션을 사용해야 합니까?**
- A. Amazon EC2 On-Demand Instances
- B. AWS Lambda
- C. Amazon EC2 Reserved Instances
- D. Amazon EC2 Spot Instances

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS Lambda - AWS Lambda는 이벤트 기반 컴퓨팅 서비스로, 데이터 변경 또는 시스템 상태 변화에 의해 호출되며, 짧은 실행 시간과 비용 효율성을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon EC2 On-Demand Instances - On-Demand Instances는 유연성을 제공하지만, 짧은 실행 시간과 이벤트 기반 호출에 최적화되어 있지 않습니다.</p>
        <p>C. Amazon EC2 Reserved Instances - Reserved Instances는 장기적인 사용에 적합하며, 짧은 실행 시간과 이벤트 기반 호출에 최적화되어 있지 않습니다.</p>
        <p>D. Amazon EC2 Spot Instances - Spot Instances는 비용 효율적이지만, 인스턴스가 언제든지 종료될 수 있어 중요한 애플리케이션에 적합하지 않습니다.</p>
    </def>
</deflist>

13.<br/>**어떤 AWS 서비스 또는 기능을 사용하면 사용자가 프로그래밍 방식으로 AWS 서비스에 연결하고 배포할 수 있습니까?**
- A. AWS Management Console
- B. AWS Cloud9
- C. AWS CodePipeline
- D. AWS 소프트웨어 개발 키트 (SDKs)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS 소프트웨어 개발 키트 (SDKs) - AWS SDKs는 프로그래밍 방식으로 AWS 서비스에 연결하고 배포할 수 있는 도구를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Management Console - AWS Management Console은 웹 기반 인터페이스로, 프로그래밍 방식의 도구는 아닙니다.</p>
        <p>B. AWS Cloud9 - AWS Cloud9는 클라우드 기반 통합 개발 환경(IDE)으로, 프로그래밍 방식의 도구는 아닙니다.</p>
        <p>C. AWS CodePipeline - AWS CodePipeline은 지속적 통합 및 지속적 배포(CI/CD) 서비스로, 프로그래밍 방식의 도구는 아닙니다.</p>
    </def>
</deflist>

14.<br/>**회사는 Amazon S3를 사용하여 데이터 레이크를 만들 계획입니다. 비용에 가장 큰 영향을 미치는 요소는 무엇입니까?**
- A. S3 스토리지 계층 선택
- B. 기존 데이터를 Amazon S3로 전송하는 비용
- C. S3 버킷 정책 추가
- D. 각 요청에 대한 S3 수집 수수료

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. S3 스토리지 계층 선택 - S3 스토리지 계층 선택은 저장 비용에 가장 큰 영향을 미칩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 기존 데이터를 Amazon S3로 전송하는 비용 - 데이터 전송 비용은 초기 비용에 영향을 미치지만, 장기적인 저장 비용에는 큰 영향을 미치지 않습니다.</p>
        <p>C. S3 버킷 정책 추가 - 버킷 정책 추가는 비용에 큰 영향을 미치지 않습니다.</p>
        <p>D. 각 요청에 대한 S3 수집 수수료 - 수집 수수료는 비용에 영향을 미치지만, 스토리지 계층 선택만큼 큰 영향을 미치지 않습니다.</p>
    </def>
</deflist>

15.<br/>**회사는 항상 사용 가능한 전자 상거래 애플리케이션을 출시하고 있습니다. 이 애플리케이션은 다음 12개월 동안 Amazon EC2 인스턴스에서 계속 실행됩니다. 이 요구 사항을 충족하는 가장 비용 효율적인 인스턴스 구매 옵션은 무엇입니까?**
- A. Spot Instances
- B. Savings Plans
- C. Dedicated Hosts
- D. On-Demand Instances

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Savings Plans - Savings Plans는 장기적인 사용에 대해 비용 절감을 제공하여 12개월 동안 계속 실행되는 애플리케이션에 가장 비용 효율적입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Spot Instances - Spot Instances는 비용 효율적이지만, 인스턴스가 언제든지 종료될 수 있어 항상 사용 가능한 애플리케이션에 적합하지 않습니다.</p>
        <p>C. Dedicated Hosts - Dedicated Hosts는 전용 물리적 서버를 제공하지만, 비용 효율적이지 않습니다.</p>
        <p>D. On-Demand Instances - On-Demand Instances는 유연성을 제공하지만, 장기적인 사용에 대해 비용 효율적이지 않습니다.</p>
    </def>
</deflist>

16.<br/>**회사는 특정 AWS 리소스를 사용하는 비즈니스 단위를 결정하기 위해 어떤 AWS 서비스 또는 기능을 사용할 수 있습니까?**
- A. 비용 할당 태그
- B. 키 페어
- C. Amazon Inspector
- D. AWS Trusted Advisor

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 비용 할당 태그 - 비용 할당 태그는 특정 AWS 리소스를 사용하는 비즈니스 단위를 추적하는 데 사용할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 키 페어 - 키 페어는 EC2 인스턴스에 대한 보안 액세스를 제공하지만, 비용 할당과는 관련이 없습니다.</p>
        <p>C. Amazon Inspector - Amazon Inspector는 보안 취약성을 평가하는 도구로, 비용 할당과는 관련이 없습니다.</p>
        <p>D. AWS Trusted Advisor - AWS Trusted Advisor는 비용 최적화, 보안, 성능 및 장애 복구에 대한 권장 사항을 제공하지만, 비용 할당과는 관련이 없습니다.</p>
    </def>
</deflist>

17.<br/>**회사는 AWS로 워크로드를 마이그레이션하려고 하지만, AWS 클라우드 컴퓨팅에 대한 전문 지식이 부족합니다. 이 회사의 마이그레이션을 돕기 위해 어떤 AWS 서비스 또는 기능을 사용할 수 있습니까?**
- A. AWS Trusted Advisor
- B. AWS Consulting Partners
- C. AWS Artifacts
- D. AWS Managed Services

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS Consulting Partners - AWS Consulting Partners는 AWS 클라우드 컴퓨팅에 대한 전문 지식을 제공하여 마이그레이션을 돕습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Trusted Advisor - AWS Trusted Advisor는 비용 최적화, 보안, 성능 및 장애 복구에 대한 권장 사항을 제공하지만, 마이그레이션 지원 서비스는 아닙니다.</p>
        <p>C. AWS Artifacts - AWS Artifacts는 규정 준수 보고서 및 문서를 제공하지만, 마이그레이션 지원 서비스는 아닙니다.</p>
        <p>D. AWS Managed Services - AWS Managed Services는 운영 관리를 돕지만, 마이그레이션 지원 서비스는 아닙니다.</p>
    </def>
</deflist>

18.<br/>**회사는 서비스 한도 증가를 중앙에서 요청하고 추적하기 위해 어떤 AWS 서비스 또는 도구를 사용해야 합니까?**
- A. AWS Config
- B. Service Quotas
- C. AWS Service Catalog
- D. AWS Budgets

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Service Quotas - Service Quotas는 서비스 한도 증가를 중앙에서 요청하고 추적할 수 있는 도구입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Config - AWS Config는 리소스 구성을 추적하고 관리하는 도구로, 서비스 한도 증가와는 관련이 없습니다.</p>
        <p>C. AWS Service Catalog - AWS Service Catalog는 승인된 제품을 중앙에서 관리하는 도구로, 서비스 한도 증가와는 관련이 없습니다.</p>
        <p>D. AWS Budgets - AWS Budgets는 비용 및 사용량을 추적하는 도구로, 서비스 한도 증가와는 관련이 없습니다.</p>
    </def>
</deflist>

19.<br/>**AWS Artifact는 어떤 문서를 제공합니까?**
- A. Amazon EC2 이용 약관
- B. AWS ISO 인증서
- C. 회사의 AWS 지출 내역
- D. 이전 세대 Amazon EC2 인스턴스 유형 목록

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS ISO 인증서 - AWS Artifact는 AWS의 ISO 인증서와 같은 규정 준수 문서를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon EC2 이용 약관 - Amazon EC2 이용 약관은 AWS Artifact에서 제공되지 않습니다.</p>
        <p>C. 회사의 AWS 지출 내역 - AWS Artifact는 회사의 AWS 지출 내역을 제공하지 않습니다.</p>
        <p>D. 이전 세대 Amazon EC2 인스턴스 유형 목록 - 이전 세대 인스턴스 유형 목록은 AWS Artifact에서 제공되지 않습니다.</p>
    </def>
</deflist>

20.<br/>**어떤 작업을 수행하려면 AWS 계정 루트 사용자 자격 증명이 필요합니까?**
- A. 청구 정보 보기
- B. AWS Support 플랜 변경
- C. Amazon EC2 인스턴스 시작 및 중지
- D. AWS Support 케이스 열기

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS Support 플랜 변경 - AWS Support 플랜을 변경하려면 루트 사용자 자격 증명이 필요합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 청구 정보 보기 - 청구 정보는 루트 사용자 자격 증명이 없어도 볼 수 있습니다.</p>
        <p>C. Amazon EC2 인스턴스 시작 및 중지 - EC2 인스턴스를 시작 및 중지하는 데 루트 사용자 자격 증명이 필요하지 않습니다.</p>
        <p>D. AWS Support 케이스 열기 - AWS Support 케이스를 여는 데 루트 사용자 자격 증명이 필요하지 않습니다.</p>
    </def>
</deflist>

21.<br/>**회사는 여러 사용자의 요청을 동시에 처리해야 합니다. 운영 효율적인 솔루션을 구축하기 위해 어떤 AWS 서비스 조합을 사용해야 합니까?**
- A. Amazon Simple Queue Service (Amazon SQS) 및 AWS Lambda
- B. AWS Data Pipeline 및 Amazon EC2
- C. Amazon Kinesis 및 Amazon Athena
- D. AWS Amplify 및 AWS AppSync

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. Amazon Simple Queue Service (Amazon SQS) 및 AWS Lambda - SQS는 요청을 큐에 저장하고, Lambda는 큐에서 요청을 처리하여 운영 효율성을 극대화할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. AWS Data Pipeline 및 Amazon EC2 - 이 조합은 데이터 처리에 적합하지만, 요청을 동시에 처리하는 데 최적화되어 있지 않습니다.</p>
        <p>C. Amazon Kinesis 및 Amazon Athena - 이 조합은 실시간 데이터 스트리밍 및 분석에 적합하지만, 요청을 동시에 처리하는 데 최적화되어 있지 않습니다.</p>
        <p>D. AWS Amplify 및 AWS AppSync - 이 조합은 애플리케이션 개발에 적합하지만, 요청을 동시에 처리하는 데 최적화되어 있지 않습니다.</p>
    </def>
</deflist>

22.<br/>**AWS 네트워크 내에서 VPC의 범위는 무엇입니까?**
- A. VPC는 전 세계 모든 가용 영역에 걸쳐 있을 수 있습니다.
- B. VPC는 각 AWS 리전에서 최소 두 개의 서브넷에 걸쳐 있어야 합니다.
- C. VPC는 각 AWS 리전에서 최소 두 개의 엣지 로케이션에 걸쳐 있어야 합니다.
- D. VPC는 AWS 리전 내의 모든 가용 영역에 걸쳐 있을 수 있습니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. VPC는 AWS 리전 내의 모든 가용 영역에 걸쳐 있을 수 있습니다. - VPC는 단일 리전 내의 여러 가용 영역에 걸쳐 있을 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. VPC는 전 세계 모든 가용 영역에 걸쳐 있을 수 있습니다. - VPC는 단일 리전 내에서만 작동합니다.</p>
        <p>B. VPC는 각 AWS 리전에서 최소 두 개의 서브넷에 걸쳐 있어야 합니다. - VPC는 서브넷 수와 관계없이 단일 리전 내에서 작동할 수 있습니다.</p>
        <p>C. VPC는 각 AWS 리전에서 최소 두 개의 엣지 로케이션에 걸쳐 있어야 합니다. - VPC는 엣지 로케이션과 관련이 없습니다.</p>
    </def>
</deflist>

23.<br/>**다음 중 AWS Site-to-Site VPN 연결의 구성 요소는 무엇입니까? (두 가지 선택)**
- A. AWS Storage Gateway
- B. 가상 프라이빗 게이트웨이
- C. NAT 게이트웨이
- D. 고객 게이트웨이
- E. 인터넷 게이트웨이

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 가상 프라이빗 게이트웨이 - 가상 프라이빗 게이트웨이는 AWS 측의 VPN 연결 지점입니다.
        D. 고객 게이트웨이 - 고객 게이트웨이는 온프레미스 측의 VPN 연결 지점입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Storage Gateway - AWS Storage Gateway는 온프레미스 스토리지와 AWS 클라우드 스토리지를 통합하는 서비스로, VPN 연결과는 관련이 없습니다.</p>
        <p>C. NAT 게이트웨이 - NAT 게이트웨이는 프라이빗 서브넷의 인스턴스가 인터넷에 액세스할 수 있도록 하는 서비스로, VPN 연결과는 관련이 없습니다.</p>
        <p>E. 인터넷 게이트웨이 - 인터넷 게이트웨이는 VPC가 인터넷과 통신할 수 있도록 하는 서비스로, VPN 연결과는 관련이 없습니다.</p>
    </def>
</deflist>

24.<br/>**회사는 두 개의 VPC 간에 연결을 설정해야 합니다. VPC는 두 개의 다른 AWS 리전에 위치해 있습니다. 회사는 이 연결을 위해 기존 VPC 인프라를 사용하고자 합니다. 이 연결을 설정하는 데 사용할 수 있는 AWS 서비스 또는 기능은 무엇입니까?**
- A. AWS Client VPN
- B. VPC 피어링
- C. AWS Direct Connect
- D. VPC 엔드포인트

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. VPC 피어링 - VPC 피어링은 두 개의 다른 리전에 있는 VPC 간에 연결을 설정할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Client VPN - AWS Client VPN은 클라이언트와 VPC 간의 연결을 설정하는 데 사용되며, VPC 간의 연결에는 적합하지 않습니다.</p>
        <p>C. AWS Direct Connect - AWS Direct Connect는 온프레미스 데이터 센터와 AWS 간의 전용 네트워크 연결을 설정하는 데 사용됩니다.</p>
        <p>D. VPC 엔드포인트 - VPC 엔드포인트는 VPC와 AWS 서비스 간의 프라이빗 연결을 설정하는 데 사용됩니다.</p>
    </def>
</deflist>

25.<br/>**AWS 공유 책임 모델에 따르면, Amazon RDS를 사용하여 데이터베이스를 호스팅할 때 고객의 책임은 무엇입니까?**
- A. 데이터베이스에 대한 연결 관리
- B. Microsoft SQL Server 설치
- C. 암호화 전략 설계
- D. 소규모 데이터베이스 패치 적용

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 데이터베이스에 대한 연결 관리 - 고객은 데이터베이스에 대한 연결을 관리해야 합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. Microsoft SQL Server 설치 - Amazon RDS는 데이터베이스 소프트웨어 설치를 관리합니다.</p>
        <p>C. 암호화 전략 설계 - Amazon RDS는 데이터베이스 암호화를 관리합니다.</p>
        <p>D. 소규모 데이터베이스 패치 적용 - Amazon RDS는 데이터베이스 소프트웨어 패치를 관리합니다.</p>
    </def>
</deflist>

26.<br/>**AWS 클라우드에서 애플리케이션을 호스팅하기 위해 Amazon EC2 인스턴스를 사용하는 것의 장점은 무엇입니까? (두 가지 선택)**
- A. EC2는 운영 체제 패치 관리를 포함합니다.
- B. EC2는 Amazon VPC, AWS CloudTrail 및 AWS Identity and Access Management (IAM)와 통합됩니다.
- C. EC2는 100% 서비스 수준 계약(SLA)을 가지고 있습니다.
- D. EC2는 유연한 사용량 기반 요금제를 가지고 있습니다.
- E. EC2는 자동 스토리지 비용 최적화를 가지고 있습니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. EC2는 Amazon VPC, AWS CloudTrail 및 AWS Identity and Access Management (IAM)와 통합됩니다. - EC2는 다양한 AWS 서비스와 통합되어 운영 효율성을 높입니다.
        D. EC2는 유연한 사용량 기반 요금제를 가지고 있습니다. - EC2는 사용한 만큼만 비용을 지불하는 유연한 요금제를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. EC2는 운영 체제 패치 관리를 포함합니다. - 운영 체제 패치 관리는 고객의 책임입니다.</p>
        <p>C. EC2는 100% 서비스 수준 계약(SLA)을 가지고 있습니다. - EC2는 100% SLA를 제공하지 않습니다.</p>
        <p>E. EC2는 자동 스토리지 비용 최적화를 가지고 있습니다. - EC2는 자동 스토리지 비용 최적화를 제공하지 않습니다.</p>
    </def>
</deflist>

27.<br/>**사용자가 지난달에 Amazon EC2 인스턴스의 보안 그룹이 수정되었는지 확인해야 합니다. 사용자가 변경 사항을 확인할 수 있는 방법은 무엇입니까?**
- A. Amazon EC2를 사용하여 보안 그룹이 변경되었는지 확인합니다.
- B. AWS Identity and Access Management (IAM)를 사용하여 보안 그룹을 변경한 사용자 또는 역할을 확인합니다.
- C. AWS CloudTrail을 사용하여 보안 그룹이 변경되었는지 확인합니다.
- D. Amazon CloudWatch를 사용하여 보안 그룹이 변경되었는지 확인합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS CloudTrail을 사용하여 보안 그룹이 변경되었는지 확인합니다. - CloudTrail은 AWS 계정의 API 호출을 기록하여 보안 그룹 변경 사항을 추적할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon EC2를 사용하여 보안 그룹이 변경되었는지 확인합니다. - EC2 콘솔에서는 보안 그룹의 현재 상태만 확인할 수 있습니다.</p>
        <p>B. AWS Identity and Access Management (IAM)를 사용하여 보안 그룹을 변경한 사용자 또는 역할을 확인합니다. - IAM은 보안 그룹 변경 사항을 추적하지 않습니다.</p>
        <p>D. Amazon CloudWatch를 사용하여 보안 그룹이 변경되었는지 확인합니다. - CloudWatch는 모니터링 및 로그 관리 도구로, 보안 그룹 변경 사항을 추적하지 않습니다.</p>
    </def>
</deflist>

28.<br/>**어떤 AWS 서비스가 AWS에서 실행되는 애플리케이션을 DDoS 공격으로부터 보호하는 데 도움이 됩니까?**
- A. Amazon GuardDuty
- B. AWS WAF
- C. AWS Shield
- D. Amazon Inspector

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Shield - AWS Shield는 DDoS 공격으로부터 애플리케이션을 보호하는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon GuardDuty - GuardDuty는 위협 탐지 서비스로, DDoS 공격 보호와는 관련이 없습니다.</p>
        <p>B. AWS WAF - WAF는 웹 애플리케이션 방화벽으로, DDoS 공격 보호 기능이 제한적입니다.</p>
        <p>D. Amazon Inspector - Inspector는 보안 취약성을 평가하는 도구로, DDoS 공격 보호와는 관련이 없습니다.</p>
    </def>
</deflist>

29.<br/>**어떤 AWS 서비스 또는 기능이 Amazon EC2 인스턴스를 위한 방화벽 역할을 합니까?**
- A. 네트워크 ACL
- B. 탄력적 네트워크 인터페이스
- C. Amazon VPC
- D. 보안 그룹

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 보안 그룹 - 보안 그룹은 EC2 인스턴스에 대한 인바운드 및 아웃바운드 트래픽을 제어하는 가상 방화벽 역할을 합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 네트워크 ACL - 네트워크 ACL은 서브넷 수준에서 트래픽을 제어하지만, 인스턴스 수준의 방화벽 역할은 하지 않습니다.</p>
        <p>B. 탄력적 네트워크 인터페이스 - 탄력적 네트워크 인터페이스는 네트워크 인터페이스를 제공하지만, 방화벽 역할은 하지 않습니다.</p>
        <p>C. Amazon VPC - VPC는 가상 네트워크를 제공하지만, 방화벽 역할은 하지 않습니다.</p>
    </def>
</deflist>

30.<br/>**AWS 클라우드 가격 모델은 전통적인 온프레미스 스토리지 가격 모델과 어떻게 다릅니까?**
- A. AWS 리소스는 비용이 발생하지 않습니다.
- B. 인프라 운영 비용이 없습니다.
- C. 선불 비용 약정이 없습니다.
- D. 소프트웨어 라이선스 비용이 없습니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 선불 비용 약정이 없습니다. - AWS 클라우드는 사용한 만큼만 비용을 지불하는 모델로, 선불 비용 약정이 없습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS 리소스는 비용이 발생하지 않습니다. - AWS 리소스는 사용량에 따라 비용이 발생합니다.</p>
        <p>B. 인프라 운영 비용이 없습니다. - AWS 클라우드에도 인프라 운영 비용이 발생합니다.</p>
        <p>D. 소프트웨어 라이선스 비용이 없습니다. - AWS 클라우드에서도 소프트웨어 라이선스 비용이 발생할 수 있습니다.</p>
    </def>
</deflist>

31.<br/>**회사는 단일 Amazon EC2 인스턴스를 보유하고 있습니다. 회사는 고가용성 아키텍처를 채택하고자 합니다. 이 요구 사항을 충족하기 위해 회사는 무엇을 해야 합니까?**
- A. 더 큰 EC2 인스턴스 크기로 수직 확장합니다.
- B. 여러 가용 영역에 걸쳐 수평 확장합니다.
- C. EC2 전용 인스턴스를 구매합니다.
- D. EC2 인스턴스 패밀리를 컴퓨팅 최적화 인스턴스로 변경합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 여러 가용 영역에 걸쳐 수평 확장합니다. - 여러 가용 영역에 걸쳐 인스턴스를 배포하면 고가용성을 보장할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 더 큰 EC2 인스턴스 크기로 수직 확장합니다. - 수직 확장은 고가용성을 보장하지 않습니다.</p>
        <p>C. EC2 전용 인스턴스를 구매합니다. - 전용 인스턴스는 고가용성과 관련이 없습니다.</p>
        <p>D. EC2 인스턴스 패밀리를 컴퓨팅 최적화 인스턴스로 변경합니다. - 인스턴스 패밀리 변경은 고가용성과 관련이 없습니다.</p>
    </def>
</deflist>

32.<br/>**회사의 온프레미스 애플리케이션 배포 주기는 3-4주였습니다. AWS 클라우드로 마이그레이션한 후, 회사는 2-3일 내에 애플리케이션을 배포할 수 있습니다. 이 회사가 AWS 클라우드로 이동함으로써 경험한 이점은 무엇입니까?**
- A. 탄력성
- B. 유연성
- C. 민첩성
- D. 복원력

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 민첩성 - AWS 클라우드는 빠른 배포와 변경에 대한 민첩성을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 탄력성 - 탄력성은 리소스를 자동으로 확장하거나 축소하는 능력을 의미합니다.</p>
        <p>B. 유연성 - 유연성은 다양한 리소스를 선택하고 사용할 수 있는 능력을 의미합니다.</p>
        <p>D. 복원력 - 복원력은 장애에서 빠르게 복구하는 능력을 의미합니다.</p>
    </def>
</deflist>

33.<br/>**다음 중 AWS Enterprise Support에 포함된 항목은 무엇입니까? (두 가지 선택)**
- A. AWS 기술 계정 관리자 (TAM)
- B. AWS 파트너 지원
- C. AWS 전문 서비스
- D. AWS와의 타사 소프트웨어 통합 지원
- E. 중요한 문제에 대한 5분 응답 시간

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. AWS 기술 계정 관리자 (TAM) - TAM은 엔터프라이즈 지원에 포함되어 고객의 기술 요구를 지원합니다.
        E. 중요한 문제에 대한 5분 응답 시간 - 엔터프라이즈 지원은 중요한 문제에 대해 5분 이내의 응답 시간을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. AWS 파트너 지원 - AWS 파트너 지원은 엔터프라이즈 지원에 포함되지 않습니다.</p>
        <p>C. AWS 전문 서비스 - AWS 전문 서비스는 별도의 서비스로, 엔터프라이즈 지원에 포함되지 않습니다.</p>
        <p>D. AWS와의 타사 소프트웨어 통합 지원 - 타사 소프트웨어 통합 지원은 엔터프라이즈 지원에 포함되지 않습니다.</p>
    </def>
</deflist>

34.<br/>**글로벌 미디어 회사는 여러 AWS 계정을 관리하기 위해 AWS Organizations를 사용합니다. 회사는 멤버 계정에 대한 AWS 서비스 액세스를 제한하기 위해 어떤 AWS 서비스 또는 기능을 사용할 수 있습니까?**
- A. AWS Identity and Access Management (IAM)
- B. 서비스 제어 정책 (SCPs)
- C. 조직 단위 (OUs)
- D. 액세스 제어 목록 (ACLs)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 서비스 제어 정책 (SCPs) - SCPs는 조직 내의 멤버 계정에 대한 AWS 서비스 액세스를 제한할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Identity and Access Management (IAM) - IAM은 개별 사용자 및 역할에 대한 액세스를 관리하지만, 조직 전체에 대한 제어는 아닙니다.</p>
        <p>C. 조직 단위 (OUs) - OUs는 계정을 그룹화하는 데 사용되지만, 액세스 제한 기능은 없습니다.</p>
        <p>D. 액세스 제어 목록 (ACLs) - ACLs는 네트워크 트래픽을 제어하는 데 사용되며, 서비스 액세스 제한과는 관련이 없습니다.</p>
    </def>
</deflist>

35.<br/>**회사는 직원의 AWS 액세스를 미리 정의된 AWS 리소스 포트폴리오로 제한하고자 합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 솔루션을 사용해야 합니까?**
- A. AWS Config
- B. AWS 소프트웨어 개발 키트 (SDKs)
- C. AWS Service Catalog
- D. AWS AppSync

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Service Catalog - AWS Service Catalog는 미리 정의된 AWS 리소스 포트폴리오로 직원의 액세스를 제한할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Config - AWS Config는 리소스 구성을 추적하고 관리하는 도구로, 액세스 제한과는 관련이 없습니다.</p>
        <p>B. AWS 소프트웨어 개발 키트 (SDKs) - SDKs는 AWS 서비스와 상호 작용하는 도구로, 액세스 제한과는 관련이 없습니다.</p>
        <p>D. AWS AppSync - AppSync는 GraphQL API를 관리하는 서비스로, 액세스 제한과는 관련이 없습니다.</p>
    </def>
</deflist>

36.<br/>**온라인 회사가 온프레미스에서 워크로드를 실행하고 있었고, 새로운 제품과 기능을 출시하는 데 어려움을 겪고 있었습니다. AWS로 워크로드를 마이그레이션한 후, 회사는 제품과 기능을 빠르게 출시하고 필요에 따라 인프라를 확장할 수 있습니다. 이 시나리오는 AWS 클라우드의 어떤 가치 제안을 설명합니까?**
- A. 비즈니스 민첩성
- B. 고가용성
- C. 보안
- D. 중앙 감사

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 비즈니스 민첩성 - AWS 클라우드는 빠른 제품 출시와 인프라 확장을 통해 비즈니스 민첩성을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 고가용성 - 고가용성은 시스템이 항상 사용할 수 있는 상태를 의미합니다.</p>
        <p>C. 보안 - 보안은 데이터 보호 및 시스템 보안을 의미합니다.</p>
        <p>D. 중앙 감사 - 중앙 감사는 감사 및 모니터링 기능을 의미합니다.</p>
    </def>
</deflist>

37.<br/>**다음 중 AWS 클라우드의 장점은 무엇입니까? (두 가지 선택)**
- A. 사용자 소유 인프라의 AWS 관리
- B. 필요한 용량을 빠르게 변경할 수 있는 능력
- C. 높은 규모의 경제
- D. 시장 출시 시간 증가
- E. 고정 비용 증가

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 필요한 용량을 빠르게 변경할 수 있는 능력 - AWS 클라우드는 필요한 용량을 빠르게 확장하거나 축소할 수 있습니다.
        C. 높은 규모의 경제 - AWS 클라우드는 대규모 사용자 기반을 통해 비용을 절감할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 사용자 소유 인프라의 AWS 관리 - AWS는 사용자 소유 인프라를 관리하지 않습니다.</p>
        <p>D. 시장 출시 시간 증가 - AWS 클라우드는 시장 출시 시간을 단축합니다.</p>
        <p>E. 고정 비용 증가 - AWS 클라우드는 고정 비용을 증가시키지 않습니다.</p>
    </def>
</deflist>

38.<br/>**AWS는 수백만 명의 사용자를 대상으로 사용량을 집계하여 사용한 만큼만 지불하는 가격 모델을 제공합니다. 이는 AWS 클라우드의 어떤 장점을 설명합니까?**
- A. 몇 분 안에 글로벌 출시
- B. 속도와 민첩성 증가
- C. 높은 규모의 경제
- D. 컴퓨팅 용량에 대한 추측 불필요

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 높은 규모의 경제 - AWS는 대규모 사용자 기반을 통해 비용을 절감할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 몇 분 안에 글로벌 출시 - 이는 AWS 클라우드의 다른 장점입니다.</p>
        <p>B. 속도와 민첩성 증가 - 이는 AWS 클라우드의 다른 장점입니다.</p>
        <p>D. 컴퓨팅 용량에 대한 추측 불필요 - 이는 AWS 클라우드의 다른 장점입니다.</p>
    </def>
</deflist>

39.<br/>**회사는 항상 실행 중인 데이터베이스 서버를 보유하고 있습니다. 회사는 이 서버를 Amazon EC2 인스턴스에서 호스팅합니다. 인스턴스 크기는 워크로드에 적합합니다. 워크로드는 1년 동안 실행됩니다. 이 요구 사항을 가장 비용 효율적으로 충족하는 EC2 인스턴스 구매 옵션은 무엇입니까?**
- A. 표준 예약 인스턴스
- B. 온디맨드 인스턴스
- C. 스팟 인스턴스
- D. 변환 예약 인스턴스

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 표준 예약 인스턴스 - 표준 예약 인스턴스는 장기적인 사용에 대해 비용 절감을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 온디맨드 인스턴스 - 온디맨드 인스턴스는 유연성을 제공하지만, 장기적인 사용에 대해 비용 효율적이지 않습니다.</p>
        <p>C. 스팟 인스턴스 - 스팟 인스턴스는 비용 효율적이지만, 인스턴스가 언제든지 종료될 수 있어 항상 실행 중인 서버에 적합하지 않습니다.</p>
        <p>D. 변환 예약 인스턴스 - 변환 예약 인스턴스는 유연성을 제공하지만, 표준 예약 인스턴스보다 비용 효율적이지 않습니다.</p>
    </def>
</deflist>

40.<br/>**회사는 고성능 NoSQL 데이터베이스가 필요한 모바일 앱을 개발하고 있습니다. 이 데이터베이스를 위해 회사가 사용할 수 있는 AWS 서비스는 무엇입니까? (두 가지 선택)**
- A. Amazon Aurora
- B. Amazon RDS
- C. Amazon Redshift
- D. Amazon DocumentDB (MongoDB 호환)
- E. Amazon DynamoDB

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. Amazon DocumentDB (MongoDB 호환) - DocumentDB는 고성능 NoSQL 데이터베이스를 제공합니다.
        E. Amazon DynamoDB - DynamoDB는 고성능 NoSQL 데이터베이스를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Aurora - Aurora는 관계형 데이터베이스 서비스입니다.</p>
        <p>B. Amazon RDS - RDS는 관계형 데이터베이스 서비스입니다.</p>
        <p>C. Amazon Redshift - Redshift는 데이터 웨어하우스 서비스입니다.</p>
    </def>
</deflist>

41.<br/>**AWS 공유 책임 모델에 따르면, 다음 중 AWS의 책임은 무엇입니까? (두 가지 선택)**
- A. Amazon EC2 게스트 운영 체제 패치
- B. 네트워크 인프라의 펌웨어 업그레이드
- C. IAM 사용자에 대한 비밀번호 회전 적용
- D. 엣지 로케이션의 물리적 보안 유지
- E. 루트 사용자 계정에 대한 최소 권한 액세스 유지

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 네트워크 인프라의 펌웨어 업그레이드 - AWS는 네트워크 인프라의 펌웨어 업그레이드를 책임집니다.
        D. 엣지 로케이션의 물리적 보안 유지 - AWS는 엣지 로케이션의 물리적 보안을 책임집니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon EC2 게스트 운영 체제 패치 - 게스트 운영 체제 패치는 고객의 책임입니다.</p>
        <p>C. IAM 사용자에 대한 비밀번호 회전 적용 - 비밀번호 회전 적용은 고객의 책임입니다.</p>
        <p>E. 루트 사용자 계정에 대한 최소 권한 액세스 유지 - 최소 권한 액세스 유지도 고객의 책임입니다.</p>
    </def>
</deflist>

42.<br/>**다음 중 AWS 클라우드에서 사용되는 네트워크 ACL의 기능은 무엇입니까? (두 가지 선택)**
- A. 상태 비저장
- B. 상태 저장
- C. 트래픽을 허용하기 전에 모든 규칙을 평가합니다.
- D. 트래픽을 허용할지 결정할 때 가장 낮은 번호의 규칙부터 순서대로 처리합니다.
- E. 인스턴스 수준에서 작동합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 상태 비저장 - 네트워크 ACL은 상태 비저장입니다.
        D. 트래픽을 허용할지 결정할 때 가장 낮은 번호의 규칙부터 순서대로 처리합니다. - 네트워크 ACL은 규칙을 순서대로 처리합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 상태 저장 - 네트워크 ACL은 상태 비저장입니다.</p>
        <p>C. 트래픽을 허용하기 전에 모든 규칙을 평가합니다. - 네트워크 ACL은 규칙을 순서대로 처리합니다.</p>
        <p>E. 인스턴스 수준에서 작동합니다. - 네트워크 ACL은 서브넷 수준에서 작동합니다.</p>
    </def>
</deflist>

43.<br/>**회사는 AWS 클라우드 인프라를 효과적으로 실행하도록 설계했으며, 지원 프로세스를 지속적으로 개선하기 위한 프로토콜도 마련되어 있습니다. 이 시나리오는 AWS Well-Architected Framework의 어떤 기둥을 나타냅니까?**
- A. 보안
- B. 성능 효율성
- C. 비용 최적화
- D. 운영 우수성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 운영 우수성 - 운영 우수성 기둥은 지속적인 프로세스 개선을 포함합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 보안 - 보안 기둥은 데이터 보호 및 시스템 보안을 다룹니다.</p>
        <p>B. 성능 효율성 - 성능 효율성 기둥은 리소스 사용을 최적화하여 시스템 성능을 향상시키는 것을 다룹니다.</p>
        <p>C. 비용 최적화 - 비용 최적화 기둥은 비용을 절감하고 효율적으로 리소스를 사용하는 것을 다룹니다.</p>
    </def>
</deflist>

44.<br/>**온프레미스 워크로드와 AWS 클라우드 워크로드 간에 프라이빗 연결을 생성하는 데 사용할 수 있는 AWS 서비스 또는 기능은 무엇입니까?**
- A. Amazon Route 53
- B. Amazon Macie
- C. AWS Direct Connect
- D. AWS PrivateLink

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Direct Connect - AWS Direct Connect는 온프레미스와 AWS 간의 프라이빗 연결을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Route 53 - Route 53은 DNS 웹 서비스로, 프라이빗 연결과는 관련이 없습니다.</p>
        <p>B. Amazon Macie - Macie는 데이터 보안 및 개인 정보 보호 서비스로, 프라이빗 연결과는 관련이 없습니다.</p>
        <p>D. AWS PrivateLink - PrivateLink는 VPC와 AWS 서비스 간의 프라이빗 연결을 제공합니다.</p>
    </def>
</deflist>

45.<br/>**회사는 AWS 청구 및 사용량을 시각적으로 그래프로 표시하고 싶습니다. 또한 월별 비용에 대한 정보도 필요합니다. 이 데이터를 그래픽 형식으로 제공하는 AWS Billing and Cost Management 도구는 무엇입니까?**
- A. AWS Bills
- B. Cost Explorer
- C. AWS Cost and Usage Report
- D. AWS Budgets

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Cost Explorer - Cost Explorer는 AWS 청구 및 사용량 데이터를 그래픽 형식으로 시각화할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Bills - AWS Bills는 청구서 세부 정보를 제공하지만, 그래픽 형식은 아닙니다.</p>
        <p>C. AWS Cost and Usage Report - Cost and Usage Report는 세부 비용 데이터를 제공하지만, 그래픽 형식은 아닙니다.</p>
        <p>D. AWS Budgets - AWS Budgets는 예산을 설정하고 추적하는 도구로, 그래픽 형식의 시각화는 아닙니다.</p>
    </def>
</deflist>

46.<br/>**회사는 AWS에서 프로덕션 워크로드를 실행하려고 합니다. 회사는 컨시어지 서비스, 지정된 AWS 기술 계정 관리자(TAM) 및 24시간 연중무휴 기술 지원이 필요합니다. 이 요구 사항을 충족하는 AWS 지원 플랜은 무엇입니까?**
- A. AWS Basic Support
- B. AWS Enterprise Support
- C. AWS Business Support
- D. AWS Developer Support

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS Enterprise Support - Enterprise Support는 컨시어지 서비스, 지정된 TAM 및 24시간 연중무휴 기술 지원을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Basic Support - Basic Support는 제한된 지원만 제공합니다.</p>
        <p>C. AWS Business Support - Business Support는 TAM을 제공하지 않습니다.</p>
        <p>D. AWS Developer Support - Developer Support는 24시간 연중무휴 지원을 제공하지 않습니다.</p>
    </def>
</deflist>

47.<br/>**AWS 클라우드에서 종속 구성 요소 간의 장애를 격리할 필요성을 설명하는 아키텍처 설계 원칙은 무엇입니까?**
- A. 모놀리식 디자인 사용
- B. 자동화를 위한 설계
- C. 단일 장애 지점을 위한 설계
- D. 구성 요소를 느슨하게 결합

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 구성 요소를 느슨하게 결합 - 구성 요소를 느슨하게 결합하면 종속 구성 요소 간의 장애를 격리할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 모놀리식 디자인 사용 - 모놀리식 디자인은 구성 요소 간의 장애 격리를 제공하지 않습니다.</p>
        <p>B. 자동화를 위한 설계 - 자동화는 장애 격리와 관련이 없습니다.</p>
        <p>C. 단일 장애 지점을 위한 설계 - 단일 장애 지점은 장애 격리를 제공하지 않습니다.</p>
    </def>
</deflist>

48.<br/>**다음 중 관리형 데이터베이스 서비스는 무엇입니까? (두 가지 선택)**
- A. Amazon Elastic Block Store (Amazon EBS)
- B. Amazon S3
- C. Amazon RDS
- D. Amazon Elastic File System (Amazon EFS)
- E. Amazon DynamoDB

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. Amazon RDS - RDS는 관리형 관계형 데이터베이스 서비스입니다.
        E. Amazon DynamoDB - DynamoDB는 관리형 NoSQL 데이터베이스 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Elastic Block Store (Amazon EBS) - EBS는 블록 스토리지 서비스입니다.</p>
        <p>B. Amazon S3 - S3는 객체 스토리지 서비스입니다.</p>
        <p>D. Amazon Elastic File System (Amazon EFS) - EFS는 파일 스토리지 서비스입니다.</p>
    </def>
</deflist>

49.<br/>**회사는 애플리케이션을 위해 여러 AWS 서비스를 AWS 프리 티어로 사용하고 있습니다. 프리 티어 사용 기간이 만료되거나 애플리케이션 사용량이 프리 티어 사용 한도를 초과하면 어떻게 됩니까?**
- A. 회사는 프리 티어 사용량을 초과한 사용량에 대해 표준 사용량 기반 요금이 부과됩니다.
- B. AWS 지원 팀이 회사에 연락하여 표준 서비스 요금을 설정합니다.
- C. 회사는 프리 티어 기간 동안 소비한 서비스에 대해 요금이 부과되며, 프리 티어 기간 이후의 서비스 소비에 대해 추가 요금이 부과됩니다.
- D. 회사의 AWS 계정이 동결되며, 결제 계획이 설정된 후 다시 시작할 수 있습니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 회사는 프리 티어 사용량을 초과한 사용량에 대해 표준 사용량 기반 요금이 부과됩니다. - 프리 티어 사용 한도를 초과하면 표준 요금이 부과됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. AWS 지원 팀이 회사에 연락하여 표준 서비스 요금을 설정합니다. - AWS 지원 팀이 연락하지 않습니다.</p>
        <p>C. 회사는 프리 티어 기간 동안 소비한 서비스에 대해 요금이 부과되며, 프리 티어 기간 이후의 서비스 소비에 대해 추가 요금이 부과됩니다. - 프리 티어 기간 동안의 사용량은 무료입니다.</p>
        <p>D. 회사의 AWS 계정이 동결되며, 결제 계획이 설정된 후 다시 시작할 수 있습니다. - 계정이 동결되지 않습니다.</p>
    </def>
</deflist>

50.<br/>**회사는 최근 VPC에 Amazon RDS 인스턴스를 배포했습니다. 회사는 프라이빗 기업 네트워크로의 트래픽을 제한하기 위해 상태 저장 방화벽을 구현해야 합니다. 회사는 RDS 인스턴스로의 네트워크 트래픽을 직접 제한하기 위해 어떤 AWS 서비스 또는 기능을 사용해야 합니까?**
- A. 네트워크 ACL
- B. 보안 그룹
- C. AWS WAF
- D. Amazon GuardDuty

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 보안 그룹 - 보안 그룹은 상태 저장 방화벽으로, RDS 인스턴스로의 트래픽을 제한할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 네트워크 ACL - 네트워크 ACL은 서브넷 수준에서 작동하며, 상태 저장 방화벽이 아닙니다.</p>
        <p>C. AWS WAF - AWS WAF는 웹 애플리케이션 방화벽으로, RDS 인스턴스와 관련이 없습니다.</p>
        <p>D. Amazon GuardDuty - GuardDuty는 위협 탐지 서비스로, 방화벽 기능이 아닙니다.</p>
    </def>
</deflist>

51.<br/>**어떤 AWS 서비스가 기계 학습을 사용하여 Amazon S3 버킷에 저장된 민감한 데이터를 발견, 모니터링 및 보호하는 데 도움을 줍니까?**
- A. AWS Shield
- B. Amazon Macie
- C. AWS Network Firewall
- D. Amazon Cognito

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Amazon Macie - Amazon Macie는 기계 학습을 사용하여 S3 버킷에 저장된 민감한 데이터를 발견, 모니터링 및 보호합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Shield - AWS Shield는 DDoS 공격으로부터 보호하는 서비스입니다.</p>
        <p>C. AWS Network Firewall - AWS Network Firewall은 네트워크 트래픽을 보호하는 서비스입니다.</p>
        <p>D. Amazon Cognito - Amazon Cognito는 사용자 인증 및 관리 서비스입니다.</p>
    </def>
</deflist>

52.<br/>**회사는 AWS에 호스팅된 애플리케이션의 전체 가용성과 성능을 개선하고자 합니다. 회사는 어떤 AWS 서비스를 사용해야 합니까?**
- A. Amazon Connect
- B. Amazon Lightsail
- C. AWS Global Accelerator
- D. AWS Storage Gateway

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Global Accelerator - AWS Global Accelerator는 전 세계적으로 애플리케이션의 가용성과 성능을 개선합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Connect - Amazon Connect는 클라우드 기반 연락 센터 서비스입니다.</p>
        <p>B. Amazon Lightsail - Amazon Lightsail은 간단한 웹 애플리케이션 및 웹사이트를 호스팅하는 서비스입니다.</p>
        <p>D. AWS Storage Gateway - AWS Storage Gateway는 온프레미스 스토리지와 AWS 클라우드 스토리지를 통합하는 서비스입니다.</p>
    </def>
</deflist>

53.<br/>**어떤 AWS 서비스 또는 기능이 Amazon S3 버킷 또는 IAM 역할이 외부 엔터티와 공유되었는지 식별합니까?**
- A. AWS Service Catalog
- B. AWS Systems Manager
- C. AWS IAM Access Analyzer
- D. AWS Organizations

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS IAM Access Analyzer - IAM Access Analyzer는 S3 버킷 또는 IAM 역할이 외부 엔터티와 공유되었는지 식별합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Service Catalog - Service Catalog는 승인된 제품을 중앙에서 관리하는 도구입니다.</p>
        <p>B. AWS Systems Manager - Systems Manager는 인프라 관리를 돕는 도구입니다.</p>
        <p>D. AWS Organizations - Organizations는 여러 AWS 계정을 중앙에서 관리하는 도구입니다.</p>
    </def>
</deflist>

54.<br/>**회사는 컴퓨팅 리소스 사용량을 결정하기 위해 복잡한 예측에 의존하지 않기를 원합니다. 대신, 회사는 사용한 리소스에 대해서만 비용을 지불하고, 비즈니스 요구에 따라 리소스 사용량을 증가 또는 감소시킬 수 있는 능력이 필요합니다. 이 요구 사항은 AWS Well-Architected Framework의 어떤 기둥과 일치합니까?**
- A. 운영 우수성
- B. 보안
- C. 신뢰성
- D. 비용 최적화

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 비용 최적화 - 비용 최적화 기둥은 사용한 리소스에 대해서만 비용을 지불하고, 필요에 따라 리소스 사용량을 조정하는 것을 다룹니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 운영 우수성 - 운영 우수성 기둥은 운영 프로세스의 최적화를 다룹니다.</p>
        <p>B. 보안 - 보안 기둥은 데이터 보호 및 시스템 보안을 다룹니다.</p>
        <p>C. 신뢰성 - 신뢰성 기둥은 시스템의 가용성과 복원력을 다룹니다.</p>
    </def>
</deflist>

55.<br/>**회사는 AWS에서 워크로드를 실행하고자 하며, 시스템이 자동으로 장애에서 복구되기를 원합니다. 이 요구 사항은 AWS Well-Architected Framework의 어떤 기둥에 포함됩니까?**
- A. 비용 최적화
- B. 운영 우수성
- C. 성능 효율성
- D. 신뢰성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 신뢰성 - 신뢰성 기둥은 시스템이 자동으로 장애에서 복구되는 것을 포함합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 비용 최적화 - 비용 최적화 기둥은 비용을 절감하고 효율적으로 리소스를 사용하는 것을 다룹니다.</p>
        <p>B. 운영 우수성 - 운영 우수성 기둥은 운영 프로세스의 최적화를 다룹니다.</p>
        <p>C. 성능 효율성 - 성능 효율성 기둥은 리소스 사용을 최적화하여 시스템 성능을 향상시키는 것을 다룹니다.</p>
    </def>
</deflist>

56.<br/>**전 세계 여러 AWS 리전에 여러 VPC를 보유한 대기업이 VPC 간의 네트워크 연결을 중앙에서 관리하고 연결하려고 합니다. 이 요구 사항을 충족하는 AWS 서비스 또는 기능은 무엇입니까?**
- A. AWS Direct Connect
- B. AWS Transit Gateway
- C. AWS Site-to-Site VPN
- D. VPC 엔드포인트

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS Transit Gateway - Transit Gateway는 여러 VPC와 온프레미스 네트워크 간의 연결을 중앙에서 관리할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Direct Connect - Direct Connect는 온프레미스 네트워크와 AWS 간의 전용 네트워크 연결을 제공합니다.</p>
        <p>C. AWS Site-to-Site VPN - Site-to-Site VPN은 온프레미스 네트워크와 AWS 간의 VPN 연결을 제공합니다.</p>
        <p>D. VPC 엔드포인트 - VPC 엔드포인트는 VPC와 AWS 서비스 간의 프라이빗 연결을 제공합니다.</p>
    </def>
</deflist>

57.<br/>**어떤 AWS 서비스가 AWS 비용 및 사용 보고서 데이터에서 시각적 보고서를 생성하는 것을 지원합니까?**
- A. Amazon Athena
- B. Amazon QuickSight
- C. Amazon CloudWatch
- D. AWS Organizations

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Amazon QuickSight - QuickSight는 AWS 비용 및 사용 보고서 데이터를 기반으로 시각적 보고서를 생성할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Athena - Athena는 S3 데이터를 쿼리하는 서비스입니다.</p>
        <p>C. Amazon CloudWatch - CloudWatch는 모니터링 및 로그 관리 도구입니다.</p>
        <p>D. AWS Organizations - Organizations는 여러 AWS 계정을 중앙에서 관리하는 도구입니다.</p>
    </def>
</deflist>

58.<br/>**어떤 AWS 서비스를 사용하여 Amazon EC2 인스턴스의 CPU 및 네트워크 사용량을 모니터링해야 합니까?**
- A. Amazon Inspector
- B. AWS CloudTrail
- C. Amazon CloudWatch
- D. AWS Config

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. Amazon CloudWatch - CloudWatch는 EC2 인스턴스의 CPU 및 네트워크 사용량을 모니터링할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Inspector - Inspector는 보안 취약성을 평가하는 도구입니다.</p>
        <p>B. AWS CloudTrail - CloudTrail은 API 호출을 기록하는 도구입니다.</p>
        <p>D. AWS Config - Config는 리소스 구성을 추적하고 관리하는 도구입니다.</p>
    </def>
</deflist>

59.<br/>**회사는 다가오는 이벤트를 위해 높은 트래픽을 받을 것으로 예상되는 새로운 웹 스토어를 출시할 준비를 하고 있습니다. 웹 스토어는 AWS에서만 실행되며, 회사는 AWS Enterprise Support 플랜을 보유하고 있습니다. 이벤트 동안 아키텍처 및 운영 지원을 확장하는 방법에 대한 지침을 제공할 AWS 리소스는 무엇입니까?**
- A. AWS Abuse 팀
- B. 지정된 AWS 기술 계정 관리자 (TAM)
- C. AWS 인프라 이벤트 관리
- D. AWS 전문 서비스

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS 인프라 이벤트 관리 - 인프라 이벤트 관리는 중요한 이벤트 동안 아키텍처 및 운영 지원에 대한 지침을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Abuse 팀 - Abuse 팀은 보안 및 남용 문제를 처리합니다.</p>
        <p>B. 지정된 AWS 기술 계정 관리자 (TAM) - TAM은 일반적인 기술 지원을 제공합니다.</p>
        <p>D. AWS 전문 서비스 - 전문 서비스는 특정 프로젝트에 대한 컨설팅을 제공합니다.</p>
    </def>
</deflist>

60.<br/>**사용자가 인프라 코드(IaC) 원칙을 사용하여 AWS 클라우드에 서비스를 배포하려고 합니다. 이 요구 사항을 충족하는 AWS 서비스는 무엇입니까?**
- A. AWS Systems Manager
- B. AWS CloudFormation
- C. AWS CodeCommit
- D. AWS Config

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS CloudFormation - CloudFormation은 인프라를 코드로 정의하고 배포할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Systems Manager - Systems Manager는 인프라 관리를 돕는 도구입니다.</p>
        <p>C. AWS CodeCommit - CodeCommit은 소스 코드 저장소 서비스입니다.</p>
        <p>D. AWS Config - Config는 리소스 구성을 추적하고 관리하는 도구입니다.</p>
    </def>
</deflist>

61.<br/>**여러 비즈니스 유닛을 보유한 회사가 AWS 클라우드 환경을 중앙에서 관리하고 통제하려고 합니다. 회사는 AWS 계정 생성을 자동화하고, 서비스 제어 정책(SCP)을 적용하며, 청구 프로세스를 간소화하고자 합니다. 이 요구 사항을 충족하는 AWS 서비스 또는 도구는 무엇입니까?**
- A. AWS Organizations
- B. Cost Explorer
- C. AWS Budgets
- D. AWS Trusted Advisor

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. AWS Organizations - AWS Organizations는 계정 생성을 자동화하고, SCP를 적용하며, 청구 프로세스를 간소화할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. Cost Explorer - Cost Explorer는 비용 분석 도구로, 계정 관리 및 SCP 적용 기능은 없습니다.</p>
        <p>C. AWS Budgets - AWS Budgets는 예산 설정 및 추적 도구로, 계정 관리 및 SCP 적용 기능은 없습니다.</p>
        <p>D. AWS Trusted Advisor - Trusted Advisor는 비용 최적화, 보안, 성능 및 장애 복구에 대한 권장 사항을 제공하지만, 계정 관리 및 SCP 적용 기능은 없습니다.</p>
    </def>
</deflist>

62.<br/>**AWS 공유 책임 모델에 따르면, 다음 중 AWS와 고객이 공유하는 IT 제어는 무엇입니까? (두 가지 선택)**
- A. 물리적 및 환경적 제어
- B. 패치 관리
- C. 클라우드 인식 및 교육
- D. 존 보안
- E. 애플리케이션 데이터 암호화

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 패치 관리 - 패치 관리는 AWS와 고객이 공유하는 책임입니다.
        E. 애플리케이션 데이터 암호화 - 애플리케이션 데이터 암호화는 AWS와 고객이 공유하는 책임입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 물리적 및 환경적 제어 - 물리적 및 환경적 제어는 AWS의 책임입니다.</p>
        <p>C. 클라우드 인식 및 교육 - 클라우드 인식 및 교육은 고객의 책임입니다.</p>
        <p>D. 존 보안 - 존 보안은 AWS의 책임입니다.</p>
    </def>
</deflist>

63.<br/>**회사는 AWS 클라우드에서 애플리케이션을 출시하고 있습니다. 애플리케이션은 Amazon S3 스토리지를 사용할 것입니다. 대규모 연구팀이 데이터를 공유하여 액세스할 수 있습니다. 회사는 실수로 덮어쓰거나 삭제된 데이터를 복구할 수 있어야 합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 S3 기능을 켜야 합니까?**
- A. 서버 액세스 로깅
- B. S3 버전 관리
- C. S3 수명 주기 규칙
- D. 전송 중 및 저장 중 암호화

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. S3 버전 관리 - S3 버전 관리는 실수로 덮어쓰거나 삭제된 데이터를 복구할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 서버 액세스 로깅 - 서버 액세스 로깅은 액세스 로그를 기록하지만, 데이터 복구 기능은 없습니다.</p>
        <p>C. S3 수명 주기 규칙 - 수명 주기 규칙은 데이터 보관 및 삭제 정책을 관리하지만, 데이터 복구 기능은 없습니다.</p>
        <p>D. 전송 중 및 저장 중 암호화 - 암호화는 데이터 보호를 제공하지만, 데이터 복구 기능은 없습니다.</p>
    </def>
</deflist>

64.<br/>**제조 회사는 느린 인터넷 연결을 가진 원격 사이트에서 실행되는 중요한 애플리케이션을 보유하고 있습니다. 회사는 이 워크로드를 AWS로 마이그레이션하고자 합니다. 애플리케이션은 지연 시간과 연결 중단에 민감합니다. 회사는 최소한의 지연 시간으로 이 애플리케이션을 호스팅할 수 있는 솔루션을 원합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스 또는 기능을 사용해야 합니까?**
- A. 가용 영역
- B. AWS 로컬 영역
- C. AWS 웨이브렝스
- D. AWS 아웃포스트

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS 아웃포스트 - AWS 아웃포스트는 온프레미스 환경에서 AWS 서비스를 제공하여 지연 시간을 최소화할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 가용 영역 - 가용 영역은 AWS 리전 내의 데이터 센터로, 원격 사이트의 지연 시간을 해결하지 못합니다.</p>
        <p>B. AWS 로컬 영역 - 로컬 영역은 특정 지리적 위치에서 지연 시간을 줄일 수 있지만, 원격 사이트의 지연 시간을 해결하지 못할 수 있습니다.</p>
        <p>C. AWS 웨이브렝스 - 웨이브렝스는 5G 네트워크 엣지에서 컴퓨팅 서비스를 제공하지만, 원격 사이트의 지연 시간을 해결하지 못할 수 있습니다.</p>
    </def>
</deflist>

65.<br/>**회사는 온프레미스 데이터 센터에서 AWS 클라우드의 VPC로 애플리케이션을 마이그레이션하려고 합니다. 이러한 애플리케이션은 온프레미스 리소스에 액세스해야 합니다. 이 요구 사항을 충족하는 작업은 무엇입니까? (두 가지 선택)**
- A. AWS Service Catalog를 사용하여 마이그레이션할 수 있는 온프레미스 리소스 목록을 식별합니다.
- B. 온프레미스 장치와 VPC의 가상 프라이빗 게이트웨이 간에 VPN 연결을 생성합니다.
- C. Amazon CloudFront 배포를 사용하고 온프레미스 리소스에 가까운 콘텐츠 전송을 가속화하도록 구성합니다.
- D. 온프레미스 데이터 센터와 AWS 간에 AWS Direct Connect 연결을 설정합니다.
- E. Amazon CloudFront를 사용하여 온프레미스 웹 서버를 통해 제공되는 정적 웹 콘텐츠에 대한 액세스를 제한합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 온프레미스 장치와 VPC의 가상 프라이빗 게이트웨이 간에 VPN 연결을 생성합니다. - VPN 연결은 온프레미스 리소스와 VPC 간의 안전한 연결을 제공합니다.
        D. 온프레미스 데이터 센터와 AWS 간에 AWS Direct Connect 연결을 설정합니다. - Direct Connect는 온프레미스 리소스와 AWS 간의 전용 네트워크 연결을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Service Catalog를 사용하여 마이그레이션할 수 있는 온프레미스 리소스 목록을 식별합니다. - Service Catalog는 리소스 목록을 식별하는 도구가 아닙니다.</p>
        <p>C. Amazon CloudFront 배포를 사용하고 온프레미스 리소스에 가까운 콘텐츠 전송을 가속화하도록 구성합니다. - CloudFront는 콘텐츠 전송 네트워크(CDN)로, 온프레미스 리소스에 대한 연결을 제공하지 않습니다.</p>
        <p>E. Amazon CloudFront를 사용하여 온프레미스 웹 서버를 통해 제공되는 정적 웹 콘텐츠에 대한 액세스를 제한합니다. - CloudFront는 콘텐츠 전송 네트워크(CDN)로, 온프레미스 리소스에 대한 연결을 제공하지 않습니다.</p>
    </def>
</deflist>

66.<br/>**회사는 AWS 클라우드를 사용하여 완전 관리형 환경에서 실행되는 데스크톱 애플리케이션에 대한 안전한 액세스를 제공하려고 합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스를 사용해야 합니까?**
- A. Amazon S3
- B. Amazon AppStream 2.0
- C. AWS AppSync
- D. AWS Outposts

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Amazon AppStream 2.0 - AppStream 2.0은 완전 관리형 환경에서 데스크톱 애플리케이션에 대한 안전한 액세스를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon S3 - S3는 객체 스토리지 서비스로, 데스크톱 애플리케이션 액세스와 관련이 없습니다.</p>
        <p>C. AWS AppSync - AppSync는 GraphQL API를 관리하는 서비스입니다.</p>
        <p>D. AWS Outposts - Outposts는 온프레미스 환경에서 AWS 서비스를 제공하는 솔루션입니다.</p>
    </def>
</deflist>

67.<br/>**회사는 AWS 인프라에서 위협 탐지를 구현하려고 합니다. 그러나 추가 소프트웨어를 배포하고 싶지 않습니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스를 사용해야 합니까?**
- A. Amazon VPC
- B. Amazon EC2
- C. Amazon GuardDuty
- D. AWS Direct Connect

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. Amazon GuardDuty - GuardDuty는 추가 소프트웨어 배포 없이 AWS 인프라에서 위협 탐지를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon VPC - VPC는 가상 네트워크를 제공하지만, 위협 탐지 기능은 없습니다.</p>
        <p>B. Amazon EC2 - EC2는 가상 서버를 제공하지만, 위협 탐지 기능은 없습니다.</p>
        <p>D. AWS Direct Connect - Direct Connect는 온프레미스 네트워크와 AWS 간의 전용 네트워크 연결을 제공합니다.</p>
    </def>
</deflist>

68.<br/>**어떤 AWS 서비스가 엣지 로케이션을 사용합니까?**
- A. Amazon Aurora
- B. AWS Global Accelerator
- C. Amazon Connect
- D. AWS Outposts

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS Global Accelerator - Global Accelerator는 엣지 로케이션을 사용하여 애플리케이션의 가용성과 성능을 개선합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Aurora - Aurora는 관계형 데이터베이스 서비스입니다.</p>
        <p>C. Amazon Connect - Connect는 클라우드 기반 연락 센터 서비스입니다.</p>
        <p>D. AWS Outposts - Outposts는 온프레미스 환경에서 AWS 서비스를 제공하는 솔루션입니다.</p>
    </def>
</deflist>

69.<br/>**회사는 Docker 컨테이너에 애플리케이션을 설치해야 합니다. 컨테이너 호스트를 프로비저닝하고 관리할 필요가 없는 AWS 서비스는 무엇입니까?**
- A. AWS Fargate
- B. Amazon FSx for Windows File Server
- C. Amazon Elastic Container Service (Amazon ECS)
- D. Amazon EC2

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. AWS Fargate - Fargate는 컨테이너 호스트를 프로비저닝하고 관리할 필요 없이 Docker 컨테이너를 실행할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. Amazon FSx for Windows File Server - FSx는 파일 스토리지 서비스입니다.</p>
        <p>C. Amazon Elastic Container Service (Amazon ECS) - ECS는 컨테이너 오케스트레이션 서비스로, Fargate와 함께 사용하여 컨테이너 호스트를 관리할 필요가 없습니다.</p>
        <p>D. Amazon EC2 - EC2는 가상 서버를 제공하지만, 컨테이너 호스트를 프로비저닝하고 관리해야 합니다.</p>
    </def>
</deflist>

70.<br/>**어떤 AWS 서비스 또는 기능이 액세스 정책을 검사하고 사용자가 안전하고 기능적인 정책을 설정할 수 있도록 실행 가능한 권장 사항을 제공합니까?**
- A. AWS Systems Manager
- B. AWS IAM Access Analyzer
- C. AWS Trusted Advisor
- D. Amazon GuardDuty

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS IAM Access Analyzer - IAM Access Analyzer는 액세스 정책을 검사하고 실행 가능한 권장 사항을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Systems Manager - Systems Manager는 인프라 관리를 돕는 도구입니다.</p>
        <p>C. AWS Trusted Advisor - Trusted Advisor는 비용 최적화, 보안, 성능 및 장애 복구에 대한 권장 사항을 제공합니다.</p>
        <p>D. Amazon GuardDuty - GuardDuty는 위협 탐지 서비스입니다.</p>
    </def>
</deflist>

71.<br/>**회사는 화물선을 보유하고 있습니다. 화물선에는 바다에서 데이터를 수집하는 센서가 있으며, 인터넷 연결이 간헐적이거나 없는 경우가 있습니다. 회사는 바다에서 데이터를 수집, 형식화 및 처리하고 나중에 AWS로 데이터를 이동해야 합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스를 사용해야 합니까?**
- A. AWS IoT Core
- B. Amazon Lightsail
- C. AWS Storage Gateway
- D. AWS Snowball Edge

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS Snowball Edge - Snowball Edge는 인터넷 연결이 없는 환경에서 데이터를 수집, 형식화 및 처리하고 나중에 AWS로 데이터를 이동할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS IoT Core - IoT Core는 실시간 데이터 수집 및 처리를 지원하지만, 인터넷 연결이 필요합니다.</p>
        <p>B. Amazon Lightsail - Lightsail은 간단한 웹 애플리케이션 및 웹사이트를 호스팅하는 서비스입니다.</p>
        <p>C. AWS Storage Gateway - Storage Gateway는 온프레미스 스토리지와 AWS 클라우드 스토리지를 통합하는 서비스입니다.</p>
    </def>
</deflist>

72.<br/>**소매 회사는 새로운 전자 상거래 플랫폼을 위해 고가용성 아키텍처를 구축해야 합니다. 회사는 여러 가용 영역에 데이터를 복제하는 AWS 서비스만 사용하고 있습니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스를 사용해야 합니까? (두 가지 선택)**
- A. Amazon EC2
- B. Amazon Elastic Block Store (Amazon EBS)
- C. Amazon Aurora
- D. Amazon DynamoDB
- E. Amazon Redshift

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. Amazon Aurora - Aurora는 여러 가용 영역에 데이터를 복제하여 고가용성을 제공합니다.
        D. Amazon DynamoDB - DynamoDB는 여러 가용 영역에 데이터를 복제하여 고가용성을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon EC2 - EC2는 인스턴스 수준에서 고가용성을 제공하지만, 데이터 복제 기능은 없습니다.</p>
        <p>B. Amazon Elastic Block Store (Amazon EBS) - EBS는 단일 가용 영역에 데이터를 저장합니다.</p>
        <p>E. Amazon Redshift - Redshift는 데이터 웨어하우스 서비스로, 고가용성 아키텍처와는 관련이 없습니다.</p>
    </def>
</deflist>

73.<br/>**AWS 클라우드의 어떤 특성이 사용자가 사용되지 않는 CPU 용량을 제거하는 데 도움이 됩니까?**
- A. 민첩성
- B. 탄력성
- C. 신뢰성
- D. 내구성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 탄력성 - 탄력성은 리소스를 자동으로 확장하거나 축소하여 사용되지 않는 CPU 용량을 제거하는 데 도움이 됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 민첩성 - 민첩성은 빠른 배포와 변경에 대한 능력을 의미합니다.</p>
        <p>C. 신뢰성 - 신뢰성은 시스템의 가용성과 복원력을 의미합니다.</p>
        <p>D. 내구성 - 내구성은 데이터의 장기적인 보존을 의미합니다.</p>
    </def>
</deflist>

74.<br/>**서비스 제어 정책(SCP)은 다음 중 무엇에 대한 권한을 관리합니까?**
- A. 가용 영역
- B. AWS 리전
- C. AWS Organizations
- D. 엣지 로케이션

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Organizations - SCP는 AWS Organizations 내의 계정에 대한 권한을 관리합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 가용 영역 - SCP는 가용 영역에 대한 권한을 관리하지 않습니다.</p>
        <p>B. AWS 리전 - SCP는 AWS 리전에 대한 권한을 관리하지 않습니다.</p>
        <p>D. 엣지 로케이션 - SCP는 엣지 로케이션에 대한 권한을 관리하지 않습니다.</p>
    </def>
</deflist>

75.<br/>**어떤 AWS 서비스를 사용하여 저장된 데이터를 암호화할 수 있습니까?**
- A. Amazon GuardDuty
- B. AWS Shield
- C. AWS Security Hub
- D. AWS Key Management Service (AWS KMS)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS Key Management Service (AWS KMS) - KMS는 저장된 데이터를 암호화하는 데 사용됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon GuardDuty - GuardDuty는 위협 탐지 서비스입니다.</p>
        <p>B. AWS Shield - Shield는 DDoS 공격으로부터 보호하는 서비스입니다.</p>
        <p>C. AWS Security Hub - Security Hub는 보안 상태를 중앙에서 관리하는 서비스입니다.</p>
    </def>
</deflist>

76.<br/>**AWS 클라우드를 사용하는 것의 장점은 무엇입니까? (두 가지 선택)**
- A. 모든 AWS 서비스에 대해 100% 서비스 수준 계약(SLA)
- B. 필요에 따라 조정되는 컴퓨팅 용량
- C. 코드 개발을 위한 AWS 지원의 가용성
- D. 향상된 보안
- E. 비용 및 복잡성 증가

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 필요에 따라 조정되는 컴퓨팅 용량 - AWS 클라우드는 필요에 따라 컴퓨팅 용량을 조정할 수 있습니다.
        D. 향상된 보안 - AWS 클라우드는 다양한 보안 기능을 제공하여 데이터를 보호합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 모든 AWS 서비스에 대해 100% 서비스 수준 계약(SLA) - AWS는 100% SLA를 제공하지 않습니다.</p>
        <p>C. 코드 개발을 위한 AWS 지원의 가용성 - AWS 지원은 코드 개발을 직접 지원하지 않습니다.</p>
        <p>E. 비용 및 복잡성 증가 - AWS 클라우드는 비용 및 복잡성을 증가시키지 않습니다.</p>
    </def>
</deflist>

77.<br/>**사용자가 Amazon S3에 객체를 저장하고 있습니다. 사용자는 규정 준수를 위해 객체에 대한 액세스를 제한해야 합니다. 이 요구 사항을 충족하기 위해 사용자는 무엇을 해야 합니까?**
- A. AWS Secrets Manager 사용
- B. S3 버킷의 객체에 태그 지정
- C. 보안 그룹 사용
- D. 네트워크 ACL 사용

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 보안 그룹 사용 - 보안 그룹은 인스턴스 수준에서 트래픽을 제어합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Secrets Manager 사용 - Secrets Manager는 비밀을 관리하는 서비스로, S3 객체 액세스 제한과는 관련이 없습니다.</p>
        <p>B. S3 버킷의 객체에 태그 지정 - 태그 지정은 객체를 분류하는 데 사용되며, 액세스 제한과는 관련이 없습니다.</p>
        <p>D. 네트워크 ACL 사용 - 네트워크 ACL은 서브넷 수준에서 트래픽을 제어합니다.</p>
    </def>
</deflist>

78.<br/>**회사는 비디오 파일과 오디오 파일을 원본 형식에서 스마트폰, 태블릿 및 웹 브라우저에서 재생할 수 있는 형식으로 변환하려고 합니다. 이 요구 사항을 충족하는 AWS 서비스는 무엇입니까?**
- A. Amazon Elastic Transcoder
- B. Amazon Comprehend
- C. AWS Glue
- D. Amazon Rekognition

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. Amazon Elastic Transcoder - Elastic Transcoder는 비디오 및 오디오 파일을 다양한 형식으로 변환할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. Amazon Comprehend - Comprehend는 자연어 처리를 위한 서비스입니다.</p>
        <p>C. AWS Glue - Glue는 데이터 통합 서비스입니다.</p>
        <p>D. Amazon Rekognition - Rekognition은 이미지 및 비디오 분석 서비스입니다.</p>
    </def>
</deflist>

79.<br/>**다음 중 Amazon EC2 Auto Scaling의 이점은 무엇입니까? (두 가지 선택)**
- A. 애플리케이션의 건강 및 가용성 향상
- B. 네트워크 지연 시간 감소
- C. 성능 및 비용 최적화
- D. 데이터의 자동 스냅샷
- E. 리전 간 복제

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 애플리케이션의 건강 및 가용성 향상 - Auto Scaling은 애플리케이션의 건강 및 가용성을 향상시킵니다.
        C. 성능 및 비용 최적화 - Auto Scaling은 리소스를 자동으로 조정하여 성능 및 비용을 최적화합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 네트워크 지연 시간 감소 - Auto Scaling은 네트워크 지연 시간과 직접적인 관련이 없습니다.</p>
        <p>D. 데이터의 자동 스냅샷 - Auto Scaling은 데이터 스냅샷 기능을 제공하지 않습니다.</p>
        <p>E. 리전 간 복제 - Auto Scaling은 리전 간 복제 기능을 제공하지 않습니다.</p>
    </def>
</deflist>

80.<br/>**회사는 여러 부서를 보유하고 있습니다. 각 부서는 애플리케이션을 위한 자체 AWS 계정을 보유하고 있습니다. 회사는 결제를 간소화하기 위해 모든 AWS 비용을 단일 청구서로 받고자 하지만, 각 부서가 발생시키는 비용을 알고 싶어합니다. 이 기능을 제공하는 AWS 도구 또는 기능은 무엇입니까?**
- A. AWS 비용 및 사용 보고서
- B. 통합 청구
- C. 절약 계획
- D. AWS 예산

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 통합 청구 - 통합 청구는 여러 계정의 비용을 단일 청구서로 통합하고, 각 계정의 비용을 추적할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS 비용 및 사용 보고서 - 비용 및 사용 보고서는 비용 분석 도구로, 청구서를 통합하지 않습니다.</p>
        <p>C. 절약 계획 - 절약 계획은 비용 절감 옵션을 제공하지만, 청구서를 통합하지 않습니다.</p>
        <p>D. AWS 예산 - 예산은 비용을 추적하고 관리하는 도구로, 청구서를 통합하지 않습니다.</p>
    </def>
</deflist>

81.<br/>**회사는 온프레미스에서 워크로드를 실행하고 있습니다. 회사는 AWS에서 대규모 애플리케이션을 실행하는 비용을 예측하고자 합니다. 이 정보를 얻기 위해 회사는 어떤 AWS 서비스 또는 도구를 사용해야 합니까?**
- A. AWS Pricing Calculator
- B. AWS Budgets
- C. AWS Trusted Advisor
- D. Cost Explorer

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. AWS Pricing Calculator - Pricing Calculator는 AWS 서비스의 비용을 예측하는 데 사용됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. AWS Budgets - Budgets는 비용을 추적하고 관리하는 도구입니다.</p>
        <p>C. AWS Trusted Advisor - Trusted Advisor는 비용 최적화, 보안, 성능 및 장애 복구에 대한 권장 사항을 제공합니다.</p>
        <p>D. Cost Explorer - Cost Explorer는 비용 분석 도구로, 예측 기능은 제한적입니다.</p>
    </def>
</deflist>

82.<br/>**회사는 배포 전에 인프라 용량을 추측할 필요를 없애고자 합니다. 또한, 회사는 리소스를 사용하는 만큼만 클라우드 리소스에 예산을 지출하고자 합니다. AWS 클라우드의 어떤 장점이 회사의 요구 사항과 일치합니까?**
- A. 신뢰성
- B. 글로벌 도달 범위
- C. 규모의 경제
- D. 사용한 만큼 지불하는 요금제

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 사용한 만큼 지불하는 요금제 - AWS 클라우드는 사용한 만큼만 비용을 지불하는 요금제를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 신뢰성 - 신뢰성은 시스템의 가용성과 복원력을 의미합니다.</p>
        <p>B. 글로벌 도달 범위 - 글로벌 도달 범위는 전 세계적으로 서비스를 제공하는 능력을 의미합니다.</p>
        <p>C. 규모의 경제 - 규모의 경제는 대규모 사용자 기반을 통해 비용을 절감하는 것을 의미합니다.</p>
    </def>
</deflist>

83.<br/>**어떤 AWS 서비스가 하이브리드 아키텍처를 지원하여 사용자가 AWS 인프라, AWS 서비스, API 및 도구를 데이터 센터, 공동 위치 환경 또는 온프레미스 시설로 확장할 수 있게 합니까?**
- A. AWS Snowmobile
- B. AWS Local Zones
- C. AWS Outposts
- D. AWS Fargate

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Outposts - Outposts는 AWS 인프라, 서비스, API 및 도구를 온프레미스 환경으로 확장할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Snowmobile - Snowmobile은 대규모 데이터 전송을 위한 서비스입니다.</p>
        <p>B. AWS Local Zones - Local Zones는 특정 지리적 위치에서 지연 시간을 줄이는 데 사용됩니다.</p>
        <p>D. AWS Fargate - Fargate는 컨테이너 호스트를 프로비저닝하고 관리할 필요 없이 Docker 컨테이너를 실행할 수 있습니다.</p>
    </def>
</deflist>

84.<br/>**회사는 데이터 백업을 저장하기 위해 물리적 테이프 라이브러리를 보유하고 있습니다. 테이프 라이브러리가 공간이 부족해지고 있습니다. 회사는 테이프 라이브러리의 용량을 AWS 클라우드로 확장해야 합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스를 사용해야 합니까?**
- A. Amazon Elastic Block Store (Amazon EBS)
- B. Amazon S3
- C. Amazon Elastic File System (Amazon EFS)
- D. AWS Storage Gateway

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS Storage Gateway - Storage Gateway는 온프레미스 테이프 라이브러리를 AWS 클라우드로 확장할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Elastic Block Store (Amazon EBS) - EBS는 블록 스토리지 서비스입니다.</p>
        <p>B. Amazon S3 - S3는 객체 스토리지 서비스입니다.</p>
        <p>C. Amazon Elastic File System (Amazon EFS) - EFS는 파일 스토리지 서비스입니다.</p>
    </def>
</deflist>

85.<br/>**온라인 소매 회사는 연중 여러 번, 주로 휴일 동안 계절적 판매 급증을 경험합니다. 다른 시기에는 수요가 낮습니다. 회사는 각 시즌의 인프라 수요 증가를 예측하기 어렵습니다. AWS 클라우드로 이동하는 것이 회사에 가장 큰 이점을 제공하는 이유는 무엇입니까? (두 가지 선택)**
- A. 글로벌 도달 범위
- B. 탄력성
- C. AWS 서비스 할당량
- D. AWS 공유 책임 모델
- E. 사용한 만큼 지불하는 요금제

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 탄력성 - AWS 클라우드는 필요에 따라 리소스를 자동으로 확장하거나 축소할 수 있습니다.
        E. 사용한 만큼 지불하는 요금제 - AWS 클라우드는 사용한 만큼만 비용을 지불하는 요금제를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 글로벌 도달 범위 - 글로벌 도달 범위는 전 세계적으로 서비스를 제공하는 능력을 의미합니다.</p>
        <p>C. AWS 서비스 할당량 - 서비스 할당량은 리소스 사용 제한을 의미합니다.</p>
        <p>D. AWS 공유 책임 모델 - 공유 책임 모델은 보안 및 규정 준수를 다룹니다.</p>
    </def>
</deflist>

86.<br/>**어떤 AWS 서비스를 사용하여 텍스트를 생동감 있는 음성으로 변환할 수 있습니까?**
- A. Amazon Polly
- B. Amazon Kendra
- C. Amazon Rekognition
- D. Amazon Connect

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. Amazon Polly - Polly는 텍스트를 생동감 있는 음성으로 변환할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. Amazon Kendra - Kendra는 지능형 검색 서비스입니다.</p>
        <p>C. Amazon Rekognition - Rekognition은 이미지 및 비디오 분석 서비스입니다.</p>
        <p>D. Amazon Connect - Connect는 클라우드 기반 연락 센터 서비스입니다.</p>
    </def>
</deflist>

87.<br/>**어떤 AWS 서비스 또는 도구를 사용하여 Amazon VPC의 인바운드 및 아웃바운드 트래픽에 대한 정보를 캡처할 수 있습니까?**
- A. VPC Flow Logs
- B. Amazon Inspector
- C. VPC 엔드포인트 서비스
- D. NAT 게이트웨이

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. VPC Flow Logs - VPC Flow Logs는 VPC의 인바운드 및 아웃바운드 트래픽에 대한 정보를 캡처할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. Amazon Inspector - Inspector는 보안 취약성을 평가하는 도구입니다.</p>
        <p>C. VPC 엔드포인트 서비스 - VPC 엔드포인트 서비스는 VPC와 AWS 서비스 간의 프라이빗 연결을 제공합니다.</p>
        <p>D. NAT 게이트웨이 - NAT 게이트웨이는 프라이빗 서브넷의 인스턴스가 인터넷에 액세스할 수 있도록 합니다.</p>
    </def>
</deflist>

88.<br/>**회사는 두 개의 Amazon EC2 인스턴스가 최소한의 통신 지연 시간으로 별도의 데이터 센터에 있도록 하려고 합니다. 이 요구 사항을 충족하기 위해 회사는 어떻게 해야 합니까?**
- A. 두 개의 EC2 인스턴스를 VPC 피어링 연결로 연결된 두 개의 별도 AWS 리전에 배치합니다.
- B. 두 개의 EC2 인스턴스를 동일한 AWS 리전 내의 두 개의 별도 가용 영역에 배치합니다.
- C. 하나의 EC2 인스턴스를 온프레미스에 배치하고 다른 하나를 AWS 리전에 배치한 다음 AWS VPN 연결을 사용하여 연결합니다.
- D. 두 개의 EC2 인스턴스를 전용 대역폭을 위한 배치 그룹에 배치합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 두 개의 EC2 인스턴스를 동일한 AWS 리전 내의 두 개의 별도 가용 영역에 배치합니다. - 동일한 리전 내의 가용 영역 간에는 낮은 지연 시간으로 통신할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 두 개의 EC2 인스턴스를 VPC 피어링 연결로 연결된 두 개의 별도 AWS 리전에 배치합니다. - 리전 간 통신은 지연 시간이 더 길 수 있습니다.</p>
        <p>C. 하나의 EC2 인스턴스를 온프레미스에 배치하고 다른 하나를 AWS 리전에 배치한 다음 AWS VPN 연결을 사용하여 연결합니다. - 온프레미스와 AWS 간의 통신은 지연 시간이 더 길 수 있습니다.</p>
        <p>D. 두 개의 EC2 인스턴스를 전용 대역폭을 위한 배치 그룹에 배치합니다. - 배치 그룹은 동일한 가용 영역 내에서만 작동합니다.</p>
    </def>
</deflist>

89.<br/>**회사는 어떤 상황에서 IAM 역할 대신 IAM 사용자를 생성해야 합니까? (두 가지 선택)**
- A. Amazon EC2 인스턴스에서 실행되는 애플리케이션이 다른 AWS 서비스에 액세스해야 할 때
- B. 회사가 개인을 위한 AWS 액세스 자격 증명을 생성할 때
- C. 회사가 AWS에 요청을 하는 모바일 애플리케이션을 생성할 때
- D. 회사가 IAM 그룹에 사용자를 추가해야 할 때
- E. 사용자가 회사 네트워크에서 인증되고 두 번째로 로그인하지 않고 AWS를 사용하려고 할 때

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 회사가 개인을 위한 AWS 액세스 자격 증명을 생성할 때 - IAM 사용자는 개인을 위한 자격 증명을 제공합니다.
        D. 회사가 IAM 그룹에 사용자를 추가해야 할 때 - IAM 사용자는 그룹에 추가될 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon EC2 인스턴스에서 실행되는 애플리케이션이 다른 AWS 서비스에 액세스해야 할 때 - 이 경우 IAM 역할을 사용하는 것이 좋습니다.</p>
        <p>C. 회사가 AWS에 요청을 하는 모바일 애플리케이션을 생성할 때 - 이 경우 IAM 역할을 사용하는 것이 좋습니다.</p>
        <p>E. 사용자가 회사 네트워크에서 인증되고 두 번째로 로그인하지 않고 AWS를 사용하려고 할 때 - 이 경우 IAM 역할을 사용하는 것이 좋습니다.</p>
    </def>
</deflist>

90.<br/>**회사는 자주 변경되는 데이터를 읽고 쓰기 위해 어떤 AWS 서비스를 사용해야 합니까? (두 가지 선택)**
- A. Amazon S3 Glacier
- B. Amazon RDS
- C. AWS Snowball
- D. Amazon Redshift
- E. Amazon Elastic File System (Amazon EFS)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Amazon RDS - RDS는 자주 변경되는 데이터를 읽고 쓸 수 있는 관계형 데이터베이스 서비스입니다.
        E. Amazon Elastic File System (Amazon EFS) - EFS는 자주 변경되는 데이터를 읽고 쓸 수 있는 파일 스토리지 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon S3 Glacier - Glacier는 장기 데이터 보관을 위한 서비스로, 자주 변경되는 데이터와는 관련이 없습니다.</p>
        <p>C. AWS Snowball - Snowball은 대규모 데이터 전송을 위한 서비스입니다.</p>
        <p>D. Amazon Redshift - Redshift는 데이터 웨어하우스 서비스로, 자주 변경되는 데이터와는 관련이 없습니다.</p>
    </def>
</deflist>

91.<br/>**어떤 AWS 서비스가 Amazon EBS에 대한 암호화를 제공합니까?**
- A. AWS Certificate Manager
- B. AWS Systems Manager
- C. AWS KMS
- D. AWS Config

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS KMS - AWS Key Management Service (KMS)는 Amazon EBS에 대한 암호화를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Certificate Manager - Certificate Manager는 SSL/TLS 인증서를 관리합니다.</p>
        <p>B. AWS Systems Manager - Systems Manager는 인프라 관리를 돕는 도구입니다.</p>
        <p>D. AWS Config - Config는 리소스 구성을 추적하고 관리하는 도구입니다.</p>
    </def>
</deflist>

92.<br/>**어떤 AWS 서비스가 글로벌 엣지 로케이션을 사용합니까? (두 가지 선택)**
- A. AWS Fargate
- B. Amazon CloudFront
- C. AWS Global Accelerator
- D. AWS Wavelength
- E. Amazon VPC

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Amazon CloudFront - CloudFront는 글로벌 엣지 로케이션을 사용하여 콘텐츠를 전송합니다.
        C. AWS Global Accelerator - Global Accelerator는 글로벌 엣지 로케이션을 사용하여 애플리케이션의 가용성과 성능을 개선합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Fargate - Fargate는 컨테이너 호스트를 프로비저닝하고 관리할 필요 없이 Docker 컨테이너를 실행할 수 있습니다.</p>
        <p>D. AWS Wavelength - Wavelength는 5G 네트워크 엣지에서 컴퓨팅 서비스를 제공합니다.</p>
        <p>E. Amazon VPC - VPC는 가상 네트워크를 제공합니다.</p>
    </def>
</deflist>

93.<br/>**회사는 제품을 제조하는 여러 공장을 운영하고 있습니다. 회사는 데이터를 처리하고 저장하며, 로컬 시스템 상호 의존성이 있는 애플리케이션을 실행할 수 있는 능력이 필요합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스를 사용해야 합니까?**
- A. AWS IoT Greengrass
- B. AWS Lambda
- C. AWS Outposts
- D. AWS Snowball Edge

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Outposts - Outposts는 로컬 시스템 상호 의존성이 있는 애플리케이션을 실행하고 데이터를 처리 및 저장할 수 있는 능력을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS IoT Greengrass - IoT Greengrass는 엣지 디바이스에서 로컬 컴퓨팅, 메시징, 데이터 캐싱 및 동기화를 제공합니다.</p>
        <p>B. AWS Lambda - Lambda는 서버리스 컴퓨팅 서비스를 제공합니다.</p>
        <p>D. AWS Snowball Edge - Snowball Edge는 대규모 데이터 전송을 위한 서비스입니다.</p>
    </def>
</deflist>

94.<br/>**다음 중 AWS 클라우드 아키텍처에 대한 권장 설계 원칙은 무엇입니까?**
- A. 구성 요소를 긴밀하게 결합하여 설계합니다.
- B. 모든 애플리케이션 기능을 처리할 수 있는 단일 애플리케이션 구성 요소를 빌드합니다.
- C. 실패 가능성을 줄이기 위해 더 적은 반복으로 큰 변경을 만듭니다.
- D. 워크로드를 분할하여 모놀리식 아키텍처를 피합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 워크로드를 분할하여 모놀리식 아키텍처를 피합니다. - 모놀리식 아키텍처를 피하고 워크로드를 분할하는 것이 권장됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 구성 요소를 긴밀하게 결합하여 설계합니다. - 구성 요소를 느슨하게 결합하는 것이 권장됩니다.</p>
        <p>B. 모든 애플리케이션 기능을 처리할 수 있는 단일 애플리케이션 구성 요소를 빌드합니다. - 단일 구성 요소 대신 여러 구성 요소로 분할하는 것이 권장됩니다.</p>
        <p>C. 실패 가능성을 줄이기 위해 더 적은 반복으로 큰 변경을 만듭니다. - 작은 변경을 자주 하는 것이 권장됩니다.</p>
    </def>
</deflist>

95.<br/>**회사는 AWS 워크로드를 설계하여 구성 요소를 정기적으로 업데이트하고 작은 가역적인 증분으로 변경할 수 있도록 하고 있습니다. 이 설계는 AWS Well-Architected Framework의 어떤 기둥을 지원합니까?**
- A. 보안
- B. 성능 효율성
- C. 운영 우수성
- D. 신뢰성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 운영 우수성 - 운영 우수성 기둥은 정기적인 업데이트와 작은 가역적인 증분으로 변경하는 것을 포함합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 보안 - 보안 기둥은 데이터 보호 및 시스템 보안을 다룹니다.</p>
        <p>B. 성능 효율성 - 성능 효율성 기둥은 리소스 사용을 최적화하여 시스템 성능을 향상시키는 것을 다룹니다.</p>
        <p>D. 신뢰성 - 신뢰성 기둥은 시스템의 가용성과 복원력을 다룹니다.</p>
    </def>
</deflist>

96.<br/>**다음 중 인스턴스 수준의 방화벽으로 작동하여 인바운드 및 아웃바운드 액세스를 제어하는 것은 무엇입니까?**
- A. 네트워크 액세스 제어 목록
- B. 보안 그룹
- C. AWS Trusted Advisor
- D. 가상 프라이빗 게이트웨이

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 보안 그룹 - 보안 그룹은 인스턴스 수준의 방화벽으로 인바운드 및 아웃바운드 트래픽을 제어합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 네트워크 액세스 제어 목록 - 네트워크 ACL은 서브넷 수준에서 트래픽을 제어합니다.</p>
        <p>C. AWS Trusted Advisor - Trusted Advisor는 비용 최적화, 보안, 성능 및 장애 복구에 대한 권장 사항을 제공합니다.</p>
        <p>D. 가상 프라이빗 게이트웨이 - 가상 프라이빗 게이트웨이는 VPC와 온프레미스 네트워크 간의 연결을 제공합니다.</p>
    </def>
</deflist>

97.<br/>**회사는 1년 동안 계속 실행될 워크로드를 보유하고 있습니다. 워크로드는 서비스 중단을 허용할 수 없습니다. 가장 비용 효율적인 Amazon EC2 구매 옵션은 무엇입니까?**
- A. 전액 선결제 예약 인스턴스
- B. 부분 선결제 예약 인스턴스
- C. 전용 인스턴스
- D. 온디맨드 인스턴스

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 전액 선결제 예약 인스턴스 - 전액 선결제 예약 인스턴스는 장기적으로 가장 비용 효율적입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 부분 선결제 예약 인스턴스 - 부분 선결제 예약 인스턴스는 전액 선결제보다 비용이 더 높을 수 있습니다.</p>
        <p>C. 전용 인스턴스 - 전용 인스턴스는 특정 요구 사항이 있는 경우에 사용됩니다.</p>
        <p>D. 온디맨드 인스턴스 - 온디맨드 인스턴스는 장기적으로 비용이 더 높을 수 있습니다.</p>
    </def>
</deflist>

98.<br/>**어떤 AWS 서비스가 DDoS 공격으로부터 보호하는 데 도움을 줍니까?**
- A. AWS Shield
- B. Amazon Inspector
- C. Amazon GuardDuty
- D. Amazon Detective

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. AWS Shield - AWS Shield는 DDoS 공격으로부터 보호하는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. Amazon Inspector - Inspector는 보안 취약성을 평가하는 도구입니다.</p>
        <p>C. Amazon GuardDuty - GuardDuty는 위협 탐지 서비스입니다.</p>
        <p>D. Amazon Detective - Detective는 보안 조사 및 분석 도구입니다.</p>
    </def>
</deflist>

99.<br/>**AWS Config를 사용하여 AWS 리소스에 대한 변경 사항을 기록, 감사 및 평가하여 추적 가능성을 제공하는 것은 AWS Well-Architected Framework의 어떤 기둥의 예입니까?**
- A. 보안
- B. 운영 우수성
- C. 성능 효율성
- D. 비용 최적화

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 보안 - 보안 기둥은 데이터 보호 및 시스템 보안을 다룹니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 운영 우수성 - 운영 우수성 기둥은 운영 프로세스의 최적화를 다룹니다.</p>
        <p>C. 성능 효율성 - 성능 효율성 기둥은 리소스 사용을 최적화하여 시스템 성능을 향상시키는 것을 다룹니다.</p>
        <p>D. 비용 최적화 - 비용 최적화 기둥은 비용을 절감하고 효율적으로 리소스를 사용하는 것을 다룹니다.</p>
    </def>
</deflist>

100.<br/>**어떤 AWS 도구 또는 기능이 서브넷 수준에서 VPC 방화벽으로 작동합니까?**
- A. 보안 그룹
- B. 네트워크 ACL
- C. 트래픽 미러링
- D. 인터넷 게이트웨이

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 네트워크 ACL - 네트워크 ACL은 서브넷 수준에서 VPC 방화벽으로 작동합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 보안 그룹 - 보안 그룹은 인스턴스 수준에서 트래픽을 제어합니다.</p>
        <p>C. 트래픽 미러링 - 트래픽 미러링은 네트워크 트래픽을 캡처하고 분석하는 데 사용됩니다.</p>
        <p>D. 인터넷 게이트웨이 - 인터넷 게이트웨이는 VPC와 인터넷 간의 연결을 제공합니다.</p>
    </def>
</deflist>

101.<br/>**어떤 AWS 서비스를 사용하여 애플리케이션을 디커플링할 수 있습니까?**
- A. AWS Config
- B. Amazon Simple Queue Service (Amazon SQS)
- C. AWS Batch
- D. Amazon Simple Email Service (Amazon SES)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Amazon Simple Queue Service (Amazon SQS) - SQS는 메시지 큐를 사용하여 애플리케이션을 디커플링할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Config - Config는 리소스 구성을 추적하고 관리하는 도구입니다.</p>
        <p>C. AWS Batch - Batch는 배치 컴퓨팅 작업을 관리하는 서비스입니다.</p>
        <p>D. Amazon Simple Email Service (Amazon SES) - SES는 이메일 전송 서비스입니다.</p>
    </def>
</deflist>

102.<br/>**가장 저렴한 재해 복구 옵션은 무엇입니까?**
- A. 웜 스탠바이
- B. 멀티사이트
- C. 백업 및 복원
- D. 파일럿 라이트

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 백업 및 복원 - 백업 및 복원은 가장 저렴한 재해 복구 옵션입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 웜 스탠바이 - 웜 스탠바이는 백업 및 복원보다 비용이 더 많이 들 수 있습니다.</p>
        <p>B. 멀티사이트 - 멀티사이트는 가장 비용이 많이 드는 옵션 중 하나입니다.</p>
        <p>D. 파일럿 라이트 - 파일럿 라이트는 백업 및 복원보다 비용이 더 많이 들 수 있습니다.</p>
    </def>
</deflist>

103.<br/>**어떤 유형의 AWS 스토리지는 일시적이며 Amazon EC2 인스턴스가 중지되거나 종료될 때 삭제됩니까?**
- A. Amazon Elastic Block Store (Amazon EBS)
- B. Amazon EC2 인스턴스 스토어
- C. Amazon Elastic File System (Amazon EFS)
- D. Amazon S3

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Amazon EC2 인스턴스 스토어 - 인스턴스 스토어는 일시적이며 인스턴스가 중지되거나 종료될 때 삭제됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Elastic Block Store (Amazon EBS) - EBS는 인스턴스가 중지되거나 종료되어도 데이터를 유지합니다.</p>
        <p>C. Amazon Elastic File System (Amazon EFS) - EFS는 네트워크 파일 시스템으로 데이터를 유지합니다.</p>
        <p>D. Amazon S3 - S3는 객체 스토리지로 데이터를 유지합니다.</p>
    </def>
</deflist>

104.<br/>**다음 중 AWS 계정 루트 사용자의 특성은 무엇입니까?**
- A. 루트 사용자는 MFA(다중 인증)를 구성할 수 있는 유일한 사용자입니다.
- B. 루트 사용자는 AWS Management Console에 액세스할 수 있는 유일한 사용자입니다.
- C. 루트 사용자는 AWS 계정이 생성될 때 사용할 수 있는 첫 번째 로그인 ID입니다.
- D. 루트 사용자의 비밀번호는 변경할 수 없습니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 루트 사용자는 AWS 계정이 생성될 때 사용할 수 있는 첫 번째 로그인 ID입니다. - 루트 사용자는 계정 생성 시 처음으로 제공되는 로그인 ID입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 루트 사용자는 MFA(다중 인증)를 구성할 수 있는 유일한 사용자입니다. - 다른 사용자도 MFA를 구성할 수 있습니다.</p>
        <p>B. 루트 사용자는 AWS Management Console에 액세스할 수 있는 유일한 사용자입니다. - 다른 사용자도 콘솔에 액세스할 수 있습니다.</p>
        <p>D. 루트 사용자의 비밀번호는 변경할 수 없습니다. - 루트 사용자의 비밀번호는 변경할 수 있습니다.</p>
    </def>
</deflist>

105.<br/>**회사는 Amazon EC2 인스턴스에서 애플리케이션을 호스팅하고 있습니다. EC2 인스턴스는 Amazon S3 및 Amazon DynamoDB를 포함한 여러 AWS 리소스에 액세스해야 합니다. 권한을 위임하는 가장 운영 효율적인 솔루션은 무엇입니까?**
- A. 필요한 권한이 있는 IAM 역할을 생성하고 해당 역할을 EC2 인스턴스에 연결합니다.
- B. IAM 사용자를 생성하고 애플리케이션에서 해당 사용자의 액세스 키와 비밀 액세스 키를 사용합니다.
- C. IAM 사용자를 생성하고 해당 사용자의 액세스 키와 비밀 액세스 키를 사용하여 EC2 인스턴스에서 CLI 프로필을 생성합니다.
- D. 필요한 권한이 있는 IAM 역할을 생성하고 해당 역할을 관리 IAM 사용자에 연결합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 필요한 권한이 있는 IAM 역할을 생성하고 해당 역할을 EC2 인스턴스에 연결합니다. - IAM 역할을 사용하면 애플리케이션이 안전하게 AWS 리소스에 액세스할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. IAM 사용자를 생성하고 애플리케이션에서 해당 사용자의 액세스 키와 비밀 액세스 키를 사용합니다. - 이 방법은 보안 위험이 있을 수 있습니다.</p>
        <p>C. IAM 사용자를 생성하고 해당 사용자의 액세스 키와 비밀 액세스 키를 사용하여 EC2 인스턴스에서 CLI 프로필을 생성합니다. - 이 방법은 보안 위험이 있을 수 있습니다.</p>
        <p>D. 필요한 권한이 있는 IAM 역할을 생성하고 해당 역할을 관리 IAM 사용자에 연결합니다. - 역할을 EC2 인스턴스에 직접 연결하는 것이 더 효율적입니다.</p>
    </def>
</deflist>

106.<br/>**다음 중 AWS 글로벌 인프라의 구성 요소는 무엇입니까?**
- A. Amazon Alexa
- B. AWS 리전
- C. Amazon Lightsail
- D. AWS Organizations

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS 리전 - AWS 리전은 AWS 글로벌 인프라의 구성 요소입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Alexa - Alexa는 음성 인식 서비스입니다.</p>
        <p>C. Amazon Lightsail - Lightsail은 간단한 웹 애플리케이션 및 웹사이트를 호스팅하는 서비스입니다.</p>
        <p>D. AWS Organizations - Organizations는 여러 AWS 계정을 중앙에서 관리하는 도구입니다.</p>
    </def>
</deflist>

107.<br/>**VPC 내에서 인터넷 게이트웨이를 사용하는 목적은 무엇입니까?**
- A. VPC에 VPN 연결을 생성하기 위해
- B. VPC와 인터넷 간의 통신을 허용하기 위해
- C. 인터넷 트래픽에 대역폭 제한을 부과하기 위해
- D. 인터넷에서 Amazon EC2 인스턴스로의 트래픽을 로드 밸런싱하기 위해

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. VPC와 인터넷 간의 통신을 허용하기 위해 - 인터넷 게이트웨이는 VPC와 인터넷 간의 통신을 허용합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. VPC에 VPN 연결을 생성하기 위해 - VPN 연결은 가상 프라이빗 게이트웨이를 사용합니다.</p>
        <p>C. 인터넷 트래픽에 대역폭 제한을 부과하기 위해 - 인터넷 게이트웨이는 대역폭 제한을 부과하지 않습니다.</p>
        <p>D. 인터넷에서 Amazon EC2 인스턴스로의 트래픽을 로드 밸런싱하기 위해 - 로드 밸런싱은 로드 밸런서를 사용합니다.</p>
    </def>
</deflist>

108.<br/>**어떤 AWS 서비스가 사용자가 AWS 인프라에 대한 보안 및 규정 준수 보고서를 온디맨드로 다운로드할 수 있도록 합니까?**
- A. Amazon GuardDuty
- B. AWS Security Hub
- C. AWS Artifact
- D. AWS Shield

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Artifact - Artifact는 보안 및 규정 준수 보고서를 온디맨드로 다운로드할 수 있도록 합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon GuardDuty - GuardDuty는 위협 탐지 서비스입니다.</p>
        <p>B. AWS Security Hub - Security Hub는 보안 상태를 중앙에서 관리하는 서비스입니다.</p>
        <p>D. AWS Shield - Shield는 DDoS 공격으로부터 보호하는 서비스입니다.</p>
    </def>
</deflist>

109.<br/>**제약 회사는 단일 AWS 리전에서 인프라를 운영하고 있습니다. 회사는 여러 AWS 계정에 수천 개의 VPC를 보유하고 있으며 이를 상호 연결하려고 합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 서비스 또는 기능을 사용해야 합니까?**
- A. VPC 엔드포인트
- B. AWS Direct Connect
- C. AWS Transit Gateway
- D. VPC 피어링

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Transit Gateway - Transit Gateway는 여러 VPC와 온프레미스 네트워크 간의 연결을 중앙에서 관리할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. VPC 엔드포인트 - VPC 엔드포인트는 VPC와 AWS 서비스 간의 프라이빗 연결을 제공합니다.</p>
        <p>B. AWS Direct Connect - Direct Connect는 온프레미스 네트워크와 AWS 간의 전용 네트워크 연결을 제공합니다.</p>
        <p>D. VPC 피어링 - VPC 피어링은 두 VPC 간의 연결을 제공합니다.</p>
    </def>
</deflist>

110.<br/>**회사는 AWS 클라우드에 인프라를 배포할 계획입니다. 배포 전에 회사는 인프라 실행 비용에 대한 견적을 원합니다. 이 정보를 제공할 수 있는 AWS 서비스 또는 기능은 무엇입니까?**
- A. Cost Explorer
- B. AWS Trusted Advisor
- C. AWS 비용 및 사용 보고서
- D. AWS Pricing Calculator

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS Pricing Calculator - Pricing Calculator는 AWS 서비스의 비용을 예측하는 데 사용됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Cost Explorer - Cost Explorer는 비용 분석 도구로, 예측 기능은 제한적입니다.</p>
        <p>B. AWS Trusted Advisor - Trusted Advisor는 비용 최적화, 보안, 성능 및 장애 복구에 대한 권장 사항을 제공합니다.</p>
        <p>C. AWS 비용 및 사용 보고서 - 비용 및 사용 보고서는 비용 분석 도구로, 예측 기능은 제한적입니다.</p>
    </def>
</deflist>

111.<br/>**중앙에서 청구를 관리하고 여러 AWS 계정 간에 리소스에 대한 제어된 액세스를 허용하는 AWS 서비스 또는 도구는 무엇입니까?**
- A. AWS Identity and Access Management (IAM)
- B. AWS Organizations
- C. Cost Explorer
- D. AWS Budgets

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS Organizations - Organizations는 중앙에서 청구를 관리하고 여러 계정 간에 리소스에 대한 제어된 액세스를 허용합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Identity and Access Management (IAM) - IAM은 사용자 및 권한을 관리합니다.</p>
        <p>C. Cost Explorer - Cost Explorer는 비용 분석 도구입니다.</p>
        <p>D. AWS Budgets - Budgets는 비용을 추적하고 관리하는 도구입니다.</p>
    </def>
</deflist>

112.<br/>**다음 중 Amazon Virtual Private Cloud (Amazon VPC) 리소스는 무엇입니까?**
- A. 객체; 액세스 제어 목록(ACL)
- B. 서브넷; 인터넷 게이트웨이
- C. 액세스 정책; 버킷
- D. 그룹; 역할

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 서브넷; 인터넷 게이트웨이 - 서브넷과 인터넷 게이트웨이는 VPC 리소스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 객체; 액세스 제어 목록(ACL) - 객체는 S3 리소스입니다.</p>
        <p>C. 액세스 정책; 버킷 - 버킷은 S3 리소스입니다.</p>
        <p>D. 그룹; 역할 - 그룹과 역할은 IAM 리소스입니다.</p>
    </def>
</deflist>

113.<br/>**회사는 특정 사용자가 AWS Management Console에 마지막으로 액세스한 시간을 식별해야 합니다. 이 정보를 제공할 AWS 서비스는 무엇입니까?**
- A. Amazon Cognito
- B. AWS CloudTrail
- C. Amazon Inspector
- D. Amazon GuardDuty

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS CloudTrail - CloudTrail은 AWS Management Console에 대한 액세스를 기록하고 추적할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Cognito - Cognito는 사용자 인증 및 관리 서비스입니다.</p>
        <p>C. Amazon Inspector - Inspector는 보안 취약성을 평가하는 도구입니다.</p>
        <p>D. Amazon GuardDuty - GuardDuty는 위협 탐지 서비스입니다.</p>
    </def>
</deflist>

114.<br/>**회사는 최신 Amazon Linux 2 Amazon Machine Image (AMI)로 Amazon EC2 인스턴스를 시작했습니다. 시스템 관리자가 EC2 인스턴스에 연결하기 위해 취할 수 있는 조치는 무엇입니까? (두 가지 선택)**
- A. Amazon EC2 Instance Connect 사용
- B. 원격 데스크톱 프로토콜 (RDP) 연결 사용
- C. AWS Batch 사용
- D. AWS Systems Manager Session Manager 사용
- E. Amazon Connect 사용

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. Amazon EC2 Instance Connect 사용 - Instance Connect는 SSH를 통해 EC2 인스턴스에 연결할 수 있습니다.
        D. AWS Systems Manager Session Manager 사용 - Session Manager는 EC2 인스턴스에 연결할 수 있는 관리 도구입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 원격 데스크톱 프로토콜 (RDP) 연결 사용 - RDP는 Windows 인스턴스에 사용됩니다.</p>
        <p>C. AWS Batch 사용 - Batch는 배치 컴퓨팅 작업을 관리하는 서비스입니다.</p>
        <p>E. Amazon Connect 사용 - Connect는 클라우드 기반 연락 센터 서비스입니다.</p>
    </def>
</deflist>

115.<br/>**회사는 고객 서비스 이메일 메시지에 대한 감정 분석을 수행하려고 합니다. 회사는 고객 서비스 참여가 긍정적이었는지 부정적이었는지 식별하고자 합니다. 이 분석을 수행하기 위해 회사는 어떤 AWS 서비스를 사용해야 합니까?**
- A. Amazon Textract
- B. Amazon Translate
- C. Amazon Comprehend
- D. Amazon Rekognition

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. Amazon Comprehend - Comprehend는 텍스트 분석 및 감정 분석을 수행할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Textract - Textract는 문서에서 텍스트를 추출하는 서비스입니다.</p>
        <p>B. Amazon Translate - Translate는 텍스트 번역 서비스입니다.</p>
        <p>D. Amazon Rekognition - Rekognition은 이미지 및 비디오 분석 서비스입니다.</p>
    </def>
</deflist>

116.<br/>**Amazon S3에서 제공하는 총 스토리지 용량은 얼마입니까?**
- A. 100MB
- B. 5 GB
- C. 5 TB
- D. 무제한

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 무제한 - Amazon S3는 무제한 스토리지 용량을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 100MB - S3는 100MB로 제한되지 않습니다.</p>
        <p>B. 5 GB - S3는 5GB로 제한되지 않습니다.</p>
        <p>C. 5 TB - S3는 5TB로 제한되지 않습니다.</p>
    </def>
</deflist>

117.<br/>**회사는 Amazon S3로 마이그레이션하고 있습니다. 회사는 온프레미스 데이터 센터에서 AWS로 60TB의 데이터를 10일 이내에 전송해야 합니다. 이 마이그레이션을 완료하기 위해 회사는 어떤 AWS 서비스를 사용해야 합니까?**
- A. Amazon S3 Glacier
- B. AWS Database Migration Service (AWS DMS)
- C. AWS Snowball
- D. AWS Direct Connect

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Snowball - Snowball은 대규모 데이터를 물리적으로 전송하는 데 사용됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon S3 Glacier - Glacier는 장기 데이터 보관을 위한 서비스입니다.</p>
        <p>B. AWS Database Migration Service (AWS DMS) - DMS는 데이터베이스 마이그레이션을 위한 서비스입니다.</p>
        <p>D. AWS Direct Connect - Direct Connect는 전용 네트워크 연결을 제공합니다.</p>
    </def>
</deflist>

118.<br/>**Amazon DynamoDB는 어떤 유형의 데이터베이스입니까?**
- A. 인메모리
- B. 관계형
- C. 키-값
- D. 그래프

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 키-값 - DynamoDB는 키-값 데이터베이스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 인메모리 - DynamoDB는 인메모리 데이터베이스가 아닙니다.</p>
        <p>B. 관계형 - DynamoDB는 관계형 데이터베이스가 아닙니다.</p>
        <p>D. 그래프 - DynamoDB는 그래프 데이터베이스가 아닙니다.</p>
    </def>
</deflist>

119.<br/>**대규모 조직이 단일 AWS 계정을 보유하고 있습니다. 단일 계정을 여러 AWS 계정으로 재구성하는 장점은 무엇입니까? (두 가지 선택)**
- A. 서로 다른 워크로드 간의 관리적 격리를 허용합니다.
- B. AWS Management Console에서 사례를 제출하여 분기별로 할인을 적용할 수 있습니다.
- C. 별도의 AWS 계정에서 Amazon S3에서 Amazon S3 Glacier로 객체를 전환하는 비용이 더 저렴합니다.
- D. 여러 계정을 보유하면 단일 계정을 대상으로 한 악의적인 활동과 관련된 위험이 줄어듭니다.
- E. Amazon QuickSight는 여러 계정에서 실행되는 환경에 대한 애플리케이션별 권장 사항을 제공하는 비용 도구에 대한 액세스를 제공합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 서로 다른 워크로드 간의 관리적 격리를 허용합니다. - 여러 계정을 사용하면 워크로드 간의 관리적 격리를 제공합니다.
        D. 여러 계정을 보유하면 단일 계정을 대상으로 한 악의적인 활동과 관련된 위험이 줄어듭니다. - 여러 계정을 사용하면 보안 위험이 줄어듭니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. AWS Management Console에서 사례를 제출하여 분기별로 할인을 적용할 수 있습니다. - 할인은 사례 제출과 관련이 없습니다.</p>
        <p>C. 별도의 AWS 계정에서 Amazon S3에서 Amazon S3 Glacier로 객체를 전환하는 비용이 더 저렴합니다. - 비용은 계정 수와 관련이 없습니다.</p>
        <p>E. Amazon QuickSight는 여러 계정에서 실행되는 환경에 대한 애플리케이션별 권장 사항을 제공하는 비용 도구에 대한 액세스를 제공합니다. - QuickSight는 비용 도구가 아닙니다.</p>
    </def>
</deflist>

120.<br/>**소매 회사는 최근 웹사이트를 AWS로 마이그레이션했습니다. 회사는 SQL 삽입 공격으로부터 보호되기를 원합니다. 웹사이트는 Application Load Balancer를 사용하여 여러 Amazon EC2 인스턴스로 트래픽을 분산합니다. SQL 삽입 공격을 차단하는 사용자 정의 규칙을 생성하는 데 사용할 수 있는 AWS 서비스 또는 기능은 무엇입니까?**
- A. 보안 그룹
- B. AWS WAF
- C. 네트워크 ACL
- D. AWS Shield

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS WAF - WAF는 웹 애플리케이션 방화벽으로, SQL 삽입 공격을 차단하는 사용자 정의 규칙을 생성할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 보안 그룹 - 보안 그룹은 인스턴스 수준에서 트래픽을 제어합니다.</p>
        <p>C. 네트워크 ACL - 네트워크 ACL은 서브넷 수준에서 트래픽을 제어합니다.</p>
        <p>D. AWS Shield - Shield는 DDoS 공격으로부터 보호하는 서비스입니다.</p>
    </def>
</deflist>

121.<br/>**어떤 AWS 서비스가 AWS 리소스의 서비스 할당량을 사전에 모니터링하고 계획할 수 있는 기능을 제공합니까?**
- A. AWS CloudTrail
- B. AWS Personal Health Dashboard
- C. AWS Trusted Advisor
- D. Amazon CloudWatch

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Trusted Advisor - Trusted Advisor는 서비스 할당량을 모니터링하고 계획할 수 있는 권장 사항을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS CloudTrail - CloudTrail은 AWS API 호출을 기록합니다.</p>
        <p>B. AWS Personal Health Dashboard - Personal Health Dashboard는 AWS 서비스의 상태를 모니터링합니다.</p>
        <p>D. Amazon CloudWatch - CloudWatch는 모니터링 및 로그 관리 도구입니다.</p>
    </def>
</deflist>

122.<br/>**온프레미스 워크로드를 AWS 클라우드로 이동할 때 사용자가 경험하는 이점은 무엇입니까?**
- A. 데이터 센터 운영 및 유지 관리 비용 제거
- B. 하드웨어 제공업체의 할인과 동일한 가격 할인
- C. 모든 운영 제어를 AWS에 분배
- D. 운영 비용 제거

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 데이터 센터 운영 및 유지 관리 비용 제거 - AWS 클라우드로 이동하면 데이터 센터 운영 및 유지 관리 비용이 제거됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 하드웨어 제공업체의 할인과 동일한 가격 할인 - AWS의 가격 할인은 하드웨어 제공업체와 다를 수 있습니다.</p>
        <p>C. 모든 운영 제어를 AWS에 분배 - 운영 제어는 여전히 고객과 AWS 간에 공유됩니다.</p>
        <p>D. 운영 비용 제거 - 운영 비용은 완전히 제거되지 않지만 줄어들 수 있습니다.</p>
    </def>
</deflist>

123.<br/>**AWS Well-Architected Framework의 운영 우수성 기둥에 포함된 설계 원칙은 무엇입니까?**
- A. 주석이 달린 문서 작성
- B. 실패 예상
- C. 성능 효율성 보장
- D. 비용 최적화

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 주석이 달린 문서 작성 - 운영 우수성 기둥에는 주석이 달린 문서 작성이 포함됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 실패 예상 - 실패 예상은 신뢰성 기둥에 포함됩니다.</p>
        <p>C. 성능 효율성 보장 - 성능 효율성 보장은 성능 효율성 기둥에 포함됩니다.</p>
        <p>D. 비용 최적화 - 비용 최적화는 비용 최적화 기둥에 포함됩니다.</p>
    </def>
</deflist>

124.<br/>**인터넷을 통해 트래픽을 보내지 않기 위해 게이트웨이 VPC 엔드포인트를 제공하는 AWS 서비스는 무엇입니까? (두 가지 선택)**
- A. Amazon Simple Notification Service (Amazon SNS)
- B. Amazon Simple Queue Service (Amazon SQS)
- C. AWS CodeBuild
- D. Amazon S3
- E. Amazon DynamoDB

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. Amazon S3 - S3는 게이트웨이 VPC 엔드포인트를 제공합니다.
        E. Amazon DynamoDB - DynamoDB는 게이트웨이 VPC 엔드포인트를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon Simple Notification Service (Amazon SNS) - SNS는 게이트웨이 VPC 엔드포인트를 제공하지 않습니다.</p>
        <p>B. Amazon Simple Queue Service (Amazon SQS) - SQS는 게이트웨이 VPC 엔드포인트를 제공하지 않습니다.</p>
        <p>C. AWS CodeBuild - CodeBuild는 게이트웨이 VPC 엔드포인트를 제공하지 않습니다.</p>
    </def>
</deflist>

125.<br/>**AWS 공유 책임 모델에 따라 고객이 업데이트 및 패치를 책임지는 항목은 무엇입니까?**
- A. Amazon FSx for Windows File Server
- B. Amazon WorkSpaces 가상 Windows 데스크탑
- C. AWS Directory Service for Microsoft Active Directory
- D. Amazon RDS for Microsoft SQL Server

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Amazon WorkSpaces 가상 Windows 데스크탑 - 고객은 WorkSpaces 가상 데스크탑의 업데이트 및 패치를 책임집니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon FSx for Windows File Server - FSx는 AWS가 관리합니다.</p>
        <p>C. AWS Directory Service for Microsoft Active Directory - Directory Service는 AWS가 관리합니다.</p>
        <p>D. Amazon RDS for Microsoft SQL Server - RDS는 AWS가 관리합니다.</p>
    </def>
</deflist>

126.<br/>**AWS 공유 책임 모델에 따라 Amazon EC2 인스턴스의 호스트 운영 체제를 패치할 책임이 있는 사람은 누구입니까?**
- A. AWS와 고객 모두
- B. 고객만
- C. EC2 하드웨어 제조업체
- D. AWS만

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 고객만 - 고객은 EC2 인스턴스의 호스트 운영 체제를 패치할 책임이 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS와 고객 모두 - AWS는 인프라를 관리하지만, 호스트 운영 체제 패치는 고객의 책임입니다.</p>
        <p>C. EC2 하드웨어 제조업체 - 하드웨어 제조업체는 운영 체제 패치와 관련이 없습니다.</p>
        <p>D. AWS만 - AWS는 인프라를 관리하지만, 호스트 운영 체제 패치는 고객의 책임입니다.</p>
    </def>
</deflist>

127.<br/>**회사는 AWS 클라우드에 배포된 애플리케이션을 위해 Amazon RDS DB 인스턴스를 사용하고 있습니다. 회사는 DB 인스턴스가 실행되는 서버의 운영 체제를 정기적으로 패치해야 합니다. AWS 공유 책임 모델에 따라 이 상황에서 회사의 책임은 무엇입니까?**
- A. 지원 사례를 열어 회사가 DB 인스턴스 운영 체제를 패치할 수 있도록 서버에 대한 관리 액세스를 얻습니다.
- B. 지원 사례를 열어 AWS에 DB 인스턴스 운영 체제를 패치하도록 요청합니다.
- C. 서버에 대한 관리 액세스를 사용하고, DB 인스턴스에 대해 정의된 정기 유지 관리 창 동안 운영 체제 패치를 적용합니다.
- D. AWS에 DB 인스턴스 운영 체제를 패치할 시간을 알려주는 정기 유지 관리 창을 설정합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS에 DB 인스턴스 운영 체제를 패치할 시간을 알려주는 정기 유지 관리 창을 설정합니다. - AWS는 RDS 인스턴스의 운영 체제를 관리하고 패치합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 지원 사례를 열어 회사가 DB 인스턴스 운영 체제를 패치할 수 있도록 서버에 대한 관리 액세스를 얻습니다. - 고객은 RDS 인스턴스의 운영 체제에 직접 액세스할 수 없습니다.</p>
        <p>B. 지원 사례를 열어 AWS에 DB 인스턴스 운영 체제를 패치하도록 요청합니다. - 정기 유지 관리 창을 설정하는 것이 더 효율적입니다.</p>
        <p>C. 서버에 대한 관리 액세스를 사용하고, DB 인스턴스에 대해 정의된 정기 유지 관리 창 동안 운영 체제 패치를 적용합니다. - 고객은 RDS 인스턴스의 운영 체제에 직접 액세스할 수 없습니다.</p>
    </def>
</deflist>

128.<br/>**AWS Well-Architected 리뷰가 클라우드 설계 프로세스의 중요한 부분인 이유는 무엇입니까?**
- A. Well-Architected 리뷰는 워크로드가 AWS에서 실행되기 전에 필수적입니다.
- B. Well-Architected 리뷰는 설계 격차를 식별하고 설계 결정 및 관련 문서를 평가하는 데 도움이 됩니다.
- C. Well-Architected 리뷰는 서비스 수준 계약 요구 사항의 일부인 감사 메커니즘입니다.
- D. Well-Architected 리뷰는 지속적인 감사 및 준수 테스트의 필요성을 제거합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. Well-Architected 리뷰는 설계 격차를 식별하고 설계 결정 및 관련 문서를 평가하는 데 도움이 됩니다. - Well-Architected 리뷰는 클라우드 설계의 모범 사례를 따르는 데 도움이 됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Well-Architected 리뷰는 워크로드가 AWS에서 실행되기 전에 필수적입니다. - 필수는 아니지만 권장됩니다.</p>
        <p>C. Well-Architected 리뷰는 서비스 수준 계약 요구 사항의 일부인 감사 메커니즘입니다. - 리뷰는 감사 메커니즘이 아닙니다.</p>
        <p>D. Well-Architected 리뷰는 지속적인 감사 및 준수 테스트의 필요성을 제거합니다. - 리뷰는 지속적인 감사 및 준수 테스트를 대체하지 않습니다.</p>
    </def>
</deflist>

129.<br/>**회사는 Amazon EC2 인스턴스에서 실행되는 비정상 애플리케이션을 자동으로 복구하기 위해 Amazon EC2 Auto Scaling 정책과 Application Load Balancer를 구현했습니다. 이 작업은 AWS Well-Architected Framework의 어떤 기둥을 다룹니까?**
- A. 보안
- B. 성능 효율성
- C. 운영 우수성
- D. 신뢰성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 신뢰성 - Auto Scaling과 Load Balancer를 사용하여 애플리케이션의 가용성과 복원력을 보장합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 보안 - 보안 기둥은 데이터 보호 및 시스템 보안을 다룹니다.</p>
        <p>B. 성능 효율성 - 성능 효율성 기둥은 리소스 사용을 최적화하여 시스템 성능을 향상시키는 것을 다룹니다.</p>
        <p>C. 운영 우수성 - 운영 우수성 기둥은 운영 프로세스의 최적화를 다룹니다.</p>
    </def>
</deflist>

130.<br/>**아키텍처가 최소한의 다운타임으로 장애를 견딜 수 있는 능력은 AWS 클라우드의 어떤 이점을 나타냅니까?**
- A. 민첩성
- B. 탄력성
- C. 확장성
- D. 고가용성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. 고가용성 - 고가용성은 시스템이 최소한의 다운타임으로 장애를 견딜 수 있는 능력을 의미합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 민첩성 - 민첩성은 빠른 배포와 변경에 대한 능력을 의미합니다.</p>
        <p>B. 탄력성 - 탄력성은 리소스를 자동으로 확장하거나 축소하는 능력을 의미합니다.</p>
        <p>C. 확장성 - 확장성은 시스템이 증가하는 워크로드를 처리할 수 있는 능력을 의미합니다.</p>
    </def>
</deflist>

131.<br/>**AWS 공유 책임 모델에 따라 AWS Lambda 함수를 관리할 때 고객의 책임은 무엇입니까?**
- A. Lambda 함수의 버전 생성
- B. 서버 및 운영 체제 유지 관리
- C. 수요에 따라 Lambda 리소스 확장
- D. Lambda 런타임 환경 업데이트

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. Lambda 함수의 버전 생성 - 고객은 Lambda 함수의 버전을 생성하고 관리할 책임이 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. 서버 및 운영 체제 유지 관리 - AWS는 Lambda의 서버 및 운영 체제를 관리합니다.</p>
        <p>C. 수요에 따라 Lambda 리소스 확장 - AWS는 Lambda 리소스를 자동으로 확장합니다.</p>
        <p>D. Lambda 런타임 환경 업데이트 - AWS는 Lambda 런타임 환경을 관리합니다.</p>
    </def>
</deflist>

132.<br/>**AWS Concierge Support 팀이 제공하는 서비스는 무엇입니까?**
- A. 사용자에게 전담 기술 전문가 제공
- B. AWS 청구 및 지원에 대한 주요 연락 지점
- C. 이벤트 출시를 위한 확장 지침 제공 파트너
- D. 사용자의 애플리케이션 아키텍처를 검토하는 전담 AWS 직원

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS 청구 및 지원에 대한 주요 연락 지점 - Concierge Support 팀은 AWS 청구 및 지원에 대한 주요 연락 지점을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 사용자에게 전담 기술 전문가 제공 - 전담 기술 전문가는 AWS Support의 일부입니다.</p>
        <p>C. 이벤트 출시를 위한 확장 지침 제공 파트너 - 확장 지침은 AWS Support의 일부입니다.</p>
        <p>D. 사용자의 애플리케이션 아키텍처를 검토하는 전담 AWS 직원 - 아키텍처 검토는 AWS Support의 일부입니다.</p>
    </def>
</deflist>

133.<br/>**회사는 제품, 회사 정의 태그, 시간, 일, 월별로 클라우드 비용을 분류할 수 있는 보고서를 생성해야 합니다. 이 요구 사항을 충족하기 위해 회사는 어떤 AWS 도구를 사용해야 합니까?**
- A. 예약 인스턴스 사용률 및 커버리지 보고서
- B. 절약 계획 사용률 보고서
- C. AWS 예산 보고서
- D. AWS 비용 및 사용 보고서

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS 비용 및 사용 보고서 - 비용 및 사용 보고서는 제품, 태그, 시간별로 비용을 분류할 수 있는 보고서를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 예약 인스턴스 사용률 및 커버리지 보고서 - 이 보고서는 예약 인스턴스 사용률에 대한 정보를 제공합니다.</p>
        <p>B. 절약 계획 사용률 보고서 - 이 보고서는 절약 계획 사용률에 대한 정보를 제공합니다.</p>
        <p>C. AWS 예산 보고서 - 예산 보고서는 비용 추적 및 관리 도구입니다.</p>
    </def>
</deflist>

134.<br/>**회사는 Amazon API Gateway API, AWS Lambda 함수 및 Amazon DynamoDB 데이터베이스를 포함하는 서버리스 애플리케이션을 보유하고 있습니다. 회사는 애플리케이션의 구성 요소를 통해 사용자 요청을 추적할 수 있는 AWS 서비스를 사용해야 합니다. 이 요구 사항을 충족하는 AWS 서비스는 무엇입니까?**
- A. AWS CloudTrail
- B. Amazon CloudWatch
- C. Amazon Inspector
- D. AWS X-Ray

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        D. AWS X-Ray - X-Ray는 애플리케이션의 구성 요소를 통해 사용자 요청을 추적할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS CloudTrail - CloudTrail은 AWS API 호출을 기록합니다.</p>
        <p>B. Amazon CloudWatch - CloudWatch는 모니터링 및 로그 관리 도구입니다.</p>
        <p>C. Amazon Inspector - Inspector는 보안 취약성을 평가하는 도구입니다.</p>
    </def>
</deflist>

135.<br/>**회사는 AWS 클라우드에 페타바이트 규모의 데이터 웨어하우스를 설정해야 합니다. 이 요구 사항을 충족하는 AWS 서비스는 무엇입니까?**
- A. Amazon DynamoDB
- B. Amazon RDS
- C. Amazon Redshift
- D. Amazon ElastiCache

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. Amazon Redshift - Redshift는 페타바이트 규모의 데이터 웨어하우스를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon DynamoDB - DynamoDB는 키-값 데이터베이스입니다.</p>
        <p>B. Amazon RDS - RDS는 관계형 데이터베이스 서비스입니다.</p>
        <p>D. Amazon ElastiCache - ElastiCache는 인메모리 캐싱 서비스입니다.</p>
    </def>
</deflist>

136.<br/>**항상 무료로 제공되는 AWS 서비스는 무엇입니까?**
- A. Amazon S3
- B. AWS Identity and Access Management (IAM)
- C. Elastic Load Balancers
- D. AWS WAF

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS Identity and Access Management (IAM) - IAM은 항상 무료로 제공됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. Amazon S3 - S3는 사용량에 따라 비용이 청구됩니다.</p>
        <p>C. Elastic Load Balancers - ELB는 사용량에 따라 비용이 청구됩니다.</p>
        <p>D. AWS WAF - WAF는 사용량에 따라 비용이 청구됩니다.</p>
    </def>
</deflist>

137.<br/>**회사는 여러 지리적 지역을 포함하는 AWS 재해 복구 계획을 설계해야 합니다. 이 요구 사항을 충족하는 조치는 무엇입니까?**
- A. 여러 AWS 계정 구성
- B. AWS 리전 내 여러 가용 영역에 아키텍처 구성
- C. 여러 AWS 리전에 아키텍처 구성
- D. 여러 엣지 로케이션에 아키텍처 구성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. 여러 AWS 리전에 아키텍처 구성 - 여러 리전에 아키텍처를 구성하면 지리적 장애로부터 보호할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 여러 AWS 계정 구성 - 계정 구성은 지리적 장애와 관련이 없습니다.</p>
        <p>B. AWS 리전 내 여러 가용 영역에 아키텍처 구성 - 가용 영역은 동일한 리전 내에 있습니다.</p>
        <p>D. 여러 엣지 로케이션에 아키텍처 구성 - 엣지 로케이션은 콘텐츠 전송에 사용됩니다.</p>
    </def>
</deflist>

138.<br/>**온프레미스 데이터 센터에서 AWS 클라우드로 이동할 때의 이점은 무엇입니까?**
- A. 필요에 따라 컴퓨팅 인스턴스를 시작하고 종료하여 비용을 최적화할 수 있습니다.
- B. AWS 청구 및 비용 관리 콘솔에서 컴퓨팅 비용을 확인할 수 있습니다.
- C. 사용자는 컴퓨팅 인스턴스에 대한 전체 관리 액세스를 유지합니다.
- D. 사용자는 최대 부하 시 항상 충분한 인스턴스를 실행하여 비용을 최적화할 수 있습니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. 필요에 따라 컴퓨팅 인스턴스를 시작하고 종료하여 비용을 최적화할 수 있습니다. - AWS 클라우드는 유연한 리소스 관리를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. AWS 청구 및 비용 관리 콘솔에서 컴퓨팅 비용을 확인할 수 있습니다. - 이 기능은 온프레미스와 관련이 없습니다.</p>
        <p>C. 사용자는 컴퓨팅 인스턴스에 대한 전체 관리 액세스를 유지합니다. - AWS는 일부 관리 작업을 수행합니다.</p>
        <p>D. 사용자는 최대 부하 시 항상 충분한 인스턴스를 실행하여 비용을 최적화할 수 있습니다. - 이는 비용 최적화와 관련이 없습니다.</p>
    </def>
</deflist>

139.<br/>**AWS 클라우드가 온프레미스 데이터 센터보다 컴퓨팅 리소스의 총 소유 비용(TCO)을 낮추는 방법은 무엇입니까? (두 가지 선택)**
- A. AWS는 선불 자본 지출을 사용한 만큼 지불하는 비용으로 대체합니다.
- B. AWS는 높은 가용성을 위해 설계되어 사용자 다운타임을 제거합니다.
- C. AWS는 온프레미스 IT 직원의 필요성을 제거합니다.
- D. AWS는 규모의 경제를 사용하여 지속적으로 가격을 낮춥니다.
- E. AWS는 Amazon EC2 인스턴스에 대한 단일 가격 모델을 제공합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. AWS는 선불 자본 지출을 사용한 만큼 지불하는 비용으로 대체합니다. - AWS는 선불 비용 없이 사용한 만큼만 비용을 지불합니다.
        D. AWS는 규모의 경제를 사용하여 지속적으로 가격을 낮춥니다. - AWS는 규모의 경제를 통해 비용을 절감합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. AWS는 높은 가용성을 위해 설계되어 사용자 다운타임을 제거합니다. - 이는 비용 절감과 직접적인 관련이 없습니다.</p>
        <p>C. AWS는 온프레미스 IT 직원의 필요성을 제거합니다. - 일부 IT 직원은 여전히 필요할 수 있습니다.</p>
        <p>E. AWS는 Amazon EC2 인스턴스에 대한 단일 가격 모델을 제공합니다. - AWS는 다양한 가격 모델을 제공합니다.</p>
    </def>
</deflist>

140.<br/>**어떤 AWS 서비스가 AWS 계정을 보안 위협으로부터 모니터링합니까?**
- A. Amazon GuardDuty
- B. AWS Secrets Manager
- C. Amazon Cognito
- D. AWS Certificate Manager (ACM)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. Amazon GuardDuty - GuardDuty는 AWS 계정을 보안 위협으로부터 모니터링합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. AWS Secrets Manager - Secrets Manager는 비밀을 안전하게 저장하고 관리합니다.</p>
        <p>C. Amazon Cognito - Cognito는 사용자 인증 및 관리 서비스입니다.</p>
        <p>D. AWS Certificate Manager (ACM) - ACM은 SSL/TLS 인증서를 관리합니다.</p>
    </def>
</deflist>

141.<br/>**AWS Enterprise Support 플랜에 포함된 혜택은 무엇입니까?**
- A. AWS Partner Network (APN) 지원 무료 제공
- B. AWS 기술 계정 관리자 (TAM)로부터 지정된 지원
- C. AWS 엔지니어의 현장 지원
- D. AWS Config를 사용한 코드로서의 관리된 규정 준수

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. AWS 기술 계정 관리자 (TAM)로부터 지정된 지원 - Enterprise Support 플랜에는 TAM의 지정된 지원이 포함됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Partner Network (APN) 지원 무료 제공 - APN 지원은 별도의 서비스입니다.</p>
        <p>C. AWS 엔지니어의 현장 지원 - 현장 지원은 일반적으로 제공되지 않습니다.</p>
        <p>D. AWS Config를 사용한 코드로서의 관리된 규정 준수 - 이는 별도의 서비스입니다.</p>
    </def>
</deflist>

142.<br/>**AWS가 자동으로 수행하는 작업은 무엇입니까?**
- A. Amazon DynamoDB에 저장된 데이터 암호화
- B. Amazon EC2 인스턴스 패치
- C. 사용자 네트워크 트래픽 암호화
- D. 사용자 웹사이트용 TLS 인증서 생성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        A. Amazon DynamoDB에 저장된 데이터 암호화 - AWS는 DynamoDB에 저장된 데이터를 자동으로 암호화합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>B. Amazon EC2 인스턴스 패치 - EC2 인스턴스 패치는 고객의 책임입니다.</p>
        <p>C. 사용자 네트워크 트래픽 암호화 - 네트워크 트래픽 암호화는 고객의 책임입니다.</p>
        <p>D. 사용자 웹사이트용 TLS 인증서 생성 - TLS 인증서 생성은 고객의 책임입니다.</p>
    </def>
</deflist>

143.<br/>**회사가 AWS 비용 및 사용량을 시각화, 이해 및 관리할 수 있는 AWS 서비스 또는 도구는 무엇입니까?**
- A. AWS Trusted Advisor
- B. Amazon CloudWatch
- C. Cost Explorer
- D. AWS Budgets

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. Cost Explorer - Cost Explorer는 AWS 비용 및 사용량을 시각화, 이해 및 관리할 수 있는 도구입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Trusted Advisor - Trusted Advisor는 비용 최적화, 보안, 성능 및 장애 복구에 대한 권장 사항을 제공합니다.</p>
        <p>B. Amazon CloudWatch - CloudWatch는 모니터링 및 로그 관리 도구입니다.</p>
        <p>D. AWS Budgets - Budgets는 비용을 추적하고 관리하는 도구입니다.</p>
    </def>
</deflist>

144.<br/>**회사는 일부 리소스를 AWS 클라우드에 배포하려고 합니다. 규제 요구 사항을 충족하기 위해 데이터는 로컬 및 온프레미스에 남아 있어야 합니다. AWS와 회사 리소스 간의 지연 시간이 낮아야 합니다. 이 요구 사항을 충족하는 AWS 서비스 또는 기능은 무엇입니까?**
- A. AWS Local Zones
- B. 가용 영역
- C. AWS Outposts
- D. AWS Wavelength Zones

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        C. AWS Outposts - Outposts는 온프레미스에 AWS 인프라를 배포하여 로컬 데이터 저장 및 낮은 지연 시간을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. AWS Local Zones - Local Zones는 특정 지역에 AWS 인프라를 배포하지만, 온프레미스는 아닙니다.</p>
        <p>B. 가용 영역 - 가용 영역은 AWS 리전 내에 있습니다.</p>
        <p>D. AWS Wavelength Zones - Wavelength Zones는 5G 네트워크 엣지에서 컴퓨팅 서비스를 제공합니다.</p>
    </def>
</deflist>

145.<br/>**회사는 보안 목적으로 AWS 내에서 격리된 환경이 필요합니다. 이를 달성하기 위해 취할 수 있는 조치는 무엇입니까?**
- A. 리소스를 호스팅할 별도의 가용 영역 생성
- B. 리소스를 호스팅할 별도의 VPC 생성
- C. 리소스를 호스팅할 배치 그룹 생성
- D. 회사와 AWS 간의 AWS Direct Connect 연결 생성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        B. 리소스를 호스팅할 별도의 VPC 생성 - 별도의 VPC를 생성하면 격리된 환경을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>A. 리소스를 호스팅할 별도의 가용 영역 생성 - 가용 영역은 격리된 환경을 제공하지 않습니다.</p>
        <p>C. 리소스를 호스팅할 배치 그룹 생성 - 배치 그룹은 격리된 환경을 제공하지 않습니다.</p>
        <p>D. 회사와 AWS 간의 AWS Direct Connect 연결 생성 - Direct Connect는 네트워크 연결을 제공합니다.</p>
    </def>
</deflist>

146.<br/>**어떤 AWS 서비스가 고가용성 및 확장 가능한 DNS 웹 서비스인가요?**
- A. Amazon VPC
- B. Amazon CloudFront
- C. Amazon Route 53
- D. Amazon Connect

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Route 53는 고가용성 및 확장 가능한 DNS 웹 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon VPC는 가상 네트워크를 생성하는 서비스입니다.</p>
        <p>Amazon CloudFront는 콘텐츠 전송 네트워크(CDN) 서비스입니다.</p>
        <p>Amazon Connect는 클라우드 기반 연락 센터 서비스입니다.</p>
    </def>
</deflist>

147.<br/>**다음 중 AWS 계정 루트 사용자 관리를 위한 AWS 모범 사례는 무엇인가요?**
- A. 루트 사용자 비밀번호를 보안 팀과 함께 보관합니다.
- B. 루트 사용자에 대해 다중 인증(MFA)을 활성화합니다.
- C. 루트 사용자에 대한 액세스 키를 생성합니다.
- D. 준수 목적으로 루트 사용자 비밀번호를 일관되게 유지합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        루트 사용자에 대해 다중 인증(MFA)을 활성화하는 것이 모범 사례입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>루트 사용자 비밀번호를 보안 팀과 함께 보관하는 것은 안전하지 않습니다.</p>
        <p>루트 사용자에 대한 액세스 키를 생성하는 것은 권장되지 않습니다.</p>
        <p>루트 사용자 비밀번호를 일관되게 유지하는 것은 보안에 취약할 수 있습니다.</p>
    </def>
</deflist>

148.<br/>**회사가 Amazon EC2 인바운드 액세스를 제한하여 보안 및 감사 태세를 개선하고자 합니다. SSH 포트를 열고 SSH 키를 관리하는 대신 인스턴스에 원격으로 액세스하려면 무엇을 사용해야 하나요?**
- A. EC2 키 페어
- B. AWS Systems Manager Session Manager
- C. AWS Identity and Access Management (IAM)
- D. 네트워크 ACL

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Systems Manager Session Manager를 사용하여 인스턴스에 원격으로 액세스할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>EC2 키 페어는 SSH 키를 관리하는 방법입니다.</p>
        <p>AWS Identity and Access Management (IAM)는 사용자 및 권한을 관리하는 서비스입니다.</p>
        <p>네트워크 ACL은 네트워크 트래픽을 제어하는 방법입니다.</p>
    </def>
</deflist>

149.<br/>**Amazon EC2 전용 호스트 예약을 선택한 후 가장 큰 할인을 제공하는 가격 옵션은 무엇인가요?**
- A. 선결제 없음
- B. 시간당 주문형 결제
- C. 부분 선결제
- D. 전체 선결제

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        전체 선결제가 가장 큰 할인을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>선결제 없음은 할인을 제공하지 않습니다.</p>
        <p>시간당 주문형 결제는 할인을 제공하지 않습니다.</p>
        <p>부분 선결제는 일부 할인을 제공하지만 전체 선결제보다 적습니다.</p>
    </def>
</deflist>

150.<br/>**회사가 특정 AWS 서비스를 사용하여 효율성을 높이고 비용을 절감하도록 워크로드를 개선했습니다. 이 예시는 비용 관리의 어떤 모범 사례를 보여주나요?**
- A. 리소스 제어
- B. 비용 할당
- C. 아키텍처 최적화
- D. 태그 적용

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        아키텍처 최적화는 효율성을 높이고 비용을 절감하는 모범 사례입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>리소스 제어는 리소스 사용을 관리하는 방법입니다.</p>
        <p>비용 할당은 비용을 추적하고 할당하는 방법입니다.</p>
        <p>태그 적용은 리소스를 식별하고 관리하는 방법입니다.</p>
    </def>
</deflist>

151.<br/>**회사가 MySQL 데이터베이스를 AWS에 호스팅하고 운영 체제, 데이터베이스 설치 및 구성을 완전히 제어하고자 합니다. 어떤 AWS 서비스를 사용해야 하나요?**
- A. Amazon RDS
- B. Amazon EC2
- C. Amazon DynamoDB
- D. Amazon Aurora

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon EC2는 운영 체제, 데이터베이스 설치 및 구성을 완전히 제어할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon RDS는 관리형 데이터베이스 서비스로, 완전한 제어를 제공하지 않습니다.</p>
        <p>Amazon DynamoDB는 NoSQL 데이터베이스 서비스로, MySQL을 지원하지 않습니다.</p>
        <p>Amazon Aurora는 관리형 데이터베이스 서비스로, 완전한 제어를 제공하지 않습니다.</p>
    </def>
</deflist>

152.<br/>**AWS 글로벌 인프라가 사용자에게 고가용성과 내결함성을 제공하는 방법은 무엇인가요?**
- A. AWS 인프라는 여러 가용 영역 내의 여러 AWS 리전으로 구성되어 있으며, 저지대 위험이 낮은 지역에 위치하고 저지연 네트워크와 중복 전원 공급 장치로 상호 연결되어 있습니다.
- B. AWS 인프라는 동일한 지리적 위치에 여러 데이터 센터가 있는 다양한 가용 영역을 포함하는 서브넷으로 구성되어 있습니다.
- C. AWS는 사용자가 AWS 리전과 데이터 센터를 선택할 수 있도록 하여 사용자가 다른 리전의 가장 가까운 데이터 센터를 선택할 수 있도록 합니다.
- D. AWS 인프라는 저지연 네트워킹 및 중복 전원 공급 장치로 연결된 독립된 가용 영역이 있는 격리된 AWS 리전으로 구성되어 있습니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS 인프라는 저지연 네트워킹 및 중복 전원 공급 장치로 연결된 독립된 가용 영역이 있는 격리된 AWS 리전으로 구성되어 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS 인프라는 여러 가용 영역 내의 여러 AWS 리전으로 구성되어 있지만, 저지대 위험이 낮은 지역에 위치하지 않을 수 있습니다.</p>
        <p>AWS 인프라는 동일한 지리적 위치에 여러 데이터 센터가 있는 다양한 가용 영역을 포함하는 서브넷으로 구성되지 않습니다.</p>
        <p>AWS는 사용자가 다른 리전의 가장 가까운 데이터 센터를 선택할 수 있도록 허용하지 않습니다.</p>
    </def>
</deflist>

153.<br/>**회사가 Amazon EC2 Auto Scaling을 사용하여 Amazon EC2 인스턴스를 확장하고 있습니다. 이 예시는 AWS 클라우드의 어떤 이점을 보여주나요?**
- A. 고가용성
- B. 탄력성
- C. 신뢰성
- D. 글로벌 도달 범위

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        탄력성은 필요에 따라 리소스를 자동으로 확장하거나 축소할 수 있는 AWS 클라우드의 이점입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>고가용성은 시스템이 지속적으로 운영될 수 있는 능력입니다.</p>
        <p>신뢰성은 시스템이 일관되게 작동할 수 있는 능력입니다.</p>
        <p>글로벌 도달 범위는 전 세계적으로 서비스를 제공할 수 있는 능력입니다.</p>
    </def>
</deflist>

154.<br/>**분산 애플리케이션에서 텍스트 및 이메일 메시지를 보내는 데 사용되는 AWS 서비스 또는 기능은 무엇인가요?**
- A. Amazon Simple Notification Service (Amazon SNS)
- B. Amazon Simple Email Service (Amazon SES)
- C. Amazon CloudWatch 알림
- D. Amazon Simple Queue Service (Amazon SQS)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Simple Notification Service (Amazon SNS)는 분산 애플리케이션에서 텍스트 및 이메일 메시지를 보낼 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Simple Email Service (Amazon SES)는 이메일 메시지를 보내는 데 사용됩니다.</p>
        <p>Amazon CloudWatch 알림은 모니터링 및 경고를 위한 서비스입니다.</p>
        <p>Amazon Simple Queue Service (Amazon SQS)는 메시지 대기열 서비스입니다.</p>
    </def>
</deflist>

155.<br/>**사용자가 마스터 결제 계정을 설정하여 통합 청구 보고서를 볼 수 있는 서비스는 무엇인가요?**
- A. AWS Budgets
- B. Amazon Macie
- C. Amazon QuickSight
- D. AWS Organizations

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Organizations를 사용하여 마스터 결제 계정을 설정하고 통합 청구 보고서를 볼 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Budgets는 예산을 설정하고 비용을 추적하는 데 사용됩니다.</p>
        <p>Amazon Macie는 데이터 보안 및 개인 정보 보호를 위한 서비스입니다.</p>
        <p>Amazon QuickSight는 비즈니스 인텔리전스 서비스입니다.</p>
    </def>
</deflist>

156.<br/>**AWS 공유 책임 모델에 따르면, 고객의 책임은 무엇인가요?**
- A. AWS Lambda를 실행하는 데 필요한 인프라 유지 관리
- B. Amazon DynamoDB 인스턴스의 운영 체제 업데이트
- C. Amazon S3 인프라 유지 관리
- D. Amazon EC2 인스턴스의 게스트 운영 체제 업데이트

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon EC2 인스턴스의 게스트 운영 체제를 업데이트하는 것은 고객의 책임입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Lambda를 실행하는 데 필요한 인프라 유지 관리는 AWS의 책임입니다.</p>
        <p>Amazon DynamoDB 인스턴스의 운영 체제 업데이트는 AWS의 책임입니다.</p>
        <p>Amazon S3 인프라 유지 관리는 AWS의 책임입니다.</p>
    </def>
</deflist>

157.<br/>**회사가 온프레미스 인프라에서 AWS 클라우드로 작은 웹사이트와 데이터베이스를 빠르게 마이그레이션하고자 합니다. 회사는 마이그레이션을 수행할 운영 지식이 제한적입니다. 이 사용 사례를 지원하는 AWS 서비스는 무엇인가요?**
- A. Amazon EC2
- B. Amazon Lightsail
- C. Amazon S3
- D. AWS Lambda

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Lightsail은 웹사이트와 데이터베이스를 빠르게 마이그레이션할 수 있는 간단한 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon EC2는 더 많은 설정과 관리가 필요합니다.</p>
        <p>Amazon S3는 객체 스토리지 서비스로, 웹사이트와 데이터베이스 호스팅에 적합하지 않습니다.</p>
        <p>AWS Lambda는 서버리스 컴퓨팅 서비스로, 웹사이트와 데이터베이스 호스팅에 적합하지 않습니다.</p>
    </def>
</deflist>

158.<br/>**회사가 여러 애플리케이션을 단일 AWS 계정으로 이동하고 있습니다. 회사는 각 애플리케이션에 의해 발생하는 AWS 클라우드 비용을 모니터링하고자 합니다. 이 요구 사항을 충족하기 위해 회사는 무엇을 해야 하나요?**
- A. 청구서 발행 설정
- B. AWS Artifact 사용
- C. Cost Explorer에서 예산 설정
- D. 비용 할당 태그 생성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        비용 할당 태그를 생성하여 각 애플리케이션의 비용을 모니터링할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>청구서 발행 설정은 비용 모니터링에 도움이 되지 않습니다.</p>
        <p>AWS Artifact는 규정 준수 관련 문서를 제공하는 서비스입니다.</p>
        <p>Cost Explorer에서 예산을 설정하는 것은 비용 모니터링에 도움이 되지만, 비용 할당 태그가 더 효과적입니다.</p>
    </def>
</deflist>

159.<br/>**AWS Well-Architected Framework의 신뢰성 원칙을 따름으로써 달성되는 설계 원칙은 무엇인가요?**
- A. 수직 확장
- B. 수동 장애 복구
- C. 복구 절차 테스트
- D. 인프라 수동 변경

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        복구 절차 테스트는 신뢰성 원칙을 따름으로써 달성되는 설계 원칙입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>수직 확장은 리소스를 추가하여 성능을 향상시키는 방법입니다.</p>
        <p>수동 장애 복구는 자동화되지 않은 복구 방법입니다.</p>
        <p>인프라 수동 변경은 자동화되지 않은 변경 방법입니다.</p>
    </def>
</deflist>

160.<br/>**사용자가 AWS에서 비관계형 데이터베이스를 신속하게 배포해야 합니다. 사용자는 기본 하드웨어나 데이터베이스 소프트웨어를 관리하고 싶지 않습니다. 이 요구를 충족하기 위해 사용할 수 있는 AWS 서비스는 무엇인가요?**
- A. Amazon RDS
- B. Amazon DynamoDB
- C. Amazon Aurora
- D. Amazon Redshift

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon DynamoDB는 비관계형 데이터베이스를 신속하게 배포할 수 있는 관리형 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon RDS는 관계형 데이터베이스 서비스입니다.</p>
        <p>Amazon Aurora는 관계형 데이터베이스 서비스입니다.</p>
        <p>Amazon Redshift는 데이터 웨어하우스 서비스입니다.</p>
    </def>
</deflist>

161.<br/>**Amazon RDS에서 워크로드가 실행될 때 AWS의 책임은 무엇인가요?**
- A. 데이터베이스 테이블 생성
- B. 데이터베이스 스키마 업데이트
- C. 데이터베이스 엔진 설치
- D. 데이터베이스 레코드 삭제

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        데이터베이스 엔진 설치는 AWS의 책임입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>데이터베이스 테이블 생성은 고객의 책임입니다.</p>
        <p>데이터베이스 스키마 업데이트는 고객의 책임입니다.</p>
        <p>데이터베이스 레코드 삭제는 고객의 책임입니다.</p>
    </def>
</deflist>

162.<br/>**개발 팀이 REST API를 제공하는 웹 서비스를 게시하고 관리하고자 합니다. 이 요구 사항을 충족하는 AWS 서비스는 무엇인가요?**
- A. AWS App Mesh
- B. Amazon API Gateway
- C. Amazon CloudFront
- D. AWS Cloud Map

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon API Gateway는 REST API를 제공하고 관리할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS App Mesh는 마이크로서비스 간의 통신을 관리하는 서비스입니다.</p>
        <p>Amazon CloudFront는 콘텐츠 전송 네트워크(CDN) 서비스입니다.</p>
        <p>AWS Cloud Map은 서비스 검색을 위한 서비스입니다.</p>
    </def>
</deflist>

163.<br/>**회사가 사용자가 사진을 업로드하고 공유하는 소셜 미디어 플랫폼을 운영하고 있습니다. 회사는 부적절한 사진을 식별하고 제거하고자 합니다. 회사에는 머신 러닝(ML) 과학자가 없으며, ML 전문 지식 없이 이 감지 기능을 구축해야 합니다. 이 기능을 구축하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. Amazon SageMaker
- B. Amazon Textract
- C. Amazon Rekognition
- D. Amazon Comprehend

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Rekognition은 부적절한 사진을 식별하고 제거할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon SageMaker는 ML 모델을 구축하고 훈련하는 서비스입니다.</p>
        <p>Amazon Textract는 문서에서 텍스트와 데이터를 추출하는 서비스입니다.</p>
        <p>Amazon Comprehend는 텍스트 분석 서비스입니다.</p>
    </def>
</deflist>

164.<br/>**회사가 Amazon EC2 인스턴스에서 데이터베이스를 호스팅할 때 AWS의 책임은 무엇인가요?**
- A. 데이터베이스 백업
- B. 데이터베이스 소프트웨어 패치
- C. 운영 체제 패치
- D. 운영 체제 설치

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        운영 체제 설치는 AWS의 책임입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>데이터베이스 백업은 고객의 책임입니다.</p>
        <p>데이터베이스 소프트웨어 패치는 고객의 책임입니다.</p>
        <p>운영 체제 패치는 고객의 책임입니다.</p>
    </def>
</deflist>

165.<br/>**회사가 Amazon S3를 사용하여 레거시 데이터를 저장하고자 합니다. 데이터는 거의 액세스되지 않지만, 중요한 데이터이며 재생성할 수 없습니다. 데이터는 몇 초 내에 검색할 수 있어야 합니다. 이러한 요구 사항을 가장 비용 효율적으로 충족하는 S3 스토리지 클래스는 무엇인가요?**
- A. S3 Standard
- B. S3 One Zone-Infrequent Access (S3 One Zone-IA)
- C. S3 Standard-Infrequent Access (S3 Standard-IA)
- D. S3 Glacier

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        S3 Standard-Infrequent Access (S3 Standard-IA)는 거의 액세스되지 않는 데이터를 비용 효율적으로 저장할 수 있으며, 몇 초 내에 검색할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>S3 Standard는 자주 액세스되는 데이터를 저장하는 데 적합합니다.</p>
        <p>S3 One Zone-Infrequent Access (S3 One Zone-IA)는 단일 가용 영역에 데이터를 저장하므로 내구성이 낮습니다.</p>
        <p>S3 Glacier는 데이터 검색 시간이 길어 몇 초 내에 검색할 수 없습니다.</p>
    </def>
</deflist>

166.<br/>**온라인 소매 회사가 온프레미스 워크로드를 AWS로 마이그레이션하고자 합니다. 회사는 비용 효율적인 방식으로 계절적 워크로드 증가를 자동으로 처리해야 합니다. 이 요구 사항을 충족하는 AWS 클라우드 기능은 무엇인가요? (두 가지 선택)**
- A. 크로스 리전 워크로드 배포
- B. 사용한 만큼 지불하는 가격 책정
- C. 내장된 AWS CloudTrail 감사 기능
- D. Auto Scaling 정책
- E. 중앙 집중식 로깅

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        사용한 만큼 지불하는 가격 책정과 Auto Scaling 정책은 계절적 워크로드 증가를 자동으로 처리하고 비용 효율성을 유지하는 데 도움이 됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>크로스 리전 워크로드 배포는 워크로드의 지리적 분산을 지원하지만, 계절적 증가를 자동으로 처리하는 데 직접적인 도움이 되지 않습니다.</p>
        <p>내장된 AWS CloudTrail 감사 기능은 보안 및 규정 준수를 지원하지만, 워크로드 증가를 처리하는 데 직접적인 도움이 되지 않습니다.</p>
        <p>중앙 집중식 로깅은 로그 관리를 지원하지만, 워크로드 증가를 처리하는 데 직접적인 도움이 되지 않습니다.</p>
    </def>
</deflist>

167.<br/>**어떤 AWS 서비스가 마이크로서비스 간의 느슨한 결합과 신뢰할 수 있는 메시징을 지원하나요?**
- A. Elastic Load Balancing
- B. Amazon Simple Notification Service (Amazon SNS)
- C. Amazon CloudFront
- D. Amazon Simple Queue Service (Amazon SQS)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Simple Queue Service (Amazon SQS)는 마이크로서비스 간의 느슨한 결합과 신뢰할 수 있는 메시징을 지원합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Elastic Load Balancing은 트래픽 분산을 지원합니다.</p>
        <p>Amazon Simple Notification Service (Amazon SNS)는 알림 메시징을 지원합니다.</p>
        <p>Amazon CloudFront는 콘텐츠 전송 네트워크(CDN) 서비스입니다.</p>
    </def>
</deflist>

168.<br/>**회사가 AWS 서비스를 사용하는 애플리케이션을 구축해야 합니다. 애플리케이션은 유럽 국가의 거주자에게 제공될 예정입니다. 회사는 지역 규제 요구 사항을 준수해야 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스 또는 프로그램을 사용해야 하나요?**
- A. AWS Audit Manager
- B. AWS Shield
- C. AWS Compliance Program
- D. AWS Artifact

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Artifact는 지역 규제 요구 사항을 충족하는 AWS 서비스를 확인하는 데 도움이 됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Audit Manager는 감사 관리를 지원합니다.</p>
        <p>AWS Shield는 DDoS 공격 방어를 지원합니다.</p>
        <p>AWS Compliance Program은 규정 준수 프로그램을 제공합니다.</p>
    </def>
</deflist>

169.<br/>**회사가 AWS 클라우드에서 실행되는 모바일 앱의 플릿에 대한 ID 관리를 구현해야 합니다. 이 요구 사항을 충족하는 AWS 서비스는 무엇인가요?**
- A. Amazon Cognito
- B. AWS Security Hub
- C. AWS Shield
- D. AWS WAF

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Cognito는 모바일 앱의 ID 관리를 지원합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Security Hub는 보안 상태를 모니터링합니다.</p>
        <p>AWS Shield는 DDoS 공격 방어를 지원합니다.</p>
        <p>AWS WAF는 웹 애플리케이션 방화벽을 제공합니다.</p>
    </def>
</deflist>

170.<br/>**회사가 1년 동안 지속적으로 실행되어야 하는 적절한 크기의 데이터베이스 서버를 위한 Amazon EC2 인스턴스가 필요합니다. 이 요구 사항을 가장 비용 효율적으로 충족하는 EC2 인스턴스 구매 옵션은 무엇인가요?**
- A. 표준 예약 인스턴스
- B. 변환 가능 예약 인스턴스
- C. 주문형 인스턴스
- D. 스팟 인스턴스

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        표준 예약 인스턴스는 1년 동안 지속적으로 실행되는 데이터베이스 서버에 가장 비용 효율적인 옵션입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>변환 가능 예약 인스턴스는 유연성을 제공하지만, 표준 예약 인스턴스보다 비용이 더 많이 들 수 있습니다.</p>
        <p>주문형 인스턴스는 유연성을 제공하지만, 장기 실행 시 비용이 더 많이 들 수 있습니다.</p>
        <p>스팟 인스턴스는 비용이 저렴하지만, 인스턴스가 중단될 수 있는 위험이 있습니다.</p>
    </def>
</deflist>

171.<br/>**회사가 여러 애플리케이션을 보유하고 있으며, 이제 새로운 다중 계층 애플리케이션을 구축하고 있습니다. 회사는 새로운 애플리케이션을 Amazon EC2 인스턴스에 호스팅할 예정입니다. 회사는 다양한 애플리케이션 간의 네트워크 라우팅 및 트래픽이 최소 권한 원칙을 따르기를 원합니다. 이 원칙을 적용하기 위해 어떤 AWS 서비스 또는 기능을 사용해야 하나요?**
- A. 보안 그룹
- B. AWS Shield
- C. AWS Global Accelerator
- D. AWS Direct Connect 게이트웨이

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        보안 그룹은 최소 권한 원칙을 적용하여 네트워크 라우팅 및 트래픽을 제어할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Shield는 DDoS 공격 방어를 지원합니다.</p>
        <p>AWS Global Accelerator는 글로벌 애플리케이션 성능을 향상시킵니다.</p>
        <p>AWS Direct Connect 게이트웨이는 온프레미스 네트워크와 AWS 간의 전용 연결을 제공합니다.</p>
    </def>
</deflist>

172.<br/>**회사의 웹 애플리케이션이 AWS 서비스 사용을 위한 AWS 자격 증명 및 권한을 필요로 합니다. 모범 사례로 어떤 IAM 엔터티를 사용해야 하나요?**
- A. IAM 역할
- B. IAM 사용자
- C. IAM 그룹
- D. IAM 다중 인증(MFA)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        IAM 역할은 AWS 서비스 사용을 위한 자격 증명 및 권한을 제공하는 모범 사례입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>IAM 사용자는 개별 사용자에게 자격 증명을 제공합니다.</p>
        <p>IAM 그룹은 여러 사용자에게 권한을 할당하는 데 사용됩니다.</p>
        <p>IAM 다중 인증(MFA)은 추가 보안 계층을 제공합니다.</p>
    </def>
</deflist>

173.<br/>**회사가 모든 시스템에 대한 운영 체제 패치 루틴을 정의하는 문서를 작성하고 있습니다. 이 문서에 포함해야 할 AWS 리소스는 무엇인가요? (두 가지 선택)**
- A. Amazon EC2 인스턴스
- B. AWS Lambda 함수
- C. AWS Fargate 작업
- D. Amazon RDS 인스턴스
- E. Amazon Elastic Container Service (Amazon ECS) 인스턴스

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon EC2 인스턴스와 Amazon RDS 인스턴스는 운영 체제 패치 루틴에 포함되어야 합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Lambda 함수는 서버리스 컴퓨팅 서비스로, 운영 체제 패치가 필요하지 않습니다.</p>
        <p>AWS Fargate 작업은 컨테이너 관리 서비스로, 운영 체제 패치가 필요하지 않습니다.</p>
        <p>Amazon Elastic Container Service (Amazon ECS) 인스턴스는 컨테이너 관리 서비스로, 운영 체제 패치가 필요하지 않습니다.</p>
    </def>
</deflist>

174.<br/>**어떤 AWS 서비스 또는 기능이 회사가 Amazon EC2 인스턴스에 대한 인바운드 및 아웃바운드 트래픽을 제어할 수 있도록 하나요?**
- A. 보안 그룹
- B. Amazon Route 53
- C. AWS Direct Connect
- D. Amazon VPC

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        보안 그룹은 Amazon EC2 인스턴스에 대한 인바운드 및 아웃바운드 트래픽을 제어할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Route 53은 DNS 웹 서비스입니다.</p>
        <p>AWS Direct Connect는 온프레미스 네트워크와 AWS 간의 전용 연결을 제공합니다.</p>
        <p>Amazon VPC는 가상 네트워크를 생성하는 서비스입니다.</p>
    </def>
</deflist>

175.<br/>**회사가 AWS 클라우드에서 인프라를 구축하기 시작하고 있습니다. 회사는 업무 시간 동안 기술 지원에 액세스하고 싶습니다. 또한 팀이 새로운 애플리케이션을 구축하고 테스트할 때 일반적인 아키텍처 지침을 원합니다. 이 요구 사항을 가장 저렴한 비용으로 충족하는 AWS 지원 플랜은 무엇인가요?**
- A. AWS 기본 지원
- B. AWS 개발자 지원
- C. AWS 비즈니스 지원
- D. AWS 엔터프라이즈 지원

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS 개발자 지원은 업무 시간 동안 기술 지원과 일반적인 아키텍처 지침을 제공하며, 가장 저렴한 비용으로 요구 사항을 충족합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS 기본 지원은 기술 지원을 제공하지 않습니다.</p>
        <p>AWS 비즈니스 지원은 더 높은 비용으로 추가 지원을 제공합니다.</p>
        <p>AWS 엔터프라이즈 지원은 가장 높은 수준의 지원을 제공하지만, 비용이 가장 많이 듭니다.</p>
    </def>
</deflist>

176.<br/>**회사가 공용 웹사이트를 AWS로 마이그레이션하고 있습니다. 회사는 웹사이트의 도메인 이름을 AWS에서 호스팅하고자 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. AWS Lambda
- B. Amazon Route 53
- C. Amazon CloudFront
- D. AWS Direct Connect

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Route 53는 도메인 이름을 호스팅할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Lambda는 서버리스 컴퓨팅 서비스입니다.</p>
        <p>Amazon CloudFront는 콘텐츠 전송 네트워크(CDN) 서비스입니다.</p>
        <p>AWS Direct Connect는 온프레미스 네트워크와 AWS 간의 전용 연결을 제공합니다.</p>
    </def>
</deflist>

177.<br/>**회사가 AWS 환경을 평가하고 비용, 성능, 서비스 한도, 내결함성 및 보안의 다섯 가지 범주에서 모범 사례 권장 사항을 제공해야 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. AWS Shield
- B. AWS WAF
- C. AWS Trusted Advisor
- D. AWS Service Catalog

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Trusted Advisor는 비용, 성능, 서비스 한도, 내결함성 및 보안에 대한 모범 사례 권장 사항을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Shield는 DDoS 공격 방어를 지원합니다.</p>
        <p>AWS WAF는 웹 애플리케이션 방화벽을 제공합니다.</p>
        <p>AWS Service Catalog는 서비스 카탈로그를 관리하는 데 사용됩니다.</p>
    </def>
</deflist>

178.<br/>**어떤 AWS 서비스가 엔드 투 엔드 성능 메트릭을 보고 분산 애플리케이션을 문제 해결할 수 있는 기능을 제공하나요?**
- A. AWS Cloud9
- B. AWS CodeStar
- C. AWS Cloud Map
- D. AWS X-Ray

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS X-Ray는 엔드 투 엔드 성능 메트릭을 보고 분산 애플리케이션을 문제 해결할 수 있는 기능을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Cloud9는 클라우드 기반 통합 개발 환경(IDE)입니다.</p>
        <p>AWS CodeStar는 애플리케이션 개발을 위한 통합 도구입니다.</p>
        <p>AWS Cloud Map은 서비스 검색을 위한 서비스입니다.</p>
    </def>
</deflist>

179.<br/>**AWS가 대량 구매로 인해 낮은 가변 비용을 제공할 수 있는 능력으로 보여주는 클라우드 컴퓨팅 이점은 무엇인가요?**
- A. 사용한 만큼 지불하는 가격 책정
- B. 고가용성
- C. 글로벌 도달 범위
- D. 규모의 경제

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        규모의 경제는 대량 구매로 인해 낮은 가변 비용을 제공할 수 있는 AWS의 능력을 보여줍니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>사용한 만큼 지불하는 가격 책정은 사용한 리소스에 대해서만 비용을 지불하는 방식입니다.</p>
        <p>고가용성은 시스템이 지속적으로 운영될 수 있는 능력입니다.</p>
        <p>글로벌 도달 범위는 전 세계적으로 서비스를 제공할 수 있는 능력입니다.</p>
    </def>
</deflist>

180.<br/>**어떤 AWS 서비스가 악의적인 활동 및 무단 작업을 모니터링하여 AWS 계정, 워크로드 및 Amazon S3에 저장된 데이터를 보호하는 위협 감지 기능을 제공하나요?**
- A. AWS Shield
- B. AWS Firewall Manager
- C. Amazon GuardDuty
- D. Amazon Inspector

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon GuardDuty는 악의적인 활동 및 무단 작업을 모니터링하여 위협 감지 기능을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Shield는 DDoS 공격 방어를 지원합니다.</p>
        <p>AWS Firewall Manager는 방화벽 규칙을 관리합니다.</p>
        <p>Amazon Inspector는 애플리케이션 보안 평가를 제공합니다.</p>
    </def>
</deflist>

181.<br/>**회사가 Docker 이미지를 저장하고 관리하기 위해 사용할 수 있는 AWS 서비스는 무엇인가요?**
- A. Amazon DynamoDB
- B. Amazon Kinesis Data Streams
- C. Amazon Elastic Container Registry (Amazon ECR)
- D. Amazon Elastic File System (Amazon EFS)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Elastic Container Registry (Amazon ECR)는 Docker 이미지를 저장하고 관리할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon DynamoDB는 NoSQL 데이터베이스 서비스입니다.</p>
        <p>Amazon Kinesis Data Streams는 실시간 데이터 스트리밍 서비스입니다.</p>
        <p>Amazon Elastic File System (Amazon EFS)는 파일 스토리지 서비스입니다.</p>
    </def>
</deflist>

182.<br/>**회사가 Amazon EC2 인스턴스에 대한 의도하지 않은 네트워크 액세스를 식별하고 운영 체제 취약성을 식별하는 자동화된 보안 평가 보고서를 필요로 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스 또는 기능을 사용해야 하나요?**
- A. AWS Trusted Advisor
- B. 보안 그룹
- C. Amazon Macie
- D. Amazon Inspector

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Inspector는 의도하지 않은 네트워크 액세스와 운영 체제 취약성을 식별하는 자동화된 보안 평가 보고서를 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Trusted Advisor는 모범 사례 권장 사항을 제공합니다.</p>
        <p>보안 그룹은 네트워크 트래픽을 제어하는 데 사용됩니다.</p>
        <p>Amazon Macie는 데이터 보안 및 개인 정보 보호를 위한 서비스입니다.</p>
    </def>
</deflist>

183.<br/>**글로벌 회사가 간단한 시간 추적 모바일 앱을 구축하고 있습니다. 앱은 전 세계적으로 운영되어야 하며, 수집된 데이터를 데이터베이스에 저장해야 합니다. 데이터는 사용자에게 가장 가까운 AWS 리전에서 액세스할 수 있어야 합니다. 최소한의 운영 오버헤드로 이러한 데이터 저장 요구 사항을 충족하려면 어떻게 해야 하나요?**
- A. 여러 리전에서 별도의 데이터베이스를 호스팅하기 위해 Amazon EC2 사용
- B. Amazon RDS 크로스 리전 복제 사용
- C. Amazon DynamoDB 글로벌 테이블 사용
- D. AWS Database Migration Service (AWS DMS) 사용

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon DynamoDB 글로벌 테이블은 최소한의 운영 오버헤드로 전 세계적으로 데이터를 저장하고 액세스할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>여러 리전에서 별도의 데이터베이스를 호스팅하는 것은 운영 오버헤드가 큽니다.</p>
        <p>Amazon RDS 크로스 리전 복제는 운영 오버헤드가 큽니다.</p>
        <p>AWS Database Migration Service (AWS DMS)는 데이터베이스 마이그레이션을 지원합니다.</p>
    </def>
</deflist>

184.<br/>**다음 중 AWS 클라우드의 경제적 이점은 무엇인가요? (두 가지 선택)**
- A. 인력 생산성 증가
- B. 사용자 데이터 암호화 필요성 감소
- C. 수동 준수 감사
- D. 총 소유 비용(TCO) 회계 단순화
- E. 빠른 제품 출시

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        인력 생산성 증가와 총 소유 비용(TCO) 회계 단순화는 AWS 클라우드의 경제적 이점입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>사용자 데이터 암호화 필요성 감소는 경제적 이점이 아닙니다.</p>
        <p>수동 준수 감사는 경제적 이점이 아닙니다.</p>
        <p>빠른 제품 출시는 경제적 이점이 아닙니다.</p>
    </def>
</deflist>

185.<br/>**AWS 공유 책임 모델에서 고객이 AWS로부터 완전히 상속받는 제어는 무엇인가요?**
- A. 패치 관리 제어
- B. 인식 및 교육 제어
- C. 물리적 및 환경적 제어
- D. 구성 관리 제어

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        물리적 및 환경적 제어는 고객이 AWS로부터 완전히 상속받는 제어입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>패치 관리 제어는 고객의 책임입니다.</p>
        <p>인식 및 교육 제어는 고객의 책임입니다.</p>
        <p>구성 관리 제어는 고객의 책임입니다.</p>
    </def>
</deflist>

186.<br/>**AWS 공유 책임 모델에 따르면, 고객의 책임은 무엇인가요?**
- A. 게스트 운영 체제 관리
- B. 인프라 장치 구성 유지 관리
- C. 호스트 운영 체제 및 가상화 관리
- D. 가용 영역을 지원하는 소프트웨어 유지 관리

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        게스트 운영 체제 관리는 고객의 책임입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>인프라 장치 구성 유지 관리는 AWS의 책임입니다.</p>
        <p>호스트 운영 체제 및 가상화 관리는 AWS의 책임입니다.</p>
        <p>가용 영역을 지원하는 소프트웨어 유지 관리는 AWS의 책임입니다.</p>
    </def>
</deflist>

187.<br/>**회사가 새로운 웹사이트 기능을 신속하게 반복적으로 제공하여 시장 출시 시간을 최소화하고자 합니다. 이 요구 사항은 어떤 AWS 클라우드 개념을 나타내나요?**
- A. 신뢰성
- B. 탄력성
- C. 민첩성
- D. 고가용성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        민첩성은 새로운 기능을 신속하게 반복적으로 제공하여 시장 출시 시간을 최소화하는 AWS 클라우드 개념입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>신뢰성은 시스템이 일관되게 작동할 수 있는 능력입니다.</p>
        <p>탄력성은 필요에 따라 리소스를 자동으로 확장하거나 축소할 수 있는 능력입니다.</p>
        <p>고가용성은 시스템이 지속적으로 운영될 수 있는 능력입니다.</p>
    </def>
</deflist>

188.<br/>**회사가 자연 재해 발생 시 인프라를 복구할 수 있는 능력을 향상시키고자 합니다. 이 능력은 AWS Well-Architected Framework의 어떤 원칙을 나타내나요?**
- A. 비용 최적화
- B. 성능 효율성
- C. 신뢰성
- D. 보안

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        신뢰성은 자연 재해 발생 시 인프라를 복구할 수 있는 능력을 나타내는 원칙입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>비용 최적화는 비용을 절감하는 방법입니다.</p>
        <p>성능 효율성은 리소스를 효율적으로 사용하는 방법입니다.</p>
        <p>보안은 시스템을 보호하는 방법입니다.</p>
    </def>
</deflist>

189.<br/>**어떤 AWS 서비스가 API 호출 및 사용자 활동을 추적하나요?**
- A. AWS Organizations
- B. AWS Config
- C. Amazon CloudWatch
- D. AWS CloudTrail

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS CloudTrail은 API 호출 및 사용자 활동을 추적합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Organizations는 여러 AWS 계정을 관리하는 서비스입니다.</p>
        <p>AWS Config는 리소스 구성을 추적하는 서비스입니다.</p>
        <p>Amazon CloudWatch는 모니터링 및 로그 관리 서비스입니다.</p>
    </def>
</deflist>

190.<br/>**어떤 AWS 서비스, 기능 또는 도구가 머신 러닝을 사용하여 비정상적인 클라우드 지출을 지속적으로 모니터링하나요?**
- A. Amazon Lookout for Metrics
- B. AWS Budgets
- C. Amazon CloudWatch
- D. AWS Cost Anomaly Detection

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Cost Anomaly Detection은 머신 러닝을 사용하여 비정상적인 클라우드 지출을 지속적으로 모니터링합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Lookout for Metrics는 비즈니스 메트릭을 모니터링합니다.</p>
        <p>AWS Budgets는 예산을 설정하고 비용을 추적합니다.</p>
        <p>Amazon CloudWatch는 모니터링 및 로그 관리 서비스입니다.</p>
    </def>
</deflist>

191.<br/>**회사가 Amazon EC2 인스턴스에 애플리케이션을 배포했습니다. 애플리케이션은 지난 6개월 동안 예상대로 실행되었지만, 지난 주에 사용자가 지연 문제를 보고했습니다. 시스템 관리자는 업무 시간 동안 CPU 사용률이 100%임을 발견했습니다. 회사는 수요를 충족하기 위해 확장 가능한 솔루션을 원합니다. 높은 수요 기간 동안 애플리케이션의 부하를 처리하기 위해 어떤 AWS 서비스 또는 기능을 사용해야 하나요?**
- A. Auto Scaling 그룹
- B. AWS Global Accelerator
- C. Amazon Route 53
- D. 탄력적 IP 주소

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Auto Scaling 그룹은 높은 수요 기간 동안 애플리케이션의 부하를 처리하기 위해 확장 가능한 솔루션을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Global Accelerator는 글로벌 애플리케이션 성능을 향상시킵니다.</p>
        <p>Amazon Route 53은 DNS 웹 서비스입니다.</p>
        <p>탄력적 IP 주소는 고정 IP 주소를 제공합니다.</p>
    </def>
</deflist>

192.<br/>**회사가 AWS로 마이그레이션하고 온프레미스에서 사용하는 동일한 보안 소프트웨어를 사용하고자 합니다. 보안 소프트웨어 공급업체는 AWS에서 서비스로 보안 소프트웨어를 제공합니다. 회사는 보안 솔루션을 어디에서 구매할 수 있나요?**
- A. AWS 파트너 솔루션 파인더
- B. AWS 지원 센터
- C. AWS 관리 콘솔
- D. AWS 마켓플레이스

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS 마켓플레이스는 보안 솔루션을 구매할 수 있는 곳입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS 파트너 솔루션 파인더는 파트너 솔루션을 찾는 데 사용됩니다.</p>
        <p>AWS 지원 센터는 지원 요청을 관리하는 데 사용됩니다.</p>
        <p>AWS 관리 콘솔은 AWS 리소스를 관리하는 데 사용됩니다.</p>
    </def>
</deflist>

193.<br/>**회사가 온프레미스 데이터 센터에서 중요한 데이터를 대량으로 생성하고 있습니다. 회사는 데이터를 AWS로 안전하게 전송하여 처리해야 합니다. 이러한 전송은 전용 연결을 통해 매일 발생해야 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. AWS Backup
- B. AWS DataSync
- C. AWS Direct Connect
- D. AWS Snowball

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Direct Connect는 전용 연결을 통해 데이터를 안전하게 전송할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Backup은 백업 및 복구 서비스를 제공합니다.</p>
        <p>AWS DataSync는 데이터 전송을 자동화하는 서비스입니다.</p>
        <p>AWS Snowball은 대규모 데이터 전송을 위한 물리적 장치입니다.</p>
    </def>
</deflist>

194.<br/>**회사가 AWS에서 프로덕션 워크로드를 실행하고자 합니다. 회사는 24시간 7일 동안 엔지니어의 기술 지원에 액세스하고자 합니다. 또한 AWS Health API 및 비즈니스 사용 사례에 대한 맥락적 아키텍처 지침에 액세스하고자 합니다. 회사는 강력한 IT 지원 팀을 보유하고 있으며, 컨시어지 지원이 필요하지 않습니다. 이 요구 사항을 가장 저렴한 비용으로 충족하는 AWS 지원 플랜은 무엇인가요?**
- A. AWS 기본 지원
- B. AWS 개발자 지원
- C. AWS 비즈니스 지원
- D. AWS 엔터프라이즈 지원

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS 비즈니스 지원은 24시간 7일 동안 기술 지원과 AWS Health API 및 아키텍처 지침을 제공하며, 가장 저렴한 비용으로 요구 사항을 충족합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS 기본 지원은 기술 지원을 제공하지 않습니다.</p>
        <p>AWS 개발자 지원은 업무 시간 동안 기술 지원을 제공합니다.</p>
        <p>AWS 엔터프라이즈 지원은 가장 높은 수준의 지원을 제공하지만, 비용이 가장 많이 듭니다.</p>
    </def>
</deflist>

195.<br/>**다음 중 데이터의 추출, 변환 및 로드(ETL)를 위해 사용되는 관리형 AWS 서비스는 무엇인가요?**
- A. Amazon Athena
- B. AWS Glue
- C. Amazon S3
- D. AWS Snowball Edge

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Glue는 데이터의 추출, 변환 및 로드(ETL)를 위해 사용되는 관리형 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Athena는 쿼리 서비스입니다.</p>
        <p>Amazon S3는 객체 스토리지 서비스입니다.</p>
        <p>AWS Snowball Edge는 대규모 데이터 전송을 위한 물리적 장치입니다.</p>
    </def>
</deflist>

196.<br/>**다음 중 AWS Identity and Access Management (IAM)으로 제어되는 작업은 무엇인가요? (두 가지 선택)**
- A. AWS 서비스 API 및 기타 특정 리소스에 대한 액세스 제어
- B. 지능형 위협 감지 및 지속적인 모니터링 제공
- C. 다중 인증(MFA)을 사용하여 AWS 환경 보호
- D. 사용자에게 AWS 데이터 센터에 대한 액세스 권한 부여
- E. 일반적인 웹 공격으로부터 애플리케이션을 보호하는 방화벽 보호 제공

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS 서비스 API 및 기타 특정 리소스에 대한 액세스 제어와 다중 인증(MFA)을 사용하여 AWS 환경 보호는 IAM으로 제어되는 작업입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>지능형 위협 감지 및 지속적인 모니터링 제공은 AWS의 다른 서비스에서 제공됩니다.</p>
        <p>사용자에게 AWS 데이터 센터에 대한 액세스 권한 부여는 IAM의 기능이 아닙니다.</p>
        <p>일반적인 웹 공격으로부터 애플리케이션을 보호하는 방화벽 보호 제공은 AWS WAF와 같은 서비스에서 제공됩니다.</p>
    </def>
</deflist>

197.<br/>**AWS 공유 책임 모델에 따르면, AWS와 고객 모두에게 적용되는 공유 제어는 무엇인가요? (두 가지 선택)**
- A. 리소스 구성 관리
- B. 네트워크 데이터 무결성
- C. 직원 인식 및 교육
- D. 물리적 및 환경적 보안
- E. 디스크 드라이브 교체 및 폐기

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        리소스 구성 관리와 직원 인식 및 교육은 AWS와 고객 모두에게 적용되는 공유 제어입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>네트워크 데이터 무결성은 AWS의 책임입니다.</p>
        <p>물리적 및 환경적 보안은 AWS의 책임입니다.</p>
        <p>디스크 드라이브 교체 및 폐기는 AWS의 책임입니다.</p>
    </def>
</deflist>

198.<br/>**AWS Identity and Access Management (IAM) 자격 증명 보고서에서 찾을 수 있는 정보는 무엇인가요? (두 가지 선택)**
- A. IAM 사용자가 AWS 관리 콘솔에 마지막으로 로그인한 날짜 및 시간
- B. IAM 사용자에게 할당된 다중 인증(MFA) 장치 유형
- C. 현재 로그인한 각 IAM 사용자의 User-Agent 브라우저 식별자
- D. IAM 사용자에 대해 다중 인증(MFA)이 활성화되었는지 여부
- E. 지난 30일 동안 각 IAM 사용자의 잘못된 로그인 시도 횟수

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        IAM 사용자가 AWS 관리 콘솔에 마지막으로 로그인한 날짜 및 시간과 IAM 사용자에 대해 다중 인증(MFA)이 활성화되었는지 여부는 IAM 자격 증명 보고서에서 찾을 수 있는 정보입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>IAM 사용자에게 할당된 다중 인증(MFA) 장치 유형은 자격 증명 보고서에 포함되지 않습니다.</p>
        <p>현재 로그인한 각 IAM 사용자의 User-Agent 브라우저 식별자는 자격 증명 보고서에 포함되지 않습니다.</p>
        <p>지난 30일 동안 각 IAM 사용자의 잘못된 로그인 시도 횟수는 자격 증명 보고서에 포함되지 않습니다.</p>
    </def>
</deflist>

199.<br/>**AWS Trusted Advisor 모범 사례 검사를 완전히 포함하는 가장 저렴한 AWS 지원 플랜은 무엇인가요?**
- A. AWS 엔터프라이즈 지원
- B. AWS 비즈니스 지원
- C. AWS 개발자 지원
- D. AWS 기본 지원

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS 비즈니스 지원은 AWS Trusted Advisor 모범 사례 검사를 완전히 포함하는 가장 저렴한 지원 플랜입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS 엔터프라이즈 지원은 더 높은 비용으로 추가 지원을 제공합니다.</p>
        <p>AWS 개발자 지원은 일부 Trusted Advisor 검사를 포함하지만, 전체 검사를 포함하지 않습니다.</p>
        <p>AWS 기본 지원은 Trusted Advisor 검사를 포함하지 않습니다.</p>
    </def>
</deflist>

200.<br/>**어떤 AWS 서비스가 도메인 등록, DNS 라우팅 및 서비스 상태 검사를 제공하나요?**
- A. AWS Direct Connect
- B. Amazon Route 53
- C. Amazon CloudFront
- D. Amazon API Gateway

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Route 53는 도메인 등록, DNS 라우팅 및 서비스 상태 검사를 제공하는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Direct Connect는 온프레미스 네트워크와 AWS 간의 전용 연결을 제공합니다.</p>
        <p>Amazon CloudFront는 콘텐츠 전송 네트워크(CDN) 서비스입니다.</p>
        <p>Amazon API Gateway는 API 관리를 지원합니다.</p>
    </def>
</deflist>

201.<br/>**은행이 연락 센터로 걸려온 통화 녹음을 6년 동안 저장해야 합니다. 녹음은 요청 시점부터 48시간 이내에 액세스할 수 있어야 합니다. 이러한 파일을 보관하기 위해 안전하고 비용 효율적인 솔루션을 제공하는 AWS 서비스는 무엇인가요?**
- A. Amazon DynamoDB
- B. Amazon S3 Glacier
- C. Amazon Connect
- D. Amazon ElastiCache

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon S3 Glacier는 장기 보관을 위한 안전하고 비용 효율적인 솔루션을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon DynamoDB는 NoSQL 데이터베이스 서비스입니다.</p>
        <p>Amazon Connect는 클라우드 기반 연락 센터 서비스입니다.</p>
        <p>Amazon ElastiCache는 인메모리 캐싱 서비스입니다.</p>
    </def>
</deflist>

202.<br/>**회사의 온프레미스 MySQL 데이터베이스를 Amazon RDS로 마이그레이션하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. AWS Direct Connect
- B. AWS Server Migration Service (AWS SMS)
- C. AWS Database Migration Service (AWS DMS)
- D. AWS Schema Conversion Tool (AWS SCT)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Database Migration Service (AWS DMS)는 온프레미스 MySQL 데이터베이스를 Amazon RDS로 마이그레이션하는 데 사용됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Direct Connect는 온프레미스 네트워크와 AWS 간의 전용 연결을 제공합니다.</p>
        <p>AWS Server Migration Service (AWS SMS)는 서버 마이그레이션을 지원합니다.</p>
        <p>AWS Schema Conversion Tool (AWS SCT)는 데이터베이스 스키마 변환을 지원합니다.</p>
    </def>
</deflist>

203.<br/>**회사가 온프레미스 IT 아키텍처에서 AWS 클라우드로 이동할 때 얻는 이점은 무엇인가요? (두 가지 선택)**
- A. 하드웨어 문제 해결, 용량 계획 및 조달 작업 감소 또는 제거
- B. 훈련된 IT 직원의 필요성 제거
- C. 클라우드로 마이그레이션된 모든 애플리케이션의 자동 보안 구성
- D. 재해 복구 계획의 필요성 제거
- E. 새로운 기능 및 애플리케이션의 빠른 배포

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        하드웨어 문제 해결, 용량 계획 및 조달 작업 감소 또는 제거와 새로운 기능 및 애플리케이션의 빠른 배포는 AWS 클라우드로 이동할 때 얻는 이점입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>훈련된 IT 직원의 필요성 제거는 AWS 클라우드로 이동할 때 얻는 이점이 아닙니다.</p>
        <p>클라우드로 마이그레이션된 모든 애플리케이션의 자동 보안 구성은 AWS 클라우드로 이동할 때 얻는 이점이 아닙니다.</p>
        <p>재해 복구 계획의 필요성 제거는 AWS 클라우드로 이동할 때 얻는 이점이 아닙니다.</p>
    </def>
</deflist>

204.<br/>**다음 중 AWS 클라우드 아키텍처를 디커플링하는 이점은 무엇인가요?**
- A. 지연 시간 감소
- B. 구성 요소를 독립적으로 업그레이드할 수 있는 능력
- C. 비용 감소
- D. 관리할 구성 요소 감소

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        구성 요소를 독립적으로 업그레이드할 수 있는 능력은 AWS 클라우드 아키텍처를 디커플링하는 이점입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>지연 시간 감소는 디커플링의 직접적인 이점이 아닙니다.</p>
        <p>비용 감소는 디커플링의 직접적인 이점이 아닙니다.</p>
        <p>관리할 구성 요소 감소는 디커플링의 직접적인 이점이 아닙니다.</p>
    </def>
</deflist>

205.<br/>**AWS 공유 책임 모델에 따르면, 고객의 책임은 무엇인가요?**
- A. Amazon EC2 인스턴스를 실행하는 하드웨어의 보안 유지 관리
- B. Amazon EC2 인스턴스의 게스트 운영 체제 패치
- C. AWS 글로벌 인프라의 보안 보호
- D. Amazon RDS 소프트웨어 패치

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon EC2 인스턴스의 게스트 운영 체제 패치는 고객의 책임입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon EC2 인스턴스를 실행하는 하드웨어의 보안 유지 관리는 AWS의 책임입니다.</p>
        <p>AWS 글로벌 인프라의 보안 보호는 AWS의 책임입니다.</p>
        <p>Amazon RDS 소프트웨어 패치는 AWS의 책임입니다.</p>
    </def>
</deflist>

206.<br/>**AWS Organizations 기능 중 여러 계정의 비용을 추적하고 결합된 비용을 보고하는 데 사용할 수 있는 기능은 무엇인가요?**
- A. 서비스 제어 정책(SCP)
- B. 비용 탐색기
- C. 통합 청구
- D. AWS Identity and Access Management (IAM)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        통합 청구는 여러 계정의 비용을 추적하고 결합된 비용을 보고하는 데 사용할 수 있는 기능입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>서비스 제어 정책(SCP)은 계정의 서비스 사용을 제어하는 데 사용됩니다.</p>
        <p>비용 탐색기는 비용을 분석하고 시각화하는 도구입니다.</p>
        <p>AWS Identity and Access Management (IAM)는 사용자 및 권한을 관리하는 서비스입니다.</p>
    </def>
</deflist>

207.<br/>**다음 중 AWS가 사용자에게 제공하는 클라우드 이점은 무엇인가요?**
- A. AWS 데이터 센터 하이퍼바이저 구성 능력
- B. 트래픽 증가에 대비하여 하드웨어를 미리 구매하는 능력
- C. 글로벌 규모로 AWS에 배포하는 능력
- D. 사용자 IT 환경에 대한 준수 감사

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        글로벌 규모로 AWS에 배포하는 능력은 AWS가 사용자에게 제공하는 클라우드 이점입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS 데이터 센터 하이퍼바이저 구성 능력은 사용자에게 제공되지 않습니다.</p>
        <p>트래픽 증가에 대비하여 하드웨어를 미리 구매하는 능력은 클라우드 이점이 아닙니다.</p>
        <p>사용자 IT 환경에 대한 준수 감사는 AWS가 제공하는 서비스가 아닙니다.</p>
    </def>
</deflist>

208.<br/>**전자상거래 회사가 IT 인프라를 온프레미스 데이터 센터에서 AWS 클라우드로 마이그레이션했습니다. 회사의 직접적인 책임은 어떤 비용인가요?**
- A. 애플리케이션 소프트웨어 라이선스 비용
- B. AWS의 하드웨어 인프라 비용
- C. AWS 서버의 전력 비용
- D. AWS 데이터 센터의 물리적 보안 비용

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        애플리케이션 소프트웨어 라이선스 비용은 회사의 직접적인 책임입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS의 하드웨어 인프라 비용은 AWS의 책임입니다.</p>
        <p>AWS 서버의 전력 비용은 AWS의 책임입니다.</p>
        <p>AWS 데이터 센터의 물리적 보안 비용은 AWS의 책임입니다.</p>
    </def>
</deflist>

209.<br/>**AWS Well-Architected Framework의 다섯 가지 원칙은 무엇인가요?**
- A. 암호화, 문서화, 속도, 하이브리드 설계 및 비용 최적화
- B. 컨테이너화, 비용 마진, 글로벌화, 마켓플레이스 및 개발자 운영
- C. 네트워크, 컴퓨팅, 스토리지, 보안 및 개발자 운영
- D. 운영 우수성, 신뢰성, 성능 효율성, 보안 및 비용 최적화

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        운영 우수성, 신뢰성, 성능 효율성, 보안 및 비용 최적화는 AWS Well-Architected Framework의 다섯 가지 원칙입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>암호화, 문서화, 속도, 하이브리드 설계 및 비용 최적화는 Well-Architected Framework의 원칙이 아닙니다.</p>
        <p>컨테이너화, 비용 마진, 글로벌화, 마켓플레이스 및 개발자 운영은 Well-Architected Framework의 원칙이 아닙니다.</p>
        <p>네트워크, 컴퓨팅, 스토리지, 보안 및 개발자 운영은 Well-Architected Framework의 원칙이 아닙니다.</p>
    </def>
</deflist>

210.<br/>**회사가 손으로 쓴 종이 양식으로 등록 신청서를 받고 있습니다. 회사는 양식 데이터를 백엔드 시스템에 수동으로 입력하는 프로세스를 사용하고 있습니다. 회사는 양식을 스캔하고 스캔된 PDF 파일에서 등록 데이터를 캡처하여 프로세스를 자동화하고자 합니다. 이 프로세스를 구축하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. Amazon Rekognition
- B. Amazon Textract
- C. Amazon Transcribe
- D. Amazon Comprehend

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Textract는 스캔된 PDF 파일에서 데이터를 캡처하여 프로세스를 자동화할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Rekognition은 이미지 및 비디오 분석 서비스입니다.</p>
        <p>Amazon Transcribe는 음성 인식 서비스입니다.</p>
        <p>Amazon Comprehend는 텍스트 분석 서비스입니다.</p>
    </def>
</deflist>

211.<br/>**회사가 대량의 이미지를 조직, 특성화 및 검색하기 위해 사용할 수 있는 AWS 서비스는 무엇인가요?**
- A. Amazon Transcribe
- B. Amazon Rekognition
- C. Amazon Aurora
- D. Amazon QuickSight

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Rekognition은 대량의 이미지를 조직, 특성화 및 검색할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Transcribe는 음성 인식 서비스입니다.</p>
        <p>Amazon Aurora는 관계형 데이터베이스 서비스입니다.</p>
        <p>Amazon QuickSight는 비즈니스 인텔리전스 서비스입니다.</p>
    </def>
</deflist>

212.<br/>**전자상거래 회사가 CPU 사용률을 기준으로 EC2 인스턴스를 추가 및 제거하기 위해 Amazon EC2 Auto Scaling을 사용하고자 합니다. 이 목표를 달성하기 위해 Amazon EC2 Auto Scaling 작업을 시작할 수 있는 AWS 서비스 또는 기능은 무엇인가요?**
- A. Amazon Simple Queue Service (Amazon SQS)
- B. Amazon Simple Notification Service (Amazon SNS)
- C. AWS Systems Manager
- D. Amazon CloudWatch 경보

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon CloudWatch 경보는 CPU 사용률을 기준으로 Amazon EC2 Auto Scaling 작업을 시작할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Simple Queue Service (Amazon SQS)는 메시지 대기열 서비스입니다.</p>
        <p>Amazon Simple Notification Service (Amazon SNS)는 알림 메시징 서비스입니다.</p>
        <p>AWS Systems Manager는 시스템 관리를 지원하는 서비스입니다.</p>
    </def>
</deflist>

213.<br/>**회사가 AWS 클라우드에서 애플리케이션 코드에 대한 개인 버전 관리 시스템을 호스팅하고자 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. AWS CodePipeline
- B. AWS CodeStar
- C. AWS CodeCommit
- D. AWS CodeDeploy

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS CodeCommit은 애플리케이션 코드에 대한 개인 버전 관리 시스템을 호스팅할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS CodePipeline은 지속적 통합 및 배포(CI/CD) 서비스입니다.</p>
        <p>AWS CodeStar는 애플리케이션 개발을 위한 통합 도구입니다.</p>
        <p>AWS CodeDeploy는 애플리케이션 배포를 자동화하는 서비스입니다.</p>
    </def>
</deflist>

214.<br/>**회사가 사용자 정의 지출 한도에 도달하거나 초과했음을 알리는 알림을 설정할 수 있는 AWS 서비스 또는 도구는 무엇인가요?**
- A. AWS Budgets
- B. AWS Trusted Advisor
- C. AWS CloudTrail
- D. AWS Support

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Budgets는 사용자 정의 지출 한도에 도달하거나 초과했음을 알리는 알림을 설정할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Trusted Advisor는 모범 사례 권장 사항을 제공합니다.</p>
        <p>AWS CloudTrail은 API 호출 및 사용자 활동을 추적합니다.</p>
        <p>AWS Support는 지원 요청을 관리합니다.</p>
    </def>
</deflist>

215.<br/>**어떤 AWS 서비스가 정적 웹사이트를 호스팅하는 데 사용되나요?**
- A. Amazon S3
- B. Amazon Elastic Block Store (Amazon EBS)
- C. AWS CloudFormation
- D. Amazon Elastic File System (Amazon EFS)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon S3는 정적 웹사이트를 호스팅하는 데 사용되는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Elastic Block Store (Amazon EBS)는 블록 스토리지 서비스입니다.</p>
        <p>AWS CloudFormation은 인프라를 코드로 관리하는 서비스입니다.</p>
        <p>Amazon Elastic File System (Amazon EFS)는 파일 스토리지 서비스입니다.</p>
    </def>
</deflist>

216.<br/>**클라우드에서 실행되는 웹 애플리케이션을 SQL 인젝션 공격 및 크로스 사이트 스크립팅으로부터 보호하기 위한 내장 엔진을 포함하는 AWS 서비스는 무엇인가요?**
- A. AWS WAF
- B. AWS Shield Advanced
- C. Amazon GuardDuty
- D. Amazon Detective

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS WAF는 SQL 인젝션 공격 및 크로스 사이트 스크립팅으로부터 웹 애플리케이션을 보호하는 내장 엔진을 포함하는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Shield Advanced는 DDoS 공격 방어를 지원합니다.</p>
        <p>Amazon GuardDuty는 AWS 워크로드에 대한 위협을 자동으로 모니터링합니다.</p>
        <p>Amazon Detective는 보안 문제를 조사하는 데 사용됩니다.</p>
    </def>
</deflist>

217.<br/>**회사가 코어당 소프트웨어 라이선스를 보유하고 있습니다. 이 라이선스 유형에 대해 어떤 Amazon EC2 인스턴스 구매 옵션을 사용해야 하나요?**
- A. 예약 인스턴스
- B. 전용 호스트
- C. 스팟 인스턴스
- D. 전용 인스턴스

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        전용 호스트는 코어당 소프트웨어 라이선스를 사용하는 데 적합한 Amazon EC2 인스턴스 구매 옵션입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>예약 인스턴스는 특정 용량을 예약하는 옵션입니다.</p>
        <p>스팟 인스턴스는 유휴 용량을 저렴한 가격에 사용하는 옵션입니다.</p>
        <p>전용 인스턴스는 단일 고객 전용 하드웨어에서 실행되는 인스턴스입니다.</p>
    </def>
</deflist>

218.<br/>**회사가 새로운 애플리케이션을 위해 사용자 인증을 설정해야 합니다. 사용자는 사용자 이름과 비밀번호를 사용하여 직접 로그인하거나 타사 제공자를 통해 로그인할 수 있어야 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. AWS Single Sign-On
- B. AWS Signer
- C. Amazon Cognito
- D. AWS Directory Service

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Cognito는 사용자 이름과 비밀번호를 사용하여 직접 로그인하거나 타사 제공자를 통해 로그인할 수 있는 사용자 인증을 설정할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Single Sign-On은 여러 AWS 계정 및 애플리케이션에 대한 단일 로그인 기능을 제공합니다.</p>
        <p>AWS Signer는 코드 서명 서비스를 제공합니다.</p>
        <p>AWS Directory Service는 디렉터리 서비스를 제공합니다.</p>
    </def>
</deflist>

219.<br/>**회사의 IT 팀이 MySQL 데이터베이스 서버 클러스터를 관리하고 있습니다. IT 팀은 데이터베이스를 패치하고 클러스터의 데이터에 대한 백업 스냅샷을 생성해야 합니다. 회사는 이러한 작업이 자동으로 완료되도록 AWS로 워크로드를 이동하고자 합니다. 이 요구 사항을 충족하기 위해 무엇을 해야 하나요?**
- A. Amazon EC2 인스턴스에 MySQL 데이터베이스 서버 클러스터 배포
- B. MySQL 데이터베이스를 사용하여 Amazon RDS 사용
- C. AWS CloudFormation 템플릿을 사용하여 Amazon EC2 인스턴스에 MySQL 데이터베이스 서버 배포
- D. 모든 MySQL 데이터베이스 데이터를 Amazon S3로 마이그레이션

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        MySQL 데이터베이스를 사용하여 Amazon RDS를 사용하면 데이터베이스 패치 및 백업 스냅샷 작업이 자동으로 완료됩니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon EC2 인스턴스에 MySQL 데이터베이스 서버 클러스터를 배포하면 수동 관리가 필요합니다.</p>
        <p>AWS CloudFormation 템플릿을 사용하여 Amazon EC2 인스턴스에 MySQL 데이터베이스 서버를 배포하면 수동 관리가 필요합니다.</p>
        <p>모든 MySQL 데이터베이스 데이터를 Amazon S3로 마이그레이션하면 데이터베이스 기능을 사용할 수 없습니다.</p>
    </def>
</deflist>

220.<br/>**Amazon GuardDuty의 주요 사용 사례는 무엇인가요?**
- A. DDoS 공격 방지
- B. SQL 인젝션 공격 방지
- C. AWS 워크로드에 대한 위협 자동 모니터링
- D. AWS 리소스 자동 프로비저닝

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon GuardDuty의 주요 사용 사례는 AWS 워크로드에 대한 위협을 자동으로 모니터링하는 것입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>DDoS 공격 방지는 AWS Shield에서 제공됩니다.</p>
        <p>SQL 인젝션 공격 방지는 AWS WAF에서 제공됩니다.</p>
        <p>AWS 리소스 자동 프로비저닝은 다른 AWS 서비스에서 제공됩니다.</p>
    </def>
</deflist>

221.<br/>**다음 중 AWS 클라우드로의 마이그레이션의 비즈니스 가치를 설명하는 문장은 무엇인가요? (두 가지 선택)**
- A. 엔터프라이즈 애플리케이션을 AWS 클라우드로 마이그레이션하면 이러한 애플리케이션이 자동으로 모바일 장치에서 사용할 수 있게 됩니다.
- B. AWS의 가용성과 보안은 서비스 수준 계약(SLA)을 개선하면서 위험과 계획되지 않은 다운타임을 줄일 수 있는 능력을 제공합니다.
- C. AWS 클라우드로 마이그레이션한 회사는 고가용성과 재해 복구 계획의 필요성을 제거합니다.
- D. AWS 클라우드로 마이그레이션한 회사는 인프라와 관련된 IT 비용을 줄여 다른 영역에 재투자할 예산을 확보합니다.
- E. AWS 클라우드로의 마이그레이션은 회사가 모든 엔터프라이즈 애플리케이션을 재설계하고 다시 작성해야 하기 때문에 애플리케이션을 현대화합니다.

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS의 가용성과 보안은 SLA를 개선하면서 위험과 계획되지 않은 다운타임을 줄일 수 있는 능력을 제공하며, AWS 클라우드로 마이그레이션한 회사는 인프라와 관련된 IT 비용을 줄여 다른 영역에 재투자할 예산을 확보합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>엔터프라이즈 애플리케이션을 AWS 클라우드로 마이그레이션하면 자동으로 모바일 장치에서 사용할 수 있게 되지 않습니다.</p>
        <p>AWS 클라우드로 마이그레이션한 회사는 고가용성과 재해 복구 계획의 필요성을 제거하지 않습니다.</p>
        <p>AWS 클라우드로의 마이그레이션은 회사가 모든 엔터프라이즈 애플리케이션을 재설계하고 다시 작성해야 하기 때문에 애플리케이션을 현대화하지 않습니다.</p>
    </def>
</deflist>

222.<br/>**회사가 Amazon S3에 저장된 데이터에서 신용 카드 번호와 같은 개인 식별 정보를 식별해야 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. Amazon Inspector
- B. AWS Shield
- C. Amazon GuardDuty
- D. Amazon Macie

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Macie는 Amazon S3에 저장된 데이터에서 개인 식별 정보를 식별할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Inspector는 애플리케이션 보안 평가를 제공합니다.</p>
        <p>AWS Shield는 DDoS 공격 방어를 지원합니다.</p>
        <p>Amazon GuardDuty는 AWS 워크로드에 대한 위협을 자동으로 모니터링합니다.</p>
    </def>
</deflist>

223.<br/>**다음 중 SQL 인젝션, 크로스 사이트 스크립팅 및 DDoS 공격으로부터 워크로드를 보호하도록 설계된 AWS 서비스 또는 도구는 무엇인가요? (두 가지 선택)**
- A. VPC 엔드포인트
- B. 가상 프라이빗 게이트웨이
- C. AWS Shield Standard
- D. AWS Config
- E. AWS WAF

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Shield Standard와 AWS WAF는 SQL 인젝션, 크로스 사이트 스크립팅 및 DDoS 공격으로부터 워크로드를 보호하도록 설계된 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>VPC 엔드포인트는 VPC 내에서 AWS 서비스에 대한 프라이빗 연결을 제공합니다.</p>
        <p>가상 프라이빗 게이트웨이는 온프레미스 네트워크와 VPC 간의 연결을 제공합니다.</p>
        <p>AWS Config는 리소스 구성을 추적하는 서비스입니다.</p>
    </def>
</deflist>

224.<br/>**회사가 과거 소비를 기반으로 AWS 리소스의 미래 비용 및 사용량을 예측하고자 합니다. 이 예측을 제공하는 AWS 서비스 또는 도구는 무엇인가요?**
- A. AWS 비용 및 사용 보고서
- B. Amazon Forecast
- C. AWS 가격 계산기
- D. 비용 탐색기

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        비용 탐색기는 과거 소비를 기반으로 AWS 리소스의 미래 비용 및 사용량을 예측할 수 있는 도구입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS 비용 및 사용 보고서는 비용 및 사용 데이터를 제공합니다.</p>
        <p>Amazon Forecast는 비즈니스 메트릭을 예측하는 서비스입니다.</p>
        <p>AWS 가격 계산기는 AWS 서비스의 비용을 계산하는 도구입니다.</p>
    </def>
</deflist>

225.<br/>**다음 중 기본적으로 여러 가용 영역에 걸쳐 복제를 제공하는 클라우드 네이티브 스토리지를 사용하는 AWS 서비스는 무엇인가요? (두 가지 선택)**
- A. Amazon ElastiCache
- B. Amazon RDS for Oracle
- C. Amazon Neptune
- D. Amazon DocumentDB (MongoDB 호환)
- E. Amazon Redshift

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Neptune과 Amazon DocumentDB (MongoDB 호환)는 기본적으로 여러 가용 영역에 걸쳐 복제를 제공하는 클라우드 네이티브 스토리지를 사용하는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon ElastiCache는 인메모리 캐싱 서비스입니다.</p>
        <p>Amazon RDS for Oracle은 관계형 데이터베이스 서비스입니다.</p>
        <p>Amazon Redshift는 데이터 웨어하우스 서비스입니다.</p>
    </def>
</deflist>

226.<br/>**다음 중 서버리스 AWS 서비스는 무엇인가요? (두 가지 선택)**
- A. AWS Fargate
- B. Amazon Managed Streaming for Apache Kafka
- C. Amazon EMR
- D. Amazon S3
- E. Amazon EC2

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Fargate와 Amazon S3는 서버리스 AWS 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Managed Streaming for Apache Kafka는 서버리스 서비스가 아닙니다.</p>
        <p>Amazon EMR은 서버리스 서비스가 아닙니다.</p>
        <p>Amazon EC2는 서버리스 서비스가 아닙니다.</p>
    </def>
</deflist>

227.<br/>**AWS 공유 책임 모델에 따르면, AWS의 책임은 무엇인가요?**
- A. Amazon EC2 인스턴스에 게스트 운영 체제 패치 적용
- B. 인적 자원 정보 관리(HRIM) 시스템 모니터링 제공
- C. Amazon RDS 인스턴스의 자동 백업 수행
- D. AWS 서비스 실행 비용 최적화

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon RDS 인스턴스의 자동 백업 수행은 AWS의 책임입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon EC2 인스턴스에 게스트 운영 체제 패치 적용은 고객의 책임입니다.</p>
        <p>인적 자원 정보 관리(HRIM) 시스템 모니터링 제공은 고객의 책임입니다.</p>
        <p>AWS 서비스 실행 비용 최적화는 고객의 책임입니다.</p>
    </def>
</deflist>

228.<br/>**회사가 Amazon RDS에 PostgreSQL 데이터베이스를 배포해야 합니다. 데이터베이스는 고가용성과 내결함성을 가져야 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 솔루션을 사용해야 하나요?**
- A. 단일 가용 영역을 사용하는 Amazon RDS
- B. Amazon RDS 스냅샷
- C. 여러 가용 영역을 사용하는 Amazon RDS
- D. AWS Database Migration Service (AWS DMS)

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        여러 가용 영역을 사용하는 Amazon RDS는 고가용성과 내결함성을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>단일 가용 영역을 사용하는 Amazon RDS는 고가용성과 내결함성을 제공하지 않습니다.</p>
        <p>Amazon RDS 스냅샷은 백업을 위한 기능입니다.</p>
        <p>AWS Database Migration Service (AWS DMS)는 데이터베이스 마이그레이션을 지원합니다.</p>
    </def>
</deflist>

229.<br/>**회사가 애플리케이션의 사용자 인증 프로세스에 얼굴 인식을 추가하고자 합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. Amazon Polly
- B. Amazon Transcribe
- C. Amazon Lex
- D. Amazon Rekognition

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Rekognition은 얼굴 인식을 추가할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon Polly는 텍스트를 음성으로 변환하는 서비스입니다.</p>
        <p>Amazon Transcribe는 음성을 텍스트로 변환하는 서비스입니다.</p>
        <p>Amazon Lex는 대화형 인터페이스를 구축하는 서비스입니다.</p>
    </def>
</deflist>

230.<br/>**회사가 기본 리소스를 프로비저닝할 필요 없이 AWS 클라우드에 애플리케이션을 신속하게 업로드할 수 있는 기능을 원합니다. 이 요구 사항을 충족하는 AWS 서비스는 무엇인가요?**
- A. AWS CloudFormation
- B. AWS Elastic Beanstalk
- C. AWS CodeDeploy
- D. AWS CodeCommit

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Elastic Beanstalk는 기본 리소스를 프로비저닝할 필요 없이 애플리케이션을 신속하게 업로드할 수 있는 기능을 제공합니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS CloudFormation은 인프라를 코드로 관리하는 서비스입니다.</p>
        <p>AWS CodeDeploy는 애플리케이션 배포를 자동화하는 서비스입니다.</p>
        <p>AWS CodeCommit은 버전 관리 시스템을 제공합니다.</p>
    </def>
</deflist>

231.<br/>**어떤 AWS 서비스가 Amazon EC2 인스턴스의 CPU 사용률을 모니터링하나요?**
- A. AWS CloudTrail
- B. Amazon Inspector
- C. AWS Config
- D. Amazon CloudWatch

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon CloudWatch는 Amazon EC2 인스턴스의 CPU 사용률을 모니터링하는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS CloudTrail은 API 호출 및 사용자 활동을 추적합니다.</p>
        <p>Amazon Inspector는 애플리케이션 보안 평가를 제공합니다.</p>
        <p>AWS Config는 리소스 구성을 추적하는 서비스입니다.</p>
    </def>
</deflist>

232.<br/>**회사가 AWS 리소스를 라벨링하여 비용을 분류하고 추적할 수 있도록 해야 합니다. 이 요구 사항을 충족하기 위해 무엇을 해야 하나요?**
- A. 비용 할당 태그 사용
- B. AWS Identity and Access Management (IAM) 사용
- C. AWS Organizations 사용
- D. AWS 비용 관리 커버리지 보고서 사용

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        비용 할당 태그는 AWS 리소스를 라벨링하여 비용을 분류하고 추적할 수 있는 방법입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Identity and Access Management (IAM)는 사용자 및 권한을 관리하는 서비스입니다.</p>
        <p>AWS Organizations는 여러 AWS 계정을 관리하는 서비스입니다.</p>
        <p>AWS 비용 관리 커버리지 보고서는 비용 및 사용 데이터를 제공합니다.</p>
    </def>
</deflist>

233.<br/>**회사가 직원들이 개인 장치를 통해 회사에서 제공하는 데스크톱에 안전하게 액세스할 수 있도록 가상 데스크톱 인프라에 액세스할 수 있기를 원합니다. 이 요구 사항을 충족하기 위해 어떤 AWS 서비스를 사용해야 하나요?**
- A. Amazon AppStream 2.0
- B. AWS AppSync
- C. Amazon FSx for Windows File Server
- D. Amazon WorkSpaces

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon WorkSpaces는 가상 데스크톱 인프라에 액세스할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon AppStream 2.0은 애플리케이션 스트리밍 서비스입니다.</p>
        <p>AWS AppSync는 GraphQL API를 관리하는 서비스입니다.</p>
        <p>Amazon FSx for Windows File Server는 파일 스토리지 서비스입니다.</p>
    </def>
</deflist>

234.<br/>**AWS Organizations를 사용하여 회사가 완료할 수 있는 작업은 무엇인가요?**
- A. 전 세계적으로 애플리케이션 배포 상태 추적
- B. 모든 계정에서 사용되지 않거나 과소 사용된 AWS 리소스 제거
- C. 모든 계정에서 DDoS 보호 활성화
- D. 계정 간에 사전 구매한 Amazon EC2 리소스 공유

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        계정 간에 사전 구매한 Amazon EC2 리소스를 공유할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>전 세계적으로 애플리케이션 배포 상태를 추적하는 것은 AWS Organizations의 기능이 아닙니다.</p>
        <p>모든 계정에서 사용되지 않거나 과소 사용된 AWS 리소스를 제거하는 것은 AWS Organizations의 기능이 아닙니다.</p>
        <p>모든 계정에서 DDoS 보호를 활성화하는 것은 AWS Organizations의 기능이 아닙니다.</p>
    </def>
</deflist>

235.<br/>**사용자가 자신의 IAM 사용자 비밀번호를 변경할 수 있는 권한을 부여받았습니다. 사용자가 비밀번호를 변경할 수 있는 AWS 서비스는 무엇인가요? (두 가지 선택)**
- A. AWS Command Line Interface (AWS CLI)
- B. AWS Key Management Service (AWS KMS)
- C. AWS Management Console
- D. AWS Resource Access Manager (AWS RAM)
- E. AWS Secrets Manager

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS Command Line Interface (AWS CLI)와 AWS Management Console을 사용하여 비밀번호를 변경할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS Key Management Service (AWS KMS)는 암호화 키를 관리하는 서비스입니다.</p>
        <p>AWS Resource Access Manager (AWS RAM)는 리소스 공유를 관리하는 서비스입니다.</p>
        <p>AWS Secrets Manager는 비밀을 관리하는 서비스입니다.</p>
    </def>
</deflist>

236.<br/>**회사가 Amazon EC2 인스턴스에서 애플리케이션을 실행해야 합니다. 인스턴스는 언제든지 중단될 수 없습니다. 회사는 장기 약정이나 선결제 없이 인스턴스를 구매할 수 있는 옵션이 필요합니다. 이 요구 사항을 가장 비용 효율적으로 충족하는 인스턴스 구매 옵션은 무엇인가요?**
- A. 온디맨드 인스턴스
- B. 스팟 인스턴스
- C. 전용 호스트
- D. 예약 인스턴스

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        온디맨드 인스턴스는 장기 약정이나 선결제 없이 인스턴스를 구매할 수 있는 옵션입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>스팟 인스턴스는 유휴 용량을 저렴한 가격에 사용하는 옵션이지만, 중단될 수 있습니다.</p>
        <p>전용 호스트는 특정 하드웨어를 예약하는 옵션으로, 비용이 더 많이 듭니다.</p>
        <p>예약 인스턴스는 장기 약정이 필요합니다.</p>
    </def>
</deflist>

237.<br/>**회사가 웹 애플리케이션을 실행하기 위해 Amazon EC2 인스턴스를 사용하고 있습니다. 회사는 온디맨드 인스턴스와 스팟 인스턴스를 사용하고 있습니다. 회사는 두 유형의 인스턴스에 대한 월별 지출을 시각화해야 합니다. 이 요구 사항을 충족하는 AWS 서비스 또는 기능은 무엇인가요?**
- A. AWS 비용 탐색기
- B. AWS 예산
- C. Amazon CloudWatch
- D. AWS 비용 카테고리

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        AWS 비용 탐색기는 온디맨드 인스턴스와 스팟 인스턴스에 대한 월별 지출을 시각화할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>AWS 예산은 예산을 설정하고 비용을 추적하는 도구입니다.</p>
        <p>Amazon CloudWatch는 모니터링 및 로그 관리 서비스입니다.</p>
        <p>AWS 비용 카테고리는 비용을 분류하는 도구입니다.</p>
    </def>
</deflist>

238.<br/>**사용자가 AWS Identity and Access Management (IAM)를 사용하여 완료할 수 있는 작업은 무엇인가요?**
- A. 애플리케이션 구성 파일의 JSON 구문 유효성 검사
- B. Amazon API Gateway 호출의 로그 분석
- C. Amazon EC2 인스턴스로의 트래픽 필터링
- D. Amazon EC2 인스턴스에서 실행되는 애플리케이션에 권한 부여

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon EC2 인스턴스에서 실행되는 애플리케이션에 권한을 부여할 수 있습니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>애플리케이션 구성 파일의 JSON 구문 유효성 검사는 IAM의 기능이 아닙니다.</p>
        <p>Amazon API Gateway 호출의 로그 분석은 IAM의 기능이 아닙니다.</p>
        <p>Amazon EC2 인스턴스로의 트래픽 필터링은 IAM의 기능이 아닙니다.</p>
    </def>
</deflist>

239.<br/>**회사가 페타바이트 규모의 반구조화 및 구조화된 데이터에 대해 비즈니스 인텔리전스 및 운영 분석 보고서를 생성해야 합니다. 이러한 보고서는 Amazon S3 데이터 레이크에 있는 데이터에 대한 표준 SQL 쿼리에서 생성됩니다. 이 데이터를 분석할 수 있는 AWS 서비스는 무엇인가요?**
- A. Amazon RDS
- B. Amazon Neptune
- C. Amazon DynamoDB
- D. Amazon Redshift

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        Amazon Redshift는 Amazon S3 데이터 레이크에 있는 데이터를 분석할 수 있는 서비스입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>Amazon RDS는 관계형 데이터베이스 서비스입니다.</p>
        <p>Amazon Neptune은 그래프 데이터베이스 서비스입니다.</p>
        <p>Amazon DynamoDB는 NoSQL 데이터베이스 서비스입니다.</p>
    </def>
</deflist>

240.<br/>**회사가 AWS 클라우드 서비스 플랫폼에서 워크로드를 실행할 때 시스템이 자동으로 장애에서 복구됩니다. 이 상황은 AWS Well-Architected Framework의 어떤 원칙을 나타내나요?**
- A. 비용 최적화
- B. 운영 우수성
- C. 성능 효율성
- D. 신뢰성

<deflist collapsible="true">
    <def title="정답" default-state="collapsed">
        신뢰성은 시스템이 자동으로 장애에서 복구되는 능력을 나타내는 원칙입니다.
    </def>
    <def title="오답" default-state="collapsed">
        <p>비용 최적화는 비용을 절감하는 방법입니다.</p>
        <p>운영 우수성은 운영 프로세스를 개선하는 방법입니다.</p>
        <p>성능 효율성은 리소스를 효율적으로 사용하는 방법입니다.</p>
    </def>
</deflist>