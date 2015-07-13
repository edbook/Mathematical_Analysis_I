Markgildi og samfelldni
=======================

.. note:: 
    **Nauðsynleg undirstaða**

    -  Jafna línu, P.2

    -  Jafna hrings, P.3

    -  Hliðrun og skölun grafs, P.3

    -  (Stranglega) minnkandi og (stranglega) vaxandi föll, 2.8

    -  Jafnstæð og oddstæð föll, P.4

    -  Margliður; deiling, þáttun og rætur, P.6

    -  Tölugildisfallið, P.1

    -  Þríhyrningsójafnan, P.1

    -  Formerkjafallið, :math:`sgn(x)`, P.5

Markgildi
---------

.. index::
    markgildi

Óformleg skilgreining á markgildi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Segjum að :math:`f(x)` *stefni á tölu* :math:`L` *þegar* :math:`x`
*stefnir á* :math:`a`, og ritum :math:`\lim_{x\rightarrow a} f(x)=L`, ef
við getum tryggt að :math:`f(x)` sé "eins nálægt :math:`L`" og við
viljum bara með því að velja :math:`x` "nógu nálægt* :math:`a`".

Skilgreining: Markgildi
~~~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili umhverfis
punktinn :math:`a`, nema hvað hugsanlega er :math:`f(a)` ekki
skilgreint. Við segjum að :math:`f(x)` *stefni á tölu* :math:`L` *þegar*
:math:`x` *stefnir á* :math:`a`, og ritum
:math:`\lim_{x\rightarrow a} f(x)=L`, ef eftirfarandi skilyrði er
uppfyllt:

Fyrir sérhverja tölu :math:`\epsilon>0` er til tala :math:`\delta>0`
þannig að um öll :math:`x` þannig að

.. math:: 0<|x-a|<\delta,\quad \text{ þá er } \quad |f(x)-L|<\epsilon.

Við segjum að talan :math:`L` sé *markgildi* :math:`f(x)` þegar
:math:`x` stefnir á :math:`a`.

.. todo::
    Mynd/Geogebra

.. note:: 
    Þegar athugað er hvort markgildið :math:`\lim_{x\rightarrow a} f(x)` er
    til og hvert gildi þess er þá skiptir ekki máli hvort :math:`f(a)` er
    skilgreint eða ekki.

Markgildi frá hægri
-------------------

.. index::
    markgildi; frá hægri

Óformleg skilgreining
~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili
:math:`(a,b)`. Segjum að :math:`f(x)` *stefni á tölu* :math:`L` *þegar*
:math:`x` *stefnir á* :math:`a` *frá hægri*, og ritum
:math:`\lim_{x\rightarrow a^+} f(x)=L`, ef við getum tryggt að
:math:`f(x)` sé "eins nálægt :math:`L`" og við viljum bara með því að
velja :math:`x>a` "nógu nálægt* :math:`a`".

Skilgreining (Markgildi frá hægri)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili
:math:`(a,b)`. Við segjum að :math:`f(x)` *stefni á tölu* :math:`L`
*þegar* :math:`x` *stefnir á* :math:`a` *frá hægri*, og ritum
:math:`\lim_{x\rightarrow a^+} f(x)=L`, ef eftirfarandi skilyrði er
uppfyllt.

Fyrir sérhverja tölu :math:`\epsilon>0` er til tala :math:`\delta>0`
þannig að um öll :math:`x` þannig að

.. math:: a<x<a+\delta,\quad \text{ þá er } \quad |f(x)-L|<\epsilon.

.. todo::
    Mynd/Geogebra


Markgildi frá vinstri
---------------------

.. index::
    markgildi; frá vinstri

