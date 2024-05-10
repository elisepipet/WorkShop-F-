# WorkShop-F#

<H1>Installation Dotnet</H1>

<h3>Sur Linux</h3>

```
sudo dnf install dotnet
```
<h3>Sur Ubuntu</h3>

```
sudo apt install dotnet
```
<h3>Sur MacOS</h3>

```
brew install dotnet
```
<h4>Pour checker l'installation</h4>

```
dotnet fsi
```

<h2>Petit exemple d'un Hello World en F#</h2>

```fsharp
let hello = printfn "%s" "Hello World from F#"

hello
```

```
dotnet fsi hello.fsx
```
```"Hello World from F#"```

<h1>Passons aux exercices :</h1>

<h2>Exercice 1</h2>
<p>Additionner deux nombres entiers: <br/>Ecrivez une fonction qui prend en paramètres deux Ints et renvoie leur somme.<br/></p>

<h2>Exercice 2</h2>

<p>Positif ou Negatif ? <br/>Ecrivez une fonction qui prend en paramètre un Int et renvoie <code>true</code> si il est positif et <code>false</code> si il est negatif.<br/></p>

<h2>Exercice 3</h2>

<p>Le plus petit : <br/>Ecrivez une fonction qui prend en paramètres deux Ints et renvoie le plus petit des deux.<br/></p>

<h2>Exercice 4</h2>

<p>Le plus grand : <br/>Ecrivez une fonction qui prend en paramètres deux Ints et renvoie le plus grand des deux.<br/></p>

<h2>Exercice 5</h2>

<p>Faire un tuple :<br/>Ecrivez une fonction qui prend en paramètres deux Ints et renvoie un tuple des deux arguments.<br/></p>

<h2>Exercice 6</h2>

<p>Faire un truple :<br/>Ecrivez une fonction qui prend en paramètres trois Ints et renvoie un truple des trois arguments.<br/></p>

<h2>Exercice 7</h2>

<p>Faire un swap :<br/>Ecrivez une fonction qui prend en paramètre un tuple et renvoie un nouveau tuple avec les deux éléments inversés.<br/></p>

<h2>Exercice 8</h2>

<p>Transformer un température en dégrés Celsuis en Fahrenheint :<br/>Ecrivez une fonction qui prend en paramètre une température en dégrés et la renvoie en Fahrenheint.<br/></p>

<h2>Exercice 9</h2>

<p>Factorielle d'un nombre :<br/>Ecrivez une fonction qui prend en paramètre un Int et renvoie le résultat de sa factorielle.<br/></p>

<h2>Exercice 10</h2>

<p>Est-ce un nombre premier ?<br/>Ecrivez une fonction qui prend en paramètre un Int et renvoie <code>true</code> si il est premier et <code>false</code> si il ne l'est pas.<br/></p>

<h2>Exercice 11</h2>

<p>Le enième de la liste : <br/>Ecrivez une fonction qui prend en paramètre un Int et une liste et renvoie l'element a la position indiqué en paramètre.<br/></p>

<h2>Exercice 12</h2>

<p>Tri d'une liste : <br/>Ecrivez une fonction qui prend en paramètre une liste et renvoie la liste triée.<br/></p>

<h2>Exercice 13</h2>

<p>Faire un getline : <br/>Ecrivez une fonction qui lit l'entrée standard et affiche son contenu.<br/></p>

<h2>Bonus...</h2>

<p>Moyenne des élements d'une liste de Ints<br/>
  Ajout d'un élément à une liste<br/>
Zip deux listes (une fonction qui prend en argument deux listes [a, b] [c, d] et renvoie [(a,c), (b, d)])</p>


