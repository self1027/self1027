<picture>
  <source media="(max-width: 600px)" srcset="assets/header-mobile.svg">
  <img src="assets/header.svg" alt="Murilo Dias — Engenharia de software, backend e APIs" width="1280">
</picture>

<p>
  <a href="https://www.murilod.dev/"><img src="assets/portfolio.svg" alt="Ver portfólio" height="44"></a>
  <a href="https://www.linkedin.com/in/murilo-dias-dev/"><img src="assets/linkedin.svg" alt="LinkedIn" height="44"></a>
  <a href="mailto:diasmurilo02@gmail.com"><img src="assets/email.svg" alt="Enviar e-mail" height="44"></a>
</p>

Sou desenvolvedor backend em Andradina, SP. Trabalho com Node.js, JavaScript e TypeScript na construção de APIs, sistemas internos e automações. Gosto de acompanhar o caminho completo: modelar os dados, implementar as regras de negócio e colocar a aplicação para rodar em Linux.

Curso Engenharia de Computação no UniSALESIANO Araçatuba. Também me interesso por processamento de mídia e comunicação em tempo real — assuntos que exploro nos meus projetos.

## Projetos

### Livro

Sistema interno da Vigilância Sanitária de Andradina para registrar denúncias, distribuir fiscalizações e consultar o histórico dos atendimentos. Substituiu consultas em papel por uma busca que leva segundos.

**Node.js · Express · Sequelize · MariaDB · EJS · Linux · Nginx · PM2**

<a href="https://livro.murilod.dev/"><img src="https://raw.githubusercontent.com/self1027/Livro/main/docs/screenshots/denuncias.png" alt="Livro: lista de denúncias com filtros e acompanhamento das fiscalizações, em uma demonstração com dados fictícios" width="1000"></a>

[Abrir demonstração](https://livro.murilod.dev/) · [Backend completo](https://github.com/self1027/Livro/tree/sistema-completo) · [Repositório](https://github.com/self1027/Livro)

A demonstração pública usa dados fictícios e persistência local no navegador. O backend do sistema interno está na branch `sistema-completo`.

### RAG VISA

API para consultar normas sanitárias em PDF. A ingestão roda em uma fila persistente; as consultas combinam busca vetorial e geração de respostas, com referências ao documento e à página quando identificadas. O projeto inclui avaliação das respostas e transmissão por SSE.

**TypeScript · Express · SQLite · Drizzle · Qdrant · RAG**

[Ver código e arquitetura](https://github.com/self1027/rag-visa)

### MeganTrimmer

Aplicativo desktop para cortar vídeos, converter formatos e extrair áudio. Integra FFmpeg ao Electron, com prévia, seleção na linha do tempo e acompanhamento da exportação. O processamento acontece no computador do usuário.

**Electron · TypeScript · FFmpeg · FFprobe · IPC**

<a href="https://github.com/self1027/MeganTrimmer"><img src="https://raw.githubusercontent.com/self1027/MeganTrimmer/main/docs/screenshots/corte-salvo.png" alt="MeganTrimmer: prévia de um vídeo de teste, seleção do corte e confirmação de exportação" width="1000"></a>

[Ver projeto](https://github.com/self1027/MeganTrimmer) · [Baixar para Windows](https://github.com/self1027/MeganTrimmer/releases)

### Integra MQF

TCC desenvolvido com Victor Hugo no UniSALESIANO Araçatuba. Conecta fala em português à transcrição local com Vosk e à sinalização por um avatar VLibras. A tradução e os sinais dependem de serviços públicos na internet; a validação linguística com usuários fluentes em Libras ainda está pendente.

**Node.js · WebSocket · Vosk · FFmpeg · Unity/WebGL · VLibras**

<a href="https://integra.murilod.dev/"><img src="https://raw.githubusercontent.com/self1027/Integra/main/docs/screenshots/tema-escuro.png" alt="Integra MQF: interface de transcrição de fala e avatar de Libras no tema escuro" width="1000"></a>

[Abrir demonstração](https://integra.murilod.dev/) · [Ver projeto](https://github.com/self1027/Integra)

## No dia a dia

- **Backend:** Node.js, JavaScript, TypeScript, Express e APIs REST.
- **Dados:** SQL, MariaDB, PostgreSQL, SQLite, Sequelize e Drizzle, conforme o projeto.
- **Entrega:** Git, Linux, Nginx, PM2 e Postman.

<details>
<summary>Read in English</summary>

### Backend development & APIs

I'm Murilo, a backend developer based in Andradina, Brazil, and a Computer Engineering student at UniSALESIANO Araçatuba. I build APIs, internal tools and automations with Node.js, JavaScript and TypeScript, from data modeling and business logic to deployment on Linux.

My projects include:

- **[Livro](https://github.com/self1027/Livro/tree/sistema-completo):** an internal system for Andradina's health surveillance team, covering complaints, inspections and case history. The [public demo](https://livro.murilod.dev/) uses fictional data and browser storage.
- **[RAG VISA](https://github.com/self1027/rag-visa):** an API for querying public health regulations in PDF, with persistent ingestion, vector search, streamed answers and source references.
- **[MeganTrimmer](https://github.com/self1027/MeganTrimmer):** an Electron desktop app for trimming and converting videos with FFmpeg. Media processing runs on the user's computer.
- **[Integra MQF](https://github.com/self1027/Integra):** a graduation project coauthored with Victor Hugo, connecting Portuguese speech recognition to a VLibras signing avatar. Transcription runs locally; translation requires internet access. Linguistic validation is pending.

I also explore media processing and real-time communication alongside my main focus on backend engineering.

[Portfolio](https://www.murilod.dev/) · [LinkedIn](https://www.linkedin.com/in/murilo-dias-dev/) · [Email](mailto:diasmurilo02@gmail.com)

</details>
