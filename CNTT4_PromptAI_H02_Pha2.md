# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 02
- **Họ tên: Trần Tuấn Anh**
- **Lớp: CNTT 4**
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini): Gemini**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký gói tập ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "PT10",
    "ngay_bat_dau": "2026-12-15",
    "nguoi_lon": 2,
    "hoc_sinh": 1,
    "ca_tap": "toi",
    "ghi_chu": null
  },
  {
    "ma_goi": "YOG1",
    "ngay_bat_dau": "2027-01-04",
    "nguoi_lon": 3,
    "hoc_sinh": 0,
    "ca_tap": null,
    "ghi_chu": "vừa mổ dây chằng gối"
  },
  {
    "ma_goi": "GYM1",
    "ngay_bat_dau": null,
    "nguoi_lon": 4,
    "hoc_sinh": 0,
    "ca_tap": "sang",
    "ghi_chu": "bị hen suyễn"
  }
]
```

**Link trò chuyện:https://share.gemini.google/LQy6UB4mJLza**

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
Tiền người lớn: 6 × 900.000 = 5.400.000 đồng
Tiền học sinh: 2 × (900.000 × 70%) = 1.260.000 đồng
Tiền gói tập: 5.400.000 + 1.260.000 = 6.660.000 đồng
Giảm giá nhóm: 6.660.000 × 5% = 333.000 đồng
Phụ thu: 2 × 150.000 = 300.000 đồng
Tổng tiền: (6.660.000 - 333.000) + 300.000 = 6.627.000 đồng
[RESULT: 6.627.000 đồng]
```

**Link trò chuyện:https://share.gemini.google/zm1jide79eBm**

### b) Kiểm tra kết quả AI

(Ghi kết luận AI đúng hay sai; nếu sai, ghi bước sai đầu tiên và kết quả đúng của bước đó – xoá dòng này)

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "huy_lop",
  "so_khach": 2,
  "so_buoi_bi_huy": 3,
  "tom_tat": "2 khách gói Yoga YOG1 khiếu nại việc hủy 3 buổi tập tối không báo trước trong tuần qua."
}
```

**Link trò chuyện:https://share.gemini.google/GFEkjsOIsKHx**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí | Điểm | Minh chứng | Đề xuất sửa |
| --- | --- | --- | --- |
| **Đúng thông tin (50%)** | 0.0/5.0 | - Sai giá: "500.000đ thôi, rẻ lắm luôn ạ" (Thực tế: 600.000 đồng).<br>

<br>- Sai chính sách bảo lưu: "vẫn bảo lưu hết nha anh" (Thực tế: đã tập 10 ngày nằm trong khoảng từ ngày 8 đến ngày 15 chỉ được bảo lưu 50% số ngày còn lại). | - Sửa giá thành: 600.000 đồng.<br>

<br>- Sửa chính sách: Theo chính sách, anh/chị đã tập 10 ngày nên sẽ được bảo lưu 50% số ngày còn lại. |
| **Đầy đủ (30%)** | 0.0/3.0 | - Thiếu lời mời khách cung cấp ngày bắt đầu và ca tập để đăng ký.<br>

<br>- Dùng từ ngữ suồng sã, không chuyên nghiệp ("rẻ lắm luôn ạ", "nha anh", "ib em"). | - Bổ sung câu mời: "Anh/chị vui lòng cung cấp ngày bắt đầu và ca tập để em hỗ trợ đăng ký ạ." |
| **Giọng điệu (20%)** | 0.0/2.0 | - Sử dụng từ ngữ suồng sã, thiếu chuyên nghiệp: "rẻ lắm luôn ạ", "nha anh", "ib em". | - Thay thế bằng văn phong lịch sự, chuyên nghiệp của tư vấn viên. |
| **Tổng điểm** | **0.0/10** |  |  |
```

**Link trò chuyện: https://share.gemini.google/R7cttcnF3WEP**
