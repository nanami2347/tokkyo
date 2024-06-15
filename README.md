元データからインストラクションデータを作成し、Loraを用いてllama2のファインチューニングを行うプログラムです。
こちらは何か解決したい問題がありllama2に投げたとき、特許を持つ技術を含めたより専門的な解決手段が返ってくるように学習されてます。
まず、zipファイルに入れた特許情報をtokkyo.ipyneのコードにより解決手段を学ぶ上で重要な、“解決したい問題”と”解決手段”のみを抜き出します。そのデータをjsonファイルに変換し、study.ipyneのコードでllama2に学習してもらいます。
こちらはGoogleドライブのMydriveに元データを入れることで使用できます。