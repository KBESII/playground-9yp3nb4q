```C
void Test () 
{ 
    int a = 0; 
    return a++; 
}
```

?[Quel va être le retour de cette fonction ?]
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

?[Quel va être le retour de cette fonction ?]
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

?[Quel va être le retour de cette fonction ?]
-[x] 0
-[ ] 1
-[ ] Un nombre inderterminé
-[ ] Cette fonction produit une erreur