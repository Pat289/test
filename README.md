# Quick Start (GitHub Pages + Jekyll)

1) สร้าง repo ใหม่บน GitHub ชื่ออะไรก็ได้
2) อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้น repo
3) ไปที่ Settings → Pages → Source: Deploy from a branch → เลือก `main` และ `/ (root)` → Save
4) เปิด URL ที่ปรากฏใต้หัวข้อ Pages

## เพิ่มบทความใหม่
- สร้างไฟล์ใน `_posts/` ชื่อรูปแบบ `YYYY-MM-DD-ชื่อเรื่อง.md`
- เติมส่วนหัว YAML เช่น:
```
---
layout: post
title: "ชื่อบทความ"
date: 2025-09-09 12:00:00 +0700
categories: blog
---
```
- เขียนเนื้อหา markdown ด้านล่าง

## ฝังวิดีโอ
- ใช้โค้ด `<iframe ...>` ของ YouTube แล้วแปะในไฟล์ Markdown ได้เลย
- หรือสร้างเพจรวมวิดีโอที่ `videos.md`

> ธีมเริ่มต้นคือ `minima` ของ GitHub Pages