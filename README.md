# 1.8 寸 360×360 TFT QSPI 模组（ST77916）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 1.8 英寸 **TFT**，分辨率 **360×360** |
| 接口 | **QSPI** |
| 驱动芯片 | **ST77916** |
| 规格标识 | 产品资料中常用 **`1.8-tft-360x360-qspi-st77916`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明、屏幕初始化相关文档 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **ESP-IDF代码**（LVGL8 基础、esp-lvgl-adapter LVGL8 / LVGL9） |
| `with-te/` | **屏幕防撕裂代码** |

### 示例工程路径

#### 基础与 esp-lvgl-adapter（`examples/` 根目录）

| 说明 | 路径 |
|:--|:--|
| LVGL8 基础 | `examples/esp32s3-idf5_st77916-qspi_lvgl8/` |
| esp-lvgl-adapter + LVGL8 | `examples/esp32s3-idf5_st77916-qspi_esp-lvgl-adapter_lvgl8/` |
| esp-lvgl-adapter + LVGL9 | `examples/esp32s3-idf5_st77916-qspi_esp-lvgl-adapter_lvgl9/` |

#### 屏幕防撕裂代码（`with-te/`）

| 说明 | 路径 |
|:--|:--|
| LVGL8 + LCD，含 TE | `examples/with-te/esp32s3-idf5_st77916-qspi_lvgl8_lcd-with-te/` |
| esp-lvgl-adapter + LVGL8 + LCD，含 TE | `examples/with-te/esp32s3-idf5_st77916-qspi_esp-lvgl-adapter_lvgl8_lcd-with-te/` |
| esp-lvgl-adapter + LVGL9 + LCD，含 TE | `examples/with-te/esp32s3-idf5_st77916-qspi_esp-lvgl-adapter_lvgl9_lcd-with-te/` |
