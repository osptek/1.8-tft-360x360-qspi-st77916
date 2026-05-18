# 1.8" 360×360 TFT QSPI module (ST77916) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 1.8-inch **TFT** panel, **360×360** resolution |
| Interface | **QSPI** |
| Driver IC | **ST77916** |
| Spec ID | **`1.8-tft-360x360-qspi-st77916`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, initialization documentation |
| `examples/` | **Sample projects** grouped by feature |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **ESP-IDF代码** (LVGL8 baseline, esp-lvgl-adapter LVGL8 / LVGL9) |
| `with-te/` | Tear-related samples (**屏幕防撕裂代码**) |

### Sample project paths

#### Baseline and esp-lvgl-adapter (`examples/` root)

| Description | Path |
|:--|:--|
| LVGL8 baseline | `examples/esp32s3-idf5_st77916-qspi_lvgl8/` |
| esp-lvgl-adapter + LVGL8 | `examples/esp32s3-idf5_st77916-qspi_esp-lvgl-adapter_lvgl8/` |
| esp-lvgl-adapter + LVGL9 | `examples/esp32s3-idf5_st77916-qspi_esp-lvgl-adapter_lvgl9/` |

#### Tear-related (`with-te/`)

| Description | Path |
|:--|:--|
| LVGL8 + LCD with TE | `examples/with-te/esp32s3-idf5_st77916-qspi_lvgl8_lcd-with-te/` |
| esp-lvgl-adapter + LVGL8 + LCD with TE | `examples/with-te/esp32s3-idf5_st77916-qspi_esp-lvgl-adapter_lvgl8_lcd-with-te/` |
| esp-lvgl-adapter + LVGL9 + LCD with TE | `examples/with-te/esp32s3-idf5_st77916-qspi_esp-lvgl-adapter_lvgl9_lcd-with-te/` |
