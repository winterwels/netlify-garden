---
{"dg-publish":true,"dg-permalink":"PKM/Obsidian","permalink":"/PKM/Obsidian/"}
---


2025-03-20 20:26

Status: 

Tags: [[PKM/PKM\|PKM]] , [[dg\|dg]] 

# Obsidian
아래 [[6. Main Notes/플러그인\|플러그인]] 관련은 해당 문서에 정리할 것. - 250216

이 페이지를 포함한 사이트는 [[PKM/Obsidian\|Obsidian]] 의 [Digital Garden](https://dg-docs.ole.dev/) 플러그인을 통해 만들어졌읍니다. 호스팅은 [Netlify](https://app.netlify.com/) 에서 하고 있읍니다

# Smart Random note 를 이용한 #재참조 방법
경로 : `path:"2. source material/시공"` 와 같이 경로로 한정하여 랜덤노트 사용 가능.
태그 : `tag:` 
# 질문
[sandbox vault](https://forum.obsidian.md/t/how-to-open-sandbox-vault/50028) 가 뭐죠? (단축키 뭔가 누르다가 갑자기 뜸)

# 활용례
- Vault Tour (타인 Vault 참고)
	- [CyanVoxel](https://www.youtube.com/watch?v=rAkerV8rlow)
- 가이드글
	- [obsidian.help](https://help.obsidian.md/Home) : 공홈
	- [대학생활 뽀개기](https://www.youtube.com/watch?v=NrwTzzSNPK8) : 유튜브 영상인데 너무 길다. 대학생, 대학원생 관련 내용.
- [미니멀리즘적으로 사용 (플러그인 최소화, 바닐라)](https://youtu.be/hSTy_BInQs8) 
- [옵시디언을 세컨드 브레인으로 만드는 방법](https://info.quokkanews.com/옵시디언을-세컨드-브레인으로-만드는-방법/) 
## 노트토크 후기
- 출처: [노트토크 후기](https://www.secondbrain.kr/0207a471-c397-48e5-9cfa-a233e8be4530
- 원칙
    - 되도록 한 곳에 데이터 저장
	- import/export 가능
	- 통일성 있는 구조 (자료구조, 네이밍)
	- 특정 앱에 귀속되어있는가?
	- GTD 방법론 → 개인지식관리에 도움됨
	- 너무 많은 걸 저장하려하지 X (CODE)

# 기본 기능
- [Use callouts](https://help.obsidian.md/How+to/Use+callouts) : 문서를 "예쁘게" 만들고자 할 때 사용
- 단축키 (Hotkeys)
	- [옵시디언 사용기3 - 단축키 극한 활용](https://kexplain.com/15)
- [분석맨 - 옵시디언 자주 묻는 질문(FAQ)](https://secondbrain.analysisman.com/1_WRITE/1_Obsidian/%EC%98%B5%EC%8B%9C%EB%94%94%EC%96%B8+%EC%9E%90%EC%A3%BC+%EB%AC%BB%EB%8A%94+%EC%A7%88%EB%AC%B8(FAQ)  
- [Obsidian 한국어 정보 페이지](https://publish.obsidian.md/help-ko/%EB%85%B8%ED%8A%B8%EC%99%80+%ED%8C%8C%EC%9D%BC+%EC%97%B0%EA%B2%B0%ED%95%98%EA%B8%B0/%EB%B3%84%EC%B9%AD). 
- [URL로 기사 스크랩하기](https://junggam2.tistory.com/43) : ``extract url content : Extract`` (기본 기능)
- [CSS Snippet](https://m.cafe.naver.com/ca-fe/web/cafes/obsidianary/articles/8325?tc=shared_link&useCafeId=false&or=nid.naver.com&buid=28feaaf8-43de-43ce-b674-83bc3e27de1e&art=ZXh0ZXJuYWwtc2VydmljZS1uYXZlci1ldGMtZm9yLWNvbW1lbnQ.eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJjYWZlVHlwZSI6IkNBRkVfSUQiLCJhcnRpY2xlSWQiOjgzMjUsImlzc3VlZEF0IjoxNzI3ODcwMjk0NjAwLCJjYWZlSWQiOjMwNTM3NDQ4fQ.J8ly4JzAmKo6_rKTD1F4g4GSJ-_hz4IWBZO_om2bZrs) 
- 절대경로로 파일 링크 첨부하기 : `[linkname](file:///<absolute-path>)` : ※ 주의 : 공백은 `%20`으로 입력

## Foot Note
각주사용법 정리한걸 전달 드려봐요

#### **기본 형식**

1. 각주를 본문에 삽입하려면 대괄호와 함께 `^` 기호를 사용:
    
    ```markdown
    본문 내용[^1]
    ```
    
2. 각주의 내용을 문서 하단에 작성:
    
    ```markdown
    [^1]: 이곳에 각주 내용을 작성
    ```
    

---

#### **여러 각주 사용**

각주를 여러 개 사용할 경우, 각 각주의 번호를 고유하게 지정:

```markdown
이것은 첫 번째 각주[^1], 이것은 두 번째 각주[^2]입니다.

[^1]: 첫 번째 각주 내용
[^2]: 두 번째 각주 내용
```

---

#### **번호 대신 텍스트 사용**

각주 식별자에 숫자 대신 텍스트를 사용할 수 있음:

```markdown
이 문장은 텍스트 각주[^example]를 포함합니다.

[^example]: 텍스트 식별자를 사용하는 각주 내용
```

---

#### **줄바꿈 포함 내용**

각주 내용이 길거나 여러 줄에 걸쳐 있을 경우 줄바꿈 가능:

```markdown
본문 내용에 각주를 추가합니다[^longnote].

[^longnote]: 각주 내용이 길다면
    이렇게 줄을 바꿔 작성 가능합니다.
```

- 줄바꿈된 내용은 반드시 공백 4칸 또는 탭 1번으로 들여쓰기 해야 같은 각주로 인식됨.

##### 예시: 줄바꿈된 각주 내용

```markdown
본문 내용에 각주를 추가합니다[^longnote].

[^longnote]: 이 내용은 첫 줄입니다.
    두 번째 줄도 같은 각주에 포함됩니다.
```

##### 주의 사항

- 들여쓰기 없이 줄바꿈하면 마크다운이 새로운 텍스트로 인식:

잘못된 예:

```markdown
[^longnote]: 첫 줄입니다.
두 번째 줄입니다. (새로운 텍스트로 인식)
```

올바른 예:

```markdown
[^longnote]: 첫 줄입니다.
    두 번째 줄도 같은 각주에 포함됩니다.
```

---

#### **문서 하단 없이 바로 삽입**

각주의 내용이 짧으면 한 줄로 바로 작성 가능:

```markdown
본문 내용[^간단한 각주 내용].
```

이 방법은 각주 목록 없이 간단히 표현할 때 유용.

---

### 활용 팁
- **템플릿에 포함**: 각주 형식을 템플릿에 포함하여 효율적으로 사용.
- **데이터뷰 연동**: 각주를 메모와 연결하거나 태그로 추가 정보를 제공할 때 유용.
- **복잡한 참고자료 작성**: 논문, 리포트, 또는 블로그 글 작성 시 각주 활용 가능.
# Trouble Shooting
## Image 업로드 시 기본으로 보여지는 사이즈 너무 큼 → CSS 조정. 
- 방법 : Setting → Appearance → CSS snippet → 해당 폴더에서 .css 파일 만들기
```
.workspace-leaf-content img:not([width]) {
    max-width: 50%;
}
```

## 모바일에서 실행 시 데스크탑 세팅을 그대로 가져온 탓에, 안쓰는 플러그인 들이 너모 많다. → 모바일 전용 CSS 설정
념념굿

# References
