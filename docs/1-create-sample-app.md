# 1. サンプル .NET アプリケーションの作成

この章では、 GitHub Copilot を使用する対象のサンプルコードを用意します。

## .NET Web アプリケーションの作成

下記コマンドを実行し、 .NET Web アプリケーションプロジェクトの作成と HelloController ファイルの追加、 Visual Studio Code の起動を行ってください。

### プロジェクト作成

下記コマンドで、新規プロジェクトを作成します。  
作成後、カレントディレクトリを移動しておきます。

```bash
dotnet new mvc -f net8.0 -n HolCopilotCSharp
cd HolCopilotCSharp
```

### API コントローラー作成

下記コマンドで、今回使用するサンプルクラス `HelloController` を追加します。

```bash
dotnet new apicontroller -o Controllers -n HelloController
```

### Visual Studio Code の起動

Visual Studio Code を起動します。

```bash
code .
```

以上で、今回使用するサンプルコードの準備が整いました。  
ここまでの手順が完了したら、次の章 [2. GitHub Copilot](./2-github-copilot.md) に進みます。

---

- 次： [2. GitHub Copilot](./2-github-copilot.md)
- TOP： [README.md](./../README.md)
