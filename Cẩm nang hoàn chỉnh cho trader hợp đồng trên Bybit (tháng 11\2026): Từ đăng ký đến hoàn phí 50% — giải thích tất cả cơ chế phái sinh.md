# Cẩm nang hoàn chỉnh cho trader hợp đồng trên Bybit (tháng 11/2026): Từ đăng ký đến hoàn phí 50% — giải thích tất cả cơ chế phái sinh

Bybit nổi lên nhờ phái sinh — đây là sân nhà của trader hợp đồng. Nhưng đa số bài hướng dẫn trên mạng chỉ dừng ở "cách đăng ký". Những cơ chế thực sự quyết định lãi lỗ — tài khoản giao dịch thống nhất (UTA), giới hạn rủi ro, funding rate, ADL — hầu như không ai giải thích kỹ.

Bài này gói gọn tất cả trong một: trước hết là đăng ký gắn hoàn phí (hoàn tới 50% phí giao dịch, một trong những mức cao nhất thị trường), sau đó lần lượt mổ xẻ biểu phí, cơ chế cốt lõi, bộ công cụ lệnh và logic thanh lý, khép lại bằng năm kiểu cháy tài khoản phổ biến nhất của trader hợp đồng. Đọc xong bài này, bạn hiểu Bybit sâu hơn 90% người dùng hợp đồng của sàn.

## Nhận quyền lợi trước đã

- Mã mời: **BYOFFICIAL**
- Link đăng ký: **https://partner.bybit.com/b/BYOFFICIAL**
- Quyền lợi: Đăng ký bằng BYOFFICIAL để nhận **hoàn tới 50% phí giao dịch**

## 1. Đăng ký và gắn hoàn phí (3 bước, phần duy nhất không thể đảo ngược)

1. Vào trang đăng ký qua link partner ở trên, đăng ký bằng email. Link mời sẽ tự động gắn quan hệ giới thiệu; nếu trang có ô nhập mã mời, nhập **BYOFFICIAL** để phòng hưu.
2. Dùng một email chuyên biệt, không dùng email chính thường ngày — email của tài khoản sàn là mục tiêu tấn công số một của hacker.
3. Xác nhận ngay sau khi đăng ký: biểu tượng hồ sơ → "My Referrals", xem thông tin người giới thiệu đã hiển thị chưa.

**Điểm mấu chốt**: Bybit không có kênh gắn mã mời sau khi tài khoản đã tạo. Nếu chưa gắn được, tài khoản còn trống — tạo lại bằng email mới không tốn gì cả. Phát hiện sau khi đã nạp tiền thì bạn sẽ trả phí mặc định mãi mãi.

## 2. Giải phẫu biểu phí của Bybit

Con số gốc trước đã (hạng người dùng thường):

- **Spot**: Maker 0,1% / Taker 0,1%
- **Hợp đồng perpetual USDT**: Maker 0,02% / Taker 0,055%

Ba sự thật đa số người không biết:

- **Phí hợp đồng thấp hơn phí spot rất nhiều.** Cùng khối lượng giao dịch, phí ở khu hợp đồng chỉ bằng khoảng một phần năm khu spot — bản thân nó đã là một tín hiệu tiết kiệm.
- **Bybit không có cơ chế giảm phí bằng token nền tảng.** Không có gì giống BNB của Binance hay OKB của OKX. Vì vậy "hoàn phí qua mã mời + hạng VIP" là hai đòn bẩy giảm phí duy nhất của bạn. Đừng lãng phí cả hai.
- **Hạng VIP nâng cấp theo khối lượng giao dịch 30 ngày và tài sản nắm giữ.** Khi khối lượng tăng lên, nhớ đối chiếu trang biểu phí với hạng thực tế của mình.

Khi hoàn phí 50% có hiệu lực, phí thực tế của bạn:

- Taker hợp đồng: 0,055% × 50% = **thực trả 0,0275%**
- Maker hợp đồng: 0,02% × 50% = **thực trả 0,01%**
- Taker spot: 0,1% × 50% = **thực trả 0,05%**

## 3. Hoàn phí thực sự tiết kiệm bao nhiêu: tính theo từng mức khối lượng

Khối lượng Taker hợp đồng, hoàn 50%, xem thẳng số liệu:

- **Khối lượng tháng 10.000 USDT**: phí 5,5 USDT → nhận lại 2,75 USDT/tháng → **33 USDT/năm**
- **Khối lượng tháng 50.000 USDT**: phí 27,5 USDT → nhận lại 13,75 USDT/tháng → **165 USDT/năm**
- **Khối lượng tháng 100.000 USDT**: phí 55 USDT → nhận lại 27,5 USDT/tháng → **330 USDT/năm**
- **Khối lượng tháng 500.000 USDT**: phí 275 USDT → nhận lại 137,5 USDT/tháng → **1.650 USDT/năm**

