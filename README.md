# HTP PDF Tools — Update & Release Distribution

Kho phân phối metadata và gói cập nhật chính thức.

## Phiên bản mới nhất: v1.1.15

Ngày phát hành: **26/11/2026**.

| Gói | Dung lượng | SHA-256 |
| --- | --- | --- |
| [HTP_PDF_Tools_Setup_v1.1.15.exe](https://github.com/huynhthanhphong86/htp_pdf_tools_update/releases/download/v1.1.15/HTP_PDF_Tools_Setup_v1.1.15.exe) | 185.8 MB | `08c7240560b76388982f45be3480820e43b7240e5363bb18318eb4a842114e3c` |
| [HTP_PDF_Tools_Portable_v1.1.15.zip](https://github.com/huynhthanhphong86/htp_pdf_tools_update/releases/download/v1.1.15/HTP_PDF_Tools_Portable_v1.1.15.zip) | 302.4 MB | `8004004ef10e398e65d16a4dce881921f442aba8c102ded4b30a5172840349ea` |
| [HTP_PDF_Tools_Patch_v1.1.15.zip](https://github.com/huynhthanhphong86/htp_pdf_tools_update/releases/download/v1.1.15/HTP_PDF_Tools_Patch_v1.1.15.zip) | 19.3 MB | `119d418aeb8b5bb1c382f5c6c211fdaf95dc81798010dc2bfa9146784d855c3d` |

## Thay đổi

- Kích hoạt trực tuyến bằng OTP email, mua bản quyền và nhập mã HTP; giữ giấy phép ngoại tuyến đã cấp.
- Dùng thử 14 ngày theo mã máy trên máy chủ: gỡ/cài lại, xóa dữ liệu hoặc đổi email không bắt đầu lại thời gian dùng thử.
- Chuyển ngày bắt đầu dùng thử cũ lên máy chủ; chỉ giữ nguyên hoặc rút ngắn hạn. Mất mạng không cấp lại dùng thử ngoại tuyến.
- Bản quyền 199.000đ/máy, mua một lần cho major 1; Viewer vẫn miễn phí. Chứng chỉ giấy phép dùng ngoại tuyến tối đa 90 ngày và được làm mới khi kết nối.
- Bao gồm các tối ưu bộ nhớ và khởi động đã kiểm tra cho tài liệu nhiều trang.

## Changes

- Activate online using email OTP and HTP license keys; previously issued offline licenses remain supported.
- One-time 14-day machine trial stored on the server. Reinstallation, deleting local data or changing email does not restart it.
- Migrate the earlier trial start date without extending the stored deadline; connection failures never grant a fresh offline trial.
- VND 199,000 paid once for one PC and major version 1. PDF viewing stays free; licensed offline certificates last up to 90 days and renew online.
- Includes verified startup and memory optimizations for large documents.

## Kiểm tra

Release build, 18 kiểm tra máy chủ với SQLite, 36 kiểm tra bản quyền trên gói phân phối, 48 kiểm tra hiệu năng và chuyển PDF sang DOCX/XLSX/PPTX trong runtime cô lập đều đạt. Live smoke trên máy chủ xác nhận hạn dùng thử không đổi sau mô phỏng xóa dữ liệu/cài lại. Chưa nghiệm thu OTP trong hộp thư, giao dịch tiền thật hoặc gỡ/cài trên máy Windows thử riêng.

Bộ cài chưa ký số. Windows 10/11 64-bit, .NET Framework 4.8. Dùng thử cần Internet; cài lại Windows hoặc thay ổ hệ thống có thể đổi mã máy.

[Trang phát hành](https://github.com/huynhthanhphong86/htp_pdf_tools_update/releases/tag/v1.1.15) · [Mã nguồn](https://github.com/huynhthanhphong86/htp_pdf_tools_free) · [Website](https://phanmemso.vn/htp-pdf-tools/)
