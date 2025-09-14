# shorinGitLearingExperience
学一学git的用法

## 简单来说

设置用户

git clone <repo>

git add 文件名或者 . 点代表全部文件

git commit -m “这里是和修改相关的note”

git push 更新git上的repo

## 设置用户

  git config --global user.email "you@example.com"

  git config --global user.name "Your Name"

如果仅在本仓库设置身份标识，则省略 --global 参数。

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
