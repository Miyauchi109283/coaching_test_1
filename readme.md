# Java-coaching_test_1
SpringBootコース フレームワークテスト1

## clone時の注意点
clone時は、Eclipseのワークスペースとなっているディレクトリにて、以下のコマンドを利用し、ローカルリポジトリの名称が `coaching_test_1` になるようにしてください。

```git
git clone https://github.com/SLStudioGithub/CoachingTest-SpringBoot-FWTest01.git coaching_test_1
```
クローンが完了したら、プロジェクトに移動しておきましょう。
```
cd coaching_test_1
```

## 連携リポジトリの切り替え
clone後、解答提出用にご自身で作成していただいたリポジトリに連携を行っていただく必要があります。

1. GitHubに新しいプロジェクトを作成
    - プロジェクト名は `coaching_test_1` とし、private なリポジトリとして作成しましょう
    - コーチング担当者をプロジェクトのCollaboratorに追加してください  
2. cloneしたプロジェクトの連携先を変更
    - GitBashにて以下のコマンドを実行してください
    ```
    git remote set-url origin 新しいリポジトリのURL
    
    // 連携中のリポジトリ情報の確認（表示される内容が自分で作ったリポジトリになっていればOKです）
    git remote -v
    ```
    - 作業前に一度pushしておき、提出用リポジトリに反映されることを確かめておきましょう
    - この時、commitなどは不要、コマンド実行後にブラウザをリロードしてソースが反映されていればOKです
    ```
    git push
    ```
    
## Eclipseへのインポート
cloneしてきたプロジェクトのインポートを行います。
Eclipseにて以下の操作を行いましょう。

1. `ファイル` をクリック
2. メニューの中から`インポート` をクリック
3. Gradle > 既存のGladleプロジェクト を選択し `次へ` をクリック
4. プロジェクト・ルート・ディレクトリー の欄にcloneしてきたプロジェクトのパスを設定（参照 を利用すると良い）
5. `完了` をクリック
