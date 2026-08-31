# Linkworld Skill 市场

Linkworld 内部 WorkBuddy 技能库。**每个技能一个独立仓库**，往下选技能，复制安装指令（或 clone）即可用。

## 怎么用

1. 在下表找到需要的技能；
2. 复制「安装指令」粘贴给 WorkBuddy（或 clone 对应仓库到 `~/.workbuddy/skills/`）；
3. 重开对话即可用。

## 技能列表

| 技能 | 干什么 | 仓库 |
|---|---|---|
| 达摩盘画像爬取 | 达摩盘人群画像分布爬取，导出 Excel | [linkworld-skill-dmp-portrait](https://gitee.com/liwell_yang/linkworld-skill-dmp-portrait) |
| 生意参谋市场排行爬取 | 生意参谋商品榜爬取，导出 Excel | [linkworld-skill-sycm-rank](https://gitee.com/liwell_yang/linkworld-skill-sycm-rank) |

## 安装指令（直接复制粘贴给 WorkBuddy）

**达摩盘画像爬取**
```
帮我把这个 skill 装到我的 WorkBuddy：https://gitee.com/liwell_yang/linkworld-skill-dmp-portrait
```

**生意参谋市场排行爬取**
```
帮我把这个 skill 装到我的 WorkBuddy：https://gitee.com/liwell_yang/linkworld-skill-sycm-rank
```

## 维护者：怎么新增一个技能

1. 在 Gitee 建一个独立仓库（命名 `linkworld-skill-<名字>`，公开）；
2. 仓库根目录放 `SKILL.md`（+ 可选 `app/` 代码）；
3. 在上方「技能列表」加一行 + 加一条安装指令；
4. 完成。

## 说明

- 仓库均为公开。如有涉及内部账号/接口/业务逻辑的敏感技能，请改用私有仓库或内网 GitLab。
