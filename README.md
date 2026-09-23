# Curso de Lógica — Material de Apoio

Material complementar de lógica e técnicas de demonstração para os primeiros anos da graduação em
Economia da Escola de Economia de São Paulo. Pensado para ser feito antes de Cálculo.

**Site publicado:** _(preencher com o endereço do GitHub Pages depois de ativar)_

## O que tem aqui

| Arquivo | O que é |
|---|---|
| `index.html` | Página inicial, com os dois módulos e a bibliografia |
| `modulo1.html` | Módulo 1 — Lógica e Linguagem Matemática (7 aulas) |
| `modulo2.html` | Módulo 2 — Técnicas de Demonstração (5 aulas) |
| `slides/` | Slides de cada aula, em PDF e em PowerPoint |

Cada módulo é um arquivo único e autocontido: o conteúdo, os exercícios interativos, o glossário de
símbolos e o controle de progresso estão todos dentro do próprio HTML. Não há dependência de servidor,
de banco de dados nem de processo de build — basta abrir o arquivo.

A única coisa carregada de fora são as fontes (Google Fonts) e os vídeos (YouTube).

## Os vídeos

Os vídeos **não ficam neste repositório**. Ficam no YouTube, como não listados, e são embutidos nas
páginas pelo domínio `youtube-nocookie.com`.

O motivo é prático: o Git guarda todas as versões de todo arquivo para sempre, então um vídeo
regravado nunca deixa de ocupar espaço. Doze aulas dariam algo perto de 400 MB, e o GitHub recomenda
manter repositórios abaixo de 1 GB.

Para publicar uma aula nova, troque o espaço reservado pelo player no HTML do módulo correspondente.

## Publicar as alterações

O site é servido pelo GitHub Pages a partir da branch principal, na raiz do repositório. Qualquer
alteração enviada aparece publicada em um ou dois minutos.

O arquivo `.nojekyll` existe para que o GitHub Pages sirva os arquivos exatamente como estão, sem
passar pelo processador de sites estáticos.

## Créditos

Material construído com o uso de inteligência artificial e submetido a supervisão e validação de
professores da Escola de Economia de São Paulo.

- **Organização pedagógica:** Prof. Raone Costa
- **Execução:** Profa. Gabriela Fonseca e Prof. Caio Castro
- **Colaborações:** Profa. Katia Nishiyama, Prof. Roberto Sarkisian, Prof. Pedro Ogeda e Profa. Verônica Orellano

## Bibliografia

- *forallx: An Introduction to Formal Logic*, P. D. Magnus — acesso livre
- *Book of Proof* (3ª ed.), Richard Hammack — acesso livre
- Slides de aula do Prof. Ricardo Masini
