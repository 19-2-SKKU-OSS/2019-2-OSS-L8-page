---
layout: post
title: Free python games - Memory
date: 2019-12-05 13:32:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: memory.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Free python games, Memory]
---

# **[memory.py] 기능 추가 / 새 파일 추가**

## 프로젝트 내용
64개의 하얀 타일이 주어졌을 때 같은 숫자를 가진 타일 두 개를 연속으로 찾으면 해당 타일이 사라지면서 뒤에 있던 이미지가 나타납니다. 모든 숫자를 맞춰 이미지를 완성시키는 것이 이 게임의 승리 방법입니다.
그런데 이미 맞춰 사라진 타일이 있는 부분을 다시 클릭했을 때 숫자가 다시 나타나는 오류가 있어 해당 사항을 수정하는 방향으로 프로젝트를 진행하였습니다.
추가적으로 게임이 너무 단조로운 것 같아 배경이 되는 사진을 2개 더 추가하였습니다. 추가된 2개를 포함한 총 3개의 이미지 중 하나가 게임 시작 시 랜덤으로 정해집니다.

- <수정 전 예시 사진> 정답을 이미 맞췄는데도 숫자가 그림 위에 나타남

![memory_1]({{site.baseurl}}/assets/img/memory_1.png)

**Memory.py 파일 수정**
![memory_2]({{site.baseurl}}/assets/img/memory_2.png)
<숫자가 나타나지 않도록 하는 추가 코드 사진>

**파일 추가**
![memory_3]({{site.baseurl}}/assets/img/memory_3.png)
<사진을 랜덤으로 선택하는 코드 사진>

<수정 후 플레이 사진> - 세가지 이미지 중 하나가 랜덤으로 나타남

![memory_4]({{site.baseurl}}/assets/img/memory_4.png)![memory_5]({{site.baseurl}}/assets/img/memory_5.png)![memory_6]({{site.baseurl}}/assets/img/memory_6.png)

**Issue / Pull request**
- Issue : https://github.com/grantjenks/free-python-games/issues/27
- Pull request : https://github.com/grantjenks/free-python-games/pull/29
- 원 프로젝트에 tap 오류에 관한 issue를 먼저 제안한 뒤 pull request를 생성하였습니다.

![memory_7]({{site.baseurl}}/assets/img/memory_7.png)![memory_8]({{site.baseurl}}/assets/img/memory_8.png)

그런데 해당 pull request의 automatic 체크 사항 중 오류가 발생하였습니다. 해당 오류는 낮은 버전의 파이썬에서는 프로그램이 제대로 작동하지 않을 수 있다는 오류로 팀에서 해결할 문제가 아니라 원 프로젝트를 담당하는 사람이 결정해야 할 문제라고 판단하여 다른 조치는 취하지 않았습니다.
![memory_9]({{site.baseurl}}/assets/img/memory_9.png)
