# PHP-uni
TP 02 PHP — Programmation Web 2 — 2026/2027
### Différence entre $note et $Note
En PHP, les noms de variables sont sensibles à la casse (case-sensitive). Cela signifie que le langage fait la distinction entre les lettres minuscules et majuscules. Par conséquent, `$note` et `$Note` constituent deux emplacements mémoire distincts et indépendants.

### Validité des noms de variables
Voici l'analyse des noms proposés :
- **Noms valides :** `$a`, `$_a`, `$a_a`, `$AAA`, `$a1`.



### Différence d'affichage de `false` entre `echo` et `var_dump()`

- **`echo`** : Convertit implicitement la valeur booléenne en chaîne de caractères avant de l'afficher. `true` est converti en `"1"`, tandis que `false` est converti en une chaîne vide `""`. Rien n'apparaît donc à l'écran lors d'un `echo` sur une valeur `false`.
- **`var_dump()`** : Affiche directement le type de la donnée ainsi que sa valeur brute. Il écrit explicitement `bool(false)`, ce qui permet d'inspecter avec précision le contenu et le type de la variable.




### Résultats des tests de moyennes (`ex05.php`)
| Moyenne | Message |
|---|---|
|9| Non validé |
|10| Passable |
|12| Assez bien |
|14| Bien |
|16| Très bien |

