# getnote2obsidian 安装说明

这个文件夹用于分享 Obsidian 插件。

## 里面有什么

需要复制给别人的插件文件夹是：

```text
getnote-obsidian-sync
```

这个文件夹里包含 Obsidian 运行插件必需的 3 个文件：

```text
manifest.json
main.js
styles.css
```

## 安装方法

1. 关闭 Obsidian，或先不要启用插件。
2. 打开对方的 Obsidian Vault 文件夹。
3. 进入隐藏目录：

```text
.obsidian/plugins
```

如果没有 `plugins` 文件夹，就手动创建。

4. 把整个插件文件夹复制进去：

```text
getnote-obsidian-sync
```

最终目录应该是：

```text
你的Vault/.obsidian/plugins/getnote-obsidian-sync/manifest.json
你的Vault/.obsidian/plugins/getnote-obsidian-sync/main.js
你的Vault/.obsidian/plugins/getnote-obsidian-sync/styles.css
```

5. 打开 Obsidian。
6. 进入「设置」->「第三方插件」。
7. 如果还没开启，先关闭「安全模式」或允许第三方插件。
8. 找到插件 `getnote2obsidian`，点击启用。
9. 进入插件设置，填写 GetNote API Key 和 Client ID。

## 注意

- 必须复制整个 `getnote-obsidian-sync` 文件夹，不是只复制里面的文件到 `plugins` 根目录。
- 文件夹名建议保持 `getnote-obsidian-sync`，因为它和插件 ID 一致。
- 插件显示名称是 `getnote2obsidian`。
- 每个人都需要填写自己的 GetNote API Key 和 Client ID。
- 不要分享自己的 `.obsidian/plugins/getnote-obsidian-sync/data.json`，里面可能有个人 API Key。
