## Funciones a implementar

1. **Escalón**\
    $x(t) = A\,\mu(t-t_0)$
2. **Seno**\
    $x(t) = A\sin(2\pi f_0t+\theta)$
3. **Exponencial**\
    $x(t) = A e^{\alpha(t-t_0)}$
4. **Señal amortiguada**\
    $x(t) = A\sin(2\pi f_0t+\theta)e^{\alpha t}$
5. **Pulso**\
    $p(t) = A[\mu(t-t_0)-\mu(t-t_0-D)]$

 ### Función escalón

 $$
\mu(t-t_0)=
\begin{cases}
0, & t<t_0\\
1, & t>t_0
\end{cases}
$$