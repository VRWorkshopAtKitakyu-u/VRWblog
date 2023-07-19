# VRWblog
北九大VR勉強会の公式サイト    
[ここ](https://vrworkshopatkitakyu-u.github.io/VRWblog/)  

静的サイトジェネレーターの[Hugo](https://gohugo.io/)を使用  

## Hugoの簡単な使い方  
インストール(windows)[公式解説](https://gohugo.io/installation/windows/)  
Go言語をインストール: winget install GoLang.Go  
Hugoをインストール: winget install Hugo.Hugo.Extended  

新規記事の作成  
hugo new post/カテゴリ名/記事名.md (半角英数字のみ使うこと)  

ビルド  
hugo  

デバッグ  
hugo server -D  
## テーマの使い方  
テーマはReyoKatsu作のRush Constructionを使用  

### 画像挿入関数: imgin  
使い方  
{{% imgin "画像のパス(media以下)" "サイズ(%表記)" "キャプション。無くてもいい" %}}  
使用例  
{{% imgin "/post/vrw.png" "30" "このサイトのファビコン" %}}  

### 警告関数: warn
使い方  
{{% warn %}}  