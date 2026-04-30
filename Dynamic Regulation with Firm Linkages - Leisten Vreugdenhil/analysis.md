# Dynamic Regulation with Firm Linkages: Evidence from Texas

- **Tác giả:** Matthew Leisten, Nicholas Vreugdenhil
- **Journal:** The Review of Economic Studies
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-01 (Asia/Saigon)
- **Nguồn bài báo chính:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdag013/8445259
- **Nguồn PDF dùng để phân tích:** https://nvreug.github.io/paper/dynamic_regulation.pdf
- **Trạng thái lưu trên GitHub:** `analysis.md`, `analysis.html`, và `analysis-style.css` được chuẩn bị để lưu trong thư mục `Dynamic Regulation with Firm Linkages - Leisten Vreugdenhil/` của repo `huylvu/00_reading`; `analysis.pdf` chưa tạo trong lượt này; PDF gốc của paper mới xác minh được nguồn công khai, chưa tải và lưu nhị phân vào repo trong lượt này.
- **Trạng thái lưu trên Google Drive:** Bỏ qua trong lượt này vì chưa có tuyến tạo Google Doc và tracker đúng thư mục đích một cách nhất quán.

## 1. Metadata

- **Tiêu đề paper:** Dynamic Regulation with Firm Linkages: Evidence from Texas
- **Tác giả:** Matthew Leisten, Nicholas Vreugdenhil
- **Journal:** The Review of Economic Studies
- **Năm / tình trạng xuất bản:** bài ReStud rất mới, published ngày 30 January 2026 trên Oxford Academic
- **Link bài báo:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdag013/8445259
- **Link PDF đã dùng để đọc:** https://nvreug.github.io/paper/dynamic_regulation.pdf

## 2. Executive summary

Paper hỏi một câu rất applied micro nhưng cũng rất rộng về policy design: khi regulator không thể kiểm tra hết mọi plant, liệu có nên tăng cường kiểm tra các plant chỉ vì chúng cùng chủ sở hữu với một plant từng vi phạm hay không. Nói cách khác, “linked regulation” có thực sự tạo thêm giá trị so với cách leo thang giám sát chỉ ở cấp plant hay không.

Để trả lời, tác giả xây dựng một framework động về moral hazard dưới regulation có liên kết giữa các plant trong cùng firm, rồi ước lượng framework đó bằng dữ liệu universe-level của 7,379 plant ở Texas giai đoạn 2012-2020, bao gồm score, inspection, violation, penalty, pollution, và mạng sở hữu firm. Điểm rất mạnh là họ quan sát trực tiếp cả plant score lẫn firm-wide score mà regulator dùng để target inspection.

Kết quả chính là linked regulation hoạt động rất tốt. Khi mô phỏng tăng ngân sách inspection đủ để xác suất bị kiểm tra tăng trung bình 10 điểm phần trăm, việc dành phần tăng thêm này cho linked regulation làm giảm social cost của violations mạnh hơn hẳn so với untargeted inspection, và cũng tốt hơn unlinked escalation. Phần lớn lợi ích không đến từ việc “đoán đúng plant xấu hơn”, mà đến từ cơ chế deterrence ở cấp firm: một violation ở plant A làm tăng scrutiny ở các plant đồng sở hữu khác, nên chủ sở hữu nội bộ hóa chi phí tương lai trên toàn portfolio.

Đây là paper đáng đọc vì nó kết nối rất đẹp ba thứ thường tách rời nhau: design của regulation, dynamic incentives, và firm organization. Nó không chỉ cho thấy linked regulation “có vẻ hay”, mà còn lượng hóa nó tốt hơn bao nhiêu, vì sao tốt hơn, và khi nào cơ chế đó có thể yếu đi.

## 3. Research question and motivation

### Câu hỏi nghiên cứu trung tâm

Linked regulation có hiệu quả hơn các cơ chế enforcement quen thuộc hay không, đặc biệt trong bối cảnh regulator có ngân sách hạn chế và chỉ quan sát được vi phạm thông qua inspection?

