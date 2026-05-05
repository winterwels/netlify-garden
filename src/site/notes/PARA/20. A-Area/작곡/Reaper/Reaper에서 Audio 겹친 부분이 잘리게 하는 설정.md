---
{"dg-publish":true,"dg-permalink":"Reaper에서-Audio-작곡/Reaper/Reaper에서-Audio-겹친-부분이-잘리게-하는-설정","permalink":"/Reaper에서-Audio-작곡/Reaper/Reaper에서-Audio-겹친-부분이-잘리게-하는-설정/","created":"2026-04-13T20:11:30.910+09:00","dg-note-properties":{"created":"2026-04-13 20:11:30","update":"2026-04-13 20:11:30"}}
---

Status: 

Tags: 


---
[[PARA/20. A-Area/작곡/Reaper/Reaper\|Reaper]] 에서 Sampling 할때 주로 건드리게 되는 설정은 Pitch, Fade 등 종류가 많다만, 나는 샘플링을 많이 하는 편이고 괴상한 걸 좋아하기 때문에 같은 샘플을 여러번 겹치는 경우가 있다.

근데 기본 설정은 **Cross-Fade** 즉, 기존에 있던 Audio 1과 겹치는 Audio 2가 서로 겹치는 부분이, 즉 각자의 끝과 시작부분이 겹치게 되어있다. 

# 1. Cross-Fade 끄기
![](https://i.imgur.com/dlZboUb.png)

상단 메뉴 Options - Auto-crossfade media items when editing (**단축키 Alt+X**) 해제

# 2. 겹친 부분을 보이지 않게 하기 (Trim Content)

아이템을 겹쳤을 때 밑에 깔린 부분을 시각적으로나 기능적으로 '잘린' 상태로 만들고 싶다면 다음 옵션을 건드려야 합니다.
- **`Options`** 메뉴에서 **`Trim content behind media items when editing`**을 **체크**하세요.
- **효과:** 이 옵션을 켜면 새로운 아이템을 기존 아이템 위로 드래그했을 때, 겹치는 부분만큼 기존 아이템의 길이가 자동으로 조절(Trim)되어 잘려 나갑니다.

![](https://i.imgur.com/kP1Q7yb.png)

# 3. 레이어 형태(Free Item Positioning) 끄기
![](https://i.imgur.com/OMnSNsp.png)

혹시 한 트랙 안에서 아이템들이 위아래로 층이 나뉘어 겹쳐 보인다면 이 설정이 켜져 있을 수 있습니다.
- 트랙 위에서 **우클릭** > **Free item positioning**이 체크되어 있다면 **해제**하세요.
- 이렇게 하면 모든 아이템이 한 줄(Lane)에 배치되어, 위에서 설정한 **`Trim content`** 기능이 더 명확하게 작동합니다.

# References
