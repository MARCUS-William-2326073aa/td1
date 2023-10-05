# td1
tp1 fait avec Casali
## résumé
ce document vas vous expliquez comment utilisé les different fonction de ce programme et leurs utilités.
ce programme a été codé en **c++** par un brillant étudiant a l'iut info d'aix marseille et qui vous fait l'honneur d'écrire ce readme en **MARKDOWN**.
## descriptif global
ce programme a était organisé cellon les demandes des exercices donné dans le prog1 sur le site du professeur [casali](https://ens.casali.me/)

### fonctionnement du programme
**appeller l'exercice souhaité**

l'intergralité du programme est basé sur le principe de _l'exercice 7_ il vous faut donc écrire le numéro de l'exercice souhaité afin de l'utilisé.

> si vous voulais connaitre l'utilité des differents fonction vous pouvais allez directement regardé les exercice sur le [site](https://ens.casali.me/category/r1-01-init-dev/r1-01-programmation/r101-prog1/) ou regardez les explication

### explication des fonction

* exo2

code:
```c++
void exo2 (){
    cout << "Bonjour!" << endl;
}
```

l'exo2 est juste le classic "hello world!" il vas seulement afficher "bonjours!"

---
* exo3

code:
```c+
  void exo3(){
    for(int i = 0; i<10; ++i){
        cout << x;
        cout << "  ";
        x = x+1;
    }
}
```

l'exo 3 vas compté de 0 a 10 avec un espace entre chaque nombres

---

* exo4

code:
```c+
void exo4(){
    for(int i = 0; i<200; ++i){
        cout << x;
        cout << "  ";
        x = x+1;
    }
}
```
comme l'exo3 sauf qu'il vas compté jusqu'a 200

---
* exo5

  code:
  ```c+
  void exo5(){
    int n(0);
    cout << "saisire un nombre" << endl;
    cin >> n ;
    for(int i = 0; i<n; ++i){
        cout << x;
        cout << "  ";
        x = x+1;
    }
}
```
