# Requisitos do Projeto

Este documento apresenta os requisitos funcionais e não funcionais do Line of Scrimmage, servindo como referência para o planejamento, desenvolvimento e evolução da plataforma.

---

## 1. Requisitos Funcionais

Os requisitos funcionais descrevem as funcionalidades que o sistema deverá disponibilizar aos usuários.

### 1.1 Conteúdo e artigos

#### RF01 — Listagem de artigos

O sistema deverá apresentar uma lista de artigos publicados, exibindo informações como título, imagem de destaque, categoria, autor e data de publicação.

**Prioridade:** Alta  
**Versão:** MVP

#### RF02 — Visualização de artigo

O sistema deverá permitir que o usuário acesse um artigo individual e visualize seu conteúdo completo.

**Prioridade:** Alta  
**Versão:** MVP

#### RF03 — Categorização de artigos

O sistema deverá permitir a organização dos artigos por categorias.

Categorias iniciais:

- Notícias
- História
- Times
- Jogadores
- Curiosidades
- Análises

**Prioridade:** Alta  
**Versão:** MVP

#### RF04 — Pesquisa de conteúdo

O sistema deverá permitir que o usuário pesquise artigos e outros conteúdos disponíveis na plataforma.

**Prioridade:** Média  
**Versão:** V2

---

### 1.2 Times da NFL

#### RF05 — Listagem de times

O sistema deverá apresentar os times da NFL organizados por conferência e divisão.

**Prioridade:** Alta  
**Versão:** MVP

#### RF06 — Detalhes do time

O sistema deverá permitir visualizar informações detalhadas de cada franquia, incluindo nome, cidade, estádio, conferência, divisão, ano de fundação e histórico.

**Prioridade:** Alta  
**Versão:** MVP

---

### 1.3 Jogadores

#### RF07 — Listagem de jogadores

O sistema deverá permitir consultar jogadores cadastrados na plataforma.

**Prioridade:** Média  
**Versão:** MVP

#### RF08 — Detalhes do jogador

O sistema deverá apresentar informações sobre o jogador selecionado, incluindo nome, posição, equipe e dados relevantes de sua carreira.

**Prioridade:** Média  
**Versão:** MVP

---

### 1.4 Partidas e temporada

#### RF09 — Calendário de partidas

O sistema deverá permitir visualizar partidas da NFL organizadas por temporada e semana.

**Prioridade:** Média  
**Versão:** V2

#### RF10 — Resultado das partidas

O sistema deverá apresentar os resultados das partidas realizadas.

**Prioridade:** Média  
**Versão:** V2

#### RF11 — Classificação

O sistema deverá permitir visualizar a classificação das equipes por conferência e divisão.

**Prioridade:** Média  
**Versão:** V2

---

### 1.5 Usuários

#### RF12 — Cadastro de usuário

O sistema poderá permitir o cadastro de usuários para acesso a funcionalidades personalizadas.

**Prioridade:** Baixa  
**Versão:** V3

#### RF13 — Autenticação

O sistema poderá permitir autenticação de usuários através de login e senha.

**Prioridade:** Baixa  
**Versão:** V3

#### RF14 — Comentários

Usuários autenticados poderão comentar em artigos publicados.

**Prioridade:** Baixa  
**Versão:** V3

---

## 2. Requisitos Não Funcionais

### RNF01 — Responsividade

A interface deverá ser responsiva e funcionar adequadamente em computadores, tablets e smartphones.

**Prioridade:** Alta

### RNF02 — Usabilidade

A aplicação deverá apresentar navegação simples e intuitiva.

**Prioridade:** Alta

### RNF03 — Desempenho

A aplicação deverá evitar operações desnecessariamente pesadas e apresentar tempos de carregamento adequados.

**Prioridade:** Alta

### RNF04 — Persistência

Os dados da aplicação deverão ser armazenados em banco de dados relacional.

**Prioridade:** Alta

### RNF05 — Arquitetura

A aplicação deverá utilizar uma arquitetura que permita a separação entre apresentação, regras de negócio e persistência de dados.

**Prioridade:** Alta

### RNF06 — API

O backend deverá disponibilizar uma API REST para comunicação com o frontend.

**Prioridade:** Alta

### RNF07 — Segurança

Dados sensíveis e funcionalidades restritas deverão possuir mecanismos adequados de proteção e controle de acesso.

**Prioridade:** Média

### RNF08 — Manutenibilidade

O código deverá seguir uma estrutura organizada, buscando facilitar manutenção, testes e evolução da aplicação.

**Prioridade:** Alta

### RNF09 — Versionamento

O projeto deverá utilizar Git para controle de versão, mantendo o desenvolvimento organizado por branches.

**Prioridade:** Alta

---

## 3. Escopo do MVP

A primeira versão funcional do Line of Scrimmage deverá concentrar-se nas funcionalidades essenciais:

- Listagem de artigos;
- Visualização de artigos;
- Categorias de conteúdo;
- Listagem de times;
- Informações detalhadas dos times;
- Listagem de jogadores;
- Informações básicas dos jogadores;
- Interface responsiva.

Funcionalidades relacionadas a partidas, classificação, usuários e comentários poderão ser implementadas em versões posteriores.

---

## 4. Evolução prevista

O projeto poderá evoluir posteriormente com recursos como:

- Calendário e resultados de partidas;
- Classificação da NFL;
- Estatísticas de jogadores;
- Dashboard;
- Autenticação;
- Comentários;
- Favoritos;
- Comparação entre jogadores;
- Integração com APIs externas;
- Painel administrativo para gerenciamento do conteúdo.

---

## 5. Status

**Status atual:** Planejamento
