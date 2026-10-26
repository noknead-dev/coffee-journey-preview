# Coffee Journey Preview 1.5.3 OCR Inference

Fix từ logic OCR v0.9.5:
- reset toàn bộ form ngay khi chọn ảnh mới và trước khi parse OCR
- suy luận `SL28` -> giống, `Nyeri` -> vùng, `Light Roast` -> mức rang, `Washed Process` -> sơ chế
- ưu tiên tên Latin, tránh chọn dòng chữ CJK làm tên khi có tên Latin rõ hơn
- nhà rang chỉ điền khi có nhãn `Roaster`, `Roasted by` hoặc `Roastery`; không đoán
- trường không nhận diện được để trống / Chưa xác định
- mở được văn bản OCR thô để kiểm tra

Giữ nguyên `OCR_SPACE_API_KEY` trên Vercel. Upload đè toàn bộ project Preview rồi redeploy.
