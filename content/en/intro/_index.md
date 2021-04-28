---
title: "들어가기"
linkTitle: "0. 들어가기"
weight: 10
description: >
   
---

## 배경과 취지

정보통신기술(ICT)의 눈부신 성장으로 인해 기업들은 AI, 5G, 빅데이터, 클라우드 등 신기술을 활용한 새로운 서비스를 끊임없이 출시하고 있다. 또 우수한 소프트웨어 개발자를 영입하기 위하여 치열한 경쟁을 벌이기도 한다. 이러한 성장과 변화의 근간은 무엇일까? 바로 오픈소스이다. 바꾸어 말하면 오픈소스 없이는 새로운 서비스를 출시할 수도, 기술 혁신을 이룰 수도 없다. 피할 수 없는 오픈소스와의 상생에 발맞추어 글로벌 ICT 기업들은 그들의 기술을 오픈소스로 공개하고 오픈소스 커뮤니티와의 협력을 위해 무던히 노력하며, 이를 위해 많은 투자를 기울이고 있다. 

오픈소스의 기본 전제는 소스 코드의 공개, 그리고 자유로운 활용이다. 하지만 사용하는 데에 비용이 들지 않는다고 해서 저작권까지 없는 것은 아니다. 제대로 살펴보지 않고 무분별하게 사용했다가는 모르는 사이에 저작권을 침해하거나 혹은 보안 취약점 이슈에 노출이 될 가능성도 있다. 따라서 어떤 오픈소스를 사용하더라도 기본적인 조건에 대해서는 꼼꼼히 확인해볼 필요가 있다.  

국내 기업들도 오픈소스를 활용하여 소프트웨어 제품과 서비스를 개발하고 출시하고 있다. 그러나 아직은 많은 기업이 단순히 오픈소스를 도입하여 사용하는 수준에 그치고 있는 실정이다. 하지만 오픈소스 커뮤니티와의 적극적인 협력 없이 소비하기만 한다면 생태계의 발전은 한계에 다다를 것이다. 

NIPA에서는 우리나라의 기업이 어떻게 하면 (1) 올바르게 오픈소스를 사용하고 (2) 커뮤니티에 적극적으로 참여하며 (3) 서로가 함께 발전할 수 있을지 고민하였다. 이에 우리나라에서 오픈소스를 적극적으로 활용하는 대표 IT기업인 카카오, 라인플러스, SK텔레콤의 경험을 바탕으로 기업의 오픈소스 거버넌스 정책 및 모범 사례를 정리한 가이드를 제작하였다. 이 기업의 오픈소스 전문가들은 오픈소스의 공유와 협업의 정신에 따라 기업의 정책과 사례를 공유하였다. 이 가이드가 우리나라의 많은 기업이 올바르게 오픈소스를 활용하는 방향을 제공할 수 있기를 바란다.

## 구성

본 가이드는 기업이 오픈소스를 활용하는 경우를 세 가지로 나누어 구분하였고, 마지막으로는 기업에서 오픈소스 정책/프로세스와 관련된 체계를 세우는 데에 필요할 조직의 구성 방안에 관해 설명한다. 

1. 오픈소스 사용하기 - 기업 편/개발자 편
2. 오픈소스 기여하기 - 기업 편/개발자 편
3. 오픈소스 공개하기 - 기업 편/개발자 편
4. OSPO<sub>Open Source Program Office, 오픈소스 프로그램 사무소</sub>

각 주제는 이해를 돕기 위해 기업 구성원의 입장에 따라 기업 편과 개발자 편으로 나누어 설명한다. 기업 편은 오픈소스 담당자가 정책과 프로세스를 구축하기 위해 알아야 할 사항을 중점적으로 다루고, 개발자 편에서는 기업에 속한 개발자가 오픈소스를 활용하는 데에 알면 도움이 될 사항을 중점적으로 다룬다. 

## 각 장 소개

### 1. 오픈소스 사용하기

이 장에서는 오픈소스를 기업 자산의 일부로 도입할 때 기업이 고려해야 할 사항을 설명한다. 

기업의 오픈소스 담당자는 기업 내 오픈소스 컴플라이언스/보안 취약점 대응을 위한 정책과 프로세스를 수립할 수 있다. 각 프로세스에서 필요하게 될 도구와 자동화에 대한 정보도 확인할 수 있다.  

- 오픈소스 도입 시 고려사항
- 오픈소스 컴플라이언스
- 라이선스 의무사항
- 오픈소스 관리 도구
- 오픈소스 보안 취약점

개발자는 기업의 정책을 이해하기 위해 필요한 라이선스 기본 지식을 쌓을 수 있고, 개발 현업에서 오픈소스를 도입할 때 고려해야 할 내용을 확인할 수 있다. 

- 오픈소스 라이선스
- 오픈소스 선택 가이드

### 2. 오픈소스 기여하기

