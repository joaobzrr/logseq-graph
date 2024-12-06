- Números reais #seção
	- Convertendo uma dízima periódica em uma razão entre dois inteiros
		- Uma dízima periódica, como $x = 3.5474747 \text{...}$ é um número racional. Para convertê-la em uma razão entre dois inteiros, escrevemos:
		  
		   $$
		   \begin{equation*}
		   \begin{split}
		   1000x &= 3547.47474747... \\
		   10x &= 35.47474747... \\
		   \hline
		   990x &= 3512.0 \\ 
		   \end{split}
		   \end{equation*}
		   $$
		  
		  Assim, $x = 3512$ (A ideia é multiplicar $x$ por potências apropriadas de 10 e depois subtrair para eliminar a parte periódica.)
- Propriedades dos números reais #seção
	- $a + b = b + a$ #propriedade
		- $7 + 3 = 3 + 7$
		- Propriedade comutativa da adição. Quando somamos dois números, a ordem não importa.
	- $ab = ba$ #propriedade
		- $3 \cdot 5 = 5 \cdot 3$
		- Propriedade comutativa da multiplicação. Quando somamos dois números, a ordem não importa.
	- $(a + b) + c = a + (b + c)$ #propriedade
		- $(2 + 4) + 7 = 2 + (4 + 7)$
		- Propriedade associativa da adição. Quando adicionamos três números, não importa qual adicionamos primeiro.
	- $(ab)c = a(bc)$ #propriedade
		- $(3 \cdot 7) \cdot 5 = 3 \cdot (7 \cdot 5)$
		- Propriedade associativa da multiplicação. Quando multiplicamos três números, não importa qual adicionamos primeiro.
	- $a(b + c) = ab + ac$ #propriedade
		- $2 \cdot (3 + 5) = 2 \cdot 3 + 2 \cdot 5$
		- Propriedade distributiva da multiplicação. Quando multiplicamos um número pela soma de dois números, obtemos o mesmo resultado que obteríamos se multiplicássemos o número por cada um dos termos separadamente e, em seguida, somássemos os resultados.
- Adição e subtração #seção
- Multiplicação e divisão #seção
	- Menor denominador comum
		- Quando somamos frações com denominadores diferentes, primeiro as reescrevemos de forma que tenham o menor denominador comum possível (geralmente menor que o produto dos denominadores).
		- Por exemplo, considere a seguinte expressão:
		  
		  $$
		  \dfrac{5}{36} + \dfrac{7}{120}
		  $$
		  
		  Fatorando cada denominador em fatores primos temos
		  
		  $$
		  36 = 2^2 \cdot 3^2 \qquad e \qquad 120 = 2^3 \cdot 3 \cdot 5
		  $$
		  
		  Nós encontramos o menor denominador comum (MDC) formando o produto de todos os fatores primos que ocorrem nessas fatorações usando a maior potência de cada fator primo. Portanto, o MDC é igual à
		  
		  $$
		  2^3 \cdot 3 ^ 2\cdot 5 = 360
		  $$
		  
		  e a soma acima pode ser calculada da seguinte forma:
		  
		  $$
		  \dfrac{5}{36} + \dfrac{7}{120} = \dfrac{5 \cdot 10}{36 \cdot 10} + \dfrac{7 \cdot 3}{120 \cdot 3} = \dfrac{50}{360} + \dfrac{21}{360} = \dfrac{71}{360}
		  $$
- A reta real #seção
- Conjuntos e intervalos #seção
- Valor absoluto e distância #seção
	- Se $a$ é um número real, então o *valor absoluto* de $a$ é
	  
	  $$
	  \begin{equation*}
	  \mid a \mid \, =
	  \left\{
	  \begin{array}{lr}
	  a & \text{if } a \geq 0 \\
	  -a & \text{if } a \lt 0
	  \end{array}
	  \right\}
	  \end{equation*}
	  $$
	  
	  #definição
	- Propriedades do valor absoluto
		- O valor absoluto de um número é sempre positivo ou zero. #propriedade
			- $\lvert a \rvert \geq 0$
			- $\lvert -3 \rvert = 3 \geq 0$
		- Um número e o seu negativo tem o mesmo valor absoluto. #propriedade
			- $\lvert a \rvert = \lvert -a \rvert$
			- $\lvert 5 \rvert = \lvert -5 \rvert$
		- O valor absoluto de um produto é o produto dos valores absolutos. #propriedade
			- $\lvert ab \rvert = \lvert a \rvert \lvert b \rvert$
			- $\lvert -2 \cdot 5 \rvert = \lvert -2 \rvert \lvert 5 \rvert$
		- O valor absoluto de um quociente é o quociente dos valores absolutos. #propriedade
			- $\Big\lvert \dfrac{a}{b} \Big\rvert = \dfrac{\lvert a \rvert}{\lvert b \rvert}$
			- $\Big\lvert \dfrac{12}{-3} \Big\rvert = \dfrac{\lvert 12 \rvert}{\lvert -3 \rvert}$
		- Desigualdade triangular. #propriedade
			- $\lvert a + b \rvert \leq \lvert a \rvert + \lvert b \rvert$
			- $\lvert -3 + 5 \rvert \leq \lvert -3 \rvert + \lvert 5\rvert$