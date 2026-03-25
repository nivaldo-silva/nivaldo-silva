<img src="https://capsule-render.vercel.app/api?type=waving&color=6db33f&height=140&section=header&text=Nivaldo%20Silva&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Java%20Backend%20Developer&descAlignY=58&descSize=18&descColor=cccccc&font=JetBrains+Mono" width="100%"/>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=300&size=16&duration=2800&pause=1000&color=6DB33F&center=true&vCenter=true&width=700&lines=Building+scalable+REST+APIs+%F0%9F%9A%80;Microservices+with+Spring+Boot+%E2%98%95;Clean+Code+%7C+SOLID+%7C+Cloud-Ready;Open+to+new+opportunities+%F0%9F%92%BC" alt="Typing SVG"/>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nivaldo-silva-5a8335289)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nivaldo-silva)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nivaldosilva.contato@gmail.com)
![Open to Work](https://img.shields.io/badge/%F0%9F%9F%A2%20Open%20to%20Work-6db33f?style=for-the-badge&logoColor=white)

</div>

## 👨‍💻 Sobre mim

> Backend Developer especializado em Java e Spring Boot, focado em construção de APIs escaláveis e sistemas distribuídos.

Atuo no desenvolvimento de microsserviços utilizando boas práticas como **Clean Code, SOLID e DDD**, com foco em performance, segurança e manutenibilidade.

- 🔐 Segurança com JWT, OAuth2 e Spring Security  
- ⚡ Comunicação síncrona e assíncrona (REST, mensageria)  
- 🐳 Deploy com Docker, AWS e infraestrutura como código  

📍 Recife, PE — Brasil  
🎓 Análise e Desenvolvimento de Sistemas — Estácio 

<br/>

## ⚙️ Stack Tecnológica

<img src="https://skillicons.dev/icons?i=java,spring,hibernate,maven,gradle,postgres,mysql,mongodb,redis,kafka,rabbitmq,docker" height="95" />
<img src="https://skillicons.dev/icons?i=kubernetes,aws,linux,terraform,nginx,git,github,postman,idea,grafana" height="95" />

<br/>

## 📈 Atividade Recente

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=nivaldo-silva&bg_color=0d1117&color=6db33f&line=6db33f&point=ffffff&area_color=6db33f&area=true&hide_border=true&custom_title=Contribui%C3%A7%C3%B5es%20nos%20%C3%BAltimos%2030%20dias" width="95%"/>

</div>

<br/>

## 🐍 Contribuições

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg"/>
  <img alt="Snake animation" src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg"/>
</picture>

</div>

---
<div align="center">
<div align="center">
<pre>
<code>
┌────────────────────────────── IntelliJ IDEA — Integrated Terminal ──────────────────────────────┐
│                                                                                                 │
│  🌿 Branch: main          🧑‍💻 User: nivaldo         🖥️ OS: linux                                │
│  ☕ Java 21              ♨ Spring Boot 3.x        🔐 Spring Security (JWT / OAuth2)              │
│  🐳 Docker              ☁ AWS Ready              📦 Maven Wrapper                               │
│                                                                                                 │
├────────────────────────────────────────── BUILD PIPELINE ───────────────────────────────────────┤
│                                                                                                 │
│  ~/workspace (main) $ ./mvnw clean package                                                      │
│                                                                                                 │
│  [INFO] Scanning for projects...                                                                │
│  [INFO] ------------------------------------------------------------------------               │
│  [INFO] Building api 1.0.0                                                                      │
│  [INFO] ------------------------------------------------------------------------               │
│                                                                                                 │
│  [INFO] --- maven-clean-plugin:3.2.0:clean ---                                                  │
│  [INFO] Deleting target directory                                                               │
│                                                                                                 │
│  [INFO] --- maven-resources-plugin:3.3.1:resources ---                                          │
│  [INFO] Copying resources                                                                       │
│                                                                                                 │
│  [INFO] --- maven-compiler-plugin:3.11.0:compile ---                                            │
│  [INFO] Compiling 42 source files                                                               │
│                                                                                                 │
│  [INFO] --- maven-surefire-plugin:3.2.5:test ---                                                 │
│  [INFO] Running unit tests...                                                                   │
│  [INFO] Tests run: 58, Failures: 0, Errors: 0, Skipped: 0                                       │
│                                                                                                 │
│  [INFO] --- jacoco-maven-plugin:0.8.11:report ---                                                │
│  [INFO] Code coverage: 91%                                                                      │
│                                                                                                 │
│  [INFO] --- spring-boot-maven-plugin:3.x:repackage ---                                           │
│  [INFO] Repackaging executable jar                                                              │
│                                                                                                 │
│  [INFO] BUILD SUCCESS                                                                           │
│  [INFO] Total time:  6.842 s                                                                    │
│                                                                                                 │
├────────────────────────────────────────── DOCKER BUILD ─────────────────────────────────────────┤
│                                                                                                 │
│  ~/workspace (main) $ docker build -t nivaldo/api:latest .                                       │
│                                                                                                 │
│  Sending build context to Docker daemon  32.76MB                                                 │
│  Step 1/6 : FROM eclipse-temurin:21-jdk                                                          │
│   ---> 8f3c...                                                                                  │
│  Step 2/6 : COPY target/api.jar app.jar                                                          │
│   ---> Using cache                                                                              │
│  Step 3/6 : ENTRYPOINT ["java","-jar","/app.jar"]                                                │
│   ---> Running in container                                                                     │
│                                                                                                 │
│  Successfully built a1b2c3d4                                                                    │
│  Successfully tagged nivaldo/api:latest                                                         │
│                                                                                                 │
├────────────────────────────────────────── FINAL STATUS ─────────────────────────────────────────┤
│                                                                                                 │
│  [✔] Tests        : PASS        🧪                                                               │
│  [✔] Coverage     : 91%         📊                                                               │
│  [✔] Build        : SUCCESS     📦                                                               │
│  [✔] Image        : CREATED     🐳                                                               │
│  [✔] Security     : ENABLED     🔐                                                               │
│  [✔] Status       : READY       🚀                                                               │
│                                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────────────────────┘
</code>
</pre>
</div>
<br/>

![Visitor Badge](https://komarev.com/ghpvc/?username=nivaldo-silva&color=6db33f&style=for-the-badge&label=VISITANTES+DO+PERFIL)

<img src="https://capsule-render.vercel.app/api?type=waving&color=6db33f&height=100&section=footer" width="100%"/>

</div>

