# Relatório de Implementação de Serviços AWS

**Data:** 05/09/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Rozvania

## Introdução

Este relatório apresenta o planejamento da implementação de uma solução em nuvem para a farmácia fictícia Abstergo Industries. O objetivo é reduzir custos e modernizar a infraestrutura usando serviços AWS.

## Serviços AWS Selecionados

### 1. Amazon S3
- **Foco:** Armazenamento de imagens de produtos, documentos e backups.
- **Benefício:** Redução de custos com servidores locais e alta durabilidade dos dados.
- **Link do diagrama:** `docs/arquitetura.png`

### 2. Amazon DynamoDB
- **Foco:** Banco de dados NoSQL para catálogo de produtos e controle de estoque.
- **Benefício:** Escalabilidade automática e sem necessidade de provisionamento de servidor.

### 3. AWS Lambda + API Gateway
- **Foco:** Processamento serverless de pedidos e integração entre S3 e DynamoDB.
- **Benefício:** Redução de custos operacionais, pagamento conforme uso e menor manutenção.

## Conclusão

A implementação desses serviços permite:
- Redução imediata de custos com infraestrutura física.
- Escalabilidade automática para atender picos de demanda.
- Segurança e durabilidade de dados críticos.
- Maior eficiência operacional e produtividade da equipe.

## Anexos

- Diagrama de arquitetura (`docs/arquitetura.png`)
- Link para template Figma ou outros arquivos necessários

**Assinatura do responsável:**  
Rozvania
