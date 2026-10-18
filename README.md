# [MINI PROJECT] XÂY DỰNG PRODUCT BACKLOG VÀ KẾ HOẠCH SPRINT CHO DỰ ÁN MOTOGO

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Hạng mục 1: Phân rã Epic – Feature

Link bảng Trello công khai của nhóm: https://trello.com/b/motogo_it206_k25

Dưới đây là phần phân rã cấu trúc từ Epic xuống Feature, bám sát các giá trị nghiệp vụ cốt lõi của nền tảng du lịch và cho thuê xe máy MotoGo tại Vũng Tàu và Đà Nẵng:

- Epic 1: Trải nghiệm tìm kiếm và đặt xe liền mạch. Giá trị mang lại: Giúp khách du lịch nhanh chóng tìm thấy chiếc xe ưng ý, xem lịch trống chính xác và giữ chỗ thành công mà không lo bị trùng lặp thời gian. Bao gồm Feature 1.1 (Tìm kiếm và lọc xe theo thời gian, địa điểm) và Feature 1.2 (Giữ chỗ và thanh toán tiền cọc tạm thời).
- Epic 2: Quản lý kho xe và vận hành cửa hàng hiệu quả. Giá trị mang lại: Giúp các chủ cửa hàng cho thuê xe kiểm soát chặt chẽ trạng thái đội xe, lịch trình đặt xe và xác nhận đơn hàng nhanh chóng mà không xảy ra xung đột lịch. Bao gồm Feature 2.1 (Xác nhận/Từ chối đơn đặt xe và quản lý lịch trình) và Feature 2.2 (Quản lý danh mục xe, thông tin kỹ thuật và kho bãi).
- Epic 3: Quy trình bàn giao xe minh bạch và tin cậy. Giá trị mang lại: Xây dựng cơ sở pháp lý và bằng chứng rõ ràng khi giao nhận xe giữa hai bên, hạn chế tối đa tranh chấp về tình trạng xe và nhiên liệu. Bao gồm Feature 3.1 (Lập biên bản bàn giao xe tại cửa hàng có hình ảnh hiện trạng) và Feature 3.2 (Xác nhận hoàn trả xe và kiểm tra kết thúc hợp đồng).

## Hạng mục 2: Danh sách User Story

Hệ thống bao gồm 8 User Story đại diện cho các nhóm nghiệp vụ chính, truy vết trực tiếp tới các mã yêu cầu chức năng (FR) và nghiệp vụ (BR) trong SRS.

- US-01: Là khách thuê, tôi muốn giữ chỗ chiếc xe vừa chọn để không bị người khác đặt mất trong lúc tôi thanh toán. | Truy vết: FR-10, BR-05 | Mức ưu tiên: Must | Story Point: 5
- US-02: Là khách thuê, tôi muốn tìm kiếm xe máy theo địa điểm Vũng Tàu hoặc Đà Nẵng và khung thời gian cụ thể để biết xe nào còn trống. | Truy vết: FR-02, BR-01 | Mức ưu tiên: Must | Story Point: 3
- US-03: Là chủ cửa hàng, tôi muốn nhận thông báo khi có đơn đặt xe mới để xem xét và xác nhận hoặc từ chối kịp thời. | Truy vết: FR-12, BR-02 | Mức ưu tiên: Must | Story Point: 3
- US-04: Là nhân viên cửa hàng, tôi muốn cập nhật trạng thái kho xe tránh việc trùng lịch đặt cho cùng một chiếc xe. | Truy vết: FR-15, BR-03 | Mức ưu tiên: Should | Story Point: 5
- US-05: Là khách thuê, tôi muốn xem chi tiết thông tin xe gồm hãng xe, dung tích, giá thuê ngày và đánh giá từ người dùng trước. | Truy vết: FR-04 | Mức ưu tiên: Should | Story Point: 2
- US-06: Là khách thuê, tôi muốn hủy đơn đặt xe trước thời gian nhận xe 24 giờ để được hoàn lại tiền cọc. | Truy vết: FR-11, BR-06 | Mức ưu tiên: Could | Story Point: 3
- US-07: Là chủ cửa hàng, tôi muốn xem báo cáo thống kê doanh thu và số lượng xe cho thuê trong tháng. | Truy vết: FR-20 | Mức ưu tiên: Won't | Story Point: 8
- US-08: Là khách thuê, tôi muốn liên hệ trực tiếp với cửa hàng qua khung chat nội bộ khi cần hỗ trợ khẩn cấp. | Truy vết: FR-25 | Mức ưu tiên: Could | Story Point: 3

