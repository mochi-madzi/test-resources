# 📦 資材置き場

## テンプレート

| ファイル | 説明 |
|---|---|
| [見積書_雛形.xlsx](./templates/見積書_雛形.xlsx) | 顧客向け見積書 |
| [議事録_雛形.docx](./templates/議事録_雛形.docx) | 打ち合わせ用 |

## スニペット

### Azure CLI よく使うコマンド

```bash
# リソースグループ一覧
az group list --output table

# VMの起動・停止
az vm start --resource-group <RG名> --name <VM名>
az vm deallocate --resource-group <RG名> --name <VM名>
```

### PowerShell

```powershell
# ディスク使用量確認
Get-PSDrive -PSProvider FileSystem
```

## メモ

- Box管理コンソール: https://app.box.com/master
- Azure Portal: https://portal.azure.com

## 更新履歴

| 日付 | 内容 |
|---|---|
| 2026-03-27 | 初回作成 |
