# 8086-assembler

Cette commande, écrite en Pascal (Turbo Pascal ou Free Pascal), permet de compiler de l'assembleur 8086.

<h3>Syntaxe</h3>

<b>ASM8086</b> [source[.A86] [destination[.H86]]] [/C] [/INLINE|/TP]

<h3>Paramètres</h3>

<table>
  <tr>
    <th>Nom</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><i>source</i></td>
    <td>Nom du fichier contenant le source assembleur 8086.</td>
  </tr>
  <tr>
    <td><i>destination</i></td>
    <td>Nom du fichier contenu le code machine en hexadecimal.</td>
  </tr>
  <tr>
    <td><b>/B</b></td>
    <td>Fabrique un fichier binaire (.BIN).</td>
  </tr>
  <tr>
    <td><b>/C</b></td>
    <td>Sortie en commentaires des instructions assembleurs.</td>
  </tr>
  <tr>
    <td><b>/INLINE</b></td>
    <td>Sortie en instruction INLINE du Turbo Pascal.</td>
  </tr>
  <tr>
    <td><b>/TP</b></td>
    <td>Sortie en instruction INLINE du Turbo Pascal.</td>
  </tr>
  <tr>
    <td><b>--version</b></td>
    <td>Indique la version de la commande</td>
  </tr>
</table>

<h2>Quoi de neuf</h2>

<h4>Version 1.0.1</h4>
<ul>
  <li>Ajout d'un paramètre "--version"</li>
  <li>Support les nombres hexadécimal se terminant par 'h' et non seulement commençant par $.</li>
  <li>Ajout du support de l'anglais</li>
</ul>


<h4>Version 1.0.0</h4>
<ul>
  <li>Première version</li>
</ul>

<h3>Exemple</h3>

L'exemple suivant permet de compiler le programme assembleur de démonstration et générer un binaire :

<pre>
<b>asm8086</b> samples\EXITEXE.A86 /B
</pre>