## Hạng mục 3: Bảng tự đánh giá INVEST

Chọn 3 User Story bất kỳ để kiểm tra chất lượng theo 6 tiêu chí INVEST:

- Giải thích lý do story US-07 chưa đạt tiêu chí Small: Story US-07 yêu cầu làm báo cáo thống kê tổng hợp toàn bộ doanh thu và lịch sử cho thuê, phạm vi quá lớn và phức tạp cho một sprint thông thường, cần phải tách nhỏ thành các báo cáo thành phần.
- Bản gốc US-07: Là chủ cửa hàng, tôi muốn xem báo cáo thống kê toàn bộ doanh thu và lịch sử cho thuê trong tháng để nắm bắt tình hình kinh doanh.
- Bản sau khi sửa và tách nhỏ:
- US-07A: Là chủ cửa hàng, tôi muốn xem tổng doanh thu theo ngày trong tháng để theo dõi dòng tiền. (Story Point: 3)
- US-07B: Là chủ cửa hàng, tôi muốn xem biểu đồ tỷ lệ loại xe nào được thuê nhiều nhất trong tháng để tối ưu kho. (Story Point: 5)

| Mã Story | Independent (Độc lập) | Negotiable (Thương lượng được) | Valuable (Có giá trị) | Estimatable (Ước lượng được) | Small (Nhỏ gọn) | Testable (Kiểm thử được) |
| --- | --- | --- | --- | --- | --- | --- |
| US-01 | Đạt | Đạt | Đạt | Đạt | Đạt | Đạt |
| US-03 | Đạt | Đạt | Đạt | Đạt | Đạt | Đạt |
| US-07 | Đạt | Đạt | Đạt | Đạt | Chưa đạt | Đạt |

## Hạng mục 4: Acceptance Criteria

Viết các tiêu chí nghiệm thu cho 3 story có mức ưu tiên cao nhất theo cấu trúc Given - When - Then, bao gồm cả luồng chính và ngoại lệ, có tham chiếu quy tắc nghiệp vụ BR.

- US-01: Là khách thuê, tôi muốn giữ chỗ chiếc xe vừa chọn để không bị người khác đặt mất trong lúc tôi thanh toán.
- - AC-01 (luồng chính): Given khách đã chọn xe còn trống và bấm đặt, When hệ thống tạo đơn thành công, Then xe được giữ chỗ 30 phút và không hiển thị cho khách khác.
- - AC-02 (ngoại lệ): Given đơn đang ở trạng thái chờ thanh toán, When quá 30 phút mà khách chưa thanh toán cọc, Then đơn tự động hủy và xe được mở lại trong kết quả tìm kiếm.
- - AC-03 (quy tắc nghiệp vụ BR-05): Given khách thực hiện đặt xe, When thời điểm chọn trùng với lịch đã có đơn xác nhận trước đó, Then hệ thống từ chối giữ chỗ và hiển thị thông báo 'Xe đã có người đặt'.
- 
- US-02: Là khách thuê, tôi muốn tìm kiếm xe máy theo địa điểm Vũng Tàu hoặc Đà Nẵng và khung thời gian cụ thể để biết xe nào còn trống.
- - AC-01 (luồng chính): Given khách chọn địa điểm Vũng Tàu và nhập khoảng thời gian từ ngày A đến ngày B, When khách bấm tìm kiếm, Then hệ thống trả về danh sách các xe còn trống trong khung giờ đó.
- - AC-02 (ngoại lệ): Given khách nhập thời gian trả xe trước thời gian nhận xe, When khách bấm tìm kiếm, Then hệ thống hiển thị thông báo lỗi 'Thời gian không hợp lệ'.
- - AC-03 (quy tắc nghiệp vụ BR-01): Given hệ thống tiếp nhận yêu cầu tìm kiếm, When khu vực nằm ngoài Vũng Tàu hoặc Đà Nẵng, Then hệ thống từ chối và hiển thị 'Chưa hỗ trợ khu vực này'.
- 
- US-03: Là chủ cửa hàng, tôi muốn nhận thông báo khi có đơn đặt xe mới để xem xét và xác nhận hoặc từ chối kịp thời.
- - AC-01 (luồng chính): Given có khách mới đặt xe thành công, When hệ thống gửi thông báo đến tài khoản chủ cửa hàng, Then chủ cửa hàng thấy hiển thị đơn hàng mới trong danh sách chờ xử lý.
- - AC-02 (ngoại lệ): Given chủ cửa hàng không thao tác xác nhận đơn trong vòng 2 giờ kể từ khi tạo, When hết thời gian chờ, Then hệ thống tự động chuyển đơn sang trạng thái 'Hết hạn chờ duyệt' và thông báo cho khách.
- - AC-03: Given chủ cửa hàng mở chi tiết đơn mới, When bấm nút 'Xác nhận đơn', Then trạng thái chuyển thành 'Đã xác nhận' và kho xe tự động trừ số lượng xe tương ứng.

