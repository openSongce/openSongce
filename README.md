<div align="center">

### 👋 안녕하세요, 송진우 입니다.
**앱도 서버도 인프라도, 끝까지 붙이는 개발자**  
Android ⇄ Spring Boot ⇄ k8s를 잇고, 기능은 빠르게 만들되 운영은 안정적으로 지킵니다.

<sub>Jetpack Compose · gRPC 실시간 동기화 · Spring Cloud(Gateway/Eureka/Config) · Jenkins+Kaniko · Traefik · cert-manager · Prom/Grafana/Loki · JWT/OAuth</sub>

**제가 잘하는 것**
- End-to-End 소유: Android 화면 → 백엔드 API → CI/CD → Ingress/TLS까지 한 흐름으로 설계/운영
- 운영형 문제해결: 재현 스크립트·대시보드·알람으로 MTTR 단축
- 표준화/자동화: Helm 템플릿화, 공통 게이트웨이/보안 정책, 파이프라인 일관화

**가치관**
- “됐네”에서 멈추지 않고 **“돌아간다”까지**. 재현 가능한 버그, 롤백 가능한 배포, 관찰 가능한 운영을 기본으로 합니다.

  <br/>

  ## 🚀 Tech Stack

  <!-- 백엔드 -->
  <details open>
  <summary><b>Backend</b></summary>
  
  <!-- Badges: flat으로 통일 -->
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/MyBatis-000000?style=flat&logo=mybatis&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST%20API-121212?style=flat"/>
  <img src="https://img.shields.io/badge/gRPC-1c7bd9?style=flat&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
  </details>

  <!-- 안드로이드 -->
  <details open>
  <summary><b>Android</b></summary>

  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat&logo=androidstudio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white"/>
  <img src="https://img.shields.io/badge/Room-1C3C3C?style=flat"/>
  <img src="https://img.shields.io/badge/Hilt-5A29E4?style=flat&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Credential%20Manager-121212?style=flat"/>
  </details>

  <!-- 인프라/데브옵스 -->
  <details open>
  <summary><b>Infra / DevOps</b></summary>

  <img src="https://img.shields.io/badge/Kubernetes(k3s)-326CE5?style=flat&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white"/>
  <img src="https://img.shields.io/badge/Traefik-24A1C1?style=flat&logo=traefikproxy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white"/>
  </details>

  <br/>

  ## 🌍 Deployment
  <!-- 운영/배포 한 줄 설명 (실서비스/학습 인프라 구분) -->
  - AWS EC2 위 **k3s** 단일 노드 클러스터 운영 (Traefik Ingress, Helm, Let’s Encrypt)
  - **Jenkins + Kaniko** 로 멀티 스테이지 도커 이미지 빌드 → 쿠버네티스 자동 배포
  - Spring Cloud (Gateway / Eureka / Config)로 MSA 구성, **JWT/OAuth** 인증 통합

  <br/>

## 💼 Projects

<table>
  <tr>
  <td>
    <b>WISL</b> — 솔루션 마켓(문제→팀빌딩→펀딩→출시) 플랫폼 · K-PaaS 공모전(진행중)<br/>
    <sub>
      <img src="https://img.shields.io/badge/Team-%ED%81%AC%EB%A0%88PaaS-181717?style=flat" />
      <img src="https://img.shields.io/badge/K--PaaS-%EA%B3%B5%EB%AA%A8%EC%A0%84-0B5FFF?style=flat" />
      <img src="https://img.shields.io/badge/Status-In%20Progress-FF9800?style=flat" />
      <img src="https://img.shields.io/badge/Android-Compose-3DDC84?style=flat&logo=android&logoColor=white" />
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white" />
      <img src="https://img.shields.io/badge/MyBatis-000000?style=flat&logo=mybatis&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS-EC2-FF9900?style=flat&logo=amazonaws&logoColor=white" />
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" />
      <img src="https://img.shields.io/badge/Jenkins%20%2B%20Kaniko-CI%2FCD-D24939?style=flat&logo=jenkins&logoColor=white" />
      <img src="https://img.shields.io/badge/Traefik-Ingress-24A1C1?style=flat" />
      <img src="https://img.shields.io/badge/cert--manager-TLS-0A7ACC?style=flat" />
      <img src="https://img.shields.io/badge/Helm-Charts-0F1689?style=flat&logo=helm&logoColor=white" />
      <img src="https://img.shields.io/badge/Prometheus%20%7C%20Grafana-Observability-E6522C?style=flat" />
      <img src="https://img.shields.io/badge/PostgreSQL-DB-4169E1?style=flat&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis-Cache-DC382D?style=flat&logo=redis&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker%20Hub-2496ED?style=flat&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/등등 최대한 많이-181717?style=flat" />
    </sub><br/>

 


  <details>
    <summary><b>개요 & 목표</b></summary>
    <ul>
      <li><b>배경</b>:<b>소비자 문제를 출발점</b>으로 펀딩·출시까지 이어주는 플랫폼 필요</li>
      <li><b>목표</b>: <b>실제 문제</b> 중심의 검증형 혁신 · K-PaaS 기반 서비스화</li>
      <li><b>핵심 값</b>: 커뮤니티 검증(공감/참여 데이터) → 리스크↓, 수익 <b>투명 분배</b></li>
    </ul>
  </details>

  <details>
    <summary><b>핵심 기능(트랙 A/B)</b></summary>
    <ul>
      <li><b>트랙 A · 아이디어 대나무숲</b>: 문제 제기·공감 수치화, 유사 문제 자동 묶기(분류)</li>
      <li><b>트랙 B · Co-Create(비공개)</b>: e-NDA로 보호된 기획 공유, 제안 수령, 전자계약(SoW/저작권/분배)</li>
      <li><b>펀딩/검증</b>: 리워드/선주문 연동, 베타 테스트 피드백 루프</li>
      <li><b>정산/분배</b>: 마일스톤·에스크로 기반 자동 정산(문제제기자/개발팀/후원자)</li>
    </ul>
  </details>

  <details>
    <summary><b>주요 기술</b></summary>
    <ul>
      <li><b>Android</b>: Kotlin, Jetpack Compose, MVVM/Repository 또는 Cross-Platform</li>
      <li><b>Backend</b>: Spring Boot, MyBatis + MySQL, REST API, MSA, Postgre, Kafka, Redis 등 </li>
      <li><b>Infra</b>: AWS EC2 배포, Kubernetes, NCP 등 (K-PaaS 연동 계획)</li>
    </ul>
  </details>

  <details>
    <summary><b>기대 효과</b></summary>
    <ul>
      <li><b>수요 검증</b> 기반 개발로 실패 리스크↓</li>
      <li>문제 제기자·개발자·후원자 간 <b>투명한 수익 공유</b></li>
      <li>지역/커뮤니티 단위의 <b>문제 해결 촉진</b></li>
    </ul>
  </details>


