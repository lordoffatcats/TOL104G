# Tegundir sannana:
## Bein sönnun (direct prood):
#### Sönnun á $p\rightarrow q$
Gerum ráð fyrir $p$ og sýnum að $q$ gildi.

### Dæmi:
Sönnum að ef $n$ er oddatala þá er $n^{2}$ oddatala.

Notum að allar oddatölur $n$ má rita sem: $n=2k+1$.

G.r.f að n sé oddatala svo $n=2k+1$. Þá fæst að:

$$n^{2}=(2k+1)^{2}=4k^{2}+4k+1$$

Skrifa má $4k^{2}+4k+1 = 2(2k^{2}+2k)+1$.

Látum $k'=2k^{2}+2k$,  svo: $n^{2}=2k'+1$ sem sannar það sem sanna átti.

## Mótskilyrðing (contraposition):

#### Sönnun á $p\rightarrow q$
Notar $p \rightarrow q \equiv \neg q\rightarrow \neg p$.

Gerum ráð fyrir $\neg q$ og sönnum $\neg p$.

### Dæmi:
Sýnum að ef $3n+2$ er oddatala þá er $n$ oddatala.

Látum $p:= 3n+2 \text{ er oddatala}$, og $q:=n\text{ er oddatala}$.

G.r.f $\neg q$, svo: $n$ er slétt tala, svo: $n=2k$.

Þá fæst: $3n+2=3\cdot 2k+2 = 2(3k+1)$.

Látum $k'=3n+1$, svo: $3n+2=2(3n+1) =2k'$, sem sýnir að þá sé 3n+2 slétt tala.

Semsagt $\neg q\rightarrow\neg p \equiv p\rightarrow q$ sem sannar það sem sanna átti.

## Sönnun með mótsögn (proof by contradiction):
#### Sönnun á $p$
Gerum ráð fyrir $\neg p$ og leiðum út mótsögn, svo $p\equiv T$

### Dæmi:
Sýnum að $\sqrt{ 2 }$ sé ekki ræð tala.

Munum að ræða tölu má skrifa sem fullstytt brot $\frac{a}{b}$ | $a,b \in \mathbb{Z}$, $b\neq0$

Látum $p:=\sqrt{ 2 }\text{ er ekki ræð tala}$.

G.r.f $\neg p$ svo $\sqrt{ 2 } = \frac{a}{b}$, þá fæst: 

$$2=\frac{a^{2}}{b^{2}} \Rightarrow a^{2}=2b^{2}$$

Svo: $a^{2}$ er slétt tala, svo: $a=2k$ er slétt tala. Þá fæst:

$$(2k)^{2}=2b^{2}\Rightarrow 4k^{2}=2b^{2} \Rightarrow 2k^{2}=b^{2}$$

Svo $b$ er slétt tala sem gefur okkur mótsögn svo $\sqrt{ 2 }$ er ekki ræð tala.

#### Sönnun á $p\rightarrow q$
G.r.f. $p\land\neg q$ og leiðum út mótsögn, sem sýnir að: $p\rightarrow q$ eða $\neg p\rightarrow q$

## Sönnun á $p\leftrightarrow q$
Sýnum að $p\rightarrow q$ og $q\rightarrow p$

## Sönnun með mótdæmi á $\neg\forall x(p(x))$
Finnum $y$ með $\neg p(y)$

# Pigeonhole principle
Ef $n$ hlutir eru settir í $m<n$ "geymslur", þá þurfa að vera $2$ hlutir í a.m.k einni "geymslu".

# Þrepasannanir
## Þrepun
### Grunnskref
Grunnskrefið felst í því að sanna að regla gildir fyrir einhverja tölu, t.d. $n=1$

### Þrepunarskref
#### Þrepunarforsenda
Gerum ráð fyrir að reglan gildir fyrir einhverja tölu $n=k$. Köllum þetta þrepunarforsendu.

#### Þrepun
Sýnum að reglan gildi fyrir $k+1$. (*Ath! við erum að sanna að reglan gildi fyrir næstu tölu á eftir $n=k$ svo við megum ekki draga þá ályktun að reglan gildri fyrir $n=k+1$*).

## Dæmi um þrepun:
Sönnum að $1+2+3+\dots+n=\frac{n(n+1)}{2}$.

#### Grunnskref:
$1=\frac{1\cdot2}{2}=\frac{2}{2}=1$, sýnir að reglan gildir fyrir $n=1$.

#### Þrepunarforsenda:
Gerum ráð fyrir að $1+2+3+\dots+k=\frac{k(k+1)}{2}$.

#### Þrepunarskref
Sjáum að:
$$
1+2+3+\dots+k+(k+1)=\frac{k(k+1)}{2}+(k+1) =\frac{k(k+1)+2(k+1)}{2} = \frac{(k+1)(k+2)}{2}
$$
Sem sannar það sem sanna átti.

## Sterk þrepun
Ólíkt hefðbundnari þrepun: "$n=k$"$\implies$"$n=k+1$", er nú gert ráð fyrir að regla gildir fyrir $n\leq k$ og sönnum að regla gildi fyrir $n=k+1$.

### Dæmi:
Sérhverja tölu $n\geq2$ má skrifa sem margfeldi prímtalna. Sönnum það með strekri þrepun:

#### Grunnskref:
$2=2$ ($2$ er prímtala)

#### Þrepunarskref:
G.r.f að reglan gildir fyrir $n\leq k$.
Þá fáum við tvö tilvik:

 1. $n=k+1$ er prímtala $p_{1}$. Þá þarf ekki að gera meir.
 
 2. $n=k+1$ er samsett, svo: $n=a\cdot b$. Skv. þrepunarforsendu er $a=p_{1}\cdot p_{2} \cdot \dots \cdot p_{k}$ og $b=q_{1}\cdot q_{2} \cdot \dots \cdot q_{l}$, þar sem $p_{i}$ og $q_{j}$ eru prímtölur.

Þá er $n = q_{1}\cdot q_{2} \cdot \dots \cdot q_{l} \cdot p_{1}\cdot p_{2} \cdot \dots \cdot p_{k}$, Svo reglan gildir fyrir öll $n$