Óformleg skilgreining
~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili
:math:`(b,a)`. Segjum að :math:`f(x)` *stefni á tölu* :math:`L` þegar
:math:`x` *stefnir á* :math:`a` *frá vinstri*, og ritum
:math:`\lim_{x\rightarrow a^-} f(x)=L`, ef við getum tryggt að
:math:`f(x)` sé "eins nálægt* :math:`L`" og við viljum bara með því að
velja :math:`x<a` "nógu nálægt* :math:`a`".

Skilgreining – Markgildi frá vinstri
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili
:math:`(b,a)`. Við segjum að :math:`f(x)` *stefni á tölu* :math:`L`
*þegar* :math:`x` *stefnir á* :math:`a` *frá vinstri*, og ritum
:math:`\lim_{x\rightarrow a^-} f(x)=L`, ef eftirfarandi skilyrði er
uppfyllt.

Fyrir sérhverja tölu :math:`\epsilon>0` er til tala :math:`\delta>0`
þannig að um öll :math:`x` þannig að

.. math:: a-\delta<x<a,\quad \text{ þá er } \quad |f(x)-L|<\epsilon.

.. todo::
    Mynd/Geogebra

Reiknireglur fyrir markgildi
----------------------------

Setning
~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili umhverfis
punktinn :math:`a`, nema hvað hugsanlega er :math:`f(a)` ekki
skilgreint. Þá er

.. math:: \lim_{x\rightarrow a} f(x)=L

ef og aðeins ef

.. math:: \lim_{x\rightarrow a^-} f(x)=L=\lim_{x\rightarrow a^+} f(x).

Setning
~~~~~~~

Gerum ráð fyrir að :math:`\lim_{x\rightarrow a}f(x)=L` og að
:math:`\lim_{x\rightarrow a}g(x)=M`. Þá gildir

(i)   :math:`\lim_{x\rightarrow a}\Big(f(x)+g(x)\Big)=L+M`.

(ii)  :math:`\lim_{x\rightarrow a}\Big(f(x)-g(x)\Big)=L-M`.

(iii) :math:`\lim_{x\rightarrow a}f(x)g(x)=LM`.

(iv)  :math:`\lim_{x\rightarrow a}kf(x)=kL`, þar sem :math:`k` fasti.

(v)   :math:`\lim_{x\rightarrow a}f(x)/g(x)=L/M`, að því gefnu að
      :math:`M\neq 0`.

(vi)  Gerum ráð fyrir að :math:`m` og :math:`n` séu heiltölur þannig að
      :math:`f(x)^{m/n}` sé skilgreint fyrir öll :math:`x` á bili
      :math:`(b,c)` umhverfis :math:`a` (en ekki endilega fyrir
      :math:`x=a`) og að :math:`L^{m/n}` sé skilgreint. Þá er
      :math:`\lim_{x\rightarrow a}f(x)^{m/n}=L^{m/n}`.

(vii) Ef til er bil :math:`(b,c)` sem inniheldur :math:`a` þannig að
      :math:`f(x)\leq g(x)` fyrir öll :math:`x\in (b,c)`, nema kannski
      :math:`x=a`, þá er
      :math:`\lim_{x\rightarrow a}f(x)=L\leq M=\lim_{x\rightarrow a}g(x)`.

.. warning::
    Liður (i) í setningunni á undan segir að ef markgildin
    :math:`\lim_{x\to a} f(x)` og :math:`\lim_{x\to a} g(x)` eru til þá sé
    markgildið :math:`\lim_{x\to a} (f(x)+g(x))` einnig til.

    En hún segir **ekki** að ef :math:`f` og :math:`g` eru föll þannig að
    markgildið :math:`\lim_{x\to a} (f(x)+g(x))` er til, að þá séu
    markgildin :math:`\lim_{x\to a} f(x)` og :math:`\lim_{x\to a} g(x)`
    einnig til.

.. index::
    klemmureglan
    
Setning – Klemmureglan
~~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að :math:`f(x)\leq
g(x)\leq h(x)` fyrir öll :math:`x` á bili :math:`(b, c)` sem inniheldur
:math:`a`, nema kannski :math:`x=a`. Gerum enn fremur ráð fyrir að

