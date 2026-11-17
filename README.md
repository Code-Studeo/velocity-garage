# VELOCITY GARAGE

Site institucional para estética e personalização automotiva.

**Performance é atitude.** Paleta: preto, vermelho racing e prata.  
O formulário apresenta uma prévia local do pedido. Ele não envia ou armazena dados.

## Tecnologia
HTML, CSS e JavaScript nativos mantêm o site leve e simples para publicação estática.  
IntersectionObserver e APIs do navegador cuidam das animações e interações, sem dependências de runtime.

## Execução local
Abra `index.html` ou rode `python -m http.server 8000` e acesse `http://localhost:8000`. Sem instalação ou build.

## Recursos
Menu mobile acessível, foco visível, revelações no scroll, parallax sutil, redução de movimento, seletor de serviços, comparador antes/depois, galeria, FAQ e orçamento simulado.

## Imagens finais
Quatro imagens finais são usadas em `public/images/`: `ambiente.jpg` (hero, manifesto e contato), `destaque-01.jpg` (galeria e comparador), `destaque-02.jpg` (galeria) e `detalhe.jpg` (galeria/PPF). A quinta, `hero.png`, foi fornecida, mas ficou fora da página porque exibe emblemas de marcas automotivas de terceiros, em conflito com a direção do projeto. As miniaturas antigas de moodboard não são usadas. Os JPEGs otimizados evitam dependências de imagem externas.

## Estrutura
- `index.html` conteúdo semântico e metadados; `styles.css` tokens, composição e responsividade.
- `script.js` interações; `favicon.svg` ícone local; `public/images/` imagens finais.
- `imagens-referencia/` originais preservadas, não usadas visualmente.

## Publicar na Vercel
Envie a pasta ao GitHub, importe na Vercel, selecione **Other** como site estático e publique sem comando de build. Associe o domínio nas configurações.

Rodapé: crédito de portfólio editável em `[NOME DO ESTÚDIO]`.
