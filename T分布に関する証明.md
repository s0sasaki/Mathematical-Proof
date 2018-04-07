
# T���z�ɂ��Ă̏ؖ�


1. Student�̒藝
2. Student�̒藝�̏ؖ��i���炷���j
3. Student�̒藝�̏ؖ��i�ڍׁj
4. ��A�W����T���z�̊֌W�̒莮��
5. ��A�W����T���z�̊֌W�̏ؖ�

���̋L���ł�$T$���z�Ɋւ���d�v�������ؖ�����B�Ƃ��Ƀ��j�[�N�Ȃ̂�5�͂́A�P��A�̌덷�̕W�{���U�����R�x$n-2$�̃J�C��敪�z�ɏ]�����Ƃ̏ؖ����@�B

���R�x�ɂ��Ă̏ؖ��͓��v�w�̓���I���ȏ��ł͂��܂����Ă��߂�����邱�Ƃ������B�܂��A�w���㋉�����x���̐������v�w�̋��ȏ��ł͓����֐��A�񎟌`���A�g���[�X�v�Z���p�����邱�Ƃ��������ǁA���̋L���ł͂�����p�����ɏؖ�������@���l�����B

**T���z�̒�`**

���R�x$n$��$T$���z�͈ȉ��̊m�����x�֐��Ƃ��Ē�`�����B

$$f_n(t) = \frac{1}{\sqrt{\pi n}}
\cdot \frac{ \Gamma{(\frac{n+1}{2})} }{ \Gamma{(\frac{n}{2})} }
\cdot (1+\frac{t^2}{n})^{-\frac{n+1}{2}} $$


## 1. Student�̒藝

$X_1$, ...,$X_n$�����K���z$N(\mu,\sigma^2)$�ɏ]���Ɨ��Ȋm���ϐ��ł���Ƃ���B�܂��W�{���ς�$\overline{X} = \frac{1}{n} \cdot \sum_{i=1}^{n}X_i$�ƒu���A�s�Ε��U��$s_n^2 = \frac{1}{n-1} \cdot \sum_{i=1}^{n}(X_i - \overline{X})^2$�ƒu���B�����Ŏ��̕ϐ�

$$ T = \frac{ \overline{X} - \mu }{ \sqrt{s_n^2/n} }$$

���l����ƁA����͎��R�x$n$��$T$���z�ɏ]���B

## 2. Student�̒藝�̏ؖ�

�ȉ��̂S�̕���p���ďؖ�����B

���2.3���A���2.2�ƕ��2.4�Ɏ����ϐ��ɑ΂��ĕ��2.1��K�p���邱�Ƃ��ł��AStudent�̒藝���������B�܂�A

$$
T = \frac{ \frac{ \overline{X} - \mu }{ \sqrt{\sigma^2/n} } }{ \sqrt{\frac{ (n-1)s_n^2 / \sigma^2}{n-1}} }
= \frac{ \overline{X} - \mu }{ \sqrt{s_n^2/n} }
$$

�͎��R�x$n$��$T$���z�ɏ]���AStudent�̒藝����������B

### 2.1 ���2.1

�ϐ�$U$�����K���z$N(0,1^2)$�ɏ]���A�ϐ�$V$���J�C��敪�z$\chi^2(k)$�ɏ]���A����炪�݂��ɓƗ��ȂƂ��A���̕ϐ�

$$Z = \frac{U}{\sqrt{V/k}}$$

���l����ƁA����͎��R�x$k$��$T$���z$T(k)$�ɏ]���B

### 2.2 ���2.2

$X_1$, ...,$X_n$�����K���z$N(\mu,\sigma^2)$�ɏ]���Ɨ��Ȋm���ϐ��ł���Ƃ���B�܂��W�{���ς�$\overline{X} = \frac{ \sum_{i=1}^{n}X_i}{n}$�ƒu���B�����Ŏ��̕ϐ�

$$ \frac{ \overline{X} - \mu }{ \sqrt{\sigma^2/n} }$$

���l����ƁA����͐��K���z$N(0,1^2)$�ɏ]���B

### 2.3 ���2.3

$X_1$, ...,$X_n$�����K���z$N(\mu,\sigma^2)$�ɏ]���Ɨ��Ȋm���ϐ��ł���Ƃ���B�܂��W�{���ς�$\overline{X} = \frac{ \sum_{i=1}^{n}X_i}{n}$�A�W�{���U��$s_n^2 = \frac{\sum_{i=1}^{n}(X_i - \overline{X})^2}{n-1}$�ƒu���B

���̂Ƃ�$\overline{X}$��$s_n^2$�݂͌��ɓƗ��ł���B

### 2.4 ���2.4

$X_1$, ...,$X_n$�����K���z$N(\mu,\sigma^2)$�ɏ]���Ɨ��Ȋm���ϐ��ł���Ƃ���B�܂��W�{���U��$s_n^2 = \frac{\sum_{i=1}^{n}(X_i - \overline{X})^2}{n-1}$�ƒu���B�����Ŏ��̕ϐ�

$$ \frac{ (n-1)s_n^2 }{ \sigma^2 }$$

���l����ƁA����͎��R�x$n-1$�̃J�C��敪�z$\chi^2(n-1)$�ɏ]���B


## 3. ���̏ؖ�

  

�ȉ��ł́A�O�q��4�̕����ؖ�����B

  

### 3.1 ���2.1�̏ؖ�

> #### ���2.1
> �ϐ�$U$�����K���z$N(0,1^2)$�ɏ]���A�ϐ�$V$���J�C��敪�z$\chi^2(k)$�ɏ]���A����炪�݂��ɓƗ��ȂƂ��A���̕ϐ�
> $$Z = \frac{U}{\sqrt{V/k}}$$
> ���l����ƁA����͎��R�x$k$��$T$���z$T(k)$�ɏ]���B

���K���z�ƃJ�C��敪�z�̊m�����x�֐���$\phi(u)$�A$\psi(v)$�Ƃ���B

�萔$a$�ɑ΂���$Z<a$�ƂȂ�m����

$$
P\bigl( Z < a \bigr)
= P\biggl( \frac{U}{\sqrt{V/k}} < a \biggr)
= \iint_{ \frac{u}{\sqrt{v/k}} < a } \phi(u)\psi(v) dudv
$$

$$
= \iint_{ \frac{u}{\sqrt{v/k}} < a }
\biggl(
\frac{1}{\sqrt{2\pi}}
e^{- u^2/2}
\biggr)
\biggl(
\frac{1}{\Gamma(\frac{k}{2})}
\bigl(
\frac{1}{2}
\bigr)^{\frac{k}{2}}
v^{\frac{k}{2}-1}
e^{-\frac{v}{2}}
\biggr)
dudv
$$

�ƂȂ�B$z = \frac{u}{\sqrt{v/k}}, v = v$�ɂ��ϐ��ϊ����s���A

$$
P\bigl( Z < a \bigr)
= \iint_{ z < a , 0 < v < \infty}
\frac{1}{\sqrt{2\pi} 2^{\frac{k}{2}} \Gamma(\frac{k}{2})}
\cdot
e^{- \frac{vz^2}{2k}-\frac{v}{2}}
\cdot
v^{\frac{k}{2}-1}
\cdot
\begin{vmatrix} \sqrt{v/k} & * \\ 0 & 1 \end{vmatrix}
dvdz
$$

����ɃK���}�֐��̌`�����悤��$s=\frac{vz^2}{2k}+\frac{v}{2}, z = z$�ƕϐ��ϊ����邱�ƂŁA

$$
P\bigl( Z < a \bigr)
= \iint_{ z < a , 0 < s < \infty}
\frac{1}{\sqrt{2\pi} \sqrt{k} 2^{\frac{k}{2}} \Gamma(\frac{k}{2})}
\cdot
e^{-s}
\cdot
\biggl( \frac{s}{\frac{z^2}{2k} + \frac{1}{2}} \biggr)^{\frac{k-1}{2}}
\cdot
\begin{vmatrix} \frac{1}{\frac{z^2}{2k} + \frac{1}{2}} & * \\ 0 & 1 \end{vmatrix}
dsdz
$$

$$
= \iint_{ z < a , 0 < s < \infty}
\frac{1}{\sqrt{k \pi} 2^{\frac{k+1}{2}} \Gamma(\frac{k}{2})}
\cdot
s^{\frac{k+1}{2}-1}
\cdot
e^{-s}
\cdot
\frac{1}{ \biggl( \frac{z^2}{2k} + \frac{1}{2} \biggr)^{\frac{k+1}{2}} }
dsdz
$$

$$
= \frac{\Gamma(\frac{k}{2} + 1)}{\sqrt{\pi k}\Gamma(\frac{k}{2})}
\int_{ z < a }
\biggl( \frac{z^2}{k} +1 \biggr)^{-\frac{k+1}{2}}
dz
$$

����Ă��̂Ƃ�$Z$�͎��R�x$k$��$T$���z$T(k)$�ɏ]���B


