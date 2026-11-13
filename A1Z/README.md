# A1Z CAD 文件 / A1Z CAD Files

## 中文

本目录存放面向 A1Z 客户的 CAD 文件，包含机械臂基座、腕部相机支架与 J6 输出法兰，供安装集成、工装与末端执行器设计使用。`.STEP` / `.stp` 为三维模型，`.pdf` 为标注尺寸与孔位的工程图纸。

| 文件 | 类型 | 作用 |
|:---|:---|:---|
| `A1Z_Base.STEP` | 三维模型 | 机械臂基座（Base）模型，用于工作台安装布局、孔位核对与结构适配 |
| `A1Z_Base_Drawing.pdf` | 工程图纸 | 基座尺寸图，标注外形尺寸、安装孔位及 Ø5 mm 销钉孔（深 6.5 mm MAX） |
| `A1Z_Wrist_Camera_Mount.stp` | 三维模型 | A1Z 腕部相机支架，用于在腕部安装相机并确定相机与末端的相对位置 |
| `A1Z_J6_Output_Flange.STEP` | 三维模型 | J6 关节输出法兰模型，用于夹爪、末端执行器或自定义工具的机械接口设计 |
| `A1Z_J6_Output_Flange_Drawing.pdf` | 工程图纸 | 输出法兰尺寸图，标注 Ø54 / Ø38 mm、厚 5.5 mm、对边 45 mm 及 3 × M3 螺纹孔（深 6 mm MAX） |

> 说明：图纸尺寸用于机械接口设计参考，最终装配请以三维模型和实物为准。

---

## English

This directory contains CAD files for A1Z customers, covering the robot base, the wrist camera mount, and the J6 output flange. They are intended for installation planning, tooling, and end-effector design. `.STEP` / `.stp` files are 3D models; `.pdf` files are dimensioned engineering drawings.

| File | Type | Description |
|:---|:---|:---|
| `A1Z_Base.STEP` | 3D model | Robot base model for workcell layout, mounting-hole verification, and mechanical adaptation |
| `A1Z_Base_Drawing.pdf` | Drawing | Base dimensioned drawing: overall dimensions, mounting holes, and Ø5 mm dowel pin holes (6.5 mm MAX depth) |
| `A1Z_Wrist_Camera_Mount.stp` | 3D model | Wrist camera mount for A1Z; fixes the camera position relative to the wrist/end-effector |
| `A1Z_J6_Output_Flange.STEP` | 3D model | J6 output flange model for designing the mechanical interface to grippers, end effectors, or custom tools |
| `A1Z_J6_Output_Flange_Drawing.pdf` | Drawing | Flange dimensioned drawing: Ø54 / Ø38 mm, 5.5 mm thickness, 45 mm across flats, and 3 × M3 threaded holes (6 mm MAX depth) |

> Note: Drawing dimensions are provided as a reference for mechanical interface design. Use the 3D models and the physical part for final fit checks.
