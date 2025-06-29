# Organo 2.0

&#x20;&#x20;

---

## 📖 Descrição

O **Organo 2.0** é uma aplicação **Single Page** construída com **React** para gerenciar equipes e colaboradores de forma dinâmica. Permite criar times, cadastrar colaboradores em cada time, alterar cores de cada equipe e destacar colaboradores favoritos.

---

## 🎯 Funcionalidades

- **Cadastro de Colaboradores** com nome, cargo, foto e time associado.
- **Criação de Times** personalizados, definindo nome e cor primária.
- **Alteração de cor** de times em tempo real usando input de cor.
- **Favoritar Colaboradores** com um clique para destacar membros importantes.
- **Remoção de Colaboradores** para manter a lista sempre atualizada.

---

## ⚙️ Tecnologias Utilizadas

| Tecnologia          | Versão |
| ------------------- | ------ |
| React               | 18.1.0 |
| react-scripts (CRA) | 5.0.1  |
| react-icons         | 4.8.0  |
| uuid                | 9.0.0  |
| hex-to-rgba         | 2.0.1  |
| CSS                 | —      |

---

## 🚀 Instalação e Execução

1. **Clone** o repositório:
   ```bash
   git clone https://github.com/Bruno-Biscaia/Organo2.0.git
   ```
2. **Instale** as dependências:
   ```bash
   cd Organo2.0
   npm install
   ```
3. **Inicie** em modo de desenvolvimento:
   ```bash
   npm start
   ```
4. **Acesse** via `http://localhost:3000`

---

## 📂 Estrutura do Projeto

```plaintext
Organo2.0/
├─ public/                # Arquivos estáticos (index.html, ícones)
├─ src/
│  ├─ componentes/        # Banner, Formulario, Time, Rodape
│  ├─ App.js              # Componente raiz
│  ├─ index.js            # Ponto de entrada
│  └─ index.css           # Estilos globais
├─ .gitignore
├─ package.json
└─ README.md              # Documentação do projeto
```

---

## ⚙️ Scripts Disponíveis

| Comando         | Descrição                                 |
| --------------- | ----------------------------------------- |
| `npm start`     | Inicia o servidor de desenvolvimento      |
| `npm run build` | Cria bundle otimizado para produção       |
| `npm test`      | Executa testes (Jest & React Testing Lib) |
| `npm run eject` | Ejecta configurações do Create React App  |

---

## 🤝 Contribuição

Contribuições são bem-vindas! Siga estes passos:

1. Faça um fork deste repositório.
2. Crie uma branch: `git checkout -b feature/nome-da-feature`.
3. Realize suas alterações e faça commit: `git commit -m "Adiciona feature X"`.
4. Envie para a branch: `git push origin feature/nome-da-feature`.
5. Abra um Pull Request.

---

## 📜 Licença

Este projeto está licenciado sob a **MIT License**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## ✒️ Autor

**Bruno Biscaia** — [GitHub](https://github.com/Bruno-Biscaia)