Nửa triệu USDT khối lượng tháng không phải mức quá lớn với trader hợp đồng — 1.650 USDT/năm hoàn phí là lợi nhuận ròng thẳng vào túi bạn. Đó chính là giá trị thật của việc gắn đúng mã ngay lúc đăng ký: không bắt bạn làm thêm gì, nhưng trả tiền cho bạn hàng tháng, liên tục.

## 4. Tài khoản giao dịch thống nhất (UTA): bật ngay từ đầu

UTA của Bybit gộp spot, perpetual USDT và hợp đồng coin-margined vào một tài khoản duy nhất với ký quỹ dùng chung:

- **Hiệu suất vốn cao hơn**: tài sản spot có thể dùng trực tiếp làm ký quỹ hợp đồng — không cần chuyển giữa các tài khoản con.
- **Phòng ngừa rủi ro tự nhiên**: vị thế long spot và short hợp đồng trong cùng một tài khoản tự chống chéo nhau.
- **Người mới nên chọn UTA ngay lúc đăng ký**, đừng dùng mô hình cũ rồi chuyển đổi sau. Tiện hơn nhiều.

## 5. Năm cơ chế cốt lõi của hợp đồng (cháy tài khoản đều nằm ở đây)

**1. One-way hay hedge mode**

- One-way: một vị thế duy nhất; mở lệnh ngược chiều là phòng ngừa hoặc đóng vị thế.
- Hedge mode: đồng thời giữ hai vị thế long và short độc lập.
- Người mới dùng one-way — logic đơn giản. Hedge mode dành cho người chơi có chiến lược phòng ngừa bài bản.

**2. Cross margin hay isolated margin**

- Cross: toàn bộ ký quỹ tài khoản dùng chung; giá thanh lý xa hơn, nhưng cháy một lần có thể tổn thương toàn bộ số vốn.
- Isolated: mỗi vị thế một quỹ ký quỹ riêng; thanh lý chỉ mất tiền của vị thế đó.
- Khuyến nghị: dùng isolated hằng ngày để cô lập rủi ro. Đừng dùng cross để "gồng lỗ" — đây là quán quân bảng xếp hạng thanh lý.

**3. Giới hạn rủi ro (Risk Limit) — cơ chế đặc trưng của Bybit**

Vị thế càng lớn, yêu cầu ký quỹ ban đầu và ký quỹ duy trì càng cao, giá thanh lý càng gần. Cùng mức đòn bẩy, lên một bậc risk limit là không gian chịu đựng của bạn co lại. Người mới giữ bậc thấp nhất; nếu thật sự cần vị thế lớn, nhớ rằng nâng bậc sẽ kéo giá thanh lý lại gần giá vào lệnh.

**4. Giá mark price so với giá giao dịch gần nhất**

Thanh lý dựa trên **giá mark price** (trung bình có trọng số từ nhiều nguồn), không phải giá giao dịch gần nhất trên màn hình của bạn. Khi thị trường dao động dữ dội, giá gần nhất có thể nháy một cái wick kinh hoàng, nhưng miễn mark price chưa chạm đường thanh lý, vị thế vẫn sống. Hiểu điều này giúp bạn không xả hàng loạn vì wick giả.

**5. Funding rate và ADL**

- **Funding rate**: khoản phí định kỳ chuyển giữa phe long và phe short — đa số hợp đồng thanh toán mỗi 8 giờ, một số hợp đồng hoạt động mạnh là 4 giờ thậm chí 1 giờ. Funding dương thì phe long trả cho phe short. Với mọi chiến lược giữ lệnh dài, funding là chi phí ẩn: kiểm tra trước khi giữ.
- **ADL (auto-deleveraging)**: khi thị trường biến động cực đoan và bên đối ứng hết thanh khoản, hệ thống xếp hạng vị thế theo "lợi nhuận + đòn bẩy" và ép đóng một phần vị thế của bạn. Đó là cơ chế bảo vệ, nhưng nó phá vỡ chiến lược của bạn — vị thế lãi nhiều, đòn bẩy cao sẽ bị ADL đầu tiên khi thị trường sập. Đó là cái giá ẩn của đòn bẩy cao.

## 6. Bộ công cụ lệnh: bốn công cụ bắt buộc phải biết

