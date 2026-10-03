# Quant Percent Terminal

Phần mềm nghiên cứu chỉ báo và chiến lược giao dịch cho thị trường Việt Nam và tiền mã hoá, chạy trên máy tính Windows của bạn. Nhà phát hành: **Quant Percent** ([quantpercent.com](https://quantpercent.com)).

*English below.*

## Tải về

**[Tải Quant Percent Terminal cho Windows](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases/latest/download/QP-Terminal-setup.exe)**

Phiên bản mới nhất: **0.1.7**. [Xem thay đổi](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases/tag/v0.1.7).

Hoặc vào mục [Releases](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases) để xem mọi phiên bản và ghi chú thay đổi.

## Yêu cầu

- Windows 10 hoặc Windows 11, 64-bit.
- Khoảng 600 MB ổ đĩa trống.
- Kết nối Internet: để kích hoạt bản quyền và tải dữ liệu thị trường. Không cần VPN.
- Microsoft Edge WebView2. Windows 11 có sẵn; Windows 10 thường cũng đã có qua Windows Update.
- Một **mã bản quyền** dạng `QP-XXXXX-XXXXX-XXXXX-XXXXX`, nhận từ Quant Percent.

## Cài đặt

1. Tải `QP-Terminal-setup.exe` và mở nó.
2. Windows có thể hiện "Windows protected your PC", vì bộ cài chưa có chữ ký số. Bấm **More info**, rồi **Run anyway**.
3. Chọn ngôn ngữ, đọc điều khoản sử dụng, tích ô chấp thuận, rồi bấm **Cài đặt**.
   - Không cần quyền quản trị. App được cài vào `%LOCALAPPDATA%\Programs\QuantPercent`.
4. Mở **Quant Percent Terminal** từ Start Menu.

Để cập nhật: đóng app, tải bộ cài mới từ liên kết trên rồi cài đè. Dữ liệu cá nhân được giữ nguyên. App hiện chưa tự tải hoặc cài bản cập nhật.

Nếu máy bật **Smart App Control**, Windows sẽ chặn hẳn app chưa có chữ ký số. Hiện chưa có cách chạy trên máy bật tính năng này.

## Kích hoạt

Lần đầu mở, app hiện màn hình nhập mã bản quyền.

1. Dán mã bản quyền vào ô, rồi bấm **Kích hoạt**.
2. Mỗi mã dùng được trên **tối đa 2 máy**. Kích hoạt lại trên cùng một máy không tốn thêm lượt.
3. Muốn chuyển sang máy khác: mở app, bấm **Ctrl+K**, chọn **Bản quyền**, rồi bấm **Gỡ máy này** để trả lại lượt.

Bạn có thể đăng nhập tài khoản Quant Percent trong app. Nếu email đã xác thực và
mã bản quyền đã được liên kết với email người mua, app hiển thị mã để sao chép
và kích hoạt. Đăng ký tài khoản hoặc thanh toán hiện chưa tự cấp mã: Quant Percent
vẫn xác nhận thanh toán, cấp mã và liên kết mã với email thủ công.

Bản 0.1.4 cũng cập nhật nến VN đã được database sửa mà không cần tải lại biểu đồ,
cho nến ngày thay đổi trong phiên, và sửa việc thiếu lịch sử Bitcoin khi luồng
giá chạy trước lần nạp dữ liệu đầu. Bản cài cho khách nhận nến VN từ gateway khi
phút đã đóng; cập nhật theo từng giây hiện áp dụng cho bản kết nối database trực tiếp.

Bản 0.1.5 cho phép chọn khung nến và phạm vi lịch sử riêng trong phân tích chuỗi
giá, kiểm định chiến lược, Walk-forward và hai kiểu so sánh. Bạn có thể chọn số
nến gần nhất, toàn bộ lịch sử hiện có hoặc khoảng ngày.

Bản 0.1.6 đồng bộ các biểu đồ Quant Portfolio và nghiên cứu: chuyển động,
tooltip, chú giải tương tác, thu phóng trên các biểu đồ phù hợp, giao diện sáng/tối
và bố cục tự co giãn. Danh mục có thêm biểu đồ lịch sử và phân phối lợi suất;
phân bổ tài sản tính cả tiền mặt. Nguồn dữ liệu thị trường không thay đổi.

App thử kiểm tra bản quyền qua Internet mỗi 12 giờ. Mỗi lần kiểm tra thành công cho phép dùng offline tối đa **3 ngày tính từ lần kiểm tra đó**, hoặc tới ngày hết hạn bản quyền nếu sớm hơn. Sau thời hạn này, app khoá lại cho tới khi kết nối lại và bấm **Kiểm tra lại**. Nếu bản quyền vẫn hợp lệ thì dùng tiếp, không cần mua mã mới; dữ liệu đã lưu trên máy được giữ nguyên. Dữ liệu thị trường mới và giá trực tiếp cần Internet.

Bản 0.1.7 có tab Quant Portfolio riêng, tự lưu danh mục trên thiết bị và ghi rõ
đơn vị tiền. Câu chữ dễ hiểu hơn; sửa chú thích chỉ báo, tìm kiếm, tràn ô chỉ số
và tải lặp khi đổi khung nến. Có nút đăng xuất và 14 cặp Binance Spot USDT.

## Dữ liệu của bạn

Cài đặt, bố cục, phiên giao dịch giả lập, cảnh báo và plugin bạn viết được lưu ở `%APPDATA%\QuantPercent`, tách khỏi thư mục cài.

- Cài bản mới đè lên bản cũ thì giữ nguyên dữ liệu.
- Khi gỡ cài, bạn được hỏi có xoá dữ liệu không. Nếu chọn xoá, dữ liệu được chuyển vào **Thùng rác**, không xoá hẳn.

## Gỡ cài đặt

Vào Settings, chọn Apps, tìm **Quant Percent Terminal**, rồi bấm Uninstall.

## Lưu ý quan trọng

Quant Percent Terminal là công cụ nghiên cứu, **không phải lời khuyên đầu tư**. Kết quả backtest và mô phỏng dựa trên dữ liệu quá khứ và các giả định về phí, trượt giá, khớp lệnh; chúng không bảo đảm kết quả trong tương lai. Bản đầy đủ của điều khoản sử dụng: [TERMS.vi.txt](TERMS.vi.txt).

## Hỗ trợ

Mua mã bản quyền, gia hạn, báo lỗi: [quantpercent.com](https://quantpercent.com).

---

# Quant Percent Terminal (English)

A Windows desktop application for researching trading indicators and strategies on Vietnamese markets and crypto. Published by **Quant Percent** ([quantpercent.com](https://quantpercent.com)).

## Download

**[Download Quant Percent Terminal for Windows](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases/latest/download/QP-Terminal-setup.exe)**

Latest version: **0.1.7**. [Release notes](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases/tag/v0.1.7).

All versions and release notes are under [Releases](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases).

## Requirements

- Windows 10 or 11, 64-bit.
- About 600 MB of free disk space.
- An Internet connection, to activate the licence and load market data. No VPN is needed.
- Microsoft Edge WebView2. It ships with Windows 11 and usually reaches Windows 10 through Windows Update.
- A **licence key** in the form `QP-XXXXX-XXXXX-XXXXX-XXXXX`, issued by Quant Percent.

## Install

1. Download `QP-Terminal-setup.exe` and open it.
2. Windows may show "Windows protected your PC", because the installer is not code-signed yet. Click **More info**, then **Run anyway**.
3. Choose a language, read and accept the terms, then click **Install**.
   - No administrator rights are needed. The app installs to `%LOCALAPPDATA%\Programs\QuantPercent`.
4. Start **Quant Percent Terminal** from the Start Menu.

To update: close the app, download the latest installer using the link above and install over the previous version. Personal data is retained. The app does not yet download or install updates automatically.

If **Smart App Control** is on, Windows blocks unsigned apps outright. There is currently no way to run Quant Percent Terminal on such a machine.

## Activate

The first time the app starts, it asks for your licence key.

1. Paste the key, then click **Activate**.
2. Each key works on **up to 2 computers**. Activating again on the same computer does not use another slot.
3. To move to another computer: open the app, press **Ctrl+K**, choose **Licence**, then click **Release this machine** to free its slot.

You can sign in to your Quant Percent account in the app. If your email is
verified and a licence key has been linked to that email, the app displays the
key for copying and activation. Registration or payment does not yet issue a
key automatically; Quant Percent still confirms payment, issues the key and
links it to the buyer's email manually.

Version 0.1.4 also updates corrected Vietnamese candles without a chart reload,
updates the daily candle during the session, and repairs missing Bitcoin history
when the live feed starts before the first backfill. Customer installations read
finished VN minutes through the gateway. Per-second VN updates currently apply
to installations with a direct database connection.

Version 0.1.5 adds separate candle interval and history range controls to
price-series analysis, strategy statistics, walk-forward and both comparison
tools. Choose recent bars, all available history or a date window.

Version 0.1.6 unifies Quant Portfolio and research plots with animation,
tooltips, interactive legends, zoom where appropriate, light/dark themes and
responsive layouts. Portfolio includes historical return and distribution
plots, and allocation accounts for cash. Market data providers are unchanged.

The app attempts an online licence check every 12 hours. Each successful check permits offline use for up to **3 days from that check**, or until the licence expires if sooner. After that the app locks until you are back online and click **Check again**. A valid licence can resume without buying another key; your locally saved data is retained. New market data and live prices require Internet access.

Version 0.1.7 adds a dedicated Quant Portfolio tab, saved local drafts and
explicit currency units. It clarifies investor guidance, fixes indicator/search
captions and metric overflow, bounds crypto refresh, adds sign-out controls
and supports 14 Binance Spot USDT pairs.

## Your data

Settings, layouts, paper-trading sessions, alerts and your own plugins are stored in `%APPDATA%\QuantPercent`, separate from the install folder.

- Installing a new version over an old one keeps your data.
- When you uninstall, you are asked whether to remove your data. If you choose to remove it, it goes to the **Recycle Bin** and is not deleted outright.

## Uninstall

Open Settings, go to Apps, find **Quant Percent Terminal**, then click Uninstall.

## Important

Quant Percent Terminal is a research tool, **not investment advice**. Backtests and simulations rely on past data and on assumptions about fees, slippage and order fills; they do not guarantee future results. Full terms of use: [TERMS.en.txt](TERMS.en.txt).

## Support

Licence purchase, renewals and bug reports: [quantpercent.com](https://quantpercent.com).