### 3.2 ���2.2�̏ؖ�

> #### ���2.2
>$X_1$, ...,$X_n$�����K���z$N(\mu,\sigma^2)$�ɏ]���Ɨ��Ȋm���ϐ��ł���Ƃ���B�܂��W�{���ς�$\overline{X} = \frac{ \sum_{i=1}^{n}X_i}{n}$�ƒu���B�����Ŏ��̕ϐ�
>$$ \frac{ \overline{X} - \mu }{ \sqrt{\sigma^2/n} }$$
>���l����ƁA����͐��K���z$N(0,1^2)$�ɏ]���B

�����ׂ�����u$\frac{ \overline{X} - \mu }{ \sqrt{\sigma^2/n} }$�͐��K���z$N(0,1^2)$�ɏ]���v�́A����u$\sum_{i=1}^{n}X_i$�͐��K���z$N(n \mu,n \sigma^2)$�ɏ]���v�Ɠ��l�ł���B�Ȃ��Ȃ�΁A�ϐ�U��V�� $U = \frac{ \overline{X} - \mu }{ \sqrt{\sigma^2/n} }, V = \sum_{i=1}^{n}X_i$ �ƒu���� $U = \frac{ V - n\mu }{ \sqrt{n\sigma^2} }$ �ł���A

$$
P(V < n\mu + a \sqrt{n\sigma^2}) = P(U < a )
$$

$$
\int_{ v < n\mu + a \sqrt{n\sigma^2}}
\frac{1}{ \sqrt{2\pi} \sqrt{n\sigma^2}}
e^{ \frac{ ( v - n\mu )^2 }{ 2n \sigma^2}} dv = \int_{ u < a}
\frac{1}{ \sqrt{2\pi} }
e^{ \frac{ u^2 }{ 2}} du
$$
  
�ł��邩��A��L�Q�̎��̉E�ӓ��m���������Ƃ����ӓ��m���������A���̋t���������邽�߂ł���B

��҂̖�����ؖ�����ɂ́u�ϐ�V��W�����K���z$N(\mu_1,\sigma_1^2)$��$N(\mu_2,\sigma_2^2)$�Ɍ݂��ɓƗ��ɏ]���Ƃ��A�ϐ�V+W�͐��K���z$N(\mu_1 + \mu_2,\sigma_1^2 + \sigma_2^2)$�ɏ]���v�������Ώ\���ł���B

