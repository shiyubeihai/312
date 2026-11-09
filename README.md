# 312核心 · PWA 部署说明（GitHub Pages）

## 一、上传

1. 打开 GitHub，新建仓库（Repository），名字建议 `312-core`，选 **Public**。
2. 进入仓库，点 **Add file → Upload files**。
3. 把本文件夹里的**全部内容**拖进去（`index.html` 必须在仓库根目录，不要多套一层文件夹）。
4. 点 **Commit changes**。

> 也可以直接把 `312核心-PWA.zip` 解压后，拖入解压出的文件。

## 二、开启 Pages

1. 仓库页 → **Settings** → 左侧 **Pages**。
2. **Source** 选 `Deploy from a branch`。
3. **Branch** 选 `main`，目录选 `/ (root)`，点 **Save**。
4. 等 1–2 分钟，页面上会出现网址：
   `https://你的用户名.github.io/312-core/`

## 三、装到手机

1. 手机 Chrome 打开上面的网址。
2. 右上角 ⋮ → **安装应用 / 添加到主屏幕**。
3. 桌面出现「312核心」图标，全屏打开，离线可用。

iPhone：Safari 打开同一网址 → 分享 → **添加到主屏幕**。

## 四、更新内容

改完 `index.html` 后，把 `sw.js` 第一行的 `core312-v1` 改成 `core312-v2`
（每次更新都加一），再上传覆盖，否则手机可能还在用旧缓存。

## 五、常见问题

- **没有“安装应用”选项**：确认网址是 `https://` 开头；GitHub Pages 自带 https。
- **打开是空白**：确认 `index.html` 在仓库根目录，不是 `312-core/index.html` 这种多一层。
- **进度丢失**：进度存在浏览器本地，换浏览器或清缓存会丢；同一个图标长期用即可。
