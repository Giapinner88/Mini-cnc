# CNC Mini – Máy phay CNC để bàn giá rẻ tự chế

**CNC Mini** là một dự án máy CNC 3 trục nhỏ gọn, dễ xây dựng, được thiết kế để cắt **nhựa, mica, mạch in PCB**, và thậm chí **nhôm mỏng** với độ chính xác tương đối cao. Dự án hướng tới **sinh viên kỹ thuật**, **người học cơ điện tử**, hoặc **những ai yêu thích chế tạo cơ khí – điều khiển – tự động hóa**.

---

## Mục tiêu dự án

* Thiết kế và chế tạo **máy CNC 3 trục** nhỏ gọn (\~200×200×60 mm)
* Tận dụng linh kiện phổ thông: **motor 895**, **Arduino Uno**, **CNC Shield**
* Cắt được: **mạch in PCB, mica, POM, nhựa ABS**, và **nhôm mỏng**
* Có khả năng mở rộng lên laser hoặc spindle khỏe hơn

---

## Cấu trúc dự án

```bash
CNC-mini/
├── docs/                 # Hướng dẫn lắp ráp, kết nối
├── firmware/             # GRBL config cho Arduino CNC Shield
├── hardware/
│   ├── BOM.md            # Danh sách linh kiện chi tiết + link mua
│   └── wiring_diagram/   # Sơ đồ đấu nối hệ thống
├── cad/                  # File thiết kế khung (FreeCAD, STL)
├── gcode_samples/        # Mẫu G-code test cắt
└── README.md             # Giới thiệu & hướng dẫn tổng quan
```

---

## Thông số kỹ thuật cơ bản

| Thành phần             | Chi tiết                             |
| ---------------------- | ------------------------------------ |
| **Diện tích làm việc** | 200×200×60 mm                        |
| **Khung**              | Nhôm định hình 2020 / plywood CNC    |
| **Truyền động**        | Vitme T8 + ray trượt LM8UU           |
| **Động cơ**            | NEMA 17 x3 + driver TMC2209          |
| **Spindle**            | Motor 895 24VDC + collet ER11        |
| **Điều khiển**         | Arduino Uno + CNC Shield + GRBL 1.1h |
| **Nguồn**              | 24V – 6A trở lên                     |
| **Phần mềm CAM**       | Fusion360, FreeCAD, FlatCAM          |

---

## Danh sách linh kiện (BOM)

> Xem chi tiết tại: [`/hardware/BOM.md`](hardware/BOM.md)
> Gồm link mua tại Shopee, Nshop, IC Day Roi...

---

## Phần mềm điều khiển

* **Firmware:** GRBL 1.1h (Arduino Uno)
* **Sender:** [Universal Gcode Sender](https://winder.github.io/ugs_website/)
* **Thiết kế CAM:** Fusion 360, FreeCAD, FlatCAM (cho PCB)

---

## Tiến độ

* ✅ Thiết kế khung + BOM
* 💠 Đang lắp ráp phần cơ khí
* 🖒 Tích hợp điện tử, chạy test G-code
* 🖒 Gắn laser / spindle công suất lớn hơn (tuỳ chọn)

---

## Hình ảnh dự kiến

*(Cập nhật sau khi hoàn thành phần khung)*

---

## Mục tiêu học tập

* Làm quen thiết kế CAD/CAM
* Hiểu cơ chế điều khiển CNC 3 trục
* Làm chủ quy trình từ bản vẻ đến vật thật
* Ứng dụng thực tiễn vào các học phần cơ điện tử, điều khiển, thiết kế kỹ thuật...

---

## Đóng góp

Rất hoan nghênh mọi đóng góp về phần cứng, thiết kế khung, mã điều khiển, hoặc cải tiến tính năng.

> Maintainer: \[YourGitHubUsername]

