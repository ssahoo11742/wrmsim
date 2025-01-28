# Wormhole simulation
![image](https://github.com/user-attachments/assets/c23dd21c-ee2b-4507-8f40-d8dd697ea20c)


simulating the space time curvature and strange lensing effects of a 3D wormhole in your browser.

Demo link: https://astonishing-donut-635527.netlify.app/

## Images
![image](https://github.com/user-attachments/assets/1752997b-55a2-486b-8d87-68f953ae029e)
![image](https://github.com/user-attachments/assets/d4e56ea8-f756-4bec-9bcb-1aaef0281653)
![image](https://github.com/user-attachments/assets/8d841e70-3ce5-4759-a4cd-83c4e8718896)


## Tech Stack
- TypeScript
- ThreeJS
- GLSL
- HTML
- Space Engine

## Mathematical details

In this simulation you see the curvature of an Ellis wormhole with a throat.

The metric used to trace all light rays is

$ds^2=dl^2+(k^2+x^2)(d\theta^2+sin^2 \theta\ d\varphi^2)$

where

$x=\max(0, |l| - a)$\
$k$ = the wormhole's interior's radius\
$a$ = half the throat's length.

Due to the spherical symmetry, instead of integrating the light rays in spherical coordinates, they are first projected onto a 2D plane through the origin and integrated in 2D space (using metric $ds^2=dl^2+(k^2+x^2)d\theta^2$). 

## Credits

The skyboxes were made using [Space Engine](http://spaceengine.org/).
