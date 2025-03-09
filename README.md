# wargame-flag-ga-even-hage
이것은 워게임입니다. 
- 분야 : MISC
- 난이도 : easy

## 문제 설명
플래그가 even하게 정리 되지 않았습니다.
even하게 정리하면 flag를 드리겠습니다.

## 문제 풀이
문제에는 아래와 같이 based txt가 제공 된다.

```
based txt : 
IS'Fl{lf lgAiGv_e9 Ay_oeuv etnh_eh AfGl3a_g1 9ljo1l_oalNohl_oal5o5l_o3lo_y_O_}
```

해당 인덱스를 홀수 짝수로 나눠서 정리하면 아래와 같이 나눌 수 있다.

- ODD : I'll give you the flag lolololololol___
- EVEN : SF{flAG_9A_even_hAG3_19j1_aNh_a55_3oyO}
(해당 문제에서는 첫 텍스트의 시작이 0이 아닌 1이다.)

위와 같이 분리 된다.
최종적으로 flag를 획득할 수 있다.

## flag
SF{flAG_9A_even_hAG3_19j1_aNh_a55_3oyO}