### Bối cảnh học thuật và thực tiễn

Trong rất nhiều setting thực tế, regulator không thể giám sát tất cả đối tượng liên tục. Environmental regulation là ví dụ điển hình: số plant bị điều tiết rất lớn, inspection tốn nguồn lực, và violations chỉ lộ ra khi có kiểm tra. Vì thế, bài toán không chỉ là “phạt nặng hay nhẹ”, mà còn là “nhắm vào đâu”.

Trong thực tế, nhiều cơ chế enforcement dùng escalation: plant từng vi phạm sẽ bị chú ý hơn ở tương lai. Texas đi xa hơn một bước: ngoài plant-specific score còn có firm-wide score, nghĩa là plant có thể bị tăng scrutiny vì hành vi của các plant khác cùng firm. Ý tưởng này rất tự nhiên nếu compliance costs hoặc management quality có tương quan trong nội bộ firm, nhưng trước paper này gần như chưa có lượng hóa nghiêm túc về giá trị thực của linked enforcement.

### Khoảng trống mà paper lấp vào

Văn liệu trước có nhiều bài về dynamic enforcement và repeated offenders, nhưng chủ yếu ở mức plant đơn lẻ. Khoảng trống là thiếu một framework thực nghiệm đủ linh hoạt để xử lý:

- portfolio lớn với nhiều plant đồng sở hữu
- decision interdependence giữa các plant trong cùng firm
- sự kết hợp giữa targeting value của information và deterrence value của punishment ở cấp firm

Paper này lấp đúng khoảng trống đó.

## 4. Main contribution

### Đóng góp 1: dữ liệu điều tiết rất hiếm và rất giàu

Tác giả xây dựng dữ liệu panel plant-year cho toàn bộ 7,379 plant chịu Resource Conservation and Recovery Act và/hoặc Clean Water Act tại Texas trong giai đoạn 2012-2020. Dữ liệu có ownership network, scores, inspections, violations, penalties, và pollution. Điểm đặc biệt là họ quan sát trực tiếp multidimensional score mà regulator thật sự dùng.

Điều này quan trọng vì nhiều paper regulation phải suy ngược latent enforcement state từ lịch sử inspection/violation. Ở đây, tác giả nhìn thấy gần như trực tiếp “dashboard” của regulator.

### Đóng góp 2: framework động về linked regulation

Paper phát triển một empirical framework kết hợp dynamic moral hazard với dynamic discrete choice. Firm chọn negligence/polluting actions ở từng plant, nhưng lựa chọn này phụ thuộc không chỉ score của plant đó mà còn firm-wide score, vì một violation có thể làm tăng scrutiny ở các plant khác trong portfolio.

Điểm mới thật sự nằm ở chỗ framework cho phép:

- portfolio lớn
- correlation trong types/compliance costs giữa các plant cùng firm
- equilibrium feedback giữa action, inspection, violation, score updates, và targeting

### Đóng góp 3: tách riêng hai cơ chế giá trị của linked regulation

Paper không dừng ở việc nói linked regulation tốt hơn. Nó còn decomposition được lợi ích thành:

- **correlated targeting mechanism:** links giúp regulator đoán plant nào đáng kiểm tra hơn
- **firm-wide moral hazard mechanism:** links làm chủ sở hữu sợ rằng sai phạm ở một plant sẽ kéo scrutiny tới cả portfolio

Đây là đóng góp rất đẹp vì nó biến một policy design tưởng như “black box” thành một cơ chế kinh tế có thể học và đem đi dùng ở setting khác.

## 5. Identification or methodology

### Setting thể chế

Texas Commission on Environmental Quality dùng hệ thống score hai chiều:

- **plant score:** phản ánh compliance history của từng plant
- **firm score:** phản ánh compliance history của các plant cùng chủ sở hữu

Các score này ảnh hưởng đến xác suất inspection trong tương lai. Nếu violation bị phát hiện, score được cập nhật, từ đó thay đổi deterrence động.

### Bằng chứng reduced-form trước khi vào structural model

