# Prumo Finanças Pessoais

## Como instalar na hospedagem

### Método 1 - Upload via FTP/cPanel File Manager
1. Conecte-se ao seu FTP ou abra o File Manager no cPanel
2. Navegue até a pasta `public_html` (ou `www` / `htdocs`)
3. Faça upload de TODOS os arquivos desta pasta
4. Acesse seu domínio no navegador — pronto!

### Método 2 - cPanel File Manager
1. Faça upload do arquivo `prumo-financas.zip`
2. Extraia o ZIP dentro de `public_html`
3. Acesse seu domínio

## Estrutura dos arquivos
```
public_html/
├── index.html      ← Aplicativo principal (todos os recursos embutidos)
├── .htaccess       ← Configuração Apache (cache, segurança, compressão)
├── robots.txt      ← Para mecanismos de busca
└── README.md       ← Este arquivo (pode deletar)
```

## Observações importantes
- O arquivo `index.html` contém TODOS os recursos embutidos (CSS, JS, imagens)
- Não é necessário banco de dados — os dados ficam salvos no navegador do usuário (localStorage)
- Compatível com qualquer hospedagem que suporte HTML estático
- Requer conexão com internet para carregar:
  - Fonte Open Sans (Google Fonts)
  - Chart.js (gráficos)

## Hospedagens compatíveis
✅ Hostinger, HostGator, GoDaddy, Locaweb, Umbler
✅ GitHub Pages (gratuito)
✅ Netlify (gratuito) — arraste a pasta e pronto!
✅ Vercel (gratuito)
✅ Amazon S3, Google Cloud Storage

## Configuração para HTTPS
Ative o SSL/TLS gratuito (Let's Encrypt) no painel da sua hospedagem.
A API de IA requer HTTPS para funcionar corretamente.

---
Desenvolvido por Del Rei Design © 2026
