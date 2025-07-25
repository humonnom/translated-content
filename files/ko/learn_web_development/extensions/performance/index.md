---
title: 웹 성능
slug: Learn_web_development/Extensions/Performance
original_slug: Learn/Performance
l10n:
  sourceCommit: 4def230f85756724b59660e3cd9de363db724ef8
---

{{LearnSidebar}}

웹사이트를 만들기 위해선 HTML과 CSS, JavaScript가 필요합니다. 사람들이 쓰고 싶은 웹사이트와 어플리케이션을 만들려면 사용자들을 끌어모으고 유지할 수 있어야 하며, 그러려면 좋은 사용자 경험을 주어야 합니다. 콘텐츠가 빠르게 로드되고 사용자와의 상호작용에 잘 반응하는 것은 좋은 사용자 경험의 일부입니다. 이를 **웹 성능**이라고 하며, 이 모듈에서는 어떻게 성능이 좋은 웹사이트를 만들 수 있는지에 대해 기초적인 부분들을 집중적으로 다룹니다.

이 초보자 교육 자료의 나머지 부분은 웹 성능과 [접근성](/ko/docs/Learn_web_development/Core/Accessibility)과 같은 모범 사례를 가능한 한 많이 다루려 했지만, 해당 주제들에 확실히 익숙해지고 싶다면 별도로 탐색해보는 것이 좋을 것입니다.

## 학습 경로

웹 성능을 높일 수 있는 권장사항들을 구현하려면 HTML과 CSS, JavaScript를 알아야 하지만, 어플리케이션을 만드는 방법을 알아야만 웹 성능을 이해하고 측정할 수 있는 것은 아닙니다. 그렇지만 본 과정을 진행하기 전, 최소한 [웹 개발 시작하기](/ko/docs/Learn_web_development/Getting_started/Your_first_website) 과정에서 웹 개발의 기본 개념을 익히는 것을 추천합니다.

다음의 과정들에서 다루는 주제를 조금 더 깊게 살펴보는 것도 도움이 될 것입니다.

- [HTML 소개](/ko/docs/conflicting/Learn_web_development/Core/Structuring_content)
- [CSS 첫걸음](/ko/docs/conflicting/Learn_web_development/Core/Styling_basics)
- [JavaScript 첫걸음](/ko/docs/conflicting/Learn_web_development/Core/Scripting)

위의 과정들을 진행했다면 웹 성능에 대해 더 깊게 알고 싶어질 것입니다. [MDN 웹 성능 구획](/ko/docs/Web/Performance)에서 웹 성능 API, 테스트 및 분석 도구, 병목 현상 잡아내기 등 더 많은 것을 배울 수 있습니다.

## 안내서들

본 주제에 속한 안내서들은 다음과 같습니다. 순서대로 진행하는 것을 권장합니다. 바로 첫 번째부터 시작하면 됩니다.

- ["어째서" 웹 성능인가](/ko/docs/Learn_web_development/Extensions/Performance/why_web_performance)
  - : 접근성, 사용자 경험, 비즈니스 목표 달성 측면에서 웹 접근성이 왜 중요한지 다룹니다.
- [웹 성능이란 무엇인가?](/ko/docs/Learn/Performance/What_is_web_performance)
  - : 웹 성능이 중요하다는 것은 누구나 압니다. 그렇다면 웹 성능이란 구체적으로 무엇일까요? 이 문서에서는 웹페이지의 로딩과 렌더링에서부터 웹 성능을 검토할 때 어떤 집단의 사람들을 고려해야 하는지까지 웹 성능의 요소들을 소개합니다. 이는 콘텐츠가 사용자의 브라우저에 보여지는 과정을 포함합니다.
- [사용자들은 어떻게 웹 성능을 인지하는가?](/ko/docs/Learn/Performance/Perceived_performance)
  - : 웹사이트가 밀리초 단위로 얼마나 빠른지보다 중요한 것은 사용자들이 웹사이트를 어느 정도로 빠르다고 느끼는지입니다. 사용자들의 인지는 웹페이지의 실제 로드 시간, 지연 시간, 사용자의 상호작용에 대한 반응성, 스크롤이나 다른 애니메이션의 부드러움 등에 영향을 받습니다. 이 문서에서는 로딩과 애니메이션, 반응성을 나타내는 다양한 지표들과 실제 타이밍을 제외하더라도 사용자의 인지 작용을 개선할 수 있는 모범 사례들을 논합니다.
- [웹 성능 측정하기](/ko/docs/Learn_web_development/Extensions/Performance/Measuring_performance)
  - : 이제 당신은 몇 가지의 웹 성능 지표를 이해하게 되었습니다. 웹 성능 도구와 지표, API, 웹 성능을 웹 개발과정의 일부로 편입시킬 수 있는 방법에 대해 더 깊게 살펴봅니다.
- [멀티미디어: 이미지](/ko/docs/Learn_web_development/Extensions/Performance/Multimedia)
  - : 많은 경우에 가장 쉬운 웹 성능 개선 방법은 미디어 최적화입니다. 사용자 에이전트의 기능, 크기, 픽셀 밀도를 고려해 미디어 파일을 각각 다르게 제공할 수 있습니다. 이 문서에서는 이미지가 웹 성능에 미치는 영향, 이미지당 전송되는 바이트의 크기를 줄이는 방법을 다룹니다.
