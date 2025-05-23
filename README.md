# Delta Lake ハンズオン

このリポジトリでは、Delta Lake の基本機能（ACIDトランザクション、スキーマエボリューション、タイムトラベル）をローカル環境で体験する。

## セットアップ手順

```bash
python -m venv venv
source venv/bin/activate  # Windowsの方は venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## 実行内容

- デルタテーブルの作成と読み取り
- ACIDな更新・削除操作
- スキーマエボリューション（列の追加）
- タイムトラベル（バージョンによる読み出し）
