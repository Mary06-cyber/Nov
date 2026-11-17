# Hướng dẫn đăng ký Bybit hoàn phí (tháng 11/2026): Kế hoạch hành động 7 ngày để thực sự nhận 50% hoàn phí

Hầu hết các bài hướng dẫn chỉ dạy bạn "đăng ký, nhập mã, xong". Nhưng đăng ký thành công ≠ hoàn phí có hiệu lực, và hoàn phí có hiệu lực ≠ bạn thực sự tiết kiệm được tiền.

Bài này viết theo hướng khác: một kế hoạch hành động 7 ngày, mỗi ngày 10~20 phút, mỗi ngày hoàn thành một việc, cuối cùng tính cho bạn từng con số một. Làm theo, sau 7 ngày bạn sẽ có ba thứ: một tài khoản đã gắn hoàn phí, một bộ thiết lập bảo mật vững chắc, và một sổ ghi chép phí mà bạn tự đọc được.

## Nhận quyền lợi trước đã

- Mã mời: **BYOFFICIAL**
- Link đăng ký: **https://partner.bybit.com/b/BYOFFICIAL**
- Quyền lợi: Đăng ký bằng BYOFFICIAL để nhận **hoàn tới 50% phí giao dịch**

50% là một trong những mức hoàn phí cao nhất mà các sàn lớn đang đưa ra. Nhưng nó chỉ có hiệu lực khi bạn được gắn mã ngay lúc đăng ký — Bybit về cơ bản không có kênh gắn mã mời sau khi tài khoản đã tạo. Vì vậy Ngày 1 phải làm đúng: làm sai thì tạo lại bằng email mới trong khi tài khoản còn trống.

## Ngày 1: Đăng ký + Gắn mã (bước duy nhất không thể đảo ngược)

- Vào trang đăng ký qua link partner ở trên, chọn đăng ký bằng email. Đăng ký qua link mời sẽ tự động gắn quan hệ giới thiệu — không cần nhập mã thủ công. Nếu trang có ô nhập mã mời, nhập **BYOFFICIAL** để phòng hưu.
- Dùng một email chuyên biệt, không dùng email chính thường ngày. Email của tài khoản sàn là mục tiêu bị tấn công hàng đầu — hãy cách ly nó.
- Việc đầu tiên sau khi đăng ký: biểu tượng hồ sơ → "My Referrals" (Giới thiệu của tôi), xác nhận thông tin người giới thiệu đã hiển thị. **Không hiển thị nghĩa là chưa gắn được.** Lúc này tài khoản còn trống, tạo lại bằng email mới không tốn gì cả; phát hiện sau khi đã nạp tiền thì bạn sẽ phải trả phí nguyên giá mãi mãi.

## Ngày 2: Bộ ba bảo mật

- **Google Authenticator (2FA)**: bắt buộc bật. Đừng dùng SMS làm lớp phòng thủ duy nhất — tấn công đánh cắp SIM sinh ra chính là để đánh vào điểm này.
- **Mật khẩu tiền (fund password)**: đặt riêng, khác mật khẩu đăng nhập. Rút tiền và tạo API key sẽ cần đến nó.
- **Mã chống lừa đảo (Anti-phishing Code)**: tự đặt một mã trong thiết lập bảo mật. Sau đó mọi email chính thức của Bybit đều kèm mã này. Email "chính thức" nào không có mã — xử lý là phishing.

Bộ ba này làm hết trong 15 phút. Xong là tài khoản của bạn đã an toàn hơn phần lớn người dùng.

## Ngày 3: KYC + Lần nạp tiền đầu tiên

- KYC cấp cơ bản là đủ cho giao dịch hàng ngày. Chụp giấy tờ đủ sáng, không bị chói, một lần là qua.
- Hai đường nạp tiền: nạp on-chain, hoặc mua USDT qua P2P.
- **Bẫy khi nạp on-chain**: nhìn kỹ mạng. Nạp USDT nên chọn TRC20 — phí chỉ khoảng 1 USDT; chọn nhầm ERC20 có thể mất vài chục USDT.
- **Lỗi chết người là sai mạng** — chuyển token mạng ERC20 vào địa chỉ TRC20 có thể mất tài sản vĩnh viễn. Trước mỗi lần nạp, kiểm tra cả địa chỉ lẫn mạng, và nạp thử một khoản nhỏ trước khi nạp lớn.

## Ngày 4: Lệnh giao dịch Spot đầu tiên (và học cách đọc phí)

- Lệnh đầu đừng all-in — 100~200 USDT là đủ. Mục tiêu là hiểu quy trình và cấu trúc phí.
- **Dùng lệnh limit, đừng dùng lệnh market.** Lệnh market trả phí Taker (0,1% trên spot); đặt lệnh limit khớp lệnh thì bạn là Maker. Cộng với hoàn phí 50%, phí Taker thực tế còn 0,05%, Maker còn thấp hơn nữa.
- Sau khi khớp lệnh, vào "Tài sản → lịch sử giao dịch" xem phí bị trừ bao nhiêu — bạn sẽ cần con số này vào Ngày 6.

