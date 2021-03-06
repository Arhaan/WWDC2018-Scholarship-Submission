<h1 align="center">π</h1>
<h5 align="center">원주율을 구하는 여러 가지 수학적 방법을<br>직접 경험하고 배울 수 있도록 도와주는<br>Swift Playground.</h5>

[<p align = "center">
![GitHub developer](https://img.shields.io/badge/Developer-Sunghyun%20Cho-yellow.svg?longCache=true&style=flat-square)](https://github.com/anaclumos)<br>[![HitCount](http://hits.dwyl.io/anaclumos/WWDC2018-Scholarship-Submission.svg)](http://hits.dwyl.io/anaclumos/WWDC2018-Scholarship-Submission) [![GitHub license](https://img.shields.io/github/license/anaclumos/WWDC2018-Scholarship-Submission.svg?longCache=true&style=flat-square)](https://github.com/anaclumos/WWDC2018-Scholarship-Submission/blob/master/LICENSE)

Preview 이미지를 보고 싶으시다면, [Images.md](Images.md)를 확인해주세요.

Apple WWDC18 학생 장학 프로그램에 선발됐습니다.

### [네이버 뉴스](https://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=105&oid=293&aid=0000022478)

![Badge](Badge.jpg)

## 내가 선발됐다고 생각하는 이유

##### 이하의 내용은 개인적인 의견이며, Apple의 의견이 아닙니다.

물론 단 한 차례 뽑힌 입장으로 이런 것을 스스로 판단할 자격은 절대 되지 않습니다. 하지만 매우 드문 한국인 장학생으로서 추후에 많은 학생들에게 조금이라도 도움이 되길 바라며 감히 스스로 평가해보려 합니다. (2009년에 미리 선발되신 분이 있었습니다. 그 뒤로 선발 규정이 많이 바뀌긴 했지만, 또 다른 한국인 장학생 분이 있는지는 불확실합니다. Apple Korea가 인지한 장학생은 제가 처음이라고 했습니다)

처음에는 게임을 만드려고 했습니다. 3분이라는 제한된 심사 시간 내에 심사관들을 매료시키기 알맞을 것이라 생각했기 때문입니다. 그래서 SpriteKit부터 배우기 시작했는데, 며칠 뒤 "Apple이 재능이 있는 학생들"을 찾는다는 것을 알게 되었습니다. 모두가 알다시피 누구나 며칠 내에 조잡한 게임을 만들어낼 수 있습니다. 하지만 이는 Apple이 원하는 것이 아닙니다. Apple은 인터넷에서 코드를 복사하는 사람을 원하는 것이 아니라 **통찰력 있고, 명석하며, 창의성 있는** 학생들을 원합니다. 때문에 저는 첫 번째 Playground를 폐기했고, 이 Playground를 만들게 되었습니다. 마감 기한을 나흘 앞둔 때였습니다.

한 가지 기억할 점은 겉치레에 집중하는 것은 의미가 없다는 점입니다. Apple은 이미 개발자들을 수천명 보유하고 있습니다. Apple이 찾는 것은 흔한 개발자들이 아닙니다. Apple은 창의력 있는 학생들을 원합니다. 단지 겉장식에만 신경 쓴다면, Apple은 전혀 인상 받지 못할 것입니다.

차라리 그것보단, 콘텐츠에 집중하는 편이 나은 것 같습니다. 창의력 있는 콘텐츠로 말입니다. Apple은 이미 모집 요강에 "Build a Swift playground to showcase your ingenuity"라고 이를 명시해 놓았습니다.

또한 평가 요소 중 하나인 "기술적 완성도"의 면에서 본다면, 기본적인 기능에 집중하고 완성도를 높이는 것이 조잡하고 복잡하지만 미려하지 못한 Playground를 만드는 것보다 더 "기술적으로 완성되어" 보일 것입니다.

### 학문적 깊이
저의 경우에는 수학적인 깊이에 초점을 맞췄습니다. 이 Playground는 원주율을 구하는 여러가지 수학적 방식을 시각적으로 상호작용하며 쉽게 경험하고 이해할 수 있도록 도와줍니다. 또한 수많은 수학적인 분석을 각주로 달았습니다. 때문에 다른 제출물과 비교했을 때 Apple 심사관들은 이 Playground를 더 기반이 튼튼하다고 생각했을 것입니다. 다른 합격생들의 Playground도 음악, 미술, 과학, 환경 등 다양한 분야의 학문적 깊이에 초점을 둔 것이 많았습니다.

### 명확한 주제와 통일성
지원을 준비할 때 미리 공개되어있는 합격생들의 Playground를 전부 다운로드해서 분석을 해보았습니다. 주제를 명확하게 가지고 있는 Playground가 대부분이었습니다. 3분이라는 짧은 시간 동안에는 여러 가지 이야기를 할 수 없습니다. 하나의 주제에 초점을 두고, 통일성 있으며 완성된 하나의 경험을 주는 것이 나은 것 같습니다.

### 독창성
이미 AP Computer Science 수업을 수강한 학생들은 알겠지만, Monte Carlo Method는 생각보다 진부한 방식입니다. 대부분 수업에서 Java로 이를 구현해보기 때문입니다. 그러나 저는 여기서 이 방식을 더 발전시켰습니다. 첫째로, 긴 소수들을 쉽게 비교할 수 있는 "Disco Level"이라는 수학적 지표를 만들어 소수 연산의 정확도 비교를 매우 간편하게 바꾸었습니다. 또한, Monte Carlo Method를 위한 좌표평면과 여러가지 차트를 그릴 수 있는 Graphing Tool을 자체 제작했습니다. 이들은 온전히 저 혼자 아무 도움 없이 한 것입니다.

### 완성도
저는 핵심 Storyboarding과 Coding 부분을 첫 이틀에 끝냈습니다. 그 다음 이틀 동안 심사장에서 발생 가능한 모든 경우를 생각해보며 버그를 잡고 UX를 다듬으며 완성도를 높이는 데 힘썼습니다. 시간에 쫓기지 말고, 마지막 며칠은 완성도를 높이는데 투자하는 것이 좋은 것 같습니다.

### 에세이
대부분의 학생들이 에세이보다 Playground를 더 우선순위로 듭니다. 근데 저는 에세이가 더 중요하다고 생각합니다. 저는 에세이에 많은 시간을 쏟았고, 주변의 여러 선생님께 첨삭을 부탁드리기도 했습니다. 에세이는 내가 누구이며, 왜 지원했는지 요약적으로 보여줄 수 있는 지표입니다. 때문에 무척 중요합니다. 당연하지만 오타나 문법적 오류가 없는 것도 중요합니다.

### 구체적인 step-by-step 설명
이미 밝힌 것처럼 저는 많은 세부 사항들과 이유들을 각주로 달았습니다. 이 과정 속에서 모든 정보들을 조직적으로 배치하기 위해 노력했습니다. 또한 Apple 심사관들을 위해 "안내된 동선"을 만들었습니다. 때문에 Apple 심사관들은 직관적으로 설명문을 따라가며 자연스럽게 모든 경험을 할 수 있었을 것입니다. 

또한, 유용한 Markup 문법을 통해 강조하고, 예시를 들고, 참고할 점을 기록했습니다. Apple이 작성한 Markup reference을 꼭 읽어보길 바랍니다.


    Written by Sunghyun Cho on June 27th, 2018.