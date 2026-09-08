# Thời Khóa Biểu Gia Đình

Lịch tuần (Lịch chung / Tuệ Lâm / Trí Lâm) trên **GitHub Pages**. Cả nhà mở **một link**; khi đổi lịch thì sửa dữ liệu rồi đẩy lại GitHub.

**Link:** https://quynhaqbim-lab.github.io/tkb-gia-dinh/

**Thư mục máy này:** `D:\02.WIP\2025\NEW API 2025\12.Lich Gia Dinh`

## Cách cập nhật lịch

Nguồn đúng là file `data.json` trong repo. Pages không tự ghi khi gõ trên web.

1. Sửa `data.json` (hoặc điền trên trang rồi bấm **Tải data.json** và ghi đè file này).
2. Trong thư mục project:

```text
git add data.json
git commit -m "Cap nhat lich tuan"
git push
```

3. Đợi ~1 phút, mở lại link (refresh mạnh nếu còn bản cũ).

Khóa ô: `"YYYY-MM-DD|sang"` hoặc `"YYYY-MM-DD|chieu"`. Ví dụ:

```json
{
  "v": 1,
  "data": {
    "chung": {
      "2026-09-08|sang": "Họp gia đình"
    },
    "tue-lam": {},
    "tri-lam": {}
  }
}
```

Repo **public** — đừng ghi thông tin nhạy cảm.
