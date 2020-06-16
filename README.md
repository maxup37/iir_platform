# Intelligent Incident Response Platform

## [[ 목표 구성도 참고 ]]
* Open Source Endpoint monitoring 
  - https://github.com/DearBytes/Opensource-Endpoint-Monitoring
  
## [[ 환경 구성 ]]
* Windows 7 32bit (Endpoint 환경) - VM 구성
  - Python 2.7 32bit
  - Elastic Winlogbeat 7.6.2
  - sysmon
    > microsoft의 sysinternals.com
  - Red Team Automation (Red Team용 MITRE ATT@CK 기반 malicious attack 발생)
    > https://github.com/endgameinc/RTA
  - SwiftOnSecurity의 sysmon-config (보안로그 발생을 위한 sysmon 환경 파일)
    > https://github.com/SwiftOnSecurity/sysmon-config
    
* Elastic Stack 64bit (Server 환경) - Host
  - Elastic Logstach (Optional) 설치
    > https://www.elastic.co/kr/downloads/logstash

  - Elastic Elasticsearch 설치
    > https://www.elastic.co/kr/downloads/elasticsearch

  - Elastic Kibana 설치
    > https://www.elastic.co/kr/downloads/kibana

* Ubuntu 18.04 64bit 환경
  - Yelp의 elastalert
    > https://github.com/Yelp/elastalert

  - elastalert 설치
    > https://elastalert.readthedocs.io/en/latest/running_elastalert.html
