# KYURS

Minecraft plugins and compatibility projects for the Oleksyuk Family Server, built around Pumpkin and its proxy integrations.

## Planned mods and future additions

This is our development roadmap. **Pending does not mean installed or ready to use.** Release dates have not been set.

| Project | Status | Planned work |
| --- | --- | --- |
| [Infinite Villager Trading / InstantRestock](https://modrinth.com/plugin/infinite-villager-trading) | **Pending — future addition; not installed** | Add infinite villager trading through a Pumpkin-compatible implementation. Compatibility work and testing are still required. |
| [Voice Messages](https://modrinth.com/plugin/voicemessages) | **Pending — future addition; not installed** | Add recorded voice messages in Minecraft chat, similar to regular voice notes. Plan integration with Simple Voice Chat and evaluate Pumpkin compatibility; the upstream mod requires both client and server support. |
| [ItemEdit](https://modrinth.com/plugin/itemedit) | **Pending — future addition; not installed** | Add item customization and saved-item management through a Pumpkin-compatible implementation. Evaluate support for names, lore, enchantments, attributes, and item storage before implementation. |
| [FastAsyncWorldEdit (FAWE)](https://modrinth.com/plugin/fastasyncworldedit) | Full port pending; native core installed | [Rust-WorldEdit](https://github.com/kyurs/Rust-WorldEdit) now provides tested operator-only `//wand`, selections, set/replace, copy/paste, and undo/redo on Pumpkin. This is a limited independent implementation, not full FAWE. Brushes, schematics, entities, biomes, regeneration, and full FAWE compatibility remain unfinished. |
| [Hurricane](https://modrinth.com/mod/hurricane) | Pending — Pumpkin compatibility | Complete the assessment and any necessary native fixes for Bedrock collision behavior. The source has been preserved, but a native Pumpkin port is not installed. |
| [TuffXPlus](https://github.com/TuffNetwork/TuffXPlus) | Pending — compatibility work | Find or build a Pumpkin-compatible integration for the previously requested plugin. It is not currently installed. |

### Deferred feature ideas

- **Custom Skins: image-URL skins.** Deferred while official Minecraft skins remain the current scope. Arbitrary image skins need a supported signing service and its configuration before this feature can be enabled.

Items will move out of this roadmap when their implementation and deployment have been verified. Listing a third-party project here does not imply affiliation with its authors or that its existing build runs directly on Pumpkin.