�ϐ�$Y=V+W$�Ƃ��AV��W�̊m�����x�֐���$\phi_v$�A$\phi_w$�Ƃ����

$$
P(Y < a)
= \int_{y=-\infty}^a \int_{v=-\infty}^{\infty}
\phi_v(v)\phi_w(y-v)
dvdy
= \int_{y=-\infty}^a \int_{v=-\infty}^{\infty}
\frac{1}{\sqrt{2\pi} \sigma_1} e^\frac{(v -\mu_1)^2}{2 \sigma_1^2}
\frac{1}{\sqrt{2\pi} \sigma_2} e^\frac{(y-v-\mu_2)^2}{2 \sigma_2^2}
dvdy
$$

$$
= \int_{y=-\infty}^a
\frac{1}{2 \pi \sqrt{ \sigma_1^2 \sigma_2^2}} e^{- \frac{(y -(\mu_1 +\mu_2)^2}{2 (\sigma_1^2 + \sigma_2^2)}}
\int_{v=-\infty}^{\infty}
e^{
-\frac{ \sigma_1^2 + \sigma_2^2}{2 \sigma_1^2 \sigma_2^2}
(v - \frac{\sigma_1^2 y + \sigma_2^2 \mu_1 - \sigma_1^2 \mu_2}{\sigma_1^2 + \sigma_2^2})^2
}
dv
dy
$$

$$
= \int_{y=-\infty}^a
\frac{1}{2 \pi \sqrt{\sigma_1^2 \sigma_2^2}} e^{- \frac{(y -(\mu_1 +\mu_2)^2}{2 (\sigma_1^2 + \sigma_2^2)}}
\sqrt{2\pi \frac{\sigma_1^2 \sigma_2^2}{\sigma_1^2 + \sigma_2^2} }
dy
$$

$$
= \int_{y=-\infty}^a
\frac{1}{\sqrt{2\pi} \sqrt{\sigma_1^2 + \sigma_2^2}}
e^\frac{(y-(\mu_1+\mu_2))^2}{2 (\sigma_1^2 + \sigma_2^2)}
dy
$$

����āA�ϐ�V+W�͐��K���z$N(\mu_1 + \mu_2,\sigma_1^2 + \sigma_2^2)$�ɏ]���B

���Ȃ킿�A$\sum_{i=1}^{n}X_i$�͐��K���z$N(n \mu,n \sigma^2)$�ɏ]���B

���Ȃ킿�A$\frac{ \overline{X} - \mu }{ \sqrt{\sigma^2/n} }$�͐��K���z$N(0,1^2)$�ɏ]���B

### 3.3 ���2.3�̏ؖ�

