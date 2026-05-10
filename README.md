English | [繁體中文](#繁體中文)

# chiatom-themes

Community themes for [Chiatom](https://github.com/dylan45132-jpg/chiatom) — a block-based handout editor built around A4 pages.

---

## How to use a theme

1. Download the theme folder you want (e.g. `slate/`)
2. Open Chiatom → click "Theme" in the toolbar → "Import Folder"
3. Select the downloaded folder

That's it. The theme applies immediately.

---

## Themes

| Theme | Style | Preview |
|---|---|---|
| **Slate** | Slate gray, fine borders, technical handouts | — |
| **Washi** | Warm off-white, washi paper feel, humanities | — |
| **Moss** | Low-saturation green accent, natural, general purpose | — |

---

## Submit your theme

1. Fork this repository
2. Create a new folder with your theme name (e.g. `my-theme/`)
3. Add `theme.css` and `theme.json` inside the folder
4. Open a Pull Request with a short description of the style

### Theme package structure

```
my-theme/
├── theme.css     # Page styles (required)
└── theme.json    # Theme metadata (required)
```

Minimum `theme.json`:

```json
{
  "name": "My Theme",
  "version": "1.0.0",
  "author": "Your Name",
  "description": "A one-line description",
  "pageSize": "A4",
  "blocks": []
}
```

For full authoring instructions, see the [Theme Guide](https://github.com/dylan45132-jpg/chiatom/blob/main/docs/en/theme-guide.md).

---

## License

All themes in this repository are released under the [MIT License](LICENSE).
You are free to use, modify, and distribute themes — including for commercial purposes.

---

---

# 繁體中文

# chiatom-themes

[Chiatom](https://github.com/dylan45132-jpg/chiatom) 的社群主題包集合。

---

## 如何使用主題

1. 下載你想要的主題資料夾（例如 `slate/`）
2. 開啟 Chiatom → 點擊工具列「主題」→「資料夾匯入」
3. 選取下載的資料夾

主題立即套用。

---

## 主題列表

| 主題 | 風格 | 預覽 |
|---|---|---|
| **Slate** | 石板灰調，細邊線，理工講義 | — |
| **Washi** | 暖米白，和紙質感，人文課程 | — |
| **Moss** | 低飽和草綠 accent，自然沉穩，通用型 | — |

---

## 提交你的主題

1. Fork 這個 repo
2. 建立一個新資料夾，命名為你的主題名稱（例如 `my-theme/`）
3. 在資料夾內放入 `theme.css` 和 `theme.json`
4. 開一個 Pull Request，簡短描述主題風格

### 主題包結構

```
my-theme/
├── theme.css     # 頁面樣式（必要）
└── theme.json    # 主題資訊（必要）
```

最小可用的 `theme.json`：

```json
{
  "name": "我的主題",
  "version": "1.0.0",
  "author": "你的名字",
  "description": "一句話描述",
  "pageSize": "A4",
  "blocks": []
}
```

完整的主題製作說明請參考[主題製作指南](https://github.com/dylan45132-jpg/chiatom/blob/main/docs/zh/主題製作指南.md)。

---

## 授權

此 repo 內的所有主題以 [MIT License](LICENSE) 授權。
你可以自由使用、修改、散布主題，包含商業用途。
