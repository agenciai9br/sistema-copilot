# Arquitetura do Sistema

## Backend
- NestJS (Node.js)
- Serviços modulares por domínio (revenda, atendimento, IA, voz, pagamentos)
- PostgreSQL (dados relacionais)
- MongoDB (dados não estruturados)
- RabbitMQ (mensageria)
- Redis (cache)

## Frontend
- React + Material UI
- Gerenciamento de estado global

## Infraestrutura
- Docker (containers)
- Kubernetes (orquestração)
- CI/CD (GitHub Actions)
- Monitoramento (Prometheus, Grafana, Sentry)

## Integrações
- Asaas (pagamentos)
- WhatsApp/Facebook/Instagram/Telegram/E-mail/SMS
- APIs de IA: OpenAI, Dialogflow, Watson, Azure, Hugging Face
- APIs de Voz: ElevenLabs, Resemble AI

## Segurança
- Autenticação JWT + 2FA
- Conformidade LGPD
- Criptografia de dados sensíveis

---

## Fluxo Básico de Usuário

1. Cadastro/Login
2. Escolha de plano/assinatura (pagamento)
3. Configuração de branding e canais
4. Criação de agentes de IA
5. Atendimento omnichannel centralizado
6. Relatórios e análises