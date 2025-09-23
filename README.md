
# Divide & Brilha — Jogo de Divisão com Vírgula

Bem-vindo à documentação oficial do **Divide & Brilha**, o jogo web para aprender divisão de números decimais de forma divertida e gamificada!

---

## Objetivo do Jogo

Ensinar crianças a resolver divisões envolvendo números com vírgula (decimais), mostrando passo a passo **como eliminar a vírgula** e calcular o resultado inteiro.

---

## Como Jogar

1. **Clique em "Começar a jogar"** na tela de boas-vindas.
2. O jogo apresenta uma **divisão de números decimais**, ex: `5,5 ÷ 2,5`.
3. **Digite o resultado inteiro** (sem vírgula!) no campo de resposta e clique em "Responder".
4. Se acertar, ganha pontos e avança para novos desafios. Se errar ou o tempo acabar, perde um coração (vida).
5. A cada 3 acertos, **sobe de nível**: fica mais difícil, com números maiores, mais casas decimais e menos tempo!
6. Se perder todos os corações, aparece o modal de "Game Over" mostrando sua pontuação e nível.

---

## Regras Gerais

- **Dividendo sempre maior que o divisor**.
- A resposta **sempre é um número inteiro**.
- Você tem **3 corações (vidas)**. Errou ou o tempo acabou, perde 1.
- O tempo para responder **varia conforme o nível** (quanto mais alto, menos tempo).
- Não há botão de pulo: cada questão conta!
- Pontuação: cada acerto vale 10 pontos + bônus pela sequência de acertos.
- A cada 3 acertos, **sobe de nível** automaticamente.

---

## Dificuldade & Níveis

| Nível | Características                      |
|-------|--------------------------------------|
| 1     | Números pequenos, 1 casa decimal     |
| 2-4   | Números médios, até 2 casas decimais |
| 5-9   | Decimais de até 2 casas, tempo menor |
| 10+   | Decimais de até 3-4 casas, números grandes, tempo menor |

- O nível atual é exibido no topo e nas dicas da questão.
- O jogo ajusta a dificuldade automaticamente, sem precisar escolher.

---

## Tempo

- Cada rodada possui **um limite de tempo** (barra + contador em segundos).
- Se o tempo acabar antes de responder, perde 1 coração.

---

## Vidas

- Você começa com **3 corações**.
- Cada erro ou tempo esgotado tira um coração.
- Ao perder todos, aparece o "Game Over".

---

## Ajuda Animada

- Botão **"Pedir ajuda"** mostra um passo a passo animado:
  1. Multiplica o dividendo por 10, 100, 1000... para eliminar a vírgula.
  2. Multiplica o divisor pelo mesmo fator.
  3. Mostra a divisão sem vírgula para resolver.
- Não mostra a resposta final, só o processo!

---

## Sons & Feedbacks

- **Sons de acerto, erro, perder vida e clique**.
- Confetes animados ao acertar.
- Modal de explicação ao perder vida (com motivo).

---

## Fluxo do Jogo

1. Tela de boas-vindas → "Começar a jogar"
2. HUD com nível, pontos, sequência, corações e tempo
3. Questão de divisão decimal
4. Campo de resposta + botão "Responder" + botão "Pedir ajuda"
5. Feedback instantâneo (acerto/erro/tempo)
6. Modal ao perder vida
7. Modal de Game Over quando vidas zeram
8. Botão para jogar novamente

---

## Exemplos de Questão

- `8,5 ÷ 2,5`
- `12,25 ÷ 2,45`
- `5,0 ÷ 2,5`
- (Sempre resulta em resposta inteira!)

---

## Outras Funcionalidades

- **Zerar progresso**: botão para reiniciar pontuação, vidas e nível.
- **Game Over**: mostra pontuação e nível alcançado, botão para tentar novamente.
- **Persistência**: progresso salvo localmente (localStorage).

---

## Observações Técnicas

- Feito em HTML, CSS e JS puro.
- Não requer backend ou instalação.
- Sons via WebAudio API, sem arquivos externos.
- Interface responsiva para desktop e mobile.

---

## Sugestões de Evolução

- Barrinha de progresso para o próximo nível
- Mascote animado
- Ranking local dos jogadores
- Modos de dificuldade extra
- Mais tipos de ajuda interativa

---

## Créditos & Licença

- João Manoel da Cruz Filho
- Murillo Frazão Cunha
- Ryan Cesar Pereira Folgado
