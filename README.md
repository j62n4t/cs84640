java c
Fundamentals of Digital Signal Processing 
Coursework Assignment 2 
1.      Consider   an   impulse   response   h[n]   such   that   h[n]   =   0   for   n   < 0 and n >   M   ,   and   h[n]   =   -h[M -   n] for 0 ≤ n   ≤ M where   M   is   an   odd   integer.
a)   Express the   Fourier transform. of   h[n] in   the   form.	
H(ejω ) = ejf   (ω)A(ω)   ,
where f   (ω) and A(ω) are   real-valued functions of ω .   Determine   f   (ω)   and   A(ω).
b)   Provide   an   example   of   such   an   impulse   response   h[n] for   M   =   7 and ﬁnd the corresponding   f   (ω) and   A(ω).
2.   Read Section 7.2.2 from the textbook and pay particular attention to   Example   7.7.   We wish to   design a generalized   linear phase ﬁlter satisfying the   speciﬁcations
0.95   < jH(ejω )j < 1.05, jH(ejω )j   < 0.15,
0   ≤   jωj   ≤   0.5π   0.6π   ≤   jωj   ≤   π                                                                                (1)by   applying   a   Kaiser   window   to   the   impulse   response   hd   [n] of   the   ideal   low-pass   ﬁlter   with   cut-   off   frequency   ωc         =   0.55π   .         Find   the   value   β   and   the   window   length   M   required   to   satisfy   the   speciﬁcations.   Plot the corresponding   Kaiser window and the   impulse   response of the designed   low-pass ﬁlter.   Plot the   magnitude   response
20   log10   jH(ejω )j
of   the   designed ﬁlter   in   the   range   ω   ∈   (0,   π) with   resolution   2π/1024 or   higher.3.   Suppose that we are given a continuous-time   low-pass   ﬁlter with   frequency   response   Hc   (jΩ) such that
1   - δ1      ≤   jHc (jω)j   ≤   1 + δ1   ,   jHc (jΩ)j   ≤ δ2   ,
0 ≤ jΩj ≤ Ωp               jΩj ≥ Ωs                                       . (2)
A   set   of   discrete-time   代 写Fundamentals of Digital Signal Processing Coursework Assignment 2Matlab
代做程序编程语言low-pass ﬁlters   can   be   obtained from   Hc   (s) by   using the   bilinear   transfor-   mation,i.e. 
H(z) = Hc   (s)js=(2/Td)(1-z-1)/(1+z-1)      ,
with Td    variable.
a)   Assuming   that   Ωp    is   ﬁxed,   ﬁnd   Td    such   that   the   corresponding   pass-band   cut-off   frequency   of   the   discrete-time   system   is   ωp    = π/2.
b)   With   Ωp      ﬁxed,   sketch ωp   ,   the   cut-off   frequency   of   the   discrete-time ﬁlter,   as   a   function   of   Td   ,   for   0   < Td < ∞ .
c) With   Ωp      and   Ωs    ﬁxed   sketch   the   width   of   the   transition   region,   △ω   = ωs    -   ωp      as   a   function   of Td   , for   Td      in   the   range   0   < Td < ∞ .4.    Suppose   that   H1   (z),   H2   (z)   and   H(z)   are   transformed   versions   of   Hc1(s),   Hc2(s)   and   Hc   (s),   respectively,   obtained   using   impulse   invariance   or the   bilinear transformation.    Which   of the two   methods   will   guarantee   that   H(z) = H1   (z) + H2   (z) whenever   Hc   (s) = Hc1(s) + Hc2(s).
5.   Suppose that we are given an   ideal   low-pass discrete-time ﬁlter with frequency   responseH(ejω) = ( 10,, π/ |ω|4< π/ < |ω 4 | ≤ π .
We wish to derive   new ﬁlters from this prototype   by   manipulating   its   impulse   response   h[n].
a)   Plot the frequency   response for the ﬁlter whose   impulse   response   is h1   [n] = h[2n].
b)   Plot the frequency   response of the ﬁlter whose   impulse   response   ish2[h] = ( h0,[n/2], notherwise= 0, ±2, ±4, . . ..
c)   Plot the frequency   response of the ﬁlter whose   impulse   response   is
h3   [n] = ejπnh[n]   =   (-1)nh[n]   .
There   is   no   need to plot these frequency   responses   in   matlab, a sketch would   be sufﬁcient.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
