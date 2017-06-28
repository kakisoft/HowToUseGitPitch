### GitHubだけで作成できるスライド
　  

　  
　  
　　　　　垣花　暁
---
こんな感じのスライドが作れます。
---
「GitPitch」というサービスを使っています。
---
必要なのは、GitHubアカウントのみ。
---
作り方
---
リポジトリを作成  
<img src="img/01.png">
---
リポジトリ名がスライドのURLとなります。  
<img src="img/02.png"/>
---
「Create New File」を選択  　
<img src="img/03.png"/>
---
PITCHME.md  
というファイルを作成します。  
<img src="img/04.png"/>  
---
内容はマークダウンで記述します。
---
GitPitch独自の記法もあります。
---
### Fragment Slides
- 要素の先頭に```\- ```を並べ |
- 末尾に```\|``` を記述すると |
- １行単位で                |
- 表示することが            |
- できます                 |
---
```
---?gist=kakisoft/92d3fc38dae2eadc97f4a2881fbfc695
```
と記述することで、Gistも表示可能です。
---
Commit new fileで完了です。  
<img src="img/05.png"/>
---
URLは、   
　  
https://gitpitch.com/<ユーザ名>/<リポジトリ名>  
　   
となります。
---
ブランチを切って  
　  
https://gitpitch.com/<ユーザ名>/<リポジトリ名>/<ブランチ名>  
　  
とする事もできます。
---
公式サイト  
https://gitpitch.com/
---
おわり
