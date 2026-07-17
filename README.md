# bltn-mockbiz

Coleção de mockups interativos da Bolten hospedados via GitHub Pages.

## Como publicar (passo a passo — upload manual)

### 1. Criar o repositório
1. Acesse https://github.com/new
2. **Repository name:** `bltn-mockbiz`
3. **Visibilidade:** `Public` (obrigatório para GitHub Pages no plano gratuito)
4. **NÃO marque** "Add a README" (já temos um)
5. Clique em **Create repository**

### 2. Fazer upload dos arquivos
1. Na página do repo recém-criado, clique em **"uploading an existing file"** (link no meio da tela)
2. Arraste **todos os arquivos** desta pasta (os 6 HTMLs + `index.html` + `README.md`) para a área de upload
3. Aguarde o upload terminar
4. No campo de commit message, escreva algo como `Initial upload dos mockups`
5. Clique em **Commit changes**

### 3. Ativar o GitHub Pages
1. No repo, vá em **Settings** (aba superior direita)
2. Na barra lateral, clique em **Pages**
3. Em **Source**, selecione: `Deploy from a branch`
4. Em **Branch**, selecione: `main` e pasta `/ (root)`
5. Clique em **Save**
6. Aguarde 1–2 minutos. A URL pública aparece no topo da mesma página:

```
https://<seu-usuario>.github.io/bltn-mockbiz/
```

### 4. Testar
Abra a URL. A landing page (`index.html`) lista todos os mockups. Cada card abre o protótipo correspondente.

---

## Adicionar novos mockups no futuro

1. Suba o novo arquivo HTML no repo (Add file → Upload files)
2. Edite o `index.html` e adicione um novo card no grid (copie o padrão dos existentes, mude ícone Lucide, título e `href`)
3. Commit. O Pages republica sozinho em ~1 min.

## Estrutura

```
bltn-mockbiz/
├── index.html                          landing page
├── inbox.html                          Inbox WhatsApp + Instagram
├── etiquetas.html                      Etiquetas de Contatos
├── whatsapp-envio-programado.html      Envio Programado
├── permissoes.html                     Permissões de Acesso
├── fale-com-parceiro.html              Fale com Parceiro + Links Úteis
├── calendario-agente-followup.html     Calendário + Agente Follow-up
└── README.md
```
