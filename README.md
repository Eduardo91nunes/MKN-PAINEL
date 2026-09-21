# 🌱 MKN — Painel Administrativo

Painel administrativo desenvolvido para gerenciamento de conteúdos do site institucional da **MKN Consultoria Ambiental**.

O projeto foi criado para facilitar a atualização de informações do site sem a necessidade de alterar diretamente o código da aplicação, permitindo maior autonomia no gerenciamento de conteúdos.

## 📌 Sobre o Projeto

O **MKN Painel Administrativo** funciona como uma área de gerenciamento do site institucional da MKN Consultoria Ambiental.

A proposta é centralizar o gerenciamento de conteúdos utilizados no site, permitindo que informações como **imagens, textos e projetos** possam ser administradas de forma mais prática.

O painel faz parte do ecossistema do projeto MKN, juntamente com o site institucional.

## 🧩 Projetos

O sistema é composto principalmente por:

```text
MKN
│
├── 🌐 Site Institucional
│   └── MKN
│
└── ⚙️ Painel Administrativo
    └── MKN-PAINEL
```

O painel é responsável pelo gerenciamento dos conteúdos que posteriormente são apresentados no site institucional.

## ✨ Funcionalidades

* 🔐 Área administrativa
* 🖼️ Gerenciamento de imagens
* ✏️ Gerenciamento de textos
* 📁 Gerenciamento de projetos
* 👀 Visualização de conteúdos
* 📤 Upload de arquivos
* 🔄 Atualização de conteúdos do site
* 🖥️ Interface administrativa

## 🛠️ Tecnologias

O projeto utiliza tecnologias web modernas para construção da interface administrativa e comunicação com a API.

### Front-end

* **React.js**
* **JavaScript**
* **HTML5**
* **CSS3**

### API

O projeto possui uma API responsável pelo processamento de uploads e comunicação entre o painel e os recursos utilizados pelo site.

## 📂 Estrutura do Repositório

A estrutura atual do repositório está organizada da seguinte forma:

```text
MKN-PAINEL/
│
├── painel-admin/
│   └── Código do painel administrativo
│
├── upload-api.zip
│   └── API responsável pelos uploads
│
└── README.md
```

## 🚀 Como Executar o Painel

### 1. Clone o repositório

```bash
git clone https://github.com/Eduardo91nunes/MKN-PAINEL.git
```

### 2. Acesse o projeto

```bash
cd MKN-PAINEL/painel-admin
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Execute o projeto

```bash
npm start
```

Após iniciar, o painel poderá ser acessado pelo endereço disponibilizado pelo ambiente de desenvolvimento.

## 📤 API de Upload

O repositório também contém o arquivo:

```text
upload-api.zip
```

Essa API é utilizada como suporte ao painel para operações relacionadas ao **upload e gerenciamento de arquivos**.

Para utilizá-la, é necessário extrair o conteúdo do arquivo e instalar suas respectivas dependências.

## 🔄 Funcionamento

O fluxo geral do sistema pode ser representado da seguinte maneira:

```text
             👤 Administrador
                    │
                    ▼
          ⚙️ Painel Administrativo
                    │
          ┌─────────┴─────────┐
          ▼                   ▼
     📝 Conteúdos         🖼️ Imagens
          │                   │
          └─────────┬─────────┘
                    ▼
                🔌 API
                    │
                    ▼
             💾 Armazenamento
                    │
                    ▼
             🌐 Site MKN
```

## 🎯 Objetivos

O painel foi desenvolvido com os seguintes objetivos:

* Facilitar a administração do site;
* Reduzir a necessidade de alterações diretamente no código;
* Centralizar o gerenciamento dos conteúdos;
* Facilitar a atualização de imagens e informações;
* Permitir maior autonomia para os responsáveis pelo site;
* Integrar o gerenciamento de conteúdos ao site institucional.

## 🔮 Melhorias Futuras

Algumas funcionalidades podem ser implementadas futuramente:

* [ ] Sistema completo de autenticação
* [ ] Controle de permissões de usuários
* [ ] Dashboard administrativo
* [ ] Gerenciamento de usuários
* [ ] Gerenciamento completo de projetos
* [ ] Editor de conteúdo
* [ ] Histórico de alterações
* [ ] Exclusão e organização de arquivos
* [ ] Melhorias de segurança
* [ ] Logs de operações
* [ ] Deploy automatizado

## 🔗 Projetos Relacionados

### 🌐 Site Institucional

Repositório do site institucional da MKN Consultoria Ambiental:

https://github.com/Eduardo91nunes/MKN

### ⚙️ Painel Administrativo

Este projeto:

https://github.com/Eduardo91nunes/MKN-PAINEL

## 👨‍💻 Desenvolvedor

Desenvolvido por **Eduardo Nunes**.

---

<p align="center">
  🌱 <strong>MKN Consultoria Ambiental</strong><br>
  Painel Administrativo
</p>
