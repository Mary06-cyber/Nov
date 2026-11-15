# Hướng dẫn toàn trình Binance (tháng 11/2026): Xác minh, nạp tiền, giao dịch, rút tiền — một đường đi hết

> Bài này viết theo đúng thứ tự bạn sẽ dùng thật: đăng ký & xác minh → nạp tiền → giao dịch → rút tiền. Bốn giai đoạn, mỗi giai đoạn chỉ nói những việc bắt buộc và chỗ dễ sai nhất. Làm đến đâu xác minh đến đó, đi hết đường này bạn đã là người dùng Binance tự vận hành được.

**🎁 Ưu đãi đăng ký Binance**

- Mã giới thiệu: `BNOFFICIAL`
- Link đăng ký: https://www.binance.com/join?ref=BNOFFICIAL
- Ưu đãi chính: Hoàn phí 40% cả phí giao dịch spot và hợp đồng

## Giai đoạn 1: Đăng ký và xác minh

**1. Đăng ký có mã**

Vào qua https://www.binance.com/join?ref=BNOFFICIAL, hoặc tự điền `BNOFFICIAL` lúc đăng ký. Đối chiếu từng chữ trước khi gửi — tài khoản tạo xong thì về cơ bản không thể gắn mã lại sau, và toàn bộ quyền hoàn phí 40% phí spot lẫn hợp đồng phụ thuộc vào bước này.

**2. Xác minh email và số điện thoại**

Làm theo hướng dẫn để xác minh email và số điện thoại. Nên dùng email chính thường xuyên sử dụng và số điện thoại giữ lâu dài — hai thứ này là mạng sống để khôi phục tài khoản.

**3. Xác minh danh tính KYC**

Đường đi: Trang cá nhân - Xác minh. CMND/CCCD hoặc hộ chiếu đều được. Ảnh giấy tờ phải đủ 4 góc, không loá, trang thông tin hiển thị đầy đủ. Làm nhận diện khuôn mặt ở nơi đủ sáng — tỷ lệ qua một lần cao hơn hẳn. Cấp xác minh càng cao, hạn mức rút tiền sau này càng lớn.

**4. Bật Google Authenticator**

Gắn Google Authenticator trong cài đặt bảo mật — đây là ổ khóa quan trọng nhất chống đánh cắp tài khoản. Gắn xong chép mã dự phòng ra giấy; đổi điện thoại sẽ cần đến nó.

> ⚠️ Lỗi hay mắc: đừng làm KYC hay gắn bảo mật qua WiFi công cộng. Bảo mật tài khoản bắt đầu từ môi trường.

## Giai đoạn 2: Nạp tiền

**1. Ưu tiên chuyển stablecoin trên chuỗi**

Cách phổ biến nhất là chuyển USDT từ nền tảng hoặc ví khác sang. Trước khi nạp, chọn đồng coin trong "Tài sản - Nạp tiền" và tạo địa chỉ nạp.

**2. Chọn mạng là ranh giới sống còn**

USDT nạp được qua nhiều mạng (TRC20, ERC20...). Quy tắc mấu chốt: mạng rút tiền của nền tảng gửi phải khớp tuyệt đối với mạng hiển thị trên địa chỉ nạp của Binance. Chọn sai mạng, tài sản có thể mất vĩnh viễn — nguồn gây mất tiền lớn nhất của người mới.

**3. Lần đầu thử với金额 nhỏ trước**

Lần nạp đầu tiên nên chuyển 10-20 USDT, xác nhận đã về rồi mới chuyển số lớn. Tốn thêm một phút, tránh tổn thất không thể hoàn tác.

**4. Đừng bỏ qua xác nhận đến tiền**

Chuyển trên chuỗi thường về trong vài phút (TRC20 nhanh). Chưa thấy tiền đừng hoảng: lấy TxID trong bản ghi rút tiền của nền tảng gửi, tra trạng thái trên trình khám phá blockchain là biết ngay.

> ⚠️ Lỗi hay mắc: một số coin (như XRP, EOS) chuyển tiền bắt buộc phải điền Memo/nhãn — thiếu sẽ khó đến tiền. Với các coin này, địa chỉ và memo thiếu một cái là không được.

## Giai đoạn 3: Giao dịch

**1. Chạy thông lệnh spot đầu tiên**

