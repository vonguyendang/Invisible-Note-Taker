# 🎙️ Invisible Note-Taker (Trợ Lý Ghi Chú Cuộc Họp Bí Mật)

<div align="center">

### 🌐 Chuyển đổi ngôn ngữ / Switch Language:
[![Tiếng Việt](https://img.shields.io/badge/🇻🇳_Đang_xem-Tiếng_Việt-d63031?style=for-the-badge)](README.md)
[![Switch to English](https://img.shields.io/badge/🇬🇧_Chuyển_sang-English-0984e3?style=for-the-badge)](README_EN.md)

</div>

> Hệ thống tự động chuyển âm thanh cuộc họp (Zoom, Google Meet, Teams, YouTube...) thành văn bản trên Google Docs trong thời gian thực qua tai nghe mà **100% người khác không hề hay biết**.

---

## 📖 1. Giới thiệu dự án (About The Project)

Trong môi trường làm việc trực tuyến hiện đại (Zoom, Google Meet, Microsoft Teams), các cuộc họp thường diễn ra dồn dập, nhiều thông tin quan trọng và khối lượng công việc phát sinh (action items) rất lớn. 

Việc vừa phải tập trung lắng nghe, trao đổi, vừa phải cặm cụi gõ phím ghi chép khiến chúng ta rất dễ bỏ sót ý hoặc mất tập trung. Trong khi đó, các giải pháp AI ghi chú cuộc họp hiện nay (như Otter.ai, Fireflies, Fathom...) thường gặp 3 rào cản lớn:
1. **Lộ liễu:** Bắt buộc phải có một con "Bot" lạ tham gia vào phòng họp, dễ gây cảm giác khó chịu hoặc nghi ngại cho đối tác, khách hàng.
2. **Bị chặn:** Nhiều cuộc họp bảo mật của công ty hoặc cơ quan nghiêm cấm quyền ghi âm (Record) và cấm tài khoản ngoài tham gia.
3. **Chi phí đắt đỏ:** Đa phần thu phí 15$ – 30$/tháng và giới hạn số phút ghi chép mỗi tháng.

**Invisible Note-Taker** ra đời như một giải pháp thay thế thông minh và tinh gọn: **Tận dụng chính màng loa tai nghe của bạn kết hợp với "sợi dây âm thanh ảo" để chuyển lời nói trong cuộc họp thẳng vào trang Google Docs cá nhân.** Bạn có được một người thư ký chép lời trung thành, chính xác từng từ mà không ai trong cuộc họp biết bạn đang ghi chép.

---

## 💰 2. Cam kết MIỄN PHÍ 100% (100% Free Forever)

Dự án này được xây dựng trên triết lý **tận dụng tối đa các công cụ có sẵn và mã nguồn mở**:
* **Không mất tiền mua phần mềm:** Không có phí khởi tạo, không cần tài khoản VIP.
* **Không phí duy trì hàng tháng:** Không bao giờ bị đòi nâng cấp gói hay mua thêm "gói giờ chép lời".
* **Không token, không API:** Sử dụng trực tiếp tính năng Nhập liệu bằng giọng nói (Voice Typing) miễn phí của Google Docs và phần mềm chia âm thanh mã nguồn mở/miễn phí (BlackHole trên Mac / VB-Audio Cable & Stereo Mix trên Windows).

---

## 🔒 3. Phân tích Bảo mật & Quyền riêng tư (Security & Privacy)

Hệ thống này an toàn và riêng tư hơn hầu hết các dịch vụ AI ghi chú bên thứ ba:

* **Âm thanh chỉ chạy nội bộ trên máy bạn (Local Audio Routing):** Tiếng nói từ cuộc họp chạy qua driver âm thanh ảo trong máy tính của bạn và đi thẳng vào trình duyệt Chrome. **Không có bất kỳ máy chủ bên thứ ba nào trung gian lắng nghe hay lưu trữ âm thanh của bạn.**
* **Bảo vệ bằng tài khoản Google chính chủ:** Toàn bộ nội dung chép lời được lưu trực tiếp vào file Google Docs nằm trong Google Drive cá nhân của bạn, được bảo vệ bởi bảo mật 2 lớp của tài khoản Google.
* **Không để lại bất kỳ dấu vết kỹ thuật nào (Zero Digital Footprint):**
  * Không có tài khoản Bot nào hiển thị trong danh sách người tham gia (Participant list).
  * Zoom / Google Meet không hiển thị biểu tượng "Đang ghi âm" (Recording...).
  * Không phát ra âm thanh thông báo *"This meeting is being recorded"* làm gián đoạn mọi người.

---

## ⚠️ 4. Nhận diện Rủi ro & Khuyến cáo Quan trọng (Risks & Disclaimers)

Dù hệ thống hoạt động vô hình và an toàn, bạn bắt buộc phải hiểu rõ các rủi ro thực tế sau để phòng tránh:

### 4.1. Rủi ro kỹ thuật và cách phòng ngừa

| RỦI RO THỰC TẾ | HẬU QUẢ | CÁCH PHÒNG NGỪA AN TOÀN |
| :--- | :--- | :--- |
| **Rủi ro lộ màn hình khi thuyết trình** | Khi đến lượt bạn chia sẻ màn hình, nếu bạn chọn Share toàn màn hình, đối tác sẽ thấy ngay file Google Docs đang tự gõ chữ lời của họ. | 👉 **Quy tắc vàng:** Chỉ chọn chia sẻ **"Một cửa sổ" (Window)** hoặc **"Một thẻ" (Tab)** chứa slide thuyết trình. Tuyệt đối không chọn Share toàn màn hình. |
| **Rủi ro thu nhỏ (Minimize) Chrome** | Khi bạn bấm thu nhỏ cửa sổ Chrome xuống đáy màn hình, hệ điều hành sẽ đưa Chrome vào chế độ ngủ để tiết kiệm pin -> Ngắt tính năng gõ chữ ngay lập tức. | 👉 **Quy tắc vàng:** Luôn để cửa sổ Chrome hiển thị trên màn hình (dù chỉ chiếm một góc nhỏ bên phải màn hình). |
| **Rủi ro bấm Mute (Tắt tiếng) trên phần mềm** | Nếu bạn tắt tiếng video YouTube hoặc bấm tắt tiếng loa cuộc họp trên trình duyệt, luồng âm thanh vào cáp ảo = 0 -> Google Docs ngừng gõ. | 👉 **Quy tắc vàng:** Luôn để âm lượng phần mềm trên 50%. Nếu thấy ồn, hãy vặn nhỏ âm lượng bằng nút vật lý trên chiếc tai nghe của bạn. |

### 4.2. Khuyến cáo Đạo đức & Pháp lý (Ethical & Legal Disclaimer)
* **Mục đích sử dụng:** Tài liệu này được biên soạn vì mục đích học tập, nghiên cứu công nghệ và hỗ trợ cá nhân ghi nhớ thông tin công việc, học tập hiệu quả hơn.
* **Tuân thủ quy định nội bộ:** Người dùng có trách nhiệm tuân thủ thỏa thuận bảo mật thông tin (NDA), chính sách an toàn thông tin của cơ quan/doanh nghiệp nơi mình công tác.
* **Quy định pháp lý địa phương:** Một số quốc gia và vùng lãnh thổ có luật định về sự đồng thuận của các bên khi lưu trữ nội dung cuộc trao đổi (Two-party consent laws). Bạn tự chịu trách nhiệm về tính hợp pháp và mục đích sử dụng các văn bản được chép lại.

---

## 📂 5. Danh mục tài liệu trong dự án

| Tài liệu | Ngôn ngữ | Mô Tả | Chuyển đổi sang bản tiếng Anh |
| :--- | :--- | :--- | :--- |
| **[README.md](README.md)** | 🇻🇳 Tiếng Việt | Giới thiệu dự án, bảo mật, cam kết miễn phí và tóm tắt | 👉 **[README_EN.md](README_EN.md)** |
| **[HUONG_DAN_CHI_TIET.md](HUONG_DAN_CHI_TIET.md)** | 🇻🇳 Tiếng Việt | Cầm tay chỉ việc từng cú click chuột từ A đến Z (Windows, Mac Intel, Mac M1-M4) | 👉 **[GUIDE_EN.md](GUIDE_EN.md)** |

---

## 🛠️ 6. Nguyên lý hoạt động (Kiến trúc luồng âm thanh)

```
Cuộc họp / Meeting (Zoom / Teams app HOẶC thẻ Google Meet trên Chrome)
                                │
                                ▼
                      [Sợi dây âm thanh ảo]
       ├── Nhánh 1 ────────────► [Tai nghe của bạn (Vẫn nghe tiếng rõ ràng)]
       ├── Nhánh 2 ────────────► [Loa ngoài máy tính (Tự động chuyển khi rút tai nghe)]
       └── Nhánh 3 ────────────► [Google Docs trên Chrome (Tự động gõ chữ Tiếng Việt)]
```

---

## ⚡ 7. Tóm tắt 4 bước thực hiện nhanh

1. **Chuẩn bị đồ nghề:** Tai nghe và **trình duyệt Google Chrome** duy nhất *(tùy chọn: cài thêm Firefox nếu thích tách riêng)*.
2. **Cài đặt sợi dây âm thanh ảo:**
   - **Windows:** Bật *Stereo Mix* có sẵn hoặc cài [VB-Audio Cable](https://vb-audio.com/Cable/).
   - **macOS:** Cài [BlackHole 2ch](https://existential.audio/blackhole/) và tạo *Multi-Output Device* tích chọn cả 3 thiết bị: BlackHole + Tai nghe + Loa máy tính *(nhớ tích Drift Correction nếu dùng Mac M1-M4)*.
3. **Chạy thử nghiệm trên YouTube:** Bật tin tức trên 1 tab (âm lượng > 50%), mở Google Docs bật Micro đỏ trên tab bên cạnh, bấm `F5` (Windows) hoặc `Command + R` (Mac) để tải lại trang và xem chữ tự gõ.
4. **Vào họp thực tế:**
   - *Họp Zoom/Teams:* Mở app họp + mở Chrome Google Docs.
   - *Họp Google Meet trên Chrome:* Tab Meet chọn Micro thật để nói, tab Docs chọn Micro ảo để chép chữ.
   - *3 Lưu ý sống còn:* Không thu nhỏ cửa sổ Chrome, Không Share toàn bộ màn hình, và Không bấm Mute trên phần mềm/trình duyệt.

👉 *Xem hướng dẫn chi tiết từng bước bấm chuột có hình ảnh mô tả: **[HUONG_DAN_CHI_TIET.md](HUONG_DAN_CHI_TIET.md) (Tiếng Việt)** hoặc **[GUIDE_EN.md](GUIDE_EN.md) (English)**.*
