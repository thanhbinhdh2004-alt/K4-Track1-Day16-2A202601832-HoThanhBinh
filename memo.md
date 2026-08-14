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
| Đặc điểm | Người dùng “tự tổ chức” hoặc người sáng tạo/nhà quản lý nhỏ: founder, PM, designer, content creator, freelancer; thích tính linh hoạt, có nhu cầu lưu trữ tri thức cá nhân và tự dựng workflow; sẵn sàng thử nghiệm nhiều template/khung cấu trúc khác nhau | Team nhỏ đến trung bình hoặc bộ phận vận hành/marketing/operations: cần một “source of truth” chung cho docs, tasks, wiki, meeting notes, project tracking; làm việc theo nhóm, cần collaboration, quyền truy cập, templates và AI hỗ trợ search/summarize |
| JTBD chính | “Tạo nơi duy nhất để ghi chú, lưu ý, ý tưởng và tổ chức công việc cá nhân theo cách của mình.” | “Tổ chức tri thức, công việc và tiến độ của cả team trong một hệ thống duy nhất; tìm thông tin nhanh, chia sẻ công việc rõ ràng và giảm công việc lặp lại bằng automation/AI.” |
| Trước đó họ làm bằng cách nào | Dùng notes app kèm file lưu trữ cá nhân, task list, docs, spreadsheet, email, và nhiều tool riêng biệt; thường tự “hack” cấu trúc bằng folders/templates, chồng ghép giữa Google Docs, Trello, Evernote, Slack,... | Dùng mix của Docs/Drive, Jira/Asana, Confluence, Slack/Teams, Calendar, Notepad, spreadsheets; mỗi team có “một bộ tool riêng” và dữ liệu bị tản mát giữa nhiều hệ thống |

**Dịch chuyển tệp:** Tệp user dịch chuyển từ “người dùng cá nhân, chú trọng tính linh hoạt và cá nhân hóa” sang “team/organization, chú trọng collaboration + process + data as shared asset”. Sự dịch chuyển này diễn ra chủ yếu qua các mốc quan trọng ở §1:

- 2018: Notion 2.0 đưa database + wiki + collaboration, chuyển Notion từ “note app” thành “all-in-one workspace”. Đây là bước đầu khiến tool phù hợp với team và workflow hơn là chỉ cá nhân.
- 2020: bỏ giới hạn blocks trên free tier khiến người dùng cá nhân cắm rễ dữ liệu trong Notion, tạo mô hình “dùng nhiều rồi mới nâng cấp”. Điều này làm tăng độ bám dính trước khi team bắt đầu chuyển sang dùng chung.
- 2021: API làm cho Notion trở thành nền tảng, không còn là app đơn lẻ. Team/agency/agency-like business bắt đầu nhúng Notion vào automations và workflow riêng.
- 2022–2024: AI + Calendar gắn thêm value cho usage hàng ngày và workspace-level context. Đây là thời điểm Notion không chỉ là nơi lưu trữ, mà là nơi “điều phối việc làm” của cả nhóm.
- 2025: AI bundle vào Business/Enterprise chuyển Notion từ “tool hạng nhì” sang “standard operating system” của một số team, giúp dễ hơn nhiều để có một workspace dùng chung cho docs + task + knowledge + agent.

Nói cách khác, Notion đã đi từ “giải quyết nhu cầu cá nhân có thể viết ghi chú tốt hơn” sang “giải quyết nhu cầu tổ chức thông tin và vận hành công việc của cả team”.

**Switching cost (map 4 forces):** Notion giữ user ở lại không chỉ vì đẹp hay linh hoạt, mà vì dữ liệu và quy trình đã được tích hợp sâu vào hệ thống. Có thể map theo 4 lực sau:

1. Data lock-in: Workspace chứa pages, databases, linked relations, templates, history, content và knowledge base; chuyển ra khỏi Notion mất chi phí cao về tái cấu trúc và tìm lại thông tin.
2. Process lock-in: Team đã xây sẵn workflow trên database, templates, views, permissions, tags, automations; thay đổi tool nghĩa là tái thiết lại cả quy trình vận hành.
3. Social lock-in: Thông tin, meeting notes, task, wiki, PMS, backlog đều được chia sẻ trong không gian công việc chung; cả team đã quen với “đi đúng chỗ” của mọi thứ.
4. Ecosystem lock-in: API, integrations, calendar, AI context và workspaces gắn chặt với phần còn lại của stack; đối với doanh nghiệp/nhóm nhỏ, rời Notion không chỉ là “đổi app” mà là “đổi cả hệ thống làm việc”.

Lực kéo đi (pull-away forces) thì cũng rõ ràng:

- Các tool chuyên biệt như Jira/Asana cho quản lý dự án, Google Workspace/Microsoft 365 cho collaboration cực mạnh, Slack/Teams cho chat, Obsidian/Apple Notes cho lưu trữ cá nhân, ClickUp/Monday cho người thích workflow có cấu trúc hơn.
- Một số user thấy Notion quá linh hoạt nhưng thiếu “sự chắc chắn” và “bộ khung chuẩn” của hệ thống chuyên biệt; họ muốn không gian rõ ràng hơn, ít “một trang chồng lên nhiều ý nghĩa”.
- AI và Big Tech bundle cũng tạo áp lực: nếu Google/Microsoft đưa AI ngay vào suite làm việc, một number of users sẽ cân nhắc di chuyển tích hợp trong ecosystem hiện có.

