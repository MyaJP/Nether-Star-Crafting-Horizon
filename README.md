# Nether Star Crafting (Horizon)

A content mod for [Horizon](https://playhorizon.dev), the Rust rewrite of Minecraft: Java Edition 26.3.
It adds a new intermediate item, the **Netherstar Shard**, and a crafting recipe for the **Nether Star**.

No code: data and assets only (Horizon content mod, API 0.2). The Wither still drops the Nether Star as usual.

## Recipes

**Netherstar Shard**

|               |               |               |
|:-------------:|:-------------:|:-------------:|
| Diamond       | Gold Ingot    | Diamond       |
| Gold Ingot    | Block of Iron | Gold Ingot    |
| Diamond       | Gold Ingot    | Diamond       |

**Nether Star**

|                  |                  |                  |
|:----------------:|:----------------:|:----------------:|
|                  | Netherstar Shard |                  |
| Netherstar Shard | Ghast Tear       | Netherstar Shard |
|                  | Netherstar Shard |                  |

## Install

1. Install it from the launcher's Mods page (Horizon), or put `netherstarrecipe.hmod` in the `horizon-mods` folder of your game folder.
2. Turn it on in Options > Mods, then restart the game.

## Java Edition

The same mod is available for Forge, NeoForge and Fabric on CurseForge: <https://www.curseforge.com/minecraft/mc-mods/nether-star-crafting>

## Build

```sh
cargo install --git https://github.com/horizon-rust/horizon cargo-horizon-mod
cargo horizon-mod build
cargo horizon-mod check target/horizon-mod/netherstarrecipe.hmod
```

---

# Nether Star Crafting（Horizon版）

Minecraft: Java Edition 26.3 を Rust で書き直した [Horizon](https://playhorizon.dev) 用のコンテンツMODです。
新しい中間素材「**ネザースターの欠片**」と、**ネザースター**のクラフトレシピを追加します。

コードは含まず、データとアセットだけでできています。ウィザーからのネザースターのドロップはそのままです。

## レシピ

- **ネザースターの欠片**：四隅にダイヤモンド、上下左右に金インゴット、中央に鉄ブロック
- **ネザースター**：上下左右にネザースターの欠片、中央にガストの涙

## 導入方法

1. ランチャーの「Mods」ページ（Horizon）から入れるか、ゲームフォルダの `horizon-mods` フォルダに `netherstarrecipe.hmod` を入れます。
2. オプション → 改造 でオンにして、ゲームを再起動します。

## Java版

Forge / NeoForge / Fabric 版は CurseForge で公開しています：<https://www.curseforge.com/minecraft/mc-mods/nether-star-crafting>

## License

MIT © Mya
