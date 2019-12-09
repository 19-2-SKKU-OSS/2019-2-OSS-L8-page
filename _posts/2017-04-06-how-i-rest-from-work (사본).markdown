---
layout: post
title: Free python games - Snake
date: 2019-12-05 13:32:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: snkae.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Free python games, Snake]
---

# Snake.py 게임에서 기능 추가

#### 추가한 기능 내용:
####  원래 snake.py 게임은 초록색 food를 먹으면 snake 가 하나씩 커지는 게임이었습니다. 랜덤으로 생기는 빨간색 점 (Trash)를 추가하여 만약 snake가 Trash를 먹을 경우 몸에 길이가 하나씩 줄어 들도록 하는 기능을 추가하였습니다. 또한 원래는 벽에 부딪치거나 snake 자기 자신의 몸과 만날 경우 그 즉시 게임이 종료 되었습니다. 게임이 종료 되기 전 ‘Game End’ 를 프린트 하도록 하는 기능을 추가하였습니다.

## 1. Trash 기능 추가

### - 기능 추가 전 snake.py 작동 화면                    ### - 기능 추가 이후 snake.py 작동 화면
![snake_1]({{site.baseurl}}/assets/img/snake_1.png) ![snake_2]({{site.baseurl}}/assets/img/snake_2.png)

## Trash 추가 코드

![snake_3]({{site.baseurl}}/assets/img/snake_3.png)

#### 코드 설명 : trash 라는 백터 생성 후, snake 와 trash 가 만날 경우 snake에 길이를 1씩 줄인 뒤 trash 위치를 랜덤으로 배치하게 했습니다. 만약 snake 길이가 1일 경우에 trash를 먹으면 게임이 종료 되도록 했습니다.

## 2. 종료시 'Game End' 출력
#### (밑에 예시 사진은 초록색 food를 2개 먹은 뒤 벽에 부딪쳐 게임이 끝나게 했습니다.)

#### 기능 추가 전 snake.py IDLE 출력창 
![snake_4]({{site.baseurl}}/assets/img/snake_4.png)

#### 기능 추가 후 snake.py IDLE 출력창
![snake_5]({{site.baseurl}}/assets/img/snake_5.png)

### 'Game End' 코드 추가
![snake_6]({{site.baseurl}}/assets/img/snake_6.png)
#### (snake가 자기 자신과 벽을 만났을 때와 종료 되는 코드에 ‘Game End’ 추가한 것입니다.)
![snake_7]({{site.baseurl}}/assets/img/snake_7.png)
#### (snake 길이가 1인 경우에서 trash 를 먹었을 때 종료 되는 코드에 ‘Game End’ 추가한 것입니다.)

## 3. 원래 프로젝트에 pull request 와 issue 등록

#### Pull request : (https://github.com/grantjenks/free-python-games/pull/26)
#### Issue : (https://github.com/grantjenks/free-python-games/issues/25)
#### Issue에 추가한 기능에 대한 설명을 적어두었고, pull request를 통해 수정된 코드를 제공했습니다.

![snake_8]({{site.baseurl}}/assets/img/snake_8.png)
#### issue에 새로운 기능에 대한 설명 추가)

![snake_8]({{site.baseurl}}/assets/img/snake_8.png)
#### pull request에 수정한 코드 추가