</td>
</tr>

  <tr>
    <td>
      <b>HelloWorld</b> — 임산부 케어 앱 (Android Compose + Spring Cloud MSA)<br/>
      <sub>
        <img src="https://img.shields.io/badge/Role-Infra%20Lead-181717?style=flat" />
        <img src="https://img.shields.io/badge/k3s-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" />
        <img src="https://img.shields.io/badge/Jenkins%20%2B%20Kaniko-CI%2FCD-D24939?style=flat&logo=jenkins&logoColor=white" />
        <img src="https://img.shields.io/badge/Traefik-Ingress-24A1C1?style=flat" />
        <img src="https://img.shields.io/badge/cert--manager-TLS-0A7ACC?style=flat" />
        <img src="https://img.shields.io/badge/Helm-Charts-0F1689?style=flat&logo=helm&logoColor=white" />
        <img src="https://img.shields.io/badge/Prometheus%20%7C%20Grafana-Observability-E6522C?style=flat" />
        <img src="https://img.shields.io/badge/PostgreSQL-DB-4169E1?style=flat&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/Redis-Cache-DC382D?style=flat&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker%20Hub-2496ED?style=flat&logo=docker&logoColor=white" />
      </sub><br/>

  <img src="assets/helloworld-arch.png" alt="HelloWorld Infrastructure Architecture" width="660"/><br/>

  <details>
    <summary><b>내 주요 기여(Infra)</b></summary>
    <ul>
      <li><b>클러스터</b>: AWS EC2 위 <b>k3s</b> 구성, 네임스페이스(ingress/apps/db/observability) 분리</li>
      <li><b>배포</b>: <b>Jenkins + Kaniko</b> 이미지 빌드·푸시 → Helm/kubectl로 자동 롤링 업데이트</li>
      <li><b>네트워킹</b>: <b>Traefik Ingress</b>, <b>cert-manager</b>로 Let’s Encrypt 자동 TLS, X-Forwarded 헤더 정합</li>
      <li><b>MSA</b>: Spring Cloud <b>Gateway / Eureka / Config</b> 부트스트랩, JWT/OAuth 엔드포인트 집약</li>
      <li><b>데이터</b>: PostgreSQL(서비스별 DB), <b>Redis</b> 캐시/세션, Loki/Promtail 로그 수집, Grafana 대시보드</li>
    </ul>
  </details>

  🔗 <a href="YOUR_HELLOWORLD_REPO">Repo</a> · <a href="https://www.notion.so/254b8bebd93a8057b1cdf2d9cf6d589b?source=copy_link">Docs</a>
  </td>
  </tr>

  <tr>
  <td>
    <b>BookgleBookgle</b> — 실시간 PDF 협업 플랫폼 (Android + Spring Boot + gRPC)<br/>
    <sub>
      <img src="https://img.shields.io/badge/Role-Android%20%7C%20Infra-181717?style=flat" />
      <img src="https://img.shields.io/badge/Android-Compose-3DDC84?style=flat&logo=android&logoColor=white" />
      <img src="https://img.shields.io/badge/gRPC-1c7bd9?style=flat" />
      <img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
    <img src="https://img.shields.io/badge/docker--compose-384d54?style=flat&logo=docker&logoColor=white" />
  </sub><br/>

  <img src="assets/bookgle-arch.png" alt="BookgleBookgle Architecture" width="660"/><br/>

  <details>
    <summary><b>내 주요 기여</b></summary>
    <ul>
    <li><b>Android</b>: Jetpack Compose 기반 UI/UX, 커스텀 PDF Viewer(페이지 썸네일·하이라이트·주석),
        <b>gRPC 페이지 동기화</b> 및 충돌 처리, Hilt/Room, JWT 인증 연동</li>

    <li><b>Infra</b>: AWS EC2에 <b>Docker</b>로 서비스 컨테이너라이징, 
        <b>docker-compose</b>로 멀티 서비스 구성·배포, 
        <b>Jenkins</b>로 빌드/배포 자동화</li>
    <li><b>Server</b>: Spring Boot 기반 gRPC 서버(프로토콜 정의/인터셉터), 인증(JWT)·권한 처리 협업</li>
    </ul>
  </details>

  🔗 <a href="https://github.com/openSongce/bookglebookgle">Repo</a> · <a href="https://www.notion.so/D204-230bf1e01d1e807d9a45eee0cd9208ec?source=copy_link">Docs</a>
  </td>
