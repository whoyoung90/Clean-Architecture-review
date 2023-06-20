# 2장 두가지 가치에 대한 이야기

## 💡<strong>행위와 구조</strong>

1. 행위<br />
   요구사항을 기계에 구현하고 버그를 수정하는 일
   <br />

2. 구조<br />
   소프트웨어는 변경하기 쉬워야 한다.<br />
   변경사항을 적용하는데 드는 어려움은 <U>변경되는 "범위"에 비례해야하며,</U> 변경사항의 "형태"와는 관련이 없어야 한다.
   <br />
   <br />
   소프트웨어 개발 비용의 증가를 결정짓는 주된 요인은 바로 이 변경사항의 범위와 형태의 차이에 있다.<br />
   새로운 요청사항이 발생할 때마다 바로 이전의 변경사항을 적용하는 것보다 조금 더 힘들어지는데, 시스템의 형태와 요구사항의 형태가 서로 맞지 않기 때문이다.
   <br />
   <br />
   아키텍처가 특정 형태를 다른 형태보다 선호하면 할수록, 새로운 기능을 이 구조에 맞추는 게 더 힘들어진다. <U>따라서 아키텍처는 형테에 독립적이어야 하고, 그럴수록 더 실용적이다.</U>
   <br />
   <br />

## 💡<strong>더 높은 가치</strong>

기능인가 아니면 아키텍처인가?<br />
소프트웨어 시스템이 동작하도록 만드는 것이 중요한가? 아니면 소프트웨어 시스템을 더 쉽게 변경할 수 있도록 하는 것이 더 중요한가?
<br />
<br />
업무 관리자에게 묻는다면 소프트웨어 시스템이 동작하는 것이 더 중요하다고 답할 것이고, 이어서 개발자에게 묻는다면 업무 관리자의 의견에 대체로 동조하는 태도를 취하게 된다. 하지만 이는 잘못된 태도이다!
<br />
<br />

## 💡<strong>아이젠하워 매트릭스</strong>

1. 긴급하고 "중요한"
2. <strong><U>긴급하지는 않지만 "중요한"</U></strong>
3. <U>긴급하지만 중요하지 않은</U>
4. 긴급하지도 중요하지도 않은

"아키텍처", 즉 중요한 일은 이 항목의 가장 높은 두 순위를 차지하는 반면,<br />
"행위"는 첫번째와 세 번째에 위치한다.
<br />
<br />
업무 관리자와 개발자가 흔하게 저지르는 실수는 세 번째에 위치한 항목을 첫 번째로 격상시켜 버리는 일이다. 다시 말해 긴급하지만 중요하지 않은 기능과 진짜로 긴급하면서 중요한 기능을 구분하지 못한다.
<br />
결국 중요도가 떨어지는 기능을 선택하게 된다.
<br />
<br />

### 👉 기능의 긴급성이 아닌 <strong>"아키텍처의 중요성"</strong>을 설득하는 일은 소프트웨어 개발팀이 마땅이 책임져야 한다!

<br />
<br />

## 💡<strong>아키텍처를 위해 투쟁하라</strong>

효율적인 소프트웨어 개발팀은 뻔뻔함을 무릅쓰고 다른 이해관계자들과 동등하게 논쟁한다.<br />
맡은 업무 자체를 봐도 소프트웨어 아키텍트는 시스템이 제공하는 특성이나 기능보다는 <strong><U>시스템의 구조</U></strong>에 더 중점을 둔다.<br />
아키텍트는 이러한 특성과 기능을 개발하기 쉽고, 간편하게 수정할 수 있으며, 확장하기 쉬운 아키텍처를 만들어야 한다.

### 👉 개발자에게는 "긴급함"(행위) 보다는 <U>"중요함"(구조)</U>이다!