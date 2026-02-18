
![Transaction](https://i.ibb.co/b50Ypjxj/Screen-Shot-2026-02-18-at-9-51-39-PM.png)

### Bitcoin Transaction ECDSA over secp256k1 Signature

$$
\begin{aligned}
R &= k G = (x_R, y_R) \quad &&\text{over } \mathbb{F}_p \\
r &= x_R \bmod n \\
s &= k^{-1}(z + r d) \bmod n
\end{aligned}
$$

### Bitcoin Transaction ECDSA Verification

$$
\begin{aligned}
w &= s^{-1} \bmod n \\
u_1 &= z \cdot w \bmod n \\
u_2 &= r \cdot w \bmod n \\
P &= u_1 \cdot G + u_2 \cdot Q = (x_P, y_P) \\
r' &= x_P \bmod n
\end{aligned}
$$

<br>

### GPG Fingerprint
[AFC8 10CF 10D3 8599 4346  A34F 44EB 919B FFFF 735E](https://keybase.io/elliptickurve256/pgp_keys.asc?fingerprint=afc810cf10d385994346a34f44eb919bffff735e) 



<!--
**ellipticKurve256k1/ellipticKurve256k1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
