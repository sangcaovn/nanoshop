# nanoShop
Đây mà 1 phiên bản rút gọn của 1 hệ thống eCommerce

# Một số lưu ý
* Đây là bài tập cá nhân 
* Không được hỏi các bạn fresher khoá trước.
* Tuy nhiên các bạn có thể copy bài của người khác và implement theo cách hiểu của mình (Không được copy nếu không hiểu)
* Luôn luôn khuyến khích các bạn đặt câu hỏi với trainer và hỏi các bạn khác.
* Các bạn được tự do thiết kế DB tuy nhiên phải đảm bảo input và ouput trong swagger 

#  Một số yêu cầu
* Dev cần phải viết 1 Python Decorator cho chức năng xác thực tài khoản
* Id trong hệ thống sẽ sử dụng UUID thay vì một số nguyên tăng dần
* Hệ thống sẽ sử dụng JWT để tạo token và xác thực (nếu không biết JWT là gì thì đừng ngại hỏi)
* Cart sau khi checkout sẽ chuyển đổi thành Order với giá trị giữ nguyên. Sau khi chuyển đổi, cart sẽ bị xoá khỏi DB
* Trong order có thuộc tính payment_status: mặc định lúc checkout xong payment status sẽ là INIT
* Các thao tác như cart/add, cart-item/changeQty cart-item/remove sẽ làm thay đổi cart do đó cần tính toán lại các giá trị SubTotal-Ex-Tax, Tax, Total của cart