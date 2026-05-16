# Documentação do Projeto Apache Hop

## Projeto: Atividade 15/05

### Alunos

Ana Luiza e Luan Matheus

---

# Objetivo do Projeto

O objetivo deste projeto foi desenvolver um pipeline ETL utilizando o Apache Hop para realizar processos de extração, transformação e carregamento de dados.

O ambiente foi configurado utilizando Docker, PostgreSQL, PgAdmin e Apache Hop Web.

---

# Tecnologias Utilizadas

* Apache Hop Web
* Docker
* Docker Compose
* PostgreSQL 15
* PgAdmin 4
* Git
* GitHub

---

# Estrutura do Projeto

```text
apache-hop/
│
├── docker-compose.yml
├── hop-config/
└── hop-projects/
    └── filename.hpl
```

---

# Configuração do Ambiente

O ambiente foi iniciado utilizando Docker Compose.

## Comando utilizado

```bash
docker compose up -d
```

---

# Containers Utilizados

| Serviço        | Porta |
| -------------- | ----- |
| Apache Hop Web | 8080  |
| PostgreSQL     | 5432  |
| PgAdmin        | 5050  |

---

# Pipeline Desenvolvido

O pipeline foi criado no Apache Hop Web e salvo no formato `.hpl`.

Arquivo principal:

```text
filename.hpl
```

O pipeline realiza operações de integração de dados utilizando transforms do Apache Hop.

---

# Versionamento com Git

O projeto foi versionado utilizando Git.

## Comandos utilizados

```bash
git init
git add .
git commit -m "Pipeline Apache Hop"
```

---

# Repositório GitHub

Repositório do projeto:

```text
https://github.com/AnaLuiza2431/atividade1505.git
```

---

# Resultado

O projeto foi configurado com sucesso utilizando Docker e Apache Hop Web.

O pipeline foi exportado do container Docker, salvo localmente e enviado para o GitHub utilizando Git.

---

# Considerações Finais

O desenvolvimento deste projeto permitiu praticar:

* Configuração de ambientes com Docker
* Utilização do Apache Hop
* Criação de pipelines ETL
* Versionamento com Git
* Publicação de projetos no GitHub