.. math:: \lim_{x\rightarrow a}f(x)=\lim_{x\rightarrow a}h(x)=L.

Þá er :math:`\lim_{x\rightarrow a}g(x)=L`.

.. todo::
    Mynd


Algeng markgildi
----------------

.. todo::
    Myndir og nokkrar sannanir


Sýnidæmi
~~~~~~~~

(i)   :math:`\lim_{x \to a} c = c`, :math:`c` fasti

(ii)  :math:`\lim_{x \to a} x = a`

(iii) :math:`\lim_{x \to a} |x| = |a|`


Sýnidæmi – Markgildi með sínus
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

(i)   

      .. math:: \lim_{x\to 0} \sin\left(\frac 1x\right) \quad \text{er ekki til}

(ii)  

      .. math:: \lim_{x\to 0} x\sin\left(\frac 1x\right) = 0

(iii) 

      .. math:: \lim_{x \to 0} \frac{\sin(x)}{x} = 1

Sýnidæmi – Markgildi með tölugildisfallinu
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

(i)   

      .. math:: \lim_{x\to 0^+} \frac x{|x|} = 1

(ii)  

      .. math:: \lim_{x\to 0^-} \frac x{|x|} = -1

(iii) 

      .. math:: \lim_{x\to 0} \frac x{|x|} \quad \text{er ekki til}

      
Markgildi þegar x stefnir á óendanlegt
--------------------------------------


.. image:: ./myndir/kafli02/06_liminf.png

.. index::
    markgildi; þegar x stefnir á óendalegt


Óformleg skilgreining
~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á bili
:math:`(a, \infty)`. Segjum að :math:`f(x)` *stefni á tölu* :math:`L`
*þegar* :math:`x` *stefnir á* :math:`\infty`, og ritum
:math:`\lim_{x\rightarrow \infty} f(x)=L`, ef við getum tryggt að
:math:`f(x)` sé eins "nálægt :math:`L`" og við viljum bara með því að
velja ":math:`x` nógu stórt".

Skilgreining
~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á bili
:math:`(a,\infty)`. Við segjum að :math:`f(x)` *stefni á tölu* :math:`L`
*þegar* :math:`x` *stefnir á* :math:`\infty`, og ritum
:math:`\lim_{x\rightarrow \infty} f(x)=L`, ef eftirfarandi skilyrði er
uppfyllt:

Fyrir sérhverja tölu :math:`\epsilon>0` er til tala :math:`R`
þannig að um öll :math:`x>R` gildir að :math:`|f(x)-L|<\epsilon`.

Fyrir :math:`-\infty` er þetta gert með sama sniði.

Óformleg skilgreining
~~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á bili
:math:`(-\infty, a)`. Segjum að :math:`f(x)` *stefni á tölu* :math:`L`
*þegar* :math:`x` *stefnir á* :math:`-\infty`, og ritum
:math:`\lim_{x\rightarrow -\infty} f(x)=L`, ef við getum tryggt að
:math:`f(x)` sé eins "nálægt :math:`L`" og við viljum bara með því að
velja :math:`x` sem "nógu stóra* mínus tölu".

Skilgreining
~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á bili
:math:`(-\infty,a)`. Við segjum að :math:`f(x)` *stefni á tölu*
:math:`L` *þegar* :math:`x` *stefnir á* :math:`-\infty`, og ritum
:math:`\lim_{x\rightarrow -\infty} f(x)=L`, ef eftirfarandi skilyrði er
uppfyllt:

Fyrir sérhverja tölu :math:`\epsilon>0` er til tala :math:`R`
þannig að um öll :math:`x<R` gildir að :math:`|f(x)-L|<\epsilon`.

Óendanlegt sem markgildi
-----------------------------------------------

.. index::
    markgildi; óendanlegt sem markgildi

