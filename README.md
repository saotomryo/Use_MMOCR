# MMOCRを利用して、AI OCRモデルを作る時のサンプルコード集です。

基本的には、学習用のデータのパスを指定するだけで、OCR用のAIモデルが作成できるようにしていこうと思います。  

文字列認識モデル
- seg_r31_1by16_fpnocr_toy_dataset.py
  →基本的には英数字のみ

- sar_r31_parallel_decoder_chinese.py
  → 基本的には中国語用のモデルですが、辞書を作成することで日本語や他の言語、記号などに応用可能

