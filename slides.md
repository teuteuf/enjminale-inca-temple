```c#
//TODO: This code looks like an Inca Temple. To refactor.
public void Nguaaah() {
	throdagl.h'n'ghft.fhtagn.nnnhupadg();
	Nyarlathotep = yhah hrii + ebunma.suhn();
	shtunggli.ngnw.ep.mg.chtenff.shoggyar();
} 
```
![](images/indianaswap.webp)  
_"Si je touche à ça... Est-ce que tout va péter..?"_

Note:
Hello tout le monde !
Je viens vous parler d'un sentiment que j'ai pu observer plus d'une fois
face à une code base qui grossit et qui commence à prendre de l'age

---

### Qui suis-je ?
- *'13 - '15 :* ENJMIN P10 ⭐  
- *'15 - '17 :* Ubisoft Mobile  
![](images/ubimobile.png)<!-- .element height="100px" -->
![](images/smurfs.jpg)<!-- .element height="100px" -->
![](images/smurfs_banniere.jpg)<!-- .element height="100px" -->
- *'17 - '19 :* OCTO Technology (ESN/SSII)  
![](images/octo.jpg)<!-- .element height="100px" -->
![](images/thereisabetterway.png)<!-- .element height="100px" -->
![](images/culturecode.png)<!-- .element height="100px" -->
- Bientôt à Montpellier ! *#LookingForJob*

---


```
//TODO: This code looks like an Inca Temple. To refactor.
```

![](images/proglife.png)<!-- .element class="fragment" data-fragment-index="3" -->

Note:
Vrai commentaire trouvé dans le code des smurfs  
quand je suis arrivé en stage...
Toujours là 2 ans après...
Un exemple parmis tant d'autres...
---

### Pourquoi ce code est resté comme ça tout ce temps ?

![](images/codersanstests.jpg)<!-- .element: class="fragment" data-fragment-index="1" height="400px" -->  

Note:
Pas confiance en notre codebase  
Peur de créer des bugs.  

---

### Conséquences ?

![](images/codebasecracra.jpg)<!-- .element: height="250px" -->  

- Frayeurs à faire évoluer des parties du jeu. <!-- .element class="fragment" data-fragment-index="1" -->  
- Beaucoup de temps perdu en bugfix. <!-- .element class="fragment" data-fragment-index="2" -->  
- De plus en plus de hacks. <!-- .element class="fragment" data-fragment-index="3" -->  
- Des développeurs tristes. <!-- .element class="fragment" data-fragment-index="4" -->  

---

### La peur des bugs

![](images/bugdetection.png)

**Détecter le maximum de bugs le plus tôt possible !**<!-- .element: class="fragment" data-fragment-index="1" -->  

Si on est capable de détecter instantanément les bugs après avoir modifier du code,
on aura pas peur d'y toucher !<!-- .element: class="fragment" data-fragment-index="1" -->  


---

### Et comment on fait ça ?

On s'équipe d'un harnais de tests automatisés !
![](images/coderavectests.jpg)<!-- .element: height="250px" -->  

---

### Un test automatisé ?

Un morceau de code qui va s'assurer que le jeu fonctionne bien.

```C#
[Test]
public void ShouldBeDeadIfMoreDamageThanInitialLife()
{
		// Given
		const int initialLife = 20;
		var playerLife = new PlayerLife(initialLife);

		// When
		playerLife.ReduceLife(999);

		// Then
		Assert.That(lifeCounter.IsDead(), Is.True);
}
```

---

### Différents types de tests automatisés

- 🤔 Tests de bout en bout <!-- .element: class="fragment" data-fragment-index="1" -->  
- 😀 Tests unitaires <!-- .element: class="fragment" data-fragment-index="2" -->  

![](images/pyramid.png) <!-- .element: class="fragment" data-fragment-index="3" height="350px" -->  

---

### Pourquoi les tests unitaires  
### c'est cool ?

- Rapide à écrire. <!-- .element: class="fragment" data-fragment-index="1" -->  
- Rapide à éxecuter. <!-- .element: class="fragment" data-fragment-index="2" -->  
- Facile à maintenir. <!-- .element: class="fragment" data-fragment-index="3" -->  
- Précis. <!-- .element: class="fragment" data-fragment-index="4" -->  
- Documentation vivante et forcément à jour. <!-- .element: class="fragment" data-fragment-index="5" -->  

---

### Oui, mais non, on peut pas faire de tests parce que...

_"Pas assez de temps."_  

Un investissement qui économisera  
du temps de bugfix.
<!-- .element: class="fragment" data-fragment-index="1" -->  
![](images/catbug.gif)<!-- .element: class="fragment" data-fragment-index="1" height="250px" --> 

---

### Oui, mais non, on peut pas faire de tests parce que...

_"Besoin de pouvoir itérer."_  

Moins de craintes de casser,  
plus simple de modifier !
<!-- .element: class="fragment" data-fragment-index="1" -->  
![](images/catbreak.gif)<!-- .element: class="fragment" data-fragment-index="1" height="250px" --> 

---

### Oui, mais non, on peut pas faire de tests parce que...

_"Ce truc, là, c'est pas testable !"_  

Bah teste le pas ! :)  
Mais ça, ça et ça, c'est testable !
<!-- .element: class="fragment" data-fragment-index="1" -->  
![](images/catthat.gif)<!-- .element: class="fragment" data-fragment-index="1" height="250px" --> 

---

### Oui, mais non, on peut pas faire de tests parce que...

_"Faire des tests, c'est compliqué !"_  

Suffit de commencer par ça !  
TTD all the way ! <3
<!-- .element: class="fragment" data-fragment-index="1" -->  
![](images/cattdd.gif)<!-- .element: class="fragment" data-fragment-index="1" height="250px" --> 

---

### Et concrètement ?
![](images/unitytestrunner.png)<!-- .element: height="400px" -->   
_Unity + Test Runner + NUnit + NSubstitute = <3_

Possible dans la plupart des langages et des moteurs.
---

### Conclusion ?

Plein de trucs à faire pour améliorer son code  
et ses habitudes de développement.  
Bien tester, ça en fait partie ! :D  

D'autres pistes : <!-- .element: class="fragment" data-fragment-index="2" -->  
- Integration continu <!-- .element: class="fragment" data-fragment-index="2" -->
_(GitLab CI, Unity Cloud Build)_ <!-- .element: class="fragment" data-fragment-index="2" --> 
- Injection de dépendance <!-- .element: class="fragment" data-fragment-index="3" -->
_(Zenject)_ <!-- .element: class="fragment" data-fragment-index="3" -->  
- Test Driven Development <!-- .element: class="fragment" data-fragment-index="4" -->
_(youtube/InfaillibleCode)_ <!-- .element: class="fragment" data-fragment-index="4" -->  

![](images/gitlab.png) <!-- .element: class="fragment" data-fragment-index="4" height="100px" -->
![](images/zenject.png) <!-- .element: class="fragment" data-fragment-index="4" height="100px" -->
![](images/infailliblecode.jpg) <!-- .element: class="fragment" data-fragment-index="4" height="100px" -->  
---

Merci !