</tr>


  <tr>
  <td>
    <b>NHCafe</b> — 음성인식 기반 AI 무인 카페 앱 (Android + Spring Boot + GPT-4o)<br/>
    <sub>
      <img src="https://img.shields.io/badge/Role-Android%20%7C%20AI-181717?style=flat" />
      <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white" />
      <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white" />
      <img src="https://img.shields.io/badge/STT-Voice%20Input-121212?style=flat" />
      <img src="https://img.shields.io/badge/TTS-Voice%20Guide-121212?style=flat" />
      <img src="https://img.shields.io/badge/GPT--4o-OpenAI-412991?style=flat" />
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white" />
      <img src="https://img.shields.io/badge/MyBatis-000000?style=flat&logo=mybatis&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS-EC2-FF9900?style=flat&logo=amazonaws&logoColor=white" />
    </sub><br/>

  <img src="assets/nhcafe-arch.png" alt="NHCafe Architecture (STT→GPT→TTS, Spring/MyBatis/MySQL on EC2)" width="660"/><br/>

  <details>
    <summary><b>내 주요 기여(Android · AI)</b></summary>
    <ul>
      <li><b>대화형 주문</b>: 음성(STT) → 텍스트 → <b>GPT-4o</b>로 의도/메뉴 파싱 → 주문 카드 자동 구성</li>
      <li><b>음성 안내</b>: 주문 단계·확인 내용을 <b>TTS</b>로 낭독, 시각/청각 동시 안내</li>
      <li><b>추천 메뉴</b>: 프롬프트 정책으로 실제 메뉴 중 <b>3가지 추천</b> 응답</li>
      <li><b>앱 구조</b>: <b>MVVM + Repository</b>, Compose UI 상태관리, Retrofit 네트워킹</li>
      <li><b>서버 연동</b>: Spring Boot + <b>MyBatis/MySQL</b> 주문/메뉴 API, AWS EC2 배포 협업</li>
    </ul>
  </details>

  🔗 <a href="https://github.com/openSongce/NHCafe">Repo</a>
  </td>
</tr>


  <tr>
    <td>
      <b>RouteMap / Broaf</b> — 지도 기반 여행·SNS (Kakao Map API)</br>
      <sub>경로 표시·리스트 UI, 성능 최적화(지연 로딩), Firebase → Spring 전환 준비</sub><br/>
      <sub>모바일 UI/UX(XML 레이아웃), RecyclerView(Adapter·ViewHolder) 구성, Kakao Map 중심 각종 외부 API 연동</sub><br/>
      🔗 <a href="https://github.com/openSongce/Routemap">RouteMap</a> · <a href="https://github.com/openSongce/broaf">Broaf</a>
    </td>
  </tr>
  

</table>

<br>


  ## 📊 GitHub Stats
  <!-- 통계 위젯은 취향껏 1~2개만 사용해도 충분 -->
  <img src="https://github-readme-stats.vercel.app/api?username=openSongce&show_icons=true&hide_title=true" height="140" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=openSongce" height="140" />
  <!-- <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=openSongce&layout=compact" height="140" /> -->

  <br/>

  ## 🔥 Contact & More
  <a href="mailto:rkddkwl059@naver.com">
    <img src="https://img.shields.io/badge/Email-181717?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.notion.so/DevOps-26f572cbac3c80778c33d467d870f822?source=copy_link">
    <img src="https://img.shields.io/badge/Resume-000000?style=flat&logo=readthedocs&logoColor=white"/>
  </a>

  <br/><br/>

  <!-- 작은 디테일: 방문자수 배지 -->
  <img src="https://komarev.com/ghpvc/?username=songjinwoo&style=flat" />

</div>
