---
{"dg-publish":true,"dg-permalink":"Digital-Garden/Digital-Garden","permalink":"/Digital-Garden/Digital-Garden/","tags":["gardenEntry"]}
---

2025-03-10 19:00

Status: 

Tags: [[dg\|dg]] 

# 바아아아

이 페이지 주소 : [링크](https://imaginative-griffin-caaf97.netlify.app/) 

커스텀 CSS 관련해서는 어떻게 하는지 잘 모르겠다. (일단 기본 폰트는 매우 안 이쁘다)

업로드 속도는 준수하나, 종종 어떤 플러그인들과 충돌하거나, 특정 문서들의 충돌로 인해 업로드가 안되는 문제점이 있다. [[AI\|ChatGPT]] 랑 열심히 씨름해야한다. (콘솔창 Ctrl+Shift+i)
플러그인 하나씩 Disable 해보거나 각 문서별로 **`dg-permalink`** 설정하면 **왠만하면** 되긴 되는데 너무 자주 문제가 생긴다.
Obsidian Sync가 가격은 비싸도 이런 걸로 고민 안해도 되니 차라리 나을지도 모름.)

Test [[Daily-Note/2025-03/2025-03-10\|2025-03-10]] 22:18

- [[2. Source Material/시공/철근\|철근]] 
- [[6. Main Notes/독서/보르헤스의-말\|보르헤스의-말]] : 나름 독후감 (다 읽지도 않음)
- [[6. Main Notes/창작/창작\|창작]] : 그냥 이것저것
- [[PKM/Obsidian\|Obsidian]] : 옵시디언 해라. 두번 해라. (내 인생이 달라졌다)
- [netlify obsidian hosting](https://www.youtube.com/watch?v=7f8e5IiUkeo) 

# 도보시오
## 가이드
[Vercel을 이용한 Digital Garden 서비스 - 가이드](https://anpigon.vercel.app/%F0%9F%A7%B0%20%EC%83%9D%EC%82%B0%EC%84%B1%20%EB%8F%84%EA%B5%AC/%EC%98%B5%EC%8B%9C%EB%94%94%EC%96%B8%20Obsidian/%ED%94%8C%EB%9F%AC%EA%B7%B8%EC%9D%B8/%EC%98%B5%EC%8B%9C%EB%94%94%EC%96%B8%20%EB%94%94%EC%A7%80%ED%84%B8%20%EA%B0%80%EB%93%A0%20%ED%94%8C%EB%9F%AC%EA%B7%B8%EC%9D%B8/01%20%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0/) 
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