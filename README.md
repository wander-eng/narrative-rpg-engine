# Narrative RPG Engine
> Motor de RPG assíncrono para Discord impulsionado por IA, com foco em campanhas persistentes e narrativas consistentes.

## Visão geral

Este projeto é um mecanismo de RPG para Discord impulsionado por IA, focado em consistência narrativa persistente, narrativa autônoma e experimentação de arquitetura de LLMs.

A ideia nasceu da dor real de grupos que gostam de RPG, mas não conseguem conciliar agendas para jogar mesas tradicionais. O bot propõe uma experiência assíncrona, em que os jogadores podem participar em momentos diferentes, sem depender de um mestre humano presente o tempo todo.

## Problema que o projeto busca resolver

O projeto tenta reduzir ou eliminar problemas comuns em grupos de RPG:

* campanhas que morrem por dificuldade de conciliar horários;
* grupos em que ninguém quer narrar;
* mestres cansados de preparar tudo sozinho;
* barreiras de entrada para quem gostaria de jogar, mas não encontra mesa.

## Público-alvo

O projeto é voltado principalmente para:

* entusiastas de RPG;
* grupos de amigos;
* jogadores de RPG textual e assíncrono;
* jogadores adultos com pouco tempo livre;
* mestres que querem participar como jogadores;
* comunidades interessadas em narrativas guiadas por IA.

## O que diferencia este projeto

* persistência narrativa;
* foco em IA aplicada;
* campanhas longas;
* sandbox narrativo;
* estado de mundo consistente.

## Objetivos do projeto

* aprender Engenharia de Software assistida por IA e documentação técnica;
* construir um produto realmente utilizável;
* servir como portfólio técnico;
* manter a possibilidade de exploração acadêmica no futuro.

## O que não é objetivo imediato

* substituir RPG de mesa tradicional;
* competir com VTTs como Foundry;
* criar um MMORPG;
* criar um chatbot genérico;
* expandir para múltiplos servidores e múltiplas campanhas complexas logo de início.

## Estado atual

O projeto está em fase de planejamento arquitetural e preparação do MVP 0.

## Roadmap resumido

### MVP 0 — Fundação técnica

Objetivo: criar a infraestrutura mínima do projeto.

Inclui:

* estrutura de pastas e documentação inicial;
* projeto Python configurado;
* bot conectado ao Discord;
* banco de dados e logging básicos.

### MVP 1 — Narrador jogável

Objetivo: disponibilizar uma campanha pequena totalmente jogável.

Inclui:

* narração de turnos;
* leitura de fichas;
* uso das regras do sistema base;
* estado mínimo persistido;
* suporte a um servidor e um grupo pequeno.

### MVP 2 — Confiabilidade do runtime

Objetivo: tornar o sistema mais robusto e previsível.

Inclui:

* schemas e contratos;
* validação determinística;
* testes automatizados;
* observabilidade inicial.

### MVP 3 — Memória e recuperação de contexto

Objetivo: melhorar a consistência narrativa em campanhas longas.

Inclui:

* memória de curto e longo prazo;
* RAG;
* banco vetorial;
* recuperação contextual.

### MVP 4 — Maturidade de engenharia

Objetivo: preparar o projeto para evolução contínua.

Inclui:

* pipeline de CI mais completa;
* evals;
* testes E2E e BDD;
* refinamento arquitetural;
* otimizações de desempenho.

## Estrutura do projeto

```text
narrative-rpg-engine/
├── .ai/         # Engenharia de contexto e documentação para IA
├── docs/        # Documentação para desenvolvedores
├── schemas/     # Contratos (Schema-Driven Development)
├── src/         # Código do runtime do bot
├── tests/       # Testes automatizados
├── scripts/     # Scripts auxiliares
└── .github/     # Pipeline de CI
```

## Tecnologias escolhidas

* Python: pela relevância no ecossistema de IA e pela disponibilidade de ferramentas maduras.
* Discord: por ser um ambiente familiar para o público-alvo e facilitar a validação.
* LLMs: para automação da narração, interpretação de linguagem ambígua e geração de cenário.
* PostgreSQL: para persistência e aprendizado de uma tecnologia de banco de dados sólida.

## Princípios que guiam o desenvolvimento

* Progressive Disclosure
* Context Engineering
* Domain-Driven Design
* Harness Engineering
* Extreme Programming
* Spec-Driven Development (Specs de desenvolvimento)
* Schema-Driven Development (Contratos estruturados entre LLM e código)
* Test-Driven Development
* Behavior-Driven Development
* Small Releases
* Determinismo fora da LLM

## Filosofia do projeto

Este projeto não busca apenas construir um narrador de RPG.

Ele também serve como um laboratório para aplicar, avaliar e aprender práticas modernas de Engenharia de Software Assistida por IA, incluindo Context Engineering, Domain-Driven Design, Harness Engineering, Schema-Driven Development, Test-Driven Development e Progressive Disclosure.

A prioridade é construir um sistema que permaneça evoluível ao longo do tempo, permitindo experimentar diferentes arquiteturas de LLM sem comprometer a consistência do domínio.
