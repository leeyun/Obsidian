***
# 데이터 파이프라인
데이터를 소스에서 [데이터 레이크](https://www.hpe.com/kr/ko/what-is/data-lake.html) 또는 [데이터 웨어하우스](https://www.hpe.com/kr/ko/what-is/data-warehouse.html)와 같은 종착지로 이동하는 데 사용합니다.
***
# 데이터 파이프라인 구성요소
- **데이터 소스**
	데이터가 생성되는 장소
	ex) 데이터베이스, CRM시스템, IoT 센서 등...
- **데이터 처리(데이터 전환 단계)**
	이동, 번역, 정렬, 통합, 중복제거, 검증, 분석 등 데이터를 변경하는 모든 운영
- **데이터 스토리지(데이터 종착지)**
	사용자가 액세스할 수 있도록 전환된 데이터가 저장되는 곳
	ex) 데이터 웨어하우스, 데이터 레이크, 데이터 마트 등...
***
# 데이터 파이프라인 유형
## 실시간 파이프라인

## 오픈 소스 파이프라인
## 클라우드 파이프라인
## 일괄 처리 파이프라인
## 스트리밍 파이프라인
***
# Bigdata의 조건 "three Vs"
- Velocity
- Volume
- Variety
***
# 유스케이스별 데이터파이프 라인 도구
### 데이터 선정, 수집
- logstash
- fluentd
- embulk
- beat
- apache flume
- aws sdk
- gcloud sdk
### 저장, 가공, 분석
- apache kafka, kafka-rest
- rabbimq, activemq
- redis, couchbase
- **Nosql** database, rdbms
- s3, gcs
- hadoop, elasticsearch
- spark, athena, bigquery
- datalab, dataproc, redshift
- kinesis, emr, redshift
- kibana, datastudio
- zeppelin