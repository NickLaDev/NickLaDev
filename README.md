# Nicolas Araújo

**Tech Lead & Full Stack Developer**

Eu trabalho transformando sistemas reais — muitas vezes legados, acoplados e difíceis de manter — em produtos mais organizados, integrados e preparados para crescer.

Minha atuação fica entre desenvolvimento e operação: backend, frontend, apps, APIs, bancos, integrações externas, deploy, suporte em produção e problemas que nem sempre estão só no código, como Android TV, Linux, rede, ADB, firmware e migrações graduais.

Atualmente atuo na InfinityMedia, liderando e desenvolvendo produtos usados em ambientes hoteleiros, com foco em APIs, sistemas administrativos, apps de TV, apps mobile, automação e IA aplicada.

## O que eu faço

- Desenvolvimento de APIs em PHP/Laravel, Node.js/TypeScript e Python/FastAPI
- Modernização de sistemas legados sem interromper operação em produção
- Desenvolvimento e integração de frontends em React/TypeScript
- Apps em Flutter para Android TV, mobile e web
- Integração entre produtos, bancos, serviços externos e sistemas existentes
- Automação e suporte remoto de Android TVs com ADB, Linux, SSH e redes
- Deploy e operação em VPS/Linux com Nginx, HTTPS e systemd
- IA aplicada a problemas reais, principalmente análise de imagens e automação operacional

## Problemas que eu resolvo

O tipo de problema que mais aparece no meu trabalho não é só "criar uma tela" ou "fazer uma API".

Normalmente envolve pegar um sistema que já existe, já está em produção, tem regra de negócio espalhada, depende de banco legado, integrações externas e operação real acontecendo — e evoluir isso sem quebrar o que já funciona. Boa parte desse trabalho é transformar um legado em uma versão moderna: repensar a arquitetura, reescrever por partes e migrar aos poucos, mantendo o produto no ar o tempo todo.

Quando o problema é novo, eu construo a solução do zero. Isso vai desde entender o problema e desenhar a arquitetura até desenvolver, colocar em produção e manter. Já toquei projetos completos nesse formato, cuidando das decisões técnicas do início ao fim.

Também lidero e coordeno o time de desenvolvimento: divido o trabalho, reviso entregas, defino padrões e ajudo a destravar quem está travado. Gosto de manter o time alinhado sem burocratizar, garantindo que o que sai esteja realmente pronto para produção.

O dia a dia também tem muito de resolver o que quebra: app que falha em TV box, dispositivo que não responde na rede, integração que muda comportamento, endpoint que precisa manter compatibilidade, fluxo legado que precisa virar API, ou uma migração que não pode ser feita de uma vez.

Uso Git e GitHub como parte central do fluxo — branches, pull requests, revisão de código e histórico organizado — tanto no meu trabalho quanto na coordenação do time. E tenho inglês em nível avançado, o que me deixa confortável para ler documentação, trabalhar com ferramentas e integrações internacionais e me comunicar em contextos técnicos em inglês.

## Experiência atual

**Tech Lead & Full Stack Developer — InfinityMedia**
_nov/2025 – atual_

Atuo na evolução do ecossistema de produtos da empresa, incluindo:

- **Infinity Manager v1** — manutenção evolutiva de sistema legado em PHP, com novas funções, correções em produção e integrações PMS.
- **Infinity Manager v2** — frontend moderno em React/TypeScript para gerenciar os serviços da InfinityMedia.
- **API Laravel do Manager v2** — API REST criada do zero para atender o novo frontend, mantendo paridade com o sistema legado.
- **API Node.js/TypeScript do Manager v2** — nova API planejada para substituir gradualmente a API Laravel.
- **Infinity Hospitality v5** — app Flutter para Android TV usado em quartos de hotel.
- **ISM API** — evolução da API Laravel consumida pelo app de TV.
- **ADB Server** — serviço em PHP/Slim para gerenciamento remoto de Android TVs via ADB.
- **API de Suporte** — API REST em PHP puro para abertura e gestão de chamados.
- **GuestCare / Room Check AI** — API em Python/FastAPI com IA para inspeção de quartos por imagem.
- **Infinity Concierge** — coordenação técnica do app mobile/web do hóspede e integração com backend.

## Projetos profissionais

> Alguns projetos são proprietários/privados. As descrições aqui focam no problema resolvido e na arquitetura, sem expor código, credenciais ou dados sensíveis.

### Infinity Manager v2 — API Laravel