Óformleg skilgreining
~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili umhverfis
punktinn :math:`a`, nema hvað hugsanlega er :math:`f(a)` ekki
skilgreint. Segjum að :math:`f(x)` *stefni á* :math:`\infty` *þegar*
:math:`x` *stefnir á* :math:`a`, og ritum
:math:`\lim_{x\rightarrow a} f(x)=\infty`, ef við getum tryggt að
:math:`f(x)` sé *hversu stórt sem við viljum* bara með því að velja
:math:`x` *nógu nálægt* :math:`a`.

Skilgreining
~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili umhverfis
punktinn :math:`a`, nema hvað hugsanlega er :math:`f(a)` ekki
skilgreint. Við segjum að :math:`f(x)` *stefni á* :math:`\infty` *þegar*
:math:`x` *stefnir á* :math:`a`, og ritum
:math:`\lim_{x\rightarrow a} f(x)=\infty`, ef eftirfarandi skilyrði er
uppfyllt.

Fyrir sérhverja tölu :math:`B` er til tala :math:`\delta>0` þannig
að um öll :math:`x` þannig að :math:`0<|x-a|<\delta` gildir að
:math:`f(x)>B`.

.. note:: 
    Athugið að :math:`\infty` er **ekki** tala. Þó að
    :math:`\lim_{x\rightarrow a} f(x)=\infty` þá er samt sagt að markgildið
    :math:`\lim_{x\rightarrow a} f(x)` sé ekki til.

Óformleg skilgreining
~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili umhverfis
punktinn :math:`a`, nema hvað hugsanlega er :math:`f(a)` ekki
skilgreint. Segjum að :math:`f(x)` *stefni á* :math:`-\infty` *þegar*
:math:`x` *stefnir á* :math:`a`, og ritum
:math:`\lim_{x\rightarrow a} f(x)=-\infty`, ef við getum tryggt að
:math:`f(x)` sé "hversu lítið sem við viljum" bara með því að velja
:math:`x` "nógu nálægt :math:`a`".

Skilgreining
~~~~~~~~~~~~

Gerum ráð fyrir að fall :math:`f` sé skilgreint á opnu bili umhverfis
punktinn :math:`a`, nema hvað hugsanlega er :math:`f(a)` ekki
skilgreint. Við segjum að :math:`f(x)` *stefni á* :math:`-\infty`
*þegar* :math:`x` *stefnir á* :math:`a`, og ritum
:math:`\lim_{x\rightarrow a} f(x)=-\infty`, ef eftirfarandi skilyrði er
uppfyllt.

Fyrir sérhverja tölu :math:`B` er til tala :math:`\delta>0` þannig
að um öll :math:`x` þannig að

:math:`0<|x-a|<\delta` gildir að :math:`f(x)<B`.

.. note:: 
    Athugið að :math:`-\infty` er **ekki** tala. Þó að
    :math:`\lim_{x\rightarrow a} f(x)=-\infty` þá er samt sagt að markgildið
    :math:`\lim_{x\rightarrow a} f(x)` sé ekki til.

.. index:: 
    samfelldni
    samfelldni; í punkti

Samfelldni
----------

.. index::
    innri punktur

Skilgreining
~~~~~~~~~~~~

Látum :math:`A\subseteq {{\mathbb  R}}` og :math:`x\in A`. Við segjum að
:math:`x` sé *innri punktur* :math:`A` ef :math:`A` inniheldur opið bil
umhverfis :math:`x`, það er að segja til er tala :math:`\delta>0` þannig
að :math:`(x-\delta, x+\delta)\subseteq
A`.

Ef :math:`x` er ekki innri punktur :math:`A` og :math:`x\in A` þá segjum
við að :math:`x` sé *jaðarpunktur* :math:`A`.


.. index:: 
    samfelldni; í punkti

Skilgreining
~~~~~~~~~~~~

