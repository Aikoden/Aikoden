### Hi, I'm Aikoden 👋

医用画像 × AI のツールと、LLM を使った学習アプリを作っています。
セグメンテーションモデルの推論、計測アルゴリズム、LLM パイプライン、デスクトップ／Web アプリ化、クラウドへのデプロイまで、一通り自分で手を動かしています。

#### 📌 Projects

**[NWI Semi-Auto](https://github.com/Aikoden/NWI-Semi-Auto)** — 半自動 NWI 計測ツール
膝関節X線画像で、AI が大腿骨の輪郭とベースラインを提示し、ノッチ幅は自分で引く計測ツール。

▶ **[Web デモ](https://lydrem6fylfjzygah4n2tzb3qi0oaddm.lambda-url.ap-northeast-1.on.aws/)**（インストール不要・ブラウザでそのまま試せます）

| | 使用技術 |
|---|---|
| デスクトップ版 | Python, PySide6, ONNX Runtime, OpenCV |
| Web 版 | FastAPI, JavaScript (Canvas), Docker, AWS Lambda / ECR / CloudWatch |

**[Coding Tutor Lab](https://github.com/Aikoden/coding-tutor-lab)** — 中日英の解説つき Python・データサイエンス練習アプリ
DS-1000 の実戦問題 794 問を、ブラウザ上の Python（Pyodide）で実行・採点します。中日英のレッスンは LangGraph のパイプラインで生成し、実行による検証と自動レビューを通ったものだけを採用しています。

▶ **[オンラインデモ](https://aikoden.github.io/coding-tutor-lab/)**（インストール不要・コードはブラウザ内で実行）

| | 使用技術 |
|---|---|
| フロントエンド | React, TypeScript, Monaco Editor, Pyodide (WebAssembly) |
| バックエンド・LLM | FastAPI, SQLite, LangChain, LangGraph, Gemini / Ollama / Amazon Bedrock |
| テスト・公開 | pytest, Playwright, GitHub Actions, GitHub Pages |

#### 🛠 Skills

Python · PyTorch（セグメンテーション・物体検出） · ONNX Runtime · OpenCV · FastAPI · LangChain / LangGraph · TypeScript / React · JavaScript · Docker · AWS · GitHub Actions · Git

---

I build AI tools for medical imaging and LLM-powered learning apps — from model inference, measurement algorithms and LLM pipelines to desktop/web apps and cloud deployment.