- **Lệnh limit / market**: limit tiết kiệm phí (Maker), market mua tốc độ (Taker). Không gấp thì dùng limit.
- **Chốt lời cắt lỗ (TP/SL)**: gắn ngay khi mở vị thế, đừng đợi mở xong rồi bổ sung. Đó là kỷ luật, không phải tùy chọn.
- **Lệnh điều kiện (conditional)**: lệnh chỉ khớp khi giá chạm mức chỉ định — dùng cho chiến lược phá vỡ vùng giá.
- **Chỉ đóng vị thế (Reduce-only)**: khi tích chọn, lệnh chỉ được đóng vị thế, không mở vị thế mới — ngăn lệnh chốt lời lật thành mở vị thế ngược trong biến động cực đoan. Công tắc nhỏ này关键时刻 có thể cứu cả tài khoản.

## 7. Cách ước tính giá thanh lý (phiên bản đại chúng)

Ước tính thô (chưa gồm ký quỹ duy trì và phí): giá thanh lý nằm ở mức lỗ khoảng "1 ÷ đòn bẩy".

- Đòn bẩy 3x: thanh lý khi giá ngược chiều khoảng 32%
- Đòn bẩy 5x: khoảng 19%
- Đòn bẩy 10x: khoảng 9,5%
- Đòn bẩy 20x: khoảng 4,8% — một nhịp điều chỉnh bình thường là hết

Số liệu nói thay tất cả: **3~5x là vùng hợp lý cho người mới**; trên 10x là trao số phận cho biến động. Ngoài ra nhớ: giá thanh lý trôi theo mỗi lần bạn cộng vị thế và mỗi lần funding thanh toán. Phải tính lại trong khi giữ lệnh — không phải tính một lần dùng mãi.

## 8. Năm kiểu cháy tài khoản phổ biến nhất

1. **Bơm đòn bẩy tối đa**: tưởng hiệu suất vốn cao là thông minh. Thực tế là nuôi động cơ thanh lý của sàn.
2. **Phớt lờ funding rate**: giữ lệnh ba ngày, gọi đúng hướng mà vẫn lỗ — bị funding ăn hết. Xem funding hiện tại và chu kỳ thanh toán trước mỗi lần giữ lệnh.
3. **Gồng lỗ bằng cross margin**: dùng cross để đánh cược thị trường "sẽ quay về". Kết cục thường là tài khoản về 0 chứ không phải hòa vốn nhẹ nhõm.
4. **Chạy lệnh trần — không TP/SL**: mọi vị thế phải gắn TP/SL ngay khi vào lệnh. Lệnh trần nghĩa là "đến lúc tôi sẽ xử tay", mà đến lúc đó bạn chỉ còn biết hoảng.
5. **Bị wick quét out**: wick ở giá gần nhất không phải là thanh lý; mark price mới là trọng tài. Wick xảy ra thì xem mark price và giá thanh lý của mình trước, rồi mới ra động tác.

## 9. Bảo mật và đối chiếu sổ sách (bản 5 phút)

- Bộ ba bảo mật: Google Authenticator (2FA), mật khẩu tiền riêng biệt, mã chống lừa đảo. Mười lăm phút, bảo toàn giá trị hơn bất kỳ chiến lược nào.
- Đối chiếu hoàn phí: hoàn phí giao dịch của Bybit thường về **T+1**, xem tại "Tài sản" → bản ghi hoàn phí/khuyến thưởng. Từ đăng ký đến khoản hoàn đầu tiên thường không quá 48 giờ. Chọn một ngày cố định mỗi tháng để đối chiếu hoàn phí với khối lượng giao dịch.

## 10. Danh sách khởi động (đủ 10 dấu tick mới vào tiền thật)

- Đăng ký qua link BYOFFICIAL, xác nhận gắn mã trong My Referrals ✅
- 2FA + mật khẩu tiền + mã chống lừa đảo đều đã bật ✅
- KYC cấp cơ bản được duyệt ✅
- Bật UTA ngay từ lúc đăng ký ✅
- Nạp thử khoản nhỏ (mạng TRC20), kiểm tra địa chỉ + mạng ✅
- Đòn bẩy đặt 3~5x, risk limit giữ bậc thấp nhất ✅
- One-way mode + isolated margin ✅
- Mỗi lệnh đều gắn TP/SL ngay khi vào ✅
- Xem funding rate hiện tại trước mỗi lần giữ lệnh ✅
- Xác nhận khoản hoàn phí đầu tiên trong bản ghi sau T+1 ✅

Đủ 10 dấu tick, tài khoản này là một cỗ máy hợp đồng hoàn chỉnh, phí tối ưu, rủi ro được kiểm soát. Phần còn lại thuộc về chiến lược và kỷ luật của bạn.

## Miễn trừ trách nhiệm

Bài viết chỉ nhằm mục đích chia sẻ thông tin, không phải lời khuyên đầu tư. Tài sản mã hóa biến động mạnh, giao dịch hợp đồng có thể dẫn đến mất toàn bộ vốn. Hãy tự đánh giá mức độ chấp nhận rủi ro và tham gia có trách nhiệm.