Látum :math:`f` vera fall og :math:`c` innri punkt skilgreiningarsvæðis
:math:`f`. Sagt er að :math:`f` sé *samfellt í punktinum* :math:`c` ef

.. math:: \lim_{x\rightarrow c}f(x)=f(c).

Setning
~~~~~~~

Látum :math:`f` og :math:`g` vera föll. Gerum ráð fyrir að :math:`c` sé
innri punktur skilgreiningarsvæðis beggja fallanna og að bæði föllin séu
samfelld í punktinum :math:`c`. Þá eru eftirfarandi föll samfelld í
:math:`c`:

(i)   :math:`f+g`

(ii)  :math:`f-g`

(iii) :math:`fg`

(iv)  :math:`kf`, þar sem :math:`k` er fasti

(v)   :math:`f/g`, ef :math:`g(c)\neq 0`

(vi)  :math:`\Big(f(x)\Big)^{1/n}`, að því gefnu að :math:`f(c)>0` ef
      :math:`n` er slétt tala og :math:`f(c)\neq 0` ef :math:`n<0`.

Setning – Samskeyting samfelldra falla
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Látum :math:`g` vera fall sem er skilgreint á opnu bili umhverfis
:math:`c` og samfellt í :math:`c` og látum :math:`f` vera fall sem er
skilgreint á opnu bili umhverfis :math:`g(c)` og samfellt í
:math:`g(c)`. Þá er fallið :math:`f\circ g` skilgreint á opnu bili
umhverfis :math:`c` og er samfellt í :math:`c`.


.. note:: 
    Ef fall er skilgreint með formúlu og skilgreingamengið er ekki tilgreint
    sérstaklega, þá er venjan að líta alla þá punkta þar sem formúlan gildir
    sem skilgreingarmengi fallsins

    
.. index:: 
    samfelldni, samfellt fall
    
Skilgreining
~~~~~~~~~~~~

Við segjum að fall :math:`f` sé *samfellt* ef það er samfellt í
sérhverjum punkti skilgreingarmengisins.

Dæmi
~~~~

Eftirfarandi föll eru samfelld

(i)   margliður

(ii)  ræð föll

(iii) ræð veldi

(iv)  hornaföll; :math:`\sin`, :math:`\cos`, :math:`\tan`

(v)   tölugildisfallið :math:`|x|`

Að búa til samfelld föll
~~~~~~~~~~~~~~~~~~~~~~~~

Með því að nota föllin úr dæminu á undan sem efnivið þá getum við búið
til fjölda samfelldra fall með því að beita aðgerðunum úr Setningu 3.14
og Setningu 3.15.

.. index::
    samfelldni; frá hægri/vinstri

Hægri/vinstri samfelldni
------------------------

Rifjum upp skilgreininguna á samfelldni.

Skilgreining
~~~~~~~~~~~~

Látum :math:`f` vera fall og :math:`c` innri punkt skilgreiningarsvæðis
:math:`f`. Sagt er að :math:`f` sé *samfellt í punktinum* :math:`c` ef

.. math:: \lim_{x\rightarrow c}f(x)=f(c).

Athugasemd
~~~~~~~~~~

Þessi skilgreining virkar aðeins fyrir innri punkta
skilgreiningarsvæðisins. Þannig að ef ætlunin er að rannsaka samfelldni
í jaðarpunktum þá gengur þessi skilgreining ekki. Hins vegar getum við
útvíkkað skilgreininguna á samfelldni fyrir hægri og vinstri endapunkta
bila með því að einskorða okkur við markgildi frá vinstri og hægri.

Skilgreining
~~~~~~~~~~~~

(i)  Fall :math:`f` er *samfellt frá hægri í punkti* :math:`c` ef
     :math:`\lim_{x\rightarrow c^+}f(x)=f(c)`.

     Hér er gert ráð fyrir að fallið :math:`f` sé amk. skilgreint á
     bilinu :math:`[c, a)`.

