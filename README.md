# 🐾 帆波 (Fanbo)

Codex 桌面宠物 — 穿酒红学院制服的粉色长发动漫少女。

## 安装方法

将本仓库内容克隆到 Codex 宠物目录即可：

```bash
# 确保 ~/.codex/pets 目录存在
mkdir -p ~/.codex/pets

# 克隆宠物文件
git clone https://github.com/Izumi-iii/fanbo-pet.git ~/.codex/pets/pink-academy
```

重启 Codex 后即可在宠物列表中看到帆波。

## 文件说明

| 文件 | 说明 |
|------|------|
| `pet.json` | 宠物配置（ID、描述、精灵图路径） |
| `spritesheet.webp` | 动画精灵图 |

## 卸载

```bash
rm -rf ~/.codex/pets/pink-academy
```