Paper đi rất đúng trình tự.

1. Họ cho thấy violations per inspection có tương quan dương giữa một plant và các plant đồng sở hữu khác. Đây là bằng chứng gợi ý compliance costs hoặc management quality có tương quan trong firm.
2. Họ cho thấy inspection thực sự target các plant có plant score và firm score cao hơn.
3. Conditional on plant fixed effects, xác suất inspection cao hơn đi cùng violations thấp hơn, phù hợp với deterrence.

Reduced-form ở đây không đủ để kết luận welfare, nhưng đủ để chứng minh rằng linked regulation không phải vật trang trí thể chế.

### Mô hình structural

Mỗi plant có một type chi phối marginal cost of abatement, hay tương đương là marginal benefit của negligence/pollution. Types có thể tương quan trong firm và theo industry. Regulator commit một inspection policy mapping từ:

- industry
- plant score
- firm score

thành xác suất inspection.

Firm sau đó chọn action ở từng plant, nội bộ hóa:

- lợi ích hiện tại của negligence
- expected penalty hiện tại nếu bị inspection
- escalation trong tương lai
- spillover scrutiny sang các plant cùng firm

### Logic nhận dạng

Nhận dạng của paper diễn ra theo ba tầng:

1. **First stage:** ước lượng inspection function từ plant score, firm score, fixed effects theo năm, sector, vùng.
2. **Second stage:** dùng moments của violations theo sector, decomposition phương sai violations trong và ngoài firm, và độ nhạy của violations với inspection probability để nhận dạng mean types, variance components ở plant-level và firm-level, cùng curvature của payoff.
3. **Third stage:** dùng điều kiện tối ưu phân bổ inspection budget của regulator để suy ra relative marginal harms của pollution theo sector.

### Điểm kỹ thuật nổi bật

Thách thức lớn nhất là state space bùng nổ vì hành vi ở một plant phụ thuộc trạng thái của cả portfolio. Tác giả xử lý bằng giả định **continuation value sufficiency**: plant chỉ cần theo dõi plant score của chính nó và firm score chung, còn ảnh hưởng của toàn bộ phần còn lại của portfolio được gói vào một scalar continuation value xấp xỉ. Đây là chỗ “structural but disciplined”: không giả vờ giải full model khi việc đó bất khả thi, mà dùng một rút gọn có intuition kinh tế rõ.

### Điểm mạnh của phương pháp

- Quan sát trực tiếp score khiến mapping từ thể chế sang model rất chặt.
- Structural model dùng để trả lời đúng câu hỏi policy counterfactual mà reduced-form khó làm.
- Decomposition hai cơ chế là một lợi thế rất lớn về mặt diễn giải.

### Điểm dễ bị nghi ngờ

- Kết quả firm-wide moral hazard dựa một phần vào giả định regulator có thể commit vào policy rule.
- Relative social harms theo sector được suy ra từ allocation behavior của regulator, nên đó là “perceived social costs” hơn là welfare measure hoàn toàn khách quan.
- Continuation value sufficiency là một approximation cần tin tưởng ở mức nào đó, dù paper có làm model fit và robustness.

## 6. Results and interpretation

### Kết quả reduced-form chính

- Violations tại các plant đồng sở hữu có tương quan dương khá mạnh; paper báo cáo correlation khoảng 0.504 ở descriptive binscatter.
- Plant score và firm score đều dự báo xác suất inspection cao hơn.
- Một plant trung bình với hồ sơ “sạch” có xác suất inspection khoảng 28%; nếu plant và firm đều ở nhóm score rất xấu, xác suất này tăng lên khoảng 44%.
- Khi score tăng trong cùng một plant theo thời gian, violations có xu hướng giảm, phù hợp với deterrence.

### Kết quả structural chính

Ước lượng structural cho thấy variance của plant-level type và firm-level draw khá gần nhau, hàm ý correlation trong compliance environment nội bộ firm là có ý nghĩa, chứ không chỉ là chuyện từng plant tách rời.

