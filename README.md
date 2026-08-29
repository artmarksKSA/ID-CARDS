ضعي هنا: mohammad-bold-art-1.ttf

المسار الذي يقرأه index.html هو fonts/mohammad-bold-art-1.ttf بجانبه في المستودع.
أو أرفقي الملف ليُضمَّن base64 داخل index.html فلا تحتاجين مجلداً أصلاً.
بعد الوضع: python3 src/check_font.py fonts/mohammad-bold-art-1.ttf
ثم: python3 src/patch_idcards.py <index.html الأصلي> <مجلد المخرجات>
