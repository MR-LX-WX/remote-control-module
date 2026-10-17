# 生产文件 / Fabrication

此目录用于存放从嘉立创EDA 专业版导出的生产文件。当前内容尚未补充。

## 需要导出的文件

| 文件 | 导出方式（嘉立创EDA 专业版） | 建议命名 |
| --- | --- | --- |
| Gerber + 钻孔 | PCB 界面 → 制造 → 导出 Gerber（RS-274X），勾选「导出钻孔文件」，打包为 ZIP | `gerber-v1.0.zip` |
| BOM | 原理图/PCB → 制造 → 导出 BOM（CSV） | `bom-v1.0.csv` |
| 坐标文件 | PCB → 制造 → 导出坐标文件（Pick & Place，CSV） | `pick-and-place-v1.0.csv` |
| 原理图 PDF | 原理图 → 导出 → PDF | `schematic-v1.0.pdf` |
| 3D 模型（可选） | PCB → 导出 3D 模型（STEP） | `model-v1.0.step` |

## 出板参数参考

- 层数：2 层
- 板材：FR-4，1.6 mm（按需调整）
- 板框：握把造型异形板，下单时注意最小外形尺寸与工艺边
- 表面处理：建议 HASL 或 沉金（按键触点密集处优先沉金）

导出后把文件放进本目录，并在根目录 `README.md` 的「生产制造」章节更新列表。
