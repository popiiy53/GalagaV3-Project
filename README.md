# c++기반의 GalagaV3게임 프로젝트 


![ezgif com-gif-maker](https://user-images.githubusercontent.com/107553545/198807298-a9a8f5bf-cd5e-4947-b421-2f41c62fff1d.gif)


## 🔍 진행된 세팅 환경

- PC 환경 
HW : Intel(R) Core(TM) i3-3220 CPU @ 3.30GHz, RAM 12.0GB
SW : Windows10 64비트 운영 체제, x64기반 프로세서

Code::Blocks 20.03
compiler : 설치시 내부 mingw 이용.
             => gcc version 8.1.0 
                x86_64-posix-seh-rev0 built by MinGW-W64 project

Search directories > Compiler 
SDL2-2.0.14\x86_64-w64-mingw32\include\SDL2
SDL2_image-2.0.5\x86_64-w64-mingw32\include\SDL2
SDL2_mixer-2.0.4\x86_64-w64-mingw32\include\SDL2
SDL2_ttf-2.0.15\x86_64-w64-mingw32\include\SDL2

Search directories > Linker
SDL2-2.0.14\x86_64-w64-mingw32\lib
SDL2_image-2.0.5\x86_64-w64-mingw32\lib
SDL2_mixer-2.0.4\x86_64-w64-mingw32\lib
SDL2_ttf-2.0.15\x86_64-w64-mingw32\lib

Linker settings
mingw32
SDL2main



SDL2.dll
SDL2_image
SDL2_mixer
SDL2_ttf
user32
gdi32
winmm
dxguid
