# Perfect IELTS Listening Dictation Vol.1 — Website & HTML Presentations

## Cấu trúc thư mục
- `index.html`: Trang chủ điều hướng toàn bộ 3 Unit và 11 chuyên đề (1A -> 3C).
- `HTML_presentations/`:
  - `unit-1.html`: Bài thuyết trình Unit 1 — Letter (95 Slide câu hỏi: 1A, 1B, 1C, 1D).
  - `unit-2.html`: Bài thuyết trình Unit 2 — Number (125 Slide câu hỏi: 2A, 2B, 2C, 2D).
  - `unit-3.html`: Bài thuyết trình Unit 3 — Letter & Number (130 Slide câu hỏi: 3A, 3B, 3C).
  - `unit-1a-address.html` .. `unit-3c-date.html`: 11 bài thuyết trình riêng cho từng chuyên đề.
- `audio/`: Chứa 350 file MP3 đã cắt riêng cho từng câu hỏi (`1A_01.mp3` đến `3C_50.mp3`).

## Tính năng trên mỗi Slide câu hỏi
1. **Audio riêng từng câu**: Phát trực tiếp từ `audio/<Mã_câu>.mp3`, hỗ trợ chỉnh tốc độ `0.75x / 1.0x / 1.25x`, tua `-3s / +3s`, lặp lại, đọc hội thoại đa giọng (Web Speech API) và nhúng trình phát Google Drive gốc.
2. **Gợi ý đáp án 3 cấp độ**: Độ dài & khuôn mẫu ký tự -> Ký tự đầu/cuối & cảnh báo bẫy IELTS -> Trích dẫn câu thoại chứa đáp án.
3. **Chấm đáp án tự động**: Không phân biệt hoa/thường, chấp nhận các biến thể viết ngày/giờ/số chuẩn IELTS, so sánh sai lệch từng ký tự và mở khóa Tapescript song ngữ Anh - Việt.
4. **Tra từ vựng mới**: Thẻ từ vựng trọng tâm của câu hỏi (IPA, từ loại, nghĩa tiếng Việt, nút nghe phát âm) + Click vào bất kỳ từ tiếng Anh nào trên đề bài hoặc Tapescript để tra nghĩa tức thì.
