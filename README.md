안녕하세요. 데이터 및 클라우드 인프라 엔지니어로 일 하고 있습니다. 더 자세한 이력은 [Linkedin](https://www.linkedin.com/in/1ambda) 에서 확인하실 수 있습니다.

대기업, 20명 이하의 스타트업, 유니콘과 같이 다양한 규모의 회사에서 아래와 같은 노동과 경험을 쌓아 왔습니다.  
몇년 전 부터는 먹고사느라 (..) 바빠서 블로그에 글 쓸 시간이 없지만 작은 [블로그](https://1ambda.blog/) 를 하나 운영하고 있습니다.  
간간히 올리곤 하는 엔지니어링에 관한 짧은 생각들은 제 [Facebook](https://www.facebook.com/1ambda) 에서 보실 수 있습니다.  


### Data / ML Pipeline

- 데이터가 흘러다니는 파이프라인을 만들 수 있습니다. 수집과 저장을 넘어 데이터를 서비스에 내보내기 위한 시스템을 AWS 의 다양한 서비스를 이용해 회사 규모에 맞추어 비용 효율적으로 구축할 수 있습니다
- 로그 포맷을 설계 / 사용 / 관리해온 수년간의 경험을 바탕으로 로그 및 데이터 파이프라인을 올바르게 설계해 추후 시스템의 규모나 비용에 의해 문제가 될 소지를 미리 제거할 수 있습니다
- 데이터를 사람이 사용하기 (SQL, ML) 위한 각종 시스템들을 빠르게 설치하고 규모에 따라 운영할 수 있으며 비즈니스 / MKT 등 다양한 조직의 사람들이 편리하게 데이터를 소비하기 위한 방법들을 제공할 수 있습니다. 필요할 경우 도구뿐만 아니라 비즈니스에 필요한 데이터를 직접 가공해 최종 고객까지 전달하는 수준까지 관여해, 영업 및 비즈니스 확장에 기여해 오고 있습니다
- 기계학습 등을 위한 ML 인프라를 팀 내 사용자의 스킬셋과 비용을 고려해 적절한 수준에서 구성하고 운영할 수 있습니다. 예를 들어, 모델의 학습과 튜닝을 편리하게 진행할 수 있는 JupyterHub, MLFlow, Viewer 와 같은 도구와 Spark / Dask 같은 다양한 프레임워크를 선택적으로 사용할 수 있도록 Kubernetes 위에서 제공해 리소스 탄력적으로 운영해온 경험이 있습니다. 또한 ML 엔지니어가 노트북을 쉽게 스케쥴링하고 만들어진 모델을 서빙할 수 있도록 Airflow, BentoML 등의 도구는 물론 커스텀 유틸리티 제작을 통해 팀 내 머신러닝 작업의 생산성을 부스팅 할 수 있습니다.
- 잘 쌓인 데이터를 서비스에 내보내기 위해 Spark / Flink 등으로 가공할 수 있으며 이를 이용해 통계 / 추천 등 사용자가 마주하는 서비스에 내보낸 경험이 있습니다
- EMR 내 Presto, Spark, Flink 등과 같은 각종 컴포넌트를 워크로드 및 애플리케이션 유형별로 분리해 머신 사이즈 및 특성에 맞는 옵션질 (...) 과 비용절감을 할 수 있으며 이로 인한 멀티 클러스터 운영을 적은 물리 노동으로 해낼 수 있습니다. 이외에도 서비스에 필요할 경우 AWS 에서 제공하지 않는 Druid 와 같은 커스텀 스토리지를 도입해 내부 엔진을 이해하고 직접 관리할 수 있으며, 이를 통해 서비스에 필요항 데이터를 (근) 실시간으로 제공한 경험이 있습니다

### Infrastructure & DevOps

- AWS Account 를 이전하며 전체 리소스를 Terraform 으로 빌딩해 옮긴 경험이 있으며 AWS 리소스가 필요할 경우 비용과 용도에 맞추어 Provisioning 하며 Cross Account 이슈를 다룰 수 있습니다
- 서비스와 데이터 파이프라인에 필요한 AWS 리소스를 다양하게 경험해보았으며, Provisioning 이후 필요한 도구를 설치 및 관리하기 위해 Ansible 을 이용하고 있으며 이를 이용해 다양한 커스텀 스토리지나 서비스를 운영해 오고 있습니다
- CI/CD 를 위한 정책을 세우고 필요한 시스템을 세팅 및 운영할 수 있습니다. 과거에는 Jenkins 를 사용했었고 최근에는 AWS 에서 제공하는 CodeBuild 등의 서비스와 Spinanker 를 조합해 사용하고 있습니다
- Kubernetes 클러스터를 직접 (Kops) 혹은 AWS 서비스 위에서 설치하고 운영할 수 있습니다.  AWS EKS 가 도입된 시점부터 1.13 부터 1.21 까지 서비스에 나가거나 데이터 처리를 위한 Self-managed / Managed 클러스터를 다수를 문제 없이 업그레이드 해온 경험이 있습니다.
- Kubernetes 클러스터를 비용 효율적으로 관리하기 위해 워크로드에 따라 On-demand / Spot 노드를 구성하고, 필요한 리소스에 맞추어 Affinity, nodeLabel 등의 정책을 세우고 리소스를 할당할 수 있습니다.
- Backoffice / API 용도 뿐만 아니라 아니라 데이터 처리용 Kubernetes 클러스터를 별도로 구성하고 운영한 경험이 있습니다
- Kubernetes Cluster 의 스케일링 / 로깅 / 모니터링 등에 필요한 Add-on 등을 직접 설치 및 관리할 수 있습니다. (EKF, Prometheus, Grafana, Cluster Autoscaler 등)
- 팀 내 사용자에게 PromQL  또는 AWS Cloudwatch Search Expression 등을 사용해 Grafana 대시보드를 만들어 Kubernetes Cluster / Application (WEB, API) / AWS 리소스에 대한 전반적인 모니터링과 관리용 뷰를 제공할 수 있습니다


### Service: API & Back Office
- B2C 서비스로 나가는 통계용 API 와 그 기반 데이터를 개발하고 운영해오고 있습니다
- API 서버와 Database 를 다루기 위해 JVM 언어 위에서 Spring 과 그 기반 생태계의 라이브러리를 (JPA 등) 주로 사용해 오며 이해도를 높여오고 있으며, 위의 기술로 만들어진 시스템을 모니터링하고 성능을 개선하는 방법을 알고 있습니다
- 데이터 시스템에 필요한 Back Office 를 여러개 제작해 왔으며 가장 최근에는 A/B 테스팅을 관리하기 위한 실험 플랫폼 관리 도구의 화면부터 API 까지 제작했습니다
- 언젠가 본인의 B2C 서비스를 제작하기 위해 발전하는 WEB 기술들에 대해 학습하고 있으며 해당 내용들을 시스템에 적용하면서 꾸준히 개선해 오고 있습니다 🙂 

### Speakings

아래 내용은, 최근까지 해온 커뮤니티 활동중 공개된 행사에서 진행된 슬라이드 일부를 모아, 참고하실 수 있도록 링크를 만든 것입니다. 과거에 작성된 내용이라 Outdated 되었을 수 있으나 도움이 되실지 몰라 남겨 둡니다. 
- [2019. 10 데이터 + 야놀자 = 야놀자에서 데이터를 더하는 법 (데이터야놀자)](https://docs.google.com/presentation/d/1AqiRVm32zCg59TKDgbs14FaVgNf8kqfXFkCYxAPw8ac/edit?usp=sharing)
- [2019. 08 궁금한 이야기 Y: 그들이 AWS 위에서 데이터 파이프라인을 운영하는 법 (AWSKRUG 밋업)](https://docs.google.com/presentation/d/1_v-f5B67v-hcmEbltLEfjSS5MKKctztdAGZzEHs2DPM/edit?usp=sharing)
- [2019. 09 AWS 위에서 데이터 파이프라인을 Terraform 으로 관리하기 (하시코프 밋업)](https://docs.google.com/presentation/d/1z92_m560ThnAK2W2h-ttp9DShqqHa4VIfmvgcWlXXLY/edit?usp=sharing)
- [2019. 10 AWS EKS 위에서 JupyterHub 분석환경 제공하기 (AWSKRUG 핸즈온)](https://docs.google.com/presentation/d/1oAkYqPFm_whJf2RW2Sf0Xz3jHUjtMc8vLH6ewkAu2js/edit?usp=sharing)

