# TLT Bios Edit Tool — kênh cập nhật

Repo này chỉ phục vụ **tự cập nhật** cho TLT Bios Edit Tool:

- `version.json` — manifest bản mới nhất (phiên bản, link tải, SHA-256, chữ ký Ed25519).
- **Releases** — file `Bios_Edit_Tool.exe` (và file phụ nếu có) của từng phiên bản.

Tool đang chạy trên máy người dùng sẽ tự đọc `version.json`, xác minh chữ ký, rồi tải
và thay bản mới. Mã nguồn tool **không** nằm ở đây.