Model fit cũng tốt ở các moments chính: mean violations theo sector, variance share trong firm, và responsiveness của violations với inspection probability đều được mô phỏng khá sát dữ liệu.

### Counterfactual cốt lõi

Paper xét một cú tăng ngân sách inspection làm xác suất bị kiểm tra tăng trung bình 10 điểm phần trăm, rồi so sánh cách dùng phần ngân sách tăng thêm:

- untargeted inspections
- unlinked regulation, tức escalation chỉ theo plant score
- linked regulation, tức escalation dùng cả firm score
- 50/50 mix giữa linked và unlinked

Kết quả nổi bật nhất là ở multi-plant firms:

- **Linked regulation:** social cost của violations giảm nhiều hơn **76.2%** so với untargeted inspections.
- **Unlinked regulation:** giảm **55.3%**.
- **50/50 mix:** gần linked, khoảng **74.6%** theo pollution-index metric và còn nhỉnh hơn linked một chút khi nhìn toàn bộ firms.

### Decomposition cơ chế

Đây là phần đáng nhớ nhất của bài.

- **Correlated targeting mechanism:** đóng góp khoảng **8.7%** trong linked regulation.
- **Firm-wide moral hazard mechanism:** đóng góp khoảng **67.5%**.

Nghĩa là linked regulation không thắng chủ yếu vì regulator “biết đoán nơi xấu hơn” một chút, mà vì nó làm incentive của owner thay đổi trên toàn portfolio. Một violation không còn là chuyện cục bộ của một plant nữa; nó làm tăng xác suất scrutiny ở nhiều plant khác, nên expected future cost của negligence phình ra.

### Diễn giải kinh tế

Thông điệp kinh tế rất rõ: khi compliance costs hoặc management quality có tương quan trong firm, enforcement tối ưu nên dùng firm as an information and incentives unit, chứ không chỉ plant as an enforcement unit.

Nói theo ngôn ngữ applied micro, firm ownership network ở đây không chỉ là biến kiểm soát; nó là một phần của treatment technology. Regulator tận dụng network đó để tăng marginal deterrence trên mỗi dollar inspection budget.

### Kết quả nào bất ngờ nhất

Điểm bất ngờ không phải linked regulation tốt hơn, mà là **mức độ phần chênh lệch đến gần như hoàn toàn từ firm-wide deterrence**, chứ không phải từ better prediction. Điều này khiến bài có sức nặng vượt ra khỏi môi trường Texas: nó nói rằng enforcement design có thể khai thác tổ chức nội bộ của firm như một “multiplier” của policy.

## 7. What is special or elegant about the paper

### Một ý tưởng policy rất đời thường được biến thành kinh tế học nghiêm túc

Nhiều cơ chế hành chính ngoài đời trông giống rule-of-thumb. Bài này cho thấy một rule hành chính tưởng nhỏ là “nếu plant A của firm vi phạm thì soi kỹ plant B hơn” thực ra chứa một logic incentive rất sâu.

### Decomposition cực đẹp

Rất nhiều paper structural cho ra counterfactual nhưng người đọc khó biết “vì sao”. Bài này làm tốt hơn hẳn vì tách được:

- giá trị thông tin của linkage
- giá trị deterrence của linkage

Vì vậy, reader không chỉ học kết quả mà còn học design principle.

### Kết nối micro detail và policy design

Paper vừa grounded trong institutional detail của Texas, vừa đưa ra lesson đủ tổng quát cho OSHA, financial inspections, restaurant hygiene, hay nhiều hệ thống compliance khác. Đây là dạng applied micro đẹp: rất cụ thể nhưng không bị local.

## 8. Required background knowledge

### Dynamic moral hazard

Trong bài này, plant hay firm chọn mức độ “lười tuân thủ” hôm nay khi biết rằng hành vi hôm nay có thể làm thay đổi xác suất bị kiểm tra ngày mai. Moral hazard là trọng tâm vì regulator không quan sát action trực tiếp, chỉ quan sát violations khi có inspection.

