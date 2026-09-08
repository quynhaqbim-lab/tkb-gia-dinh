# Thời Khóa Biểu Gia Đình

Lịch tuần (**Thóc** / **Su**, tab Lịch chung) trên **GitHub Pages**. Cả nhà mở **một link**; khi đổi lịch thì sửa dữ liệu rồi đẩy lại GitHub.

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

Lịch **lặp mỗi tuần**. Tab **Thóc** / **Su** theo giấy viết tay. Khóa ô: `t2|sang`, `t5|toi`, `cn|chieu`… Ví dụ:

```json
{
  "v": 2,
  "data": {
    "thoc": {
      "t2|sang": "7h45 → 17h10 → Ở trường"
    },
    "su": {
      "t2|chieu": "13h30 → 17h40 → Ở trường"
    }
  }
}
```

Repo **public** — đừng ghi thông tin nhạy cảm.
