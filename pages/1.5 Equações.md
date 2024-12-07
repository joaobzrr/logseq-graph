- Uma equação é uma declaração de que duas expressões matemáticas são iguais. Por exemplo, $3 + 5 = 8$ é uma equação. A maioria das equações que estudamos na álgebra contém variáveis, que são símbolos (normalmente letras) que assumem o lugar de números. Na equação $4x + 7 = 19$ a letra $x$ é a variável. Consideramos $x$ a incógnita na equação, e nosso objetivo é encontrar o valor de $x$ que torna a equação verdadeira. Os valores da incógnita que tornam a equação verdadeira são chamados de **soluções** ou **raízes** da equação, e o processo de encontrar as soluções é chamado de **resolver a equação**. #definição
- Duas equações com exatamente as mesmas soluções são chamadas de **equações equivalentes**. Para resolver uma equação, tentamos encontrar uma equação equivalente mais simples na qual a variável esteja isolada em um dos lados do sinal de igual. #definição
- Propriedades da igualdade
	- $A = B \iff A + C = B + C$ #propriedade
		- Adicionar o mesmo número à ambos os lados de uma equação produz uma equação equivalente.
	- $A = B \iff CA = CB \quad (C \neq 0)$ #propriedade
		- Multiplicar ambos os lados de uma equação por um número diferente de zero produz uma equação equivalente.
- Resolvendo equações lineares #seção
	- Uma **equação linear** em uma variável é uma equação equivalente a outra da forma $ax + b = 0$ onde $a$ e $b$ são números reais e $x$ é a variável. #definição
- Fórmulas: resolvendo uma variável em termos de outras #seção
- Resolvendo equações quadráticas #seção
	- Uma **equação quadrática** é uma equação da forma $ax^2 + bx + c = 0$ onde $a$, $b$ e $c$ são números reais com $a \neq 0$. #definição
	- Resolvendo equações quadráticas
		- Algumas equações quadráticas podem ser resolvidas por fatoração e usando a seguinte propriedade básica dos números reais:
		  
		  $$
		  AB = 0 \qquad \text{se e somente se} \qquad A = 0 \quad \text{ou} \quad B = 0
		  $$
		  
		  Isso significa que, se podemos fatorar o lado esquerdo de uma equação quadrática (ou qualquer outro tipo), então podemos resolve-la igualando cada um dos fatores à zero. **Esse método só funciona quando lado direito da equação é igual a zero**.
	- Resolvendo equações quadráticas simples
		- Uma equação quadrática da forma $x^2 - c = 0$, onde $c$ é uma constante positiva, é equivalente a $(x - \sqrt{c})(x + \sqrt{c}) = 0$, portanto as soluções são $x = \sqrt{c}$ e $x = -\sqrt{c}$. Frequentemente abreviamos isso como $x = \pm \sqrt{c}$.
	- Resolvendo equações quadráticas pelo método de completar quadrados
		- Para tornar $x^2 + bx$ um quadrado perfeito, adicione $\left( \dfrac{b}{2} \right)^2$, o quadrado de metade do coeficiente de $x$. Isso produz o quadrado perfeito
		  
		  $$
		  x^2 + bx + \left( \dfrac{b}{2} \right)^2 = \left( x + \dfrac{b}{2} \right)^2
		  $$
	- A fórmula quadrática
		- As soluções da equação quadrática geral $ax^2 + bx + c = 0$, onde $a \neq 0$, são
		  
		  $$
		  x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}
		  $$
	- Discriminante #definição
		- O **discriminante** da equação quadrática geral $ax^2 + bx + c = 0 \enspace (a \neq 0)$ é $D = b^2 - 4ac$.
		- Se $D > 0$, então a equação tem duas raízes reais distintas.
		- Se $D = 0$, então a equação tem exatamente uma raiz real.
		- Se $D < 0$, então a equação não tem raiz real.
- Outros tipos de equações #seção
	- Soluções extrínsecas
		- Quando resolvemos uma equação, podemos acabar com uma ou mais **soluções extrínsecas**, ou seja, soluções possíveis que não satisfazem a equação original. No caso de equações envolvendo expressões fracionárias, soluções possíveis podem ser indefinidas na equação original e, portanto, são soluções extrínsecas. No caso de soluções envolvendo radicais, soluções extrínsecas podem ser introduzidas quando elevamos cada lado da equação ao quadrado porque a operação de elevar ao quadrado pode tornar verdadeira uma equação falsa. Por exemplo, $-1 \neq 1$, mas $(-1)^2 = 1^2$. Portanto, a equação elevada ao quadrado pode ser verdadeira para mais valores da variável do que a equação original. #definição
	- Equações de tipo quadrático
		- Uma equação da forma $aW^2 + bW + c = 0$, onde $W$ é uma expressão algébrica, é uma **equação de tipo quadrático**. Resolvemos equações de tipo quadrático substituindo a expressão algébrica por uma nova variável. #definição
	- Equações de valor absoluto
		- Ao resolver equações de valor absoluto, usamos a seguinte propriedade:
		  
		  $$
		  \lvert X \rvert = C \qquad \text{é equivalente a} \qquad X = C \quad \text{ou} \quad X = -C
		  $$