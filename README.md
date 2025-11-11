
  <h1 style="color:#dff9ff; margin:6px 0;">Daniel Goes — Desenvolvedor Full Stack</h1>
  <p style="color:#a9bdc9; margin:0 0 10px 0;">
    Soluções Web • Mobile • IoT — Performance, Segurança e Escalabilidade
  </p>

  <p>
    <img src="https://img.shields.io/badge/Status-Dispon%C3%ADvel-00EAFF?style=for-the-badge&logo=git&logoColor=white" alt="status" />
    <img src="https://img.shields.io/badge/Stack-Java%20|%20Angular%20|%20Node.js%20|%20Flutter-101820?style=for-the-badge&logo=visualstudiocode&logoColor=00eaff" alt="stack" />
    <img src="https://img.shields.io/badge/Experi%C3%AAncia-T%C3%A9cnico%20Pleno%20%2F%20S%C3%AAnior-00b7ff?style=for-the-badge" alt="nivel" />
    <img src="https://img.shields.io/badge/Local-Brasil-00eaff?style=for-the-badge" alt="local" />
  </p>
</div>

---

<div style="background:linear-gradient(180deg,#06070a,#071023); border-radius:10px; padding:16px; color:#bfefff; margin:14px 0;">
  <strong>Resumo profissional</strong>
  <p style="color:#9fbccb; margin:8px 0 0 0;">
    Engenheiro de software full stack com atuação em projetos corporativos e produtos digitais. Experiência consolidada em arquiteturas REST/GraphQL, microsserviços, CI/CD, observability e soluções IoT. Entrego aplicações resilientes, seguras e testadas, com foco em performance e manutenção.
  </p>
</div>

## 🎯 Destaques técnicos (tema escuro + neon cyan)
- Linguagens: Java, TypeScript, Dart, JavaScript, SQL
- Back-end: Spring Boot, Node.js, NestJS, APIs REST/GraphQL
- Front-end: Angular (NgRx), React, TypeScript, otimização e acessibilidade
- Mobile: Flutter (iOS/Android), integração nativa, push notifications
- IoT: MQTT, CoAP, BLE, ESP32/ESP8266, telemetria e pipelines
- Infra & DevOps: Docker, Kubernetes, GitHub Actions, AWS / Azure
- Observability: Prometheus, Grafana, ELK, tracing (Jaeger)
- Testes & Performance: JUnit, Mockito, Jest, Cypress, testes de carga

---

## 🧭 Painel visual — Competências (neon cyan)
<p align="center">
  <img alt="skill-chart" src="https://quickchart.io/chart?c={
    type:'radar',
    data:{
      labels:['Back-end','Front-end','Mobile','DevOps','IoT','DBs','Testes'],
      datasets:[{
        label:'Nível',
        data:[95,88,82,78,83,87,86],
        backgroundColor:'rgba(0,234,255,0.12)',
        borderColor:'rgba(0,234,255,0.95)',
        pointBackgroundColor:'rgba(0,234,255,0.95)'
      }]
    },
    options:{
      plugins:{legend:{display:false}},
      scale:{angleLines:{display:false},grid:{color:'#0b1220'},pointLabels:{color:'#9fbccb'},ticks:{display:false}}
    }
  }&width=900&height=420" />
</p>

---

## 🧰 Ferramentas & Ecosistema
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="36" style="margin-right:6px;" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="36" style="margin-right:6px;" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" width="36" style="margin-right:6px;" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="36" style="margin-right:6px;" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" width="36" style="margin-right:6px;" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="36" style="margin-right:6px;" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="36" style="margin-right:6px;" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="36" style="margin-right:6px;" />
</p>

---

## 📁 Projetos relevantes (resumo técnico)
- Plataforma de Telemetria IoT  
  - Stack: ESP32 → MQTT → Node.js / Kafka → PostgreSQL → Angular / Grafana  
  - Entregas: ingestão e normalização em tempo real, dashboards, regras e alertas, retenção e compressão de payloads.
- ERP / Sistema de Gestão (B2B)  
  - Stack: Spring Boot, PostgreSQL, Angular  
  - Entregas: módulos de estoque, faturamento, integrações com gateways, testes automatizados e deploy contínuo.
