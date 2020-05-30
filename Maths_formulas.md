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
&nbsp;&nbsp;$$\sigma(A)  \hspace{0.5cm}\overset{def}\Leftrightarrow \hspace{0.5cm} \{\lambda \in \mathbb{C} \hspace{0.4cm}| p(\lambda)=0\}$$

$$Def.$$ **Raggio di una matrice**
&nbsp;&nbsp;$$\rho(A) \hspace{0.5cm} \overset{def}\Leftrightarrow \hspace{0.5cm} \max_{\lambda_{i}\in \mathbb{\sigma(\lambda)}} |\lambda_i|$$

$$propr.$$ **Autovalori/Autovettori**
&nbsp;&nbsp;
 1. $$det(A) = \prod_{i=1}^n \lambda_i$$
 2. $$multgeom$$ è il numero di autovettori **lin-ind** associati ad A
 3. $$moltgeom \leq moltalg$$
 4. L'autospazio associato a $$\lambda$$ è l'informazione direzionale
 5. A non singolare $$\Rightarrow$$ $$\nexists \lambda = 0 \hspace{0.3cm} 0 \notin \sigma(A)$$ cioè se A è non singolare, il determinante è diverso da $$0$$ e quindi anche il $$det(A - \lambda I)$$ è diverso da $$0$$
6. Se la matrice A è simmetrice, allora lo spettro è un sottoinsieme di $$\mathbb R$$ che possiamo ordinare in modo crescente
7. Se $$(\lambda,x)$$ è autocoppia di $$A\in\mathbb R^{n\times n}$$ allora $$(\dfrac 1 \lambda, x)$$ autocoppia di $$A^{-1}$$
8. $$A\in\mathbb{R}^{n\times n}  \hspace{0.5cm} \mu \notin \sigma(A)  \hspace{0.5cm} (\lambda, x) autocoppia  \hspace{0.1cm}di \hspace{0.1cm} A \hspace{0.5cm}$$ &nbsp;&nbsp;$$\Rightarrow x  \hspace{0.1cm}autovettore \hspace{0.1cm} di  \hspace{0.1cm}(A-\mu I) \hspace{0.2cm}associato  \hspace{0.1cm}a \hspace{0.2cm} (\lambda -\mu)$$


$$Def.$$ **Matrice Ortogonale**
&nbsp;&nbsp; $$Q \in \mathbb{R}^{n\times n} è  \hspace{0.1cm}ortogonale \hspace{0.5cm} \overset{def}\Leftrightarrow  \hspace{0.5cm} Q^TQ=I_n=QQ^T$$
**Nota**: Le matrici ortogonali sono matrici le cui colonne sono perpendicolari fra di loro

$$Def.$$ **Autovettore sinistro**
&nbsp;&nbsp;Si dice che $$y$$ è autovettore sinistro se  $$A \in \mathbb{R}^{n\times n}$$ $$y$$ è un vettore riga $$\neq 0$$ &nbsp;t.c.&nbsp;   $$yA = \mu y$$

$$Def.$$ **Quoziente di Rayleigh**
$$\hspace{5cm}$$ $$\lambda= \dfrac{x^TAx}{x^Tx}$$

$$propr.$$ **Prodotto Scalare**
&nbsp;&nbsp; Sia $$V(+,*)$$ uno spazio vettoriale
1. $$\forall x \in V$$ $$\hspace{0.5cm}(x,x) \geq 0$$
2. $$\forall \alpha \in \mathbb{R} \hspace{0.6cm}$$ $$\forall x, y \in V \hspace{0.5cm} (x, \alpha x) = \alpha(x,y)$$
3. $$\forall x,y \in V \hspace{0.2cm}$$ $$(x,y) = (y,x)$$
4. $$\forall x, y, z \in V \hspace{0.2cm} (x, y+z) = (x,y)+(y,z)$$

$$Def.$$ **Norma indotta**
$$\forall x \in V  \hspace{0.5cm} \parallel x \parallel_{indotta} = \sqrt{(x,x)}= \hspace{0cm}\parallel x \parallel_{2}$$

$$Def.$$ **Ortogonalità**
&nbsp;&nbsp; $$u\perp v \overset{def}\Leftrightarrow \parallel u\parallel_2^2 + \parallel v \parallel_2^2 \hspace{0cm} =  \hspace{0cm}\parallel u - v \parallel_2^2$$

