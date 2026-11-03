# images-bed

词通 App 的动漫海报图床。图片按**动画工作室**归档，通过 raw.githubusercontent.com 按 commit pin 引用。

## 目录约定

```
img/
├── <studio>/<作品名>.avif   # 按动画工作室分组（目录名用英文小写 + 下划线）
└── _unused/<原目录>/<作品名> # 未接入 App 的孤儿图（隔离区，可随时删除或重新接线）
```

- 文件名保留作品原名（允许中文），URL 使用时做 percent-encoding。
- App 端引用表：`wordapp/data/anime_img.json`，值形如
  `https://raw.githubusercontent.com/jayz24017-code/images-bed/<commit>/img/<studio>/<name>`。
- 移动/重命名图片后，必须同步改写引用并重新 pin 到新 commit，否则 App 海报会 404。
- 仓库体积约 874MB，超过 jsDelivr 免费版 50MB 上限（会间歇 403），因此不使用 jsDelivr。

## 统计

- 图片总数：**3763**
- 工作室目录：**166**
- 隔离区 `_unused`：**938** 张

## 工作室目录

<details><summary>展开全部 166 个目录</summary>

| 目录 | 张数 | 大小 |
|---|---:|---:|
| `sunrise` | 288 | 51.2 MB |
| `madhouse` | 223 | 41.1 MB |
| `j_c_staff` | 215 | 33.6 MB |
| `tms` | 190 | 36.9 MB |
| `a_1_pictures` | 173 | 41.2 MB |
| `bones` | 87 | 16.8 MB |
| `doga_kobo` | 75 | 20.2 MB |
| `silver_link` | 75 | 18.4 MB |
| `mappa` | 72 | 26.7 MB |
| `shaft` | 71 | 21.5 MB |
| `kyoto_animation` | 60 | 27.0 MB |
| `8_bit` | 56 | 11.4 MB |
| `olm` | 49 | 14.7 MB |
| `wit_studio` | 48 | 12.1 MB |
| `cloverworks` | 43 | 7.8 MB |
| `kinema_citrus` | 42 | 6.7 MB |
| `paworks` | 42 | 17.9 MB |
| `diomedea` | 41 | 9.0 MB |
| `studio_deen` | 41 | 9.6 MB |
| `brain_s_base` | 39 | 10.5 MB |
| `pierrot` | 39 | 9.2 MB |
| `pigar` | 38 | 21.2 MB |
| `david_production` | 37 | 14.9 MB |
| `ufotable` | 36 | 14.8 MB |
| `disney` | 33 | 23.9 MB |
| `passione` | 33 | 9.5 MB |
| `white_fox` | 32 | 12.4 MB |
| `lerche` | 30 | 7.3 MB |
| `pixar` | 28 | 18.8 MB |
| `sanzigen` | 28 | 6.4 MB |
| `hal_film_maker` | 26 | 4.5 MB |
| `ghibli` | 25 | 10.2 MB |
| `gainax` | 24 | 5.1 MB |
| `gohands` | 24 | 7.1 MB |
| `polygon_pictures` | 24 | 1.9 MB |
| `engi` | 22 | 9.1 MB |
| `c2c` | 20 | 5.4 MB |
| `trigger` | 20 | 9.1 MB |
| `dreamworks` | 19 | 13.5 MB |
| `toei_animation` | 19 | 5.4 MB |
| `production_i_g` | 15 | 2.6 MB |
| `studio_3hz` | 14 | 4.6 MB |
| `bibury_animation_studios` | 13 | 3.1 MB |
| `cygamespictures` | 13 | 2.9 MB |
| `arvo` | 10 | 3.2 MB |
| `fate` | 9 | 2.5 MB |
| `naz` | 9 | 0.5 MB |
| `nut` | 9 | 0.6 MB |
| `shin_ei_animation` | 9 | 1.0 MB |
| `hosoda_mamoru` | 8 | 2.3 MB |
| `illumination` | 8 | 2.7 MB |
| `khara` | 8 | 1.9 MB |
| `lidenfilms` | 8 | 2.1 MB |
| `shadowmachine` | 8 | 2.2 MB |
| `studiokai` | 8 | 1.2 MB |
| `shinkai_makoto` | 7 | 4.7 MB |
| `feel` | 6 | 1.5 MB |
| `synergysp` | 6 | 1.6 MB |
| `kon_satoshi` | 5 | 4.7 MB |
| `shuka` | 5 | 0.3 MB |
| `emt_squared` | 4 | 0.4 MB |
| `felix_film` | 4 | 0.7 MB |
| `zero_g` | 4 | 0.9 MB |
| `east_fish_studio` | 3 | 0.6 MB |
| `gekkou` | 3 | 0.3 MB |
| `geyeg_pictures` | 3 | 0.3 MB |
| `maho_film` | 3 | 0.2 MB |
| `nippon_animation` | 3 | 0.5 MB |
| `project_no_9` | 3 | 0.2 MB |
| `science_saru` | 3 | 0.2 MB |
| `tatsunoko` | 3 | 0.5 MB |
| `troyca` | 3 | 0.2 MB |
| `100studio` | 2 | 0.2 MB |
| `actas` | 2 | 0.1 MB |
| `asahi_production` | 2 | 0.1 MB |
| `ashi_productions` | 2 | 0.2 MB |
| `atorie` | 2 | 0.5 MB |
| `bridge` | 2 | 1.0 MB |
| `cue` | 2 | 0.2 MB |
| `dle` | 2 | 0.2 MB |
| `gonzo` | 2 | 0.1 MB |
| `hornets` | 2 | 0.6 MB |
| `imagin` | 2 | 0.2 MB |
| `jumondou` | 2 | 0.3 MB |
| `konami_animation` | 2 | 0.8 MB |
| `lay_duce` | 2 | 0.3 MB |
| `magic_bus` | 2 | 0.2 MB |
| `mgm` | 2 | 0.1 MB |
| `mushi_production` | 2 | 0.1 MB |
| `orange` | 2 | 0.2 MB |
| `shanghai_animation` | 2 | 0.0 MB |
| `studio42` | 2 | 0.2 MB |
| `studio_4_c` | 2 | 0.1 MB |
| `studio_a_cat` | 2 | 0.7 MB |
| `studio_bind` | 2 | 0.5 MB |
| `studio_comet` | 2 | 0.2 MB |
| `tezuka_production` | 2 | 0.6 MB |
| `typhoon_graphics` | 2 | 0.2 MB |
| `yokohama_animation_lab` | 2 | 0.2 MB |
| `a_c_g_t` | 1 | 0.1 MB |
| `akatsuki_media` | 1 | 0.1 MB |
| `asread` | 1 | 0.1 MB |
| `atra` | 1 | 0.5 MB |
| `aura_studio` | 1 | 0.1 MB |
| `bakkka` | 1 | 0.1 MB |
| `bandai_namco_pictures` | 1 | 0.1 MB |
| `benten_film` | 1 | 0.1 MB |
| `bn_pictures` | 1 | 0.2 MB |
| `bug_films` | 1 | 0.1 MB |
| `c_station` | 1 | 0.1 MB |
| `cocoa_bean` | 1 | 0.1 MB |
| `colored_pencil` | 1 | 0.0 MB |
| `comptown` | 1 | 0.1 MB |
| `connect` | 1 | 0.1 MB |
| `daily_plan_net` | 1 | 0.1 MB |
| `drive` | 1 | 0.1 MB |
| `e_and_h_production` | 1 | 0.9 MB |
| `electric_circus` | 1 | 0.1 MB |
| `elias` | 1 | 0.1 MB |
| `gallop` | 1 | 0.4 MB |
| `graphinica` | 1 | 0.1 MB |
| `hanmuharu` | 1 | 0.0 MB |
| `juvenage` | 1 | 0.1 MB |
| `lapin_track` | 1 | 0.1 MB |
| `lapintrack` | 1 | 0.1 MB |
| `lesprit` | 1 | 0.1 MB |
| `m_s_c` | 1 | 0.1 MB |
| `makaria` | 1 | 0.0 MB |
| `manglobe` | 1 | 0.0 MB |
| `newon` | 1 | 0.1 MB |
| `nichicaline` | 1 | 0.1 MB |
| `okuruto_noboru` | 1 | 0.1 MB |
| `pine_jam` | 1 | 0.1 MB |
| `platinum_vision` | 1 | 0.1 MB |
| `pra` | 1 | 0.1 MB |
| `production_h` | 1 | 0.9 MB |
| `quad` | 1 | 0.3 MB |
| `qubic_pictures` | 1 | 0.3 MB |
| `roll2` | 1 | 0.1 MB |
| `s_o_k` | 1 | 0.2 MB |
| `seven_arcs` | 1 | 0.1 MB |
| `signal_md` | 1 | 0.1 MB |
| `smde` | 1 | 0.6 MB |
| `soigne` | 1 | 0.1 MB |
| `studio_candy_box` | 1 | 0.1 MB |
| `studio_chromato` | 1 | 0.9 MB |
| `studio_durian` | 1 | 0.7 MB |
| `studio_flad` | 1 | 0.1 MB |
| `studio_gokumi` | 1 | 0.1 MB |
| `studio_h_kiboshi` | 1 | 0.4 MB |
| `studio_hibari` | 1 | 0.1 MB |
| `studio_kafka` | 1 | 0.1 MB |
| `studio_leo` | 1 | 0.1 MB |
| `studio_seven` | 1 | 0.1 MB |
| `studio_voln` | 1 | 0.1 MB |
| `studiomassket` | 1 | 0.1 MB |
| `studiopallet` | 1 | 0.4 MB |
| `toon_harbor_works` | 1 | 0.1 MB |
| `triangle_staff` | 1 | 0.2 MB |
| `unend` | 1 | 0.1 MB |
| `uwan_pictures` | 1 | 0.1 MB |
| `voil` | 1 | 0.1 MB |
| `wao_world` | 1 | 0.5 MB |
| `yostar_pictures` | 1 | 0.1 MB |
| `yumeta_company` | 1 | 0.1 MB |
| `zexcs` | 1 | 0.1 MB |

</details>