(ii) Fall :math:`f` er *samfellt frá vinstri í punkti* :math:`c` ef
     :math:`\lim_{x\rightarrow c^-}f(x)=f(c)`.

     Hér er gert ráð fyrir að fallið :math:`f` sé amk. skilgreint á
     bilinu :math:`(a, c]`.

Uppfærum nú skilgreiningu [skilgr:samfellt:sub:`f`\ all].

.. index:: 
    fall; samfellt

Skilgreining (uppfærð)
~~~~~~~~~~~~~~~~~~~~~~

Gerum ráð fyrir að :math:`f` sé fall sem er skilgreint á mengi
:math:`A`, þar sem :math:`A` er sammengi endanlega margra bila. Við
segjum að fallið :math:`f` sé *samfellt* ef það er samfellt í öllum
innri punktum skilgreingarmengisins, og ef það er samfellt frá
hægri/vinstri í jaðarpunktum skilgreingarmengisins, eftir því sem við á.

.. note::
    Ef fall er samfellt á opnu bili :math:`(a,b)`, og ef :math:`a<c<d<b`, þá
    er fallið einnig samfellt á bilinu :math:`[c,d]`.

Eiginleikar samfelldra falla
----------------------------

.. index::
    há- og lággildislögmálið


Setning – Há- og lággildislögmálið
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Látum :math:`f` vera samfellt fall skilgreint á lokuðu takmörkuðu bili
:math:`[a,b]`. Þá eru til tölur :math:`x_1` og :math:`x_2` í
:math:`[a,b]` þannig að fyrir allar tölur :math:`x` í :math:`[a,b]` er

.. math:: f(x_1)\leq f(x)\leq f(x_2).

Þetta þýðir að samfellt fall :math:`f` á lokuðu og takmörkuðu bili
:math:`[a,b]` tekur bæði hæsta og lægsta gildi á bilinu. Hæsta gildið er
þá :math:`f(x_2)` og lægsta gildið er :math:`f(x_1)`.

.. note::
    Það er mögulegt að fallið taki há/lággildi sitt í fleiri en einum
    punkti.

.. index::
    milligildissetningin


Setning: Milligildissetningin
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Látum :math:`f` vera samfellt fall skilgreint á lokuðu takmörkuðu bili
:math:`[a,b]`. Gerum ráð fyrir að :math:`s` sé tala sem liggur á milli
:math:`f(a)` og :math:`f(b)`. Þá er til tala :math:`c` sem liggur á
milli :math:`a` og :math:`b` þannig að :math:`f(c)=s`.

.. ggb:: zEQQcGcQ
    :width: 700
    :height: 500
    :img: 10_milligildissetn.png
    :imgwidth: 8cm

Fylgisetning
~~~~~~~~~~~~

Ef :math:`P(x)=a_nx^n+a_{n-1}x^{n-1}+\cdots+a_1x+a_0` er margliða af
oddatölu stigi, þá er til rauntala :math:`c` þannig að :math:`P(c)=0`.

.. todo::
    Þarf að setja sannanir undir > takk, show/hide fídus

.. begin-toggle::
    :label: Sýna/fela sönnun

|

**Sönnun**

Gerum ráð fyrir að :math:`a_n>0`. Þá er
:math:`\lim_{x\to -\infty} P(x) = -\infty` og
:math:`\lim_{x\to \infty} P(x) = \infty`. Það þýðir að til eru tölur
:math:`a` og :math:`b` þannig að :math:`P(a)<0` og :math:`P(b)>0`. Með
því að beita Milligildissetningunni á fallið :math:`P` á bilinu
:math:`[a,b]` og með :math:`s=0` þá fæst að til er núllstöð á bilinu
:math:`[a,b]`.

Ef :math:`a_n < 0` þá víxlast markgildin að ofan en röksemdafærslan er
að öðru leyti eins.

|

.. end-toggle::

|

