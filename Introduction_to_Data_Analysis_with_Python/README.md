# 書籍「Pythonによるデータ分析入」の学習用リポジトリ
## 環境構築
VSCodeで開発することでGitHub Copilotを利用できるようにする。
```powershell
docker pull jupyter/scipy-notebook

docker run -p 8888:8888 --rm --name jupyter-notebook -v ${PWD}/work:/home/jovyan/work jupyter/scipy-notebook
```
VSCodeからJupyter Notebookを開く
```powershell
code --remote "http://127.0.0.1:8888/lab?token=a28cb931156c73bf35a19a20617115a0fb11c78cfcce7ea1"
```
## 
