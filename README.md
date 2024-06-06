# rails_devcontainer
 
## 使い方

### 1. リポジトリのクローン  

wslで適当なリポジトリを作って、その中で以下のコマンドを実行する。

```bash
git clone https://github.com/WNomunomu/rails_devcontainer.git
cd rails_devcontainer
rm -rf .git # gitの追跡から外れるため
code . # VSCodeを開く
```

### 2. devcontainerの起動
VSCodeでリポジトリからcloneしたディレクトリを開いたら、`Dev Containers: Open Folder in Container`でrails_devcontainerディレクトリを開く。

しばらくするとdevcontainerが起動し始める。

### 3. railsアプリの作成

以下のコマンドを実行して、rubyとrailsがコンテナ内にインストールされていることを確認する。
```bash
ruby -v
rails -v
```

以下のコマンドの *app_name* を自分の好きな名前にして、実行。

```bash
rails new <app_name>
```

無事railsアプリが作成されれば成功です。


