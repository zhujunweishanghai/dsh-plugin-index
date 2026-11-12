# DSH 插件索引

一份符合 DeepSeek Harness 插件市场索引格式 1 的 JSON 文件，供「插件页 → 发现」添加为索引源。

- 索引地址：`https://zhujunweishanghai.github.io/dsh-plugin-index/index.json`
- 收录插件均来自 GitHub 开源仓库，已逐个校验 `package.json` 中的 `dsh.bundle.patch` 与 npm 发布状态。
- 收录 ≠ 审计。插件是会在本机执行的代码，安装前请自行确认来源可信。

## 收录内容

| 插件 | 用途 |
|---|---|
| `dsh-blender-plugin` | 让智能体直接驱动 Blender 建模 |
| `dsh-plugin-blender-3d` | 基础几何体 / 布尔运算建模 |
| `dsh-better-sidebar` | 侧边栏增加文件、终端、Git 页面 |
| `dsh-plugin-wallpaper-engine` | 界面动态壁纸 |

## 更新

重新生成 `index.json` 后推送即可，Pages 会自动重建。
