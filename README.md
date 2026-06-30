# Flecha Arcana

Projeto de jogo 2D feito no Construct 3 para uma game jam. O jogo coloca um arqueiro em uma luta contra um boss mago muito mais poderoso, com foco em sobrevivencia, leitura de padroes e uma virada temporaria de poder.

## Sobre o jogo

Em Flecha Arcana, o jogador controla um arqueiro em uma arena de floresta sombria. O inimigo principal e um mago gigante que dispara bolas de fogo roxas em diferentes alturas e causa muito dano em contato direto.

No inicio da batalha, o boss domina o combate. A flecha normal do jogador causa pouco dano, entao o objetivo principal e sobreviver, observar os ataques e acertar o ponto fraco no topo do cajado do boss.

Quando o ponto fraco e atingido, o jogador rouba temporariamente parte do poder do boss e passa a disparar uma flecha mais forte, a FlechaOP. Durante esse curto periodo, o jogador consegue causar muito mais dano e deve aproveitar a janela antes que o poder acabe.

## Como jogar

Abra o arquivo principal no Construct 3:

```text
projects/JogoOP.c3p
```

Depois clique no botao de play do Construct para testar o jogo.

### Controles

| Acao | Tecla |
| --- | --- |
| Mover para a esquerda | Seta esquerda |
| Mover para a direita | Seta direita |
| Pular | Controle de plataforma padrao do Construct |
| Atirar | Barra de espaco |

## Objetivo

Derrote o boss antes de perder toda a vida.

Para vencer, o jogador precisa alternar entre dois momentos:

1. Sobreviver aos ataques do boss.
2. Acertar o ponto fraco no cajado para liberar a FlechaOP.

## Mecanicas principais

- Boss com muita vida e ataques de longa distancia.
- Bolas de fogo roxas disparadas em diferentes alturas.
- Dano corpo a corpo quando o jogador encosta no boss.
- Barra de vida do player acima da cabeca.
- Barra de vida do boss na tela.
- Ponto fraco no cajado do boss.
- Roubo temporario de poder ao acertar o ponto fraco.
- FlechaOP com dano maior durante a transformacao.
- Animacoes de ataque, dano e morte para player e boss.

## Estrutura do repositorio

```text
.
├── README.md
├── assets/
│   ├── flechaoverpowered.png
│   └── source-packs/
│       ├── GandalfHardcore Archer.zip
│       └── GreenForest.rar
└── projects/
    ├── JogoOP.c3p
    └── prototypes/
        ├── jamconstruct.c3p
        └── teste2.c3p
```

## Arquivos principais

- `projects/JogoOP.c3p`: versao principal e mais completa do jogo.
- `projects/prototypes/jamconstruct.c3p`: prototipo inicial do projeto.
- `projects/prototypes/teste2.c3p`: versao intermediaria usada durante testes.
- `assets/flechaoverpowered.png`: arte da flecha poderosa.
- `assets/source-packs/`: pacotes de recursos usados como base visual.

## Versao do Construct

O projeto foi salvo no Construct 3 release `r487.3`.

Caso o Construct mostre erro ao abrir, atualize o Construct 3 para uma versao igual ou mais recente.

## Estado atual do jogo

O jogo ja possui uma batalha funcional entre player e boss. Ainda ha espaco para evoluir a experiencia com:

- tela inicial;
- tela de vitoria e derrota;
- efeitos sonoros;
- musica de fundo;
- indicadores visuais para quando o poder roubado esta ativo;
- ajuste fino no intervalo dos disparos;
- mais padroes de ataque do boss;
- polimento nas animacoes e feedbacks de dano.

## Equipe

Projeto desenvolvido para game jam usando Construct 3.
