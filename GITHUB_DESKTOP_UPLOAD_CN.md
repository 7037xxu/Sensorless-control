# 使用 GitHub Desktop 上传项目页

网页上传器会在一次提交包含多个较大视频时失败。GitHub Desktop 可以直接通过 Git 推送；普通 Git 仓库要求每个文件小于 100 MB。

## 第一次使用

1. 打开 GitHub Desktop，登录账号 `7037xxu`。
2. 选择 `File > Clone repository`。
3. 在 `GitHub.com` 列表中选择 `7037xxu/Sensorless-control`。
4. 选择本地保存位置，然后点击 `Clone`。
5. 在文件资源管理器中打开本项目包 `Sensorless-control` 文件夹。
6. 将本项目包里面的所有文件和文件夹复制到 GitHub Desktop 刚克隆的 `Sensorless-control` 文件夹，选择覆盖同名文件。
7. 回到 GitHub Desktop。左下角 Summary 填写 `Update project page and add experiment videos`。
8. 点击 `Commit to main`。
9. 点击顶部 `Push origin`。

推送结束后等待 GitHub Pages 部署，再刷新：

`https://7037xxu.github.io/Sensorless-control/`

## 视频路径

四个视频已经放在：

`assets/videos/`

页面使用以下固定文件名：

- `test-bench.mp4`
- `10rpm.mp4`
- `1500rpm.mp4`
- `sinusoidal-tracking.mp4`
