# Umraðanir og samantektir
## Umraðanir skilgreining
Er $r$ stök eru valin úr $n$ staka mengi og þeim raðað nefnist það $r$-umröðun

### Fjöldi mismunandi $r$-umraðana er táknað $P(n,r)$
$P(n,r) = n(n-1)(n-2)\cdot\dots \cdot (n-(r-1))$.

## Samantektir skilgreining
Er $r$ stök eru valin úr $n$ staka mengi en þeim ekki raðað nefnist það $r$-samantekt

### Fjöldi mismunandi $r$-samantekta er táknað $C(n,r)$ eða $\binom{n}{r}$
$$\binom{n}{r}=\frac{n(n-1)(n-2)\cdot\dots \cdot (n-(r-1)}{r!}$$

# Líkindafræði (*Probability*)
## Líkur (*frequency*)
Líkur á atburði: $$
O(A)=\frac{|A|}{n}
$$
Þar sem $n$ er heildarfjöldi möguleika og $|A|$ er fjöldi staka í $A$.

#### Ath! þetta gildir bara ef allir möguleikar eru jafn líklegir

## Tvíkostadreifing (*binomial distribution*)
Tilraun er endurtekin $n$-sinnum (með sömu upphafsaðstæðum) og gefur "jákvæða" niðurstöðu. Látum $X$ tákna fjölda jákvæðra niðurstaðna, 
$p=\text{ líkur á jákvæðu}$,
$q=1-p= \text{líkur á neikvæðu}$ (Í hverri tilraun).
Sagt er að $X$ hafi tvíkostadreifingu.

### Regla
$$
P(X=k) = \binom{n}{k}p^kq^{(n-k)}
$$

# Hendingar og væntigildi
## Hending(*random variable*)
Hendigng er fall frá útkomurými yfir í rauntölur

### Dæmi
1. Samtala þegar tveimur teningum er kastað.
2. Hærri tala þegar tveimur teningum er kastað.
3. Vinningsupphæðin í lottó-inu.

## Væntigildi
Væntigildi hendingar er "meðal útkoma" ef hending er endurtekin mjög oft.
$$
\sum_{s\in S}P(s)\cdot X(s)
$$
$S$ er útkomumengið.

### Dæmi
Lottó stefnir í 115 milljónir, væntigildi af öðrum vinning: $E(X)=P(\text{annar vinningur})\cdot \text{annar vinningur í kr}$.