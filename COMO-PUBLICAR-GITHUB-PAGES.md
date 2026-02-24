# Como colocar no GitHub Pages — Passo a passo

## 1. Criar conta no GitHub (se não tiver)
Acesse https://github.com e crie uma conta gratuita.

## 2. Criar o repositório
1. Clique em **"New repository"** (botão verde no canto superior direito)
2. Dê o nome: `credito` (ou qualquer nome que quiser)
3. Marque **"Public"** (obrigatório para GitHub Pages gratuito)
4. Clique em **"Create repository"**

## 3. Fazer upload dos arquivos
1. Na página do repositório recém criado, clique em **"uploading an existing file"**
2. Extraia o ZIP `credito-ghpages.zip` que você baixou
3. Arraste os dois arquivos (`index.html` e `README.md`) para a área de upload
4. Clique em **"Commit changes"**

## 4. Ativar o GitHub Pages
1. Vá em **Settings** (aba no topo do repositório)
2. No menu lateral esquerdo, clique em **"Pages"**
3. Em **"Branch"**, selecione `main` e pasta `/ (root)`
4. Clique em **"Save"**

## 5. Acessar seu app
Após ~1 minuto, seu app estará disponível em:
```
https://SEU-USUARIO.github.io/credito/
```
(substituindo SEU-USUARIO pelo seu nome de usuário do GitHub)

Salve esse link nos favoritos do Chrome — é seu acesso diário.

---

## Como atualizar quando eu enviar melhorias

1. Baixe o novo `inteligencia-credito.html` que eu entregar aqui
2. Acesse seu repositório no GitHub
3. Clique no arquivo `index.html` → clique no ícone de lápis (editar)
4. Clique em **"..."** → **"Upload file"** → substitua pelo novo arquivo
5. Clique em **"Commit changes"**
6. Em ~1 minuto o site já está atualizado com a versão nova

---

## Segurança
- Seu repositório é público, mas **a chave de API fica salva só no seu navegador** (localStorage)
- Nenhuma informação sensível está no código
- Cada dispositivo precisa configurar a chave separadamente na primeira abertura
