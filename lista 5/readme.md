# List 04

This repository contains the exercicios proposed by list 04 of the subject *Processamento Gráfico*.

| ex number | description           | source                            | executable      |
|-----------|-----------------------|-----------------------------------|-----------------|
| a         | vermelho              | [source.cpp](ex_a/src/Source.cpp) | [app](ex_a/app) |
| b         | azul                  | [source.cpp](ex_b/src/Source.cpp) | [app](ex_b/app) |
| c         | verde                 | [source.cpp](ex_c/src/Source.cpp) | [app](ex_c/app) |
| d         | grayscale             | [source.cpp](ex_d/src/Source.cpp) | [app](ex_d/app) |
| e         | colorizacao (nao fiz) | [source.cpp](ex_e/src/Source.cpp) | [app](ex_e/app) |
| f         | inversao              | [source.cpp](ex_f/src/Source.cpp) | [app](ex_f/app) |
| g         | binarizacao           | [source.cpp](ex_g/src/Source.cpp) | [app](ex_g/app) |
| h         | próprio               | [source.cpp](ex_h/src/Source.cpp) | [app](ex_h/app) |
 
## Running in macOS

```
g++ src/Source.cpp src/glad.c src/SceneManager.cpp src/Sprite.cpp src/stb_image.cpp -g -o app -Iinclude -lglfw -ldl
./app
```