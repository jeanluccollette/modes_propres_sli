# Modes propres d'un système linéaire invariant

## Pendules couplés

On considère $N$ barres horizontales de moment d'inertie $J$, suspendues à un fil de torsion de raideur $K$ et régulièrerement espacées sur un axe vertical. Les deux extrémités du fil sont fixées. L'angle de la barre numéro $n$ avec $0\leq n \leq N-1$ est noté $\theta_n$, de sorte que $\theta_n=0$ corresponde à la position d'équilibre. Le couple qui s'exerce sur cette barre est $K(\theta_{n-1}-\theta_n) + K(\theta_{n+1}-\theta_n)=K(\theta_{n-1}-2\theta_n+\theta_{n+1})$, avec $\theta_{-1}=\theta_N=0$.

Le principe fondamental de la dynamique appliqué à la barre $n$ donne alors

$$\dfrac{d^2\theta_n}{dt^2}=\dfrac{K}{J}(\theta_{n-1}-2\theta_n+\theta_{n+1})$$

Le vecteur d'état choisi est

$$Y=\left[\theta_0,\dots, \theta_{N-1}, \dfrac{d\theta_0}{dt},\dots,\dfrac{\theta_{N-1}}{dt}\right]^T$$

Le régime libre est déterminé par l'équation dynamique

$$\dfrac{dY}{dt}=AY$$

avec

$$A=
\pmatrix{
0_{N \times N}&I_N\\
\dfrac{K}{J}
\pmatrix{
-2&1&0&\dots&0&0&0\\
1&-2&1&\dots&0&0&0\\
\vdots&\vdots&\vdots&\vdots&\vdots&\vdots&\vdots\\
0&0&0&\dots&1&-2&1\\
0&0&0&\dots&0&1&-2
}
&0_{N \times N}
}$$

Il apparaît que les valeurs propres de la matrice A sont toutes imaginaires pures. Elles figurent par paire $j\omega_k$ et $-j\omega_k$, associées à des vecteurs propres conjugués $p_k$ et $p_k^*$.

Avec une condition initiale de la forme $Y_0=\Re(Gp_k)$, avec $G$ complexe, la solution sera associée à un seul mode

$$Y=e^{At}Y_0=e^{At}\Re(Gp_k)=\Re(Gp_ke^{j\omega_kt})$$

Les 3 exemples figurant dans la rubrique **Illustrations** montrent les simulations réalisées avec des conditions initiales qui correspondent aux modes sélectionnés. Avec la condition initiale imposée dans l'exemple **Impulsion initiale**, on retrouve un mélange de tous les modes identifiés.
 
## Illustrations

### Exemple 1

![puls_1](https://github.com/user-attachments/assets/67026d3f-120c-4ff4-892d-b11f21a61507)

![peri_1](https://github.com/user-attachments/assets/75e62acc-fad3-4aeb-9601-50c2baf802de)

![cond_1](https://github.com/user-attachments/assets/7e4266bb-dfbc-4af2-a88d-f1c623f5179f)

https://github.com/user-attachments/assets/cc91676f-f620-4086-86da-7b39dad2d5eb

### Exemple 2

![puls_2](https://github.com/user-attachments/assets/7567ff9d-2d39-4276-955b-838ef3889a4d)

![peri_2](https://github.com/user-attachments/assets/7b915255-810a-4b11-8264-eccaa4e62f71)

![cond_2](https://github.com/user-attachments/assets/3eda74c2-9e05-40f5-b170-7565704b6285)

https://github.com/user-attachments/assets/4fae1fa9-fa40-4cc4-9fab-2663b134c473

### Exemple 3

![puls_3](https://github.com/user-attachments/assets/9616e04b-9ed2-4fae-946c-26450beca1a6)

![peri_3](https://github.com/user-attachments/assets/7c5133bc-2e54-45c5-a9fe-d8292c6b0419)

![cond_3](https://github.com/user-attachments/assets/5281ac57-002d-4c23-9719-819520cbb26b)

https://github.com/user-attachments/assets/17b9687f-a79f-4731-92e4-08ea820e5780

### Impulsion initiale

https://github.com/user-attachments/assets/2c80725d-21d8-4d6a-913c-015207d800e2