Vào "Giao dịch - Spot", chọn một cặp coin lớn (ví dụ BTC/USDT). Tập với lệnh limit: nhập giá và số lượng, đặt lệnh → chờ khớp → xem trong lịch sử lệnh. Lệnh limit giúp bạn kiểm soát giá — hợp để luyện tập hơn lệnh thị trường.

**2. Khi nào dùng lệnh thị trường**

Cần khớp ngay thì dùng lệnh thị trường — nhưng biết rõ nó khớp theo sổ lệnh hiện tại, biến động mạnh có thể trượt giá. Giai đoạn vốn nhỏ tập sự, nên dùng lệnh limit là chủ yếu.

**3. Ba kỷ luật khi chơi hợp đồng**

Định chơi hợp đồng thì nhớ ba điều: đòn bẩy bắt đầu từ mức nhỏ; trước khi đặt mọi lệnh phải nghĩ sẵn điểm cắt lỗ; tháng đầu dùng vị thế nhỏ để luyện quy trình, đừng vào nặng ngay từ đầu.

**4. Đừng quên hoàn phí 40% của bạn**

Phí bị trừ theo tỷ lệ tiêu chuẩn, hoàn phí 40% tự động cộng lại theo chu kỳ — thấy bản ghi phí nguyên giá đừng hoảng. Mỗi khoản hoàn đều xem được trong "Tài sản - Lịch sử giao dịch"; nên đối chiếu hàng tháng.

> 💡 Cái này là điểm cộng chứ không phải lỗi: trả phí spot bằng BNB được giảm 25% — vào "Trung tâm tài khoản - Cài đặt phí" tích bật lên. Nó cộng gộp với hoàn phí 40%, bật được thì bật.

## Giai đoạn 4: Rút tiền

**1. Thêm danh sách trắng rút tiền trước**

Bật danh sách trắng địa chỉ rút trong cài đặt bảo mật, thêm các địa chỉ hay dùng. Trước khi danh sách trắng có hiệu lực có 24 giờ bảo vệ — kể cả tài khoản bị đánh cắp cũng không chuyển nổi tiền ra ngoài.

**2. Rút tiền bốn bước**

Đường đi: "Tài sản - Rút tiền" → chọn coin → dán địa chỉ nhận → chọn mạng → nhập số lượng và mã xác minh. Bước chọn mạng là chết người nhất, giống như lúc nạp: mạng rút phải khớp với mạng của địa chỉ nhận.

**3. Rút lớn thì thử trước**

Lần đầu rút về một địa chỉ mới, chuyển số nhỏ xác nhận đã về rồi mới chuyển phần còn lại. Hai lần phí là cái giá đáng trả cho sự an toàn.

**4. Lưu lại bản ghi rút tiền**

Sau mỗi lần rút thành công, lưu TxID. Nếu có bất thường, đây là bằng chứng duy nhất để khiếu nại và truy vết.

> ⚠️ Lỗi hay mắc: sau khi rút tiền hoặc đổi cài đặt bảo mật, tài khoản vào giai đoạn bảo vệ, rút tiền có thể bị hạn chế — đừng đợi đúng ngày cần gấp tiền mới đi sửa đổi lớn.

## Checklist toàn trình

- [ ] Đăng ký qua https://www.binance.com/join?ref=BNOFFICIAL, đối chiếu mã `BNOFFICIAL` chuẩn từng chữ
- [ ] Xác minh email + số điện thoại hoàn tất
- [ ] Xác minh danh tính KYC đã qua
- [ ] Google Authenticator đã gắn, mã dự phòng chép ra giấy
- [ ] Lần nạp đầu đã thử số nhỏ rồi mới chuyển lớn
- [ ] Mỗi lần chuyển đều đối chiếu mạng chuyển với mạng địa chỉ
- [ ] Khấu trừ phí BNB đã bật trong cài đặt phí
- [ ] Danh sách trắng địa chỉ rút đã cài
- [ ] Hàng tháng đối chiếu hoàn phí trong lịch sử giao dịch

---

*Bài viết tổng hợp từ quy tắc công khai của Binance tính đến tháng 11/2026. Đường dẫn chức năng cụ thể và quy tắc hoàn phí theo trang hiển thị thời gian thực trên trang chính thức.*
