# 灵兽游记 音频署名

## 配乐

| 位置 | 曲目 | 用法 |
| --- | --- | --- |
| 小院 | Lotus Pond · BiteMe Games | 保留作者的循环版，筝和笛适合轻巧上场 |
| 桃溪 | Dragon Dance · BiteMe Games | 保留作者的循环版，用清晰鼓点撑起开阔野地和交战 |
| 竹庭 | 故敌愁 · 乌鸦Producer | 取鼓点稳定的一段，编辑为游戏循环 |
| 月宫 | Rivers and Mountains · ziniyeons | 取古筝、二胡和鼓推动的中段，编辑为游戏循环 |

Music by [乌鸦Producer]. 曲目用于游戏内配乐，作者的原始发行包可从下方获取。

- BiteMe Games《Chinese Game Music》，[CC0 与原始下载](https://bitemegames.itch.io/chinese-game-music)
- 乌鸦Producer《Chinese style music Pack》，[作者的授权条款与原始下载](https://crowbacillus.itch.io/crows-free-commercial-music-pack-chinese-style-music-pack)
- Music: “Rivers and Mountains” by ziniyeons. [曲目与原始下载](https://niftyshelf.com/music/rivers-and-mountains/) · [NiftyShelf 商业项目许可](https://niftyshelf.com/license/)
- 竹庭的气质参考梅林茂为《十面埋伏》写的 [Bamboo Forest](https://www.youtube.com/watch?v=IZfN7eBypek)。游戏曲目仍是上表所列的授权作品。

## 武器音效

- 三种短促的开火底录音来自 [Gunshots，OpenGameArt，CC0](https://opengameart.org/content/gunshots)。
- 散花铳、长铳和机械装填使用 [3d_shooter 标注的 CC0 源录音](https://github.com/Ollie1o1/3d_shooter/blob/main/assets/sfx/CREDITS.md)，其枪声出处为 [Gunshot Sounds](https://opengameart.org/content/gunshot-sounds)。
- 刀刃碰撞来自 Ben Jaszczak 和 Brian Nelson / Still North Media 的 [Medieval Sound Effects · Weapon impacts，CC0](https://opengameart.org/content/medieval-sound-effects-weapon-impacts)。取用 3d_shooter 整理的三个录音片段。
- 剑气、符咒、拳击质感来自 [SFX Brew 的仙侠武侠包](https://sfxbrew.com/packs/xianxia-game-sound-pack/)，原作者允许商用。
- 录音补充层来自 Freesound 的 CC0 发布：[Bamboo hit / michorvath](https://freesound.org/people/michorvath/sounds/386888/)、[Clean fast Swoosh / Danjocross](https://freesound.org/people/Danjocross/sounds/507466/)、[whip02 / snowflakes](https://freesound.org/people/snowflakes/sounds/72190/)、[Paper Rustle / BenjaminNelan](https://freesound.org/people/BenjaminNelan/sounds/353125/)。

配乐做了音量匹配、编码和所标注的循环编辑。武器层的选材和混合过程见 `audio-production.py`。设计参考了 [3d_shooter 的录音处理脚本](https://github.com/Ollie1o1/3d_shooter/blob/main/tools/gen_arsenal.py) 和 [r/gamedev 关于枪声分层的讨论](https://www.reddit.com/r/gamedev/comments/13o56ca/where_can_i_get_weapon_sounds/)。

身体命中由 SFX Brew 的拳击声与 HighWaistedPants 的泥团落地声叠合。精准命中由 Still North Media 的金属碰击与 SFX Brew 的短钟声叠合。两种音效均为本游戏重新剪辑的版本。

## 敌袭方位音

- 拉弓素材来自 [Bow Drawn / Paveroux，CC0](https://freesound.org/people/Paveroux/sounds/490556/)。
- 弓弦与弩弦素材来自 [Arrow Loose / saturdaysoundguy，CC0](https://freesound.org/people/saturdaysoundguy/sounds/394185/) 和 [Bow Release 4 / Ali_6868，CC0](https://freesound.org/people/Ali_6868/sounds/384917/)。
- 陶弹落地使用 [wet clay thud / HighWaistedPants，CC0](https://freesound.org/people/HighWaistedPants/sounds/847272/) 和近距离的金属碰撞层。首领和符印素材使用上文列出的 SFX Brew、公开录音及 GitHub 来源。
- 将相应原素材放入项目上一级的 `.qa-work/research/` 后，可用 `python audio-production.py --threats` 重新生成内嵌提示音。
