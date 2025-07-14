# 📱 KingSMS

<div align="center">

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge&color=FFD700)
![Versão](https://img.shields.io/badge/Versão-1.0.0-blue?style=for-the-badge&color=1a1a1a&labelColor=FFD700)
![Licença](https://img.shields.io/badge/Licença-Proprietária-red?style=for-the-badge&color=2a2a2a&labelColor=FFD700)
![Família King](https://img.shields.io/badge/Família-King-gold?style=for-the-badge&color=FFD700&labelColor=1a1a1a)

**Leitor Inteligente de SMS para Caminhoneiros**

[📱 Download APK](https://kinggrouptech.com/downloads/apk/kingsms/) • [🌐 Versão Web](https://kingsms-app.web.app) • [📖 Documentação](./docs/) • [🐛 Reportar Bug](./issues/)

</div>

---

## 📋 Índice

- [🎯 Sobre o Projeto](#-sobre-o-projeto)
- [✨ Funcionalidades](#-funcionalidades)
- [🚀 Tecnologias](#-tecnologias)
- [📦 Instalação](#-instalação)
- [🔧 Configuração](#-configuração)
- [📱 Como Usar](#-como-usar)
- [🎨 Padrão Visual](#-padrão-visual)
- [🔄 Workflows](#-workflows)
- [🤝 Contribuição](#-contribuição)
- [📄 Licença](#-licença)
- [👥 Equipe](#-equipe)

---

## 🎯 Sobre o Projeto

O **KingSMS** é parte da **Família King**, uma suíte completa de aplicativos desenvolvidos especialmente para caminhoneiros e profissionais do transporte rodoviário brasileiro.

### 🎯 Objetivo
Leitor Inteligente de SMS para Caminhoneiros, oferecendo uma solução completa e integrada para as necessidades específicas dos usuários.

### 🌟 Diferenciais
- ✅ **Interface Intuitiva** - Máximo 3 cliques para qualquer funcionalidade
- ✅ **Comandos de Voz** - Controle hands-free total
- ✅ **Modo Offline** - Funciona sem conexão com internet
- ✅ **Integração Família King** - Conecta com outros apps da suíte
- ✅ **Padrão Profissional** - Qualidade empresarial

---

## ✨ Funcionalidades

### 🔥 Principais
- 📱 **Leitura por Voz** - SMS lidas automaticamente
- 🎤 **Resposta por Voz** - Ditado inteligente com IA
- 📞 **Envio Inteligente** - Manual ou por comando
- 🔗 **Integração KingRoad** - Funciona durante navegação
- ⚡ **Respostas Rápidas** - Templates para caminhoneiros

### 🎤 Comandos de Voz
- **"KingSMS, abrir"** - Inicia o aplicativo
- **"KingSMS, ajuda"** - Mostra comandos disponíveis
- **"KingSMS, configurações"** - Abre configurações
- **"KingSMS, sair"** - Fecha o aplicativo

### 🔗 Integração Família King
- 🚛 **KingRoad** - Navegação integrada
- 📱 **KingSMS** - Notificações por voz
- 💬 **KingChat** - Comunicação entre usuários
- 🔒 **KingLock** - Segurança unificada

---

## 🚀 Tecnologias

### 📱 Mobile (Android)
- **React Native 0.72** - Framework mobile
- **Speech-to-Text** - Reconhecimento de voz
- **Text-to-Speech** - Síntese de voz
- **SMS API** - Integração com sistema nativo

### 🌐 Web (Frontend)
- **React 18** - Interface moderna e responsiva
- **TypeScript** - Tipagem estática para maior robustez
- **Material-UI** - Componentes visuais profissionais
- **PWA** - Progressive Web App para melhor experiência

### ⚙️ Backend (APIs)
- **Python 3.11** - Linguagem principal do backend
- **Flask** - Framework web minimalista e eficiente
- **Google Cloud** - Infraestrutura escalável
- **Firestore** - Banco de dados NoSQL

### 🔄 DevOps
- **GitHub Actions** - CI/CD automatizado
- **Docker** - Containerização para deploy
- **Google App Engine** - Hospedagem backend
- **Firebase Hosting** - Hospedagem frontend

---

## 📦 Instalação

### 📱 Android (APK)
1. Acesse [kinggrouptech.com/downloads/apk/kingsms/](https://kinggrouptech.com/downloads/apk/kingsms/)
2. Baixe o arquivo **kingsms-latest.apk**
3. Habilite "Fontes desconhecidas" nas configurações
4. Instale o APK baixado

### 🌐 Web (Browser)
1. Acesse [kingsms-app.web.app](https://kingsms-app.web.app)
2. Para melhor experiência, adicione à tela inicial
3. O app funciona offline após primeiro acesso

### 💻 Desenvolvimento Local
```bash
# Clone o repositório
git clone https://github.com/kinggroup/KingSMS.git
cd KingSMS

# Instale dependências
npm install

# Configure variáveis de ambiente
cp .env.example .env.local

# Execute em modo desenvolvimento
npm run dev
```

---

## 🔧 Configuração

### 🔑 Variáveis de Ambiente
```env
# Configurações da aplicação
APP_NAME=KingSMS
APP_VERSION=1.0.0
NODE_ENV=production

# APIs e serviços
API_BASE_URL=https://kingsms-backend-dot-kinggrouptech-93908.uc.r.appspot.com
FIREBASE_PROJECT_ID=kinggrouptech-93908

# Recursos específicos
VOICE_COMMANDS_ENABLED=true
OFFLINE_MODE_ENABLED=true
KING_INTEGRATION_ENABLED=true
```

### ⚙️ Configurações Avançadas
- **Modo Desenvolvedor** - Ative nas configurações para logs detalhados
- **Comandos Personalizados** - Configure atalhos de voz específicos
- **Sincronização** - Configure backup automático na nuvem

---

## 📱 Como Usar

### 🚀 Primeiro Acesso
1. **Instale** o aplicativo seguindo as instruções acima
2. **Abra** o KingSMS
3. **Configure** suas preferências iniciais
4. **Teste** os comandos de voz básicos

### 💡 Dicas de Uso
- Use comandos de voz para operação hands-free
- Mantenha o app atualizado para novas funcionalidades
- Configure backup automático para não perder dados
- Explore a integração com outros apps da Família King

### 🆘 Solução de Problemas
- **App não abre**: Verifique se tem espaço suficiente no dispositivo
- **Comandos de voz não funcionam**: Verifique permissões de microfone
- **Sincronização falha**: Verifique conexão com internet
- **Performance lenta**: Reinicie o aplicativo

---

## 🎨 Padrão Visual

### 🎨 Paleta de Cores Oficial
```css
:root {
  --king-gold: #FFD700;           /* Dourado principal */
  --king-black: #1a1a1a;          /* Preto profundo */
  --king-gray-dark: #2a2a2a;      /* Cinza escuro */
  --king-white: #ffffff;          /* Branco puro */
  --king-gray-light: #cccccc;     /* Cinza claro */
  --king-beige-jupiter: #f5f5f0;  /* Bege Júpiter */
}
```

### 🎯 Princípios de Design
- **Máximo 3 cliques** para qualquer funcionalidade (Regra Steve Jobs)
- **Contraste alto** para melhor legibilidade
- **Ícones intuitivos** com significado universal
- **Responsividade total** para todos os dispositivos
- **Acessibilidade** seguindo padrões WCAG

---

## 🔄 Workflows

Este repositório possui **4 workflows automatizados**:

### 🚀 Deploy Backend
- **Trigger**: Push em `main` com mudanças no backend
- **Destino**: Google App Engine
- **URL**: https://kingsms-backend-dot-kinggrouptech-93908.uc.r.appspot.com

### 🌐 Deploy Frontend  
- **Trigger**: Push em `main` com mudanças no frontend
- **Destino**: Firebase Hosting
- **URL**: https://kingsms-app.web.app

### 📱 Build APK
- **Trigger**: Push em `main` com mudanças no mobile
- **Destino**: Google Cloud Storage
- **Download**: https://kinggrouptech.com/downloads/apk/kingsms/

### 💾 Backup Código Fonte
- **Trigger**: Push em `main` ou agendamento diário
- **Destino**: Google Cloud Storage
- **Retenção**: 90 dias

---

## 🤝 Contribuição

### 👨‍💻 Para Desenvolvedores
1. **Fork** este repositório
2. **Crie** uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. **Commit** suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. **Push** para a branch (`git push origin feature/nova-funcionalidade`)
5. **Abra** um Pull Request

### 📋 Padrões de Código
- **ESLint** - Linting automático
- **Prettier** - Formatação consistente
- **TypeScript** - Tipagem obrigatória
- **Testes** - Cobertura mínima de 80%

### 🐛 Reportar Bugs
Use o template de issue para reportar bugs:
- Descreva o problema detalhadamente
- Inclua passos para reproduzir
- Adicione screenshots se necessário
- Informe versão do app e dispositivo

---

## 📄 Licença

Este projeto é **propriedade privada** da **KingGroup** e está protegido por direitos autorais.

### ⚖️ Termos de Uso
- ✅ **Uso pessoal** permitido para usuários finais
- ❌ **Redistribuição** não autorizada
- ❌ **Modificação** do código fonte proibida
- ❌ **Uso comercial** sem licença específica

Para licenciamento comercial, entre em contato: **suporte@kinggrouptech.com**

---

## 👥 Equipe

### 🏢 KingGroup
- **Desenvolvimento**: Equipe KingGroup
- **Design**: Estúdio Família King
- **QA**: Departamento de Qualidade
- **DevOps**: Infraestrutura KingGroup

### 📞 Contato
- **Website**: [kinggrouptech.com](https://kinggrouptech.com)
- **Email**: suporte@kinggrouptech.com
- **Suporte**: [kinggrouptech.com/suporte](https://kinggrouptech.com/suporte)

---

<div align="center">

**Desenvolvido com ❤️ pela equipe KingGroup**

**Família King** • **Qualidade Profissional** • **Inovação Constante**

[🏠 Voltar ao Início](#-kingsms) • [📱 Download](https://kinggrouptech.com/downloads/apk/kingsms/) • [🌐 Site Oficial](https://kinggrouptech.com)

</div>
