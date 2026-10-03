Quant Percent Terminal 0.1.7

- Quant Portfolio có tab riêng: nhập danh mục và xem kết quả trong cùng màn hình; quay lại Biểu đồ giữ mã và khung nến đang xem.
- Danh mục tự lưu trên thiết bị, giữ cả các ô đang nhập, tiền mặt và khoảng thời gian phân tích.
- Tiền hiển thị đầy đủ đơn vị: triệu đồng, tỷ đồng; dấu phẩy thập phân theo tiếng Việt.
- Giải thích và nhãn công cụ dễ hiểu hơn cho nhà đầu tư cá nhân. Công thức và phương pháp mở khi cần.
- Sửa chú thích chỉ báo `[object Object]`, mục tìm kiếm `undefined`, tràn ô chỉ số và chuyển khung nến gây tải lặp.
- Thêm 14 cặp Binance Spot USDT, lọc mã trùng; danh sách cũ Bitcoin/Ethereum tự chuyển sang cặp Binance tương ứng.
- Có nút tài khoản/đăng xuất; bỏ nút toàn màn hình, chấm kết nối và tab Thành tích trong Nghiên cứu thị trường.
- Biểu đồ phân tích dùng ECharts với cùng màu sắc, tương tác và hiệu ứng như bản web.

Đóng Quant Percent Terminal rồi cài bộ cài mới đè lên bản hiện tại. Dữ liệu cá nhân được giữ nguyên.

Close Quant Percent Terminal and install this update over the existing version. Personal data is retained.

The release adds a dedicated Quant Portfolio workspace, saved portfolio drafts, explicit currency units, clearer investor guidance, fixed indicator/search captions, bounded crypto refresh and 14 Binance Spot pairs, account/sign-out controls and consistent interactive research plots.

Website startup readiness is deployed separately; it does not change desktop licence requirements. Gold, oil and forex providers are unchanged.


## Build and verification

- Built from source commit `3855c0558cc24124d2da3c70e1b1e9a00d7aa654` with Nuitka; EXE FileVersion and ProductVersion `0.1.7.0`.
- NSIS installer `QP-Terminal-setup.exe`: 205,713,649 bytes; FileVersion `0.1.7`.
- SHA-256: `7248c78b1b5842970608b8cb39d07281e369af03ba618b12b60e0fca96387a14`.
- Distribution audit: 1,355 files, no known credentials or development pages found.
- All 70 bundled frontend files match the source.
- Compiled WebView2 app: fresh customer licence gate, API/config health, unique crypto catalogue, Portfolio assets and persistent storage after restart passed on an isolated profile.
- Browser checks: dedicated Portfolio workspace, submitted holdings, five result tabs, Vietnamese/English, keyboard navigation, dark theme and four screen widths passed for app and embedded web.
- Investor UI, saved portfolio drafts, rapid candle switching and all research report rendering checks passed. Website frontend lint, typecheck and production build passed; backend 241 tests passed.
- Website changes deployed successfully, including full Quant Percent naming.
- A separate clean-machine Windows installation has not been performed.