API REST desenvolvida em PHP/Laravel para servir o novo frontend do Manager v2, mantendo paridade com o sistema legado em PHP. Essa API foi criada para permitir a modernização do produto sem migrar todo o legado de uma vez.

**Stack:** PHP, Laravel, MySQL, JWT, OpenAPI, Swagger, PHPUnit, APIs REST

### Infinity Manager v2 — Frontend Administrativo

Frontend moderno em React/TypeScript usado para gerenciar os produtos e serviços da InfinityMedia implantados em hotéis. O objetivo é centralizar operação, configuração e acompanhamento dos serviços da empresa, sem atuar como PMS.

**Stack:** React, TypeScript, Vite, REST APIs, RBAC, UX administrativo

### Infinity Manager v2 — API Node.js/TypeScript

API em Node.js/TypeScript planejada para substituir gradualmente a API Laravel no mesmo frontend do Manager v2. A estratégia é migrar por etapas, com paridade funcional, testes e integração com banco legado.

**Stack:** Node.js, TypeScript, Express, Zod, JWT, RBAC, MySQL/MariaDB

### Infinity Hospitality v5

App Flutter para Android TV usado em quartos de hotel, com TV ao vivo, EPG, room service, apps, QR Code, notificações, checkout, automação de quarto e integração PMS. O projeto exige atenção a performance em TV boxes, cache, feature flags, limitações de hardware, rede e firmware.

**Stack:** Flutter, Dart, Android TV, IPTV, HLS, EPG, REST APIs, cache

### ADB Server e suporte remoto de Android TVs

Serviço em PHP/Slim para executar comandos ADB remotamente em Android TVs, com instalação de APKs, limpeza de apps, validação de dispositivos, logs e integração com painel. Também envolve troubleshooting em produção com Linux, SSH, redes, ADB TCP/IP, logcat e firmware Android.

**Stack:** PHP, Slim Framework, ADB, Android TV, Linux, SSH, TCP/IP, Bash

### GuestCare / Room Check AI

API em Python/FastAPI para análise de quartos por imagem usando IA. Recebe fotos, realiza moderação, processa com modelo de visão e retorna laudo estruturado com status, nota, pontos positivos, negativos e justificativa.

**Stack:** Python, FastAPI, GPT-4o Vision, Pydantic, Nginx, HTTPS, Linux

## Projetos independentes

### CastTV

Plataforma de streaming multi-tenant com backend Node.js/Express, MongoDB, dashboard administrativo e apps Flutter para TV, mobile e web. Inclui gestão de instâncias, usuários, dispositivos, canais, EPG, pareamento, license server, HLS e criptografia.

**Stack:** Node.js, Express, MongoDB, Flutter, Android TV, HLS, JWT, criptografia

### NeoStream

Plataforma de streaming sob demanda com Python, MongoDB, Flussonic, BTCPay/Binance Pay e deploy em VPS Linux.

**Stack:** Python, MongoDB, Flussonic, Linux, APIs REST, pagamentos

### Sistema de pagamento via Bitcoin

Backend em Node.js para integração real de pagamentos via BTCPay, com geração de cobranças, webhooks, assinatura/licenciamento e operação em VPS.

**Stack:** Node.js, BTCPay, Webhooks, Linux, VPS

## Formação e histórico técnico

Estudante de Engenharia da Computação na PUC-Campinas.

Antes da minha atuação profissional atual, tive uma base forte em robótica competitiva e projetos de baixo nível:

- Campeão estadual e regional da Olimpíada Brasileira de Robótica
- 24º colocado nacional na OBR
- Projetos em C, Assembly 8086, estrutura de dados e robótica

## Stack principal

**Backend:** PHP, Laravel, Node.js, TypeScript, Python, FastAPI
**Frontend/App:** React, Flutter, Dart, Android TV
**Banco:** MySQL, MongoDB, SQLite
**Infra:** Linux, VPS, Nginx, Docker, SSH, systemd
**Integrações:** REST APIs, JWT, OpenAPI, Swagger, Webhooks
**Ferramentas & versionamento:** Git, GitHub, pull requests e code review
**Idiomas:** Inglês avançado (leitura, escrita e comunicação técnica)
**Outros:** ADB, IPTV, Streaming, IA aplicada, troubleshooting em produção

## Contato

- **LinkedIn:** https://www.linkedin.com/in/nicolas-araújo-0165a435a
- **GitHub:** https://github.com/NickLaDev
- **E-mail:** nicolas.laredo@yahoo.com
