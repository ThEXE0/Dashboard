# MeuNegócio

Gestão de fornecedores e produtos para vendedores do Mercado Livre e da Shopee: cadastro, simulador de margem, compras e relatórios.

App de um único arquivo (`index.html`), sem build e sem dependências para instalar. Os dados ficam salvos no navegador (localStorage); use **Configurações > Exportar backup** para guardar uma cópia.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub e envie `index.html` e `README.md` para a raiz.
2. Vá em **Settings > Pages**.
3. Em **Source**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
4. Salve e aguarde um minuto. O site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Observações

- Os ícones vêm da biblioteca Lucide, carregada pela CDN do cdnjs, então é preciso ter internet.
- Os dados ficam só no navegador de cada pessoa, sem sincronização entre aparelhos. Para isso seria preciso um banco de dados, como o Supabase.
- Revise as comissões e tarifas em Configurações, pois variam por categoria e preço.
