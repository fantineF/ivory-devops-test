# Teste Técnico - Estágio DevOps | IVORY IT

## Objetivo

Este projeto foi desenvolvido como parte do processo seletivo para a vaga de Estágio DevOps da IVORY IT.

O objetivo foi implementar uma pipeline de CI/CD capaz de automatizar o processo desde o versionamento do código até o deploy de um site estático em ambiente AWS.

---

## Arquitetura

Developer
↓
GitHub
↓
GitHub Actions
↓
SonarCloud
↓
Amazon S3
↓
Amazon CloudFront
↓
Usuário Final

---

## Tecnologias Utilizadas

- Git
- GitHub
- GitHub Actions
- SonarCloud
- AWS S3
- AWS CloudFront
- AWS IAM
- HTML
- CSS

---

## Fluxo da Pipeline

1. Desenvolvimento local
2. Commit e Push para o GitHub
3. Execução automática da GitHub Actions
4. Análise de qualidade pelo SonarCloud
5. Deploy dos arquivos para o Amazon S3
6. Invalidação do cache do CloudFront
7. Atualização automática do site

---

## Estrutura de Branches

- main
- homolog
- develop
- feature/add-static-site

---

## Site em Produção

https://d2bwci5gje1q6i.cloudfront.net

---

## Requisitos Atendidos

- Versionamento utilizando Git
- Estratégia de branches
- Pipeline CI/CD automatizada
- Integração com SonarCloud
- Deploy automatizado para AWS
- Hospedagem em Amazon S3
- Distribuição via Amazon CloudFront

---

## Autora

Fantine Bonfim
