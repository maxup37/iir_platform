[[ windows 7 ]]
* sysmon 10.x 실행 오류
  > kb2533623 설치 (wevtapi.dll 문제)
  > kb3033929 설치

* sysmon-config.xml
  ** 변경전 
       >  <PipeEvent onmatch="exclude">
	
	     <EVENTID condition="is">1</EVENTID> 
     
           </PipeEvent>
	

  > <PipeEvent onmatch="include">
									   
     </PipeEvent> 




[[ Elasticsearch ]] 
* network.host 설정 bootstrap checks failed
  > https://soye0n.tistory.com/178



