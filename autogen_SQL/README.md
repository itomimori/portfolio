# SQL 生成 AI アシスタント

このプロジェクトは、テーブルスキーマ情報と自然言語による質問をもとに、適切な SQL クエリを自動生成する AI アシスタントです。Gradio によるチャット UI を通じて、誰でも簡単に SQL を生成できます。

## 🔧 主な機能

- `.md` や `.xlsx` ファイルからスキーマ情報を読み込み
- LangChain + OpenAI API による SQL クエリ生成
- Gradio UI によるインタラクティブなチャット体験
- スキーマに基づいた JOIN 句の自動挿入
- 会話履歴に基づく文脈理解（※今後拡張予定）

## 🚀 実行方法

1. 必要なライブラリをインストール：

```bash
pip install -r requirements.txt

2. env ファイルを作成し、OpenAI APIキーを設定：

OPENAI_API_KEY=your-api-key

3.　スキーマファイルを databaseフォルダ内に配置

🧠 使用技術

- LangChain
- OpenAI GPT-4o
- Gradio
- Chroma Vector Store
- dotenv / pandas / markdown / Excel読み込み対応

簡単な指示
![alt text](image-1.png)
言語による指示
![alt text](image-2.png)
ミスタイピングを含むもの
![alt text](image-3.png)

```
