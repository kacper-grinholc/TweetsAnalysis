<div style="text-align: left"> Kacper Grinholc </div> 
<div style="text-align: left"> 17.06.2022 </div>

<div style="text-align: center"> <h1> Inteligencja obliczeniowa </h1> </div>
<div style="text-align: center"> <h2> Zadanie projektowe nr2 </h2> </div>
<div style="text-align: center"> <h3> Analiza tweetów na temat państw </h3> </div>
<br /><br />

Z okresu 1.06.2021 do 30.05.2022 pobrano 200 tweetów dziennie w języku angielskim dla każdego z hashtagów: #Ukraine, #Russia, #Israel, #Poland oraz #Turkey.
Zrobiono wordcloud z tweetów podano je ocenie algorytmom z biblioteki vader oraz text2emotion i wyniki zaprezenotwano na wykresach.
<br /><br />

<div style="text-align: center"> <h1> WordCloud </h1> </div>
<br />

![Alt Text](Gifs/Ukraine.gif)

![Alt Text](Gifs/Russia.gif)

![Alt Text](Gifs/Israel.gif)

![Alt Text](Gifs/Poland.gif)

![Alt Text](Gifs/Turkey.gif)

W większości państw od lutego 2022 mówiło się o ukrainie oraz rosji, po za tym w większości państw widać, że głównym tematem jest polityka, dodatkowo w polsce w okresie czerwiec - wrzesień dużo tweetów zawierało słowa związane z grami np. steam, gaming, pcgaming, gamedev, gamingnews.

<br /><br />


<div style="text-align: center"> <h1> Vader </h1> </div>
<br />

![Alt Text](Plots/Ukraine.jpg)

![Alt Text](Plots/Russia.jpg)

Dla Rosji oraz Ukrainy negatywnośc tweetów cały czas rosła, szczególnie od momentu rozpoczęcia wojny

![Alt Text](Plots/Israel.jpg)

Dla Izraela negatywnośc wzrosła bardzo w kwietniu 2022 kiedy to wybuchły starcia między Izraelczykami a Palestyczykami

![Alt Text](Plots/Poland.jpg)

Dla Polski poziom tweetów raczej się nie zmieniał, zwiększył się tylko w listopadzie 2021 kiedy to uchodźcy próbowali wydostać się z białorusko-polskiej granicy

![Alt Text](Plots/Turkey.jpg)

Dla Turcji tweety były również stałe przez większość czasu, jednak ilośc pozytywnych tweetów wzrosła wraz ze świętem dziękczynienia w USA

<br /><br />

<div style="text-align: center"> <h1> Text2emotion </h1> </div>
<br />


<div style=
"text-align: center"> <h3> Ukraina </h3> </div>
<br />

![Alt Text](RadarGifs/Ukraine.gif)

<div style="text-align: center"> <h3> Rosja </h3> </div>
<br />

![Alt Text](RadarGifs/Russia.gif)

<div style="text-align: center"> <h3> Izrael </h3> </div>
<br />

![Alt Text](RadarGifs/Israel.gif)

<div style="text-align: center"> <h3> Polska </h3> </div>
<br />

![Alt Text](RadarGifs/Poland.gif)

<div style="text-align: center"> <h3> Turcja </h3> </div>
<br />

![Alt Text](RadarGifs/Turkey.gif)

W większości państw dominuje strach ponieważ text2emotion słowa związane z polityką uznaje za słowa należące do tej kategorii. Dla losowych pobranych tweetów przeanalizowałem jakie słowa wywołują strach według tej biblioteki i oto niektóre z nich:

![Alt Text](Test.png)

Wniosek jest taki, że żadna z tych bibliotek nie ocenia dobrze tekstu, może być to również spowodowany złymi danymi ponieważ uważam, że tweety nie są najlepszymi danymi do oceniania.


