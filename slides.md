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
vrai commentaire trouvé dans le code des smurfs  
quand je suis arrivé en stage...

toujours là 2 ans après...<!-- .element: class="fragment" data-fragment-index="2" -->  

Un exemple parmis tant d'autres...<!-- .element: class="fragment" data-fragment-index="3" -->  

![](images/proglife.png)<!-- .element class="fragment" data-fragment-index="3" height="250px" -->
---

### Pourquoi ce code est resté comme ça tout ce temps ?
- Difficile de prévoir les effets de bords.  
- Eviter de créer des bugs.  
- Eviter de longs aller-retours avec la QA.
- Eviter de prendre le risque de tout péter.  

![](images/codersanstests.jpg)<!-- .element: class="fragment" data-fragment-index="1" height="250px" -->  

---

### Conséquences ?

- Frayeurs à faire évoluer des parties du jeu.
- Beaucoup de temps perdu en bugfix.
- Contournements qui propage la grangraine.
- Des développeurs tristes.
- Une codebase de plus en plus cracra...

![](images/codebasecracra.jpg)<!-- .element: class="fragment" data-fragment-index="1" height="250px" -->  

---

### La peur des bugs

![](images/bugdetection.png)

**Réduire au max la boucle de feedback !**<!-- .element: class="fragment" data-fragment-index="1" -->  

Si on est capable de détecter instantanément les bugs après avoir modifier du code,  
on aura pas peur d'y toucher !<!-- .element: class="fragment" data-fragment-index="1" -->  


---

### Et comment on fait ça ?

On s'équipe d'un harnais de tests automatisés !
![](images/coderavectests.jpg)<!-- .element: height="250px" -->  

---

### Un test automatisé ?

Un morceau de code qui va executer une partie  
ou l'intégralité du jeu pour s'assurer  
que tout fonctionne bien.

---

### Différents types de tests

- 😒 Tests manuels <!-- .element: class="fragment" data-fragment-index="1" -->  
- 🤔 Tests de bout en bout <!-- .element: class="fragment" data-fragment-index="2" -->  
- 😀 Tests unitaires <!-- .element: class="fragment" data-fragment-index="4" -->  

pyramide de tests <!-- .element: class="fragment" data-fragment-index="5" -->  

---

### Pourquoi les tests unitaires  
### c'est cool ?

- Rapide à écrire.
- Rapide à éxecuter.
- Facile à maintenir.
- Précis.
- Documentation vivante et forcément à jour.

---

### Oui, mais non, on peut pas faire de tests parce que...

_"Pas assez de temps."_  

Un investissement qui économisera  
du temps de bugfix.
<!-- .element: class="fragment" data-fragment-index="1" -->  

---

### Oui, mais non, on peut pas faire de tests parce que...

_"Besoin de pouvoir itérer."_  

Moins de craintes de casser,  
plus simple de modifier !
<!-- .element: class="fragment" data-fragment-index="1" --> 

---

### Oui, mais non, on peut pas faire de tests parce que...

_"Ce truc, là, c'est pas testable !"_  

Ok, mais ça, ça et ça,  
ça l'est ! :)
<!-- .element: class="fragment" data-fragment-index="1" --> 

---

### Oui, mais non, on peut pas faire de tests parce que...

_"Faire des tests, c'est chiant !"_  

Suffit de commencer par ça !  
TTD all the way ! <3
<!-- .element: class="fragment" data-fragment-index="1" --> 

---

### Et concrètement ?

exemple avec unity

---

### Conclusion ?

Au dela de la perf, y a plein de trucs à faire pour améliorer son code.  
Bien tester, ça en fait partie ! :D

---

### Pour aller plus loin ?

- integration continu avec GitLab CI  
  ou avec Unity Cloud Build  
- injection de dépendance avec ZenJect  
- TDD > vidéos de InfaillibleCode sur YouTube
