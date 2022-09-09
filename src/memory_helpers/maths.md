**Égalité entre deux vecteurs (principe de translation)**
\\[ \overrightarrow u = \overrightarrow v \iff \Vert \overrightarrow u \Vert = \Vert \overrightarrow v \Vert \\]

**Forme polaire**
\\[ \overrightarrow u = \Vert \overrightarrow u \Vert,\theta_\overrightarrow u \\]

**Forme matricielle (ou algébrique)**
\\[ \overrightarrow u = [\begin{array}{cc}u_x & u_y\end{array}] \\]

**Passer de la forme matricielle à la forme polaire**
\\[ \Vert \overrightarrow u \Vert = \sqrt{u_x^2 + u_y^2} \\]
\\[ \theta_\overrightarrow u = \begin{cases} \arctan\frac{u_y}{u_x} + \phi & \text{si }  u_x \neq 0 
                                         \\\ \frac{\pi}{2} \text{ ou } 90^\circ & \text{si } u_x = 0 \text{ et } u_y \gt 0
                                         \\\ \frac{3\pi}{2} \text{ ou } 270^\circ & \text{si } u_x = 0 \text{ et } u_y \lt 0 
                               \end{cases}\\]

**Passer de la forme polaire à la forme matricielle**
\\[ u_x = \Vert \overrightarrow u \Vert \times \cos \theta_\overrightarrow u \\]
\\[ u_y = \Vert \overrightarrow u \Vert \times \sin \theta_\overrightarrow u \\]