> #### ���2.3
>$X_1$, ...,$X_n$�����K���z$N(\mu,\sigma^2)$�ɏ]���Ɨ��Ȋm���ϐ��ł���Ƃ���B�܂��W�{���ς�$\overline{X} = \frac{ \sum_{i=1}^{n}X_i}{n}$�A�W�{���U��$s_n^2 = \frac{\sum_{i=1}^{n}(X_i - \overline{X})^2}{n-1}$�ƒu���B
>
>���̂Ƃ�$\overline{X}$��$s_n^2$�݂͌��ɓƗ��ł���B

n�����x�N�g����n���������s��

  

$$
U = \begin{pmatrix} \frac{X_1-\mu}{\sigma} \\ : \\ \frac{X_n-\mu}{\sigma} \end{pmatrix},
A = \begin{pmatrix} 1/\sqrt{n} & ... & 1/\sqrt{n}
\\ * & ... & *
\\ : & & :
\\ * & ... & * \end{pmatrix}
$$

���l����B�iA�̂悤�Ȓ����s�񂪑��݂��邱�Ƃ́A�O�����E�V���~�b�g�̕��@�Ŏ��ۂɏ��������Ε����邪�����ł͏ȗ�����B�j

U��A�ɂ��An�����x�N�g��

$$
V = \begin{pmatrix} V_1 \\ : \\ V_n \end{pmatrix} = AU
$$

���`����B

���̂Ƃ��A

$$
\sum_{i=1}^{n}V_i^2 = V^T V = (AU)^T (AU) = U^T (A^T A) U = U^T U = \sum_{i=1}^{n}U_i^2
$$

�ƂȂ邱�Ƃ𗘗p���āA���L�̂悤��$\overline{X}$��$s_n^2$��\�����Ƃ��ł���B

$$
\overline{X}
= \frac{\sum_{i=1}^{n}X_i}{n}
= \frac{\sum_{i=1}^{n}(\mu + \sigma U_i)}{n}
= \mu + \frac{\sigma}{\sqrt{n}} \sum_{i=1}^{n}\frac{U_1}{\sqrt{n}}
= \mu + \frac{\sigma}{\sqrt{n}} V_1
$$

$$
s_n^2
= \frac{1}{n-1} \sum_{i=1}^{n}(X_i - \overline{X})^2
= \frac{\sigma}{n-1} \sum_{i=1}^{n}(U_i - \overline{U})^2
= \frac{\sigma}{n-1} \bigl( \sum_{i=1}^{n}U_i^2 - n\overline{U}^2 \bigr)
$$

$$
= \frac{\sigma}{n-1} \bigl( \sum_{i=1}^{n}U_i^2 - (\sum_{i=1}^{n}U_i/\sqrt{n})^2 \bigr)
= \frac{\sigma}{n-1} \bigl( \sum_{i=1}^{n}V_i^2 - V_1^2 \bigr)
= \frac{\sigma}{n-1} \sum_{i=2}^{n}V_i^2
$$

�����ŁA$\overline{U} = \sum_{i=1}^{n}U_i/n$�ł���B

$\overline{X}$��$V_1$�ŕ\����A$s_n^2$��$V_2 ,.., V_n$�ŕ\�����̂ŁA$\overline{X}$��$s_n^2$���Ɨ��ł��邱�Ƃ������ɂ́A$V_i$�������݂��ɓƗ��ł��邱�Ƃ������Ώ\���ł���B

���2.2�̏ؖ��̒��ŗp�������@�Ɠ��l�ɂ��āA$U_i$�A$V_i$�͐��K���z$N(0,1^2)$�ɏ]�����Ƃ�������B

�C�ӂ̗̈�$D_1 \subset \mathbb{R}^n$�ɂ��āA�����s��$A^T$��������|����ʑ��ɂ����$D_1$���ڂ����̈��$D_2$�Ƃ���B���̎ʑ��ɂ͋t�ʑ�������̂�

  

$$
U \in D_2 \Leftrightarrow V \in D_1
$$

�ł���B���̂Ƃ��A

  

$$
P(V \in D_1)
= P( U \in D_2)
= \int_{u \in D_2}
\frac{1}{\sqrt{2 \pi}}e^{u_1^2/2}...\frac{1}{\sqrt{2 \pi}}e^{u_n^2/2}
du_1...du_n
$$

$$
= \int_{u \in D_2}
\Bigl( \frac{1}{\sqrt{2 \pi}} \Bigr)^n
e^{\frac{u_1^2 + ... + u_n^2}{2}}
du_1...du_n
$$

$$
= \int_{v \in D_1}
\Bigl( \frac{1}{\sqrt{2 \pi}} \Bigr)^n
e^{\frac{v_1^2 + ... + v_n^2}{2}}
\mid A \mid dv_1...dv_n
$$

$$
= \int_{v \in D_1}
\frac{1}{\sqrt{2 \pi}}e^{v_1^2/2}...\frac{1}{\sqrt{2 \pi}}e^{v_n^2/2}
dv_1...dv_n
$$
  
����āA$V$�̊m�����x�֐��͊e$V_i$�̊m�����x�֐��̐ςƂȂ�̂ŁA$V_i$�����݂͌��ɓƗ��ł���B

���Ȃ킿�A$\overline{X}$��$s_n^2$�͓Ɨ��ȕϐ��ł��ꂼ��\�����̂ŁA$\overline{X}$��$s_n^2$�݂͌��ɓƗ��ł���B


### 3.4 ���2.4�̏ؖ�

> #### ���2.4
>$X_1$, ...,$X_n$�����K���z$N(\mu,\sigma^2)$�ɏ]���Ɨ��Ȋm���ϐ��ł���Ƃ���B�܂��W�{���U��$s_n^2 = \frac{\sum_{i=1}^{n}(X_i - \overline{X})^2}{n-1}$�ƒu���B�����Ŏ��̕ϐ�
>$$ \frac{ (n-1)s_n^2 }{ \sigma^2 }$$
>���l����ƁA����͎��R�x$n-1$�̃J�C��敪�z$\chi^2(n-1)$�ɏ]���B

���L(1)(2)(3)���A�ϐ�$\frac{ (n-1)s_n^2 }{ \sigma^2 }$�͎��R�x$n-1$�̃J�C��敪�z$\chi^2(n-1)$�ɏ]�����Ƃ��������B

(1). �ϐ�$X$�����K���z$N(0,1^2)$�ɏ]���Ƃ��A$X^2$�̓J�C��敪�z$\chi^2(1)$�ɏ]���B

(2). �ϐ�$W_1,..,W_n$���݂��ɓƗ��ɃJ�C��敪�z$\chi^2(1)$�ɏ]���Ƃ��A�ϐ�$W_1 + ... + W_n$�̓J�C��敪�z$\chi^2(n)$�ɏ]���B

(3). �ϐ�$\frac{ (n-1)s_n^2 }{ \sigma^2 }$�́A���K���z$N(0,1^2)$�ɏ]��$n-1$�݂̌��ɓƗ��ȕϐ��̓��a�ł���B

�ȉ��ł�(1)(2)(3)�ɂ��ďؖ�����B

##### (1)�̏ؖ��F

�ϐ�$W = X^2$�Ƃ���B

$$
P \bigl( W < a \bigr)
= P \bigl(- \sqrt{a} < X < \sqrt{a} \bigr)
= \int_{-\sqrt{a}}^{\sqrt{a}} \frac{1}{\sqrt{2 \pi}} e^{-\frac{x^2}{2}} dx
= 2 \int_{ 0}^{\sqrt{a}} \frac{1}{\sqrt{2 \pi}} e^{-\frac{x^2}{2}} dx
$$

$ u = x^2 $�Ƃ��ĕϐ��ϊ������

$$
P \bigl( W < a \bigr)
= 2 \int_{0}^{a} \frac{1}{\sqrt{2 \pi}} e^{-\frac{u}{2}} \frac{du}{2 \sqrt{u}}
= \int_{0}^{a}
\frac{1}{\sqrt{\pi}}
\bigl(
\frac{1}{2}
\bigr)^{-\frac{1}{2}}
u^{-\frac{1}{2}}
e^{-\frac{u}{2}}
du
$$

�ƂȂ�B���Ȃ킿�A$W = X^2$�̓J�C��敪�z$\chi^2(1)$�ɏ]���B

##### (2)�̏ؖ��F

�ϐ�$W_1$���J�C��敪�z$\chi^2(n)$�ɏ]���A�ϐ�$W_2$���J�C��敪�z$\chi^2(m)$�ɏ]���Ƃ��A�ϐ�$W_1+W_2$�̓J�C��敪�z$\chi^2(n+m)$�ɏ]�����Ƃ������Ώ\���ł���B

�ϐ�$Z = W_1 + W_2$�Ƃ��A���R�xk�̃J�C��敪�z��$f_k$�ƕ\���Ƃ����

$$
P \bigl( Z < a \bigr)
= \int_{z=0}^a \int_{w_1=0}^{\infty}
f_n(w_1) f_m(z - w_1)
dw_1 dz
$$

$$
= \int_{z=0}^a \int_{w_1=0}^{\infty}
\biggl(
\frac{1}{\Gamma(\frac{n}{2})}
\bigl(
\frac{1}{2}
\bigr)^{-\frac{n}{2}}
w_1^{\frac{n}{2}-1}
e^{-\frac{w_1}{2}}
\biggr)
\biggl(
\frac{1}{\Gamma(\frac{m}{2})}
\bigl(
\frac{1}{2}
\bigr)^{-\frac{m}{2}}
(z-w_1)^{\frac{m}{2}-1}
e^{-\frac{z-w_1}{2}}
\biggr)
dw_1 dz
$$

�ƂȂ�B$w_1$�̐ϕ��ɂ�����$u = w_1/z$�ƕϐ��ϊ������

$$
P \bigl( Z < a \bigr)
= \int_{z=0}^a \int_{u=0}^{\infty}
\biggl(
\frac{1}{\Gamma(\frac{n}{2})}
\bigl(
\frac{1}{2}
\bigr)^{-\frac{n}{2}}
(zu)^{\frac{n}{2}-1}
e^{-\frac{zu}{2}}
\biggr)
\biggl(
\frac{1}{\Gamma(\frac{m}{2})}
\bigl(
\frac{1}{2}
\bigr)^{-\frac{m}{2}}
(z-zu)^{\frac{m}{2}-1}
e^{-\frac{z-zu}{2}}
\biggr)
zdu dz
$$

$$
= \int_{z=0}^a
\frac{1}{\Gamma(\frac{n}{2})\Gamma(\frac{m}{2})}
\bigl(
\frac{1}{2}
\bigr)^{-\frac{n+m}{2}}
z^{\frac{n+m}{2}-1}
e^{-\frac{z}{2}}
\int_{u=0}^{\infty}
u^{\frac{n}{2}-1}
(1-u)^{\frac{m}{2}-1}
du
dz
$$

�ƂȂ�Au�̐ϕ��ɂ����ăx�[�^�֐��̐����𗘗p���āA

$$
P \bigl( Z < a \bigr)
= \int_{z=0}^a
\frac{1}{\Gamma(\frac{n}{2})\Gamma(\frac{m}{2})}
\bigl(
\frac{1}{2}
\bigr)^{-\frac{n+m}{2}}
z^{\frac{n+m}{2}-1}
e^{-\frac{z}{2}}
\frac{\Gamma(\frac{n}{2})\Gamma(\frac{m}{2})}{\Gamma(\frac{n+m}{2})}
dz
$$

$$
= \int_{z=0}^a
\frac{1}{\Gamma(\frac{n+m}{2})}
\bigl(
\frac{1}{2}
\bigr)^{-\frac{n+m}{2}}
z^{\frac{n+m}{2}-1}
e^{-\frac{z}{2}}
dz
$$

�ƂȂ�B����āA�ϐ�$W_1$���J�C��敪�z$\chi^2(n)$�ɏ]���A�ϐ�$W_2$���J�C��敪�z$\chi^2(m)$�ɏ]���Ƃ��A�ϐ�$Z = W_1+W_2$�̓J�C��敪�z$\chi^2(n+m)$�ɏ]�����Ƃ��������B

���Ȃ킿�A�ϐ�$W_1,..,W_n$���݂��ɓƗ��ɃJ�C��敪�z$\chi^2(1)$�ɏ]���Ƃ��A�ϐ�$W_1 + ... + W_n$�̓J�C��敪�z$\chi^2(n)$�ɏ]���B

##### (3)�̏ؖ��F

���2.3�̏ؖ��̒��Œ�`�����ϐ�$V_1,..,V_n$�ɂ��āA�����݂͌��ɓƗ��ɐ��K���z$N(\mu,\sigma^2)$�ɏ]���A�܂�

$$
s_n^2 = \frac{ \sigma^2 }{n-1} \sum_{i=2}^{n}V_i^2
$$

�ł���B���Ȃ킿�A�ϐ�$\frac{ (n-1)s_n^2 }{ \sigma^2 }$�́A���K���z$N(0,1^2)$�ɏ]��$n-1$�݂̌��ɓƗ��ȕϐ��̓��a�ł���B



