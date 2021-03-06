---
description: 스케줄러(PBS)를 통한 작업 실행
---

# 스케줄러(PBS)를 통한 작업 실행

\
5호기 누리온 시스템의 작업 스케줄러는 Portable Batch System (이하 PBS)을 사용한다. 이 장에서는 스케줄러를 통해 작업 제출하는 방법 및 관련 명령어들을 소개한다. 사용자가 작업 제출 시 사용할 수 있는 큐는 정해져 있으며, 큐 별로 사용자별 최대 제출할수 있는 작업의 수는 제한이 있고, 이 값은 시스템의 부하 정도에 따라 변동될 수 있다.

&#x20;

누리온 시스템은 **베타적 노드 할당 정책**을 기본적으로 적용하여, 한 노드에 한 사용자의 작업만이 실행될 수 있도록 보장한다. 이는 공유 노드 정책을 적용할 경우 종종 발생할 수 있는 사용자 어플리케이션의 심각한 성능 저하를 예방하기 위함이다. 그러나 상용 SW를 사용할 수 있는 큐의 경우는 노드의 규모가 크지 않아서 효율적인 자원 활용을 위해 공유 노드 정책을 적용한다.

&#x20;

사용자 작업은 로그인 노드를 통해서만 제출이 가능하며 또한, 일반 사용자가 계산노드에 직접적으로 접근할 수 없다.



**가.** [**큐 구성** ](untitled.md)****

**나.** [**작업 제출 및 모니터링**](.-1.md)****

**다.** [**작업 제어** ](.-2.md)****
