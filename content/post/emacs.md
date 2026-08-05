---
author: "G. Caelestis"
date: 2026-08-05
title: Sobre o Emacs

lastmod: 2026-07-03
banner: images/emacs1.png
cover: images/emacs1.png
summary: Explicação sobre o editor que uso sempre e amo.

tags: [programação, editor, emacs, diário]
featured_image: "images/emacs1.png"
description: "Descrição sobre meu editor preferido"
---

## Apresentação
O Emacs é um editor de texto, falando de uma forma resumida. Mas, no final das contas, ele é uma agenda, um caderno, uma IDE complexa, um gerenciador de Git, um provedor de e-mail, entre outros. O maior diferencial do Emacs é simplesmente ser um editor capaz de ser extremamente flexível.

O Emacs abriga funções diversas que eu levaria muito tempo para detalhar cada uma, ou apresentar só as mais relevantes. É um editor que apresenta recursos como a capacidade de organizar e escrever notas em Org-mode, tem uma agenda flexível e customizável, a capacidade de gerenciar projetos GIT, personalizar rotinas e entre outros. O Emacs é feito em Lisp e possui uma linguagem própria chamada de Emacs-Lisp (ELisp), onde é possível personalizar o editor inteiro, assim como construir add-ons, rotinas, funções e até integrações! O editor é Software Livre e parte do ecossistema GNU, sendo um editor extremamente antigo e muito utilizado na academia de áreas como escritores e pesquisadores de história - por sua capacidade robusta para escrita, anotação, gerenciamento de notas e entre outros.

É difícil classificar o Emacs hoje em dia, porque ele pode fazer realmente tudo: tem provedores de e-mail, uma agenda em Org-Mode capaz de criar até um sistema de rotinas pontuando os dias concluídos, clientes de mensagens como IRC, navegadores sem JS e até uma integração para as teclas do VIM! Além de rodar diversos recursos voltados para programadores, como Flycheck e LSP, gerenciar projetos e workflows, dividir buffers múltiplos e utilizar recursos de terminal.

## Meus motivos
Meu maior motivo de utilizar o Emacs foi primeiramente curiosidade! Como usuário do VIM clássico, já havia o costume de gostar de editores flexíveis assim, então, quando soube que uma das suas "frameworks" (uma configuração já montada como LunarVIM ou SpaceVIM), precisei testar.

O Emacs trouxe recursos que são extremamente úteis na minha rotina, veja só, você pode organizar notas inteiras e referenciá-las utilizando o modelo Org-Mode e pesquisá-las rapidamente por tags - além de criar categorias e templates para elas. E isso ainda vai mais fundo! Utilizando um recurso nativo chamado Babel, você consegue criar um arquivo Org-Mode onde você pode escrever algoritmos e executá-los por baixo dos panos diretamente na nota; e o resultado pode ser exibido dentro da sua anotação ou interagir com outros algoritmos da anotação! E indo mais além, isso é utilizado por mim e diversos usuários do Emacs para criar um arquivo documentado de configurações do sistema operacional e do próprio Emacs, exportando todas as alterações para seus devidos arquivos e diretórios diretamente de um único arquivo! 

Isso que nem falei que isso tudo é um sistema ainda maior, já que o Emacs pode exportar Org-Mode para LaTeX, PDF, HTML e ainda nem falei da calculadora própria, agenda Org e os milhares de automatizações que elas permitem. Emacs é um ecossistema inteiro dentro de um editor, que te permite maximizar a eficiência de diversos softwares dentro de um único, sem perder seu ambiente de trabalho. Isso me trouxe um ambiente onde posso estudar, programar, criar configurações documentadas, conversar no IRC e exportar meus trabalhos para o Forgejo/Github; tudo ao mesmo tempo e na mesma janela.

E claro, tudo isso com uma documentação dos recursos, da linguagem, do editor e dos addo-ons diretamente integrados no próprio editor de forma offline. Podendo pesquisar variáveis, teclas, funções, add-ons e até syntax do Elisp no editor.
### Emacs VS Vim
Como já ficou claro, o Emacs é muito superior ao Vim quando o assunto é flexibilidade e ecossistema; e, sendo sincero, muitos recursos como SpaceVIM surgem justamente pelo Emacs (Spacemacs) e até o Neorg para utilizar o Org-Mode no Neovim. 

É indiscutível que o Emacs é mais flexível; porém, ele perde em muito para a questão de desempenho, portabilidade e flexibilidade na questão de ambientes. Emacs é um editor pesado em armazenamento por conta de suas funções, nem tanto em RAM - mas ainda utiliza muito mais do que um editor como o VIM com plugins. O desempenho não é algo muito abaixo do VIM, mas o VIM é realmente mais rápido em otimização e desempenho dentro de qualquer máquina limitada ou controlada; e, por fim, a portabilidade do Emacs, sendo GNU, é mais focada ao ambiente Linux/Unix, tendo suas versões mobile e Windows, só que não possuindo muitas vezes a mesma eficiência - além de sua versão CLI não ser muito boa comparada ao VIM ou sua versão gráfica. 

## Minha configuração
A minha configuração é simples e utiliza integração das teclas e comandos do VIM dentro do Emacs, focada mais em programação e anotação de conteúdos. Há muitas partes que copiei da documentação ou de meu amigo que é um usuário mais experiente.

Como ainda estou aprendendo ELisp e a configurar o Emacs (a curva de aprendizado é enorme), pode conter algumas coisas bem discutíveis nela. Mas fiz minha configuração e moldei pensando em ser portátil para iniciantes e ser utilizada como experimento por outras pessoas, apesar de elas também terem como opção utilizar o DoomEmacs como opção já feita pensando em não necessitar de configurações extensas. Minha configuração pode ser acessada diretamente pelo GitHub, com o DoomEmacs.  

- [Minha Configuração](https://github.com/rahvax/emacs)
- [DoomEmacs](https://github.com/doomemacs/core)

## Meu primeiro projeto
Meu primeiro projeto em Emacs foi uma necessidade de ser preguiçoso, como o nome sugere; para criar diretórios já definidos para projetos em C. Assim, economizei o tempo de sempre criar tudo e me dei a experiência de criar um projeto em Elisp ao invés de só utilizar modelos do Projectile.  

- [SlackC.el](https://github.com/rahvax/Slack-C.el)

## Conclusão
É difícil falar sobre o Emacs por sua complexidade, mas fico feliz em apresentar um editor tão importante para mim hoje em dia - que é muito desconhecido na grande bolha geral da tecnologia - e estar dando os primeiros passos para começar a fazer parte da comunidade desse editor.

Vale muito o teste e a pesquisa mais a fundo sobre esse editor e perceber o quanto ele é realmente completo. Claro, para alguém sem tempo ou com a paciência curta, pode preferir uma IDE, Obsidian ou até o VIM - mas para quem quiser testar, fico feliz se eu conseguir ser a sua porta de entrada para esse mundo.