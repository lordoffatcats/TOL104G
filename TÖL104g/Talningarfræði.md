# Talningarfræði (*counting*)
## Margföldunarregla
Ef verk er framkvæmt í tveimur skrefum $v_{1}$ og $v_{2}$, og $v_{1}$ hefur $n_{1}$ leiðir og $v_{2}$ hefur $n_2$ leiðir, þá er heildarfjöldi leiða til að framkvæma verkið: $n_{1}\cdot n_{2}$.
<!-- https://q.uiver.app/#q=WzAsNSxbMiwwLCJcXGJ1bGxldCBWXzEiXSxbNCwwLCJcXGJ1bGxldCBWXzIiXSxbMywxLCJIZWlsZGFyXFwgbGVpw7BpcjogbV8xIFxcY2RvdCBtXzIiXSxbNywwXSxbMCwwXSxbMCwxLCJtXzFcXCBsZWnDsGlyIl0sWzEsMywibV8yXFwgbGVpw7BpciJdLFs0LDBdXQ== --> <iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsNSxbMiwwLCJcXGJ1bGxldCBWXzEiXSxbNCwwLCJcXGJ1bGxldCBWXzIiXSxbMywxLCJIZWlsZGFyXFwgbGVpw7BpcjogbV8xIFxcY2RvdCBtXzIiXSxbNywwXSxbMCwwXSxbMCwxLCJtXzFcXCBsZWnDsGlyIl0sWzEsMywibV8yXFwgbGVpw7BpciJdLFs0LDBdXQ==&embed" width="600" height="300" style="border-radius: 8px; border: none;"></iframe>

## Samlagningarregla
Ef verk getur farið  annaðhvort í skref $v_{1}$ með $n_{1}$ leiðir, eða $v_{2}$ með $n_{2}$ leiðir, þá er heildarfjöldi leiða til að framkvæma verkið: $n_{1}+n_{2}$.
<!-- https://q.uiver.app/#q=WzAsNixbNCwwLCJcXGJ1bGxldFxcIFZfMVxcIChuXzFcXCBsZWnDsGlyKSJdLFs0LDIsIlxcYnVsbGV0IFZfMlxcIChuXzJcXCBsZWnDsGlyKSJdLFsyLDFdLFswLDFdLFs2LDFdLFs4LDFdLFsyLDBdLFsyLDFdLFszLDJdLFswLDRdLFsxLDRdLFs0LDUsIm5fMStuXzJcXCBsZWnDsGlyIl1d --> <iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsNixbNCwwLCJcXGJ1bGxldFxcIFZfMVxcIChuXzFcXCBsZWnDsGlyKSJdLFs0LDIsIlxcYnVsbGV0IFZfMlxcIChuXzJcXCBsZWnDsGlyKSJdLFsyLDFdLFswLDFdLFs2LDFdLFs4LDFdLFsyLDBdLFsyLDFdLFszLDJdLFswLDRdLFsxLDRdLFs0LDUsIm5fMStuXzJcXCBsZWnDsGlyIl1d&embed" width="600" height="300" style="border-radius: 8px; border: none;"></iframe>


## Frádráttarregla í mengjum
Heildarfjöldi staka í mengjum $A$ og $B$ er: $|A|+|b|-|A \cap B|$.
<!-- https://q.uiver.app/#q=WzAsNixbMywwLCJBIl0sWzEsMV0sWzMsMiwiQiJdLFs1LDFdLFs2LDFdLFswLDFdLFsxLDBdLFsxLDJdLFswLDNdLFsyLDNdLFszLDRdLFs1LDFdXQ== --> <iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsNixbMywwLCJBIl0sWzEsMV0sWzMsMiwiQiJdLFs1LDFdLFs2LDFdLFswLDFdLFsxLDBdLFsxLDJdLFswLDNdLFsyLDNdLFszLDRdLFs1LDFdXQ==&embed" width="600" height="300" style="border-radius: 8px; border: none;"></iframe>
Heildarfjöldi staka í mengjum $A$, $B$ og $C$ er: $|A|+|B|+|C| - |A\cap B| - |A\cap C| - |B\cap C|+|A\cap B\cap C|$.


## Deilingarregla
Ef mengi $A=A_{1}\cup A_{2}\cup\dots\cup A_{n}$, og öll $A_{i}$-in eru sundurlæg ($\forall i\forall j (A_{i}\cap A_{j}=\emptyset)$), of $|A_{i}|=d \text{ fyrir }\forall i$. Þá er $n=\frac{|A|}{d}$.