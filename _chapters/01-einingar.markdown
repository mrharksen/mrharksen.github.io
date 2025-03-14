---
layout: post
title:  "Kafli 1: Einingar"
date:   2025-02-21
categories: jekyll update
---
## SI-einingakerfið og mælistærðir

Eðlisfræði eru vísindi byggð á **tilraunum** þar sem við gerum **markvissar mælingar** og túlkum niðurstöður þeirra.

- **Mæling** felur í sér **samanburð við staðal** (e. standard).  
  - Dæmi: Lengd er mæld í metrum ($\si{m}$), tími í sekúndum ($\si{s}$).  

- Túlkun mæliniðurstöðu styðst við fræðilegt **líkan** byggt á stærðfræði t.d. aflfræði Newtons.

Við notum **alþjóðlega einingakerfið** (SI), sem hefur sjö grunneiningar sem sýndar eru í [Töflu 2.1](#tafla-einingakerfi).  

---

<div class="table-wrapper" markdown="block">

| **Eining**  | **Heiti**       | **Mælistærð**   |
|:----------:|:--------------:|:--------------:|
| $\si{s}$   | sekúnda        | tími              |
| $\si{m}$   | metri          | lengd             |
| $\si{kg}$  | kílógramm      | massi             |
| $\si{K}$   | kelvin         | hiti              |
| $\si{mol}$ | mól            | magn efnis        |
| $\si{A}$   | amper          | rafstraumur       |
| $\si{cd}$  | kandela        | geislunarstyrkur  |

</div>

*Tafla 2.1: Grunneiningar alþjóðlega SI-einingakerfisins.*

---
Mælanlegar stærðir hafa **mælivídd** (e. dimension)

$$
\begin{aligned}
    \text{[Lengd]} & \quad L \\
    \text{[Massi]} & \quad M \\
    \text{[Tími]}  & \quad T \\
    \text{[Hiti]}  & \quad \Theta \\
    \text{[Magn efnis]} & \quad N \\
    \text{[Rafstraumur]} & \quad I \\
    \text{[Geislunarstyrkur]} & \quad J
\end{aligned}
$$


Forskeyti sem notuð eru til að gefa stærðargráðu eininga má sjá í [Töflu 2.2](#tafla-forskeyti).

<div class="table-wrapper" markdown="block">

| **Forskeyti** | **Skammstöfun** | **Gildi**  |
|:------------:|:--------------:|:----------:|
| tera        | $\si{T}$       | $10^{12}$  |
| giga        | $\si{G}$       | $10^{9}$   |
| mega        | $\si{M}$       | $10^{6}$   |
| kilo        | $\si{k}$       | $10^{3}$   |
| hecto       | $\si{h}$       | $10^{2}$   |
| deka        | $\si{da}$      | $10^{1}$   |
| deci        | $\si{d}$       | $10^{-1}$  |
| centi       | $\si{c}$       | $10^{-2}$  |
| milli       | $\si{m}$       | $10^{-3}$  |
| micro       | $\si{\mu}$     | $10^{-6}$  |
| nano        | $\si{n}$       | $10^{-9}$  |
| pico        | $\si{p}$       | $10^{-12}$ |
| femto       | $\si{f}$       | $10^{-15}$ |

</div>

*Tafla 2.2: Helstu forskeyti alþjóðlega einingakerfisins.*

---


## Dæmi

### **Einingar, markverðir stafir og staðalform**

#### **Dæmi 2.1** – Breyting á lengdareiningum

Við Evrópubúarnir búum svo vel að hafa alist upp með SI-einingakerfið og notum því metra í daglegu tali. En víðsvegar um heiminn notar fólk aðrar (óheppilegar) lengdareiningar enn þann dag í dag. Við skulum skoða nokkrar þeirra hér:

<div class="table-wrapper" markdown="block" id="tafla-einingakerfi2">

| **Stærð**    | **Enska** | **Skammstöfun** | **Jafngildir** |
|:------------:|:--------:|:--------------:|:--------------:|
| Þumlungar    | Inch     | in             | $\SI{2,54}{cm}$  |
| Fet         | Feet     | ft             | $\SI{30,5}{cm}$  |
| Álnir       | Ell      | el             | $\SI{49,1}{cm}$  |
| Yardar      | Yard     | yd             | $\SI{91,44}{cm}$ |
| Mílur       | Mile     | mi             | $\SI{1,609}{km}$ |

</div>

\[
\text{Tafla 2.3} \quad \tag{2.3}
\]

Breytið eftirfarandi stærðum yfir á staðalform:

- (a) $\SI{6}{ft}$ $\SI{6}{in}$
- (b) $\SI{410}{mi}$
- (c) $120$ álnir vaðmáls
- (d) $100$ yards

---

#### **Dæmi 2.2** – Staðalform

Breytið eftirfarandi stærðum yfir á staðalform:

- (a) $\SI{286,6}{mm}$
- (b) $\SI{760}{mg}$
- (c) $\SI{22,5}{nm}$
- (d) $\SI{62,1}{ps}$

---

#### **Dæmi 2.3** – Þorgeir og hlaupið

Þorgeir er mikill hlaupagarpur. Hann lætur alltaf iPodinn sinn mæla vegalengdirnar sem hann hleypur. Því miður kann hann ekki að breyta stillingunum í honum svo iPodinn er alltaf stilltur á mílur. Ef hann ætlar að hlaupa $\SI{16,0}{km}$ hversu margar mílur á hann þá að hlaupa?

<details>
  <summary><strong>📖 Svar</strong></summary>
$\SI{9,94}{}$mílur.
</details>

---

#### **Dæmi 2.4** – Sekúndur í einu ári

Hversu margar sekúndur eru í einu ári?

---

#### **Dæmi 2.5** – Stjarnfræðieining (AU)

Meðalfjarlægðin milli jarðarinnar og sólarinnar kallast **stjarnfræðieining** og er táknuð með $\SI{1}{AU}$ sem jafngildir $\SI{149,6}{}$ milljón kílómetrum. Setjið fram **stjarnfræðieininguna** á staðalformi.

---

#### **Dæmi 2.6** – Lengd ljósárs

Ljósár er, þrátt fyrir nafnið, lengdarmælieining og jafngildir vegalengdinni sem ljósið ferðast á einu ári. Ef hraði ljósins er:

$$
c = \SIexp{3{,}00}{3}{m/s}
$$

hver er þá lengd eins ljósárs, $\SI{1}{ly}$, á staðalformi?

---

#### **Dæmi 2.7** – Stjarnfræðieiningar í ljósári

Hversu margar **stjarnfræðieiningar** eru í **einu ljósári**?
