# Net (*graph*)
Net er mengi af **Hnútum** (*verticies*) og samsvarandi **Leggja** (*edges*), hver leggur tengir annaðhvort tvo hnúta eða hnút við sjálfan sig.
Net geta verið óstefnd eða stefnd.
### Dæmu um stefnt net
[Hlekkur]( https://q.uiver.app/#q=WzAsNSxbMiwyLCJcXGJ1bGxldCJdLFs0LDIsIlxcYnVsbGV0Il0sWzMsMCwiXFxidWxsZXQiXSxbMCwxLCJcXGJ1bGxldCJdLFszLDQsIlxcYnVsbGV0Il0sWzMsMl0sWzIsMF0sWzAsNF0sWzQsMV0sWzEsMF0sWzAsM11d) <iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsNSxbMiwyLCJcXGJ1bGxldCJdLFs0LDIsIlxcYnVsbGV0Il0sWzMsMCwiXFxidWxsZXQiXSxbMCwxLCJcXGJ1bGxldCJdLFszLDQsIlxcYnVsbGV0Il0sWzMsMl0sWzIsMF0sWzAsNF0sWzQsMV0sWzEsMF0sWzAsM11d&embed" width="600" height="300" style="border-radius: 8px; border: none;"></iframe>
### Dæmi um óstefnt net með lykkju
[hlekkur](https://q.uiver.app/#q=WzAsNSxbMiwwLCJcXGJ1bGxldCJdLFswLDAsIlxcYnVsbGV0Il0sWzIsMiwiXFxidWxsZXQiXSxbMCwyLCJcXGJ1bGxldCJdLFsxLDEsIlxcYnVsbGV0Il0sWzEsMywiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFszLDQsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbNCwwLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzEsNCwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFsxLDAsIiIsMix7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMCwwLCIiLDIseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzIsMCwiIiwyLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFs0LDIsIiIsMix7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMywyLCIiLDEseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV1d) <iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsNSxbMiwwLCJcXGJ1bGxldCJdLFswLDAsIlxcYnVsbGV0Il0sWzIsMiwiXFxidWxsZXQiXSxbMCwyLCJcXGJ1bGxldCJdLFsxLDEsIlxcYnVsbGV0Il0sWzEsMywiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFszLDQsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbNCwwLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzEsNCwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFsxLDAsIiIsMix7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMCwwLCIiLDIseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzIsMCwiIiwyLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFs0LDIsIiIsMix7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMywyLCIiLDEseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV1d&embed" width="600" height="300" style="border-radius: 8px; border: none;"></iframe>
## Lykkja (*loop*)
Lykkja er leggur sem tengir hnút í sjálfan sig.
## Stig (*degree*)
Stig hnúts er fjöldi leggja sem tengjast í hann. *báðir endar á lykkjum eru taldir*.

## Grannar (*neighbors*)
Grannar eru tveir tengdir hnútar. Sagt er að hnútar eru *adjacent* ef þeir eru grannar.

## Vegur
Vegur er runa af tengdum leggjum: $v_{1}\to v_{2}\to\dots\to v_{n}$.

## Hringrás (*cycle*)
Er vegur sem fer í hring svo: $v_{1}\to\dots\to v_{n}\to\dots\to v_{1}$
### Fulltengt (*complete*) net (táknað $K_{4}$)
[Hlekkur](https://q.uiver.app/#q=WzAsNCxbMSwwLCJcXGJ1bGxldCJdLFswLDEsIlxcYnVsbGV0Il0sWzEsMiwiXFxidWxsZXQiXSxbMiwxLCJcXGJ1bGxldCJdLFswLDMsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMywyLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzIsMSwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFsxLDAsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMCwyLCIiLDEseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzEsMywiIiwxLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dXQ== ) <iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsNCxbMSwwLCJcXGJ1bGxldCJdLFswLDEsIlxcYnVsbGV0Il0sWzEsMiwiXFxidWxsZXQiXSxbMiwxLCJcXGJ1bGxldCJdLFswLDMsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMywyLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzIsMSwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFsxLDAsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMCwyLCIiLDEseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzEsMywiIiwxLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dXQ==&embed" width="600" height="300" style="border-radius: 8px; border: none;"></iframe>

### Hringnet (*cyclic graph*) (táknað $C_{6}$)
[Hlekkur](https://q.uiver.app/#q=WzAsNixbMiwwLCJcXGJ1bGxldCJdLFs0LDEsIlxcYnVsbGV0Il0sWzQsMywiXFxidWxsZXQiXSxbMiw0LCJcXGJ1bGxldCJdLFswLDMsIlxcYnVsbGV0Il0sWzAsMSwiXFxidWxsZXQiXSxbNSwwLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzAsMSwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFsxLDIsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMiwzLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzMsNCwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFs0LDUsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XV0=) <iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsNixbMiwwLCJcXGJ1bGxldCJdLFs0LDEsIlxcYnVsbGV0Il0sWzQsMywiXFxidWxsZXQiXSxbMiw0LCJcXGJ1bGxldCJdLFswLDMsIlxcYnVsbGV0Il0sWzAsMSwiXFxidWxsZXQiXSxbNSwwLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzAsMSwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFsxLDIsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMiwzLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzMsNCwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFs0LDUsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XV0=&embed" width="600" height="300" style="border-radius: 8px; border: none;"></iframe>

### Hjólnet (*wheel graph*) (táknað $W_{5}$)
[hlekkur](https://q.uiver.app/#q=WzAsOCxbMiwwLCJcXGJ1bGxldCJdLFswLDFdLFsxLDQsIlxcYnVsbGV0Il0sWzMsNCwiXFxidWxsZXQiXSxbMCwyLCJcXGJ1bGxldCJdLFs1LDJdLFs0LDIsIlxcYnVsbGV0Il0sWzIsMiwiXFxidWxsZXQiXSxbMCw3LCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzcsMiwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFsyLDQsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbNCw3LCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzcsNiwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFs2LDMsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMyw3LCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzAsNCwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFswLDYsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMywyLCIiLDEseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV1d) <iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsOCxbMiwwLCJcXGJ1bGxldCJdLFswLDFdLFsxLDQsIlxcYnVsbGV0Il0sWzMsNCwiXFxidWxsZXQiXSxbMCwyLCJcXGJ1bGxldCJdLFs1LDJdLFs0LDIsIlxcYnVsbGV0Il0sWzIsMiwiXFxidWxsZXQiXSxbMCw3LCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzcsMiwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFsyLDQsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbNCw3LCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzcsNiwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFs2LDMsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMyw3LCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzAsNCwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFswLDYsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMywyLCIiLDEseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV1d&embed" width="600" height="300" style="border-radius: 8px; border: none;"></iframe>

## Tvíhlutanet (*bipartite graph*)
Tvíhluta net er skilgreint þannig að hægt er að skipta hnútunum í tvennt: $V_{1}$ og $V_{2}$, svo: $V = V_{1}\cup V_{2}$ og $V_{1}\cap V_{2}=\emptyset$, og að allir leggirnir liggja aðeins á milli $V_{1}$ og $V_{2}$.

## Fullskipað tvíhlutanet (*Complete bipartite graph*)
Fullskipað tvíhlutanet með $|V_{1}|=m$ og $|V_{2}|=n$ er táknað $K_{mn}$

### Dæmi $K_{32} = K_{23}$
[hlekkur](https://q.uiver.app/#q=WzAsNSxbMCwwLCJcXGJ1bGxldCJdLFswLDIsIlxcYnVsbGV0Il0sWzAsNCwiXFxidWxsZXQiXSxbMiwxLCJcXGJ1bGxldCJdLFsyLDMsIlxcYnVsbGV0Il0sWzAsMywiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFszLDEsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMSw0LCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzQsMiwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFs0LDAsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMywyLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV1d)<iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsNSxbMCwwLCJcXGJ1bGxldCJdLFswLDIsIlxcYnVsbGV0Il0sWzAsNCwiXFxidWxsZXQiXSxbMiwxLCJcXGJ1bGxldCJdLFsyLDMsIlxcYnVsbGV0Il0sWzAsMywiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFszLDEsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMSw0LCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV0sWzQsMiwiIiwwLHsic3R5bGUiOnsiaGVhZCI6eyJuYW1lIjoibm9uZSJ9fX1dLFs0LDAsIiIsMCx7InN0eWxlIjp7ImhlYWQiOnsibmFtZSI6Im5vbmUifX19XSxbMywyLCIiLDAseyJzdHlsZSI6eyJoZWFkIjp7Im5hbWUiOiJub25lIn19fV1d&embed" width="600" height="300" style="border-radius: 8px; border: none;"></iframe>
# Litun neta
Net er litað með því að lita hnútana svo a enginn hnútur tengist hnút með sama lit.

## $n$-litanlegt (*$n$-colorable*) net
Net er $n$-litanlegt ef það er hægt að lita það með $n$ litum.
## Litunartala
Lægsti fjöldi lita sem hægt er að lita net með.

## Samhangandi net
Net er samhangandi ef til er vegur mill sérhverra tveggja hnúta.

## Sterkt samhangandi net
Stefnt net þar sem hægt er að fara frá hnút $a$ til $b$ fyrir alla hnúta $a$ og $b$.

# Framsetning neta og einsmótun
Það eru þrjár leiðir til að setja fram net í tölvu
## Grannalisti (*adjacency list*)
Listi þar sem tekið er fram hvaða hnútar tengjast við $i$-ta hnútinn í listanum

## Grannfylki (*adjacency matrix*)
Tengingar milli hnúta merktir með $1$.
$$
\begin{bmatrix}
 0 & 1 & 1 & 1 \\
 1 & 0 & 1 & 1 \\
 1 & 1 & 0 & 1 \\
 1 & 1 & 1 & 0
\end{bmatrix}
= K_{4}
$$
## Legufylki (*incidence matrix*)
Fylki þar sem leggir og hnútar eru merktir með bókstöfum og tölum, og tengingar milli hnúta og leggja merktir með $1$.

$$\begin{matrix} 1 & 0 & 0 & 1 & 0 & 1 \\1 & 1 & 0 & 0 & 1 & 0 \\0 & 1 & 1 & 1 & 0 & 0 \\ 0 & 0 & 1 & 0 & 1 & 1 \\ \end{matrix}\hskip 2ex = K_{4} \hskip-11.5em\raise 8ex \hbox{a}\hskip 1em\raise 8ex \hbox{b}\hskip 1em\raise 8ex \hbox{c}\hskip 1 em\raise 8ex \hbox{d} \hskip 1em\raise 8ex \hbox{e}\hskip 1em\raise 8ex \hbox{f}\hskip -9.7em\raise 4.8ex \hbox{1} \hskip -0.5em\raise 1.8ex \hbox{2} \hskip -0.5em\raise -1.8ex \hbox{3} \hskip -0.5em\raise -4.8ex \hbox{4} 
$$
## Einsmóta net
Tvö net eru $G_{1}(V_{1},E_{1})$ og $G_{2}(V_{2},E_{2})$ eru einsmóta ef til er gagntæk vörpun $f:V_{1}\to V_{2}$ þannig að: $x,y\text{ eru grannar í } G_{1} \leftrightarrow f(x), f(y) \text{ eru grannar í } V_{2}$.
Óformlega má orða þetta svo að tvö net eru einsmóta ef það er hægt að færa hnúta í einu neti, án þess að breyta leggjum milli hnúta svo að netin líti eins út.

## Sléttunet (*Planar graph*)
Sléttunet er net sem teikna má í plani án þess að leggir þess krossast.
### Formúla Eulers:
Ef við erum með sléttunet sem skiptir planinu í svæði, (þar meðtalið svæðið fyrir utan netið). Látum $r=\text{ fjöldi svæða}$, $e= \text{ fjöldi leggja}$ og $v=\text{ Fjöldi hnúta}$, þá gildir að:
$$
r=e-v+2
$$
#### Sönnun á formúlu Eulers (með þrepun á fjölda leggja):
##### Grunnskref:
Ef $e=0$ þá er netið bara einn hnútur svo $v=1$ og $r=1$
$1=0-1+2$, svo reglan gildir fyrir $e=0$.
##### Forsenda:
G.r.f að reglan gildi fyrir net með $e=k$, svo: $r=k-v+2$.
##### Þrepun:
Skoðum net með $k+1$ legg. Veljum legg af handahófi og fjarlægjum hann úr netinu, þá eru tveir möguleikar:
	1. að leggurinn sé "bryggja", fjöldi svæða stendur þá í stað, en $v$ og $e$ lækka um $1$, $r=(e-1)-(v-1)+2=r=e-v+2$ svo reglan gildir í minna netinu og þar afleiðandi í því stærra.
	2. að leggurinn sé "brú", þá lækka $r$ og $e$ um $1$, en $v$ stendur í stað. Líkt og í 1. þá fæst: $r-1=(e-1)-v+2=r=e-v+2$ svo reglan gildir í báðum netunum.
Þar afleiðandi gildir formúla Eulers í neti með $k+1$ leggjum, ergo gildir reglan í öllum sléttunetum.
