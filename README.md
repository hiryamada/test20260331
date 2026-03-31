# test20260331

Python（FastAPI）で構築されたシンプルな Web API アプリケーションです。

## 機能

- `GET /` — `{"message": "Hello World"}` を返すルートエンドポイント

## 必要な環境

- Python 3.8+

## セットアップ

依存パッケージをインストールします。

```bash
pip install -r requirements.txt
```

## サーバーの起動

uvicorn を使用してアプリケーションを起動します。

```bash
uvicorn src.main:app --reload
```

起動後、ブラウザで http://127.0.0.1:8000 にアクセスするとレスポンスを確認できます。
FastAPI が自動生成する API ドキュメントは http://127.0.0.1:8000/docs で確認できます。

## テストの実行

pytest を使用してテストを実行します。

```bash
pytest
```
