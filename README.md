 <h1> <b>Python AST praksa</b> </h1>

<p> <b> Odradjene teme: </b></p> 
 <p>1. Koristeci python biblioteku AST u kombinaciji sa graphviz-om iscrtano apstraktno sintaksno stablo <br>
 za naredbu dodele i funkciju. </br></p>
 <p>2. Prolazak kroz AST koristeci visitor. ispisivanje cvorova stabla u infiksnom, prefiksnom i postfiksnom redosledu. </br> </p>
 <p>3. Prevodjenje uproscenog python-a u medjukodnu reprezentaciju pomocu 
 <a href="https://github.com/numba/llvmlite"> llvmite, </a></br>
 a zatim izvrsavanje tog medjukoda i ispisivanje rezultata funkcije. </br>
 </p>
 
 </br> <br>
 
 <p> Uprosceni python jezik radi samo sa promenjivama koje su tipa int32 (4 bajta) i konstantama (koje su takodje tipa int32).
 Podrzan je rad sa funkcijama, kontrole toka, naredbe dodele, return naredbe kao i pozivi tih funkcija. Od aritmetickih operacija podrzani su sabiranje i mnozenje, svi relacijski (and, or) i logicki operatori ('<', '>', '==', '<=', '>=', '!=').
</p>
 
 
 <h3>requires:</h3>
<ul> 
 <li> graphViz </li>
 <li>astor </li>
 <li> showast </li>
 <li> llvmite </li>
</ul>