Vì vậy, switching cost của Notion mạnh nhất khi user đã gắn dữ liệu + workflow + team collaboration vào workspace, nhưng vẫn bị đe dọa ở phần “người dùng muốn độ chuyên biệt và tích hợp sâu trong hệ sinh thái mà họ đã quen”.

---

## §3. Ba dự đoán hướng đi (6–12 tháng tới)

<!-- Cách làm: mỗi người viết nháp ít nhất 1 dự đoán kèm lập luận,
     cả nhóm chất vấn "dựa vào mốc nào? tệp nào?" rồi mài lại thành 3 cái chung. -->

**Dự đoán 1** *(loại: mở rộng segment)*
- **Dự đoán:** Notion sẽ ra các Agent template dựng sẵn theo phòng ban/ngành (CSKH, IT helpdesk, sales ops) để bán sâu hơn vào doanh nghiệp lớn, thay vì chỉ để user tự cấu hình Agent từ đầu.
- **Lập luận:** mốc 09/2025 — Notion 3.0 (§1) đã hé lộ "Custom Agents" xử lý customer feedback/IT requests; tệp hiện tại đã dịch chuyển sang team/organization cần "một hệ thống vận hành chung" (§2) — bước hợp lý tiếp theo là đóng gói sẵn use case theo phòng ban thay vì để mỗi team tự mò.

**Dự đoán 2** *(loại: mô hình kiếm tiền)*
- **Dự đoán:** Notion sẽ chuyển một phần giá AI sang mô hình tính theo mức dùng Agent (agent credits/usage-based) thay vì chỉ gộp cứng vào giá seat Business/Enterprise như hiện tại.
- **Lập luận:** mốc 05/2025 (§1) cho thấy Notion sẵn sàng đổi cả mô hình tiền tệ hoá AI (bỏ add-on, gộp vào tier); Agent giờ chạy tác vụ đa bước tốn compute hơn nhiều so với text completion, nên khó giữ mãi flat-fee khi Agent càng làm nhiều việc thay user.

**Dự đoán 3** *(loại: đe dọa Big Tech)*
- **Dự đoán:** Notion sẽ đẩy mạnh AI Connectors (Slack, GitHub, Outlook, Box…) để trở thành "lớp context" tổng hợp dữ liệu xuyên nhiều tool, thay vì đấu trực diện "AI ai giỏi hơn" với Microsoft Copilot/Google Gemini.
- **Lập luận:** phân tích switching cost ở §2 chỉ ra rủi ro lớn nhất là Big Tech bundle AI sẵn trong suite hiện có của user; nguyên lý "Vertical AI/moat từ domain context" ở mốc 09/2025 (§1) cho thấy Notion đặt cược vào việc sở hữu ngữ cảnh xuyên nhiều tool — thứ Copilot/Gemini (chỉ chạy trong hệ sinh thái riêng của họ) khó sao chép.

---

## §4. AI Log

<!-- Cách làm: mỗi người tự khai phần việc của mình (không ai khai hộ ai). -->

| Việc | AI làm hay nhóm làm? | Nhóm kiểm chứng/phán đoán lại thế nào? |
|---|---|---|
| Hồ Thanh Bình: tổng hợp chuỗi timeline từ changelog/blog và chọn các mốc quan trọng để đưa vào §1. | AI hỗ trợ tổng hợp và gợi ý cấu trúc; nhóm làm kiểm tra, chọn lọc và quyết định cuối cùng. | Nhóm mở lại các link gốc, loại bỏ mốc chỉ là feature update hoặc nâng cấp model, và giữ lại các mốc có ảnh hưởng rõ tới JTBD, pricing hoặc nền tảng. |
| Nguyễn Thị Việt Vinh: phân tích tệp user, JTBD, switching cost và mô hình lock-in để viết §2. | AI hỗ trợ sắp xếp logic và gợi ý nhánh phân tích; nhóm làm chính việc xác nhận bằng chứng và chỉnh lại câu chữ. | Nhóm đọc lại từng đoạn để đảm bảo lập luận đi từ data, collaboration, process, ecosystem lock-in, không chỉ dựa vào nhận định chung về AI. |
| Cả nhóm: viết ba dự đoán hướng đi 6–12 tháng tới và đối chiếu với các nguyên lý ở §1–§2. | Nhóm làm chính; AI chỉ hỗ trợ sắp xếp phrasing và kiểm tra tính hợp lý của câu văn. | Nhóm chất vấn từng dự đoán theo ba tiêu chí: có dựa trên mốc nào, đúng trục nào (segment/pricing/ecosystem), và có đủ bằng chứng để vượt qua phản biện. |
| Ghép memo vào 4 phần hoàn chỉnh và rà soát lại toàn bộ bài trước khi nộp. | Nhóm làm chính; AI hỗ trợ gợi ý chỉnh dạng, flow và độ rõ ràng. | Nhóm đọc lại cả file 1 lượt, sửa lỗi logic, kiểm tra độ nhất quán giữa timeline, JTBD và dự đoán, rồi chốt phiên bản final. |


