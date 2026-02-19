# ModernizacaoMonolitos

Projeto do curso FullCycle 4.0 que demonstra práticas e estratégias para a modernização de aplicações monolíticas.

## Sobre

Este repositório reúne exemplos, diagramas e anotações para guiar a transformação de um monólito em uma arquitetura mais modular e escalável. O foco está em técnicas práticas como quebra por módulos, extração de serviços, conteinerização, e melhoria de observabilidade e deployment.

## Objetivos

- Documentar abordagens de modernização aplicáveis a sistemas legados.
- Fornecer exemplos e modelos para migração incremental.
- Demonstrar integração com containers, CI/CD e práticas de monitoração.

## Principais tópicos

- Análise e identificação de limites de módulos
- Estratégias de extrair serviços (strangling, facades)
- Conteinerização (Docker) e orquestração básica
- Observabilidade (logs, métricas, tracing)
- Padrões de deploy contínuo e testes automatizados

## Tecnologias (exemplos)

- Docker
- Kubernetes (opcional)
- Ferramentas de CI/CD (GitHub Actions, GitLab CI)
- Ferramentas de observabilidade (Prometheus, Grafana, Jaeger)

## Como usar

1. Explore o diagrama em `modelo.puml` para entender a proposta arquitetural.
2. Adapte os exemplos e passos para o seu monólito, iterando por módulos.
3. Acompanhe os commits e issues para ver as decisões tomadas durante a modernização.

## Estrutura do repositório

- `modelo.puml` — diagrama do modelo arquitetural.
- `README.md` — esta documentação.

## Licença

Projeto aberto para estudo e experimentação. Sinta-se livre para adaptar e contribuir.
