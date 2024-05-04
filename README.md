# Flutter Docker Project

このプロジェクトは、Flutter開発環境をDockerを使用して簡単に構築することを目的としています。

## 概要

このプロジェクトでは、以下のツールを含むFlutter開発環境を提供します：

- Flutter SDK
- Visual Studio Code
- Android Studio
- IntelliJ IDEA

Dockerコンテナ内でこれらのツールを実行することで、環境構築の手間を省き、開発者がすぐにFlutterアプリケーションの開発を始めることができます。

## インストールと使用方法

1. このリポジトリをクローンします：

    ```
    git clone https://github.com/MaylayExec/Flutter_container.git
    ```

2. クローンしたディレクトリに移動します：

    ```
    cd Flutter-container
    ```

3. Dockerを使用して環境をビルドします：

    ```
    make build
    ```

4. 次のコマンドを実行して、Flutter開発環境のコンテナを起動します：

    ```
    make run
    ```

5. コンテナが起動したら、選択したIDEを起動してFlutterプロジェクトを作成または開きます：

    - Visual Studio Code:

        ```
        code .
        ```

    - Android Studio:

        ```
        studio.sh .
        ```

    - IntelliJ IDEA:

        ```
        idea .
        ```

6. 開発を開始します！

## ライセンス

[MIT ライセンス](LICENSE) の下でリリースされています。

## 貢献

バグの報告や改善提案など、どんな形でも貢献を歓迎します。プルリクエストも大歓迎です！
