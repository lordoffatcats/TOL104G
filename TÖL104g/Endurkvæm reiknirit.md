# Endurkvæ reiknirit (*recursive algorithms*)
## Dæmi um reiknirit $n!$:
### Með hefðbundnari lykkju:
```
fall hróp(n):
	h<-1
	fyrir k=2,...,n:
		h<-h*k
	Skila h
```

### Með endurkvæmni:
```
fall hróp(n):
	Ef n=1:
		Skila 1
	Annars:
		Skila hróp(n-1)*n
```
Taka má eftir því að endurkvæma reikniritið kallar á sjálft sig *svipað og þrepun*.

## Dæmi tvinnröðun (*merge sort*)
```
fall tvinnraða(L=a1,a2,...,an):
	Ef n=1:
		Skila L
	Annars:
		m<-floor(n/2)
		L1<-a1,...am
		L2<-am+1,...an
		Skila tvinna(tvinnraða(L1),tvinnraða(L2))

#tvinnar saman listana A og B.
fall tvinna(A, B):
	L<-Tómur listi
	lykkja þar til bæði A og B eru tómir:
		Ef A er tómur þá L<-L+B
		Annars Ef B er tómur þá L<-L+A
		Annars Ef a1 <=b1 þá:
			L<-L+a1
			taka a1 úr A
		Annars:
			L<-L+b1
			taka b1 úr B
	Skila L
```

## Helmingunarleit
Erum með raðaðan lista, leitum í miðjum listanum og tékkum hvort talan sé minni eða stærri en miðjan á listanum
```
fall helming(x, L=a1,...an)
	m<-floor(=n/2)
	Ef x==am:
		Skila m
		
	L1<-a1...am
	L2<-am+1...an
	Ef x <= am
		skila helming(L1)
	Annars
		Skila helming(L2)
```

## Quicksort
```
fall quick(L=a1,...,an):
	veljum am af handhófi
	L2<-tómur listi
	L3<-tómur listi
	Ef lengd L = 1:
		Skila L
	fyrir ai í l:
		Ef ai <=am:
			L2<- L2+ai
		Annars:
			L3<-L3+ai
	Skila quick(L2)+quick(L3)
```