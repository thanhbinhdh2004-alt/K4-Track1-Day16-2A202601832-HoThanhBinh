# Memo Teardown — Notion

**Nhóm: ABC** · **2 Thành viên:**

| Họ tên | MSSV |
|---|---|
| Hồ Thanh Bình | 2A202601832 |
| Nguyễn Thị Việt Vinh | 2A202601836 |


**Vì sao chọn sản phẩm này:** Notion đi từ một workspace ghi chú thuần túy thành nền tảng có AI Agent thao tác xuyên toàn bộ dữ liệu công ty, nên AI không phải tính năng phụ mà đã trở thành lý do định giá lại cả sản phẩm (§1, mốc 05/2025 và 09/2025). Sản phẩm có 10 năm changelog/blog/báo chí công khai để dựng timeline, và JTBD chuyển dịch rõ từ "cá nhân ghi chú" sang "doanh nghiệp vận hành qua agent" — đủ chất liệu để phân tích tệp user và dự đoán hướng đi.

---

## §1. Timeline các cập nhật lớn

<!-- DRAFT do AI research — nhóm PHẢI tự mở lại từng link nguồn để kiểm chứng trước khi chốt (yêu cầu bắt buộc của lab),
     và chất vấn chéo lại nguyên lý ở mỗi mốc trước khi coi là final. Khai vào §4 AI Log. -->

