# Peace for KAITO
#KAITOで揉めている界隈を技術で平和にしたい  

## コンテクスト

「タチ悪すぎ」の声も…高橋海人「KAITO」名義でデビュー、同名ボカロ界隈が大荒れ　炎上加速の発言:   
https://news.yahoo.co.jp/articles/dba47f8b6881e5db6fb5b22ce50fe77fb9568091

## 取り組み1: uBlock Origin用フィルター
ハッシュタグで揉めている主な原因は、それぞれのハッシュタグに対する考え方の違いがあると思われます。  
King & Princeのファンはハッシュタグを多く使うことでトレンドに載せることを目的としているのに対し、ボカロ界隈ではハッシュタグを使って他のファンを探したり、作品を見つける目的で使っているとされています。

そこで、#KAITOのハッシュタグをつけた投稿からそれぞれの界隈の投稿を減らすためのフィルターを作成しました。  
自界隈でないと思われる投稿を非表示にすることで、棲み分けとして機能するのではないかと考えています。

### 使い方

1. uBlock Originをインストールする
2. 下のフィルターリストから使いたいフィルターを選ぶ
3. 「インストール」リンクを開く
4. uBlock Originが自動で認識し、内容の確認画面とともに「購読」ボタンが表示されるので、クリックする

#### uBlock Originのインストール
- FireFox系ブラウザ: [uBlock Origin - Add-ons for Firefox](https://addons.mozilla.org/ja/firefox/addon/ublock-origin/)
- Edge: [uBlock Origin - Microsoft Edge Addons](https://microsoftedge.microsoft.com/addons/detail/ublock-origin/odfafepnkmbhccpbejgmiehpchacaeak)
- Opera: [uBlock Origin - Opera add-ons](https://addons.opera.com/ja/extensions/details/ublock/)
- 手動インストール: [uBlock Origin - GitHub](https://github.com/gorhill/uBlock)

Google Chromeでは、uBlock Originが必要とするManifest V2がサポートされなくなったため、uBlock Originをインストールできません。Vivaldi等のChromium系ブラウザでも将来的に同様の状況になる可能性があります。  
以前まではChromeウェブストアからuBlock Originをインストールできましたが、2026年8月をもってGoogleはManifest V2拡張機能をストアから削除しました。現在、独自のストアを持たずChromeウェブストアに依存するChromiumブラウザでuBlock Originをインストールするには、GitHubから手動でインストールする必要があります。
  
##### Androidの場合
Androidで拡張機能をサポートしたブラウザはあまり多くありません。FireFox系ブラウザであればほとんどの場合拡張機能をサポートしていますが、個人的には以下のChromium系ブラウザを推奨します:
- [Titanium Browser](https://play.google.com/store/apps/details?id=io.github.jqssun.helium)
- [Bare Browser](https://github.com/BareBrowser/bare-browser)
- [Vivaldi Browser](https://play.google.com/store/apps/details?id=com.vivaldi.browser)

Titanium BrowserはManifest V2をサポートしており、uBlock Originをインストールできます。Playストアから更新できます。  
Bare BrowserはManifest V2をサポートしており、uBlock Originが組み込まれています。ストアにないためObtanium等を使用してGitHubからインストールしてください。  
Vivaldi Browserでも裏技的にuBlock Originを動かせます。ブラウザ自体が優秀であるため推奨リストに入れていますが、いつまで使えるかは不明で、近いうちにManifest V2サポートを終了するはずです。

Bare Browserの紹介記事: https://note.com/appgrove/n/nc20fecb20159  
VivaldiでuBlock Originを使う方法: https://note.com/appgrove/n/nbd987e64136b


### Hide #KAITO from King & Prince Fans for Peace
VOCALOID界隈向けのフィルターです。

#KAITOを含む投稿のうち、King & Princeのファンが投稿したと思われる投稿を非表示にします。

[インストール](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fraw.githubusercontent.com%2Fdaizu-007%2FPeace-for-KAITO%2Frefs%2Fheads%2Fmain%2Ffilter%2Fhide-kinpuri.txt\&title=Hide%20KAITO%20from%20King%20and%20Prince%20Fans%20for%20Peace)

```
https://raw.githubusercontent.com/daizu-007/Peace-for-KAITO/refs/heads/main/filter/hide-kinpuri.txt
```

### Hide #KAITO from VOCALOID Fans for Peace
King & Prince界隈向けのフィルターです。

#KAITOを含む投稿のうち、VOCALOIDのファンが投稿したと思われる投稿を非表示にします。

[インストール](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fraw.githubusercontent.com%2Fdaizu-007%2FPeace-for-KAITO%2Frefs%2Fheads%2Fmain%2Ffilter%2Fhide-vocaloid.txt\&title=Hide%20KAITO%20from%20VOCALOID%20Fans%20for%20Peace)

```
https://raw.githubusercontent.com/daizu-007/Peace-for-KAITO/refs/heads/main/filter/hide-vocaloid.txt
```

### Hide unpleasant Arguments about KAITO from Twitter
#KAITOに関する議論を非表示にするフィルターです。

#KAITOを含まない投稿も対象にします。

[インストール](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fraw.githubusercontent.com%2Fdaizu-007%2FPeace-for-KAITO%2Frefs%2Fheads%2Fmain%2Ffilter%2Fhide-argument.txt\&title=Hide%20unpleasant%20Arguments%20about%20KAITO%20from%20Twitter)

```
https://raw.githubusercontent.com/daizu-007/Peace-for-KAITO/refs/heads/main/filter/hide-argument.txt
```
