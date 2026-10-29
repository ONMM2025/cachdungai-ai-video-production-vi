# Sản xuất video AI từ brief

Lập quy trình sản xuất video AI từ ý tưởng đến bản nháp nhiều cảnh, có kịch bản, shot list, prompt và checklist duyệt.

## Skill này giúp gì?

Skill điều phối quy trình video có nhiều cảnh: từ mục tiêu truyền thông đến kịch bản, storyboard, prompt tạo tài nguyên, phương án âm thanh, dựng nháp và bàn giao. Skill giúp Agent giữ nhân vật, không gian, thông điệp và nhịp kể nhất quán qua từng cảnh; nó không hứa tự tạo hay xuất video nếu phiên làm việc không có công cụ phù hợp.

## Nội dung gói

- `SKILL.md`: quy trình chi tiết, đầu vào, đầu ra và tiêu chí tự kiểm tra.
- `README.md`: hướng dẫn cài và prompt bắt đầu.
- `LICENSE`: giấy phép MIT.

## Cách cài và dùng

1. Tải ZIP rồi giải nén; giữ nguyên thư mục có `SKILL.md`.
2. Mở phần Skills/Agent Skills của ứng dụng AI đang dùng và thêm thư mục hoặc tải gói theo hướng dẫn trong ứng dụng. Nếu ứng dụng chưa hỗ trợ nạp skill, dán nội dung `SKILL.md` vào chỉ dẫn của một cuộc trò chuyện/dự án và dùng prompt mẫu bên dưới.
3. Bắt đầu cuộc trò chuyện bằng mục tiêu, người xem, nền tảng, giới hạn và tệp tham chiếu bạn có quyền sử dụng. Không gửi mật khẩu, mã xác minh, token hoặc dữ liệu khách hàng không cần thiết.
4. Đọc phần **Giả định** và **Cần người dùng duyệt**. Kiểm tra kỹ quyền dùng tài nguyên, dữ liệu, giá và quy định hiện hành trước khi tạo tệp tốn phí hoặc đăng công khai.
5. Lặp lại bằng cách nêu một thay đổi cụ thể; yêu cầu Agent giữ nguyên những phần đã duyệt.

Cách nạp skill khác nhau giữa ứng dụng và tài khoản. Hãy làm theo giao diện hiện hành của ChatGPT, Claude hoặc Agent khác; đừng giả định một nút cài đặt giống nhau có ở mọi gói.

## Prompt bắt đầu

> Từ brief dưới đây, hãy tạo một video dọc 35 giây giải thích [chủ đề] cho [nhóm xem]. Hãy hỏi tối đa 5 câu nếu thiếu dữ liệu ảnh hưởng đến nội dung hoặc chi phí. Trả về lời hứa, kịch bản tính theo thời lượng, shot list 6–9 cảnh, prompt độc lập cho từng cảnh, quy tắc giữ nhân vật nhất quán và checklist duyệt; ghi rõ giả định và không bịa dữ kiện.

## Tác giả và watermark

Biên soạn: [cachdungai.blog](https://cachdungai.blog/)

Gói được phân phối miễn phí theo điều khoản trong `LICENSE`. Kết quả tạo media có thể cần công cụ, tài khoản hoặc chi phí riêng; hãy duyệt đầu ra trước khi dùng công khai.
