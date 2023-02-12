# stable-diffusion-webui
[![GitHub Repo stars](https://img.shields.io/github/stars/AUTOMATIC1111/stable-diffusion-webui?style=social)](https://github.com/AUTOMATIC1111/stable-diffusion-webui)    
現在のStable Diffusionをローカルで利用する際のツールで、もっともStar数が多いリポジトリ。  
Gradioというフレームワークを使用しているためUIには多少難があるが、情報が多い。


## インストール
1. [GitHubのリリース](https://github.com/AUTOMATIC1111/stable-diffusion-webui/releases/latest)から最新のものをダウンロードする。  
![](./iamges/assets.png)
2. ダウンロードしてきたファイルを展開する。  
![](./iamges/extract.png)
この段階ですでに使いたいドライブがある場合はフォルダごと移動させる。  
展開したあとに、このようなファイル構成になっていれば大丈夫です。  
![](./iamges/folder.png)
3. `environment.bat`というファイルがあるので実行する。  
このファイルの実行が終えた時点ですでに環境が整っています。
4. `run.bat`を実行します。  
時間がかかるので少し待ちましょう
5. `Running on local URL: http://127.0.0.1:7860`のような表示が現れたら実行完了です。
![](./iamges/access.png)  
[このURL](http://127.0.0.1:7860)をクリックするとアクセスできます。


## アップデート
1日1回どころか、**数分に1回**の頻度でアップデートが入ることがあります。  
しかし、毎回のようにアップデートをしていると致命的なバグを引き当ててしまいます。  
慣れている方や、開発者などリスクを理解している方以外はあまりオススメしません。  
入門者の方や怖いという方は、2週間に1回程度。  
あるいは周りの知っている方に安定してるかどうかを聞いてから行うとよいでしょう。  

1. `run.bat`や`enviroment.bat`が含まれるフォルダへ移動します。
2. `update.bat`を実行します。
3. アップデートが完了すると、`続行するには何かキーを押してください...`という表示が出ます。
![](./iamges/update.png)
4. 適当なキーを押すとアップデートが終了し、黒い画面が閉じます。
5. そのまま`run.bat`を実行すると、アップデートが完了した状態で起動します。


## 好きなモデルを使用する
stable-diffusion-webuiでは自分の好きなモデルを使用することができます。
好みに応じてモデルを使い分けるようにしましょう。

1. 好きなモデルを入手します。  
モデルの有名な配布場所としては、[HuggingFace](https://huggingface.co/)や、[CivitAI](https://civitai.com/)があります。  
今回は例として、Stable-Diffusion 2.1を使用します。
2. [Stable-Diffusion 2.1](https://huggingface.co/stabilityai/stable-diffusion-2-1/tree/main)にアクセスします。
3. 
4. 