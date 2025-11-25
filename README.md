# 👟 Loja de Sapatos - Backend

Bem-vindo ao backend da Loja de Sapatos! Este guia irá te ajudar a instalar, configurar e rodar o projeto de forma simples e rápida.

---

## 🚀 Passo a Passo para rodar o projeto

### 1. Pré-requisitos
- [Node.js](https://nodejs.org/) instalado
- [npm](https://www.npmjs.com/) instalado

### 2. Instalação das dependências
Abra o terminal na pasta `backend` e execute:
```powershell
npm install
```

### 3. Configuração de variáveis de ambiente
Edite o arquivo `.env` na pasta `backend` conforme necessário. Exemplo:
```
PORT=3000
DB_URL=mongodb://localhost:27017/loja
```

### 4. Inicialização do servidor
Execute o comando abaixo na pasta `backend`:
```powershell
node server.js
```
Ou, se houver script no `package.json`:
```powershell
npm start
```

### 5. Acessar a aplicação
O servidor estará rodando na porta definida no `.env` ou no `server.js`.
Acesse: [http://localhost:3000](http://localhost:3000)

---

## 📁 Estrutura do Projeto
```
backend/
├── package.json
├── server.js
├── routes/
├── .env
```

---

## 💡 Dicas Úteis
- Instale novas dependências: `npm install <nome-do-pacote>`
- Pare o servidor: pressione `Ctrl + C` no terminal
- Para atualizar dependências: `npm update`
- Para verificar erros: consulte o terminal para mensagens de erro

---

## 📝 Sobre
Este projeto é um exemplo de backend para uma loja de sapatos, utilizando Node.js e Express. Sinta-se à vontade para contribuir ou adaptar conforme sua necessidade!

---

## 📞 Suporte
Em caso de dúvidas, procure o responsável pelo projeto ou abra uma issue.
