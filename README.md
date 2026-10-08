# PortFlow

Estudo de front-end que reproduz um layout de agencia criativa com HTML e CSS. A pagina apresenta uma abertura visual, galeria de trabalhos e rodape com icones de redes sociais.

O layout de referencia foi produzido pelo **Vai Na Web para fins educacionais**, conforme o credito preservado no rodape. Este repositorio apresenta a implementacao do estudo, sem reivindicar autoria do design de referencia.

## O Que Existe No Projeto

- Cabecalho com marca e itens de navegacao visual.
- Banner com imagem de fundo e chamada de contato.
- Galeria com 12 imagens armazenadas no repositorio.
- Rodape com icones de redes sociais.
- Regras de CSS para uma versao de tela estreita, atualmente ate 376 pixels.
- Link de retorno ao topo no layout mobile.

## Tecnologias

HTML5, CSS3, Flexbox e media queries. A fonte Montserrat e carregada pelo Google Fonts. Nao ha framework, JavaScript, backend ou etapa de build.

## Como Executar

```bash
git clone https://github.com/GabrielYuri1127/Portflow.git
cd Portflow
```

Abra `index.html` no navegador. Se preferir servir por HTTP e tiver Python 3 instalado:

```bash
python -m http.server 8080 --bind 127.0.0.1
```

Depois abra `http://localhost:8080/`. As imagens ficam em `img/`; a fonte externa precisa de internet para carregar, com fallback para fonte sans-serif.

## Organizacao

```text
index.html       Estrutura da pagina e referencias das imagens
style.css        Estilos, Flexbox e regras para telas estreitas
img/             Marca, banner, galeria e icones
```

## Escopo E Pontos De Evolucao

E uma pagina estatica de estudo. Os itens do menu, icones sociais e chamada de contato nao implementam navegacao completa ou envio de mensagens. O icone mobile nao abre um menu interativo.

Os proximos passos naturais sao ampliar os breakpoints, revisar acessibilidade e textos alternativos, e conectar os elementos visuais aos destinos de navegacao. Esses recursos nao devem ser apresentados como funcionalidades ja entregues.
