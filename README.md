# CSharpFree
NetAcademia ingyenes C# bevezető

```
<reklám>
```
Ha tetszik amit csinálunk, és valakit komolyabban érdekel a C#, az még becsatlakozhat a [C# alapok](http://www.netacademia.hu/2016c%23-) tanfolyamunkra. Ennek az elvégzése után már nagyon komoly és alapos C#/.NET tudást ismerhetsz meg, érdemes megnézni a tanfolyami tematikát. 

Sőt, [előfizetés keretében](http://netacademia.hu/Subscriptions) is csatlakozhatsz, ekkor már nem csak ez a tanfolyam, hanem egy évig akár a Netakadémiánál megtartandó, valamint megtartott és felvételen elérhető **összes** tanfolyamhoz hozzáférsz. Így [multiplatformos C# kliens alkalmazások irását](http://www.netacademia.hu/2016crossplatformkliens-cross---platform-kliens-oldali-fejlesztes-net-ben) (windows/android/ios telefonok, desktop) *és* [multiplatformos C# szerveralkalmazások fejlesztését](http://www.netacademia.hu/2016crossplatform-cross---platform-szerver-oldali-fejlesztes-aspnet-mvc-hasznalataval) (windows, linux, osx) **is** megtanulhatod. 

Ha az adatbázisok a kérdés, [akkor is van ötletünk](http://www.netacademia.hu/2016nosql-nosql-vs-sql).

[A java sem az ellenségünk, sőt](http://www.netacademia.hu/2016java-java-halado)! 

És ez csak még csak 5 (azaz csak **ÖT**) tanfolyam a jelenleg elérhető 109-ből!

Nem kell most mindent eldönteni. Vannak [ingyenes tanfolyamaink](http://www.netacademia.hu/), vess rájuk egy pillantást.

```
</reklám>
```

## Előkészületek
A tanfolyamon **Windows** operációs rendszeren futó [Visual Studio 2015 Community](https://www.visualstudio.com/vs/community/) fejlesztői keretrendszert fogunk használni.

### Visual Studio 2015 Community telepítése
A tanfolyamon ezt az alkalmazást fogjuk használni. Ingyenesen elérhető önálló fejlesztők, nyílt forráskódú projektek, akadémiai kutatók számára. Továbbá oktatási célokra és kis (max 5 fős) fejlesztőcsapatoknak.

Letölteni az előző linkről vagy [innen lehet](https://www.visualstudio.com/free-developer-offers/). Ehhez a tanfolyamhoz telepíteni az alapértelmezett beállításokkal elég.

Vagy, ha valaki szeret újat kipróbálni, akkor telepítheti [Chocolatey](https://chocolatey.org/) csomagkezelővel is. 

[Telepítés](https://chocolatey.org/install): ehhez indítsunk egy adminisztrátori parancssort ([elevated command prompt](http://www.computerhope.com/jargon/e/elevated.htm)), majd tegyük vágólapra ezt (igen, az egészet!):

**@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"**

majd a parancssorunkba illesszük be és futtassuk le. 

Ezzel telepítettünk egy csomagkezelőt, innentől kezdve nem kell letölteni és telepíteni kattintgatásokkal az alkalmazásainkat, hanem a csomagkezelőnkre bizhatjuk a dolgot, legalábbis [jelenleg már több, mint 4000 alkalmazás esetében](https://chocolatey.org/packages).

Ha van csomagkezelőnk, a Visual Studio Community telepítése [adminisztrátori parancssorból így megy](https://chocolatey.org/packages/VisualStudio2015Community): 

**cinst visualstudio2015community**

Ezzel meg is vagyunk az előkészületekkel, a többit a tanfolyamon folytatjuk!
