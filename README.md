# Modes propres d'un système linéaire invariant

## Pendules couplés

On considère $N$ barres horizontales de moment d'inertie $J$, suspendues à un fil de torsion de raideur $K$ et régulièrerement espacées sur un axe vertical. Les deux extrémités du fil sont fixées. Pour la barre numéro $n$ avec $0\leq N \leq N-1$, l'angle de cette barre est noté $\theta_n$, de sorte que $\theta_n=0$ corresponde à la position d'équilibre. Le couple qui s'exerce sur cette barre est $K(\theta_{n-1}-\theta_n) + K(\theta_{n+1}-\theta_n)=K(\theta_{n-1}-2\theta_n+\theta_{n+1})$, avec $\theta_{-1}=\theta_N=0$.

Le principe fondamental de la dynamique appliqué à la barre $n$ donne alors

$$\dfrac{d^2\theta_n}{dt^2}=\dfrac{K}{J}(\theta_{n-1}-2\theta_n+\theta_{n+1})$$

Le vecteur d'état choisi est

$$Y=[\theta_0, ..., \theta_{N-1}, \dfrac{d\theta_0}{dt},...,\dfrac{\theta_{N-1}}{dt}]^T$$
 
## Illustrations

### Impulsion initiale

https://github.com/user-attachments/assets/2c80725d-21d8-4d6a-913c-015207d800e2

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





