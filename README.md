<div align="center">

# Olá, eu sou o William 👋
### Full Stack | Java/Spring Boot · Angular/React · JavaFX · ESP32

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wsdr96/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:williambfs2011@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/William-Willam)

</div>

> *Se o projeto precisa de API, tela web, app desktop ou até um ESP32 lendo GPS — eu quero entender como cada peça encaixa, não só fazer funcionar.*

---

## 👨‍💻 Sobre mim

Analista e Desenvolvedor de Sistemas formado, mas quem realmente me ensinou foi construir os projetos abaixo do zero — errando dialect do Hibernate, descobrindo na marra que `SessionCreationPolicy.STATELESS` quebra `@WithMockUser` nos testes, corrigindo senha em texto plano que eu mesmo deixei hardcoded num projeto antigo (DF-Vistoria) e nunca mais repetindo esse erro.

Gosto de projetos que me obrigam a sair da zona do CRUD: geolocalização com PostGIS no Guincho, fila FIFO de reserva na Biblioteca, ESP32 conversando com SIM800L num rastreador. Cada repo abaixo tem uma decisão de arquitetura por trás — e eu consigo explicar o porquê de cada uma.

💼 Hoje trabalho com Suporte Técnico N1 na Autotrac e testes de sistema, construindo esses projetos nas horas livres pra migrar de vez pra desenvolvimento.

📍 Brasília, DF

---

## 🚀 Tecnologias

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Frontend
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Embarcados & IoT
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

### DevOps & Ferramentas
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

---

## 🗂️ Projetos em destaque

### 🚛 Projeto Guincho
Plataforma pra conectar quem precisa de um guincho a quem tá disponível na região, em tempo real. O desafio aqui não foi CRUD — foi modelar posição geográfica direito: banco com PostGIS, índices espaciais validados, entidades com `@MapsId` onde a localização é ao mesmo tempo chave e relação.
**Stack:** Spring Boot · PostgreSQL/PostGIS · Hibernate Spatial (JTS) · Angular PWA
[Repositório »](https://github.com/William-Willam/Projeto-Guincho)

### 📚 Sistema Biblioteca
Antes de escrever uma linha de código, passei pela etapa de planejamento inteira: requisitos, ER, casos de uso, sequência — tudo documentado em `docs/` antes do primeiro commit de código. Decisões como fila de reserva em FIFO e multa fixa saíram dessa fase, não de tentativa e erro.
**Stack:** Spring Boot · PostgreSQL · Angular · JWT com refresh em cookie httpOnly
[Repositório »](https://github.com/William-Willam/biblioteca)

### 🚗 AutoVistor
O maior dos meus projetos até agora: três aplicações rodando junto (API, desktop, web) pra cobrir o fluxo real de uma empresa de vistoria — desde o agendamento até o boleto e o laudo em PDF saindo pronto pro cliente.
**Stack:** Java 21 · Spring Boot 4 · JavaFX · React/TypeScript · MySQL · JWT · Flyway · PDFBox
[Repositório »](https://github.com/William-Willam/ProjetoVistoria)

### 📡 GPS Tracker
Meu primeiro projeto saindo do software puro pra hardware. ESP32 lendo GPS NEO-6M, mandando posição via SIM800L (que aprendi na prática que puxa até 2A e não pode ser ligado direto no 3.3V do ESP32) e detectando movimento com o MPU6050.
**Stack:** ESP32 · C++ · GPS NEO-6M · SIM800L · MPU6050

### 🍔 Sales Manager
PDV pra lanchonete com três níveis de acesso — o atendente só vê o que precisa pra vender, o gerente enxerga o dashboard completo. Do requisito ao deploy, esse eu fechei sozinho de ponta a ponta.
**Stack:** Spring Boot · JavaFX · React/TypeScript · MySQL
[Repositório »](https://github.com/William-Willam/SalesManager)

### 💈 Sistema de Agendamento — Barbearia
Regra de negócio que parece simples (não deixar dois clientes marcarem o mesmo horário) mas que dá trabalho pra fazer direito quando envolve múltiplos serviços e profissionais.
**Stack:** Spring Boot · Thymeleaf · MySQL
[Repositório »](https://github.com/William-Willam/Barbearia)

<details>
<summary><strong>Outros projetos</strong></summary>
<br>

| Projeto | Descrição | Stack |
|---|---|---|
| 👟 [ShoeStock](https://github.com/William-Willam/Calcados) | Estoque de calçados com API REST, desktop JavaFX e loja Angular | Spring Boot · JavaFX · Angular · PostgreSQL |
| 📋 [TaskFlow](https://github.com/William-Willam/TaskFlow) | Gerenciador de tarefas com JWT e controle por papel de usuário | Spring Boot · Angular · MySQL · Docker |
| ⛅ [Sistema Meteorológico](https://github.com/William-Willam/Sistema-Meterologico) | App desktop de clima com imagens dinâmicas por condição/período | JavaFX · OpenWeatherMap API · IBGE API |
| 🚗 [DF-Vistorias](https://github.com/William-Willam/DF-Vistoria) | Vistorias veiculares — projeto de conclusão de curso | Java Swing · MySQL |
| 🧮 [Calculadora](https://github.com/William-Willam/Calculadora) | Calculadora desktop com tema estilo iOS | JavaFX · Scene Builder |
| 🐍 [Jogo da Cobra](https://github.com/William-Willam/JogodaCobra) | Snake game — exercício de lógica e OO | Java |

</details>

---

## 📈 GitHub Stats

<div align="center">

![Stats](https://streak-stats.demolab.com?user=William-Willam&theme=tokyonight&hide_border=true&locale=pt_BR&date_format=j%20M%20Y)

![Gráfico de contribuições](https://ghchart.rshah.org/William-Willam)

</div>

---

## 🎓 Formação & Trajetória

```
2023  ──  Graduação em Análise e Desenvolvimento de Sistemas · Uniplan
2025  ──  Aprofundamento em Full Stack Java, Angular, Docker e AWS
2026  ──  Suporte Técnico N1 na Autotrac, atuando também em testes de sistema
        ──  Expansão para geolocalização (PostGIS) e sistemas embarcados (ESP32)
```