| Thời điểm | Cập nhật | Context lúc đó | Nguyên lý |
|---|---|---|---|
| 03/2016 | [Notion 1.0 ra mắt lại](https://bullet.so/blog/history-of-notion-everything-from-users-funding-and-more/) sau khi viết lại toàn bộ từ đầu ở Kyoto (tiền thân "Folio" thất bại, gần hết vốn) | Đội co về vài người, founder vay tiền gia đình để cứu công ty; phải đặt cược lại từ đầu | **x10** — không vá sản phẩm cũ, đặt cược toàn bộ vào một primitive nền tảng mới (block làm đơn vị dựng mọi thứ) thay vì thêm tính năng lên nền cũ |
| 03/2018 | [Notion 2.0](https://bullet.so/blog/history-of-notion-everything-from-users-funding-and-more/): thêm databases, wiki, collaboration → thành "all-in-one workspace" | Thị trường đang phân mảnh: Evernote (note), Trello (task), Confluence (wiki) mỗi app một việc | **Wrapper/Moat** — để user tự dựng hệ thống riêng trên block + database khiến cấu trúc dữ liệu trở thành tài sản không copy-paste sang app khác được |
| 05/2020 | [Bỏ giới hạn 1.000 block trên gói Free cá nhân](https://techcrunch.com/2020/05/19/notion-drops-usage-limit-on-its-its-personal-free-tier/), mở unlimited blocks | Free tier giới hạn khiến user rời đi khi workspace lớn dần; PLG đang nóng (Airtable, Coda cạnh tranh mạnh) | **Liquidity trước, margin sau** — tối đa hoá số workspace "cắm rễ" dữ liệu trước, thu tiền sau qua nâng cấp gói khi đã khó rời đi |
| 05/2021 | [Ra mắt Notion API](https://www.notion.com/releases/2021-05-13) (public beta) | Hệ sinh thái no-code/low-code bùng nổ (Zapier, Airtable đã có API từ lâu); user muốn nối Notion với hàng nghìn app khác | **Moat qua nền tảng** — biến Notion từ một app đơn lẻ thành hạ tầng cho workflow khác dựng lên trên, tăng switching cost qua tích hợp |
| 11/2022 | [Notion AI ra mắt private alpha](https://www.notion.com/blog/introducing-notion-ai) (waitlist, đạt 1 triệu người sau 5 tuần) | Làn sóng AI-writing (Jasper, Copy.ai) đã chứng minh nhu cầu; Notion có early access model GPT-3/4 của OpenAI, ra alpha ngay trước khi ChatGPT public bùng nổ cả ngành | **Gắn AI vào đúng chỗ user đã có data sẵn** — AI không phải sản phẩm riêng mà là lớp tăng cường trên trang/database có sẵn, giữ moat từ dữ liệu hiện có thay vì cạnh tranh trực diện với ChatGPT |
| 06/2022 mua lại → 01/2024 [ra mắt Notion Calendar](https://techcrunch.com/2024/01/17/notion-launches-a-calendar-app/) | Mua Cron (calendar app vừa được Product Hunt vinh danh App of the Year) rồi tái skin thành app standalone | Calendar bị Google/Apple thống trị nhưng thiếu tích hợp sâu với công cụ năng suất | **Mở rộng bề mặt sản phẩm** — từ "workspace tài liệu" sang chiếm thêm điểm chạm hàng ngày, tăng tần suất mở app, giữ user trong hệ sinh thái |
| 05/2025 (hiệu lực 08/2025) | [Gộp Notion AI đầy đủ vào gói Business/Enterprise](https://www.usecarly.com/blog/notion-ai-pricing-change/), bỏ add-on $10 riêng cho tài khoản mới, giá Business tăng $15→$20/user/tháng | AI đã phổ biến ở mọi đối thủ (Google Workspace, Microsoft Copilot đều bundle sẵn); add-on riêng không còn đủ sức là điểm khác biệt để thu thêm tiền | **Định nghĩa lại "tốt"** — AI chuyển từ tính năng bán thêm thành tiêu chuẩn nền tảng; nguồn thu chuyển từ bán feature sang bán tier/seat |
| 09/2025 | [Notion 3.0: AI Agents](https://www.notion.com/releases/2025-09-18) — agent đa bước thao tác xuyên workspace, giữ nguyên quyền hạn user, nhớ ngữ cảnh qua thời gian | Cuộc đua agentic AI giữa các nền tảng (Microsoft Copilot Agents, Google Workspace) tăng tốc; model nền (Claude, GPT-5) đủ mạnh để thực thi tác vụ nhiều bước | **Vertical AI / moat từ domain context** — giá trị không nằm ở model (ai cũng dùng được Claude/GPT-5) mà ở việc agent có toàn bộ cấu trúc dữ liệu, quyền hạn, thói quen làm việc riêng của từng workspace — thứ model gốc không có |

**Vì sao chọn những mốc này:** (nhóm điền sau khi review) — các mốc bị loại nên gồm: Notion Projects (05/2023, chỉ là tính năng quản lý dự án trong workspace, không đổi segment/pricing/nguyên lý); các bản AI GA/update nhỏ lẻ trong 2023–2024 (nâng cấp model nền, không phải quyết định sản phẩm mới).

---

## §2. Tệp user & JTBD

<!-- Cách làm: chia đọc nguồn song song (review G2/App Store, community/Discord),
     mỗi người tự viết nháp JTBD trước, rồi đối chiếu chốt chung. -->

| | Early adopters | Tệp hiện tại |
|---|---|---|
| Đặc điểm | | |
| JTBD chính | | |
| Trước đó họ làm bằng cách nào | | |

**Dịch chuyển tệp:** cột mốc nào ở §1 gây ra sự dịch chuyển? Tại sao?

**Switching cost (map 4 forces):** điều gì giữ user ở lại? Lực nào đang kéo họ đi / giữ họ lại?

---

## §3. Ba dự đoán hướng đi (6–12 tháng tới)

<!-- Cách làm: mỗi người viết nháp ít nhất 1 dự đoán kèm lập luận,
     cả nhóm chất vấn "dựa vào mốc nào? tệp nào?" rồi mài lại thành 3 cái chung. -->

**Dự đoán 1** *(loại: mở rộng tính năng / segment / mô hình kiếm tiền / đe dọa Big Tech)*
- **Dự đoán:** …
- **Lập luận:** … *(dẫn ngược về §1–§2)*

**Dự đoán 2** *(loại: …)*
- **Dự đoán:** …
- **Lập luận:** …

**Dự đoán 3** *(loại: …)*
- **Dự đoán:** …
- **Lập luận:** …

---

## §4. AI Log

<!-- Cách làm: mỗi người tự khai phần việc của mình (không ai khai hộ ai). -->

| Việc | Phụ trách | Nhóm kiểm chứng/phán đoán lại thế nào? |
|---|---|---|
| | | |
| | | |
| | | |
