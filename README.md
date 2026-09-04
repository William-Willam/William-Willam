<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,100:ED8B00&height=180&section=header&text=William%20dos%20Santos%20Rodrigues&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full%20Stack%20Developer&descAlignY=58&descSize=18" alt="header"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=0A66C2&center=true&vCenter=true&width=560&lines=Java+%2F+Spring+Boot;Angular+%2F+React;JavaFX+Desktop;ESP32+%2F+Embarcados;Do+backend+ao+hardware." alt="Typing SVG" />

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wsdr96/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:williambfs2011@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/William-Willam)

</div>

<br>

## 👨‍💻 Sobre mim

Analista e Desenvolvedor de Sistemas formado, mas quem realmente me ensinou foi construir os projetos abaixo do zero — errando dialect do Hibernate, descobrindo na marra que `SessionCreationPolicy.STATELESS` quebra `@WithMockUser` nos testes, corrigindo senha em texto plano que eu mesmo deixei hardcoded num projeto antigo e nunca mais repetindo esse erro.

Gosto de projetos que me tiram da zona do CRUD: geolocalização com PostGIS no Guincho, fila FIFO de reserva na Biblioteca, ESP32 conversando com SIM800L num rastreador. Cada repo abaixo tem uma decisão de arquitetura por trás — e eu consigo explicar o porquê de cada uma.

```yaml
trabalho_atual: "Suporte Técnico N1 @ Autotrac + testes de sistema"
construindo_agora: "Projeto Guincho (geolocalização) e GPS Tracker (ESP32)"
localização: "Brasília, DF"
buscando: "oportunidade como desenvolvedor Full Stack"
```

<br>

## 🚀 Stack

<div align="center">

**Backend**
<br>
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Frontend & Desktop**
<br>
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Embarcados & DevOps**
<br>
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

</div>

<br>

## 🗂️ Projetos em destaque

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🚛 Projeto Guincho
Conecta quem precisa de um guincho a quem tá disponível na região, em tempo real. Desafio central: modelar posição geográfica direito — PostGIS, índices espaciais, entidades com `@MapsId` onde a localização é chave e relação ao mesmo tempo.

`Spring Boot` `PostgreSQL/PostGIS` `JTS` `Angular PWA`

[**→ Repositório**](https://github.com/William-Willam/Projeto-Guincho)

</td>
<td width="50%" valign="top">

### 📚 Sistema Biblioteca
Planejamento completo antes do código: requisitos, ER, casos de uso e sequência documentados em `docs/`. Fila de reserva FIFO e multa fixa nasceram dessa fase, não de tentativa e erro.

`Spring Boot` `PostgreSQL` `Angular` `JWT + refresh httpOnly`

[**→ Repositório**](https://github.com/William-Willam/biblioteca)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚗 AutoVistor
O maior projeto até agora: três aplicações rodando junto (API, desktop, web) cobrindo o fluxo real de uma empresa de vistoria — do agendamento ao boleto e laudo em PDF.

`Java 21` `Spring Boot 4` `JavaFX` `React/TS` `PDFBox`

[**→ Repositório**](https://github.com/William-Willam/ProjetoVistoria)

</td>
<td width="50%" valign="top">

### 📡 GPS Tracker
Primeiro projeto saindo do software puro pra hardware. ESP32 + GPS NEO-6M, transmissão via SIM800L (que puxa até 2A — não pode ligar direto no 3.3V do ESP32) e detecção de movimento com MPU6050.

`ESP32` `C++` `GPS NEO-6M` `SIM800L` `MPU6050`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🍔 Sales Manager
PDV pra lanchonete com três níveis de acesso — atendente vê só o que precisa pra vender, gerente enxerga o dashboard completo. Do requisito ao deploy, fechado sozinho de ponta a ponta.

`Spring Boot` `JavaFX` `React/TS` `MySQL`

[**→ Repositório**](https://github.com/William-Willam/SalesManager)

</td>
<td width="50%" valign="top">

### 💈 Barbearia
Agendamento com regra de negócio que parece simples — não deixar dois clientes marcarem o mesmo horário — mas dá trabalho pra fazer direito com múltiplos serviços e profissionais.

`Spring Boot` `Thymeleaf` `MySQL`

[**→ Repositório**](https://github.com/William-Willam/Barbearia)

</td>
</tr>
</table>

<details>
<summary><strong>📦 Outros projetos</strong></summary>
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

<br>

## 📈 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=William-Willam&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=William-Willam&layout=compact&theme=tokyonight&hide_border=true" alt="top langs"/>

<br>

<img src="https://streak-stats.demolab.com?user=William-Willam&theme=tokyonight&hide_border=true&locale=pt_BR&date_format=j%20M%20Y" alt="streak"/>

<br>

<img src="https://ghchart.rshah.org/0A66C2/William-Willam" alt="Gráfico de contribuições" width="100%"/>

</div>

<br>

## 🎓 Trajetória

```
2023  ──  Graduação em Análise e Desenvolvimento de Sistemas · Uniplan
2025  ──  Aprofundamento em Full Stack Java, Angular, Docker e AWS
2026  ──  Suporte Técnico N1 na Autotrac + expansão para PostGIS e ESP32
```

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:ED8B00,100:0A66C2&height=100&section=footer" alt="footer"/>
