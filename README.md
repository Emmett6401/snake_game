# snake_game
뱀꼬리 늘리는 게임
## 코드 설명 
```
import pygame
import sys
import random
```
pygame: 게임 개발을 위한 라이브러리입니다. 화면 그리기, 키 입력 처리, 소리 재생 등을 제공합니다.   

sys: Python의 시스템 관련 기능을 사용하기 위한 모듈입니다. 프로그램 종료에 사용됩니다.   

random: 랜덤 숫자를 생성하기 위한 모듈입니다. 먹이의 위치를 랜덤하게 설정할 때 사용됩니다.   

```
pygame.init()
```
pygame.init(): Pygame을 초기화합니다. 화면 생성, 키 입력 처리 등 Pygame의 모든 기능을 사용하기 전에 호출해야 합니다.    

```
WIDTH, HEIGHT = 800, 600
CELL_SIZE = 20
screen = pygame.display.set_mode((WIDTH, HEIGHT))
pygame.display.set_caption("Snake Game")
```

WIDTH, HEIGHT: 게임 화면의 가로와 세로 크기를 설정합니다.
CELL_SIZE: 뱀과 먹이의 크기를 설정합니다. 모든 요소는 이 크기를 기준으로 움직입니다.
pygame.display.set_mode: 게임 화면을 생성합니다.
pygame.display.set_caption: 게임 창의 제목을 설정합니다.

## 실행 화면 
<img width="601" alt="image" src="https://github.com/user-attachments/assets/3186768e-58d0-4e8f-bc3e-2f5edfab5543" />
