# shorinGitLearingExperience
学一学git的用法



## git clone自己的私人repo

github点击右上角的头像，选择 **Settings** (设置)。

在左侧菜单滚动到底部，选择 **Developer settings** (开发者设置)。

选择 **Personal access tokens** -> **Tokens (classic)**。

点击 **Generate new token** -> **Generate new token (classic)**。

**配置令牌**:

- **Note (备注)**: 给它起一个能识别的名字，比如 `Arch KDE Desktop`。
- **Expiration (有效期)**: 强烈建议设置一个有效期，比如 30 天或 90 天。
- **Select scopes (选择权限)**: 这是最关键的一步。对于克隆、拉取、推送仓库等日常操作，您只需要勾选 **`repo`** 这一个大项就足够了。它包含了所有对仓库进行操作的权限。

滚动到底部，点击 **Generate token**。