이 장에서는 기업의 구성원이 외부 오픈소스 개발에 참여하고 직접 기여할 때 기업이 고려해야 할 사항을 설명한다. 

기업의 오픈소스 담당자는 기업의 기여 방향성과 올바른 기여 정책을 수립할 수 있다. 이런 견고한 전략 없이는 투자한 노력이 무상하게 오픈소스 커뮤니티에서 반응을 얻지 못하거나 법적 위험을 초래할 수도 있기 때문에 오픈소스 프로젝트와 운영 방식을 제대로 이해할 필요가 있다. 

- 기업이 오픈소스에 기여해야 하는 이유
- 오픈소스 기여 전략 수립 시 고려 사항
- 오픈소스 기여 정책 포함 내용

개발자는 오픈소스에 기여할 때 필요한 기초 지식과 오픈소스 개발에 참여하는 방법을 확인할 수 있다. 

- 오픈소스 프로젝트 구성
- 오픈소스 기여 준비
- 좋은 기여자가 되기 위한 길잡이
- 기여 제출 방법

### 3. 오픈소스 공개하기

이 장에서는 내부에서 제작한 소프트웨어를 오픈소스로 공개하는 기업이 고려해야 할 사항을 설명한다. 

기업의 오픈소스 담당자는 오픈소스 공개의 궁극적인 목표를 설정하고 이에 따른 정책과 프로세스를 수립할 수 있다. 각 프로세스를 진행하는 실무에 대해서도 이해할 수 있다. 

- 오픈소스 공개 이유
- 오픈소스 공개 규칙
- 문서화
- 오픈소스 공개 절차
- 공개 후에 해야 할 일

개발자는 회사 업무로 오픈소스를 공개하고 운영할 때 고려해야 할 부분에 관한 내용을 확인할 수 있다. 
- 오픈소스 공개 준비
- 오픈소스 운영하기

### 4. OSPO

이 장에서는 OSPO<sub>Open Source Program Office, 오픈소스 프로그램 사무소</sub>가 무엇인지, 이를 만들기 위한 방법과 절차에 관해 설명한다.

지금까지 위에서 설명한 것처럼 오픈소스를 효과적으로 활용하기 위해서는 기업 내 오픈소스 거버넌스 체계를 수립해야 한다. 기업이 오픈소스와 관련된 다양한 활동을 적극적으로 관리한다면 오픈소스로부터 최대한의 가치를 창출하고 동시에 법적인 리스크를 완화할 수 있기 때문이다. 글로벌 ICT 기업은 오픈소스 거버넌스 체계를 구축하고 이를 성장시키기 위해 OSPO 조직을 설립하고 있다. OSPO는 기업의 오픈소스 거버넌스 체계를 구축할 뿐만 아니라 기업의 성공을 위한 오픈소스 전략을 수립하고 실행하는데 필요한 정책, 프로세스 및 도구를 제공하기도 한다.

- OSPO란?
- OSPO 구성 절차
- OSPO 인원 구성
- OSPO 역할

## 결론 및 제언

오픈소스의 영역은 앞으로도 빠르게 확장될 것이다. 오픈소스는 기업이 추구하는 혁신을 빠르게 이룰 수 있게 하는 중요한 동력이다. 오픈소스 활용이 늘면 그만큼 라이선스/보안 취약점 이슈도 증가한다. 기업은 이슈 대응뿐만 아니라 효율성을 극대화하기 위해 오픈소스 거버넌스 정책과 프로세스를 구축해야 한다. 또 단순히 오픈소스를 사용하는 데에서 그치지 않고, 커뮤니티와 협조하며 오픈소스의 진정한 가치를 창출해야만 생태계의 자원이 고갈되지 않을 것이다. 

본 가이드는 이 모든 활동들을 위한 길라잡이를 제공한다. 이미 여러 해외 기업이나 재단에서 내놓은 가이드 문서가 있지만, NIPA의 주관으로 국내 대표 ICT 기업의 오픈소스 전문가의 오랜 경험과 실무 지식을 바탕으로 작성되었다. 오픈소스를 올바르게, 그리고 적극적으로 활용하려는 기업에 길라잡이가 되기를 바란다. 

이 가이드는 여러 일반적인 사항을 다루고 있지만, 모든 예외사항까지 다룰 수는 없었다. 하지만, NIPA의 GitHub Repository에 가이드 전문을 공개하였고, 누구나 보완이 필요하다면 추가로 작성하여 직접 Pull Request를 제출할 수 있다. 또, 문의나 요청에 대해 Issue를 생성할 수도 있다. 이처럼 오픈소스 개발 방법을 가이드 제작에 적용하였으므로 오픈소스에 관심 있는 독자들의 많은 참여를 바란다.

{{% alert title="가이드 전문 GitHub Repository" color="success" %}}
*  https://github.com/NIPA-OpenUP/oss-governance-guide
{{% /alert %}}