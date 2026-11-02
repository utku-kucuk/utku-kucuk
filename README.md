<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e1b4b,55:5b3df5,100:0f766e&height=190&section=header&text=Utku%20K%C3%BC%C3%A7%C3%BCk&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Backend%20Engineer%20%C2%B7%20Istanbul&descSize=18&descAlignY=58&animation=fadeIn" alt="Utku Küçük — Backend Engineer" width="100%" />
</p>

<p align="center">
  <a href="https://utkukucuk.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3200&pause=900&color=8B7BFF&center=true&vCenter=true&width=640&lines=Backend+systems+that+keep+running.;Java+%26+Spring+Boot+at+the+core.;Events+over+Kafka+%C2%B7+messages+over+RabbitMQ.;Shipped+with+Docker%2C+Kubernetes+%26+Helm." alt="Backend systems that keep running" />
  </a>
</p>

<p align="center">
  <a href="https://utkukucuk.com"><img src="https://img.shields.io/badge/Website-utkukucuk.com-5b3df5?style=for-the-badge&logo=astro&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/utkukucuk/"><img src="https://img.shields.io/badge/LinkedIn-utkukucuk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:utku@utkukucuk.com"><img src="https://img.shields.io/badge/Email-utku%40utkukucuk.com-0f766e?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
  <a href="https://utkukucuk.com/cv"><img src="https://img.shields.io/badge/CV-Download-1f2937?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Download CV" /></a>
</p>

<p align="center">
  <i>I build the parts users never see: APIs, data models, event flows, and the pipelines that ship them.</i>
</p>

---

### ⚡ Featured work

<table>
  <tr>
    <td colspan="2" valign="top">
      <h4><a href="https://github.com/utku-kucuk/partradar">📍 PartRadar</a></h4>
      Event-driven microservices that route a driver's part request to the nearest shops that have it in stock. A <b>Spring Cloud Gateway</b> in front of shop, inquiry and notification services, a database per service, <b>Kafka</b> domain events through a transactional outbox, <b>RabbitMQ</b> notifications with retries and a dead-letter queue, <b>PostGIS</b> search and <b>Keycloak</b> security — tested with Testcontainers and deployed to Kubernetes with Helm.<br/><br/>
      <code>Java 25</code> <code>Spring Boot 4</code> <code>Kafka</code> <code>RabbitMQ</code> <code>PostgreSQL + PostGIS</code> <code>Keycloak</code> <code>Kubernetes</code> <code>Helm</code><br/>
      <a href="https://utkukucuk.com/projects/partradar/">Case study →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/utku-kucuk/viducate">🎬 Viducate</a></h4>
      Video learning platform with chunked uploads, <b>byte-range streaming</b>, FFmpeg transcoding and <b>JWT + LDAP / Active Directory</b> sign-in for three roles.<br/><br/>
      <code>Node.js</code> <code>Express</code> <code>PostgreSQL</code> <code>FFmpeg</code> <code>Nginx</code><br/>
      <a href="https://utku-kucuk.github.io/viducate/">Live demo ↗</a> · <a href="https://utkukucuk.com/projects/viducate/">Case study →</a>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/utku-kucuk/IronEcho">🏋️ IronEcho</a></h4>
      Offline-first fitness platform with its own <b>sync engine</b>: queued offline writes, last-write-wins conflict resolution and live updates over Socket.io.<br/><br/>
      <code>Node.js</code> <code>TypeScript</code> <code>MongoDB</code> <code>Socket.io</code> <code>React Native</code><br/>
      <a href="https://utkukucuk.com/projects/ironecho/">Case study →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/utku-kucuk/SmartBlind-ESP32">🏠 Smart Home IoT</a></h4>
      ESP32 devices — a motorised blind, a smart lamp and climate sensors — talking <b>MQTT</b> to a self-hosted Home Assistant running in Docker.<br/><br/>
      <code>ESP32</code> <code>ESPHome</code> <code>C++</code> <code>MQTT</code> <code>Home Assistant</code><br/>
      <a href="https://utkukucuk.com/projects/smart-home-iot/">Case study →</a>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/utku-kucuk/hirehub">💼 HireHub</a></h4>
      Role-based job board for seekers, employers and admins, with <b>route guards</b> over a REST-shaped service layer and automated deploys.<br/><br/>
      <code>React 19</code> <code>React Router 7</code> <code>Tailwind CSS</code> <code>GitHub Actions</code><br/>
      <a href="https://utku-kucuk.github.io/hirehub/">Live demo ↗</a> · <a href="https://utkukucuk.com/projects/hirehub/">Case study →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/utku-kucuk/utkukucuk.com">🌐 utkukucuk.com</a></h4>
      Bilingual portfolio with a WebGL hero and a hashed Content Security Policy; every pull request passes lint, type checks and Lighthouse CI.<br/><br/>
      <code>Astro</code> <code>TypeScript</code> <code>Tailwind CSS</code> <code>Cloudflare</code><br/>
      <a href="https://utkukucuk.com">Visit ↗</a>
    </td>
    <td width="50%" valign="top">
      <h4>🛒 Commerce Platform <sub>· in progress</sub></h4>
      E-commerce backend on Java and Spring Boot: domain model, DTOs, repositories and services, built step by step.<br/><br/>
      <code>Java</code> <code>Spring Boot</code> <code>Spring Data JPA</code> <code>Hibernate</code>
    </td>
  </tr>
</table>

### 🛠️ Toolbox

<p>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
<img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security" />
<img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white" alt="Hibernate" />
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
<img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white" alt="Keycloak" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/Testcontainers-291A3F?style=flat-square&logo=testcontainers&logoColor=white" alt="Testcontainers" />
</p>

---

<p align="center">
  <sub>More on <a href="https://utkukucuk.com">utkukucuk.com</a> · say hi at <a href="mailto:utku@utkukucuk.com">utku@utkukucuk.com</a></sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f766e,45:5b3df5,100:1e1b4b&height=110&section=footer" alt="" width="100%" />
