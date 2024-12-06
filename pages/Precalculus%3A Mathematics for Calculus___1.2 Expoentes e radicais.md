- #seção Expoentes inteiros
  id::
- #seção Regras para trabalhar com expoentes
	- Leis dos expoentes
		- #propriedade $a^m a^n = a^{m + n}$
		  collapsed:: true
			- Para multiplicar duas potências do mesmo número, somamos os expoentes.
			- $3^2 \cdot 3^5 = 3^{2+5} = 3^7$
		- #propriedade $\dfrac{a^m}{a^n} = a^{m - n}$
		  collapsed:: true
			- Para dividir duas potências do mesmo número, subtraímos os expoentes.
			- $(a^m)^n = a^{mn}$.
		- #propriedade $(ab)^n = a^n b^n$
		  collapsed:: true
			- Para elevar um produto à uma nova potência, multiplicamos os expoentes.
			- $(3 \cdot 4)^2 = 3^2 \cdot 4^2$
		- #propriedade $\left( \dfrac{a}{b} \right)^n  = \dfrac{a^n}{b^n}$
		  collapsed:: true
			- Para elevar um quociente à uma potência, elevamos o numerador e o denominador à potência.
			- $\left( \dfrac{3}{4} \right)^2  = \dfrac{3^2}{3^2}$
		- #propriedade $\left( \dfrac{a}{b} \right)^{-n} = \left( \dfrac{b}{a} \right)$
		  collapsed:: true
			- Para elevar uma fração à uma potência, elevamos o numerador e o denominador à potência.
			- $\left( \dfrac{3}{4} \right)^{-2} = \left( \dfrac{4}{3} \right)^{2}$
		- #propriedade $\dfrac{a^{-n}}{b^{-m}} = \dfrac{b^m}{a^n}$
		  collapsed:: true
			- Para mover um número elevado à uma potência do numerador para o denominador e vice-versa, troque o sinal do expoente.
			- $\dfrac{3^{-2}}{4^{-5}} = \dfrac{4^5}{3^2}$
- #seção Notação científica
	- Ver [[Algarismos significativos]].
- #seção Radicais
	- #definição Se $n$ é um inteiro positivo, então a enésima raiz positiva de $a$ é definida da seguinte forma:
	  
	  $$
	  \sqrt[n]{a} = b \qquad \text{significa} \qquad b^n = a
	  $$
	  
	  Se $n$ é par, então necessariamente $a \geq 0$ e $b \geq 0$.
	- Propriedades dos radicais
		- #propriedade $\sqrt[n]{ab} = \sqrt[n]{a} \sqrt[n]{b}$
			- $\sqrt[3]{-8 \cdot 27} = \sqrt[3]{-8} \sqrt[3]{27} = (-2)(3) = -6$
		- #propriedade $\sqrt[n]{\dfrac{a}{b}} = \dfrac{\sqrt[n]{a}}{\sqrt[n]{b}}$
			- $\sqrt[4]{\dfrac{16}{81}} = \dfrac{\sqrt[4]{16}}{\sqrt[4]{81}} = \dfrac{2}{3}$
		- #propriedade $\sqrt[m]{\sqrt[n]{a}} = \sqrt[mn]{a}$
			- $\sqrt{\sqrt[3]{729}} = \sqrt[6]{729} = 3$
		- #propriedade $\sqrt[n]{a^n} = a \quad \text{se } n \text{ é ímpar}$
			- $\sqrt[3]{(-5)^3} = -5 \text{,} \quad \sqrt[5]{2^5} = 2$
		- #propriedade $\sqrt[n]{a^n} = \lvert a \rvert \quad \text{se } n \text{ é par}$
			- $\sqrt[4]{(-3)^4} = \lvert -3 \rvert = 3$
- #seção Expoentes e racionais
	- #definição Para qualquer expoente racional $\dfrac{m}{n}$ na sua forma mais simplificada, onde $m$ e $n$ são inteiros e $n \gt 0$, definimos:
	      
	  $$
	  a^{\frac{m}{n}} = \left(\sqrt[n]{a}\right)^m \qquad \text{ou, equivalentemente} \qquad a^{\frac{m}{n}} = \sqrt[n]{a^m}
	  $$
- #seção Racionalizando o denominador; Forma padrão
	- Freqüentemente, é útil eliminar o radical em um denominador multiplicando tanto o numerador quanto o denominador por uma expressão apropriada. Esse procedimento é chamado de racionalização do denominador. Se o denominador for da forma $\sqrt{a}$, então multiplicamos o numerador e o denominador por $\sqrt{a}$. Ao fazer isso, estamos multiplicando a quantidade dada por 1, de modo que não alteramos seu valor. Por exemplo:
	  
	  $$
	  \dfrac{1}{\sqrt{a}} = \dfrac{1}{\sqrt{a}} \cdot 1 = \dfrac{1}{\sqrt{a}} \cdot \dfrac{\sqrt{a}}{\sqrt{a}} = \dfrac{\sqrt{a}}{a}
	  $$
	  
	  Note que o denominador na última fração não contém radical. No geral, se o denominador é da forma $\sqrt[n]{a^m}$, com $m \lt n$, podemos multiplicar o numerador e o denominador por $\sqrt[n]{a^{n - m}}$ para racionalizar o denominador, considerando que:
	  
	  $$
	  \sqrt[n]{a^m} \sqrt[n]{a^{n - m}} = \sqrt[n]{a^{m + n - m}} = \sqrt[n]{a^n} = a \qquad \text{para } a \gt 0
	  $$
	- Dizemos que uma expressão fracionária cujo denominador não contém radical está na **forma padrão**.