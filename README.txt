COMO USAR (GitHub Pages + Jekyll)

1) Crie (ou confirme) estas pastas no seu repositório:
   - assets/img/
   - blog/

2) Envie estes arquivos (arrastando no GitHub ou via git):
   - index.html
   - blog/index.html
   - assets/img/banner.jpg
   - assets/img/banner.webp

3) Depois faça commit e aguarde o build do GitHub Pages.
   A página inicial vai mostrar a sua logo como banner no topo.

Observação:
- Se você estiver usando 'baseurl' diferente de "", mantenha o '_config.yml' atualizado.
- Os caminhos das imagens usam: {{ '/assets/img/banner.jpg' | relative_url }} (compatível com baseurl).
