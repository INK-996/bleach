# 死神（BLEACH）角色图床资源包

生成时间：2026-11-26T13:45:31.380Z
收录角色：106 位

## 目录结构

- `avatar/<UID>.webp`：256×256 正方形头像（106 张，共 1.00 MB）
- `portrait/<UID>.webp`：日常立绘 WebP（106 张，共 6.13 MB）
- `battle/<UID>.webp`：战斗/解放姿态 WebP（106 张，共 9.02 MB）
- `manifest.json`：全角色 UID、姓名、分组与裁切元数据索引

总计：318 个 WebP 文件，约 16.16 MB。

## 推送到 GitHub 图床仓库

1. 在 GitHub 新建一个 **Public** 仓库（例如 `bleach-assets`）。
2. 将本目录下的 `avatar/`、`portrait/`、`battle/`、`manifest.json`（可选 `README.md`）推至 `main` 分支根目录。
3. 可用访问基准前缀（替换 `<user>` 与 `<repo>`）：
   - GitHub Pages（推荐）：`https://<user>.github.io/<repo>`
   - Fastly jsDelivr：`https://fastly.jsdelivr.net/gh/<user>/<repo>@main`
   - jsDelivr CDN：`https://cdn.jsdelivr.net/gh/<user>/<repo>@main`
   - Raw 直连：`https://raw.githubusercontent.com/<user>/<repo>/main`
