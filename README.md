# 🔐 Gerador de Tokens BossDV

Projeto completo para geração, listagem e exportação de tokens com autenticação Firebase.

## 🚀 Funcionalidades

- Login com Firebase Auth (email/senha)
- Geração de token único
- Validação de nomes duplicados
- Salva token com:
  - `valid`: boolean
  - `expire_at`: data
  - `device_id`: UUID
  - `nome`: maiúsculo
- Listagem de tokens ativos e expirados
- Exportação como `.json`
- QR Code do token gerado
- Histórico de uso

## ⚙️ Como usar

1. Configure seu projeto no Firebase
2. Cole suas credenciais em `firebase-config.js`
3. Suba os arquivos no GitHub
4. Ative o GitHub Pages

## 🧾 Estrutura
