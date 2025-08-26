# 🌐 LibManager Frontend

[![React](https://img.shields.io/badge/React-18.x-61dafb?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

O **LibManager Frontend** é a interface web desenvolvida em **React** para consumo da [LibManager API](../libmanager-api).  
Fornece uma experiência moderna, responsiva e intuitiva para **usuários, administradores e bibliotecários**.  

---

## 🚀 Funcionalidades
- 🏠 **Dashboard** → visão geral do sistema  
- 📚 **Livros** → listagem, cadastro e gerenciamento visual  
- 👥 **Usuários** → autenticação e controle de acesso  
- 🔄 **Empréstimos** → fluxo de retirada e devolução com interface amigável  
- 🎨 **UI/UX Moderna** → responsivo, com TailwindCSS e componentes reutilizáveis  

---

## 🛠️ Tecnologias
- [React 18.x](https://react.dev/)  
- [Vite](https://vitejs.dev/)  
- [TailwindCSS](https://tailwindcss.com/)  
- [Axios](https://axios-http.com/) → integração com a API  
- [React Router](https://reactrouter.com/) → navegação  
- [JWT Decode](https://www.npmjs.com/package/jwt-decode) → autenticação  

---

## ⚙️ Instalação

Clone o repositório:
```bash
git clone https://github.com/FeJoestar18/FRONT-LibManager.git
```

```bash
cd FRONT-LibManager
```

Instale as dependências:
```bash
npm install
```

Configure o ambiente criando um arquivo `.env`:
```env
VITE_API_URL=http://localhost:8000/api
```

Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

---

## 📌 Estrutura de pastas (simplificada)
```
src/
 ├── assets/        # Imagens, ícones e estáticos
 ├── components/    # Componentes reutilizáveis (Botões, Inputs, Modais...)
 ├── hooks/         # Hooks customizados
 ├── pages/         # Páginas principais (Login, Dashboard, Livros...)
 ├── services/      # Conexão com API (Axios)
 ├── styles/        # Estilos globais (Tailwind configs)
 └── App.jsx        # Arquivo principal
```

---

## 🤝 Contribuição
Contribuições são sempre bem-vindas!  
Para contribuir:
1. Faça um fork do projeto  
2. Crie uma branch (`git checkout -b feature/nova-feature`)  
3. Commit suas alterações (`git commit -m 'Adicionando nova feature'`)  
4. Envie um push (`git push origin feature/nova-feature`)  
5. Abra um Pull Request 🎉  

---

## 📄 Licença
Este projeto está licenciado sob a **MIT License** – veja o arquivo [LICENSE](LICENSE) para mais detalhes.  

---
