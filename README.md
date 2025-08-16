# Gerador de Notas Promissórias (PWA)

Este é um **aplicativo web progressivo (PWA)** para gerar notas promissórias em PDF, que funciona em **Android, iOS e Desktop**.  
Ele pode ser instalado como um app na tela inicial do celular.

---

## 🚀 Como usar
1. Acesse o app pelo link do GitHub Pages (quando publicado).  
   👉 `https://SEU-USUARIO.github.io/nota-promissoria-pwa/`  

2. Preencha os dados do emitente, beneficiário, valores e datas.  
3. Clique em **Gerar Nota**.  
4. O PDF será baixado automaticamente.

---

## 📲 Instalação no Celular

### Android (Chrome)
1. Abra o link no navegador **Chrome**.  
2. Clique no menu (⋮) → **Adicionar à tela inicial**.  
3. O app ficará instalado como um ícone.

### iOS (Safari)
1. Abra o link no **Safari**.  
2. Toque no botão **Compartilhar** (quadrado com seta para cima).  
3. Escolha **Adicionar à Tela de Início**.  
4. O app ficará instalado como um ícone.

---

## ⚙️ Estrutura do projeto
- `index.html` → Página principal  
- `manifest.json` → Configuração do PWA  
- `service-worker.js` → Cache offline  
- `icon-192.png` → Ícone para Android/iOS  
- `icon-512.png` → Ícone maior para instalação  

---

## 📌 Observações
- Funciona somente em **HTTPS** (ou localhost).  
- Para rodar offline, o navegador precisa abrir o app pelo menos **uma vez conectado**.  
- Os ícones fornecidos são **placeholders** → substitua por imagens reais para um visual melhor.

---

✍️ Criado para facilitar a geração de **Notas Promissórias** em qualquer dispositivo.
