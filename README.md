<pre>
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

bitcoin block hash: 000000000000000000008e19f4df61c8fd2017bf9bce55713835fa958d79841a
txid: a8827036e3294851ae2a84296aef74def9c64fe5febac403620ffabd0d858d32

txn hex:
02000000000101813e1f43bbf527fa835bc9c7b84affbad361b3def3c37a628cd3015da66547680000000000fdffffff036b570000000000001600146b6da4d47692cc8023eab8f39e14a0312fb6746bf96a000000000000160014dc3f2d8ae634eaa4af2c28cce2a98c521bb287f50000000000000000116a0f707362746275696c6465722e636f6d02473044022073bc8dfa0146161a3839f8ab10c8a010e86b67430f543a336d1771f31626b217022051c658e151c036f0e6efee883b9aa94cd06e128928ca30001af204bc438e7f6b012102c0e0d7bb9ff3b8f3caf32472b87bcb0bff670df1b8ef3dd4dff56d3d622496f300000000

-----BEGIN PGP SIGNATURE-----

iQIzBAEBCAAdFiEE1HpzWe/z2/rexrF1BtKzho4nYMYFAmp51PUACgkQBtKzho4n
YMZLRRAAmx7IbzDZsJkb2crQfk56eblXXRoxkFuQ6MIjY0ohppYwkbGcyB/WAc7y
sQ1qPXml1zWLqgsj1Q+auZjNesIxc8S0j0Im+Ig1BTStxyVtWg9yIXRsTt/t8k2N
yP25wUSqygT/kQOYj4YQkMoG6TSKM1ABRxW8U3lKokRUaCJ5zWQQiOMXmLpJnWg7
izVc7FtUuOXHnEEp+s3Gj9Yj1AaVu7MYdIcqYLqwsdcnAcGjqqLnLQDcpl22dTjk
R+f4PHHGmUFRrnCAt7AW2C7d5l0g+vNBTIfwaUIL6kqbu/+pvPa5lGcf7/ImthZe
0Z1j+m+fQLxR3K+IAUlvDUKilSvHx/J3K02tx1119Kl1INJOAP3YPH2cFUxiCvr4
CMgHSYhq0eBeyoggRKSkmnpahk/Z2uzCMND8gg0iWfmXJUvfdCKet5Du6HRrY+ku
5S+nGuTEuerjLMYsHvMewxohJBR1ri1bAS3C46CTxagiSarUuxRtKkrrMPZGNLZs
Do91yeBZYCgqwSoV0JDh79KA1O+7j/6VWKiMkNiIRQ1GBR7MzKL8E/RnZVtVvE1E
GXTbZvx9qvIPmXNTmjiE0hDCCMBL3ORkaKRswfCDVtgEd30k2l/Os8xBG+mXYoZs
s1YkGX3KhCFo/3bh4Yz6CVzjoqXYGcg+9n/OrzJNAvY+flUeEzM=
=KJip
-----END PGP SIGNATURE-----

</pre>

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
