<div align="center">

  ### 👋 안녕하세요 :) **성장하는 개발자** 송진우 입니다.
  빠르게 만들고, 끝까지 운영하는 걸 좋아합니다. Android ⇄ Spring Boot ⇄ Infra(쿠버네티스/CI·CD)까지 전 과정을 직접 붙입니다.

  <!-- 한 줄 소개 키워드 -->
  <sub>Android • Spring Boot • gRPC • PostgreSQL • Kubernetes(k3s) • Jenkins • Traefik • JWT/OAuth</sub>

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

  🔗 <a href="YOUR_HELLOWORLD_REPO">Repo</a>
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
        <img src="https://img.shields.io/badge/k3s-Cluster-326CE5?style=flat&logo=kubernetes&logoColor=white" />
        <img src="https://img.shields.io/badge/Jenkins%20%2B%20Kaniko-CI%2FCD-D24939?style=flat&logo=jenkins&logoColor=white" />
        <img src="https://img.shields.io/badge/Traefik-Proxy-24A1C1?style=flat" />
      </sub><br/>

  <img src="assets/bookgle-arch.png" alt="BookgleBookgle Architecture" width="660"/><br/>

  <details>
    <summary><b>내 주요 기여</b></summary>
    <ul>
      <li><b>Android</b>: Jetpack Compose 기반 UI/UX, 커스텀 PDF Viewer(페이지 썸네일·하이라이트·주석),
          <b>gRPC 페이지 동기화</b> 및 충돌 처리, Hilt/Room, JWT 인증 연동</li>
      <li><b>Infra</b>: AWS EC2 위 <b>k3s</b> 클러스터 구성, <b>Jenkins+Kaniko</b> 파이프라인으로 이미지 빌드/배포 자동화,
          <b>Traefik Ingress</b> 라우팅·TLS, Helm 차트 템플릿, Prometheus/Grafana 모니터링</li>
      <li><b>Server</b>: Spring Cloud Gateway/Eureka/Config로 MSA 부트스트랩, gRPC 서버 스키마/인터셉터 협업</li>
    </ul>
  </details>

  🔗 <a href="YOUR_REPO_LINK">Repo</a>
</td>
  </tr>

  <tr>
    <td>
      <b>RouteMap / Broaf</b> — 지도 기반 여행·SNS (Kakao Map API)</br>
      <sub>경로 표시·리스트 UI, 성능 최적화(지연 로딩), Firebase → Spring 전환 준비</sub><br/>
      <sub>모바일 UI/UX(XML 레이아웃), RecyclerView(Adapter·ViewHolder) 구성, Kakao Map 중심 각종 외부 API 연동</sub><br/>
      🔗 <a href="#">RouteMap</a> · <a href="#">Broaf</a>
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
  <a href="https://your-notion-or-resume-link">
    <img src="https://img.shields.io/badge/Resume-000000?style=flat&logo=readthedocs&logoColor=white"/>
  </a>

  <br/><br/>

  <!-- 작은 디테일: 방문자수 배지 -->
  <img src="https://komarev.com/ghpvc/?username=songjinwoo&style=flat" />

</div>
