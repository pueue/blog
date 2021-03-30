---
title: 무엇이 좋은 퍼즐을 만드는가?
date: 2020-03-30 02:01:31
tags:
---
지금 Lara Croft GO와 Monument Valley 2가 모바일 스토어에서 무료 이벤트를 하고 있다. 두 게임 모두 수준 높은 퀄리티를 자랑하는 퍼즐 게임이다. 게임을 플레이하면서 이런 퍼즐게임은 어떻게 만드는 것인지, 레벨 디자인은 어떻게 하는지 궁금했다. 

내가 가장 좋아하는 유튜브 채널 중 하나인 Game maker's toolkit의 Mark brown이 플레이어가 잘 만들어진 퍼즐을 풀 때 어떤 요소가 있었는지 본인만의 방식으로 풀어두었길래 정리해 보았다.

{% youtube zsjC6fa_YBg %}

**1. Mechanics - 규칙과 제약**

Mechanics은 게임이 어떻게 돌아가는지 규정하는 규칙과 제약을 의미한다. 이 mechanics으로 퍼즐을 만들 수 있다. 따라서 mechanics가 퍼즐의 수와 난이도를 결정한다. mechanics을 증강시키기 위해 다양한 요소를 이용할 수 있는데, 이런 요소는 임시적일 수도 있고, 계속 mechanics에 포함될 수도 있다.

**2. Catch - 문제**

Catch는 얼핏 보면 해결하기 불가능해 보이는 문제를 의미한다. 플레이어는 퍼즐 풀기를 시도하면서 몇 가지 액션 조합을 사용한다. 이때 이 액션 조합들이 논리적으로 충돌해 목표까지 갈 수 없다는 것을 깨달았을 때 catch를 발견한다.  이 때 플레이어는 액션 조합의 순서를 바꾸거나 해결 방법을 완전히 바꾸는 식으로 다시 접근한다.

**3. Revelation - 발견**

플레이어는 catch를 해결하기 위해서 생각의 틀을 깨려고 하거나 mechanics에 대해 다시 고민한다. 플레이어가 해결책을 찾아낸 순간이 Revelation이다. 이 때 플레이어는 스스로 똑똑하다고 느낄 수 있다(이게 퍼즐 게임의 실질적인 보상이라고 생각한다). 이렇게 찾아낸 해결책은 플레이어의 무기가 되고 다음 문제를 풀 때 사용할 수 있게 된다. 

**4. Assumption - 추정**

Assumption 이란 플레이어가 이렇게 하면 문제를 풀 수 있겠지하고 예상하는 것이다. 퍼즐은 플레이어가 assumption 을 통해 catch를 발견하도록 해야하는데, 그 이유는 다음과 같다.

1. 플레이어가 해법을 안다고 생각하게 만드므로, 새로운 퍼즐에 압도당하지 않고 실제로 퍼즐 풀기를 시도하게 한다.
2. 잘못된 assumption 으로 첫 시도를 실패하면서 퍼즐이 어떻게 동작하는지 깨닫고, catch가 어떻게 만들어졌는지에 대해 이해한다.
3. 플레이어가 첫 시도에 퍼즐을 못 풀 것을 보장한다. 바로 풀 수 있을 것이라고 생각했지만 catch를 만나고 당황할 것이다.
4. 플레이어가 퍼즐의 진짜 목표에 집중할 수 있게 해준다.

**5. Presentation - 제시**

Presentation은 퍼즐이 배치된 방식을 뜻한다. 플레이어에게 어떤 정보를 제공하냐에 따라 난이도가 달라진다. 퍼즐게임은 미니멀한게 좋다. 퍼즐과 관련있는 요소만 남겨둬서 플레이어가 퍼즐을 가장 단순하게 이해하는데에 도움을 줘야한다. 퍼즐이 어떻게 구성되어 있는지 알아내게 하는 것은 시간낭비다.

**6. Curve - 학습곡선**

모든 퍼즐은 이전 퍼즐에서 새로운 레이어를 추가하는 식이여야 한다. 플레이어는 앞서 학습한 모든 요소를 이용하려고 할 것이고, 점점 난이도가 높아져야 만족할 수 있기 때문이다. 따라서 퍼즐을 난이도 순으로 정렬할 필요가 있다. GO 시리즈를 만든 Square Enix Montreal에서는 아래와 같은 4가지 난이도 기준을 제시해 퍼즐의 난이도 순위를 정한다.

- 솔루션의 수가 많아지면 퍼즐이 쉬워진다.
- 해결까지의 스탭 수가 많으면 퍼즐은 어려워지지만, 또 너무 많으면 지루하다.
- 스탭마다 플레이어가 선택할 수 있는 가지 수가 많으면 어렵다.
- 플레이어가 mechanics에 익숙할수록 쉽다.