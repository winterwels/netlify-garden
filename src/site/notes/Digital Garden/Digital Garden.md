---
{"dg-publish":true,"dg-permalink":"Digital-Garden/Digital-Garden","permalink":"/Digital-Garden/Digital-Garden/","tags":["gardenEntry"],"created":"2026-03-23T10:58:23.344+09:00"}
---

2025-03-10 19:00

Status: 

Tags: [[Tags/dg\|dg]] 

# 안녕안녕

이 페이지 주소 : [링크](https://imaginative-griffin-caaf97.netlify.app/) 

2026-03-31 현재 기준 테마는 Avatar. 나름 이쁜거같지만 너무 형광이다.

업로드 속도는 준수하나, 종종 어떤 플러그인들과 충돌하거나, 간혹 특정 문서들의 충돌로 인해 업로드가 안되는 문제점이 있다. (콘솔창 Ctrl+Shift+i)
플러그인 하나씩 Disable 해보거나 각 문서별로 **`dg-permalink`** 설정하면 **왠만하면** 되긴 되는데 너무 자주 문제가 생긴다.
그러나 일단 체계를 갖춰두면 Obsidian Sync 를 굳이 비싼 돈 주고 유료로 안 써도 될거같다.

Test [[20. Daily-Note/2025-03/2025-03-10\|2025-03-10]] 22:18

- [[PARA/10. P-Project/현장 관리/철근\|철근]] 
- [[PARA/10. P-Project/1,000권 독서/보르헤스의-말\|보르헤스의-말]] : 나름 독후감 (다 읽지도 않음)
- [[PARA/20. A-Area/글쓰기/글쓰기\|창작]] : 그냥 이것저것
- [[PARA/20. A-Area/PKM/Obsidian\|Obsidian]] : 옵시디언 해라. 두번 해라. (내 인생이 달라졌다)
- [netlify obsidian hosting](https://www.youtube.com/watch?v=7f8e5IiUkeo) 

- [[Digital Garden/Digital Garden\|Digital Garden]]
- [[PARA/00. Inbox/TRPG/One Page Dungeon\|One Page Dungeon]]
- [[PARA/00. Inbox/TRPG/Into the darkness/Brian Dax\|Brian Dax]]
- [[PARA/00. Inbox/TRPG/Into the darkness/Ruth Kalail\|Ruth Kalail]]
- [[PARA/00. Inbox/건축법규\|건축법규]]
- [[PARA/00. Inbox/예민한 성격은 축복일까 저주일까\|예민한 성격은 축복일까 저주일까]]
- [[PARA/00. Inbox/인지적 종결욕구\|인지적 종결욕구]]
- [[PARA/00. Inbox/전문가의 세계에서 메모하는 방법\|전문가의 세계에서 메모하는 방법]]
- [[PARA/00. Inbox/지식을 수집하는 질문의 예시\|지식을 수집하는 질문의 예시]]
- [[PARA/00. Inbox/행복한-기억\|행복한-기억]]
- [[PARA/20. A-Area/PKM/Obsidian\|Obsidian]]
- [[PARA/20. A-Area/PKM/세컨드브레인\|세컨드브레인]]
- [[PARA/20. A-Area/TRPG/TRPG\|TRPG]]
- [[PARA/20. A-Area/TRPG/Into the darknessasdsd/Into the Darkness\|Into the Darkness]]
- [[PARA/20. A-Area/글쓰기/2042년, DC 메리디언 힐 공원\|2042년, DC 메리디언 힐 공원]]
- [[PARA/20. A-Area/글쓰기/Baby ruth and the finest tale about the greatest adventure\|Baby ruth and the finest tale about the greatest adventure]]
- [[PARA/20. A-Area/글쓰기/The Eternal Construction Site\|The Eternal Construction Site]]
- [[PARA/20. A-Area/글쓰기/Payback DOJO\|Payback DOJO]]
- [[PARA/20. A-Area/글쓰기/가제는 엄마 편\|가제는 엄마 편]]
- [[PARA/20. A-Area/글쓰기/글쓰기\|글쓰기]]

{ .block-language-dataview}

# 도보시오
## 가이드
[Vercel을 이용한 Digital Garden 서비스 - 가이드](https://anpigon.vercel.app/%F0%9F%A7%B0%20%EC%83%9D%EC%82%B0%EC%84%B1%20%EB%8F%84%EA%B5%AC/%EC%98%B5%EC%8B%9C%EB%94%94%EC%96%B8%20Obsidian/%ED%94%8C%EB%9F%AC%EA%B7%B8%EC%9D%B8/%EC%98%B5%EC%8B%9C%EB%94%94%EC%96%B8%20%EB%94%94%EC%A7%80%ED%84%B8%20%EA%B0%80%EB%93%A0%20%ED%94%8C%EB%9F%AC%EA%B7%B8%EC%9D%B8/01%20%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0/) : Vercel은 별로 쓰기 좋지 않다. **그냥 Netlify 를 이용**할 것. 방법은 거진 같다.

[Digital Garden Docs - 02 Commands](https://dg-docs.ole.dev/getting-started/02-commands/) : 기본 명령어
[Digital Garden Docs - 03 Note Settings](https://dg-docs.ole.dev/getting-started/03-note-settings/) : 노트 세팅 방법 (properties 등)
[Digital Garden Docs - 04 Appearance Settings](https://dg-docs.ole.dev/getting-started/04-appearance-settings/) : 테마 설정 등.

## Imgur Plugin 에러 이슈
로컬 이미지 대신 [imgur](https://imgur.com/) 로 자동으로 링크 걸어주는 플러그인이 있다. ([플러그인 페이지](https://github.com/gavvvr/obsidian-imgur-plugin))
문제는, 익명 계정이 아닌 로그인된 계정으로 업로드하는 Authenticated imgur upload 의 사용자 인증이 안되는데, [Reddit](https://www.reddit.com/r/ObsidianMD/comments/1b6d2me/imgur_plugin_no_longer_working/) 의 mghalix의 해결책을 따르면 됨.
1. Go to [https://api.imgur.com/oauth2/addclient](https://api.imgur.com/oauth2/addclient)
2. Use any name for "Application name". For example: "Obsidian Imgur plugin"
3. Choose "OAuth 2 authorization **with a callback URL**"
4. Important: use `obsidian://imgur-oauth` as an "Authorization callback URL" value
5. Fill in the "Email" field and proceed to get your Client ID
---
Now go back to your Obsidian `Settings` > `Imgur Plugin Setting`
- Switch `Images upload approach` to `Anonymous Imgur Upload`
- A new field `Client ID` will appear, fill it with the `Client ID` generated after completing step 5
    - You can find and manage your `Client ID`s [here](https://imgur.com/account/settings/apps
    - You don't need the secret key for this to work.

If you're curious why this has changed in the first place, it was mentioned in the plugin developer's repository that this is to avoid hitting daily rate limits, so it was decided that each user should create his own `Client ID`
# References