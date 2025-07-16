# 🌾 Portal Fornecedor SCADIAgro

**Portal de fornecedores para o sistema SCADIAgro - Gestão simplificada para o agronegócio**

Este é um projeto acadêmico desenvolvido como parte do Projeto Integrador do IFB (Instituto Federal de Brasília), que implementa um portal web para fornecedores do sistema SCADIAgro, permitindo o gerenciamento de clientes, orçamentos e preços de produtos agrícolas.

## 📋 Sobre o Projeto

O Portal Fornecedor SCADIAgro é uma aplicação web responsiva que permite aos fornecedores:

- 🔐 **Autenticação segura** - Sistema de login e registro de usuários
- 👥 **Gestão de clientes** - Visualização e gerenciamento de clientes
- 💰 **Gestão de preços** - Controle de preços de produtos agrícolas
- 📊 **Orçamentos** - Criação e gerenciamento de orçamentos
- 👤 **Perfil de usuário** - Edição de dados pessoais e configurações

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica das páginas
- **CSS3** - Estilização e design responsivo
- **JavaScript** - Interatividade e funcionalidades dinâmicas
- **Bootstrap 5** - Framework CSS para componentes e grid system
- **Bootstrap Icons** - Biblioteca de ícones
- **Font Awesome** - Ícones adicionais
- **Google Fonts (Raleway)** - Tipografia moderna

## 📁 Estrutura do Projeto

```
scadiago-supplier-portal/
├── index.html              # Página de login
├── customers.html           # Gestão de clientes
├── budgets.html            # Gestão de orçamentos
├── prices.html             # Gestão de preços
├── register.html           # Cadastro de novos usuários
├── edit-register.html      # Edição de perfil
├── forgot-pass.html        # Recuperação de senha
├── password.html           # Alteração de senha
├── imgs/                   # Imagens e logos
│   ├── agro.jpg
│   ├── img-logo_icon.png
│   ├── img-logo_scadiagro.png
│   └── ...
├── styles/                 # Arquivos CSS
│   ├── style.css          # Estilos principais
│   ├── customers.css      # Estilos da página de clientes
│   ├── budgets.css        # Estilos da página de orçamentos
│   ├── prices.css         # Estilos da página de preços
│   └── edit-register.css  # Estilos da página de edição
├── LICENSE                 # Licença do projeto
└── README.md              # Este arquivo
```

## 🎯 Funcionalidades

### 🔑 Sistema de Autenticação
- Login de usuários cadastrados
- Registro de novos fornecedores
- Recuperação de senha via e-mail
- Alteração de senha

### 👥 Gestão de Clientes
- Visualização de lista de clientes
- Informações detalhadas dos clientes
- Interface responsiva com Bootstrap

### 💰 Gestão de Preços
- Cadastro de preços de produtos
- Atualização de valores
- Histórico de alterações

### 📊 Orçamentos
- Criação de novos orçamentos
- Gestão de orçamentos existentes
- Exportação de dados

### 👤 Perfil do Usuário
- Edição de dados pessoais
- Configurações da conta
- Gerenciamento de informações

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, mas recomendado)

### Método 1: Abrir diretamente no navegador
1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` em seu navegador

### Método 2: Servidor local (recomendado)
1. Clone o repositório:
   ```bash
   git clone https://github.com/TML45/scadiago-supplier-portal.git
   cd scadiago-supplier-portal
   ```

2. Inicie um servidor local:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (se tiver o http-server instalado)
   npx http-server
   
   # PHP
   php -S localhost:8000
   ```

3. Acesse `http://localhost:8000` no seu navegador

## 🎨 Design e UX

O projeto segue os princípios de design moderno com:

- **Design Responsivo** - Adaptável a diferentes tamanhos de tela
- **Interface Intuitiva** - Navegação clara e objetiva
- **Cores Corporativas** - Paleta baseada na identidade visual SCADIAgro
- **Tipografia Legível** - Fonte Raleway para melhor experiência de leitura
- **Acessibilidade** - Estrutura semântica e contraste adequado

## 🔄 Fluxo de Navegação

```
index.html (Login)
    ├── register.html (Cadastro)
    ├── forgot-pass.html (Esqueci a senha)
    └── customers.html (Dashboard principal)
            ├── budgets.html (Orçamentos)
            ├── prices.html (Preços)
            ├── edit-register.html (Editar perfil)
            └── password.html (Alterar senha)
```

## 👨‍💻 Equipe de Desenvolvimento

Este projeto foi desenvolvido por estudantes do IFB como parte do Projeto Integrador:

- **Gabriel** - Desenvolvedor Frontend
- **Jafah** - Desenvolvedor Frontend  
- **Tássio** - Desenvolvedor Frontend

## 📝 Licença

Este projeto está licenciado sob a [licença especificada no arquivo LICENSE](./LICENSE).

## 🤝 Contribuições

Como este é um projeto acadêmico, contribuições são bem-vindas para fins educacionais. Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## 📞 Contato

Para dúvidas ou sugestões sobre o projeto, entre em contato com a equipe de desenvolvimento através do repositório GitHub.

---

**Projeto Integrador - IFB | Portal Fornecedor SCADIAgro**