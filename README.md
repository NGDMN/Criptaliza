# Criptaliza - Sistema de Gestão de Investimentos em Criptoativos

## 📊 Visão Geral

Sistema web para gerenciamento de carteiras de criptomoedas com análise de perfil de risco e recomendações personalizadas. Desenvolvido como projeto acadêmico para a disciplina de Engenharia de Software (2º ano) da FIAP.

**Status:** Em desenvolvimento  
**Entrega:** Fase 2 - Implementação de Classes Java

## 🎯 Problema e Solução

### Problema Identificado
- 12% da população brasileira possui criptomoedas, mas enfrenta barreiras:
  - Interfaces complexas e técnicas
  - Falta de orientação personalizada
  - Insegurança sobre custódia e riscos
  - Fragmentação entre múltiplas exchanges

### Nossa Solução
Plataforma web que atua como assistente virtual financeiro, oferecendo:
- ✅ Análise automatizada de perfil de investidor
- ✅ Recomendações personalizadas de alocação
- ✅ Dashboard unificado de múltiplas carteiras
- ✅ Gestão de risco e rebalanceamento automático
- ✅ Integração segura com exchanges

## 🏗️ Arquitetura

### Tecnologias
- **Linguagem:** Java 17 (puro, sem frameworks)
- **Banco de Dados:** PostgreSQL (planejado)
- **Padrões:** MVC, Singleton, Factory, Observer
- **Segurança:** PBKDF2 para senhas, JWT para autenticação

### Decisões Técnicas

| Decisão | Justificativa |
|---------|--------------|
| UUID para IDs | Unicidade global, segurança contra enumeração, preparado para distribuição |
| BigDecimal para valores | Precisão absoluta em cálculos financeiros |
| Versionamento otimista | Controle de concorrência sem locks pessimistas |
| Idempotency keys | Evita duplicação em operações críticas |
| Interfaces segregadas | Auditable, Negotiable, Validatable - responsabilidades claras |

## 📦 Estrutura do Projeto


## 🔧 Como Executar

### Pré-requisitos


### Compilação e Execução