## 4.��A�W����T���z�̊֌W

�����ł͂܂���A���̒莮�����s���A���̂��Ɖ�A�W����$T$���z�̊֌W�ɂ��ċL���B

����ׂɑI�΂ꂽ�l�Ƃ���ɑΉ���������ɂ���ē����l�̑g$(X_1,Y_1),..,(X_n,Y_n)$�ɂ��āA�ȉ��̂悤�Ȋ֌W������Ƃ���B

$$
\begin{pmatrix} Y_1
\\ :
\\ Y_n \end{pmatrix}
=\begin{pmatrix} 1 & X_1 - \overline{X}
\\ : & :
\\ 1 & X_n - \overline{X} \end{pmatrix}
\begin{pmatrix} \beta_0
\\ \beta_1 \end{pmatrix}
+
\begin{pmatrix} \epsilon_1
\\ :
\\ \epsilon_n \end{pmatrix}
$$

������

  
- �����ϐ�$X_i$�݂͌��ɈقȂ�l���Ƃ�B(�����͊m���ϐ��ł͂Ȃ��萔�ł���B)

- �����ϐ��̕��ϒl��$\overline{X} = \frac{ \sum_{i=1}^{n}X_i}{n}$�Ƃ���

- �m���ϐ�$\epsilon_1$, ...,$\epsilon_n$�͐^�̌덷�ƌĂ΂�A���K���z$N(0,\sigma^2)$�ɏ]���Ɨ��Ȋm���ϐ��ł���

