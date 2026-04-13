# test20260331

FastAPI を使用したシンプルな Web API プロジェクトです。

## プロジェクト構成

```
src/
  main.py          # FastAPI アプリケーション本体
tests/
  test_main.py     # テストコード
requirements.txt   # 依存パッケージ一覧
```

## 機能

- `GET /` — `{"message": "Hello World"}` を返すルートエンドポイント

## 必要条件

- Python 3

## セットアップ

依存パッケージをインストールします。

```bash
pip install -r requirements.txt
```

## 実行方法

Uvicorn を使用してアプリケーションを起動します。

```bash
uvicorn src.main:app --reload
```

起動後、http://127.0.0.1:8000 でアクセスできます。

## テストの実行

pytest を使用してテストを実行します。

```bash
pytest
```
