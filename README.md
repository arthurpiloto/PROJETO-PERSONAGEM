# Projeto Personagem

## TAGs semânticas
* HEADER (Cabeçalho)
* MAIN (Conteúdo principal)
* FOOTER (Rodapé)

## TAGs genéricas (sem significado semãntico)
* DIV (Usado para "conter" qualquer item, funciona como os cômodos de uma casa)
* SPAN (usado para escrever textos simples e pequenos)

## Seletores
*   "*"   --> Universal
* header  --> Nome da tag
* .itens  --> Nome da classe
* #titulo --> Nome do ID (MUITO ESPECÍFICO, USADO POR APENAS UM ELEMENTO)

* https://flukeout.github.io/

* A + B --> seleciona todos os elementos "B" que seguem diretamente "A"
* A ~ B --> seleciona todos os irmãos "B" que seguem o "A"
* A > B --> seleciona todos os elementos "B" que são filhos de "A"
* :first-child --> seleciona o primeiro elemento filho
* :oly-child --> seleciona qualquer elemento que seja o único dentro de outro, ou seja, qualquer elemento que tenha apenas um filho
* :last-child --> seleciona o último elemento filho dentro de outro elemento
* :nth-child(A) --> seleciona o elemento de acordo com a ordem(A) que está dentro de outro elemento
* :nth-last-child(A) --> seleciona o filho de trás para frente de acordo com o elemento pai

## Display flex (flex-box)

* https://flexboxfroggy.com/

* Column (coluna)
* Row (linha)
* Dependem da direção que estão, column ou row
    * justify-content (eixo principal)
    * align-items (eixo secundário)

## TAG a
* Atributos
    * href="#" (link sem destino)
    * target= "_blank" (abre em nova guia)