- �萔$\beta_0$�A$\beta_1$�͐^�̉�A�W���ƌĂ΂��

  

�Ƃ���B���̂Ƃ��A������ϐ�$Y_i$�݂͌��ɓƗ���$N(\beta_0 + (X_i-\overline{X})\beta_1, \sigma^2)$�ɏ]���B

  

��A�W���͍Ŗޖ@�ɂ���Đ��肷�邱�ƂƂ��A

$$
L(\beta_0, \beta_1)
= \bigl( \frac{1}{2 \pi \sigma^2} \bigr)^{n/2}
\exp\{-\frac{1}{2\sigma^2} \sum_1^n \bigl( Y_i - \beta_0 - \beta_1(X_i - \overline{X}) \bigr)^2 \}
$$

�ɂ��āA$\beta_0$�A$\beta_1$�̐���l��$b_0$�A$b_1$�Ƃ����

$$
\frac{\partial}{\partial \beta_0}\log L(b_0, b_1)
= \frac{\partial}{\partial \beta_1}\log L(b_0, b_1)
= 0
$$

�𖞂����B���Ȃ킿�A$\overline{Y} = \frac{\sum_1^n Y_i}{n}$�Ƃ���

$$
b_0 = \overline{Y}
$$

$$
b_1 = \frac{\sum_1^n (X_i - \overline{X})(Y_i - \overline{Y})}{\sum_1^n (X_i - \overline{X})^2}
= \frac{\sum_1^n (X_i - \overline{X})Y_i}{\sum_1^n (X_i - \overline{X})^2}
= \frac{\sum_1^n (X_i - \overline{X})\epsilon_i}{\sum_1^n (X_i - \overline{X})^2} + \beta_1
$$

�ł���B

���̂悤�ȏ󋵂ɂ����āA$\hat{\epsilon}_i$������

$$
\begin{pmatrix} Y_1
\\ :
\\ Y_n \end{pmatrix}
=\begin{pmatrix} 1 & X_1 - \overline{X}
\\ : & :
\\ 1 & X_n - \overline{X} \end{pmatrix}
\begin{pmatrix} b_0
\\ b_1 \end{pmatrix}
+
\begin{pmatrix} \hat{\epsilon_1}
\\ :
\\ \hat{\epsilon_n} \end{pmatrix}
$$

�Ƃ��Ē�߂�B

�ȏ�̂悤�ȉ�A���ɂ����āA

$$
T_0 = \frac{b_0 - \beta_0}{\sqrt{ \frac{\sum_1^n \hat{\epsilon}_i^2}{n(n-2)} }}
$$

$$
T_1 = \frac{b_1 - \beta_1}{\sqrt{ \frac{\sum_1^n \hat{\epsilon}_i^2}{(n-2)\sum_1^n (X_i - \overline{X})^2} }}
$$

�𖞂����ϐ�$T_0,T_1$�͎��R�x$n-2$��$T$���z$T(n-2)$�ɂ��ꂼ��]���B

## 5. ��A�W����T���z�̊֌W�̏ؖ�

�O�͂̕ϐ�$T_0,T_1$��$T$���z�ɏ]�����Ƃ��ؖ�����B

�����ŁA���2.1���Ăї��p����B

>#### 2.1 ���
>
>�ϐ�$U$�����K���z$N(0,1^2)$�ɏ]���A�ϐ�$V$���J�C��敪�z$\chi^2(k)$�ɏ]���A����炪�݂��ɓƗ��ȂƂ��A���̕ϐ�
>$$Z = \frac{U}{\sqrt{V/k}}$$
>���l����ƁA����͎��R�x$k$��$T$���z$T(k)$�ɏ]���B


���2.1��$U,V,k$�Ƃ��ēK�؂Ȃ��̂�I�Ԃ��ƂŁA$T$���z�ɏ]���ϐ�$T_0,T_1$�𓱏o����B

4�͂�$b_0,b_1$��\���������A$b_0$�͐��K���z$N(\beta_0, \frac{\sigma^2}{n})$�ɏ]���A$b_1$�͐��K���z$N(\beta_1, \frac{\sigma^2}{\sum_1^n (X_i - \overline{X})^2})$�ɏ]�����Ƃ�������B

�܂�ϐ� $\frac{b_0 - \beta_0}{ \sqrt{\frac{\sigma^2}{n}} }$ �� $\frac{b_1 - \beta_1}{ \sqrt{\frac{\sigma^2}{\sum_1^n (X_i - \overline{X})^2}} }$ �͐��K���z$N(0, 1^2)$�ɏ]���i�����͕��2.2�̏ؖ��O�������Ɠ��l�Ɏ������Ƃ��ł���j�B

�����ŁA�ϐ�

$$
\frac{\sum_1^n \hat{\epsilon}_i^2}{\sigma^2}
$$

���l���A���ꂪ�O�L�� $\frac{b_0 - \beta_0}{ \sqrt{\frac{\sigma^2}{n}} }$ �� $\frac{b_1 - \beta_1}{ \sqrt{\frac{\sigma^2}{\sum_1^n (X_i - \overline{X})^2}} }$ �Ƃ��ꂼ��݂��ɓƗ��Ŏ��R�x$n-2$�̃J�C��敪�z$\chi^2(n-2)$�ɏ]�����Ƃ�������΁A���Ȃ킿�A���2.1���ϐ�

