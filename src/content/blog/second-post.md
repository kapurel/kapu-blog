---
title: "Tailwind CSS v4の新機能"
description: "Tailwind CSS v4で導入された主な変更点と新機能をまとめました。"
pubDate: 2025-02-10
tags: ["tailwind", "css"]
draft: false
---

## Tailwind CSS v4とは

Tailwind CSS v4は、パフォーマンスと開発体験を大幅に改善したメジャーアップデートです。

## 主な変更点

### CSSファーストの設定

v4では `tailwind.config.js` が不要になり、CSSファイル内で直接設定できるようになりました。

```css
@import "tailwindcss";
```

これだけでTailwindが使えるようになります。

### パフォーマンスの向上

新しいエンジン「Oxide」により、ビルド速度が大幅に向上しました。

### CSSネイティブ機能の活用

- `@layer` によるカスケードの制御
- CSS変数を活用したテーマシステム
- `color-mix()` によるカラー操作

## まとめ

Tailwind CSS v4は、よりモダンなCSS機能を活用した進化版です。新規プロジェクトでは積極的に採用していきたいですね。
