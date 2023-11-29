### 본론으로 들어가기 전에
![](https://velog.velcdn.com/images/noyohanx/post/4ac37302-023e-4895-b0cb-bb359d063f50/image.png)

이름과 프로필 이미지를 설정했는데도 뭔가 허전해보이는 프로필.. 1학년때의 저를 생각해보면 깃허브를 잘 사용하지도 않았지만 친구들과 팔로우도 하고, 깃허브를 서로 교환하였기 때문에 이 허전한 화면을 꾸밀 순 없을까하며 다른 사람들의 프로필을 찾아보기도 했던 것 같아요.
![](https://velog.velcdn.com/images/noyohanx/post/e0e2e7ba-be93-4984-83e9-6cd60c7e9a92/image.png)
그렇게 찾아보고 있는데 Velog에서 글을 쓰시는분의 프로필을 들어가면 알록달록한 소개 글들이 있더라고요. 따라하고 싶은데 이건 어떻게 하는거지? 라는 생각이 들더라고요.

지금 이 글을 읽는 여러분도 이런 고민을 하진 않으신가요? ~~궁금해주세요~~ 그런 여러분들의 궁금증을 해결하기 위해 들고왔습니다. 프로필 README 꾸미기!
### 프로필 README 꾸미기
![](https://velog.velcdn.com/images/noyohanx/post/a0dc0ad1-3dad-402b-bf98-a85f4d36e34a/image.png)

프로필을 꾸미는 README라는걸 작성하기 위해선 레포지토리를 생성해야합니다. 레포지토리가 뭐하는 공간인지는 추후 업로드할 글에서 알려드리도록 하겠습니다.
`Repositories` -> `New` 를 클릭하여 레포지토리 생성 창으로 이동해줍니다.
![](https://velog.velcdn.com/images/noyohanx/post/31ec6d20-5c7e-4a10-8d3c-3daddaf996a5/image.png)
이때 자신의 깃허브 ID로 Repository name을 설정하면 스폐셜한 레포지토리라고 뜨게 되고, public, Add a README file 등의 옵션을 체크해주고 `Create Repository`를 클릭하여 레포지토리를 생성해줍니다.
![](https://velog.velcdn.com/images/noyohanx/post/40c411d6-e189-493e-b46e-10c09f3982c8/image.png)
생성을 하게되면 오른쪽에 스페셜한 레포지토리라며 프로필 	방문하기, README 수정하기 버튼이 보일겁니다. `Edit README` 를 클릭하여 사람들에게 보여줄 README.md 파일을 수정해줍니다.
![](https://velog.velcdn.com/images/noyohanx/post/eabe75c8-de6e-4ecb-83a2-af42e5a8ab03/image.png)
저는 간단하게 소개하도록 하겠습니다. `요한의 블로그 전용 깃허브` 라고만 적어둘게요.이때 마크다운 문법으로 작성하게 되는데 마크다운 문법도 추후 소개해드리도록 할게요.
![](https://velog.velcdn.com/images/noyohanx/post/79e9f1dc-6629-48b3-8b20-4184410a17ba/image.png)
이때 `Preview` 를 눌러 작성한 마크다운의 결과물을 미리 볼 수 있습니다.
![](https://velog.velcdn.com/images/noyohanx/post/ff4114da-6488-4fe5-9dcb-7ab883dbe07f/image.png)
`Commit changes` 를 눌러 변경 사항을 저장해줍니다. Commit Message, branch 지정 등 다양한 옵션이 있지만 지금은 별로 중요하지 않아 넘어가도록 합니다. `Commit changes` 를 클릭해줍니다. 변경 사항이 반영된 것을 볼 수 있습니다.
![](https://velog.velcdn.com/images/noyohanx/post/79d92c23-dc66-48d7-8fa0-0c512f684ed7/image.png)
그리고 프로필의 메인에 가보면 자신이 변경한대로 반영된 것을 볼 수 있습니다. 이제 자신이 원하는대로 자신의 프로필을 예쁘게 꾸미시면 되겠습니다.

## 꾸미기 위한 도구 소개
### 뱃지
https://github.com/Envoy-VC/awesome-badges
자신이 할 수 있는 기술, SNS 등을 공유할 때 유용한 뱃지들입니다. 
![](https://velog.velcdn.com/images/noyohanx/post/941528ac-9a79-48f0-a299-192c393bbff6/image.png)
위 링크에 접속하시면 여러가지 뱃지들이 나오게 되는데요. 이때 자신이 넣고 싶은 뱃지의 URL을 복사하여 `![](URL_링크)` 이런식으로 붙여넣어주면 
![](https://velog.velcdn.com/images/noyohanx/post/02ec3507-0cb4-4898-bba9-7344d1f988fc/image.png)
위의 사진과 같은 결과물이 나오게됩니다.

### 백준 티어
https://github.com/mazassumnida/mazassumnida
알고리즘 문제를 푸는 사이트인 [백준](https://www.acmicpc.net/)의 티어를 가져올 수 있는 도구에요.
```
[![Solved.ac
프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=wke1wke1)](https://solved.ac/wke1wke1)
```
적용법은 위와 같고, `boj=wke1wke1` 에서 wke1wke1 부분을 자신의 백준 아이디로 변경해주시면돼요. (wke1wke1는 제 백준 아이디에요.)
![](https://velog.velcdn.com/images/noyohanx/post/99574bb6-1098-4579-83d8-ad43900342c1/image.png)
적용한 이후 미리보기는 위와 같습니다. 저는 백준을 안풀다시피해서 브론즈네요..ㅎㅎ 블로그를 운영하며 여러분과 함께 올려보도록 하겠습니다!

### 방문자 수
https://hits.seeyoufarm.com/
방문자 수를 체크할 수 있는 도구입니다. 위 사이트에 접속합니다.
![](https://velog.velcdn.com/images/noyohanx/post/cf1ebaff-fc7e-4c68-8d18-6f98a855742a/image.png)

접속하셔서 github.com/ 뒤에 본인의 github 아이디를 입력해주세요! 그리고 `MARKDOWN` 우측 아래에 있는 `COPY` 버튼을 클릭하셔서 복사합니다.
![](https://velog.velcdn.com/images/noyohanx/post/a6bcd7b7-4cf5-496f-b7e6-48bac98b27bb/image.png)


붙여넣은 결과물은 위와 같습니다.

### Most Language
https://github.com/anuraghazra/github-readme-stats
```
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=yohan050605)](https://github.com/anuraghazra/github-readme-stats)
```
자신이 주로 사용하는 프로그래밍 언어를 공유할 수 있는 도구입니다. 
![](https://velog.velcdn.com/images/noyohanx/post/4548b305-39d9-4b1f-a879-7a4656555c7f/image.png)
제 깃허브는 현재 만든지 얼마 되지 않아 집계할 수 없다고 뜨는데요..
![](https://velog.velcdn.com/images/noyohanx/post/ca909f41-a87d-42bf-bc7c-33b48b33cc51/image.png)
코드들을 업로드하시다보면 위와 같이 통계가 잡혀 어떤 언어를 어느 정도 사용했는지를 공유할 수 있습니다.

### Github Stats
https://github.com/anuraghazra/github-readme-stats
```
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=yohan050605)](https://github.com/anuraghazra/github-readme-stats)
```
`api?username=자신의깃허브고유아이디` 로 변경해주시면 됩니다.
![](https://velog.velcdn.com/images/noyohanx/post/c3f2c0d8-478b-4ffd-8c73-87da4d29e81b/image.png)

깃허브 프로필에서 요쪽이 본인의 깃허브 고유 아이디입니다.

![](https://velog.velcdn.com/images/noyohanx/post/cb300957-43a7-4983-be02-cfc3409f0c70/image.png)



결과는 위와 같습니다. 깃허브에서 코드를 업로드하며 협업을 지속적으로 하다보면 등급이 올라가게될거에요.

### Header 및 Footer
https://github.com/kyechan99/capsule-render
Header 및 Footer를 예쁘게 꾸밀 수 있는 도구입니다.

위 사이트에 접속하여 본인의 마음에 드는 type, color, height, section, text, fontSize 등을 골라 채워넣습니다.
```
![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule&fontSize=90)
```
저는 이런식으로 옵션들의 값들을 채웠고

![](https://velog.velcdn.com/images/noyohanx/post/5e4e436a-ef27-4ac9-84c0-3e0323d9a4c4/image.png)
결과물은 위와 같습니다.


### 남의 RADME 코드 가져오기
위의 방법들을 참고해서 꾸며봐도 마음에 들지 않거나, 어떻게 꾸며하는지 감도 안오시는 분들도 있을거에요. 그럴땐 남의 README를 배껴봅시다!
![](https://velog.velcdn.com/images/noyohanx/post/5da065ed-fc42-418f-aca9-0c276ced9419/image.png)
![](https://velog.velcdn.com/images/noyohanx/post/feefef72-7cc8-4b32-8387-28a6a6f71731/image.png)


다른 사람의 프로필 메인으로 들어가 빨간 박스 부분을 클릭해줍니다.

![](https://velog.velcdn.com/images/noyohanx/post/c8637970-e8b0-48e1-96a8-1cab9bfb54f3/image.png)
그렇다면 그 사람의 README.md 가 저장된 레포지토리로 이동하게 되는데요. README.md 파일을 클릭해줍시다.
![](https://velog.velcdn.com/images/noyohanx/post/eb05700b-3609-4799-a6b5-5a1aa750df37/image.png)
이후 오른쪽 상단에 뜨는 연필 모양 아이콘을 클릭하여 `Fork this repository and edit this file` 을 진행해줍니다.
![](https://velog.velcdn.com/images/noyohanx/post/0478bc8d-3951-4e9d-9455-faf540b92102/image.png)
클릭하게되면 레포지토리를 Fork 할거냐고 묻는데요. Fork를 간단히 설명하면 다른 사람의 레포지토리를 내 레포지토리로 복사해온다고 생각하면 편해요. 

`Fork this repository` 를 클릭하여 Fork를 진행해줍니다.


![](https://velog.velcdn.com/images/noyohanx/post/861a5851-e065-4a09-b359-f260b0ebd769/image.png)

Fork를 진행하게 되면 위와 같이 그 사람이 작성한 README.md 파일의 코드가 보이게되는데요 복사하고, 위에서 알려준 도구들을 응용해서 본인의 입맛에 맞게 수정해줍니다.
![](https://velog.velcdn.com/images/noyohanx/post/078f9cbe-90a7-4af4-9d13-3fcf869a7400/image.png)
다른 사람의 README를 입맛에 맞게 수정했으니 Fork해온 레포지토리를 본인의 Repositories에서 삭제해보도록합시다. Repositories에 가게되면 Fork 해온 Repository가 있을텐데요. 클릭하여 들어가줍니다.

![](https://velog.velcdn.com/images/noyohanx/post/018afc7c-7996-4b51-a629-05fe3af04b7d/image.png)
해당 레포지토리의 Settings 로 이동하여 아래로 쭉 스크롤을합니다. 
![](https://velog.velcdn.com/images/noyohanx/post/8fd010d4-a3d7-4eed-b2b8-6673a83e3e1f/image.png)
아래쪽으로 가게되면 위와 같이 `Delete this repository`가 보일텐데 `Delete this repository` 를 클릭하여 레포지토리를 삭제해줍니다.
![](https://velog.velcdn.com/images/noyohanx/post/0bbae16d-db9b-4916-a4e7-1465c4407b8a/image.png)
다시 본인의 Repositories로 가보면 Fork 한 레포지토리가 삭제된 것을 볼 수 있습니다.
