# MIC Exam Lab

เว็บเตรียมสอบ MIC321 / MIC322 / MIC332 / MIC391 / MIC392 (ไฟล์เดียว `index.html` ไม่ต้อง build)

## ขึ้นเว็บ
- **GitHub Pages:** Settings → Pages → Source: *GitHub Actions* (workflow อยู่ใน `.github/workflows/pages.yml`)
- **Cloudflare Pages:** Workers & Pages → Create → Connect to Git → เลือก repo นี้
  Framework preset: None · Build command: (ว่าง) · Output directory: `/`

## อัปเดต
แก้ `index.html` แล้ว commit ระบบจะ deploy เอง
