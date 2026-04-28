# What Do Policies Value?

- **Tác giả:** Daniel Björkegren, Joshua E. Blumenstock, Samsun Knight
- **Journal:** *The Review of Economic Studies*
- **Năm:** 2025
- **Ngày agent chạy:** 2026-04-29 (Asia/Saigon)
- **Nguồn bài báo chính:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdaf089/8276643
- **Nguồn PDF dùng để phân tích:** https://www.jblumenstock.com/files/papers/policies.pdf
- **Trạng thái lưu trên GitHub:** trong lượt này chỉ coi `analysis.md` và `analysis.html` là đã lưu khi bước tạo hoặc cập nhật file trên repo thành công; chưa coi PDF gốc là đã lưu vì môi trường hiện tại chưa tải được binary PDF về máy để upload lại lên repo
- **Trạng thái lưu trên Google Drive:** bỏ qua trong lượt này vì chưa có tuyến tạo Google Doc và tracker đúng folder đích một cách nhất quán trong phạm vi chạy hiện tại

## 1. Metadata

- **Tiêu đề paper:** *What Do Policies Value?*
- **Tác giả:** Daniel Björkegren, Joshua E. Blumenstock, Samsun Knight
- **Journal:** *The Review of Economic Studies*
- **Năm / tình trạng xuất bản:** bài ReStud rất mới, published ngày 7 October 2025 trên Oxford Academic; bản PDF công khai mà mình dùng là bản tác giả dated September 2, 2025 nhưng hiển thị rõ đây là bản Open Access đã tải từ trang ReStud
- **Link bài báo / trang nguồn chính:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdaf089/8276643
- **Link PDF đã dùng:** https://www.jblumenstock.com/files/papers/policies.pdf

## 2. Executive Summary

Paper hỏi một câu rất hay: khi một chính sách ưu tiên người này hơn người kia, đó là vì nhà làm chính sách thực sự coi người đó “đáng được ưu tiên hơn”, hay chỉ vì người đó được dự đoán sẽ hưởng lợi nhiều hơn từ can thiệp? Đây là một khác biệt cực quan trọng, nhưng trong thực tế thường bị trộn lẫn.

Bài báo xây dựng một khung “inverse policy design”: trước hết ước lượng heterogeneous treatment effects, tức ai hưởng lợi nhiều hơn trên từng outcome; sau đó dùng ranking hoặc allocation rule quan sát được của chính sách để suy ra các welfare weights ngầm ẩn và các outcome weights mà chính sách đang thực sự tối ưu. Nói ngắn gọn, bài đảo ngược bài toán target assignment: thay vì hỏi “nên cấp cho ai”, họ hỏi “policy hiện tại đang ngầm coi trọng điều gì và coi trọng ai”.

Trong ứng dụng thực nghiệm với PROGRESA ở Mexico, kết quả nổi bật nhất là: nhìn bề ngoài, chương trình có vẻ ưu tiên hộ indigenous; nhưng sau khi tính đến việc nhóm này hưởng lợi mạnh hơn hẳn từ chương trình, ta không còn kết luận rằng policy đặt welfare weight cao hơn cho họ nữa. Thậm chí, ước lượng còn phù hợp với việc welfare weight implicit dành cho họ thấp hơn một chút. Đồng thời, bài cho thấy policy không thuần utilitarian theo nghĩa chỉ tôn trọng household choice; nó mang tính paternalistic, vì outcome weights ngầm ẩn cho thấy policy coi health và schooling khác với cách hộ gia đình tự trade-off.

Đây là một paper rất đáng đọc vì nó kết nối applied micro, development, policy evaluation, machine learning treatment heterogeneity, và normative economics trong cùng một khung thống nhất. Nó không chỉ đánh giá tác động chương trình, mà còn audit “giá trị” thật sự nằm sau chương trình.

## 3. Research Question and Motivation

### Câu hỏi trung tâm

Câu hỏi nghiên cứu cốt lõi là: từ một allocation rule quan sát được của chính sách, liệu ta có thể suy ra một cách có hệ thống policy đó đang ngầm đặt welfare weight lên những nhóm dân cư nào, và đang coi trọng outcome nào hơn outcome nào không?

### Động lực học thuật

Trong applied micro và development economics, ta thường đánh giá chương trình theo hai hướng tách rời:

- ai được nhận chương trình
- tác động của chương trình lên consumption, health, education, hay các outcome khác

