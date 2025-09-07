# Requisitos — Módulo 1: Sistema de Revenda

## 1. Gestão de Contas de Revendedores
- Criação de contas com níveis: admin, revendedor, cliente final
- Cadastro: nome, empresa, contato
- Configuração de permissões e comissões por revendedor

## 2. Configuração de Planos e Preços
- Criar planos (básico, intermediário, avançado, customizado)
- Definir funcionalidades liberadas por plano
- Customização de branding (logotipo, cores, temas)

## 3. Interface Administrativa
- Painel para gestão de revendedores, clientes e agentes de IA
- Visualização de desempenho

## 4. Relatórios e Análises
- Relatórios de performance dos revendedores
- Métricas de uso e receita

## 5. Sistema de Pagamento
- Integração com API do Asaas para cobranças automáticas e gestão de faturas

---

## Exemplo de User Stories

- **Como Admin**, quero criar e editar contas de revendedores para controlar o acesso ao sistema.
- **Como Revendedor**, quero configurar meus próprios clientes finais e planos para oferecer o serviço conforme meu modelo de negócio.
- **Como Revendedor**, quero acompanhar meus ganhos e desempenho em um painel.
- **Como Cliente Final**, quero acessar o sistema apenas às funções liberadas pelo meu plano.

---

## Regras de Negócio
- Apenas administradores podem criar novos revendedores
- Revendedores podem criar clientes finais, mas não outros revendedores
- Comissão definida por plano e por revendedor
- Permissão granular por função/acesso

---

## Integrações
- API Asaas: criação de cobranças, consulta de faturas e status de pagamento

---

## Critérios de Aceite
- Fluxo de cadastro e login funcional para todos os tipos de usuário
- Permissões respeitadas em todas as ações administrativas
- Relatórios acessíveis via painel e exportáveis (PDF/Excel)