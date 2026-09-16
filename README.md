
# 🃏 BlackJack em Java

Jogo de Blackjack (21) desenvolvido em Java utilizando Swing para a interface gráfica. O projeto simula uma mesa de blackjack completa, com baralho embaralhado dinamicamente, dealer automático e sistema de apostas com fichas.

## Funcionalidades

- 🎲 Baralho completo de 52 cartas, embaralhado a cada rodada
- 💰 Sistema de apostas: o jogador começa com 1000 fichas e aposta em cada rodada
- 🤖 Dealer joga automaticamente seguindo a regra clássica (compra cartas até somar 17)
- 🂡 Cálculo automático do valor da mão, incluindo o ajuste de Ases (11 ou 1)
- 🏆 Resultado da rodada (vitória, derrota ou empate) com pagamento automático da aposta
- 🔁 Botão de nova rodada para continuar jogando

## Tecnologias

- Java
- Swing (interface gráfica)

## Como jogar

1. Escolha o valor da aposta clicando nos botões de fichas (+10, +25, +50)
2. Clique em **Apostar** para receber suas cartas
3. Use **Hit** para pedir mais uma carta ou **Stay** para parar e passar a vez ao dealer
4. O resultado da rodada é exibido na tela, e o saldo é atualizado automaticamente
5. Clique em **Nova Rodada** para jogar novamente

## Como executar

```bash
javac BlackJack.java
java BlackJack
```

> É necessário ter uma pasta `cards/` no mesmo diretório do projeto, contendo as imagens das cartas (ex: `A-C.png`, `10-H.png`) e a imagem do verso da carta (`BACK.png`).

## Próximos passos

- [ ] Adicionar double down
- [ ] Adicionar split de pares
- [ ] Adicionar seguro (insurance)
- [ ] Persistir o saldo entre execuções

---

Projeto desenvolvido para fins de estudo e prática de Java/POO.
