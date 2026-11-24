# HTP PDF Tools - Update & Release Distribution

Kho phân phối chính thức metadata cập nhật và các gói phát hành của **HTP PDF Tools**.

## Phiên bản mới nhất: v1.1.14

Ngày phát hành: **25/11/2026**.

| Gói tải xuống | Dung lượng | Cách dùng |
| --- | --- | --- |
| [Patch ZIP](https://github.com/huynhthanhphong86/htp_pdf_tools_update/releases/download/v1.1.14/HTP_PDF_Tools_Patch_v1.1.14.zip) | 18.1 MB | Cập nhật ứng dụng đã có sẵn |
| [Setup EXE](https://github.com/huynhthanhphong86/htp_pdf_tools_update/releases/download/v1.1.14/HTP_PDF_Tools_Setup_v1.1.14.exe) | 185.8 MB | Cài đặt hoặc cập nhật đầy đủ |
| [Portable ZIP](https://github.com/huynhthanhphong86/htp_pdf_tools_update/releases/download/v1.1.14/HTP_PDF_Tools_Portable_v1.1.14.zip) | 302.3 MB | Giải nén và chạy trực tiếp |

[Trang phát hành v1.1.14](https://github.com/huynhthanhphong86/htp_pdf_tools_update/releases/tag/v1.1.14)

## Thay đổi trong v1.1.14

- Lưu PDF tạo từ Word, Excel, PowerPoint, văn bản và ảnh cùng thư mục với tệp nguồn. Tự thêm số khi trùng tên để giữ các tệp đã có.
- Chuyển nhiều tệp thành từng PDF riêng hoặc gộp thành một PDF. Có nút Lên/Xuống để sắp thứ tự; hỗ trợ mở tệp, kéo thả và menu chuột phải trong Explorer.
- Giữ nguyên lề đã đặt khi đổi khổ giấy hoặc hướng giấy trong thuộc tính máy in, khắc phục lỗi lề bị đặt lại thành 2,54 cm.
- Bổ sung thư viện chuyển đổi còn thiếu trong gói Setup/Portable; kiểm tra runtime Python ở chế độ cô lập khi đóng gói.

## Changes in v1.1.14

- Save PDFs created from Word, Excel, PowerPoint, text and images next to their source files. Add a number when an output name already exists.
- Convert multiple selected files into individual PDFs or a single merged PDF, with Up/Down ordering and support for file opening, drag-and-drop and Explorer context menus.
- Preserve custom margins when changing paper size or orientation in printer properties instead of resetting them to 2.54 cm.
- Complete the bundled conversion dependencies in Setup/Portable packages and validate Python in isolated mode during packaging.

## Kiểm tra phát hành

Release build và 53 kiểm tra tự động cho luồng PDF: chuyển Word/Excel/ảnh, vị trí lưu, trùng tên, thứ tự gộp, hủy tác vụ và giữ lề. Chưa nghiệm thu in trên máy in thật.

[Kho mã nguồn](https://github.com/huynhthanhphong86/htp_pdf_tools_free) · [Metadata cập nhật](version.json)
