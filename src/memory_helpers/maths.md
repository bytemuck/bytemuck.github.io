Égalité entre deux vecteurs (principe de translation): 
\\[ \overrightarrow u = \overrightarrow v \iff \Vert \overrightarrow u \Vert = \Vert \overrightarrow v \Vert \\]

Forme polaire: 
\\[ \overrightarrow u = \Vert \overrightarrow u \Vert,\theta_\overrightarrow u \\]

Forme matricielle (ou algébrique): 
\\[ \overrightarrow u = [\begin{array}{rr}u_x & u_y\end{array}] \\]

Passer de la forme matricielle à la forme polaire: 
\\[ \Vert \overrightarrow u \Vert = \sqrt{u_x^2 + u_y^2} \\]
\\[ \theta_\overrightarrow u = \begin{cases} \arctan\frac{u_y}{u_x} + \phi & \text{si }  u_x \neq 0 
                                         \\\ \frac{\pi}{2} \text{ ou } 90^\circ & \text{si } u_x = 0 \text{ et } u_y \gt 0
                                         \\\ \frac{3\pi}{2} \text{ ou } 270^\circ & \text{si } u_x = 0 \text{ et } u_y \lt 0 
                               \end{cases}\\]

Passer de la forme polaire à la forme matricielle: 
\\[ u_x = \Vert \overrightarrow u \Vert \times \cos \theta_\overrightarrow u \\]
\\[ u_y = \Vert \overrightarrow u \Vert \times \sin \theta_\overrightarrow u \\]

Opérations sur les vecteurs:
- Propriétés de l'addition dans les \\( \mathbb{R},+ \\)
\\[ \begin{array}{rr} 
        x + y \in \mathbb{R}        & \text{fermeture}
    \\\ x + y = y + x               & \text{commutativité}
    \\\ x + (y + z) = (x + y) + z   & \text{associativité}
    \\\ x + 0 = x                   & \text{0 est l'élément neutre}
    \\\ x + (-x) = 0                & -x \text{ est l'inverse additif} \end{array}
\\]

- Propriétés de la multiplication dans les \\( \mathbb{R},\cdot \ \\)
\\[ \begin{array}{rr} 
        x \cdot y \in \mathbb{R}                    & \text{fermeture}
    \\\ x \cdot y = y \cdot x                       & \text{commutativité}
    \\\ x \cdot (y \cdot z) = (x \cdot y) \cdot z   & \text{associativité}
    \\\ x \cdot 1 = x                               & \text{1 est l'élément neutre}
    \\\ \vee x \in \mathbb{R^*}, x \cdot (\frac{1}{x}) = 1                                & \frac{1}{x} \text{ est l'inverse multiplicatif si } x \neq 0 \end{array}
\\]

- Autres propriétés dans les \\( \mathbb{R},+,\cdot \ \\)
\\[ \begin{array}{rr} 
        x \cdot 0 = 0                               & \text{0 est l'élément absorbant}
    \\\ x \cdot (y + z) = x \cdot y + x \cdot z     & \text{distributativité de la multiplication sur l'addition} \end{array}
\\]

Addition et soustraction algébrique (avec composantes): \
\\[\text{Soit} \overrightarrow v = [\begin{array}{rr}v_x & v_y\end{array}] \text{ et} \overrightarrow u = [\begin{array}{rr}u_x & u_y\end{array}], \text{ alors} \\] \\[ \overrightarrow v \pm \overrightarrow v = [\begin{array}{rr}v_x \pm u_x & v_y \pm u_y\end{array}] \\]

- Propriétés de l'addition sur \\( \mathbb{R^2},\+ \ \\)
\\[ \begin{array}{rr} 
        \overrightarrow u + \overrightarrow v \text{ est un vecteur}                                                                & \text{fermeture}
    \\\ \overrightarrow u + \overrightarrow v = \overrightarrow v + \overrightarrow u                                               & \text{commutativité de + dans } \mathbb{R^2}
    \\\ \overrightarrow u + (\overrightarrow v + \overrightarrow w) = (\overrightarrow u + \overrightarrow v) + \overrightarrow w   & \text{associativité de + dans } \mathbb{R^2}
    \\\ \overrightarrow u + \overrightarrow 0 = \overrightarrow 0 + \overrightarrow u = \overrightarrow u                           & \overrightarrow 0 \text{ est élément neutre de +}
    \\\ \overrightarrow u + (-\overrightarrow u)                                                                                   & \text{inverse additif, } -\overrightarrow u \end{array}
\\]