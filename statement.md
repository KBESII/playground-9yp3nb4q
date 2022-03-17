```C
void Test () 
{ 
    int a = 0; 
    return a++; 
}
```

?[Quel va être le retour de la fonction ci dessus ?]
-[ ] 0
-[ ] 1
-[ ] Un nombre inderterminé
-[x] Cette fonction produit une erreur

```C
int Test () 
{ 
    int * a; 
    return &a; 
}
```

?[Quel va être le retour de la fonction ci dessus ?]
-[ ] 0
-[ ] 1
-[x] Un nombre inderterminé
-[ ] Cette fonction produit une erreur

```C
int Test () 
{ 
    int a,b,c;
    c = a + b; 
    return c; 
}
```

?[Quel va être le retour de la fonction ci dessus ?]
-[x] 0
-[ ] 1
-[ ] Un nombre inderterminé
-[ ] Cette fonction produit une erreur

```C
int a, b, c;
a = 12;
b = 22;
c = 16;
printf("%d %x %x", a, b, c);
```

?[Quel va être la trace affichée suite à l'execution du bloc de code ci dessus ?]
-[ ] 12 22 16
-[ ] C 16 10 
-[ ] 0C 16 10
-[x] 12 16 10