## Hạng mục 5: Definition of Done (DoD)

Bộ điều kiện hoàn thành (DoD) áp dụng chung cho mọi User Story trong dự án MotoGo:

1. Mã nguồn đã được kiểm tra và vượt qua ít nhất 80% độ bao phủ unit test (Có/Không?).

2. Đã được Review code bởi ít nhất một thành viên khác trong Development Team (Có/Không?).

3. Đã viết đủ Acceptance Criteria và kiểm thử thủ công không còn lỗi nghiêm trọng (Có/Không?).

4. Đã cập nhật tài liệu API và tài liệu hướng dẫn sử dụng liên quan (Có/Không?).

5. Đã được Product Owner nghiệm thu trực tiếp trên môi trường Staging (Có/Không?).



Phân biệt DoD và Acceptance Criteria kèm ví dụ:

- Acceptance Criteria (AC) là các điều kiện cụ thể để xác định một User Story đơn lẻ có đạt yêu cầu nghiệp vụ của người dùng hay không. Ví dụ (từ US-01): Hệ thống phải giữ chỗ xe trong vòng 30 phút khi khách bấm đặt.

- Definition of Done (DoD) là tập hợp các tiêu chuẩn kỹ thuật chung mà toàn bộ mọi User Story phải đạt được trước khi được công nhận là hoàn thành toàn diện để phát hành. Ví dụ: Code phải được review và vượt qua unit test.

## Hạng mục 6: Prioritized Product Backlog

Toàn bộ User Story được phân loại theo mức độ ưu tiên MoSCoW. Tỷ lệ hạng mục Must không vượt quá 50% tổng số lượng story.

- Giải trình lý do xếp hạng các hạng mục:
- - US-01 và US-02 thuộc Must: Bám sát mục tiêu 'Khách tìm xe còn trống và đặt giữ chỗ', là luồng cốt lõi bắt buộc phải có để hệ thống vận hành giao dịch đầu tiên.
- - US-03 thuộc Must: Bám sát mục tiêu 'Cửa hàng xác nhận đơn và quản lý kho xe', giúp chủ cửa hàng không bị mất kiểm soát đơn hàng.
- - US-04 thuộc Should: Hỗ trợ quản lý kho xe chi tiết nhưng có thể xử lý thủ công ở giai đoạn đầu nếu lượng xe chưa quá lớn.
- - US-07 được xếp Won't: Chưa làm ở phiên bản đầu tiên vì mục tiêu trọng tâm của MVP là kết nối và xử lý đặt xe thực tế tại Vũng Tàu và Đà Nẵng, các tính năng báo cáo tài chính nâng cao sẽ đưa vào Backlog của phiên bản 2.

| Mã Story | Tên User Story | Mức MoSCoW | Story Point | Mục tiêu kinh doanh gắn kết |
| --- | --- | --- | --- | --- |
| US-01 | Giữ chỗ xe trong lúc thanh toán | Must | 5 | Khách tìm xe còn trống và đặt giữ chỗ |
| US-02 | Tìm kiếm xe theo địa điểm và thời gian | Must | 3 | Khách tìm xe còn trống và đặt giữ chỗ |
| US-03 | Nhận thông báo và xác nhận đơn | Must | 3 | Cửa hàng xác nhận đơn và quản lý kho xe |
| US-04 | Cập nhật trạng thái kho xe | Should | 5 | Cửa hàng xác nhận đơn và quản lý kho xe |
| US-05 | Xem chi tiết thông tin xe | Should | 2 | Khách tìm xe còn trống và đặt giữ chỗ |
| US-06 | Hủy đơn đặt xe trước 24 giờ | Could | 3 | Khách tìm xe còn trống và đặt giữ chỗ |
| US-07 | Xem báo cáo thống kê doanh thu | Won't | 8 | Ngoài phạm vi phiên bản MVP đầu tiên |
| US-08 | Liên hệ trực tiếp qua khung chat | Could | 3 | Hai bên lập biên bản giao nhận xe |