$$Def.$$ **Legge del Coseno**
$$\hspace{4cm}cos \theta_xy=$$$$\hspace{0.3cm}$$$$\dfrac{u^Tv}{||u||_2 \hspace{0.2cm}||v||_2}$$

$$Def.$$ **Similarità fra due matrici**
&nbsp;&nbsp; $$A, B \in \mathbb{R}^{n\times n}$$ sono simili se  $$\exists P \in \mathbb{R}^{n\times n}$$ **non singolare** t.c. $$B=P^{-1}AP$$

&nbsp;&nbsp;$$\hspace{0.5cm}propr.$$ **Similarità fra matrici**
1. Se A e B sono matrici simili, allora avranno stessi *autovalori*
2. Se A e B sono matrici simili, allora se $$x$$ è *autovettore* di B, $$Px$$ sarà autovettore di A

$$Def.$$ **Matrice Diagonalizzabile**
&nbsp;&nbsp; $$A \in \mathbb{R}^{n\times n}$$ è diagonalizzabile se possiede $$n$$ autovettori **lin-ind** t.c. $$\exists S \in \mathbb{R}^{n\times n}$$ non singolare contenente gli autovettori della matrice $$A$$ per cui:
$$\hspace{5cm} A= S^{-1}\Lambda S$$ 
doe: $$\Lambda$$ è la matrice *diagonale* contenente gli *autovalori* di A$$

$$Teorema$$ **Di Schur**
&nbsp;&nbsp; $$\forall a \in \mathbb{R}^{n\times n}$$ è simile mediante una trasformazione **ortogonale** ad una matrice *triangolare superiore* con elementi diagonali che sono gli *autovalori* di A, cioe $$t_{ii} \in \sigma (A)$$.
In altri termini:
&nbsp;&nbsp;$$\exists T \in \mathbb{R}^{n \times n} \hspace{0.1cm}triang. sup.$$ t.c $$\hspace{0cm}$$ $$\hspace{0.5cm}t_{ii} \in \sigma(A)$$
&nbsp;&nbsp;$$\exists Q \in \mathbb{R}^{n \times n} \hspace{0.1cm} ortonormale$$ t.c.$$\hspace{0.29cm} Q^{-1}=Q^T$$ le colonne di Q sono autovettori di A
$$\hspace{4cm} QAQ^T=T$$ ovvero $$A = Q^TTQ$$

**Proposizione**
&nbsp;&nbsp;Se $$A \in \mathbb{R}^{n\times n}$$, le seguenti proposizioni sono equivalenti:
1. A è non singolare
2. $$rank(A) = n$$
3. $$Range(A) = \mathbb{n}$$
4. $$Null(A) = \{0\}$$
5. le colonne di A sono **lin-ind**

**Proposizione**
&nbsp;&nbsp;Se $$A \in \mathbb{R}^{m\times n}$$  con $$k = rank(A)$$, le seguenti proposizioni sono equivalenti:
1. $$Range(A)$$ è lo spazio generato dalle colonne di base di A
2. $$dim(Range(A))=k$$
3. le k colonne di base ottenute tramite la trasformazione di A nella forma di **Echelon** sono vettori **lin-ind**
4. $$\exists$$ una sottomatrice di A quadrata di dimensione $$k \times k$$
5. Lo spazio nullo di A è un **sottoinsieme** di $$\mathbb{R}^m$$
6. $$dim(Null(A)) = n - k$$ [che corrispondono alle variabili libere (gradi di libertà)]
7.  $$dim(Null(A^T)) = n - k$$ $$\hspace{0.6cm}Null(A^T)$$ sottoinsieme di $$\mathbb{R}^n$$
8.  $$rank(A)\leq min(m,n)$$

$$Def.$$ **Spazio Range, Spazio Null**
&nbsp;&nbsp; $$Range(A) = \{y \in \mathbb{R^m} | \exists x \in \mathbb{R^n} \hspace{0.2cm}t.c.\hspace{0.2cm} Ax = y\}$$
&nbsp;&nbsp; $$Range(A^T) = \{y \in \mathbb{R^n} | \exists x \in \mathbb{R^m} \hspace{0.2cm}t.c.\hspace{0.2cm} A^Tx = y\}$$
&nbsp;&nbsp; $$Null(A) = \{x \in \mathbb{R^n} \hspace{0.2cm}t.c.\hspace{0.2cm} Ax = 0\}$$
&nbsp;&nbsp; $$Null(A) = \{x \in \mathbb{R^m} \hspace{0.2cm}t.c.\hspace{0.2cm} A^Tx = 0\}$$










