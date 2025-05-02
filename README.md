# ☁️ Desafio DIO: Construindo Arquiteturas no Azure

Este repositório foi criado como parte do desafio de projeto da DIO com o objetivo de aplicar, na prática, os conceitos aprendidos sobre arquitetura de soluções em nuvem utilizando a plataforma Microsoft Azure.

---

## 📚 Conteúdo

- [Objetivo](#objetivo)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Passo a Passo da Implementação](#passo-a-passo-da-implementação)
- [Melhorias Adicionais](#melhorias-adicionais)
- [Recursos e Links Úteis](#recursos-e-links-úteis)
- [Conclusão](#conclusão)

---

## 🎯 Objetivo

- Reproduzir (e, se possível, aprimorar) a arquitetura proposta nas aulas práticas;
- Documentar cada etapa da construção da arquitetura no Azure;
- Consolidar conhecimento técnico e fortalecer o portfólio pessoal.

---

## 🛠 Tecnologias Utilizadas

- **Microsoft Azure**
- **Azure Resource Group**
- **Azure Virtual Network**
- **Azure Virtual Machines**
- **Azure Storage Account**
- **Azure App Services**
- **Azure SQL Database**
- [Outros recursos conforme necessário]

---

## 🔧 Passo a Passo da Implementação

1. **Criação do Resource Group**
   - Nome: `rg-projeto-arquitetura`
   - Região: *Brazil South*

2. **Configuração da Rede Virtual (VNet)**
   - Nome: `vnet-projeto`
   - Sub-redes: `subnet-web`, `subnet-db`

3. **Criação das Máquinas Virtuais**
   - Web Server (Linux/Windows)
   - Definição de regras de firewall e grupos de segurança de rede (NSG)

4. **Configuração do Banco de Dados**
   - Azure SQL Database
   - Conexão segura com a VNet/Subnet

5. **Deploy de Aplicações**
   - Azure App Services
   - Conexão com banco de dados
   - Testes de endpoint

6. **Monitoramento e Logs**
   - Azure Monitor
   - Application Insights

---

## 🚀 Melhorias Adicionais (Opcional)

- Implementação de **Balanceador de Carga (Load Balancer)**
- Configuração de **Escalabilidade automática (Auto-scaling)**
- Deploy com CI/CD via GitHub Actions
- Backup e recuperação do banco de dados

---

## 🔗 Recursos e Links Úteis

- [Portal do Azure](https://portal.azure.com/)
- [Documentação Oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Guia do Azure Architecture Center](https://learn.microsoft.com/pt-br/azure/architecture/)
- [GitHub do Expert (caso aplicável)](https://github.com/EXEMPLO)
- [Template no Figma (caso aplicável)](https://www.figma.com/EXEMPLO)

---

---

## ✅ Conclusão

Este projeto foi uma excelente oportunidade para aplicar conceitos reais de arquitetura em nuvem utilizando os serviços do Azure. A documentação detalhada aqui servirá como base para futuros projetos e revisões, além de compor um portfólio técnico sólido.

---