Nhưng giữa hai khâu này còn một khoảng trống: cùng một observed targeting pattern có thể tương thích với nhiều hệ giá trị khác nhau. Ví dụ, nếu người nghèo được ưu tiên, đó có thể là vì nhà nước coi người nghèo có welfare weight cao hơn; nhưng cũng có thể đơn giản vì người nghèo có treatment effects lớn hơn. Không tách hai cơ chế này ra, ta rất dễ đọc sai “đạo đức ẩn” của chính sách.

### Động lực thực tiễn

Điều này đặc biệt quan trọng với các chương trình anti-poverty, admission, grants, hay health allocation, nơi policy phải phân bổ nguồn lực khan hiếm. Policy debate thường xoay quanh means: ai nhận, score nào, cutoff nào. Paper muốn chuyển debate sang ends: policy thực ra đang coi trọng outcome nào và nhóm nào.

## 4. Main Contribution

### Đóng góp chính

Đóng góp lớn nhất của paper là cung cấp một framework thực chứng để suy ra revealed social preferences từ allocation decisions, trong bối cảnh treatment effects dị biệt giữa các đối tượng và outcome là đa chiều.

### Cái mới so với văn liệu trước

- So với literature về optimal targeting, bài này giải “bài toán ngược”: không giả định sẵn welfare function để tìm policy tối ưu, mà từ policy quan sát được suy ngược ra welfare function nhất quán với policy đó.
- So với literature về heterogeneous treatment effects, bài không dừng ở chỗ dự báo ai hưởng lợi nhiều, mà dùng các dự báo đó để tách “who benefits” khỏi “who is valued”.
- So với literature về multidimensional welfare indices, bài đưa ra outcome weights có diễn giải kinh tế rõ hơn PCA hay ad hoc weights, vì các weights này được reveal bởi trade-offs implicit trong policy.
- So với inverse-optimum public finance, bài tổng quát hóa từ thuế thu nhập một chiều sang arbitrary allocation rules có nhiều covariates và nhiều outcomes.

### Vì sao quan trọng trong micro applied / development

Đây là đóng góp rất mạnh vì development policy thường vừa paternalistic vừa multi-objective. Chương trình như PROGRESA không chỉ muốn tăng consumption; nó còn muốn cải thiện schooling và child health. Paper cho ta ngôn ngữ thực chứng để mô tả chính xác các trade-off đó, thay vì chỉ kể lại mục tiêu chính thức của policy documents.

## 5. Identification or Methodology

### Khung khái niệm

Policy quan sát một ranking hoặc score `z_i` trên các household. Tác giả giả sử policy ngầm tối đa hóa social welfare:

- mỗi household có utility theo góc nhìn policy
- utility này được nhân với welfare weight `w(x_i)` phụ thuộc vào đặc điểm household
- utility lại được tách thành nhiều thành phần outcome, mỗi thành phần có outcome weight riêng
- thêm một thành phần “base value” của treatment không phụ thuộc trực tiếp vào impacts

Intuition rất đẹp: cùng một observed ranking có thể đến từ welfare weights khác nhau tùy theo treatment effects. Nếu người nghèo được ưu tiên:

- có thể vì policy coi người nghèo “xứng đáng hơn”
- có thể vì người nghèo hưởng lợi nhiều hơn
- thậm chí có thể vì người nghèo hưởng lợi nhiều đến mức dù policy không thích ưu tiên họ hơn, ranking vẫn ra như vậy

### Thủ tục 2 bước

Paper ước lượng theo hai bước:

1. **Bước 1: ước lượng heterogeneous treatment effects**
   - Với mỗi outcome `j`, tác giả dự báo tác động điều trị `v_ij` như một hàm của covariates giàu hơn `x̃_i`.
   - Trong application chính, họ dùng OLS; đồng thời cũng cho thấy machine learning methods như causal forest có thể dùng được.

2. **Bước 2: suy ra preferences từ ranking**
   - Cho trước predicted treatment effects, tác giả dùng full ranking của policy để ước lượng welfare weights và impact weights sao cho ranking quan sát được là hợp lý nhất.
   - Họ mô hình hóa ranking error theo extreme value type I và dùng exploded logit likelihood cho dữ liệu ranked choice.

### Setting thực nghiệm: PROGRESA

Application dùng PROGRESA, một chương trình chống nghèo nổi tiếng ở Mexico. Trong phase đầu:

- 506 villages vào evaluation
- 320 villages được randomize vào treatment, bắt đầu chương trình từ mùa hè 1998
- 186 villages vào control và chỉ nhận chương trình từ năm 2000

Trong các poor communities, hộ được xếp hạng bằng household poverty score proxy means test. Dữ liệu chính là household surveys tháng 10/1998 và tháng 11/1999. Mẫu phân tích chính có:

- 14,801 households trong dữ liệu evaluation
- 7,767 households trong endline sample dùng cho ranking analysis
- 6,784 observations dùng cho bước treatment-effect estimation

### Outcomes chính

Paper tập trung vào ba outcomes mà policy documents nhấn mạnh và prior literature coi là robust:

- log consumption per capita
- số ngày trẻ nghỉ học
- số ngày trẻ nhỏ bị ốm

Điểm hay là ba outcomes này cho phép bài đo được trade-off giữa poverty relief, schooling, và child health.

### Giả định nhận dạng cốt lõi

Giả định trung tâm là **exclusion restriction**: tập covariates dùng để mô tả heterogeneity trong treatment effects `x̃_i` phải giàu hơn tập covariates được phép đi trực tiếp vào welfare weights `x_i`. Nói nôm na, phải có vài biến giúp dự báo ai hưởng lợi nhiều, nhưng không phải là biến mà policymaker trực tiếp “coi trọng” trong welfare weights.

Trong application PROGRESA, household demographics khá thô đi vào welfare weights, còn các biến chi tiết hơn về age-gender composition của household được giữ lại ở first stage để nhận dạng treatment heterogeneity nhưng bị loại khỏi welfare weights. Chính lựa chọn này giúp tách “benefit” khỏi “value”.

### Điểm mạnh của phương pháp

- Kết hợp rất tự nhiên giữa treatment heterogeneity và policy design.
- Dùng ranking đầy đủ của policy, không chỉ binary eligibility, nên khai thác nhiều thông tin hơn.
- Có thể áp dụng cho nhiều setting khác ngoài anti-poverty programs: scholarships, health interventions, grants, admission, social programs.
- Cho phép đi từ positive analysis sang normative audit mà không cần giả vờ policy objectives đã được công bố minh bạch.

### Điểm dễ bị nghi ngờ

- Exclusion restriction là chỗ nhạy nhất. Nếu các biến bị loại khỏi welfare weights thực ra lại proxy cho “neediness” hay unobserved deservingness, khi đó impact weights có thể hấp thụ nhầm phần preference.
- First stage treatment effects phải đủ tốt. Nếu dự báo impacts sai hoặc quá nhiễu, bước hai sẽ suy ra preferences trên một nền dự báo méo.
- Functional form matters: ví dụ dùng log consumption hay linear consumption sẽ ảnh hưởng diễn giải.
- Khi outcome là household choices, impact weights không còn là welfare weights thuần mà đo chênh lệch giữa policy valuation và household valuation, nên cần diễn giải cẩn thận.

## 6. Results and Interpretation

### Bước 1: nếu chỉ nhìn ranking thô của PROGRESA

Table 1 cột “Decision Rule” cho thấy poverty score 1999 ưu tiên:

- hộ indigenous
- hộ nghèo hơn
- hộ đông người hơn
- household head trẻ hơn
- household head ít học hơn

Nếu dừng ở đây, ta sẽ kể câu chuyện quen thuộc: PROGRESA ưu tiên indigenous, nghèo, và ít học.

### Bước 2: sau khi tính treatment heterogeneity

Đây là chỗ paper thực sự tạo khác biệt. Khi đưa predicted treatment effects vào mô hình, implied welfare weights thay đổi đáng kể:

- welfare weight của hộ indigenous trở thành âm về log scale, khoảng `-0.174`
- log income vẫn âm, tức policy vẫn ưu tiên hộ nghèo hơn
- household size dương
- household head age âm
- educated âm mạnh

Diễn giải kinh tế ở đây rất quan trọng: việc hộ indigenous được xếp cao trong ranking **không có nghĩa** policy coi họ “đáng giá hơn” về mặt welfare weight. Vì họ hưởng lợi nhiều hơn từ chương trình, observed prioritization có thể được giải thích bởi impacts chứ không phải bởi preference thuần. Chính vì thế, sau khi điều chỉnh heterogeneity, welfare weight implicit trên indigenous households thậm chí có thể thấp hơn khoảng 17.4%.

### Outcome weights và paternalism