$$
T_0 = \frac{\frac{b_0 - \beta_0}{ \sqrt{\frac{\sigma^2}{n}} }}
{\sqrt{ \frac{\sum_1^n \hat{\epsilon}_i^2/\sigma^2}{n-2} }}
= \frac{b_0 - \beta_0}{\sqrt{ \frac{\sum_1^n \hat{\epsilon}_i^2}{n(n-2)} }}
$$

$$
T_1 = \frac{\frac{b_1 - \beta_1}{ \sqrt{\frac{\sigma^2}{\sum_1^n (X_i - \overline{X})^2}} }}
{\sqrt{ \frac{\sum_1^n \hat{\epsilon}_i^2/\sigma^2}{n-2} }}
= \frac{b_1 - \beta_1}{\sqrt{ \frac{\sum_1^n \hat{\epsilon}_i^2}{(n-2)\sum_1^n (X_i - \overline{X})^2} }}
$$

�͂��ꂼ�ꎩ�R�x$n-2$��$T$���z$T(n-2)$�ɏ]���B

�������A�ȉ��̕��5.1���ؖ�����΂悢�B


### 5.1 ���5.1

�O�L�̉�A���ɂ����āA�ϐ�

$$
\frac{\sum_1^n \hat{\epsilon}_i^2}{\sigma^2}
$$

�́A $\frac{b_0 - \beta_0}{ \sqrt{\frac{\sigma^2}{n}} }$ �� $\frac{b_1 - \beta_1}{ \sqrt{\frac{\sigma^2}{\sum_1^n (X_i - \overline{X})^2}} }$ �Ƃ��ꂼ��݂��ɓƗ��Ŏ��R�x$n-2$�̃J�C��敪�z$\chi^2(n-2)$�ɏ]���B

  
### ���5.1�̏ؖ�

�܂��A���̂悤�Ȏ������藧�B

$$
\begin{pmatrix} \epsilon_1
\\ :
\\ \epsilon_n \end{pmatrix}
=\begin{pmatrix} 1 & X_1 - \overline{X}
\\ : & :
\\ 1 & X_n - \overline{X} \end{pmatrix}
\begin{pmatrix} b_0 - \beta_0
\\ b_1 - \beta_1 \end{pmatrix}
+
\begin{pmatrix} \hat{\epsilon_1}
\\ :
\\ \hat{\epsilon_n} \end{pmatrix}
$$

$$
\hspace{6em}
=(b_0 - \beta_0)
\begin{pmatrix} 1
\\ :
\\ 1 \end{pmatrix}
+
(b_1 - \beta_1)
\begin{pmatrix} X_1 - \overline{X}
\\ :
\\ X_n - \overline{X} \end{pmatrix}
+
\begin{pmatrix} \hat{\epsilon_1}
\\ :
\\ \hat{\epsilon_n} \end{pmatrix}
$$

���m�ȕ\���ł͂Ȃ��������I�ȉ�������Ă����ƁA���ӂ̓J�C��敪�z$\chi^2(n)$�ɏ]���ϐ��̑f(����)�ł���A�E�ӑ�1���A��2���A��3���͂��ꂼ��J�C��敪�z$\chi^2(1),\chi^2(1),\chi^2(n-2)$�ɏ]���ϐ��̑f�ł���Ƃ������Ƃ��ӎ����Ȃ��玮��ό`���Ă����B

$b_0,b_1$�̒�`�������Ă���Ɏ��ό`�����

$$
\begin{pmatrix} \epsilon_1
\\ :
\\ \epsilon_n \end{pmatrix}
=\overline{Y}
\begin{pmatrix} 1
\\ :
\\ 1 \end{pmatrix}
+
\frac{\sum_1^n \epsilon_i(X_i - \overline{X})} {\sum_1^n (X_i - \overline{X})^2}
\begin{pmatrix} X_1 - \overline{X}
\\ :
\\ X_n - \overline{X} \end{pmatrix}
+
\begin{pmatrix} \hat{\epsilon_1}
\\ :
\\ \hat{\epsilon_n} \end{pmatrix}
$$

$$
\hspace{6em}
=\sum_1^n \frac{\epsilon_i}{\sqrt{n}}
\begin{pmatrix} \frac{1}{\sqrt{n}}
\\ :
\\ \frac{1}{\sqrt{n}} \end{pmatrix}
+
\sum_1^n \frac{\epsilon_i(X_i - \overline{X})}{\sqrt{\sum_1^n (X_i - \overline{X})^2}}
\begin{pmatrix} \frac{X_1 - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}}
\\ :
\\ \frac{X_n - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}} \end{pmatrix}
+
\begin{pmatrix} \hat{\epsilon_1}
\\ :
\\ \hat{\epsilon_n} \end{pmatrix}
$$

$$
\hspace{6em}
=\begin{pmatrix} \frac{1}{\sqrt{n}}
& ...
& \frac{1}{\sqrt{n}} \end{pmatrix}
\cdot
\begin{pmatrix} \epsilon_1
\\ :
\\ \epsilon_n \end{pmatrix}
\begin{pmatrix} \frac{1}{\sqrt{n}}
\\ :
\\ \frac{1}{\sqrt{n}} \end{pmatrix}
+
\begin{pmatrix} \frac{X_1 - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}}
& ...
& \frac{X_n - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}} \end{pmatrix}
\cdot
\begin{pmatrix} \epsilon_1
\\ :
\\ \epsilon_n \end{pmatrix}
\begin{pmatrix} \frac{X_1 - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}}
\\ :
\\ \frac{X_n - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}} \end{pmatrix}
+
\begin{pmatrix} \hat{\epsilon_1}
\\ :
\\ \hat{\epsilon_n} \end{pmatrix}
$$

n�����x�N�g��

$$
\epsilon =
\begin{pmatrix} \epsilon_1
\\ :
\\ \epsilon_n \end{pmatrix},
\hat{\epsilon} =
\begin{pmatrix} \hat{\epsilon}_1
\\ :
\\ \hat{\epsilon}_n \end{pmatrix},
a_1 =
\begin{pmatrix} \frac{1}{\sqrt{n}}
\\ :
\\ \frac{1}{\sqrt{n}} \end{pmatrix},
a_2 =
\begin{pmatrix} \frac{X_1 - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}}
\\ :
\\ \frac{X_n - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}} \end{pmatrix}
$$

�ƒu���ƁA�㎮��

$$
\epsilon = (a_1^T \cdot \epsilon)a_1 + (a_2^T \cdot \epsilon)a_2 + \hat{\epsilon}
$$

�Ə�����B

$a_1$��$a_2$�͒������钷��1��n�����x�N�g���ł���̂ŁA$a_1$��$a_2$���܂ސ��K�����x�N�g��$a_1, a_2, .., a_n$���Ƃ邱�Ƃ��ł���i���̂悤�Ȓ������W�n�����݂��邱�Ƃ́A�O�����E�V���~�b�g�̕��@�Ŏ��ۂɏ��������Ε����邪�����ł͏ȗ�����j�B�܂����̂Ƃ�n�sn��s�� $A=(a_1 a_2 ... a_n)^T$�͒����s��ɂȂ�B

�����ŁA �V����$z_i$��

$$
\begin{pmatrix} z_1
\\ :
\\ z_n \end{pmatrix}
=A \epsilon
=\begin{pmatrix} \frac{1}{\sqrt{n}}
& ... &
\frac{1}{\sqrt{n}}
\\
\frac{X_1 - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}}
& ... &
\frac{X_n - \overline{X}}{\sqrt{\sum_1^n (X_i - \overline{X})^2}}
\\* & ... & * \\: & & : \\* & ... & * \end{pmatrix}
\begin{pmatrix} \epsilon_1
\\ :
\\ \epsilon_n \end{pmatrix}
$$

�ƒ�߂�B$\epsilon_i$�݂͌��ɓƗ��ɐ��K���z$N(0,\sigma^2)$�ɏ]�����ƂƁA$a_1, a_2, .., a_n$�����K�����x�N�g���ł��邱�Ƃ���A$z_i$�͐��K���z$N(0,\sigma^2)$�ɏ]���i����͕��2.2�̏ؖ��Ɠ��l�Ɏ������Ƃ��ł���j�B�܂�$z_i$�݂͌��ɓƗ��ł���i����͕��2.3��$V_i$�̓Ɨ������ؖ������̂Ɠ��l�Ɏ������Ƃ��ł���j�B


�������A$\epsilon$�ɍ�����$A$�������A�ό`�����

$$
A\epsilon = A(a_1^T \cdot \epsilon)a_1 + A(a_2^T \cdot \epsilon)a_2 + A\hat{\epsilon}
$$

$$
\begin{pmatrix} a_1^T \cdot \epsilon
\\ :
\\ a_n^T \cdot \epsilon \end{pmatrix}
=(a_1^T \cdot \epsilon)
\begin{pmatrix} 1
\\ 0
\\ 0
\\ :
\\ 0 \end{pmatrix}
+
(a_1^T \cdot \epsilon)
\begin{pmatrix} 0
\\ 1
\\ 0
\\ :
\\ 0 \end{pmatrix}
+
A \hat{\epsilon}
$$

$$
\begin{pmatrix} 0
\\ 0
\\ z_3
\\ :
\\ z_n \end{pmatrix}
=A \hat{\epsilon}
$$

�ƂȂ�B����āA

$$
\sum_{i=1}^n \hat{\epsilon_i}^2
=\parallel \hat{\epsilon} \parallel^2
=\hat{\epsilon}^T \hat{\epsilon}
=\hat{\epsilon}^T (A^T A) \hat{\epsilon}
=(A \hat{\epsilon})^T (A \hat{\epsilon})
=\parallel A \hat{\epsilon} \parallel^2
=\sum_{i=3}^n z_i^2
$$

����������B$z_i/\sigma$�݂͌��ɓƗ��ɐ��K���z$N(0,1^2)$�ɏ]���̂ŁA

$$
\frac{\sum_{i=1}^n \hat{\epsilon_i}^2}{\sigma^2}
=\sum_{i=3}^n \bigl( \frac{z_i}{\sigma} \bigr)^2
$$

��n�[2�݂̌��ɓƗ��ɐ��K���z$N(0,1^2)$�ɏ]���ϐ��̓��a�ŕ\����Ă���A���2.4(1),(2)��莩�R�x$n-2$�̃J�C��敪�z$\chi^2(n-2)$�ɏ]���B

����ĕ��5.1�͐�������B

���Ȃ킿�A�O�L�̂悤�ɒ�`����$T_0,T_1$�͎��R�x$n-2$��$T$���z$T(n-2)$�ɏ]���B

  

## �Q�l����


- Robert V. Hogg, Joeseph McKean, Allen T Craig "Introduction to Mathematical Statistics, Fourth Edition"

- ���������u�m���Ɗm���ߒ��v

- �����]�u���哝�v��́v

- [�s�Ε��U�Ǝ��R�xn-1�̃J�C��敪�z | ���Z���w�̔���������](https://mathtrain.jp/chinijoproof)

- [���K��W�c���瓾����W�{���ςƕW�{���U�͓Ɨ��ł��邱�Ƃ̏ؖ� | ���H�n���w�̃A���J���g](http://physmath.main.jp/src/st-sample-mean-variance-independent.html)