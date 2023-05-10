# Markdown Links

## Índice

* [1. Projeto MdLinks](#1-projeto-mdlinks)
* [2. Backlog](#2-backlog)
* [3. Utilização](#3-utilizacao)

***

## 1. Projeto MdLinks

Ferramenta de linha de comando (CLI) com a sua própria biblioteca (library) em JavaScript, 
desenvolvida em [Markdown](https://pt.wikipedia.org/wiki/Markdown), no qual é uma linguagem 
de marcação muito popular entre os programadores. É usada em muitas plataformas que
manipulam texto (GitHub, fórum, blogs e etc) e é muito comum encontrar arquivos
com este formato em qualquer repositório (começando pelo tradicional `README.md`).
Os arquivos `Markdown` normalmente contém _links_ que podem estar
quebrados, ou que já não são válidos, prejudicando muito o valor da
informação que está ali, o MdLinks é uma solução para automatizar a 
verificação desses _links_ .

## 2. Backlog

Para densenvolver o projeto, foi criado um fluxograma para planejar e compreender o processo 
de implementação de todas as partes do projeto.

![fluxograma](https://github.com/talitamsx/SAP009-md-links/assets/107422798/4421ec4e-6b81-42e0-be35-6259c3f57785)

## 3. Utlização

Comando :
md-links ./"rota-do.arquivo"/"arquivo.md" (absoluta ou relativa)
![md-links](https://github.com/talitamsx/SAP009-md-links/assets/107422798/9f17114a-491a-409f-a420-f45b1bf4d1d2)


Comando: 
md-links ./"rota-do.arquivo"/"arquivo.md" --validate
![md-links-validate](https://github.com/talitamsx/SAP009-md-links/assets/107422798/a2ad6b35-74c6-4ff6-b068-d28fd59d7f94)

Comando:
md-links ./"rota-do.arquivo"/"arquivo.md" --stats
![md-links-stats](https://github.com/talitamsx/SAP009-md-links/assets/107422798/82406918-8440-4ffe-a5a0-5ed38bba4804)

Comando:
md-links ./"rota-do.arquivo"/"arquivo.md" --stats --validate
![md-links-stats-validate](https://github.com/talitamsx/SAP009-md-links/assets/107422798/dc15008e-d327-455f-9e10-4920a8472dda)
