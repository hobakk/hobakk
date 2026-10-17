<div align="center">

# 김민재 · Terbo

**DevOps Engineer** — 서버 4대, 컨테이너 105개, 제조 현장 92개의 인프라를 혼자 설계하고 운영합니다.

</div>

운영하면서 문제가 커지기 전에 먼저 제안하고 만드는 일을 합니다.

- 배포·운영 플랫폼(Terkins)과 사설 Docker 레지스트리를 직접 만들어 배포 시간을 **8분 → 3분**으로 줄였습니다.
- AWS 비용을 월 **115만원 → 3천원**으로 낮췄습니다 (인스턴스 재산정 → 전송 구조 개선 → 온프레미스 이관).
- 장애가 잦던 현장 30곳을 WireGuard VPN으로 전환해 연결 장애를 **40% → 0건**으로 만들었습니다.
- Prometheus · Loki · Grafana로 컨테이너 105개를 한곳에서 관제합니다.

> 쿠버네티스와 Terraform은 아직 실무 경험이 없고, Ansible은 아래 프로젝트로 직접 익히고 있습니다.

## Projects

| 프로젝트 | 설명 |
|---|---|
| [**ansible**](https://github.com/hobakk/ansible) | 서버 2대의 초기 설정(계정·SSH 보안·Docker·방화벽·감사 로그)을 코드로 정의한 Ansible 프로젝트. 재실행 시 `changed=0`, `ansible-lint` production 프로필 통과, Molecule 자동 테스트 |

## Tech Stack

<div align="center">

<h4>Infra &amp; Operations</h4>
<div>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
  <img alt="WireGuard" src="https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white">
  <img alt="Amazon EC2" src="https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">
  <img alt="Amazon S3" src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
</div>

<h4>CI / CD &amp; Automation</h4>
<div>
  <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">
  <img alt="GitLab" src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
  <img alt="Ansible" src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white">
  <img alt="Bash" src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white">
</div>

<h4>Monitoring</h4>
<div>
  <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
  <img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
  <img alt="Loki" src="https://img.shields.io/badge/Loki-F46800?style=for-the-badge&logo=grafana&logoColor=white">
  <img alt="OpenTelemetry" src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white">
</div>

<h4>Backend</h4>
<div>
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white">
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
</div>

</div>

<details>
<summary>그 밖에 써 본 것</summary>
<br>
<div align="center">
  <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white">
  <img alt="Spring Security" src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="Redux" src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white">
  <img alt="styled-components" src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white">
</div>
</details>

## GitHub Stats

<div align="center">
  <a href="https://github.com/hobakk">
    <img alt="hobakk GitHub stats" height="170" src="https://github-readme-stats.vercel.app/api?username=hobakk&show_icons=true&theme=radical" />
  </a>
  <a href="https://github.com/hobakk">
    <img alt="hobakk top languages" height="170" src="https://github-readme-stats.vercel.app/api/top-langs?username=hobakk&layout=compact&langs_count=8&theme=radical" />
  </a>
</div>

## Contact

[manlyman0714@gmail.com](mailto:manlyman0714@gmail.com)
