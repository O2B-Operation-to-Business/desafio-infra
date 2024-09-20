# Desafio O2B SRE/DevOps CI/CD

## Objetivo

Implementar e automatizar uma aplicação MERN (MongoDB, Express, React, Node.js) utilizando as seguintes tecnologias e práticas:

- **GitOps**: Fork model.
- **Docker & Docker-Compose**: Para rodar a stack localmente.
- **Jenkins X**: Pipeline CI/CD para rodar os testes automatizados.
- **Kubernetes (Minikube/Docker-Desktop/OpenShift)**: Orquestração de containers.
- **ArgoCD**: Continuous Delivery.
- **Ansible e Terraform**: Automação da infraestrutura.
- **Helm e Istio**: Gerenciamento de pacotes e malha de serviço.
- **Prometheus e Grafana**: Monitoramento e alertas.
- **Golang**: Criação de uma CLI para rodar localmente.
- **Testes Automatizados**: Unitários e de integração com erros intencionais.

## Passos

1. **Fork** este repositório.
2. **Clone** o repositório forkado para sua máquina local.
3. **Rodar a stack localmente** utilizando `docker-compose`:
   ```bash
   docker-compose up --build
   ```
4. **Provisione e configure a infraestrutura** utilizando Ansible e Terraform.
5. **Implemente a aplicação no Kubernetes** utilizando Helmfiles e Istio para roteamento.
6. **Implemente um pipeline com Jenkins X** para rodar os testes unitários e de integração automaticamente.
7. **Crie uma CLI em Go** para interagir com o backend localmente.
8. **Adicione Continuous Delivery** utilizando ArgoCD.
9. **Configure monitoramento e alertas** com Prometheus e Grafana.
10. **Execute os testes automatizados**:
   ```bash
   cd tests/unit
   npm install
   npm test

   cd ../integration
   npm install
   npm test
   ```
11. **Faça um Pull Request (PR)** com suas modificações para a branch `main`.
12. **Para submeter o desafio** adicione a tag "QueroO2B" ao PR e assine-o.
13. **Avaliação:** O sistema de score será executado via GitHub Actions após o PR ser mesclado.

## Tecnologias Utilizadas

- **MERN**: MongoDB, Express, React, Node.js
- **GitOps**: Fork Model
- **Automação**: Ansible, Terraform
- **Orquestração**: Kubernetes, Helm, Istio
- **CI/CD**: Jenkins X, ArgoCD
- **Monitoramento**: Prometheus, Grafana
- **CLI**: Desenvolvida em Go

## O que será avaliado

- Implementação de GitOps.
- Configuração do pipeline Jenkins X.
- Automação da infraestrutura com Ansible e Terraform.
- Implementação de Continuous Delivery com ArgoCD.
- Monitoramento e alertas com Prometheus e Grafana.
- Criação da CLI em Golang.
- Documentação do projeto.

## Submissão do Desafio

1. Ao finalizar, crie um Pull Request (PR) com as suas modificações.
2. Adicione a tag `QueroO2B` ao PR.
3. Certifique-se de que o PR está assinado.
4. O sistema de avaliação será executado automaticamente após a submissão.
