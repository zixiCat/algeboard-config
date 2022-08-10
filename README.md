# ALGEBOARD 配置

## 使用 GitHub Actions 构建固件

### 准备工作

- Fork 该仓库或者点击使用该模板（会包含所有的 branch）
- 在你的 fork 中启用 GitHub Action，（如果已经开启，请跳过）

### 修改键盘映射

- 打开[键盘映射编辑页面](https://nickcoutsos.github.io/keymap-editor/) ，Source 选择 GitHub，然后登录，授权上一步 fork 的仓库。
- 点击页面中每个 key，即可进行修改。完整的键值可以参考 ZMK 给的[列表](https://zmk.dev/docs/codes)
- 修改完成后，点击页面右下方的 commit change 按钮变更，几分钟构建完成后，点击下方的 firmware 链接进入 GitHub 下载 firmware。
- 如果需要添加自定义层，可以参考[层的文档](https://zmk.dev/docs/behaviors/layers)

