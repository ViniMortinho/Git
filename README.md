[![Typing SVG](https://readme-typing-svg.demolab.com?font=arial&size=23&pause=1000&center=falso&vCenter=falso&repeat=verdadeiro&width=435&lines=Versionamento+com+GIT)](https://git.io/typing-svg)
##
O Git é um sistema que permite gerenciar as diferentes versões de um projeto de software, armazenando o histórico completo das alterações em repositórios locais. Com o Git, é possível criar, modificar e sincronizar o código com outros desenvolvedores, usando comandos para adicionar, confirmar, mesclar e enviar as alterações. O Git também oferece vantagens de desempenho, segurança e flexibilidade em relação a outros sistemas de controle de versão. O Git foi criado em 2005 pelo mesmo criador do kernel do Linux e é usado por muitos projetos de software comerciais e de código aberto.

Link para download
https://git-scm.com/downloads
##
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Roboto&size=24&pause=1000&center=falso&vCenter=falso&repeat=verdadeiro&width=450&lines=git+commit+--amend)](https://git.io/typing-svg)

Alterar o último commit:
Sintax
git commit --amend

`git commit --amend` é uma mão na roda pra mudar o último commit que você fez. Ele deixa você juntar as mudanças que você preparou com o commit anterior em vez de fazer um commit novo. Ele também serve pra mudar a mensagem do último commit sem mexer no resto.

Tem uns exemplos de como usar o `git commit --amend` aqui:

- Pra mudar a mensagem do último commit, é só rodar `git commit --amend` sem preparar nada. Aí vai abrir um editor pra você escrever a mensagem nova e salvar.
- Pra botar mais mudanças no último commit, é só preparar os arquivos que você quer incluir e depois rodar `git commit --amend --no-edit`. Aí vai fazer um commit novo com a mesma mensagem do anterior, mas com as mudanças a mais.
- Pra mudar a mensagem e os arquivos do último commit, é só preparar os arquivos que você quer incluir e depois rodar `git commit --amend -m "uma mensagem nova de commit"`. Aí vai fazer um commit novo com uma mensagem diferente e as mudanças a mais.

Só que tem um detalhe: o `git commit --amend` não muda o último commit, ele troca ele inteiro, quer dizer que o commit emendado vai ser uma coisa nova com uma referência própria. Pro Git, vai parecer um commit novo. Isso pode dar problema se você já mandou o commit original pra um lugar remoto ou se outros desenvolvedores usaram ele como base. Nesse caso, é melhor não usar o `git amend` e usar outros jeitos de reescrever o histórico.