- [멀티미디어: 비디오](/ko/docs/Learn_web_development/Extensions/Performance/video)
  - : 많은 경우에 가장 쉬운 웹 성능 개선 방법은 미디어 최적화입니다. 이 문서에서는 비디오 콘텐츠가 웹 성능에 미치는 영향, 배경 영상에서 오디오 트랙을 제거하여 웹 성능 높이기와 같은 팁들을 다룹니다.
- [JavaScript를 활용한 웹 성능 모범사례](/ko/docs/Learn/Performance/JavaScript)
  - : 적절하게 JavaScript를 사용하면 상호작용할 수 있고 몰입되는 웹 경험을 줄 수 있습니다. 하지만 JavaScript를 잘못 사용할 경우 다운로드 시간, 렌더링 시간, 앱 자체의 성능, 배터리 수명, 사용자 경험을 심각하게 해칠 수도 있습니다. 이 문서에서는 컨텐츠가 복잡하더라도 최대한의 성능을 발휘할 수 있도록 고려해야 할 JavaScript 모범사례에 대해 소개합니다.
- [HTML과 웹 성능](/ko/docs/Learn/Performance/HTML)
  - : 마크업이 배치된 순서나 속성은 웹사이트 성능에 영향을 미칠 수 있습니다. DOM 노드의 개수를 최소화하고 HTML 문서에 콘텐츠(스타일, 스크립트, 미디어, 써드파티 스크립트 등)를 포함시키는 순서와 속성을 최적화하여 사용자 경험을 크게 개선할 수 있습니다. 이 문서에서는 최고의 성능을 끌어내려면 어떻게 HTML을 사용해야 하는지를 자세히 다룹니다.
- [CSS와 웹 성능](/ko/docs/Learn/Performance/CSS)
  - : 성능 개선에서 CSS 최적화는 상대적으로 덜 중요할 수 있습니다. 하지만 웹 성능에 더 많은 영향을 끼치는 CSS 기능이 몇 있습니다. 이 글에서는 해당 CSS 속성들과 웹 성능에 부정적인 영향을 끼치지 않으면서 스타일을 다루기 위해 권장되는 방법을 살펴봅니다.
- [글꼴과 웹 성능](/ko/docs/Learn/Performance/Fonts)
  - : 외부 글꼴을 포함해야 하는지, 만약 포함해야 한다면 어떻게 웹사이트의 성능에 미치는 영향을 최소화하면서 디자인이 요구하는 글꼴을 포함시킬 수 있는지를 살펴봅니다.
- [모바일 환경에서의 웹 성능](/ko/docs/Learn/Performance/Mobile)
  - : 모바일 기기로 웹에 접속하는 것이 대중화되면서, 모든 모바일 플랫폼은 완전한 형태의 웹 브라우저를 탑재하고 있습니다. 그러나 대역폭, CPU, 배터리 수명이 여전히 제한적이기 때문에 모바일 플랫폼에서 웹 컨텐츠의 성능을 고려해야 합니다. 이 글에서는 모바일 환경에 특화된 검토사항을 살펴봅니다.
- [비즈니스에서의 웹 성능 활용 사례](/ko/docs/Learn/Performance/business_case_for_performance)
  - : 웹 성능을 개선하기 위해 개발자는 많은 것을 할 수 있지만, 어느 정도까지 "빨라야" 할까요? 어떻게 경영진에게 웹 성능을 개선하는 것이 중요하다고 설득해야 할까요? 한 번 최적화를 하면 웹 성능 관련 문제가 다시 발생하지 않는다고 보장할 수 있을까요? 이 문서에서는 경영진 설득하는 법, 웹 성능을 중시하는 문화 만드는 법, 웹 성능을 위한 예산 책정하는 법을 살펴보고 코드베이스가 퇴보하지 않도록 하는 방법들을 소개합니다.

## 참조 항목

- [웹 성능 기초](/ko/docs/Learn_web_development/Extensions/Performance/Web_Performance_Basics)
  - : HTML, CSS, JavaScript, 미디어 파일 등 프론트엔드 구성 요소뿐만 아니라 어플리케이션을 느리게 만들 수 있는 기능들과 주관적, 객관적으로 빠르게 만들 수 있는 기능들이 있습니다. 웹 성능과 관련된 API, 개발자 도구, 모범 사례, 안 좋은 사례를 여럿 소개합니다. 여기에서는 그런 기능들을 기본적인 수준으로 다루면서 각 주제별로 성능을 개선하기 위해 더 깊게 살펴볼 수 있는 링크를 제공합니다.
- [반응형 이미지](/ko/docs/Web/HTML/Guides/Responsive_images)
  - : 이 문서에서는 반응형 이미지의 개념과 이를 구현하기 위해 HTML에서 제공하는 도구들을 배웁니다. 반응형 이미지란 화면 크기와 해상도, 그 외 여타 기능들에서 제각기 다른 다양한 기기들에서 잘 보여지는 이미지를 말합니다. 이를 통해 다양한 기기에서 웹 성능을 높일 수 있습니다. 반응형 이미지는 앞으로 배울 CSS 주제인 [반응형 디자인](/ko/docs/Learn_web_development/Core/CSS_layout/Responsive_Design)의 한 부분입니다.
- [MDN 웹 성능 구획](/ko/docs/Web/Performance)
  - : 가장 주요한 웹 성능 구획입니다. 여기에서 웹 성능 API 개괄, 테스트 및 분석 도구, 웹 성능 병목현상 잡아내기 등 웹 성능에 관한 훨씬 더 자세한 내용들을 찾을 수 있습니다.
