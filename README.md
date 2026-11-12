# game

游戏项目工作区。本仓库目前只包含工作区配置骨架，业务代码在此之上逐步添加。

## 目录约定

```
game/
├── README.md          # 项目说明（本文件）
├── .gitignore         # 忽略规则
├── .gitattributes     # 换行与二进制处理规则
├── .editorconfig      # 编辑器统一风格
└── (后续) src/ docs/ assets/
```

## 开发约定

- 主分支为 `main`，提交前先 `git pull --rebase`。
- 提交信息使用 `<type>(<scope>): <summary>` 形式，type 取 `feat` / `fix` / `docs` / `chore` / `refactor` / `test`。
- 二进制资源（美术、音频、字体）放入 `assets/`，交由 `.gitattributes` 按二进制处理，不进文本 diff。

## 起步

```bash
git clone https://github.com/guan-chengjun/game.git
cd game
```
