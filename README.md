# TP Sextant

## Réponses

### Option tftp Qemu

L'option tftp permet de lancer un serveur tftp, ainsi il n'est pas nécessaire de reconstruire l'image à chaque fois mais juste remplacer le fichier binaire exécuté.

### Boucle

La boucle est due à ces instructions:

```source
    cli
1:  hlt
    jmp 1b
```
