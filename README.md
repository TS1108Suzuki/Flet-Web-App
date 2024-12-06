# Dev Containers を使用した Flet(Web) アプリケーションの環境構築

このリポジトリでは、**VS Code**の拡張機能 **Dev Containers** と **Docker** を使用して、**Flet(Web)アプリケーション**の開発環境を簡単に構築できます。これにより、プロジェクトメンバー全員が同じ環境で効率的に開発を進めることが可能です。

---

## 必要な環境

以下がインストールされている必要があります。

-   **VS Code**: [ダウンロードとインストール](https://code.visualstudio.com/)
-   **Docker Desktop**: [ダウンロードとインストール](https://www.docker.com/products/docker-desktop)

---

## VS Code に拡張機能を追加

1. **Remote Development 拡張機能パックをインストール**  
   Remote Development 拡張機能には、Dev Containers 機能が含まれています。以下のリンクからインストールしてください。  
   [Remote Development 拡張機能パックを追加](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

---

## 仮想環境の起動方法

### 方法 1: VS Code でプロジェクトフォルダを開く

1. **プロジェクトを開く**  
   VS Code でこのリポジトリを開きます。

2. **コンテナを開く**  
   右下にポップアップが表示されるので、「Reopen in Container」（コンテナで再オープン）を選択します。

3. **ビルド・起動した仮想環境の確認**  
   ターミナルで以下を実行し、Python パッケージがインストールされていることを確認します。
    ```bash
    pip list
    ```