**Opérations sur les vecteurs**
- Propriétés de l'addition dans les \\( \mathbb{R},+ \\)
\\[ \begin{array}{rl} 
        x + y \in \mathbb{R}        & \text{fermeture}
    \\\ x + y = y + x               & \text{commutativité}
    \\\ x + (y + z) = (x + y) + z   & \text{associativité}
    \\\ x + 0 = x                   & \text{0 est l'élément neutre}
    \\\ x + (-x) = 0                & -x \text{ est l'inverse additif} \end{array}
\\]

- Propriétés de la multiplication dans les \\( \mathbb{R},\cdot \ \\)
\\[ \begin{array}{rl} 
        x \cdot y \in \mathbb{R}                    & \text{fermeture}
    \\\ x \cdot y = y \cdot x                       & \text{commutativité}
    \\\ x \cdot (y \cdot z) = (x \cdot y) \cdot z   & \text{associativité}
    \\\ x \cdot 1 = x                               & \text{1 est l'élément neutre}
    \\\ \vee x \in \mathbb{R^*}, x \cdot (\frac{1}{x}) = 1                                & \frac{1}{x} \text{ est l'inverse multiplicatif si } x \neq 0 \end{array}
\\]

- Autres propriétés dans les \\( \mathbb{R},+,\cdot \ \\)
\\[ \begin{array}{rl} 
        x \cdot 0 = 0                               & \text{0 est l'élément absorbant}
    \\\ x \cdot (y + z) = x \cdot y + x \cdot z     & \text{distributativité de la multiplication sur l'addition} \end{array}
\\]

**Addition et soustraction algébrique (avec composantes)**
\\[ \text{Soit } \overrightarrow v = [\begin{array}{rr}v_x & v_y\end{array}] \text{ et} \overrightarrow u = [\begin{array}{rr}u_x & u_y\end{array}], \text{ alors} \\] \\[ \overrightarrow v \pm \overrightarrow v = [\begin{array}{rr}v_x \pm u_x & v_y \pm u_y\end{array}] \\]

- Propriétés de l'addition sur \\( \mathbb{R^2},\+ \ \\)
\\[ \begin{array}{rl} 
        \overrightarrow u + \overrightarrow v \text{ est un vecteur}                                                                & \text{fermeture}
    \\\ \overrightarrow u + \overrightarrow v = \overrightarrow v + \overrightarrow u                                               & \text{commutativité de + dans } \mathbb{R^2}
    \\\ \overrightarrow u + (\overrightarrow v + \overrightarrow w) = (\overrightarrow u + \overrightarrow v) + \overrightarrow w   & \text{associativité de + dans } \mathbb{R^2}
    \\\ \overrightarrow u + \overrightarrow 0 = \overrightarrow 0 + \overrightarrow u = \overrightarrow u                           & \overrightarrow 0 \text{ est élément neutre de +}
    \\\ \overrightarrow u + (-\overrightarrow u)                                                                                    & \text{inverse additif, } -\overrightarrow u \end{array}
\\]

**Relation de Chasles**
\\[ \text{Soient } A \text{, } B \text{ et } C \text{ des points du plan, alors } \\] \\[ \overrightarrow {AB} + \overrightarrow {BC} = \overrightarrow {AC} \\] 

**Multiplication par un scalaire**
\\[ \text{Soit } k \in \mathbb{R} \text{ et } \overrightarrow u \text{ un vecteur, alors la } \textbf{ multiplication par un scalaire } k \textbf{ d'un vecteur } \overrightarrow u \text{ est: }  \\] \\[ k \cdot \overrightarrow u = [\begin{array}{rl}k \cdot u_x & k \cdot u_y\end{array}] \\] 

**Propriété de la multiplication par un scalaire**
\\[ \text{Soit } k \in \mathbb{R} \text{ et } \overrightarrow u \text{ un vecteur, alors } \\]
\\[ \begin{array}{c} 
        k \cdot \overrightarrow u \text{ est un vecteur;}
    \\\ \Vert k \cdot \overrightarrow u \Vert =  \vert k \vert \cdot \Vert \overrightarrow u \Vert \text{;}
    \\\ \text{le vecteur } k \cdot \overrightarrow u \text{ est parallèle au vecteur } \overrightarrow u \text{;}
    \\\ \text{les vecteurs} \overrightarrow u \text{ et } k \cdot \overrightarrow u \text{ ont la même direction si } k \gt 0 \text{ et sont de direction contraire si } k \lt 0 \text{;}
    \\\ 0 \cdot \overrightarrow u = \overrightarrow 0 \text{.}
    \end{array}
\\]

**Théorème du parallélisme**
\\[ \text{Soit } \overrightarrow u \text{,} \overrightarrow v \in \mathbb{R^2} \text{ et } \overrightarrow u \text{,} \overrightarrow v \neq \overrightarrow 0 \text{, alors } \\] 
\\[ \overrightarrow u \parallel \overrightarrow v \iff \text{ tel que } k \cdot \overrightarrow u = \overrightarrow v \text{ ou } k \cdot \overrightarrow v = \overrightarrow u \text{.}\\] 

**Autres propriété de la multiplication par un scalaire**
\\[ \text{Soit } k \in \mathbb{R} \text{ et } \overrightarrow u \text{ un vecteur, alors } \\]
\\[ \begin{array}{c} 
        1 \cdot \overrightarrow u = \overrightarrow u \text{;}
    \\\ a \cdot \overrightarrow 0 = \overrightarrow 0 \text{;}
    \\\ (ab)\overrightarrow u = a(b\overrightarrow u) \text{;}
    \\\ (a + b)\overrightarrow u = a\overrightarrow u + b\overrightarrow u \text{;}
    \\\ a(\overrightarrow u + \overrightarrow v) = a\overrightarrow u + a\overrightarrow v \text{;}
    \\\ \text{si } \overrightarrow u \neq \overrightarrow 0 \text{, alors le vecteur } \frac{1}{\Vert \overrightarrow u \Vert} \cdot \overrightarrow u \text{ est un vecteur unitaire.}
    \end{array}
\\]

**Combinaison linéaire**
\\[ \text{Une } \textbf{combinaison linéaire } \text{de } n \text{ vecteurs } \overrightarrow u_1 \text{,} \overrightarrow u_2 \text{,...,} \overrightarrow u_n \text{est une expression de la forme} \\]
\\[ a_1 \overrightarrow u_1 + a_2\overrightarrow u_2 + \text{...} + a_n \overrightarrow u_n \in \mathbb{R} \\]

**Produit scalaire**
\\[ \text{Soit } \overrightarrow u \text{ et } \overrightarrow v \text{ deux vecteurs du plan. Le } \textbf{produit scalaire de } \overrightarrow u \textbf{ par } \overrightarrow v \text{, noté } \overrightarrow u \cdot \overrightarrow v \text{, est donné par} \\]
\\[ \begin{array}{rcl} 
        \overrightarrow u \cdot \overrightarrow v & = & \Vert \overrightarrow u \Vert \cdot \Vert \overrightarrow v \Vert \cos{\theta_{\overrightarrow u,\overrightarrow v}} & \text{, définition polaire}
    \\\ & = & \overrightarrow u_x \overrightarrow v_x + \overrightarrow u_y \overrightarrow v_y & \text{, définition algébrique}
    \end{array}
\\]

- Propriétés
\\[ \begin{array}{rl} 
        \overrightarrow u \cdot \overrightarrow v \in \mathbb{R} & \text{non-fermeture} 
    \\\ \overrightarrow u \cdot \overrightarrow v = \overrightarrow v \cdot \overrightarrow u & \text{commutativitié de } \cdot \text{ sur } + \text{dans} \mathbb{R^2}
    \\\ \overrightarrow u \cdot (\overrightarrow v + \overrightarrow w) = \overrightarrow u \cdot \overrightarrow v + \overrightarrow u \cdot \overrightarrow w & \text{commutativitié de } \cdot \text{ sur } + \text{dans} \mathbb{R^2}
    \\\ a (\overrightarrow u \cdot \overrightarrow v) = (a \overrightarrow u) \cdot \overrightarrow v = \overrightarrow u \cdot (a\overrightarrow v) & \text{commutativitié de } \cdot \text{ sur } + \text{dans} \mathbb{R^2}
    \end{array}
\\]

**Autres propriétées**
\\[ \begin{array}{c} 
        \overrightarrow u \cdot \overrightarrow u = {\Vert \overrightarrow u \Vert}^2 
    \\\ \text{si } \overrightarrow u \neq \overrightarrow 0 \text{ et } \overrightarrow v \neq \overrightarrow 0 \text{, alors } \overrightarrow u \text{ et } \overrightarrow v \text{ sont perpendiculaires si } \overrightarrow u \cdot \overrightarrow v = 0 \text{.}
    \end{array}
\\]

**Angle entre deux vecteurs**\
L'angle entre deux vecteurs non-nuls du plan \\( \overrightarrow u \\) et \\( \overrightarrow v \\), noté \\( \theta(\overrightarrow u\text{,}\overrightarrow v) \\) par 
\\[ \theta(\overrightarrow u\text{,}\overrightarrow v) = \arccos{\frac{\overrightarrow u \cdot \overrightarrow v}{\Vert\overrightarrow u\Vert\cdot\Vert\overrightarrow v\Vert}} \text{.} \\]

**Projection orthogonale**\
La projection orthogonale \\( \overrightarrow u_\overrightarrow v \\) est l'ombre d'un vecteur \\( \overrightarrow u \\) sur un vecteur \\( \overrightarrow v \\)

\\[ \overrightarrow u_\overrightarrow v = \frac{\overrightarrow u \cdot \overrightarrow v}{{\Vert \overrightarrow v \Vert}^2} \cdot \overrightarrow v \text{.} \\]

**Barycentre**
Le point \\( P \\) est le barycentre d'un ensemble de \\( n \\) points \\( P_1,P_2,...,P_n \\) si
\\[ \overrightarrow PP_1 + \overrightarrow PP_2 + ... + \overrightarrow PP_n = \overrightarrow 0 \\]