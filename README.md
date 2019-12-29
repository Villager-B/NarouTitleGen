# NarouTitleGen

Web小説(なろう)のタイトルをマルコフ連鎖を使用して自動生成するリポジトリ

てくてくぷれいす「markovifyを使ってマルコフ連鎖でなろう小説のタイトルを自動生成するぞ！」で紹介したプログラムをNotebook形式で用意しています．

`mkdir ndata`しなくてはいけないことに注意してください！

- Collect_Narou_Title.ipynb : APIを使用してなろうのタイトルを取得，各種オブジェクトで保存
- MarkovChain.ipynb : markovifyを使ってマルコフ連鎖のモデルを作成，タイトル自動生成
