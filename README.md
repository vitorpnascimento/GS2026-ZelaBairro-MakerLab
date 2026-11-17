# ZelaBairro - Módulo tátil para placa de rua

Global Solution 2026.2 (CitizenTech) - FIAP, Engenharia de Software 4ESPA
Disciplina: Project-Based Maker Lab - Profª Thais Aparecida Fernandes Kabuchi

Página do projeto: https://vitorpnascimento.github.io/GS2026-ZelaBairro-MakerLab/

Vídeo (1min36): https://youtu.be/QdJ4Rl47I1k

## O problema

A placa de nome de rua fica no alto (a que a gente mediu, na Al. Ribeirão Preto x R. Pamplona, tem 68 x 30 cm e está a 3,12 m do chão) e só tem informação visual. Quem é cego ou tem baixa visão não consegue saber em que rua está, e quando a placa está apagada ou torta não tem um jeito simples de avisar alguém.

## A proposta

Um módulo pequeno (170 x 95 mm) preso na mesma coluna da placa, na altura da mão (1,20 m), com:

- nome da rua em relevo (1 mm) e em braille logo abaixo
- seta em relevo indicando o sentido da numeração
- rebaixo de 40 x 40 mm para um adesivo de QR code que abre o registro de ocorrência no ZelaBairro
- borda e cantos arredondados
- atrás, duas bases para as abraçadeiras que prendem o módulo na coluna de 2 1/2" (63,5 mm), sem furar a coluna

A placa original continua no lugar. O módulo só acrescenta a informação tátil e o acesso ao ZelaBairro.

## Antes e depois

![Antes e depois](Imagens/antes_depois_onshape.png)

## Modelos (Onshape)

| Original | Redesign |
|---|---|
| ![Original](Imagens/onshape_original.jpg) | ![Redesign](Imagens/onshape_redesign_frente.jpg) |

Parte de trás do módulo (bases das abraçadeiras) e o módulo montado na coluna:

![Trás](Imagens/onshape_redesign_tras.jpg)

![Montado](Imagens/onshape_abracadeiras.jpg)

## Arquivos

- `CAD/Original/` - coluna com as placas (STEP e STL)
- `CAD/Redesign/` - módulo tátil (STEP e STL, pronto pra imprimir)
- `CAD/Abracadeira_MakerWorld/` - abraçadeira baixada e ajustada pra 63 mm (crédito abaixo)
- `Imagens/` - prints do Onshape e comparação

Impressão sugerida: PLA ou PETG, camada 0,2 mm, 3 paredes, 20% de preenchimento, face do texto pra cima, sem suporte.

## Peça baixada (crédito)

Abraçadeira usada na fixação: "BRACE PVC PIPE CLAMPS with hinge (DN50, 63mm, etc)", de Mihai B Mike, licença CC BY-NC-SA. Gerada no Parametric Model Maker com diâmetro interno de 63 mm e base de 30 mm, para a coluna de 63,5 mm. São duas por módulo, parafusadas nas bases de trás com parafusos M4. Mantida com a mesma licença (CC BY-NC-SA).
https://makerworld.com/models/1781504

## ODS

- ODS 11 - Cidades e Comunidades Sustentáveis
- ODS 10 - Redução das Desigualdades

## Integrantes

- Gabriel Leão da Silva - RM552642
- Matheus Farias - RM554254
- Miguel Mauricio Parrado Patarroyo - RM554007
- Pedro Chaves - RM553988
- Vitor Pinheiro Nascimento - RM553693
