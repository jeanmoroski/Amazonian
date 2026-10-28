# Amazonian

Cúpula de luminária impressa em 3D, com parede única e padrão de nós em nervuras helicoidais, gerada por algoritmo no Grasshopper, sem fatiador. Projeto de TCC em Design de Produto da Universidade Federal do Paraná (UFPR), 2026.

> Um meio vivo, sensorial e abundante. É como a copa de uma árvore em uma floresta tropical: a trama filtra a luz como as folhas filtram o sol.

## O que tem aqui

| Arquivo | O que é |
|---|---|
| `amazonian_fase_2_mesa22x22x22cm_PLA_160g.gcode` | G-code pronto da cúpula, para impressoras com mesa de pelo menos 22 × 22 × 22 cm |
| `README.md` | Este arquivo |
| `LICENSE.md` | Licença de uso |

Em breve: o gerador de G-code (`.ghx`), a superfície de entrada (`.3dm`), a prancha técnica (`.pdf`) e o relatório do TCC.

## A peça

- **Dimensões:** cerca de 172 × 175,5 mm em planta e 130 mm de altura
- **Abertura para o LED:** encaixe de pressão para o LED kit 001
- **Parede:** única, com cerca de 0,85 mm, em camadas de 0,5 mm
- **Material:** PLA de 1,75 mm, de preferência branco ou natural
- **Impressão:** cerca de 3 h 15 min

## Para imprimir

1. **Impressora:** mesa de pelo menos 22 × 22 × 22 cm, bico de **0,8 mm**. Testado numa Creality Hi.
2. **Firmware:** o cabeçalho do G-code é o da Creality (Klipper). Em outras marcas, troque o cabeçalho e o rodapé pelos da sua impressora.
3. **Temperatura:** vem fixa no cabeçalho do arquivo.
4. Limpe a mesa e confira o nivelamento: a primeira camada é a parte mais sensível.
5. Envie o arquivo, acompanhe a primeira camada e os primeiros nós, e espere a mesa esfriar antes de tirar a peça.

**Se algo der errado**

- **A parede descola:** a forma pode estar se deslocando mais de meia linha por volta. Reduza a amplitude ou a torção no gerador.
- **O bico afunda nos nós:** diminua o PAUSE ou aumente o multiplicador vertical (regra que funcionou: PAUSE 1,7 e multiplicador vertical 3,0).
- **A base sai com excesso de material:** confira se o multiplicador de fluxo da base está em 0,68.

## Para montar

Você precisa da cúpula impressa e de um **LED kit 001** (padrão das luminárias da Bambu Lab), ou outro módulo compatível: LED de 60 mm de diâmetro, alimentação USB de 5 V e cabo com interruptor. Prefira a versão de luz quente.

1. Encaixe o módulo LED na abertura da cúpula, pressionando com as mãos. O encaixe é justo e não precisa de cola nem ferramentas.
2. Ligue o cabo USB num carregador de celular, numa porta de computador ou num power bank.
3. Acenda pelo interruptor do cabo.

## Cuidados

- Use só fonte de luz LED de baixa potência, como a do kit. Lâmpadas incandescentes e halógenas esquentam demais e deformam o PLA, que amolece por volta de 55 a 60 °C.
- Use em ambiente interno, longe de sol direto e de fontes de calor.
- O kit não é indicado para iluminação fixa de teto ou parede: use o Amazonian como luminária de mesa.
- Para limpar, tire o pó com um pincel macio ou pano seco, sem álcool nem solventes.
- Se a cúpula amarelar, deformar ou quebrar, imprima uma nova e reaproveite o kit LED.

## Créditos

- **Autoria:** Jean Moroski, com orientação do Prof. Gabriel Rosenmann (UFPR)
- **Gerador de G-code:** adaptado e simplificado a partir do gerador do [Estúdio Lasso Design](https://www.patreon.com/cw/lassodesign/home), feito com o plugin [Silkworm](https://www.food4rhino.com/en/app/silkworm)
- **Primeiros geradores:** com base nas aulas de Raphael Bastos (R3Lab) e no livro *Advanced 3D Printing with Grasshopper: Clay and FDM*, de Diego García Cuevas e Gianluca Pugliese
- **Software:** Rhinoceros 8 e Grasshopper (Robert McNeel & Associates)

## Licença

[Creative Commons Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.pt-br). Você pode imprimir, adaptar e compartilhar, desde que dê os créditos, não venda e compartilhe as adaptações com a mesma licença. Veja o `LICENSE.md`.
