# Yrðingar
Yrðingar eru setningar sem eru annaðhvort sannar eða ósannar.

### Dæmi um yrðingar:
Himininn er blár
$$2+2 = 4$$

### Dæmi um ekki yrðingar:
Er himinninn blár?
$$x+2=4$$

# Helstu tákn
$\neg$ : ekki, 
	t.d. $\neg p$  ekki $p$ þar sem $p$ er einhver yrðing.
	
$\land$ : og, 
	t.d. $p \land q$ : er satt ef $p$ og $q$ eru sönn.
	
$\lor$ : eða, 
	t.d. $p \lor q$ : er satt er p$ eða $q$ eða bæði eru sönn.
	
$\oplus$ : annaðhvort (en ekki bæði), 
	t.d. $p \oplus q$ : er satt ef $p$ er satt eða ef $q$ er satt.
	
$\rightarrow$ : leiðir til,
	t.d. $p \rightarrow q$ : ef $p$ er satt, þá hlýtur $q$ að vera satt. (Ef $p$ er ósatt getur $q$ verið satt eða ósatt). Sagt ef $p$ þá $q$.
	
$\leftrightarrow$ : Tvíleiðing,
	t.d. $p \leftrightarrow q$ : jafngildir $p \rightarrow q \land q \rightarrow p$.
	
$\equiv$ : jafngildir,
	t.d. $p \equiv p$ : $p$ jafngildir $p$.
### Quantifiers
$\forall$, fyrir öll.

$\exists$, er til.

$\therefore$ "therefore", "ergo". (því, svo, þannig).

## Sanntöflur

| $$p$$ | $$q$$ | $$\neg p$$ | $$p \land q$$ | $$p \lor q$$ | $$p \oplus q$$ |
| --- | --- | -------- | ----------- | ---------- | ------------ |
| F   | F   | T        | F           | F          | F            |
| F   | T   | T        | F           | T          | T            |
| T   | F   | F        | F           | T          | T            |
| T   | T   | F        | T           | T          | F            |

| $$p$$ | $$q$$ | $$p \rightarrow q$$ | $$p \leftrightarrow q$$ | $$\neg(p\oplus q)$$ |
| --- | --- | ----------------- | --------------------- | ----------------- |
| F   | F   | T                 | T                     | T                 |
| F   | T   | T                 | F                     | F                 |
| T   | F   | F                 | F                     | F                 |
| T   | T   | T                 | T                     | T                 |

# Rökfræði reglur
### Identity laws
$$p\land T \equiv p$$
$$p \lor F \equiv p$$

### Domination laws
$$p\lor T \equiv T$$
$$p \land F \equiv F$$

### Indempotent laws
$$p \lor p \equiv p$$
$$p \land p \equiv p$$

### Double neagtion law
$$\neg(\neg p) \equiv p$$

### Commutative laws
$$p \lor q \equiv q \lor p$$
$$p \land q \equiv q \land p$$

### Associative laws
$$(p \lor q) \lor r \equiv p \lor (q \lor r)$$
$$(p \land q) \land r \equiv p \land (q \land r)$$

### Distributive laws
$$p \lor (q \land r) \equiv (p\lor q)\land(p \lor r)$$
$$p \land (q\lor r) \equiv (p\land q)\lor(p\land r)$$

### DeMorgans laws
$$\neg(p\land q) \equiv \neg p \lor \neg q$$
$$\neg(p\lor q) \equiv \neg p \land \neg q$$

### Absorption laws
$$p\lor(p\land q) \equiv p$$
$$p\land(p\lor q) \equiv p$$

### Negation laws
$$p\lor\neg p \equiv T$$
$$p\land\neg p \equiv F$$

## Logical equivalences
$$p\rightarrow q \equiv \neg p\lor q\equiv\neg q\rightarrow\neg p$$


$$p\lor q\equiv \neg p\rightarrow q$$
$$p\land q \equiv \neg(p\rightarrow\neg q)$$


$$\neg(p\rightarrow q) \equiv p\lor\neg q$$


$$(p\rightarrow q)\land(p\rightarrow r) \equiv p\rightarrow(q\land r)$$
$$(p\rightarrow r)\land(q\rightarrow r) \equiv (p\lor q)\rightarrow r$$


$$(p\rightarrow q)\lor(p\rightarrow r)\equiv p\rightarrow(q\lor r)$$
$$(p\rightarrow r)\lor(r\rightarrow r)\equiv (p\lor q)\rightarrow r$$


$$\neg(p\leftrightarrow q)\equiv p\leftrightarrow\neg q$$

## Rules of inference
### Modus ponens
$$(p\land(p\rightarrow q))\rightarrow q$$

### Modus tollens
$$(\neg q\land(p\rightarrow q)) \rightarrow \neg p$$

### Hypothetical syllogism
$$((p\rightarrow q)\land(q\rightarrow r))\rightarrow (p\rightarrow r)$$

### Disjunctive syllogism
$$((p\lor q)\land\neg p)\rightarrow q$$

### Addition
$$p\rightarrow p\lor q$$

### Simplification
$$(p\land q)\rightarrow p$$

### Conjuction
$$((p)\land(q))\rightarrow p\land q$$

### Resolution
$$((p\lor q)\land(\neg p\lor r))\rightarrow (q\lor r)$$
