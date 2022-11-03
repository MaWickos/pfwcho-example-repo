# Programowanie fullstack w chmurze obliczeniowej
## Lab03 (27.10.2022)
Instrukcja budowania obrazu na podstawie pliku dockerfile z niniejszego repozytorium
```
docker build --no-cache --ssh default=C:\Users\macie\.ssh\id_ed25519 -t lab2.v1 -f PFwChO_Lab03_dockerfile . 
```

Ogólne polecenie do budowania obrazu
```
docker build --no-cache --ssh default=ssh_key -t image_name.version -f dockerfile_name
```

## Autor
Maciej Wicha, IMST I2S 1.5
Politechnika Lubelska, rok akademicki 2022/2023
