# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS  

**Data:** 10 de fevereiro de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Gustavo Leal  

---

## Introdução  

Este relatório apresenta o processo de implementação de serviços da Amazon Web Services (AWS) na empresa Abstergo Industries, conduzido por Gustavo Leal.  

O objetivo do projeto foi selecionar e implementar três serviços estratégicos da AWS com foco na redução imediata de custos operacionais, aumento da disponibilidade dos sistemas e melhoria da escalabilidade da infraestrutura tecnológica.

---

## Descrição do Projeto  

O projeto foi dividido em três etapas, cada uma com objetivos específicos e impacto direto na redução de custos e modernização da infraestrutura.

---

## Etapa 1: Migração de Servidores Físicos para Amazon EC2  

- **Foco da ferramenta:** Virtualização e eliminação de servidores on-premise  
- **Descrição do caso de uso:**  

A empresa mantinha dois servidores físicos locais para hospedagem de sistemas internos e aplicações web. Esses servidores geravam custos elevados com energia, manutenção preventiva, substituição de hardware e suporte técnico.

Com a migração para instâncias EC2:
- Eliminou-se o custo de manutenção de hardware físico  
- Reduziu-se o consumo de energia elétrica  
- Passou-se a pagar apenas pelos recursos utilizados (modelo pay-as-you-go)  
- Obteve-se escalabilidade sob demanda  

**Resultado:** Redução estimada de 35% nos custos de infraestrutura no primeiro mês.

---

## Etapa 2: Migração do Banco de Dados para Amazon RDS  

- **Foco da ferramenta:** Banco de dados gerenciado  
- **Descrição do caso de uso:**  

O banco de dados anteriormente rodava em servidor próprio, exigindo manutenção manual, backups periódicos realizados pela equipe interna e alto risco operacional.

Com a implementação do Amazon RDS:
- Backups automáticos foram configurados  
- Atualizações de segurança passaram a ser gerenciadas automaticamente  
- Implementou-se alta disponibilidade com replicação  
- Reduziu-se o tempo de indisponibilidade  

**Resultado:** Diminuição de 40% no tempo gasto com administração de banco de dados e maior confiabilidade do sistema.

---

## Etapa 3: Armazenamento de Arquivos em Amazon S3  

- **Foco da ferramenta:** Armazenamento escalável e de baixo custo  
- **Descrição do caso de uso:**  

Arquivos internos, relatórios e backups eram armazenados em servidores locais com espaço limitado e risco de perda de dados.

Com a adoção do Amazon S3:
- Os arquivos passaram a ser armazenados em ambiente altamente durável  
- Implementou-se política de versionamento  
- Configurou-se armazenamento em camadas para redução de custos  
- Garantiu-se acesso seguro via controle de permissões  

**Resultado:** Redução de 50% nos custos relacionados a armazenamento e backup.

---

## Conclusão  

A implementação dos serviços AWS na Abstergo Industries proporcionou redução significativa de custos operacionais, maior escalabilidade da infraestrutura e aumento da segurança dos dados.

Recomenda-se a continuidade da utilização dos serviços implementados, bem como a avaliação futura de novas soluções em nuvem, como balanceamento de carga e monitoramento avançado, para aprimorar ainda mais a eficiência operacional da empresa.

---

## Anexos  

- Plano de migração de infraestrutura  
- Planilha comparativa de custos (antes e depois da migração)  
- Diagrama da nova arquitetura em nuvem  
- Política de backup e recuperação de desastres  

---

**Assinatura do Responsável pelo Projeto:**  

Gustavo Leal  
