# OverTheWire Spoilers

## _This is a guide step to solve each level of the bandit wargame_

## SSH INFORMATION
- _host:_ bandit.labs.overthewire.org
- _port:_ 2220

### _!!! IMPORTANT !!!_
For every level, you will need to log into the game using ssh 

by replacing the username "bandit0" with the username corresponding to the level :

```sh
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
and logout after finding the password to be able to connect to the next level.


## level 0
```sh
ssh bandit0@bandit.labs.overthewire.org -p 2220
password: bandit0
```

## level 0 > level 1
```sh
ls
cat readme
```
The password is :
```sh
NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
```

## level 1 > level 2
```sh
cat ./-
```
The password is :
```sh
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
```

## level 2 > level 3
```sh
cat "spaces in the filename"
```
The password is :
```sh
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
```

## level 3 > level 4
```sh
cd inhere
ls -a
cat <.hidden
```
The password is :
```sh
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
```

## level 4 > level 5
```sh
cd inhere
file ./*
cat ./-file07
```
The password is :
```sh
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
```

## level 5 > level 6
```sh
cd inhere
find -size 1033c ! -executable
cat ./maybehere07/.file2
```
The password is :
```sh
P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
```

## level 6 > level 7
```sh
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat ./var/lib/dpkg/info/bandit7.password
```
The password is :
```sh
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
```

## level 7 > level 8
```sh
grep 'millionth' ./data.txt
```
The password is :
```sh
TESKZC0XvTetK0S9xNwm25STk5iWrBvP
```

## level 8 > level 9
```sh
sort ./data.txt | uniq -u
```
The password is :
```sh
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
```

## level 8 > level 9
```sh
sort ./data.txt | uniq -u
```
The password is :
```sh
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
```

## level 9 > level 10
```sh
strings ./data.txt | grep '='
```
The password is :
```sh
G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
```

## level 10 > level 11
```sh
base64 --decode ./data.txt
```
The password is :
```sh
6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
```

## level 11 > level 12
```sh
cat ./data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```
The password is :
```sh
JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv
```
