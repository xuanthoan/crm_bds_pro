# CRM_BDS_PRO — COMPLETE DOCUMENTATION FOUNDATION PACK

**Package version:** `1.0.0`  
**Generated:** `2026-08-05`  
**Purpose:** Bộ tài liệu Greenfield để Goose thực hiện Sprint 0, kích hoạt Sprint 1 và điều phối Opencode xây `crm_bds_pro` từ repository trống.

## Phạm vi

Gói này cung cấp Product, Architecture, ADR, Engineering, Security, Design, Context Packs, Operations, Runbooks, Sprint Packs, Agent prompts và machine-contract templates.

Gói này **không phải application source code** và không chứng minh CRM đã chạy. Trình tự bắt buộc:

```text
Giải nén
→ Goose đọc README.md và .skills/
→ Sprint 0 Readiness Audit
→ đóng blockers/open decisions cần thiết
→ Sprint 0 Acceptance Report = PASS
→ kích hoạt Sprint 1
→ Opencode bootstrap repository
→ chạy CI/health/contracts/migrations
→ chỉ code business Context khi Context Readiness Gate PASS
```

## Entry point

```text
crm_bds_pro/README.md
```

Không tạo thêm README entry point cạnh tranh trong thư mục tài liệu.
