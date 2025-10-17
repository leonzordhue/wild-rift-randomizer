# 🛡️ Política de Segurança

## Reportando Vulnerabilidades

Leve a segurança a sério! Se você descobrir uma vulnerabilidade, por favor:

**⚠️ NÃO reporte issues públicas para vulnerabilidades de segurança**

Em vez disso, entre em contato diretamente através de:
- **Email**: [seu-email@provedor.com]
- **Discord**: [seu-discord]

## Medidas de Segurança Implementadas

### 🔒 Frontend
- **Content Security Policy (CSP)** para prevenir ataques XSS
- **Validação de entrada** no client-side
- **Sanitização de dados** no console
- **HTTPS obrigatório** via GitHub Pages

### 💾 Dados
- **Armazenamento local** apenas (não há servidor backend)
- **Dados anonimizados** quando possível
- **Nenhum dado sensível** é coletado ou armazenado

### 🌐 Segurança do Navegador
- **Prevenção contra clickjacking**
- **Headers de segurança** via GitHub Pages
- **Origins autorizadas** validadas

## Escopo de Segurança

Este projeto é um aplicativo **client-side apenas**, o que significa:

### ✅ O que TEMOS:
- Aplicativo estático hospedado no GitHub Pages
- Dados salvos localmente no seu navegador
- Código aberto e auditável

### ❌ O que NÃO TEMOS:
- Servidor backend
- Banco de dados centralizado
- Coleta de dados pessoais
- Cookies de rastreamento
- APIs externas

## Responsabilidade do Usuário

Como usuário, você é responsável por:
- Manter seu navegador atualizado
- Não compartilhar dados sensíveis
- Usar o aplicativo em dispositivos seguros

## Agradecimentos

Agradecemos a todos os pesquisadores de segurança que ajudam a manter nossa comunidade segura!