### Escalation mechanisms

Escalation là cơ chế trong đó đối tượng từng vi phạm sẽ bị xử lý nghiêm hoặc bị giám sát nhiều hơn ở tương lai. Logic kinh tế là marginal deterrence: tái phạm phải đắt hơn lần đầu thì mới tạo động cơ mạnh.

### Correlated types / correlated costs

Nếu các plant cùng firm dùng cùng management practices hoặc cùng công nghệ, thì cost of compliance có thể tương quan. Khi đó, quan sát violation ở một plant giúp update niềm tin về plant khác cùng owner. Đây là nền tảng cho correlated targeting.

### Dynamic discrete choice và state dependence

Firm không chỉ phản ứng với current penalty mà còn với state variables như plant score và firm score. Vì thế đây là bài toán động với continuation values. Nếu chưa quen với dynamic discrete choice, người đọc nên nắm intuition về Bellman equation và sufficient statistics.

### Structural estimation for counterfactual policy

Reduced-form thường mạnh ở causal effect cục bộ. Nhưng để hỏi “nếu đổi toàn bộ rule target inspection thì sao”, paper phải đi structural. Người đọc nên quen với tư duy: model được kỷ luật bằng moments và institutional rules, rồi dùng để mô phỏng equilibrium mới.

### Welfare versus perceived welfare

Paper aggregate violations thành “social costs” theo trọng số sector mà regulator ngầm tiết lộ qua hành vi phân bổ inspections. Đây không phải social welfare đúng nghĩa tuyệt đối; nó gần hơn với regulator-implied objective. Hiểu điều này rất quan trọng để không over-interpret kết quả.

## 9. Limitations and open questions

### 1. Vai trò của commitment

Cơ chế firm-wide moral hazard mạnh vì firm tin regulator sẽ thật sự tăng scrutiny lên các plant liên quan trong tương lai. Nếu regulator không commit tốt, phần lợi ích lớn nhất của linked regulation có thể yếu đi. Paper có thảo luận điều này, nhưng không đặc tả hoàn chỉnh equilibrium khi commitment không trọn vẹn.

### 2. Perceived social costs không phải external harm đo trực tiếp

Main welfare metric dựa vào implied harms mà regulator gán cho các sector. Điều đó hợp lý cho policy evaluation “theo góc nhìn regulator”, nhưng vẫn khác với social damages đo trực tiếp. Paper có kiểm tra thêm bằng pollution index và kết quả tương tự, nhưng đây vẫn là giới hạn đáng nhớ.

### 3. Approximation trong continuation value

Continuation value sufficiency là giải pháp thông minh cho curse of dimensionality, nhưng vẫn là approximation. Một câu hỏi mở là trong setting ownership network phức tạp hơn nữa, approximation này chịu tải tốt tới đâu.

### 4. External validity

Texas có scoring rules khá minh bạch và dữ liệu rất giàu. Không phải regulator nào cũng có được hệ thống score rõ như vậy. Do đó, việc mang đúng magnitude của kết quả sang setting khác cần cẩn trọng.

### 5. Các phản ứng chiến lược khác của firm

Paper kiểm tra và không thấy bằng chứng mạnh về strategic avoidance hay production reallocation trong appendix. Tuy nhiên, ở một số ngành khác, firms có thể chuyển ô nhiễm, thay đổi legal entity, hoặc tái cấu trúc ownership để né linked regulation. Đây là hướng nghiên cứu rất đáng mở rộng.

## 10. Takeaways for a researcher

1. Nếu institution có một “score” hay rule vận hành thật sự, hãy cố đo trực tiếp nó; đừng quá nhanh biến nó thành latent variable.
2. Network hoặc ownership structure nhiều khi không chỉ là control hay source of clustering, mà là một phần của treatment technology.
3. Một paper policy mạnh thường cần tách “có hiệu quả không” khỏi “hiệu quả qua cơ chế nào”.
4. Structural model thuyết phục nhất khi nó mọc lên từ institution cụ thể chứ không phải áp xuống dữ liệu từ trên trời.
5. Khi muốn làm counterfactual, reduced-form nên được dùng để dựng chân đế: trước tiên phải chứng minh targeting, correlation, và deterrence có mặt trong dữ liệu.
6. Decomposition cơ chế là cách rất mạnh để làm structural paper dễ tin hơn và dễ dùng hơn cho policy.

