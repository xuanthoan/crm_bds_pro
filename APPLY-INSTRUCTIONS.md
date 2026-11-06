# APPLY INSTRUCTIONS

## 1. Giải nén

Giải nén ZIP vào thư mục workspace. Kết quả mong đợi:

```text
G:\WorkSpace\Tool\crm_bds_pro\README.md
G:\WorkSpace\Tool\crm_bds_pro\.skills\...
G:\WorkSpace\Tool\crm_bds_pro\docs\...
```

## 2. Không trộn với dự án khác

- Không copy đè lên repository `crm_bds_pro`.
- Không giữ đồng thời tài liệu mang tên sản phẩm khác trong mandatory reading.
- Không mang code, migration, API hoặc database schema từ hệ thống khác vào dự án Greenfield nếu chưa có approved import scope.

## 3. Hành động đầu tiên

Mở `GOOSE-START-PROMPT.md`, giao nguyên prompt cho Goose từ repository root.

## 4. Gate

Không giao Opencode code business trước khi:

- Sprint 0 Acceptance Report = PASS.
- Sprint 1 ACTIVE.
- Relevant Context Pack accepted cho scope.
- Open decisions ảnh hưởng task đã đóng hoặc được waiver.
