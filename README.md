# BookIdle — site

Página de apresentação do [BookIdle](https://github.com/PatrickKenji/BookIdle-releases), gerenciador de contas
para jogos idle, com ferramentas personalizadas por jogo (gratuito e de código aberto).

Site estático, sem build, em três idiomas: `index.html` (português), `en/index.html` (inglês) e `es/index.html` (espanhol), mais `fonts/` e `img/`. As três páginas têm a mesma estrutura: ao mudar uma, mude as outras duas, e mantenha os links `hreflang` e o seletor PT/EN/ES do topo. Para ver localmente:

```bash
python -m http.server 8765   # e abra http://localhost:8765
```

Na Vercel: importe este repositório como projeto **Other**, sem comando de build e com a raiz como diretório de saída.

A fonte Space Grotesk é licenciada sob a OFL; o texto da licença está em `fonts/`.
