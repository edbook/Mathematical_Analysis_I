Diffurjöfnur
============

.. index::
    diffurjafna
    see: afleiðujafna; diffurjafna
    see: deildajafna; diffurjafna
    diffurjafna; stig

Diffurjöfnur
------------

.. _diffurjafna:

Skilgreining: Diffurjafna
~~~~~~~~~~~~~~~~~~~~~~~~~

Ritum :math:`y=y(x)` sem fall af :math:`x`.

*Diffurjafna* er jafna á forminu

.. math:: F(x, y, y', y'', \ldots, y^{(n)})=0

þar sem :math:`F` er fall (formúla) í :math:`n+1` breytistærð.

Jafnan er sögð vera af :math:`n`-ta *stigi* ef hæsta afleiða :math:`y`
sem kemur fyrir í formúlu er :math:`n`.

.. note:: 
    Deildajafna, afleiðujafna og diffurjafna eru samheiti yfir
    sama hlutinn. 

Dæmi
~~~~

Það að finna stofnfall fyrir fall :math:`f` er jafngilt því að leysa
fyrsta stigs diffurjöfnuna

.. math:: y'(x) = f(x),

eða með framsetningunni úr :ref:`skilgreiningunni <diffurjafna>` hér
að ofan,

.. math:: F(x,y') = f(x) - y'(x) = 0.

.. index::
    diffurjafna; aðgreinanleg
    
Skilgreining: Aðgreinanleg diffurjafna
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Fyrsta stigs diffurjafna sem má rita á forminu

.. math:: \frac{dy}{dx}=f(x)g(y)

kallast *aðgreinanleg* (e. seperable). Það er, þátta má hægri hliðina
þannig að annar þátturinn er bara fall af :math:`x` og hinn þátturinn er
bara fall af :math:`y`.

Umritum jöfnuna yfir á formið

.. math:: \frac{dy}{g(y)}=f(x)\,dx.

.. warning::
    Það má ekkert :math:`x` koma fyrir í vinstri hliðinni og
    ekkert :math:`y` má koma fyrir í hægri hliðinni.

Síðan heildum við báðar hliðar og reiknum stofnföllin hægra og vinstra 
megin í jöfnunni

.. math:: \int\frac{dy}{g(y)}=\int f(x)\,dx.

og munum eftir að setja inn heildunarfasta (einn er nóg). Þá höfum við
jöfnu sem lýsir sambandi :math:`x` og :math:`y`, og inniheldur engar
afleiður af :math:`y`. Út frá þeirri jöfnu má fá upplýsingar um
eiginleika lausnarinnar :math:`y`. Stundum er hægt að einangra :math:`y`
og fá þannig formúlu fyrir lausn diffurjöfnunar.

.. todo:: Dæmi


.. index::
    diffurjafna; línuleg

Línulegar fyrsta stigs diffurjöfnur
-----------------------------------

.. index:: 
    diffurjafna; hliðruð
    diffurjafna; óhliðruð

Skilgreining: Línuleg diffurjafna
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Diffurjafna á forminu

.. math:: a_n(x)y^{(n)}+a_{n-1}(x)y^{(n-1)}+\cdots+a_1(x)y'+a_0(x)y=f(x)

kallast *línuleg diffurjafna*. Hún er :math:`n`-ta stigs ef
:math:`a_n(x)` er ekki fastafallið :math:`0`.

Ef :math:`f` er fastafallið :math:`0` þá er jafnan sögð *óhliðruð* (e.
homogeneous) en ef :math:`f` er ekki fastafallið :math:`0` þá er hún
sögð *hliðruð* (e. nonhomogeneous).

.. index::
    diffurjafna; fyrsta stigs

Línulegar fyrsta stigs diffurjöfnur
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Almenna línulega fyrsta stigs jöfnu má rita á forminu

.. math:: y'+p(x)y=q(x).

Samsvarandi óhliðruð jafna er

.. math:: y'+p(x)y=0.

Skilgreinum :math:`\mu(x)=\int p(x)\,dx` (eitthvert stofnfall). Þá er

.. math:: y(x)=e^{-\mu(x)}\int e^{\mu(x)}q(x)\,dx

lausn á diffurjöfnunni.

.. warning:: 
    Þegar þið reiknið :math:`\mu(x)=\int p(x)\,dx` þá megið þið sleppa
    heildunarfastanum, en **ekki** þegar þið reiknið heildið
    :math:`\int e^{\mu(x)}q(x)\,dx`.

.. index::
    diffurjafna; annars stigs

Línulegar annars stigs diffurjafnur með fastastuðla
---------------------------------------------------

Skilgreining
~~~~~~~~~~~~

*Línuleg annars stigs diffurjafna með fastastuðla* er diffurjafna á
forminu

.. math:: ay''+by'+cy=f(x)

þar sem :math:`a, b` og :math:`c` eru fastar.

Jafnan er sögð *óhliðruð* (e. homogeneous) ef fallið :math:`f(x)` er
fastafallið 0.

.. index::
    diffurjafna; kennijafna

Skilgreining: Kennijafna
~~~~~~~~~~~~~~~~~~~~~~~~

Jafnan :math:`ar^2+br+c=0` kallast *kennijafna* (e. auxiliary equation)
diffurjöfnunnar :math:`ay''+by'+cy=0`.

Setning
~~~~~~~

Ef föllin :math:`y_1(x)` og :math:`y_2(x)` eru lausnir á diffurjöfnunni
:math:`ay''+by'+cy=0` þá er fallið

.. math:: y(x)=Ay_1(x)+By_2(x),

þar sem :math:`A` og :math:`B` eru fastar, líka lausn.

Ef :math:`y_2(x)` er ekki fastamargfeldi af :math:`y_1(x)` þá má skrifa
**sérhverja** lausn :math:`y(x)` á diffurjöfnunni :math:`ay''+by'+cy=0`
á forminu

.. math:: y(x)=Ay_1(x)+By_2(x),

þar sem :math:`A` og :math:`B` eru fastar.

Setning
~~~~~~~

Ef leysa á annars stigs óhliðraða diffurjöfnu með fastastuðla

.. math:: ay''+by'+cy=0

þá geta komið upp þrjú tilvik.

Tilvik I
    *Kennijafnan* :math:`ar^2+br+c=0` *hefur tvær ólíkar rauntölulausnir*
    :math:`r_1` og :math:`r_2`.

    Þá er fallið

    .. math:: y(x)=Ae^{r_1x}+Be^{r_2x}

    alltaf lausn sama hvernig fastarnir :math:`A` og :math:`B` eru
    valdir og sérhverja lausn má rita á þessu formi.

Tilvik II
    *Kennijafnan* :math:`ar^2+br+c=0` *hefur bara eina rauntölulausn*
    :math:`k=-\frac{b}{2a}`.

    Þá er fallið

    .. math:: y(x)=Ae^{kx}+Bxe^{kx}

    alltaf lausn sama hvernig fastarnir :math:`A` og :math:`B` eru
    valdir og sérhverja lausn má rita á þessu formi.

Tilvik III
    *Kennijafnan* :math:`ar^2+br+c=0` *hefur engar rauntölulausnir.*

    Setjum :math:`k=-\frac{b}{2a}` og
    :math:`\omega=\frac{\sqrt{4ac-b^2}}{2a}`.

    Rætur kennijöfnunnar eru :math:`r_1=k+i\omega` og
    :math:`r_2=k-i\omega`.

    Þá er fallið

    .. math:: y(x)=Ae^{kx}\cos(\omega x)+Be^{kx}\sin(\omega x)

    alltaf lausn sama hvernig fastarnir :math:`A` og :math:`B` eru
    valdir og sérhverja lausn má rita á þessu formi.

Setning
~~~~~~~

Látum :math:`y_{\rm p}(x)` vera einhverja lausn á hliðruðu jöfnunni

.. math:: ay''+by'+cy=f(x).

Látum :math:`y_1(x)` og :math:`y_2(x)` vera lausnir sem fást úr 21.4 á
óhliðruðu jöfnunni

.. math:: ay''+by'+cy=0.

.. todo:: laga tilvísun

Sama hvernig fastarnir :math:`A` og :math:`B` eru valdir þá er fallið

.. math:: y(x)=Ay_1(x)+By_2(x)+y_{\rm p}(x)

alltaf lausn á diffurjöfnunni :math:`ay''+by'+cy=f(x)` og sérhverja
lausn má skrifa á þessu formi.

Ágiskanir
---------

.. index::
    diffurjafna; ágiskun
    diffurjafna; sérlausn

.. _ágiskun:

Ágiskun
~~~~~~~

(Sjá ramma í grein 17.6)

.. todo:: tilvísun í bók?



Lausn á hliðruðu jöfnu :math:`ay''+by'+cy=f(x)` kallast *sérlausn*.
Stundum, ef :math:`f` er ekki of flókið, þá er mögulegt að giska á sérlausn.

Látum :math:`P_n(x)` standa fyrir einhverja :math:`n`-ta stigs margliðu
og látum :math:`A_n(x)` og :math:`B_n(x)` tákna :math:`n`-ta stigs
margliður með óákveðnum stuðlum.

-  Ef :math:`f(x)=P_n(x)` þá giskað á :math:`y_{\rm p}(x)=x^mA_n(x)`.

-  Ef :math:`f(x)=P_n(x)e^{rx}` þá giskað á
   :math:`y_{\rm p}(x)=x^mA_n(x)e^{rx}`.

-  Ef :math:`f(x)=P_n(x)e^{rx}\sin(kx)` þá giskað á
   :math:`y_{\rm p}(x)=x^me^{rx}[A_n(x)\cos(kx)+B_n(x)\sin(kx)]`.

-  Ef :math:`f(x)=P_n(x)e^{rx}\cos(kx)` þá giskað á
   :math:`y_{\rm p}(x)=x^me^{rx}[A_n(x)\cos(kx)+B_n(x)\sin(kx)]`.

Hér táknar :math:`m` minnstu töluna af tölunum 0, 1, 2 sem tryggir að
enginn liður í ágiskuninni sé lausn á óhliðruðu jöfnunni
:math:`ay''+by'+cy=0`.


Ef við erum búin að finna sérlausn :math:`y_p` og almenna lausn 
:math:`y` á óhliðruðu jöfnunni :math:`ay''+by'+cy=0`, þá er 
:math:`y+y_p` áfram lausn á hliðruðu jöfnunni. Reyndar er sérhver 
lausn á forminu á óhliðruðu jöfnunni á forminu :math:`y+y_p`, bara
með mismundandi :math:`A` og :math:`B` í :math:`y`.

.. todo::
    Dæmi: sérlausn, almenn lausn og svo upphafsskilyrðum bætt við. 

Samantekt
---------

Aðskiljanlegar jöfnur
~~~~~~~~~~~~~~~~~~~~~

Jöfnur sem hægt er að rita á forminu

.. math:: \frac{dy}{dx} = f(x)g(y),

má leysa með því að heilda og einangra :math:`y` út úr

.. math:: \int \frac 1{g(y)}\, dy = \int f(x)\, dx.

Línulegar fyrsta stigs jöfnur
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Lausn við jöfnu á forminu

.. math:: y'(x) + p(x)y = q(x)

er gefin með

.. math:: y(x) = e^{-\mu(x)} \int e^{\mu(x)} q(x)\, dx,

þar sem :math:`\mu(x) = \int p(x)\, dx`.

Línulegar annars stigs jöfnur með fastastuðla
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Lausn á :math:`ay''+by'+cy=0` er gefin með 

Tilvik I 
    :math:`y(x)=Ae^{r_1x}+Be^{r_2x}`   
    ef kennijafnan hefur tvær ólíkar rauntölulausnir :math:`r_1` og
    :math:`r_2`.

Tilvik II
    :math:`y(x)=Ae^{kx}+Bxe^{kx}`     
    ef kennijafnan :math:`ar^2+br+c=0` hefur bara eina tvöfalda rauntölulausn
    :math:`k=-\frac{b}{2a}`.

Tilvik III
    :math:`y(x)=Ae^{kx}\cos(\omega x)+Be^{kx}\sin(\omega x)`
    ef kennijafnan :math:`ar^2+br+c=0` hefur engar rauntölulausnir, 
    bara tvinntölulausnir :math:`r_1=k+i\omega` og
    :math:`r_2=k-i\omega`, þar sem 
    :math:`k=-\frac{b}{2a}` og :math:`\omega=\frac{\sqrt{4ac-b^2}}{2a}`.

Ĺausn hliðruðu jöfnunni  á :math:`ay''+by'+cy=f(x)` er mögulega hægt að finna
með :ref:`ásgiskun <Ágiskun>`. Sérhver lausn á óhliðruðu jöfnunni :math:`ay''+by'+cy=f(x)` er svo á forminu :math:`y+y_p` þar sem :math:`y` er
lausn á óhliðruðu jöfnunni.