Impact weights ước lượng cho thấy consumption được policy đặt trọng số lớn nhất trong specification cơ sở, schooling có trọng số âm theo đơn vị “missed school day” nên hàm ý policy muốn giảm nghỉ học, còn sickness weight nhỏ và kém chính xác hơn trong baseline. Quan trọng hơn, các kiểm định cho thấy dữ liệu bác bỏ mạnh giả thuyết “not paternalistic”. Nghĩa là policy không đơn thuần chấp nhận household choices như một utilitarian planner thuần túy; nó đặt giá trị riêng lên child outcomes.

Về mặt ý tưởng, đây là một kết quả rất giàu nội dung: cash transfer policy không chỉ là income support, mà còn là một công cụ social engineering mềm, với các mục tiêu child-oriented vượt ra ngoài revealed household demand.

### So sánh với stated preferences của cư dân Mexico

Tác giả còn làm survey năm 2023 với 429 Mexican residents để so sánh estimated implied preferences với stated preferences. Kết quả khá thú vị:

- overall pattern khá giống nhau
- survey còn ủng hộ welfare weight dương cho indigenous households
- người trả lời survey đánh giá health impacts của trẻ em cao hơn cả households lẫn implemented policy

Điểm này làm bài mạnh hơn hẳn: nó không chỉ suy ra preferences từ hành vi policy, mà còn benchmark chúng với preferences do người dân phát biểu trực tiếp.

### Counterfactual policy design

Ở Table 3, paper dùng framework để trả lời câu hỏi ngược lại: nếu đổi preferences, policy sẽ trông ra sao?

- nếu dùng resident preferences, allocation sẽ hơi tăng consumption và giảm nhẹ missed school days lẫn sick days so với policy thật
- nếu welfare weights bằng nhau cho mọi household, indigenous households lại được ưu tiên hơn
- nếu chỉ tối đa hóa education impacts, policy sẽ ưu tiên các hộ nhỏ hơn và giàu hơn
- nếu chỉ tối đa hóa consumption impacts, policy sẽ ưu tiên indigenous và hộ thu nhập thấp hơn

Đây là phần rất đẹp vì nó biến framework từ một công cụ audit thành công cụ design. Người đọc không chỉ thấy “policy đang value gì”, mà còn thấy “nếu value khác đi thì policy sẽ đổi như thế nào”.

## 7. What Is Special or Elegant About the Paper

Điểm đẹp nhất của paper là nó tách rời ba thứ mà applied work thường gom lại:

- ai được ưu tiên
- ai hưởng lợi nhiều hơn
- ai thực sự được policy coi trọng hơn

Nhiều paper đánh giá targeting chỉ dừng ở observed allocation. Paper này cho thấy observed allocation chỉ là reduced form. Muốn hiểu policy thật sự “có giá trị gì”, phải nhìn cùng lúc allocation rule và treatment effect heterogeneity.

Điểm hay thứ hai là paper làm một cây cầu rất hiếm giữa positive economics và normative economics. Nó không nhảy thẳng sang nói policy “nên” làm gì. Thay vào đó, nó hỏi policy “đang ngầm làm gì về mặt giá trị”, rồi mới mở cửa cho tranh luận normative.

Điểm hay thứ ba là cách authors dùng PROGRESA. Họ không chọn một chương trình obscure; họ chọn một canonical development program mà mọi người tưởng đã hiểu rất rõ. Rồi họ cho thấy ngay cả ở setting kinh điển ấy, ta vẫn có thể đọc sai targeting logic nếu bỏ qua heterogeneity.

## 8. Required Background Knowledge

### Heterogeneous Treatment Effects

Người đọc nên quen với ý tưởng treatment effect không giống nhau giữa các đơn vị. Trong paper này, đó là nền tảng của toàn bộ lập luận: cùng một policy targeting pattern có thể phản ánh differences in impacts chứ không phải differences in moral priority.

### Proxy Means Testing và Targeting trong development

PROGRESA dùng household poverty score, tức một proxy means test. Đây là công cụ rất phổ biến trong social assistance ở các nước đang phát triển, nơi income thật khó đo chính xác. Cần hiểu rằng score loại này luôn là một reduced-form targeting rule chứ không phải welfare function công khai hoàn chỉnh.

### Welfare Weights

Welfare weight là trọng số xã hội đặt lên lợi ích của từng loại đối tượng. Trong optimal tax/public finance, welfare weight thường gắn với income groups. Paper này mở rộng khái niệm đó sang vector attributes rộng hơn: indigenous status, household size, education, age, v.v.