## 11. Vietnam relevance and extension

### Vì sao bài này có liên quan tới Việt Nam

Việt Nam có rất nhiều lĩnh vực mà enforcement bị giới hạn bởi ngân sách và năng lực giám sát:

- môi trường công nghiệp
- an toàn lao động
- an toàn thực phẩm
- phòng cháy chữa cháy
- compliance thuế hoặc hóa đơn điện tử

Trong nhiều lĩnh vực này, cơ quan quản lý thường giám sát ở cấp cơ sở, nhà máy, cửa hàng, hoặc chi nhánh. Paper gợi ý rằng nếu các cơ sở cùng một owner có hành vi và quality tương quan, thì enforcement chỉ ở cấp đơn vị riêng lẻ có thể bỏ lỡ rất nhiều hiệu quả.

### Có thể triển khai ở Việt Nam không

Có thể, nhưng điều kiện dữ liệu là then chốt. Cần ít nhất:

- dữ liệu inspection ở cấp cơ sở theo thời gian
- lịch sử violation và sanction
- mã nhận diện để nối các cơ sở cùng owner hoặc cùng corporate group
- nếu tốt hơn nữa, dữ liệu về emissions, chất lượng môi trường, hoặc outcome hành chính liên quan

Nếu không có ownership link rõ, có thể bắt đầu với tax ID, pháp nhân mẹ-con, hoặc mạng chi nhánh trong cùng tập đoàn.

### Trở ngại chính

- ownership data ở Việt Nam có thể rời rạc hoặc không sạch
- score/risk rating của regulator có thể không được lưu chuẩn hóa hoặc không dễ truy cập
- enforcement rule trên giấy và enforcement rule trong thực tế có thể khác nhau
- commitment của regulator vào một rule minh bạch có thể yếu hơn so với setting Texas

### Hướng mở rộng phù hợp với Việt Nam

1. **Environmental inspections trong khu công nghiệp:** một vi phạm tại một nhà máy có nên kéo tăng xác suất thanh tra ở các nhà máy cùng chủ trong cùng tỉnh hoặc tỉnh khác không?
2. **Food safety hoặc pharmacy inspections:** liệu linked targeting theo chuỗi cửa hàng cùng thương hiệu/chủ sở hữu có hiệu quả hơn random inspections?
3. **Tax or invoice compliance:** doanh nghiệp nhiều chi nhánh có thể là setting tốt để xem firm-wide enforcement có tăng deterrence so với branch-level enforcement không.

### Một số research question cụ thể cho bối cảnh Việt Nam

1. Liệu thanh tra môi trường dựa trên thông tin từ các cơ sở đồng sở hữu có giúp giảm vi phạm hiệu quả hơn so với thanh tra dựa trên lịch sử của từng cơ sở riêng lẻ?
2. Khi cơ quan thuế phát hiện sai phạm ở một chi nhánh, việc tăng xác suất kiểm tra các chi nhánh cùng pháp nhân có tạo deterrence mạnh ở toàn hệ thống không?
3. Các ngành có management quality tương quan mạnh trong nội bộ firm tại Việt Nam là ngành nào, và ở các ngành đó linked enforcement có payoff lớn hơn không?

## Kết luận ngắn

Đây là một paper applied micro rất mạnh vì nó cho thấy enforcement design có thể khai thác cấu trúc firm để khuếch đại deterrence. Bài học lớn nhất là: khi hành vi tuân thủ có tương quan trong một tổ chức, regulator không nên chỉ nghĩ theo từng plant hay từng cơ sở độc lập. Chính “đơn vị tổ chức” mới có thể là nơi policy tạo ra nhiều giá trị nhất.