# Disclaimer
Ég missti af fyrirlestrunum svo þetta er kannski ekki allt eins.

# Mengi
Mengi eru "óröðuð söfn" af "hlutum" (kallaðir stök) hvort sem það eru tölur, strengir, önnur mengi eða í raun hvað sem er. Gagnlegt getur verið að hugsa um mengi sem lista ef þau eru ekki óendanleg. T.d. listi af öllum nöfnum á Íslandi eða eih.

## Algeng mengi
$\mathbb{N} = \{0,1,2,3,\dots\}$, mengið af öllum náttúrulegu tölunum.

$\mathbb{Z} = \{\dots,-2,-1,0,1,2,,\dots\}$ , mengið af öllum heiltölunum.

$\mathbb{z^+} = \{1,2,3,\dots\}$  mengið af öllum jákvæðu heiltölunum.

$\mathbb{Q}=\left\{ \frac{p}{q}|p \in \mathbb{Z}, q \in \mathbb{Z}, \text{ og } q\neq{0}\right\}$, mengið af öllum ræðu tölunum.

$\mathbb{R}$, mengið af öllum rauntölunum.

## Stak
Ef $a$ er stak í mengi $A$ þá ritum við:
$$a\in A$$

Ef $a$ er ekki stak í $A$ þá ritum við: 
$$a\notin A$$

## Tómamengið
Tómamengið er mengið með engum stökum, táknað $\{ \}$ eða $\emptyset$. Takið eftir því að $\emptyset \neq \{\emptyset\}$.

## Vennmyndir
Venn myndir eru myndræn leið til þess að tákna mengi. Þar er $U$ "universal set" sem inniheldur alla hluti í samhenginu teiknað sem rétthyrningur. Mengi eru svo teiknuð inn $U$, vanalega sem hringir.

### Dæmi um Vennmynd
```tikz
\begin{document}
\begin{tikzpicture}[fill=gray]
% outline
\draw (0,0) circle (1) (0,1)  node [text=black,above] {$A$}
      (1,0) circle (1) (1,1)  node [text=black,above] {$B$}
      (-2,-2) rectangle (3,2) node [text=black,above] {$U$};
\end{tikzpicture}
\end{document}
```


## Hlutmengi
Mengi $A$ er hlutmengi í $B$, og $B$ er *superset* af $A$, ef og aðeins ef öll stök í $A$ eru líka stök í $B$. Við táknum $A\subseteq B$ til að tákna að $A$ sé hlutmengi í $B$. Líka er hægt að nota $B \supseteq A$ til að tákna að $B$ sé *superset* af $A$. $A\subseteq B \equiv B \supseteq A$ (Táknar það sama).

## Sammengi
Sammengi $A$ og $B$ er notað til að tákna þau stök sem eru í $A$ eða $B$, táknað 
$$
A \cup B
$$
Takið eftir að $\cup$ er svipað og $\lor$
```tikz
\begin{document}
\begin{tikzpicture}[fill=gray]
% fill
\scope
\fill(0,0) circle (1) (1,0) circle (1);
\endscope
% outline
\draw (0,0) circle (1) (0,1)  node [text=black,above] {$A$}
      (1,0) circle (1) (1,1)  node [text=black,above] {$B$}
      (-2,-2) rectangle (3,2) node [text=black,above] {$U$};
\end{tikzpicture}
\end{document}
```

## Sniðmengi
Snipmengi $A$ og $B$ er notað til að tákna þau stök sem eru í $A$ og $B$, táknað 
$$
A\cap B
$$

Takið eftir að $\cap$ er svipað og $\land$
```tikz
\begin{document}
% shapes
\def\firstcircle{(0,0) circle (1) (0,1)}
\def\secondcircle{(1,0) circle (1) (1,1)}
\def\bound{(-2,-2) rectangle (3,2)}
    
\begin{tikzpicture}[fill=gray]
	% fill
    \begin{scope}
        \clip \firstcircle;
        \fill \secondcircle;
    \end{scope}
    \begin{scope}
        \clip \secondcircle;
        \fill \firstcircle;
    \end{scope}
    % outline
    \draw \firstcircle node [text=black,above] {$A$};
    \draw \secondcircle node [text=black,above] {$B$};
    \draw \bound node [text=black,above] {$U$};
\end{tikzpicture}
\end{document}
```
![[Mengjamyndir.png]]

#### Öll mengi hafa a.m.k tvö hlutmengi:
Fyrir öll mengi $S$:

(i)    $\emptyset \subseteq S$

(ii)    $S\subseteq S$

Tómamengið og megið sjálft eru hlutmengi í hverju mengi.

### Dæmi um hlutmengi:
$A$ er hlutmengi í $B$
```tikz
\begin{document}
\begin{tikzpicture}[fill=gray]
% outline
\draw (1/2,0) circle (1) (1/2,1)  node [text=black,above] {$A$}
      (1/2,0) circle (1/2) (1/2,1/2)  node [text=black,above] {$B$}
      (-2,-2) rectangle (3,2) node [text=black,above] {$U$};
\end{tikzpicture}
\end{document}
```


## Jöfn mengi
Tvo mengi eru jöfn ef og aðeins ef þau hafa sömu stök. 
Því, ef $A$ og $B$ eru mengi, þá eru $A$ og $B$ jöfn ef og aðeins ef $\forall x(x\in A \leftrightarrow x \in B)$. 
Við skrifum $A=B$ ef $A$ og $B$ eru jöfn mengi.

Ef $(A \subseteq B) \land (B \subseteq A)$ Þá er $A=B$.

## Stærð mengis
Fjöldi staka í mengi $S$ er táknað: $|S|$. Ef $|S|$ er jákvæð heiltala er $S$ sagt vera endanlegt mengi annars er það óendanlegt.

#### Dæmi:
$|\emptyset| = 0$.
$A=\{ 1,2,3,4,5 \}$, $|A| = 5$.


## Veldismengi (*Power set*)
Veldismengi mengis $S$ er mengi allra hlutmengja $S$, táknað $\mathcal{P}(S)$.
Ef mengi $S$ hefur $n$ stök, svo $|S|=n$ þá er $|\mathcal{P}(S)|=2^n$.

## Faldmengi (*Cartesian product*)
Látum $A$ og $B$ vera mengi. Faldmengið af $A$ og $B$, táknað $A\times B$, er mengi allra raðaðra para $(a,b)$, þar sem $a\in A$ og $b\in B$. Þannig:
$$A\times B = \{ (a,b)|a\in A\land b\in B \}$$

#### Mikilvægt $A\times B \neq B\times A$

### Dæmi um faldmengi:
Látum $A = \{ 0,1,2 \}$ og $B = \{ 0,1 \}$. 

Þá er $A \times B = \{ (0,0),(0,1),(1,0),(1,1),(2,0),(2,1) \}$

Teikna má faldmengi í hnitakerfi