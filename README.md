# ops-portal-demo

ERP_SMES Demo: bản demo portal quản lý vận hành nội bộ cho team doanh nghiệp vừa và nhỏ: giao việc, duyệt yêu cầu, theo dõi thanh toán nhà cung cấp và xem báo cáo tiến độ ở một nơi.

Repo này công khai nên chỉ chứa bản demo với dữ liệu mẫu. Proposal và báo giá nằm ở repo riêng tư `claude-workspace` (thư mục `docs/ops-portal/`).

## Cấu trúc

```
ops-portal-demo/
├── demo/            Bản demo v2 bấm được, chỉ dùng dữ liệu mẫu
│   └── portal/      Bản demo giao diện portal đầy đủ hơn (Tổng quan, Sự kiện, Công việc, Ngân sách, Tài liệu)
└── .github/    Tự động đưa thư mục demo/ lên GitHub Pages
```

## Chạy thử trên máy

Mở `demo/index.html` bằng trình duyệt. Không cần cài đặt gì.

## Đưa demo lên đường link

1. Vào **Settings → Pages** của repo, chọn **Source: GitHub Actions**.
2. Mỗi lần đẩy thay đổi lên nhánh `main`, workflow trong `.github/workflows/pages.yml` sẽ tự cập nhật trang.

Gói GitHub miễn phí chạy Pages với repo công khai, vì vậy repo này giữ công khai và không chứa gì ngoài demo.

## Lưu ý

- Repo công khai: ai có link cũng xem được. Không đưa báo giá, tên khách, số liệu hay quy trình thật của công ty vào đây.
- Dữ liệu trong demo hoàn toàn là dữ liệu giả.
- Không commit mật khẩu hoặc API key.
- Dự án cá nhân nên tách khỏi tài liệu và dữ liệu của công ty đang làm.
