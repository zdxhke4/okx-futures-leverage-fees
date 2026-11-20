# OKX Futures là gì: đòn bẩy tối đa bao nhiêu, phí tính thế nào, người mới có nên vào? (kèm bảng loại hợp đồng và bài tính chi phí giữ lệnh)

OKX Futures là mảng hợp đồng phái sinh của OKX: bạn dùng tiền ký quỹ để đặt cược vào hướng giá, không mua và không nắm giữ coin thật. Các cặp chủ lực có thanh khoản tốt nhất cho đòn bẩy tới 125x, phí cơ bản là 0,02% cho lệnh maker và 0,05% cho lệnh taker. CoinGecko đang theo dõi khoảng 555 cặp futures trên OKX, với khoảng 8,1 tỷ USD giá trị hợp đồng đang mở và 21 tỷ USD khối lượng giao dịch mỗi ngày.

Phần dưới đây nói rõ bốn thứ mà một bài giới thiệu chung thường bỏ qua: các loại hợp đồng OKX thực sự niêm yết, chi phí giữ lệnh khi tính cả funding, chuyện cháy tài khoản với từng chế độ ký quỹ, và danh sách khu vực bị chặn ngay từ cửa.

> **Điểm khởi đầu cho người mới:** bật tài khoản demo, chọn ký quỹ riêng (isolated) cho từng lệnh, đòn bẩy 3–5x trong vài tuần đầu, và đặt stop-loss trước khi bấm vào lệnh. Futures không có gói tháng, không có bản trả phí cố định: mọi chi phí đến từ phí giao dịch và funding.
>
> 👉 [Mở tài khoản OKX bằng mã giới thiệu CASH20 để vào trang đăng ký](https://okx.com/join/CASH20)

## Hợp đồng futures trên OKX gồm những loại nào?

OKX niêm yết cả hợp đồng vĩnh viễn (perpetual) không có ngày đáo hạn lẫn hợp đồng có kỳ hạn (delivery), cộng thêm vài dòng đặc biệt như Pre-Market và futures cho cổ phiếu, chỉ số, dầu. Tài sản thanh toán không chỉ có USDT: còn USDC, các đồng gắn với USD như USDG và RLUSD, và chính đồng coin cơ sở trong hợp đồng coin-margined.

Một điểm dễ nhầm: OKX Futures không bán gói thuê bao theo tháng hay theo năm. Không có bảng giá kiểu Basic/Pro, không có phí nền tảng cố định. Chi phí duy nhất là phí giao dịch theo khối lượng và funding, nên "chọn gói nào" thực chất là chọn loại hợp đồng và chế độ tài khoản.

| Loại hợp đồng | Ký quỹ / thanh toán | Đáo hạn | Phù hợp với | Điểm cần biết |
| --- | --- | --- | --- | --- |
| Vĩnh viễn USDT (ví dụ BTC-USDT-SWAP) | USDT | Không | Đa số nhà giao dịch, long/short dài hạn | Thanh khoản sâu nhất; trả hoặc nhận funding 3 lần mỗi ngày |
| Vĩnh viễn USDC / USD / RLUSD | USDC, USD, USDG, RLUSD | Không | Người muốn tránh USDT, đặc biệt ở EEA dưới MiCA | Sổ lệnh riêng, độ sâu mỏng hơn cặp USDT |
| Coin-margined | Chính đồng coin cơ sở | Không | Hedge vị thế spot, người giữ BTC/ETH dài hạn | Ký quỹ biến động cùng chiều vị thế, long có đòn bẩy bị phóng đại rủi ro |
| Có kỳ hạn: tuần / quý / bán niên | USDT | Có | Hedge sự kiện (dữ liệu macro, token unlock), cash-and-carry | Không có funding; phải đóng hoặc roll trước ngày đáo hạn |
| Pre-Market | USDT | Không | Đặt cược token trước khi lên sàn spot | Đòn bẩy thấp hơn, sổ lệnh mỏng, gap và trượt giá mạnh |
| X-Perps (EEA) | Theo quy định EU | 5 năm | Nhà đầu tư châu Âu | Dùng funding để bám giá spot, đáp ứng MiFID II |
| TradFi vĩnh viễn: cổ phiếu, chỉ số, dầu | USDT | Không | Người muốn exposure cổ phiếu Mỹ hoặc dầu 24/7 | Trần đòn bẩy 5x với cổ phiếu, 10x với X-Perps; giới hạn theo khu vực |

Hai cơ chế dễ lẫn nhất là vĩnh viễn và có kỳ hạn. Hợp đồng vĩnh viễn không có ngày đáo hạn, cứ đủ ký quỹ và chưa bị thanh lý thì giữ được vô thời hạn; giá được neo về spot bằng funding. Hợp đồng có kỳ hạn thì đóng theo lịch, và OKX thanh toán theo giá index bình quân của giờ cuối trước khi đáo hạn, cách này hạn chế việc một cây nến nhọn làm lệch giá thanh toán cuối cùng.

Hợp đồng tuần dùng để hedge đúng một sự kiện, ví dụ công bố dữ liệu macro hoặc đợt mở khóa token, rồi thoát vị thế mà không phải chịu funding vô hạn. Hợp đồng quý và bán niên hợp với cash-and-carry và hedge dài hạn. Nhóm Pre-Market cho phép đặt cược vào token trước khi nó lên spot, đổi lại đòn bẩy thường thấp và sổ lệnh mỏng, giá có thể nhảy qua khoảng trống rất mạnh.

## Phí giao dịch 0,02% / 0,05% và chi phí thật khi giữ lệnh

Phí cơ bản của OKX Futures là **0,02% cho maker** và **0,05% cho taker**. Maker là lệnh giới hạn nằm chờ trong sổ lệnh, taker là lệnh khớp ngay vào giá đang chào. Điểm quan trọng hơn con số: phí được tính trên **toàn bộ giá trị danh nghĩa của vị thế**, không phải trên phần ký quỹ bạn bỏ ra.

Ví dụ dễ hình dung: mở vị thế 20x, phí tính trên 20 lần số vốn thực tế. Mở và đóng là hai lần tính riêng, nên một vòng taker vào – taker ra tốn khoảng **0,10% giá trị danh nghĩa** trước khi nói tới funding. Lệnh bị thanh lý cũng bị tính theo giá taker, tức là thêm một khoản phí đúng lúc tài khoản đang lỗ.

Mức phí giảm dần theo bậc VIP, dựa trên khối lượng giao dịch 30 ngày và lượng OKB nắm giữ. Bậc càng cao, mức phí càng thấp, nhưng với người giao dịch vài nghìn USD mỗi tháng thì bậc cơ bản là con số cần tính.

Funding mới là phần hay bị bỏ qua. Đa số hợp đồng chốt funding vào **00:00, 08:00 và 16:00 UTC**, và chỉ ai đang giữ vị thế đúng thời điểm đó mới trả hoặc nhận. Funding dương thì long trả short, âm thì ngược lại. Thành phần lãi suất cố định là **0,01% mỗi chu kỳ 8 giờ**, giảm theo tỷ lệ với hợp đồng chốt 4, 2 hoặc 1 giờ.

Từ **tháng 4/2026**, khi funding chạm trần hoặc sàn, OKX tăng tần suất chốt theo từng nấc: 8 giờ → 4 giờ → 2 giờ → 1 giờ. Hợp đồng chỉ trở về lịch mặc định khi mọi lần chốt trong 12 giờ trước đó đều nằm trong khoảng **±0,20%**. Với vị thế 10.000 USDT trả 0,01% mỗi lần chốt, chi phí khoảng **3 USDT/ngày**; nếu bị đẩy lên chu kỳ 1 giờ, con số này lớn hơn nhiều lần.

Bài tính đầy đủ với hợp đồng SOL-USDT vĩnh viễn, dùng số liệu minh họa:

- Mua 200 hợp đồng, giá vào 110 USD, đòn bẩy 10x, ký quỹ khoảng 2.200 USD, khớp bằng lệnh market.
- Funding 0,025% mỗi 8 giờ, vị thế đi qua một lần chốt.
- Đóng ở 115 USD.

Lãi gộp = (115 − 110) × 200 = **1.000 USD**. Funding phải trả = 200 × 115 × 0,025% = **5,75 USD**. Phí taker hai chiều ≈ 200 × 110 × 0,05% × 2 = **22 USD**. Còn lại khoảng 972 USD trước các khoản khác. Với vị thế nhỏ, phí và funding đã ăn gần 3% lợi nhuận; với vị thế lớn hoặc giữ lâu, tỷ lệ này tăng lên.

👉 [Xem biểu phí và mở tài khoản OKX trước khi đặt lệnh đầu tiên](https://okx.com/join/CASH20)

## Đòn bẩy 125x, ba chế độ ký quỹ và lúc tài khoản bị thanh lý

Các cặp tiền có thanh khoản tốt nhất trên OKX cho đòn bẩy tối đa **125x**; những tài sản mỏng hơn có trần thấp hơn. Tài liệu cũ của chính OKX ghi mức 100x tùy tài sản, nên nếu bạn đọc ở nơi khác thấy con số khác, khác biệt nằm ở loại cặp và thời điểm công bố. Với người mới, trần 125x không phải thứ nên chạm tới: ở mức đó, một cú giật 1% đủ xóa sạch ký quỹ.

Ba chế độ ký quỹ thay đổi cách rủi ro lan truyền trong tài khoản:

**Ký quỹ riêng (isolated)** khóa ký quỹ cho từng vị thế. Lệnh đó cháy thì chỉ mất phần đã gán, số dư còn lại trong tài khoản không bị kéo theo. Đây là lựa chọn mặc định hợp lý khi mới tập.

**Ký quỹ chéo (cross)** chia sẻ ký quỹ cho toàn bộ vị thế. Vị thế đang lãi có thể đỡ vị thế đang lỗ, nhờ vậy khó bị thanh lý hơn, nhưng một lệnh sai có thể lôi cả tài khoản vào rủi ro.

**Ký quỹ danh mục (portfolio margin)** tối ưu yêu cầu ký quỹ cho các vị thế bù trừ nhau, dành cho người đã quen hedge và hiểu cách hệ thống tính.

Thanh lý xảy ra khi số dư ký quỹ xuống dưới mức duy trì mà OKX đặt theo từng hợp đồng và bậc đòn bẩy. Hệ thống đóng vị thế theo giá mark để tránh số dư âm, và có cảnh báo thời gian thực khi tài khoản tiến gần ngưỡng. Nên bật cơ chế hai giá (dual price mechanism) để giảm nguy cơ bị đóng vị thế bởi một cú nhiễu giá ngắn trên sàn giao ngay.

Phần đỡ phía sau là quỹ bảo hiểm: khi thanh lý hàng loạt tạo ra khoản thiếu hụt, quỹ này bù vào, nhờ đó người dùng ít gặp auto-deleveraging hơn. OKX cũng công bố báo cáo dự trữ (Proof of Reserves) được kiểm toán định kỳ, cho thấy tài sản người dùng được bảo chứng 1:1, cộng với lưu trữ lạnh và xác thực hai lớp.

## Futures cho cổ phiếu, chỉ số và dầu: phần mới nhất của OKX

Từ **tháng 3/2026**, OKX mở hợp đồng vĩnh viễn cho cổ phiếu Mỹ như Nvidia, Apple, Microsoft, cùng SPY và QQQ, tất cả thanh toán bằng USDT và giao dịch 24/7 mà không cần tài khoản chứng khoán. Trần đòn bẩy ở nhóm này là **5x**, thấp hơn hẳn cặp crypto chủ lực, vì rủi ro nhảy giá quanh mùa báo cáo, cuối tuần và các sự kiện doanh nghiệp.

Danh sách được mở rộng liên tục trong mùa thu. Tháng 11 có thêm MURATA, OXY và SMR; trước đó là Bank of America, Interactive Brokers và Constellation Energy. Bên cạnh cổ phiếu riêng lẻ còn có hợp đồng chỉ số US100, US500, JP225 với ký quỹ USDT. Giữ các vị thế này không nhận cổ tức, không có quyền biểu quyết hay bất kỳ quyền cổ đông nào khác.

Mảng hàng hóa có hợp đồng vĩnh viễn lấy giá tham chiếu từ các chuẩn **ICE Brent và WTI** đã được cấp phép. Đây là sản phẩm đầu tiên OKX làm với ICE, và chỉ mở ở những nơi OKX có giấy phép hợp đồng vĩnh viễn.

Có một chi tiết ảnh hưởng trực tiếp tới người giữ lệnh: chia tách cổ phiếu sẽ kích hoạt điều chỉnh hợp đồng. Tháng 11/2026, đợt chia tách của SanDisk là ví dụ, vị thế đang mở có thể bị đặt lại mức giá cơ sở để khớp với giá thị trường. Ai đang giữ lệnh qua những sự kiện kiểu này nên đọc thông báo trước.

Nhà đầu tư ở EEA tiếp cận nhóm tài sản tương tự qua X-Perps, hợp đồng 5 năm dùng funding để bám spot, gồm cả bảy cổ phiếu Magnificent 7, vàng, bạc, dầu, SPY và QQQ, giao dịch 24/7 với đòn bẩy tối đa **10x**.

Về phía chủ sở hữu, ICE đầu tư vào OKX từ tháng 3/2026 ở mức định giá 25 tỷ USD và nhận một ghế trong hội đồng quản trị; vòng gọi vốn tháng 10 cùng năm có thêm Circle, Ripple, Qube Research & Technologies và SC Ventures của Standard Chartered, vẫn ở mức định giá đó.

## Ai mở được tài khoản, ai bị chặn

OKX chặn hoặc giới hạn truy cập futures ở cấp sản phẩm với người dùng từ **Mỹ, Anh, Úc, Brazil và Hàn Quốc**. Cư dân Mỹ cũng bị khóa khỏi nhóm hợp đồng cổ phiếu và chỉ số nêu trên. Các khu vực khác phụ thuộc giấy phép địa phương, nên quyền truy cập được xác định theo từng thị trường.

Việt Nam không nằm trong danh sách hạn chế mà các tài liệu đã công bố liệt kê, nhưng điều đó không đủ để kết luận là mở được. Cách duy nhất để biết chắc là kiểm tra theo quốc gia cư trú ngay trên trang đăng ký trước khi nạp tiền.

KYC là bước không thể bỏ qua. Tài khoản chưa xác minh bị hạn chế nạp rút và hạn chế cả đòn bẩy, nên làm xong trước khi tính tới chuyện vào lệnh.

👉 [Kiểm tra quyền truy cập futures theo khu vực và đăng ký OKX với mã CASH20](https://okx.com/join/CASH20)

## So sánh phí cơ bản với Binance, Bybit và Hyperliquid

Ở bậc cơ bản dành cho tài khoản thường, mức phí của OKX tương đương bậc futures tiêu chuẩn của Binance và thấp hơn mức taker của Bybit. Hyperliquid, sàn on-chain, khởi điểm thấp hơn cả ba. Các con số dưới đây là mức công bố công khai, thay đổi theo bậc khối lượng, và giữa các nguồn có chênh lệch nhỏ.

| Sàn | Phí maker cơ bản | Phí taker cơ bản | Số hợp đồng |
| --- | --- | --- | --- |
| OKX | 0,02% | 0,05% | Khoảng 555 cặp theo CoinGecko; OKX tự công bố 100+ cặp, 150+ tài sản |
| Binance | 0,02% | 0,04% (một số nguồn ghi 0,05%) | 90+ |
| Bybit | 0,01% | 0,055% | 70+ |
| Hyperliquid | 0,015% | 0,045% | Sàn on-chain, danh mục hẹp hơn |

Ba cách đếm "số hợp đồng" đang tồn tại: số tài sản, số cặp hợp đồng, và số cặp giao dịch mà CoinGecko theo dõi. Chênh lệch giữa 150+, 100+ và khoảng 555 đến từ việc mỗi bên đếm một thứ khác nhau, không phải bên nào sai.

## Câu hỏi thường gặp

**Cần bao nhiêu tiền để bắt đầu?**
OKX không công bố một mức nạp tối thiểu cố định cho futures. Số tiền cần phụ thuộc kích thước lệnh và đòn bẩy: với ví dụ SOL ở trên, 200 hợp đồng tại giá 110 USD với đòn bẩy 10x cần khoảng 2.200 USD ký quỹ. Hãy tính ngược từ kích thước lệnh bạn muốn vào, rồi cộng thêm một khoản đệm để chịu được biến động trước khi bị gọi ký quỹ.

**Funding bị trừ vào lúc nào?**
Vào 00:00, 08:00 và 16:00 UTC với đa số hợp đồng. Chỉ vị thế đang mở đúng thời điểm đó mới bị tính. Mở lệnh sau 16:00 UTC vài phút thì không trả funding của lần chốt vừa rồi.

**Nên chọn vĩnh viễn hay có kỳ hạn?**
Giao dịch liên tục, không muốn canh ngày đáo hạn thì dùng vĩnh viễn, đổi lại phải theo dõi funding. Cần hedge đúng một sự kiện hoặc làm cash-and-carry thì hợp đồng tuần/quý phù hợp hơn, vì không có funding nhưng phải tính basis và thời điểm roll.

**Tài khoản demo nằm ở đâu?**
Có sẵn trong ứng dụng iOS/Android và trên dashboard web. Tài khoản demo dùng vốn ảo nhưng mô phỏng đúng giao diện, loại lệnh và công cụ quản lý rủi ro của tài khoản thật. Đây là nơi nên thử lần đầu, đặc biệt với lệnh điều kiện và stop-loss từng phần.

**Cháy tài khoản có bị nợ âm không?**
OKX đóng vị thế theo giá mark trước khi khoản lỗ vượt ký quỹ, và quỹ bảo hiểm xử lý phần thiếu hụt khi giá nhảy quá mạnh. Cơ chế này giảm khả năng số dư âm, không phải bảo đảm tuyệt đối trong mọi điều kiện thị trường.

## Chọn theo tình huống của bạn

Mục tiêu khác nhau dẫn tới lựa chọn khác nhau, và không có lựa chọn nào đúng cho tất cả:

- **Chỉ muốn hiểu cơ chế trước khi bỏ tiền:** tài khoản demo, ký quỹ riêng, đòn bẩy 3–5x. Chưa cần nạp gì.
- **Long/short dài hạn trên coin chủ lực:** hợp đồng vĩnh viễn USDT, thanh khoản sâu nhất, và đặt nhắc funding để biết chi phí giữ lệnh mỗi ngày.
- **Hedge lượng coin đang giữ:** hợp đồng coin-margined hoặc hợp đồng có kỳ hạn, tùy bạn muốn trung hòa cả khoản mục bằng USD hay chỉ chốt một mốc thời gian.
- **Muốn exposure cổ phiếu Mỹ hoặc dầu:** kiểm tra khu vực trước, rồi mới tính tới trần 5x với cổ phiếu và 10x với X-Perps. Nhóm này không trả cổ tức và có thể bị điều chỉnh hợp đồng khi doanh nghiệp chia tách.

Trước khi bấm lệnh đầu tiên, xác nhận hai thứ: KYC đã xong và quốc gia của bạn thực sự được mở futures. Sai ở bước này thì mọi tính toán phí bên trên đều vô nghĩa.

👉 [Đăng ký OKX với mã giới thiệu CASH20, hoàn tất KYC và bật tài khoản demo trước khi vào lệnh thật](https://okx.com/join/CASH20)
