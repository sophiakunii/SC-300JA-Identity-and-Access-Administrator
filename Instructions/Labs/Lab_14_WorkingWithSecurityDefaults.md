---
lab:
    title: '14 - セキュリティの規定値群を使用する'
    learning path: '02'
    module: 'モジュール 03 -条件付きアクセスの計画、実装、管理を行う'
---

# ラボ 14 - セキュリティの規定値群を使用する

## ラボ シナリオ

組織で Azure Active Directory のセキュリティの規定値群の設定を構成する必要があります。

#### 推定時間: 5 分

## セキュリティの既定値群を有効化する

ディレクトリでセキュリティの既定値群を有効にする方法:

1. ディレクトリのグローバル管理者アカウントを使用して [https://portal.azure.com](https://portal.azure.com) を参照し、サインインします。

1. **「ポータル メニューの表示」** ハンバーガー アイコンを選択し、**「Azure Active Directory」** を選択します。

    ![「Azure Active Directory」 が選択された Azure portal メニュー](./media/azure-portal-menu-aad.png)

1. 左側のナビゲーションの「管理」セクションで **「プロパティ」** を選択します。

1. 「プロパティ」ブレードの下部にある **「Manage Security defaults」** (セキュリティの既定値群の管理) を選択します。

1. **「セキュリティの既定値群を有効にする」** トグルを **「はい」** に設定します。

1. これは、既に有効になっている可能性があります。

1. **「保存」** を選択します。

### セキュリティの既定値群を無効にする

セキュリティの既定値群を置き換える条件付きアクセス ポリシーを実装する組織では、セキュリティの既定値群を無効にする必要があります。

ディレクトリでセキュリティの既定値群を無効にする方法:

1. ディレクトリのグローバル管理者アカウントを使用して [https://portal.azure.com](https://portal.azure.com/) を参照し、サインインします。

1. **「ポータル メニューの表示」** ハンバーガー アイコンを選択し、**「Azure Active Directory」** を選択します。

1. 「プロパティ」ブレードの下部にある **「Manage Security defaults」** (セキュリティの既定値群の管理) を選択します。

1. **「セキュリティの既定値群を有効にする」** トグルを **「いいえ」** に設定します。

    ![無効になっているセキュリティの既定値群と、無効にするために必要な理由が選択されている画面イメージ。このケースでは、組織は条件付きアクセスを使用しています。](./media/security-defaults-disable-before-conditional-access.png)

1. **「保存」** を選択します。
