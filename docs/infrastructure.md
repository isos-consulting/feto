# 사내 웹 서버 구성
![사내 웹 서버 구성도](https://github.com/isos-consulting/feto/assets/49608580/1038eb46-49f5-40a9-accb-819ac1282cf8)

서버 정보
``` json
[
   {
      "name":"dms-server",
      "username":"isos",
      "ip":"191.1.70.192",
      "용도":"문서관리 시스템 개발 확인용 웹서버",
      "웹 서버 포트":8080
   },
   {
      "name":"isos-server",
      "username":"isos-server",
      "ip":"191.1.70.205",
      "용도":"웹 MES API 서버 + DB 서버(Postgresql, Redis)",
      "API 서버 포트":3004
   },
   {
      "name":"iso-client",
      "username":"isos-server",
      "ip":"191.1.70.232",
      "용도":"웹 MES 클라이언트 서버",
      "포트":3000
   },
   {
      "name":"jenkins",
      "username":"isos-server",
      "ip":"191.1.70.215",
      "용도":"CI/CD 서버",
      "웹 서버 포트":8080
   }
]
```