### Paternalism vs. Respecting Household Choice

Nếu policy hoàn toàn tôn trọng household preferences, thì việc household đổi tiền mặt lấy health hay schooling như thế nào sẽ được coi là đủ. Nhưng nếu policymaker nghĩ parents underinvest vào child outcomes, họ có thể đặt weight riêng lên schooling hoặc health. Paper gọi đó là paternalistic component.

### Ranked Choice / Exploded Logit

Phần estimation bước hai dùng exploded logit cho full ranking. Người đọc không cần thuộc hết kỹ thuật, nhưng nên hiểu đây là cách khai thác thông tin từ một ordering đầy đủ chứ không chỉ từ lựa chọn nhị phân.

### Exclusion Restriction

Đây là mấu chốt econometric. Muốn tách impacts khỏi preferences, cần một số biến giúp dự báo treatment heterogeneity nhưng không đi trực tiếp vào policy preferences. Nếu điều này không đáng tin, identification suy yếu đáng kể.

## 9. Limitations and Open Questions

### Hạn chế 1: exclusion restriction khó hoàn toàn thuyết phục

Đây là hạn chế quan trọng nhất. Nếu policymaker thật ra quan tâm tới các yếu tố tinh vi như “neediness”, vulnerability, hay social exclusion nhưng các biến đó chỉ xuất hiện ở first stage chứ không nằm trong welfare weights, mô hình có thể diễn giải nhầm preference thành impact weight.

### Hạn chế 2: first-stage dependence

Toàn bộ inferential edifice dựng trên predicted heterogeneous treatment effects. Nếu first stage misspecified, nhất là với outcomes noisy như child sickness, thì second-stage preferences cũng dao động theo.

### Hạn chế 3: outcome menu còn hẹp

Paper tập trung vào consumption, schooling, sickness. Đây là lựa chọn hợp lý vì prior literature cho thấy các outcomes này robust, nhưng rõ ràng welfare space của PROGRESA rộng hơn: nutrition quality, empowerment, long-run human capital, intra-household bargaining, stress, expectations, v.v.

### Hạn chế 4: policy process thực tế có thể không tối ưu hóa nhất quán

Framework giả định observed ranking có thể rationalize bằng một latent objective function cộng error. Nhưng real-world policy có thể là sản phẩm của bureaucratic compromise, lobbying, administrative convenience, hay data limitations. Khi đó “revealed values” nên được hiểu là values consistent with the implemented rule, không nhất thiết là true moral beliefs của mọi actor trong nhà nước.

### Câu hỏi mở

- Nếu áp dụng framework này cho algorithmic targeting hiện đại, kết quả sẽ khác thế nào?
- Nếu outcomes là long-run outcomes thay vì short-run survey outcomes, welfare weights có đổi mạnh không?
- Có thể mở rộng khung này sang dynamic allocation, nơi policy vừa target hôm nay vừa ảnh hưởng treatment effects ngày mai không?
- Khi có nhiều policymakers với objective khác nhau, revealed weights có còn có ý nghĩa rõ ràng không?

## 10. Takeaways for a Researcher

1. **Đừng đọc targeting rule như welfare weights.** Ranking quan sát được chỉ là reduced form; nếu treatment effects dị biệt, diễn giải thẳng observed prioritization thành social preference là rất nguy hiểm.
2. **Heterogeneity có thể đổi hoàn toàn câu chuyện substantive.** Kết quả về indigenous households trong paper là ví dụ đẹp: apparent favoritism có thể biến thành lower implied welfare weight khi đã account cho higher impacts.
3. **Policy evaluation có thể đi xa hơn ATE/HTE.** Tác động không chỉ để báo “program works”, mà còn để audit logic phân bổ của policy.
4. **Normative content có thể được gắn lại với empirical design.** Paper cho thấy normative economics không nhất thiết phải tách khỏi applied micro; ta có thể dùng dữ liệu để truy ra trade-offs mà policy đang thực hiện.
5. **Counterfactual policy design nên làm trong outcome space.** Thay vì chỉ thay score formula theo kiểu ad hoc, ta nên hỏi: nếu muốn coi trọng education hơn health, policy frontier thay đổi ra sao?
6. **Survey stated preferences có thể là benchmark hữu ích, không chỉ là phụ lục.** Việc so sánh revealed policy values với stated citizen values làm paper thuyết phục hơn nhiều.

