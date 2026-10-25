# HƯỚNG DẪN CẦM TAY CHỈ VIỆC: TỰ TẠO TRỢ LÝ GHI CHÚ CUỘC HỌP BÍ MẬT (DÀNH CHO AI CŨNG LÀM ĐƯỢC)

<div align="center">

### 🌐 Chuyển đổi ngôn ngữ / Switch Language:
[![Tiếng Việt](https://img.shields.io/badge/🇻🇳_Đang_xem-Tiếng_Việt-d63031?style=for-the-badge)](HUONG_DAN_CHI_TIET.md)
[![Switch to English](https://img.shields.io/badge/🇬🇧_Chuyển_sang-English-0984e3?style=for-the-badge)](GUIDE_EN.md)
[![Về trang README](https://img.shields.io/badge/📖_Trang_chủ-README.md-2d3436?style=for-the-badge)](README.md)

</div>

---

## 1. Hệ thống này giúp gì cho bạn và nó hoạt động thế nào?

### 1.1. Hình dung đơn giản nhất
Hãy tưởng tượng bạn thuê được một **người thư ký vô hình**. Người này ngồi ngay cạnh loa máy tính của bạn:
* Khi sếp hoặc đối tác cất tiếng nói trong cuộc họp Zoom hoặc Google Meet, người thư ký nghe thấy tới đâu sẽ cặm cụi gõ lại từng từ thành văn bản Tiếng Việt trên một trang giấy trắng tới đó.
* Bạn chỉ việc đeo tai nghe ngồi nghe bình thường, mắt liếc sang góc màn hình là thấy toàn bộ cuộc họp đang được chép lại thành chữ rõ ràng từng câu.

### 1.2. Ba cam kết tuyệt đối
* **100% Bí mật:** Không cài thêm bất kỳ con bot (robot lạ) nào vào phòng họp. Không hiện biểu tượng ghi âm nhấp nháy. Không ai trong cuộc họp biết bạn đang chép lời.
* **100% Miễn phí:** Dùng hoàn toàn các công cụ miễn phí có sẵn, không mất một đồng phí duy trì hàng tháng.
* **Chạy bền bỉ:** Cuộc họp kéo dài 3 đến 4 tiếng đồng hồ vẫn tự động gõ chữ liên tục, không bị ngắt quãng giữa chừng.

---

## 2. Những thứ bạn cần chuẩn bị sẵn trên bàn làm việc

Trước khi bắt đầu, hãy kiểm tra danh sách đồ nghề sau:

- [ ] **1. Chiếc tai nghe bạn hay dùng:**
  * Có thể dùng tai nghe có dây (cắm chân tròn 3.5mm hoặc chân dẹt Type-C).
  * Hoặc tai nghe không dây Bluetooth (như AirPods, tai nghe Sony, Samsung...).

- [ ] **2. Trình duyệt Internet:**
  * **Bạn CHỈ CẦN DUY NHẤT 1 TRÌNH DUYỆT: Google Chrome** *(Khuyên dùng vì tiện lợi nhất, tải tại: [google.com/chrome](https://www.google.com/chrome/))*.
  * *(Tùy chọn mở rộng nếu thích):* Bạn có thể cài thêm **Firefox** ([mozilla.org/firefox](https://www.mozilla.org/firefox/)) nếu bạn muốn tách hẳn cuộc họp sang một trình duyệt riêng biệt cho đỡ nhầm lẫn.

- [ ] **3. Phần mềm "Sợi dây âm thanh ảo" (Chọn 1 trong 2 đường link tùy theo máy tính của bạn):**
  * **Nếu bạn dùng máy tính Windows:** Tải phần mềm **VB-Audio Cable** miễn phí tại: [vb-audio.com/Cable](https://vb-audio.com/Cable/) *(Bấm vào nút màu cam có chữ "Download" hình đĩa mềm để tải file về).*
  * **Nếu bạn dùng máy tính Mac (Apple):** Tải phần mềm **BlackHole 2ch** miễn phí tại: [existential.audio/blackhole](https://existential.audio/blackhole/) *(Điền email để nhận link tải gói cài đặt dành cho cả chip Intel đời cũ và chip M1, M2, M3, M4 đời mới).*

> **"Sợi dây âm thanh ảo" là gì?**  
> Bình thường tiếng từ cuộc họp chỉ chạy thẳng vào màng loa tai nghe của bạn rồi mất đi. Phần mềm này đóng vai trò như một **ống dẫn nước chia ba**: một nhánh dẫn tiếng vào tai nghe, một nhánh dự phòng sẵn cho loa ngoài, và một nhánh dẫn thẳng tiếng nói đó vào ô gõ chữ của Google Chrome để máy tự gõ thành văn bản.

---

## 3. Các bước thiết lập chi tiết trên máy tính của bạn

*(Hãy nhìn vào máy tính của bạn và chọn đúng phần hướng dẫn bên dưới)*

---

### PHẦN A: DÀNH CHO MÁY TÍNH WINDOWS (MÁY HP, DELL, ASUS, LENOVO, THINKPAD...)

#### BƯỚC 1: Kiểm tra tính năng có sẵn mang tên "Stereo Mix"
Nhiều máy tính Windows đã có sẵn sợi dây ảo này mà không cần cài thêm gì.

* **Thao tác 1.1:** Trên bàn phím, giữ phím **Windows** (phím có hình 4 ô vuông) rồi bấm chữ **R**. Một khung nhỏ hiện ra ở góc dưới bên trái màn hình.
* **Thao tác 1.2:** Nhập vào dòng chữ `mmsys.cpl` rồi ấn phím **Enter** trên bàn phím.
* **Thao tác 1.3:** Một bảng nhỏ tên là **Sound** xuất hiện. Bấm vào thẻ thứ hai có tên là **Recording** (hình chiếc micro nhỏ).
* **Thao tác 1.4:** Tìm xem trong danh sách có dòng chữ nào tên là **Stereo Mix** (biểu tượng hai cột sóng đứng cạnh nhau) hay không:
  * *Nếu có và đang bị mờ:* Bấm chuột phải vào chữ **Stereo Mix** -> Bấm chọn chữ **Enable** (Bật). Lúc này xuất hiện dấu tích màu xanh lá cây là xong, bạn chuyển thẳng sang **Mục 4** để chạy thử!
  * *Nếu không thấy chữ Stereo Mix:* Đừng lo, máy bạn thuộc nhóm cần dùng phần mềm phụ trợ. Hãy làm tiếp **Bước 2** ngay dưới đây.

#### BƯỚC 2: Cài đặt và kích hoạt phần mềm "VB-Audio Cable" (Nếu không có Stereo Mix)

* **Thao tác 2.1 (Cài đặt):** Mở file tải về từ link ở Mục 2, giải nén thư mục, bấm chuột phải vào file `VBCABLE_Setup_x64.exe` và chọn dòng có hình chiếc khiên nhỏ: **Run as administrator** (Chạy với quyền quản trị) -> Bấm **Install Driver** -> Khởi động lại máy tính một lần.
* **Thao tác 2.2 (Đổi loa chính):** Nhìn xuống góc dưới cùng bên tay phải của màn hình máy tính, bấm chuột trái vào hình **Chiếc Loa**. Bấm vào mũi tên nhỏ cạnh tên loa hiện tại -> Bấm chọn dòng chữ **CABLE Input (VB-Audio Virtual Cable)**.
* **Thao tác 2.3 (Dẫn tiếng về tai nghe):** Mở lại bảng **Sound** (bằng cách ấn phím `Windows + R`, gõ `mmsys.cpl` rồi ấn Enter). Bấm chuột vào thẻ **Recording** (thẻ thứ 2 từ trái sang).
* **Thao tác 2.4:** Bấm chuột phải vào dòng chữ **CABLE Output** -> Chọn dòng cuối cùng có chữ **Properties** (Thuộc tính).
* **Thao tác 2.5:** Một cửa sổ mới mở ra, bấm vào thẻ thứ hai tên là **Listen** (hình chiếc tai nghe). Tích chuột vào ô vuông nhỏ có chữ **Listen to this device**.
* **Thao tác 2.6:** Ngay dòng phía dưới có chữ *Playback through this device*, bấm vào thanh thả xuống và chọn đúng **Tên chiếc tai nghe bạn đang cắm** -> Bấm nút **OK** ở góc dưới cùng bên phải.  
*(Lúc này, âm thanh cuộc họp sẽ vừa chạy vào phần mềm ảo để biến thành chữ, vừa phát vào tai bạn).*

---

### PHẦN B: DÀNH CHO MÁY MÁC (MACBOOK, IMAC DÙNG CHIP INTEL ĐỜI CŨ)

*Sau khi đã tải và cài đặt xong phần mềm BlackHole 2ch từ link ở Mục 2:*

#### BƯỚC 1: Mở công cụ quản lý âm thanh của Mac
* **Thao tác 1.1:** Trên bàn phím, bấm cùng lúc phím **Command (⌘)** và **Thanh dấu cách (Space)** để mở thanh tìm kiếm Spotlight ở giữa màn hình.
* **Thao tác 1.2:** Gõ chữ `Audio MIDI Setup` rồi ấn phím **Return (Enter)**. Cửa sổ *Thiết bị Âm thanh* sẽ hiện lên.

#### BƯỚC 2: Tạo đường truyền âm thanh song song "Một lần dùng mãi mãi"
* **Thao tác 2.1:** Nhìn xuống góc dưới cùng bên tay trái của cửa sổ, bấm vào nút **Dấu cộng (+)** màu trắng nằm trong vòng tròn.
* **Thao tác 2.2:** Một menu nhỏ bật lên, bấm chọn dòng chữ **Create Multi-Output Device** (Tạo thiết bị nhiều đầu ra).
* **Thao tác 2.3 (TÍCH CHỌN CẢ 3 Ô ĐỂ DÙNG LINH HOẠT TAI NGHE VÀ LOA NGOÀI):**  
  Nhìn sang khung bên phải, hãy tích chuột vào **CẢ 3 Ô VUÔNG** sau:
  1. Ô vuông cạnh dòng chữ **BlackHole 2ch** *(để đưa âm thanh vào gõ chữ)*.
  2. Ô vuông cạnh dòng chữ **External Headphones** *(hoặc tên tai nghe Bluetooth bạn đang đeo)*.
  3. Ô vuông cạnh dòng chữ **MacBook Speakers** *(Loa ngoài có sẵn của máy)*.  
  👉 *Việc tích sẵn cả 3 ô này ngay từ đầu giúp bạn sau này rút tai nghe ra nghe loa ngoài hoặc cắm tai nghe vào lại máy vẫn tự động chép chữ liên tục, không bao giờ phải mở lại bảng cài đặt này nữa!*
* **Thao tác 2.4:** Nhìn lại danh sách bên trái, bấm chuột phải vào dòng chữ **Multi-Output Device** vừa tạo -> Bấm chọn dòng **Use This Device For Sound Output** (Dùng thiết bị này làm đầu ra âm thanh).

#### BƯỚC 3: Chọn nguồn ghi âm cho máy
* **Thao tác 3.1:** Bấm vào hình quả táo khuyết ở góc trên cùng bên trái màn hình -> Chọn **System Settings** (Cài đặt hệ thống) hoặc **System Preferences**.
* **Thao tác 3.2:** Bấm vào mục **Sound** (biểu tượng hình chiếc Loa) -> Bấm chọn thẻ **Input** (Đầu vào) -> Bấm chuột chọn dòng **BlackHole 2ch**.

---

### PHẦN C: DÀNH CHO MÁY MÁC MỚI (MACBOOK CHIP M1, M2, M3, M4... CHIP APPLE SILICON)

*Các dòng máy Mac đời mới dùng chip Apple Silicon có cơ chế bảo mật và tốc độ xử lý âm thanh rất nhạy, bạn thực hiện theo các bước chuẩn sau:*

> ⚠️ **CẢNH BÁO QUAN TRỌNG VỀ THÔNG BÁO QUYỀN TRÊN MAC:**  
> Khi bạn bấm Micro trên Google Chrome lần đầu tiên, hệ thống macOS sẽ hiện một hộp thoại nhỏ hỏi: *"Google Chrome muốn truy cập Microphone"*.  
> 👉 **BẠN PHẢI LUÔN BẤM "CHO PHÉP" (ALLOW / OK).**  
> Tuyệt đối không bấm "Từ chối" (Don't Allow). Nếu lỡ bấm Từ chối, hệ thống Mac sẽ khóa cứng Micro lại và bạn sẽ phải làm Bước 2 dưới đây để mở khóa.

#### BƯỚC 1: Tạo thiết bị song song và bật tính năng chống lệch nhịp
* **Thao tác 1.1:** Nhấn **Command + Thanh dấu cách**, gõ `Audio MIDI Setup` rồi ấn **Enter**.
* **Thao tác 1.2:** Bấm vào **Dấu cộng (+)** ở góc dưới bên trái -> Chọn **Create Multi-Output Device**.
* **Thao tác 1.3 (TÍCH CHỌN CẢ 3 Ô):** Ở bảng bên phải, tích chuột vào **CẢ 3 Ô VUÔNG**:
  1. **BlackHole 2ch**
  2. **Tai nghe của bạn** (External Headphones hoặc tai nghe Bluetooth)
  3. **MacBook Speakers** (Loa ngoài của máy).
* **Thao tác 1.4 (BẮT BUỘC):** Ở cột có tiêu đề **Drift Correction** (Sửa độ lệch), tìm dòng ngang của chữ **BlackHole 2ch** và **tích dấu chọn vào ô vuông nhỏ** đó.  
  *(Bước này cực kỳ quan trọng đối với chip Apple Silicon: nó giúp âm thanh không bị giật hoặc nuốt chữ khi chuyển thành văn bản).*
* **Thao tác 1.5:** Chuột phải vào dòng **Multi-Output Device** ở cột bên trái -> Chọn **Use This Device For Sound Output**.

#### BƯỚC 2: Cấp quyền Micro cho Google Chrome (Phòng ngừa trường hợp lỡ bấm Từ chối)
* **Thao tác 2.1:** Bấm vào biểu tượng hình quả táo ở góc trên cùng bên trái màn hình -> Chọn **System Settings** (Cài đặt hệ thống, hình bánh răng cưa màu xám).
* **Thao tác 2.2:** Tìm và bấm vào mục **Privacy & Security** (Quyền riêng tư & Bảo mật, biểu tượng bàn tay màu xanh) ở cột bên trái -> Bấm vào mục **Microphone** (hình chiếc micro).
* **Thao tác 2.3:** Tìm dòng chữ **Google Chrome** -> Gạt thanh công tắc nhỏ bên cạnh sang phải để nó hiện **Màu xanh lá cây**.

---

## 4. Quy trình CHẠY THỬ (TEST) hệ thống bằng YouTube

*(Bắt buộc làm bước này trước khi vào cuộc họp thật để đảm bảo 100% ăn khớp)*

```
[Phát video YouTube (Thẻ 1 trên Chrome hoặc mở trên Firefox)] 
                                │
                                ▼ (Âm thanh đi qua Sợi dây ảo)
                                │
        [Tai nghe của bạn (Vẫn nghe rõ tiếng bình thường)] 
                                + 
        [Google Docs (Thẻ 2 trên Chrome: Tự động gõ chữ Tiếng Việt)]
```

### Bước 4.1: Phát âm thanh mẫu
* Mở một Thẻ (Tab) trên Chrome (hoặc mở Firefox), vào `youtube.com` và bật một video tin tức tiếng Việt có giọng đọc rõ (Ví dụ: *"Bản tin thời sự VTV24"*).
* **LƯU Ý ÂM LƯỢNG:** Kéo thanh âm lượng của video YouTube lên mức lớn (từ 50% đến 100%).
* **Kiểm tra:** Đeo tai nghe vào, bạn vẫn phải nghe thấy tiếng phát thanh viên nói bình thường trong tai nghe.

### Bước 4.2: Kích hoạt trang gõ chữ trên Google Chrome
* Mở thêm một Thẻ (Tab) mới trên Google Chrome, truy cập `docs.google.com` và bấm mở một **Trang tài liệu trống**.
* Nhìn lên thanh menu trên cùng, bấm vào chữ **Công cụ** -> Chọn dòng **Nhập dữ liệu bằng giọng nói** (hoặc bấm phím tắt `Ctrl + Shift + S` trên Windows, `Command + Shift + S` trên Mac).
* Trên trang giấy sẽ xuất hiện một hộp nhỏ có **Hình chiếc Micro màu xám**. Ngay phía trên chiếc micro, bấm vào mũi tên nhỏ và chọn đúng chữ **Tiếng Việt**.

### Bước 4.3: Định tuyến nguồn âm thanh và TẢI LẠI TRANG
* Nhìn lên thanh gõ địa chỉ trang web của Chrome (nơi hiển thị chữ `docs.google.com...`):
* Bấm vào biểu tượng **Hình hai thanh gạt điều chỉnh** (hoặc hình cái khóa nhỏ) ở góc bên trái thanh địa chỉ:
  * Bấm chọn dòng **Cài đặt trang web** (Site settings).
  * Tìm dòng **Micrô** (Microphone): Bấm vào mũi tên thả xuống và chọn đúng tên thiết bị ảo:
    * *Trên Windows:* Chọn **Stereo Mix** hoặc **CABLE Output (VB-Audio Cable)**.
    * *Trên Mac:* Chọn **BlackHole 2ch**.
* **BƯỚC QUAN TRỌNG NHẤT — TẢI LẠI TRANG:**  
  Quay lại thẻ Google Docs, bạn bắt buộc phải tải lại trang để Chrome kích hoạt mic ảo mới:
  * **Trên máy tính Windows:** Bấm phím **F5** trên bàn phím.
  * **Trên máy tính Mac:** Bấm tổ hợp phím **Command + R** trên bàn phím (hoặc bấm chuột vào **Biểu tượng mũi tên xoay tròn** nằm ở góc trên bên trái trình duyệt, cạnh thanh địa chỉ).

### Bước 4.4: Bấm nút chạy
* Bấm chuột thẳng vào **Biểu tượng chiếc Micro màu xám** trên Google Docs. *(Nếu máy Mac hiện popup hỏi quyền, bấm ngay **Cho phép / Allow**)*.
* Chiếc micro sẽ đổi sang **Màu đỏ tươi** và có vòng tròn nhấp nháy bao quanh.

### Bước 4.5: Đọc kết quả chạy thử
* **Trường hợp THÀNH CÔNG:**  
  Tai bạn vẫn nghe tiếng video thời sự nói rõ ràng, đồng thời trên trang giấy Google Docs, chữ tiếng Việt bắt đầu tự động tuôn ra thành hàng theo đúng từng lời nói. Hệ thống đã sẵn sàng 100%!
* **Trường hợp THẤT BẠI (Hiện thông báo "Không thể nghe thấy bạn" hoặc micro đỏ nhưng không ra chữ):**
  * *Cách sửa 1:* Kiểm tra xem bạn đã bấm tải lại trang (`F5` hoặc `Command + R`) ở Bước 4.3 chưa.
  * *Cách sửa 2:* Kiểm tra xem âm lượng của video YouTube có bị Mute (Tắt tiếng) không. Phải kéo âm lượng video lên mức cao.
  * *Cách sửa 3:* Bấm tắt micro đỏ đi và bấm bật lại một lần nữa.

---

## 5. Hướng dẫn cách ngồi họp thực tế trên Zoom và Google Meet

### 5.1. BẠN CHỌN PHƯƠNG ÁN 1 TRÌNH DUYỆT HAY 2 TRÌNH DUYỆT?

#### 👉 PHƯƠNG ÁN A: DÙNG 1 TRÌNH DUYỆT CHROME DUY NHẤT (Khuyên dùng - Rất tiện lợi)
* **Nếu bạn họp bằng ứng dụng ZOOM hoặc TEAMS trên máy tính:**  
  * Cực kỳ dễ dàng: Mở phần mềm Zoom/Teams lên họp như bình thường.
  * Mở trình duyệt Chrome ở một nửa màn hình để mở Google Docs (bật Micro đỏ để chép lời). Không cần cài thêm bất kỳ trình duyệt nào khác!
* **Nếu bạn họp bằng GOOGLE MEET ngay trên Chrome:**  
  * Mở 2 cửa sổ Chrome và đặt cạnh nhau (Một cửa sổ chạy Google Meet để họp, một cửa sổ mở Google Docs để chép lời).
  * **CỰC KỲ QUAN TRỌNG - Quy tắc 2 Micro độc lập:**
    * **Tại cửa sổ Google Meet (để bạn phát biểu):** Bấm nút ba chấm `⋮` ở đáy màn hình Meet -> *Cài đặt* -> *Âm thanh* -> Mục **Microphone** chọn đúng **Micro thật của bạn** (Mic tai nghe hoặc Mic laptop) để người khác nghe thấy bạn nói.
    * **Tại cửa sổ Google Docs (để máy tự chép lời):** Chọn Micro là **Sợi dây ảo** (`CABLE Output` hoặc `BlackHole 2ch`) theo đúng hướng dẫn ở Bước 4.3.  
    *(Chrome rất thông minh, nó cho phép trang Meet dùng micro thật còn trang Docs dùng micro ảo cùng lúc mà không hề bị xung đột).*

#### 👉 PHƯƠNG ÁN B: DÙNG 2 TRÌNH DUYỆT KHÁC NHAU (Dành cho người sợ chỉnh nhầm Micro)
* Đặt trình duyệt **Firefox** ở một bên màn hình (dùng để vào link Google Meet hoặc Zoom web).
* Đặt trình duyệt **Google Chrome** ở một bên màn hình (dùng để mở Google Docs chép chữ).

---

### 5.2. Ba nguyên tắc an toàn tuyệt đối (Không bao giờ được vi phạm)

| NGUYÊN TẮC | LÝ DO VÀ CÁCH XỬ LÝ AN TOÀN |
| :--- | :--- |
| **1. KHÔNG thu nhỏ (Minimize) cửa sổ Chrome** | Nếu bạn bấm nút dấu trừ `_` để ẩn cửa sổ Chrome xuống thanh đáy màn hình, máy tính sẽ đưa tab Chrome vào trạng thái ngủ để tiết kiệm pin -> **Tính năng chép lời sẽ bị ngắt ngay.** <br>👉 *Hãy luôn để cửa sổ Chrome hiển thị trên màn hình (dù chỉ chiếm một góc nhỏ).* |
| **2. KHÔNG chia sẻ toàn bộ màn hình (Entire Screen)** | Nếu đến lượt bạn thuyết trình, nếu chọn chia sẻ toàn màn hình, đối tác sẽ nhìn thấy cửa sổ Google Docs đang chép lời của họ. <br>👉 *Khi bấm Share màn hình, hãy luôn chọn mục **"Một cửa sổ" (Window)** hoặc **"Một thẻ" (Tab)** để chỉ hiển thị đúng slide bài giảng.* |
| **3. KHÔNG bấm Mute (Tắt tiếng) trên phần mềm/video** | Nếu bạn tắt tiếng trên video hoặc bấm Mute loa cuộc họp trên phần mềm, âm thanh đi vào sợi dây ảo sẽ bằng 0 -> **Google Docs sẽ không nghe thấy gì để gõ chữ.** <br>👉 *Luôn để âm lượng cuộc họp từ 50% trở lên. Nếu thấy ồn tai, hãy bấm nút giảm âm lượng vật lý trực tiếp trên chiếc tai nghe của bạn.* |

---

## 6. Mẹo đổi loa ngoài và tai nghe linh hoạt mà không làm mất chữ

### Đối với máy Mac:
* Nhờ bạn đã **tích chọn cả 3 ô (BlackHole, Tai nghe và MacBook Speakers)** ngay từ Thao tác 2.3 / 1.3 ở Bước 1, nên hệ thống của bạn đã là hệ thống **tự động hoàn toàn**:
  * Khi bạn cắm tai nghe: Âm thanh sẽ phát vào tai nghe và đồng thời truyền vào Google Docs để gõ chữ.
  * Khi bạn rút tai nghe ra: Âm thanh sẽ tự động phát ra loa ngoài của máy và Google Docs **vẫn chép lời bình thường 100% không hề bị đứt quãng một giây nào**.
  * Nếu bạn dùng tai nghe Bluetooth và không muốn loa ngoài kêu: Chỉ cần vặn nhỏ âm lượng loa máy tính hoặc tắt loa ngoài, tai nghe Bluetooth vẫn nghe và Google Docs vẫn chạy mượt mà.

### Đối với máy Windows:
* Nhấn phím `Windows + R`, nhập `mmsys.cpl` rồi ấn **Enter**.
* Chuyển sang thẻ **Recording**, bấm đúp chuột vào chữ **CABLE Output** (hoặc Stereo Mix) -> Chọn thẻ **Listen**.
* Ở mục *Playback through this device*, bấm đổi từ tên chiếc tai nghe sang chữ **Speakers (Realtek Audio...)** (Loa ngoài của máy) -> Bấm **OK**.
* Âm thanh cuộc họp sẽ ngay lập tức chuyển sang phát qua loa ngoài mà dòng chữ trên Google Docs không hề bị gián đoạn.
