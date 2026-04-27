---
type: adversary
aliases:
  - Verme das Areias
  - Verme
tags:
  - campaign/adversary/boss
  - campaign/adversary/tier-1
tier: 1
difficulty: 12
hp: 22
---

# 🐛 Verme das Areias
*Adversário — Tier 1 · Solo Boss Multi-Segmento*

[[Inicio|🏠 Início]] | [[Garganta dos Ventos]]

**Sessão:** [[Sessao 2 - Travessia do Desfiladeiro|Sessão 2 — Travessia do Desfiladeiro]]

> *"SAIAM DAS PEDRAS BAIXAS!" — Tareq, um segundo antes do cascalho explodir.*

---

## Descrição

Predador de emboscada que habita os trechos mais profundos da [[Garganta dos Ventos]]. Boca circular de dentes em anéis concêntricos, pele cinza-pedra cheia de cicatrizes, corpo de dez a quinze metros — a maior parte enterrado na rocha e cascalho. Emerge sob a presa sem aviso: **o chão vibra antes**.

Raro nas altitudes da Garganta, mas não impossível — e cada vez menos raro desde o [[Era IV - O Clarao|Clarão]]. As caravanas yashianas aprendem a escutar o som do cascalho assentando.

---

## Comportamento

- **Emboscada:** emerge sob a presa, ataca antes de qualquer reação
- **Tremor anuncia:** sempre que submerge para reposicionar, o chão vibra — **mestre DEVE narrar isso** para dar chance de reação
- **Engolir é icônico:** quando reduz um PC a 0 PV com Mordida, engole em vez de matar — cena de combate de dentro do corpo
- **Foge se acuado:** se Cabeça e Cauda forem destruídas, tenta mergulhar e escapar. Sobreviver derrotando só o Corpo é **vitória moral e mecânica**

---

## Mecânicas

> [!info] Stat block gerado via [DaggerHub](https://erickcassoli.github.io/DaggerHub/)
> JSON importável: [[DaggerHub JSON/verme-das-areias.json|verme-das-areias.json]]

![[verme-das-areias.png]]

> [!mechanics] Ficha Daggerheart — Verme das Areias (Corpo principal)
> **Tier:** 1 · **HP:** 22 · **Evasão:** 12 · **Armor Score:** 0
>
> **Limiares:** Menor 6 / Maior 12 / Grave 18
>
> **Experiências:** Emboscada +4, Sentido do Tremor +3

---

## Partes Destrutíveis

O Verme tem **três partes** — os PCs declaram qual atacam. Cada uma tem PV e Evasão próprios.

| Parte | PV | Evasão | Limiar Menor | Limiar Maior | Efeito se destruída |
|-------|----|----|----|----|---------------------|
| **Cabeça** (boca + cuspe ácido) | 10 | 14 | 4 | 8 | Perde Cuspe Ácido e Mordida em alvo distante |
| **Corpo** (alvo principal — morte = vitória) | 22 | 12 | 6 | 12 | **Verme morre. Fim do combate.** |
| **Cauda** (chicoteia em área) | 8 | 15 | 3 | 7 | Perde Caudada em Área |

**Dano recebido (todas as partes):**
- < Limiar Menor → 1 PV
- ≥ Limiar Menor → 2 PV
- ≥ Limiar Maior → 3 PV

---

## Movimentos

**Mordida** +6 (corpo-a-corpo, alcance 1 do pescoço): 2d8+3 físico.
*Se reduzir a 0 PV: tenta Engolir (Movimento de Medo).*

**Cuspe Ácido** +5 (distante, até 15m): 1d10+2 físico + 1d4 ácido na rodada seguinte + 1 Estresse.

**Caudada em Área** +4 (área raio 3m): 1d8+2 físico + Força CD 12 ou Prostrado.

### Movimentos de Medo

| Custo | Movimento |
|-------|-----------|
| 1 Medo | **Tremor Sob os Pés** — submerge e ressurge. PCs em raio 5m rolam Agilidade CD 12 ou Prostrados |
| 2 Medo | **Engolir** — após Mordida que reduz PC a 0 PV, engole em vez de matar. PC vivo dentro (1d6 ácido/rodada), atacar o Corpo de dentro causa dano em dobro. Sair: Força CD 14 |
| 2 Medo | **Guincho Perfurante** — PCs fazem Instinto CD 12 ou 1 Estresse + desvantagem na próxima ação |
| 3 Medo | **Explosão de Cascalho** — 2d6 físico em raio 6m + cria terreno difícil permanente |

### Ações Reativas

**Mergulho Final** *(se só o Corpo vivo)*: tenta fugir — mergulha, aparece 10m adiante com +2 Evasão temporário. PCs rolam Agilidade CD 13 para perseguir; 2 falhas seguidas = Verme escapa (**+2 Esperança** pelo grupo sobreviver, mas vira ameaça viva da região).

---

## ⏳ Contagem Opcional — Calor do Meio-Dia

Se o combate passar do **turno 5**, coloque **d6 em 6** na mesa. A cada turno, PC rola **Vigor CD 10** — falha = 1 Estresse. Ao chegar a 0: todos ganham 1 Estresse automático e ataques com desvantagem até fim do combate.

*Serve para incentivar o grupo a encerrar rápido — com 6 jogadores, a contagem é ferramenta de ritmo.*

---

## Momentos de Esperança

| Situação | Ganho |
|---|---|
| Destruir a Cauda antes do turno 4 | +1 Esperança |
| Destruir a Cabeça antes do turno 5 | +1 Esperança |
| Salvar um guia yashiano (Tareq ou Youssef) de um ataque | +1 Esperança |
| Libertar um PC engolido em 1 turno | +1 Esperança ao grupo |
| Crítico contra o Corpo | +1 Esperança automático |
| Encerrar sem ativar o Calor do Meio-Dia | +2 Esperança ao grupo |

---

## GM Notes

**Narre o tremor.** Toda vez que o Verme for submergir ou ressurgir, descreva o chão vibrando 1 segundo antes. É a ferramenta que dá chance de reação — sem ela, vira "gotcha".

**Engolir é lembrado, não optimized.** Se um PC for engolido, **pare a mesa**. Descreva visualmente (ácido queimando, escuridão pulsante, voz abafada dos companheiros chamando). Esse é o tipo de momento que vira lenda de mesa.

**Fugir é válido.** Se o Verme mergulhar e escapar com Corpo em PV baixo, isso não é derrota — é "sobrevivemos". Celebrar isso ensina aos jogadores que nem todo combate precisa acabar em cadáver.

**Ativos fora do combate:** sangue seco em trilha, marcas de três dedos no cascalho, bota sozinha com cadarço amarrado — tudo semente de atmosfera antes do encontro. A skill de identificação (**Conhecimento CD 13**) reconhece como "Verme das Areias" antes do ataque.
