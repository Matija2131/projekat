# projekat iz grafike

Korišćen je skelet sa https://github.com/matf-racunarska-grafika/project_base.
Na sceni je statua oko koje se vrti sunce koje predstavlja point light.

Uputstvo:
1. `git clone
2. CLion -> Open -> path/to/my/project
3. Main se nalazi u src/main.cpp
4. ALT+SHIFT+F10 -> project_base -> run
5. W A S D za kretanje
6. f1 -> otvara i zatvara gui 

Projekat sadrži dva modela:

1. Statua:
https://sketchfab.com/3d-models/colossal-bust-ramesses-ii-livestream-tutorial-62ffe231f1664b84ae8c263a77b83e15

2. Sunce:
https://sketchfab.com/3d-models/the-sun-0d28aa65eb174d948c2716d73e8fd3bd

Teksture:

1. Pod:
https://3dtextures.me/2022/09/14/stone-floor-004/

2. Trava:
https://learnopengl.com/img/textures/grass.png

Na podu je demonstrirana tehnika Normal mapping.

Na travi je demonstriran blending.

Slike za skybox su:
https://opengameart.org/content/xonotic-skyboxes

Komande na tastaturi:

f1: otvara ImGUI i omogućava podešavanje izgleda scene i zatvara ImGUI

W, A, S, D i miš: kretanje po sceni

B: uključuje i isključuje Blinn-Phong-ov model osvetljenja (najbolje se vidi na statui)

esc: isključuje aplikaciju


Pomoću ImGUI-a moguće je menjati poziciju statue na sceni, podešavati faktore point lighta.

Drugi ImGUI prikazuje faktore trenutne pozicije kamere na sceni.

Autor: 
Stanković Matija 207/2021

