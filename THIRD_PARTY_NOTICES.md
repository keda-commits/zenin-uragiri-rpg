# THIRD_PARTY_NOTICES

## フォント

| 名称 | 作者 | URL | ライセンス | 変更 | 保存場所 |
|---|---|---|---|---|---|
| PixelMplus12 Regular / PixelMplus10 Regular（PixelMplus-20130602） | itouhiro / M+ FONTS PROJECT | https://github.com/itouhiro/PixelMplus | M+ FONT LICENSE（改変・再配布・商用利用可） | なし（TTFをそのまま同梱） | `public/fonts/`、ライセンス原文は `public/fonts/licenses/` |

## ライブラリ（npm、`package-lock.json` で固定）

| 名称 | バージョン | ライセンス | 用途 |
|---|---|---|---|
| Phaser | 3.90.0 | MIT | ゲームエンジン |
| TypeScript | 5.9.3 | Apache-2.0 | 開発時のみ |
| Vite | 7.3.8 | MIT | 開発サーバー・ビルド（開発時のみ） |
| Vitest | 3.2.7 | MIT | ユニットテスト（開発時のみ） |
| @playwright/test | 1.57.0 | Apache-2.0 | E2Eテスト（開発時のみ） |

## 画像・音声

外部の画像・音声素材は使用していません。

- ドット絵（キャラクター、顔グラ、タイル、小物、UI枠、エフェクト）はすべて `src/art/` のコードが起動時に描画する自作です。
- BGM・効果音はすべて `src/systems/Audio.ts` が WebAudio で合成する自作です（メロディも本作用の書き下ろし）。
- 仕様書が候補に挙げた Ninja Adventure Asset Pack（CC0）と Kenney Tiny Dungeon（CC0）は、配布ページからの自動取得ができなかったため使っていません。画風を統一するため、すべて自作にしました。
