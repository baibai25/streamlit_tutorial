# streamlit_tutorial
ラボ勉強会用

## How to use
### Streamlit
- Notebookを実行し、app.pyを作成
- `streamlit run app.py `

### ngrok
- .envrcを作成
  - `NGROK_TOKEN="YOUR ngrok TOKEN"`

```
$ ngrok authtoken $NGROK_TOKEN
$ streamlit run app.py
$ ngrok http PORT_NUMBER
```

### Streamlit Community Cloud
- リポジトリ直下にapp.pyとrequirements.txtを作成
- 公式の手順通りに進めるだけ
  - https://streamlit.io/cloud
- 構成例
  - https://github.com/baibai25/patoyata-gacha
