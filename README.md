# DPmatching
DPマッチングで小規模の単語音声認識を行う。
用意するデータファイルcity_mcepdataは、音声入力→音響分析までの過程がすでに完了している。
データファイルはリポジトリに上げないので、自分のデータを使用してください。

### このプログラムについて

講義で作成しましたものをgithubに上げました。音声入力→音響分析までの過程がすでに完了しているデータファイルを用いて、
100語のテンプレートに対して、同じ発生内容の100単語(同一話者または別話者)を道音声と見立てて入力しとき、
何単語が正しく認識できるかを調べるプログラムです。  
DPマッチングの参考にしてください。  

### 出力結果
cygwin上で実行しました。  
誤認識したものだけ詳細を出力しています。
結果は、以下のように画面上に出力されました。  
![DPmatching_result.JPG](DPmatching_result.JPG)  

正解率は[output001.txt](output001.txt)にも別途でファイル出力されています。

