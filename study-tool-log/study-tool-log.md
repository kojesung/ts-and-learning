# 학습 도구 로그

-   학습에 도움이 되는 도구를 만들고, 기록합니다. 필요하면 코드를 남깁니다.

## **도구 이름**

-   PiFSR 도우미

## **도구 유형** (예: GPTs, gems, Claude Code(skill, command, agent, ...) Chrome Extension, CLI, 웹사이트 등)

-   Claude Code(sub-agents)

## **해결하려는 문제**: 어떤 학습 상의 불편/문제를 해결하려 했는가?

-   문제 위주로 학습할 때 Problem-Driven 단계에서 문제의 목적(왜 배워야하는지)을 파악하기 어려움
-   개념에 대한 이해가 완벽하지 않을 때 i+1 단게에서 어떤 도전을 해야할지 결정하기 어려움

## **어떻게 만들었는가**: 간단한 제작 과정

-   처음에는 tsc-check 스크립트나 typescript best practice skills를 찾아서 적용할까 고민했지만 적절한 외부 skills를 찾기 어려웠고 tsc-check와 같은 스크립트는 터미널에서 간단하게 확인 가능했던 점과 typescript best practice 또한 agent가 별다른 프롬프트 없이 좋은 결과물을 만들어 줄 것이라고 생각하여 sub-agents만 활용하기로 결정했음

    -   problem-prep: 문제 풀기 전 실행. 문제 번호를 말하면 `exercises/exercise-0N/index.ts`를 직접 읽고 핵심 개념과 왜 배워야 하는지(Problem-Driven), 이번에 집중할 한 가지 목표(i+1)를 제시한다.

    -   typescript-mentor: 문제 풀고 나서 실행. 코드를 읽고 사용된 개념 키워드 추출, 실무 예시 연결, Best Practice 개선 제안을 해준다. 정답 코드는 절대 주지 않는다.

## **어떻게 도움이 되었는가**: 실제 사용 경험과 효과

-
