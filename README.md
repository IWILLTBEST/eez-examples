# IWILLTBEST EEZ Examples

Standalone collection of EEZ Studio example projects. Tracks [eez-open/eez-project-examples](https://github.com/eez-open/eez-project-examples) and adds widget examples contributed through [IWILLTBEST/studio](https://github.com/IWILLTBEST/studio) while they go through upstream review.

## Added on top of upstream

| Example | Content |
|---|---|
| `examples/LVGL/GIF.eez-project` | GIF widget (`lv_gif`), replicating the official LVGL gif example: two animated bulb GIFs from embedded raw bytes, aligned left-mid and right-mid. Requires a Studio build with `LV_USE_GIF` in the editor wasm (e.g. IWILLTBEST/studio) for the animated Run preview; the generated C is standard `lv_gif_create`/`lv_gif_set_src`. |
| `examples/LVGL/MessageBox.eez-project` | `lv_example_msgbox_1` replica |
| `examples/LVGL/List.eez-project` | `lv_example_list_1` replica (symbols + per-button click handlers) |
| `examples/LVGL/Menu.eez-project` | `lv_example_menu_1` replica |
| `examples/LVGL/TileView.eez-project` | `lv_example_tileview_1` replica (L-shaped navigation) |

All new examples replicate the official LVGL documentation examples, per the upstream examples rule of thumb.
