$$propr.$$ **Vettori**
$$somma$$
1.  $$x, y \in V \Rightarrow x + y \in V \hspace{2cm}$$ CHIUSURA 
2.  $$x, y, z \in V \Rightarrow (x + y)+z = x +(y + z) \in V \hspace{0.2cm}$$ ASSOCIATIVITA' 
3.  $$x, y \in V \Rightarrow x + y = y + x\in V \hspace{2cm}$$ COMMUTATIVITA' 
4.  $$\exists 0  \in V \hspace{0.7cm}\forall x \in V \Rightarrow x + 0 = 0\hspace{0.9cm}$$ ESISTENZA EL. NEUTRO 
5. $$\forall x  \in V \hspace{0.7cm} \exists -x \in V \Rightarrow x + (-x) = 0\hspace{0.8cm}$$  ESISTENZA OPPOSTO

$$prodotto$$
1. $$\forall x \in V \hspace{0.7cm}\forall \alpha \in  \mathbb{R} \Rightarrow a*x \in V$$ CHIUSURA PRODOTTO
2. $$\forall \alpha, \beta \in \mathbb{R}\hspace{0.7cm} \forall x \in V \Rightarrow  \alpha*(\beta*x) = (\alpha * \beta)*x$$  DISTRIBUTIVITA' 
3. $$\forall \alpha \in \mathbb{R} \hspace{0.7cm}\forall x, y \in \mathbb{R} \Rightarrow \alpha*(x+y) = \alpha x + \alpha y$$
4. $$\forall \alpha \in \mathbb{R} \hspace{0.7cm} \forall x, y \in V \Rightarrow (x+y)*\alpha = x\alpha + y\alpha$$
5. $$\exists 1 \in \mathbb{R} \hspace{0.7cm} \forall x \in V \Rightarrow 1*x = x \hspace{0.7cm}$$ MOLTIPLICAZIONE ESTERNA

$$Def.$$ **Trasformazione Lineare**
&nbsp;&nbsp; $$f:D \rightarrow C$$ è lineare quando $$\forall x,y \in D$$
1. $$f(x+y) = f(x) + f(y)$$
2. $$\forall \alpha \in \mathbb{R} \hspace{0.7cm}\forall x \in D \Rightarrow f(\alpha x) = \alpha f(x)$$



$$Def.$$**Prodotto fra matrici**
&nbsp;&nbsp; $$A \in \mathbb{R}^{m*n} \hspace{0.5cm} B \in \mathbb{R}^{n*p}$$
$$\hspace{3cm} A*B\overset{def}{\Leftrightarrow} \sum_{k=1}^{n} (a_{ik}*b_{kj})$$
**Nota**: Il prodotto è definito se e solo se il #colonne di A = #righe di B




$$propr.$$ **Prodotto fra matrici**
&nbsp;&nbsp; 1. $$(A + B) C = AC + BC$$
&nbsp;&nbsp; 2. $$A (B + C) = AB + AC$$
&nbsp;&nbsp; 3. $$(AB)C = A(BC)$$

$$Def.$$ **Vettori Ortogonali**
&nbsp;&nbsp;$$x, y \in \mathbb{R}^n \hspace{0.6cm} t.c.\hspace{0.6cm} x\perp y \overset{def}{\Leftrightarrow} x^{T}y=0$$


$$Def.$$ **Inversa**
$$A \in \mathbb{R}^n \hspace{0.6cm}t.c. \hspace{0.6cm}n=rank(A) \hspace{1.5cm}A^{-1} \overset{def}{\Leftrightarrow}AA^{-1}=I_n=A^{-1}A$$

$$Teorema$$ **Rouchè-Capelli**
&nbsp;&nbsp; $$A\in\mathbb{R}^{m\times n} \hspace{0.5cm} b \in \mathbb{R}^n$$
$$\hspace{1cm}\exists x\in \mathbb{R}^n \hspace{0.2cm} t.c. \hspace{0.6cm}Ax=b \hspace{0.6cm}ha \hspace{0.1cm}soluzione\hspace{0.1cm}se\hspace{0.1cm}rank(A)=rank(A|b)$$
**Inoltre**
- $$Se \hspace{0.2cm} k=n \hspace{0.7cm}\Rightarrow \exists| \hspace{0.1cm}x \hspace{0.6cm}soluzione(una \hspace{0.1cm}e \hspace{0.1cm}una \hspace{0.1cm}sola)$$
- $$Se \hspace{0.2cm} k<n \hspace{0.7cm}\Rightarrow \exists \infty^{n-k}soluzioni$$


$$Def.$$ **Determinante**
$$A\in\mathbb{R}^{n\times n}$$
$$\hspace{3cm}det(A) \overset{def}{\Leftrightarrow} \sum \sigma(p)a_{1}p_{1}a_{2}p_{2}...a_{n}{p_{n}}$$
dove: 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$$\sigma(p)$$ è: $${}+1$$ se il segno della permutazione è pari
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$${}-1$$ se il segno della permutazione è dispari
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $$p$$ è la permutazione i-esima

$$propr.$$ **Determinante**
1. $$det(AB) = det(A)\times det(B)$$
2. $$det(A^T) = det(A)$$
3. $$det(A^{-1}) = \dfrac{1}{ det(A)}$$
4. Se esiste una riga (colonna) di A con tutti zeri $$\hspace{0.5cm}\Rightarrow\hspace{0.5cm}det(A)=0$$
5. $$det(A) = 1$$
6. Lo scambio di righe scambia il segno del determinante

$$Def.$$ **Spettro di una matrice**
&nbsp;&nbsp;$$\sigma(\lambda) = \{\lambda \in \mathbb{C} \hspace{0.4cm}| p(\lambda)=0\}$$

$$Def.$$ **Raggio di una matrice**
&nbsp;&nbsp;$$\max_{\lambda_{i}\in \mathbb{\sigma(\lambda)}} |\lambda_i|$$

$$propr.$$ **Autovalori/Autovettori**
&nbsp;&nbsp;
 1. $$det(A) = \prod_{i=1}^n \lambda_i$$
 2. $$multgeom$$ è il numero di autovettori **lin-ind** associati ad A
 3. $$moltgeom \leq moltalg$$
 4. L'autospazio associato a $$\lambda$$ è l'informazione direzionale
 5. A non singolare $$\Rightarrow$$ $$\nexists \lambda = 0 \hspace{0.3cm} 0 \notin \sigma(A)$$ cioè se A è non singolare, il determinante è diverso da $$0$$ e quindi anche il $$det(A - \lambda I)$$ è diverso da $$0$$
6. Se la matrice A è simmetrice, allora lo spettro è un sottoinsieme di $$\mathbb R$$ che possiamo ordinare in modo crescente
7. Se $$(\lambda,x)$$ è autocoppia di $$A\in\mathbb R^{n\times n}$$ allora $$(\dfrac 1 \lambda, x)$$ autocoppia di $$A^{-1}$$




