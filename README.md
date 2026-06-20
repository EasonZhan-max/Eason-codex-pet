# Eason Codex 桌宠

这是一个可以在 Codex 里使用的自定义桌宠：Eason。

## 文件说明

桌宠文件在 `eason/` 文件夹里：

- `eason/pet.json`
- `eason/spritesheet.webp`

## 安装方法

### 方法一：一键安装

下载本仓库后，在当前文件夹里运行：

```powershell
powershell -ExecutionPolicy Bypass -File .\install.ps1
```

然后重启 Codex，或者在 Codex 里切换一次桌宠，选择 `Eason`。

### 方法二：手动安装

把 `eason` 文件夹复制到你的 Codex 桌宠目录：

```text
C:\Users\<your-user-name>\.codex\pets\eason
```

最终文件结构应该是：

```text
C:\Users\<your-user-name>\.codex\pets\eason\pet.json
C:\Users\<your-user-name>\.codex\pets\eason\spritesheet.webp
```

然后重启 Codex，或者在 Codex 里切换一次桌宠，选择 `Eason`。

## 注意事项

- 只有拖动桌宠时会播放走路动画。
- 选中或非拖动状态不会触发走路动画，只会播放站立/待机动作。
- 图集格式为 Codex 自定义桌宠格式：`1536x1872`，8 列 9 行，每格 `192x208`。