## Ngày 5: Lệnh Futures đầu tiên (ngày người mới dễ cháy tài khoản nhất)

- Đòn bẩy tối đa 3~5x, vị thế không quá 10% vốn. Futures để luyện tập, không phải để đánh bạc.
- **Cơ chế "giới hạn rủi ro" (risk limit) của Bybit — điều các bài khác hiếm khi nói**: vị thế càng lớn, yêu cầu ký quỹ ban đầu và ký quỹ duy trì càng cao. Nghĩa là cùng đòn bẩy 10x, vị thế mở lớn hơn sẽ đẩy giá thanh lý lại gần bạn hơn. Người mới nên giữ risk limit ở mức thấp nhất.
- **Thanh lý dựa trên giá mark price, không phải giá giao dịch gần nhất.** Khi thị trường dao động mạnh, giá gần nhất có thể nháy một cây nến nhọn, nhưng miễn giá mark chưa chạm giá thanh lý, vị thế của bạn vẫn sống. Biết điều này giúp bạn đỡ bị dập lệnh vì mỗi cái wick.
- Quyết định chế độ vị thế rõ ràng: người mới nên chọn one-way mode — logic đơn giản, ít tự làm rối mình.

## Ngày 6: Ngày đối chiếu sổ sách (hoàn phí đã về chưa?)

- Hoàn phí giao dịch của Bybit thường về theo chu kỳ T+1 — ghi có vào tài khoản funding vào ngày hôm sau.
- Nơi kiểm tra: "Tài sản" → bản ghi hoàn phí/khuyến thưởng, mỗi khoản hoàn đều hiển thị số tiền và thời gian. Từ lúc đăng ký đến khoản hoàn đầu tiên thường không quá 48 giờ.
- Tính một phép toán cho bạn xem: giả sử trong một tháng bạn giao dịch 50.000 USDT spot theo lệnh Taker (phí 0,1% = 50 USDT) và 50.000 USDT futures theo lệnh Taker (phí 0,055% ≈ 27,5 USDT). Tổng phí: 77,5 USDT. Hoàn phí 50% mang lại khoảng **38,75 USDT/tháng** — tương đương **khoảng 465 USDT/năm**. Khối lượng càng lớn, đường số này càng dốc.

## Ngày 7: Nâng cấp (con đường giảm phí thứ hai ngoài hoàn phí)

- Một sự thật quan trọng: **Bybit không có token nền tảng để giảm phí giao dịch** — không có gì giống BNB của Binance hay OKB của OKX. Trên Binance bạn còn có thể giảm thêm bằng cách giữ BNB; trên Bybit con đường đó không tồn tại. Vì vậy "hoàn phí qua mã mời + hạng VIP" chính là hai đòn bẩy giảm phí duy nhất của bạn. Đừng lãng phí cả hai.
- Hạng VIP nâng cấp theo tài sản và khối lượng giao dịch. Khi khối lượng tăng lên, nhớ đối chiếu biểu phí với hạng của mình.
- Nhận luôn phần thưởng nhiệm vụ người mới trong "Rewards Hub" — đó là thu nhập thêm bên cạnh hoàn phí.
- Cuối cùng, phân tầng tài sản: phần nắm giữ dài hạn chuyển sang ví lạnh hoặc tài khoản chính, trên sàn chỉ giữ tiền dành cho giao dịch. Sàn giao dịch là chiến trường, không phải két sắt.

## Danh sách kiểm tra 7 ngày

- Ngày 1: Đã xác nhận gắn mã mời và hiển thị ✅
- Ngày 2: 2FA + mật khẩu tiền + mã chống lừa đảo đều đã bật ✅
- Ngày 3: KYC được duyệt + nạp thử khoản nhỏ thành công ✅
- Ngày 4: Lệnh spot đầu tiên đã khớp, đã xem lịch sử phí ✅
- Ngày 5: Lệnh futures đầu tiên với số vốn nhỏ, đòn bẩy ≤ 5x, risk limit thấp nhất ✅
- Ngày 6: Khoản hoàn phí đầu tiên hiện trong bản ghi ✅
- Ngày 7: Đã nhận thưởng người mới + phân tầng tài sản ✅

Đủ 7 dấu tick là tài khoản chính thức đưa vào sử dụng. Sau này, trước mỗi giao dịch lớn chỉ cần nhìn lại danh sách này.

## Miễn trừ trách nhiệm

Bài viết chỉ nhằm mục đích chia sẻ thông tin, không phải lời khuyên đầu tư. Tài sản mã hóa biến động mạnh, giao dịch futures có thể dẫn đến mất toàn bộ vốn. Hãy tự đánh giá mức độ chấp nhận rủi ro và tham gia có trách nhiệm.