- Marketplace Mobile (B2C)  
  - Stack: Flutter, Firebase/Auth, APIs REST  
  - Entregas: onboarding, autenticação, pagamento, notificações push, testes e pipelines multiplataforma.
- Automação & Performance  
  - Resultados: redução de 40% no tempo de deploy; baseline de performance com testes de carga programados.

---

## 🧾 Tabela de certificados (detalhada — dark cards)
| Ano | Certificado | Organização | Link |
|---:|---|---|---|
| 2024 | Competência Transversal – Segurança no Trabalho (14h) | SENAI-SP | [PDF](./certificados/seguranca_trabalho.pdf) |
| 2024 | Privacidade e Proteção de Dados (LGPD) (4h) | SENAI-SP | [PDF](./certificados/lgpd.pdf) |
| 2024 | Economia Circular (20h) | SENAI-SP | [PDF](./certificados/economia_circular.pdf) |
| 2024 | Desvendando o 5G (15h) | SENAI-SP | [PDF](./certificados/5g.pdf) |
| 2024 | Especialista em Performance / Testes de Carga e Estresse | SENAI-SP | [PDF](./certificados/performance.pdf) |

> Dica: para miniaturas use imagens em ./certificados/miniaturas/*.png e adicione a coluna de preview com Markdown de imagem.

---

## 🔧 Snippets & Artefatos técnicos prontos

### 2) Dockerfile (serviço Java otimizado)
```dockerfile
// filepath: examples/Dockerfile
// ...existing code...
FROM eclipse-temurin:17-jdk-jammy
WORKDIR /app
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
ENV JAVA_OPTS="-Xms256m -Xmx512m -Dspring.profiles.active=prod -Djava.security.egd=file:/dev/./urandom"
EXPOSE 8080
ENTRYPOINT ["sh","-c","java $JAVA_OPTS -jar /app/app.jar"]
// ...existing code...
```

### 3) GitHub Actions (workflow: build, test, badge update)
```yaml
// filepath: .github/workflows/ci.yml
// ...existing code...
name: CI

on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]
  workflow_dispatch:

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Set up JDK 17
        uses: actions/setup-java@v4
        with:
          distribution: 'temurin'
          java-version: '17'
      - name: Build (Maven)
        run: mvn -B -DskipTests=false clean verify
      - name: Run unit tests
        run: mvn test -q
  update-readme-assets:
    needs: build-and-test
    runs-on: ubuntu-latest
    if: github.ref == 'refs/heads/main'
    steps:
      - uses: actions/checkout@v4
      - name: Generate charts
        run: |
          echo "Gerando gráficos (ex: quickchart) e atualizando assets/docs"
      - name: Commit assets
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "actions@github.com"
          git add docs/assets || true
          git commit -m "Atualiza assets do README" || echo "No changes"
          git push || echo "Push falhou"
// ...existing code...
```

---

## 🎮 Seção "Easter Games" — jogos integráveis e badges
- 2048 — https://play2048.co/ (link rápido para demonstração)
- Snake — https://playsnake.org/
- Pequeno micro-jogo (embed) — sugerido: hospedar HTML/JS em /docs/playground e linkar aqui.

Badge de "streak" de commits (exemplo):
![Commit Streak](https://github-readme-streak-stats.herokuapp.com/?user=dn-goes&theme=dark&background=071023&fire=00eaff)

---

## ✅ Boas práticas aplicadas (resumo)
- Autenticação: OAuth2 / JWT, roles e scopes bem estruturados  
- Segurança: validações, proteções OWASP Top10, LGPD awareness  
- Observability: métricas, traces distribuídos e logs estruturados  
- Qualidade: testes unitários, integração, e2e e pipelines automatizados

---

## ⚙️ Comandos úteis (Windows)
- Build Java (Maven): mvn clean package -DskipTests  
- Rodar Docker: docker build -t app:latest . && docker run -p 8080:8080 app:latest  
- Flutter (emulador): flutter run -d emulator-5554

---

## 📬 Contato & redes (tema escuro)
<p>
  <a href="https://www.linkedin.com/in/daniel-goes-a856a4361/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/dn-goes"><img src="https://img.shields.io/badge/GitHub-101820?style=for-the-badge&logo=github&logoColor=00eaff" /></a>
  <a href="mailto:danielgoesrosa07@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://wa.me/5519993426057"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" /></a>
</p>

---
