# $$\LaTeX \text{ in Obsidian}$$
# Basics

Inline maths can be inserted using single dollar signs `$ (content) $`

Lorem ipsum $f(x) = 2x + 1$ dolor sit amet.

Math blocks can be inserted using double dollar signs `$$ (content) $$`

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

Obsidian formatting still applies to math blocks, and the css property is `.math {}`

# Greek alphabet

- $A$ $\alpha$ (Alpha)
- $B$ $\beta$ (Beta)
- $\Gamma$ $\gamma$ (Gamma)
- $\Delta$ $\delta$ (Delta)
- $E$ $\epsilon$ (Epsilon)
- $Z$ $\zeta$ (Zeta)
- $H$ $\eta$ (Eta)
- $\Theta$ $\theta$ (Theta)
- $I$ $\iota$ (Iota)
- $K$ $\kappa$ (Kappa)
- $\Lambda$ $\lambda$ (Lambda)
- $M$ $\mu$ (Mu)
- $N$ $\nu$ (Nu) 
- $\Xi$ $\xi$ (Xi)
- $O$ $\omicron$ (Omicron)
- $\Pi$ $\pi$ (Pi)
- $R$ $\rho$ (Rho)
- $\Sigma$ $\sigma$ / $\varsigma$ (Sigma)
- $T$ $\tau$ (Tau)
- $\Upsilon$ $\upsilon$ (Upsilon)
- $\Phi$ $\phi$ (Phi)
- $X$ $\chi$ (Chi)
- $\Psi$ $\psi$ (Psi)
- $\Omega$ $\omega$ (Omega)

# Operators

$$\cos(2 \theta) = cos^2\theta - sin^2\theta$$

$$\lim\limits_{x \to \infty} \exp(-x) = 0$$

# Powers and indices

$$k_{n+1} = n^2 + k_n^2 - k_{n-1}$$

# Fractions and binomials

$$\frac{n!}{k!(n-k)!} = \binom{n}{k}$$

$$\frac{\frac{1}{x}+\frac{1}{y}}{y-z}$$

For mini inline fractions: $^3/_7$
# Roots

$$\sqrt{\frac{a}{b}}$$

$$\sqrt[n]{1+x+x^2+x^3+\dots+x^n}$$

# Sums and integrals

$$\sum_{i=1}^{10} t_i$$

$$\int_0^\infty \mathrm{e}^{-x}\,\mathrm{d}x$$

## Other "big" commands

$$\sum \bigoplus \bigcup \bigsqcup \int \iiint \prod \bigotimes \bigcap \bigvee \oint \iiiint \coprod \bigodot \biguplus \bigwedge \iint \idotsint$$

## Multiple lined limits

$$\sum_{\substack{0<i<m \\ 0<j<n}} P(i,j)$$

## Labelled integrations

$$\int\limits_a^b$$

# Brackets, braces and delimiters

$$( a ), [ b ], \{ c \}, | d |, \| e \|,
\langle f \rangle, \lfloor g \rfloor,
\lceil h \rceil, \ulcorner i \urcorner,
/ j \backslash$$

# Matrices and arrays

$$ \begin{matrix} a & b & c \\ d & e & f \\ g & h & i \end{matrix} $$

$$\begin{array}{c|c}
  1 & 2 \\ 
  \hline
  3 & 4
 \end{array}$$

# Text in equations

$$
\text{A man goes to the store and buys } 5^3 \text{ apples, then takes away } 5 \text{.}
$$

# Accents
Primes: $a'$, $a''$, $a'''$ etc.
Hat: $\hat{a}$
Bar: $\bar{a}$
Grave: $\grave{a}$
Acute: $\acute{a}$
Dot: $\dot{a}$
Double dot: $\ddot{a}$
Not: $\not{a}$
Math ring: $\mathring{a}$
Check: $\check{a}$
Breve: $\breve{a}$
Vectors: $\vec{a}$
Tilde: $\tilde{a}$
Underline $\underline{a}$

Over arrows: $\overrightarrow{AB}$, $\overleftarrow{AB}$
Overlines: $\overline{abc}$
Wide hats: $\widehat{ABC}$
Wide tildes: $\widetilde{ABC}$
# Colors

$$k = {\color{orange}x} \mathbin{\color{cyan}-} 2$$

# Special characters

Multiplication: $\times$ (or $\cdot$)
Division: $\div$
Plus minus: $\pm$
Minus plus: $\mp$
Equivalence: $\equiv$
Approx. equals: $\approx$
Not equals: $\neq$

Dots: $\dots$
Vertical dots: $\vdots$
Diagonal dots: $\ddots$
Big dot: $\bullet$

Less than, greater than: $<$ $>$
Double greater / less than: $\ll$ $\gg$
Less than or equal, greater than or equal: $\leq$, $\geq$

Parallel: $\parallel$
Not parallel: $\nparallel$
Perpendicular: $\perp$
Angle: $\angle$
Measured angle: $\measuredangle$

Therefore: $\therefore$
Because: $\because$
Left arrow: $\leftarrow$
Right arrow: $\rightarrow$
Left right arrow: $\leftrightarrow$

Infinity: $\infty$
Pi: $\pi$