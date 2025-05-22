# Regresja liniowa — w pigułce

Regresja liniowa to jedno z najstarszych, ale wciąż najczęściej używanych narzędzi analitycznych.  
Jej celem jest **oszacowanie zależności liniowej** pomiędzy zmienną zależną  \(y\) a jedną lub wieloma zmiennymi niezależnymi  \(x_1,\,x_2,\dots,x_p\).

$$
\hat y = \beta_0 + \beta_1 x_1 + \dots + \beta_p x_p
$$

Kluczowe założenia modelu:

* liniowość relacji (brak potęg czy logarytmów w parametryzacji),  
* reszty o średniej równej 0 i jednakowej wariancji (homoskedastyczność),  
* brak silnej współliniowości między zmiennymi objaśniającymi.

W praktyce regresja liniowa służy nie tylko do predykcji, ale i do **wyjaśniania wpływu** poszczególnych czynników, bo współczynniki \(\beta\) mają intuicyjną interpretację: o ile średnio zmieni się \(y\) przy jednostkowej zmianie danego \(x_j\), zakładając niezmienność pozostałych.

*Źródła polecane do dalszej lektury:*  
— A. Gelman *Regression and Other Stories*  
— J. Montgomery *The Fundamentals of Linear Regression*