## Hạng mục 7: Bảng ước lượng Story Point

Chọn story chuẩn US-02 làm mốc với giá trị 3 Story Point. Các story khác được ước lượng dựa trên phương pháp so sánh tương đối theo thang Fibonacci (1, 2, 3, 5, 8, 13):

- Lưu ý: Không có story nào vượt quá 13 điểm nên không cần phải tiến hành tách nhỏ thêm trong đợt này.

| Mã Story | Story Point | Căn cứ so sánh tương đối với story chuẩn (US-02: 3 điểm) |
| --- | --- | --- |
| US-01 | 5 | Độ phức tạp cao hơn US-02 do cần xử lý logic đếm ngược thời gian giữ chỗ 30 phút và đồng bộ trạng thái kho. |
| US-02 | 3 | Chọn làm story chuẩn mốc cơ sở cho các chức năng tìm kiếm cơ bản. |
| US-03 | 3 | Độ phức tạp tương đương US-02, bao gồm gửi thông báo đẩy và cập nhật trạng thái đơn hàng đơn giản. |
| US-04 | 5 | Tương tự US-01, đòi hỏi kiểm tra logic xung đột lịch trình kho xe giữa nhiều chi nhánh. |
| US-05 | 2 | Chỉ hiển thị thông tin tĩnh và đánh giá, ít logic phức tạp hơn US-02. |
| US-06 | 3 | Logic hủy đơn và hoàn tiền cọc có điều kiện thời gian tương đương độ khó của việc lọc tìm kiếm. |
| US-07 | 8 | Yêu cầu tổng hợp dữ liệu lớn từ nhiều bảng cơ sở dữ liệu và xử lý biểu đồ phức tạp. |
| US-08 | 3 | Tích hợp khung chat thời gian thực ở mức cơ bản. |

## Hạng mục 8: Kế hoạch Sprint 1

Sprint Goal: Hoàn thiện luồng cốt lõi giúp khách du lịch tại Vũng Tàu và Đà Nẵng dễ dàng tìm kiếm, chọn xe trống và giữ chỗ thành công, đồng thời giúp cửa hàng xác nhận đơn hàng nhanh chóng.

Velocity giả định cho Sprint 1 là 14 điểm. Sprint Backlog bao gồm các story: US-01 (5 điểm), US-02 (3 điểm), US-03 (3 điểm), và US-05 (2 điểm). Tổng cộng là 13 điểm (nhỏ hơn velocity giả định 14 điểm).



Bảng phân rã task cho User Story US-01 (5 điểm):

- Bảng capacity cá nhân cho Sprint 1 (Sprint kéo dài 10 ngày làm việc, mỗi ngày 6 giờ làm việc thực tế sau khi trừ họp hành và dự phòng 2 giờ):
- - Thành viên 1 (Dev Backend): 10 ngày x 6 giờ = 60 giờ.
- - Thành viên 2 (Dev Frontend): 10 ngày x 6 giờ = 60 giờ.
- - Thành viên 3 (Tester / PO): 10 ngày x 6 giờ = 60 giờ.
- Tổng capacity của Scrum Team (3 thành viên) là 180 giờ làm việc trong suốt Sprint 1, đảm bảo dư sức hoàn thành các task kỹ thuật của Sprint Backlog.

| Mã Task | Nội dung công việc | Người thực hiện | Số giờ dự kiến |
| --- | --- | --- | --- |
| TASK-01-01 | Thiết kế cơ sở dữ liệu bảng Booking và trạng thái giữ chỗ | Backend Dev | 4 giờ |
| TASK-01-02 | Viết API xử lý logic giữ chỗ xe trong 30 phút | Backend Dev | 6 giờ |
| TASK-01-03 | Xây dựng giao diện màn hình xác nhận đặt xe và nút thanh toán cọc | Frontend Dev | 6 giờ |
| TASK-01-04 | Viết Unit Test cho luồng giữ chỗ và timeout tự động hủy đơn | Tester / Dev | 4 giờ |
| TASK-01-05 | Kiểm thử tích hợp toàn bộ luồng US-01 trên môi trường Staging | Tester | 4 giờ |

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
