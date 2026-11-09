1\. Mẫu Prompt 3 thành phần nhờ AI giải thích:  
"Tôi đang đẩy code lên GitHub bằng Terminal thì gặp lỗi: error: open(".git/FETCH\_HEAD"): Permission denied. Hãy đóng vai một lập trình viên senior, giải thích nguyên nhân lỗi này một cách bình dân, ngắn gọn nhất cho người mới và đưa ra hướng dẫn cách sửa."  
2\. Hướng dẫn thực hiện và chụp ảnh "Run as Administrator":  
Thao tác: Tắt Terminal hiện tại, click chuột phải vào icon phần mềm Terminal (hoặc Git Bash/VS Code) $\rightarrow$ Chọn Run as Administrator $\rightarrow$ Chạy lại lệnh git.  
Tiêu chuẩn chụp ảnh: Chụp lại cửa sổ lỗi, dùng công cụ (Snipping tool/Lightshot) khoanh vùng viền đỏ vào đúng dòng chữ error: ... Permission denied. Bắt buộc phải làm mờ/bôi đen tên User hoặc đường dẫn máy tính cá nhân để bảo mật thông tin.  
3\. Mẫu tin nhắn Bug Report gửi giảng viên (Nếu cách trên thất bại):  
Context: Dạ chào thầy/cô, em đang tiến hành push code lên GitHub. Em đã thử mở Terminal bằng quyền Run as Administrator và chạy lại lệnh nhưng vẫn không thành công.  
Expected: Lệnh thực thi thành công và code được đẩy lên repository.  
Actual: Terminal từ chối quyền thao tác với file hệ thống của git nên quá trình bị gián đoạn.  
Log: Màn hình trả về mã lỗi error: open(".git/FETCH\_HEAD"): Permission denied. Dạ em có đính kèm ảnh màn hình chi tiết lỗi bên dưới, nhờ thầy/cô xem giúp em ạ.  