## 11. Vietnam Relevance and Extension

### Liên hệ với Việt Nam

Bài này rất hợp với bối cảnh Việt Nam, nơi rất nhiều chương trình công và bán công phải target người thụ hưởng bằng score, eligibility list, hay local review:

- trợ giúp xã hội và hộ nghèo/cận nghèo
- học bổng và miễn giảm học phí
- phân bổ bảo trợ trẻ em, y tế dự phòng, hay các chương trình nutrition
- ưu tiên tín dụng chính sách
- support cho hộ dễ tổn thương sau thiên tai, dịch bệnh, hay biến động giá

Ở Việt Nam, tranh luận thường xoay quanh việc danh sách có “đúng đối tượng” không. Paper gợi ý một câu hỏi sâu hơn: danh sách đó đang reveal loại giá trị nào? Policy đang ưu tiên nghèo nhất, vulnerable nhất, hay những người có marginal returns cao nhất?

### Điều kiện cần để triển khai ở Việt Nam

- Có một allocation rule đủ quan sát được: score, ranking, cutoff, hoặc binary eligibility.
- Có dữ liệu baseline đủ tốt về households hoặc individuals.
- Có variation hoặc pilot/RCT/quasi-experiment đủ để ước lượng treatment heterogeneity.
- Có outcome measures đủ gần với policy goals: consumption, attendance, nutrition, health use, labor supply, learning outcomes.
- Có một tập covariates giàu hơn cho first stage, và một lập luận đủ chặt cho exclusion restriction.

### Trở ngại chính

- Ranking đầy đủ thường khó tiếp cận; nhiều chương trình chỉ lưu final eligibility chứ không lưu score chi tiết.
- Dữ liệu hành chính có thể không sạch hoặc không link được qua thời gian.
- Policy implementation ở Việt Nam thường có yếu tố xét duyệt cộng đồng hoặc discretionary adjustment; phần này làm observed rule bớt “cơ giới” hơn PROGRESA.
- Exclusion restriction sẽ đặc biệt khó nếu local officials dùng những tín hiệu phi chính thức về neediness mà data không đo được.

### Cách làm mới cho Việt Nam

Một hướng hay là không cố sao chép nguyên xi PROGRESA, mà dùng khung của paper cho các setting hiện đại hơn:

- trợ cấp học sinh khó khăn, nơi outcome có thể là attendance và learning
- credit targeting qua ngân hàng chính sách, nơi outcome là income smoothing, business survival, repayment
- y tế dự phòng hoặc nutrition targeting, nơi outcome là child growth, morbidity, school absence

### 3 research questions có thể phát triển ở Việt Nam

1. **Chính sách hỗ trợ học sinh nghèo ở Việt Nam đang ưu tiên “người nghèo nhất” hay “người có learning returns cao nhất”?**
2. **Trong tín dụng chính sách, allocation rule hiện hành reveal welfare weight nào giữa hộ rất nghèo, hộ dân tộc thiểu số, và hộ có khả năng sinh lời cao hơn từ vốn vay?**
3. **Với các chương trình dinh dưỡng hoặc bảo trợ trẻ em, policy đang mang tính paternalistic đến mức nào so với revealed household choices?**

## 12. Vì sao mình chọn paper này hôm nay

Mình chọn bài này vì nó là một bài rất mới trên ReStud, đúng vùng giao giữa applied micro và development economics, đồng thời có một methodological twist đủ khác để đáng học hơn nhiều bài “tác động + heterogeneity” thông thường. Nó cũng có public PDF tốt từ tác giả và full article page rõ ràng trên Oxford Academic, nên có thể làm một briefing chắc tay chứ không phải suy đoán từ abstract.

## 13. Tình trạng lưu trữ và giới hạn của lượt chạy này

- **Có thể lưu chắc:** `analysis.md`, và nếu render ổn thì thêm `analysis.html`
- **Chưa coi là đã lưu:** `analysis.pdf`
- **Chưa coi là đã lưu:** PDF gốc của paper

Lý do là dù nguồn PDF công khai đã được xác minh chắc và nội dung PDF đọc được tốt qua web, môi trường shell hiện tại bị chặn khi tải binary PDF trực tiếp từ nguồn ngoài. Vì vậy, trong lượt này mình chỉ nên báo trung thực rằng đã xác minh được nguồn PDF tốt nhất và dùng nó để phân tích, chứ chưa thể nói là raw PDF đã được tải về và upload lên GitHub.