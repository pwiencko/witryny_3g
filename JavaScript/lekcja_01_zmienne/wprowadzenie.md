# Zmienne
W trakcie tworzenia dowolnej aplikacji, przyjdzie nam zmierzyc się z problemem związanym z przechowywaniem danych.

Niektóre dane musimy wykorzystac wielokrotnie (i nie chcemy, aby uzytkownik podawał nam te same dane wielokrotnie). Z innych nie chcemy korzystac od razu, a odłozyc to w czasie (np. na koniec wykonania programu). 

Z pomocą przychodzą nam wtedy **zmienne**. Pozwalają one nam na przechowywanie danych. Są niejako pudełkami, które mozemy dowolnie podpisac (nazwa zmiennej) i wsadzic tam dowolną rzecz (wartośc). 

W JavaScripcie nie musimy przejmowac się tym, ze w pudełku będzie znajdowała się rzecz niepasująca **rozmiarem** albo **rodzajem** (np. przyprawy w pudełku po butach albo słoń w słoiku). Zmienne mają tak zwane miękkie (dynamiczne) typowanie i w zalezności od tego co chcemy do nich włozyc - dopasują się same. 

Aby skorzystac ze zmiennej musimy ją najpierw zadeklarowac. W JavaScripcie uzywamy do tego słowa kluczowego **let**. Np. w taki sposób:

    let nazwa_zmiennej = "wartosc zmiennej";

Aha - przy okazji. Teksty w JavaScripcie podajemy w cudzysłowie. :) **Warto zapamiętac**. 

Jezeli zmienna jest juz zadeklarowana - mozemy dowolnie z niej korzystac (jako np. parametr funkcji):

    console.log(nazwa_zmiennej); //wyświetli nam w konsoli wartośc zmiennej.
 albo edytowac (przypisując do niej inną wartośc):

    nazwa_zmiennej = 123;

