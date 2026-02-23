# Black Soluções — Novo Site

Proposta de redesign do site [blacksolucoes.com.br](https://blacksolucoes.com.br).

---

## 📥 Passo 1 — Baixar o projeto

1. Acesse: **https://github.com/alankardecm/blacksolucoes**
2. Clique no botão verde **`<> Code`**
3. Clique em **`Download ZIP`**
4. Salve o arquivo em qualquer pasta do seu computador
5. **Descompacte** o arquivo ZIP (clique com o botão direito → "Extrair aqui")

---

## 🖥️ Passo 2 — Testar na sua máquina

1. Abra a pasta descompactada (`blacksolucoes-main`)
2. **Dê duplo-clique no arquivo `index.html`**
3. O site abrirá no seu navegador (Chrome, Edge, Firefox...)
4. Navegue pelo site e verifique se está tudo certo
5. Anote tudo que deseja alterar (textos, cores, informações, etc.)

> 💡 **Dica:** Não precisa instalar nada. O site roda direto no navegador.

---

## 🚀 Passo 3 — Publicar na HostGator

### 3.1 — Acessar o cPanel

1. Entre no painel da HostGator: **https://financeiro.hostgator.com.br**
2. Vá em **Hospedagens** → clique em **cPanel**
3. Ou acesse diretamente: `https://blacksolucoes.com.br/cpanel`

### 3.2 — Fazer backup do site atual (segurança)

1. No cPanel, clique em **"Gerenciador de Arquivos"** (File Manager)
2. Abra a pasta **`public_html`**
3. Selecione todos os arquivos (Ctrl+A)
4. Clique em **"Compactar"** → salve como `backup_site_antigo.zip`
5. Pronto — seu backup está salvo caso precise voltar atrás

### 3.3 — Remover o site antigo

1. Ainda em `public_html`, selecione todos os arquivos **EXCETO** o `backup_site_antigo.zip`
2. Clique em **"Excluir"**

### 3.4 — Enviar os novos arquivos

1. Clique em **"Enviar"** (Upload) no topo do Gerenciador de Arquivos
2. Faça o upload do **ZIP** que você baixou do GitHub (`blacksolucoes-main.zip`)
3. Após o upload, clique com o botão direito no ZIP → **"Extrair"**
4. Os arquivos serão extraídos para uma pasta `blacksolucoes-main/`
5. **Entre nessa pasta** e **mova todos os arquivos** para `public_html`:
   - Selecione tudo → **"Mover"** → destino: `/public_html`
6. Delete a pasta vazia `blacksolucoes-main/` e o ZIP

### 3.5 — Verificar

1. Acesse **https://blacksolucoes.com.br** no navegador
2. O novo site deve estar no ar! 🎉

> ⚠️ **Se algo der errado:** Basta extrair o `backup_site_antigo.zip` de volta na `public_html` para restaurar o site anterior.

---

## 📂 Estrutura dos arquivos

```
├── index.html        ← Página principal
├── css/
│   └── style.css     ← Estilos e design
├── js/
│   └── main.js       ← Animações
└── img/
    ├── logo.png
    └── logo-white.png
```

## 💬 Feedback

Após testar, envie suas observações pelo WhatsApp ou e-mail:
- **WhatsApp:** (19) 3800-3300
- **E-mail:** contato@blacksolucoes.com.br

---

*Desenvolvido por Alan Moreira — 2026*
