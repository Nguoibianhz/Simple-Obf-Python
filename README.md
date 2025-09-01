cat > README.md << 'EOF'
# 🐍 Simple Python Obfuscator

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-research--only-red.svg)
![Owner](https://img.shields.io/badge/owner-HieuDz-blue.svg)

---

## ⚠️ CẢNH BÁO QUAN TRỌNG

- 🚫 Công cụ này chỉ phục vụ **học tập, nghiên cứu, và thử nghiệm cá nhân**.  
- 🚫 Không sử dụng để:
  - Phát tán mã độc hoặc gây hại cho người khác.  
  - Vi phạm pháp luật, điều khoản của bất kỳ nền tảng nào.  
- 🛑 **Tác giả không chịu trách nhiệm** cho mọi hành vi lạm dụng.

---

## 🎯 Giới thiệu

**Simple-Obf-Python** là một công cụ đơn giản để obfuscate (làm rối mã nguồn) file Python.  

- 🔒 Ẩn code gốc, gây khó khăn cho việc đọc/hiểu.  
- 🧩 Dễ sử dụng, chạy trực tiếp bằng Python.  
- 📂 Xuất file Python đã obfuscate sẵn sàng chạy.

---

## ⚡ Setup

Yêu cầu: **Python 3.8+**

\`\`\`bash
# Clone repo
git clone https://github.com/Nguoibianhz/Simple-Obf-Python.git
cd Simple-Obf-Python
\`\`\`

Cài thư viện cần thiết:

\`\`\`bash
pip install pystyle
\`\`\`

---

## 🚀 Cách dùng

\`\`\`bash
python3 simple_obf.py
\`\`\`

Nhập tên file Python bạn muốn obfuscate (ví dụ: `demo.py`).  

File kết quả sẽ lưu thành:

\`\`\`
obf-demo.py
\`\`\`

---

## 📂 File cấu trúc

- \`simple_obf.py\` → Script chính để obfuscate.  
- \`demo.py\` → File test (do bạn chuẩn bị).  
- \`obf-demo.py\` → File sau khi obfuscate.  

---

## 📜 License & Bản quyền

Phát hành theo giấy phép **MIT License** — *For Educational Purposes Only*.  

© 2025 **Nguyễn Mạnh Hiếu (HieuDz)** — Chủ sở hữu repository này.  

> Nếu bạn sử dụng lại code hoặc chỉnh sửa để chia sẻ công khai, **hãy ghi rõ tên tác giả: Nguyễn Mạnh Hiếu (HieuDz)** trong code hoặc README.  
EOF
