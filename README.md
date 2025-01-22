# Tailwind CSS

## O que é?

- Tailwind CSS é basicamente um utility-first CSS framework que prioriza a construção ultra-rápida de interfaces customizadas.

- É uma estrutura CSS de baixo nível altamente personalizável que fornecce todos os blocos de construção de que você precissa para criar designs sob medida, sem nenhum estilo opinativo irritante que você precise lutar para ignorar.

#### Design responsivo

- Cada classe no Tailwind pode seer aplicada condicionalmente em diferentes breakpoints, o que torna muito fácil construir interfaces responsivass complexas sem nunca deixar seu html.

ex:

md:w-32

md: medium, prefixo para identificar responsividade;
w: width;
32: valor do width.

#### Estados (hover, focus...)

- Semelhante ao modo como o Tailwind lida com o design responsivo, estilizar elementos com hover, focus, etc. podem ser realizadoss prefixando com a variedade de estado apropriada.

ex:

hover:text-gray-300
focus:ring-2

#### Dark Mode

- Dark mode é um recurso de muitos sistemas operacionais e está se tornando cada vez mais comum projetar uma versão escura de seu sistema para acompanhar o designpadrão do sistema.

ex:

dark:bg-gray-800

#### Classes customizadas

- Com o tailwind é possivel customizar classes adicionando seus próprios utilitário adicionando ao seu CSS.

ex:

```CSS
@tailwind base;
@tailwind components;
@tailwind utilities;


@layer utilities{
    .scroll-snap-none{
        scroll-snap-type: none;
    }

    .scroll-snap-x{
        scroll-snap-type: x;
    }
    .scroll-snap-y{
        scroll-snap-type: y;
    }

    
}

```
--- 

## Fontes e Cores

