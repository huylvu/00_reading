# The Private Provision of Public Services: Evidence from Random Assignment in Medicaid

- Tác giả: Danil Agafiev Macambira, Michael Geruso, Anthony Lollo, Chima D. Ndumele, Jacob Wallace
- Journal: American Economic Review (forthcoming)
- Năm: forthcoming trên trang AEA tại thời điểm chạy; bản PDF công khai dùng để đọc sâu là NBER Working Paper 30390, revised January 2025
- Ngày agent chạy: 2026-05-18
- Nguồn chính: https://www.aeaweb.org/articles?id=10.1257/aer.20230541
- Nguồn PDF tốt nhất dùng để phân tích: https://www.nber.org/system/files/working_papers/w30390/w30390.pdf
- GitHub folder path: `The Private Provision of Public Services - Macambira Geruso Lollo Ndumele Wallace/`
- Trạng thái GitHub: đã lưu `analysis.md` và `analysis.html` vào repo `huylvu/00_reading`; chưa lưu `analysis.pdf`; chưa lưu PDF gốc của paper vì lượt này không tải được file nhị phân ra khỏi nguồn công khai trong tuyến shell/proxy của môi trường, nên không có raw PDF để upload chắc chắn lên GitHub
- Trạng thái Google Drive: bỏ qua trong lượt này; chưa tạo Google Doc hay tracker sheet vì không triển khai đủ chắc chắn toàn bộ tuyến Drive-native trong cùng lượt chạy

## 1. Metadata

- Tiêu đề paper: *The Private Provision of Public Services: Evidence from Random Assignment in Medicaid*
- Tác giả: Danil Agafiev Macambira, Michael Geruso, Anthony Lollo, Chima D. Ndumele, Jacob Wallace
- Journal: *American Economic Review* (forthcoming)
- Nguồn bài báo chính: https://www.aeaweb.org/articles?id=10.1257/aer.20230541
- Nguồn PDF công khai tốt nhất đã xác minh: NBER Working Paper 30390, revised January 2025
- Link PDF đã lưu hoặc nguồn PDF: chưa lưu được raw PDF lên GitHub trong lượt này; nguồn PDF dùng để đọc sâu là https://www.nber.org/system/files/working_papers/w30390/w30390.pdf

## 2. Executive summary

Paper hỏi một câu rất kinh điển nhưng khó trả lời sạch về mặt thực nghiệm: khi một chương trình bảo hiểm y tế công nên được nhà nước vận hành trực tiếp, và khi nào nên outsource cho private managed care? Bối cảnh là Medicaid ở bang Louisiana, nơi tác giả có một quasi-experiment rất mạnh: gần 100.000 người thụ hưởng bị auto-assign ngẫu nhiên vào hoặc hệ thống fee-for-service do bang quản lý, hoặc các managed care plans tư nhân.

Kết quả headline rất sắc: managed care làm giảm tổng chi tiêu y tế khoảng 5,6%, nhưng phần lớn savings đến từ dược phẩm chứ không phải medical care. Cơ chế trung tâm không phải là “mặc cả giá” nói chung, mà là utilization management ở pharmacy, đặc biệt là real-time adjudication và claims denials tại quầy thuốc, dẫn tới chuyển dịch từ brand sang generic và sang lựa chọn chi phí thấp hơn mà không làm giảm số đơn thuốc nhận được một cách tổng thể.

Tuy vậy, paper không kể một câu chuyện “tư nhân hóa là tốt toàn diện”. Savings đi kèm với dấu hiệu chất lượng và trải nghiệm kém hơn ở phần medical benefits: primary care giảm, avoidable ED visits tăng, và người được xếp vào MMC có xác suất rời plan cao hơn rất mạnh. Điểm hay nhất của paper là nó biến câu hỏi “public hay private?” từ một tranh luận nhị phân thành một bài toán thiết kế hợp đồng và phân tách chức năng: private outsourcing có vẻ đặc biệt hiệu quả cho pharmacy benefits, nhưng kém thuyết phục hơn cho medical benefits.

## 3. Research question and motivation

### Câu hỏi trung tâm

Nhà nước có nên trực tiếp cung cấp bảo hiểm y tế công, hay nên ký hợp đồng với private managed care plans để vận hành thay? Nếu outsource, private plans thực sự tiết kiệm chi phí bằng cách nào, và cái giá phải trả là gì về chất lượng và welfare của người thụ hưởng?

### Bối cảnh học thuật và thực tiễn

Trong lý thuyết hợp đồng và tổ chức công, đây là bài toán “make or buy” rất cổ điển: khi nào public sector nên tự làm, khi nào nên thuê private sector. Nhưng ở y tế công, câu hỏi này đặc biệt khó vì:

- người dân thường không chọn plan ngẫu nhiên, nên so sánh observed giữa public và private dễ bị selection bias
- các bang thay đổi managed care thường cùng lúc đổi những policy khác, làm identification yếu
- dữ liệu thường chỉ cho biết tổng spending, khó thấy mechanism thật sự

Medicaid là nơi tranh luận này có ý nghĩa chính sách trực tiếp vì quy mô cực lớn, đối tượng dễ tổn thương, và vì phần lớn bang Mỹ đã outsource ngày càng nhiều sang managed care.

### Khoảng trống paper lấp vào

Literature trước paper này thường thiếu một design đủ sạch để so sánh trực tiếp private managed care với public fee-for-service trong cùng setting và cùng thời điểm. Ngay cả khi có ước lượng về cost, người ta vẫn ít biết savings đến từ giá, lượng, network, hay utilization management. Paper này lấp cả hai khoảng trống:

- causal effect sạch hơn nhờ auto-assignment ngẫu nhiên ở mức cá nhân
- mechanism sắc hơn nhờ dữ liệu claims và claims denials rất chi tiết, đặc biệt ở pharmacy

## 4. Main contribution

### Đóng góp chính

Paper có ba đóng góp lớn.

Thứ nhất, nó cung cấp bằng chứng causal hiếm và rất mạnh về tác động của private provision trong social health insurance bằng random assignment giữa public FFS và private MMC ở mức người thụ hưởng.

Thứ hai, nó không dừng ở reduced form “managed care tiết kiệm bao nhiêu” mà đi xa hơn sang mechanism. Tác giả cho thấy phần lớn savings đến từ pharmacy utilization management, chứ không phải từ một sức mạnh mơ hồ nào đó của managed care.

Thứ ba, paper cho thấy private provision không phải là một gói đồng nhất. Pharmacy benefits và medical benefits có technology quản trị rất khác nhau. Nếu nhìn như vậy, câu hỏi policy tối ưu không phải là “có privatize toàn bộ hay không”, mà là “nên outsource phần nào”.

### Điểm mới về dữ liệu và thiết kế

- Random auto-assignment của gần 95.000 auto-assignees giữa FFS và MMC.
- Dữ liệu claims hành chính đủ chi tiết để đo spending theo loại dịch vụ, high-value care, low-value care, outpatient, inpatient, pharmacy.
- Dữ liệu denials ở pharmacy, cho phép nhìn vào real-time utilization management.
- Một identification strategy thứ hai: plan transition khi FFS bị xóa bỏ và plan còn lại bị buộc chuyển sang MMC, cho phép difference-in-differences trên cùng insurer.

### Vì sao đóng góp này quan trọng trong applied micro

Đây là một paper applied micro rất “đẹp” vì nó nối ba tầng trong cùng một bài:

1. một câu hỏi policy lớn
2. một design thực nghiệm mạnh
3. một decomposition cơ chế đủ chi tiết để policy takeaway không bị quá chung chung

## 5. Identification or methodology

### Design 1: random auto-assignment + IV

Thiết kế chính dựa trên việc Louisiana auto-assign những người không chủ động chọn plan vào một plan FFS hoặc MMC. Assignment này tạo ra variation gần như ngẫu nhiên. Nhưng vì người dân có thể switch khỏi plan được chỉ định, treatment thực nhận không hoàn toàn trùng assignment ban đầu. Vì vậy:

- `Z`: assignment ngẫu nhiên vào MMC
- `D`: enrollment thực tế trong MMC
- `Y`: spending, quality, satisfaction

Tác giả dùng assignment làm instrument cho enrollment thực tế trong MMC. Nói cách khác, ước lượng IV ở đây là local average treatment effect cho nhóm compliers, tức nhóm mà assignment thực sự kéo họ vào MMC tương đối bền.

### Điều kiện nhận dạng

Logic nhận dạng dựa trên:

- assignment là exogenous do randomization
- first stage mạnh vì auto-assignment ảnh hưởng lớn đến enrollment thực tế
- không có pre-trends khác biệt trước treatment
- exclusion restriction: assignment ảnh hưởng outcome chủ yếu qua plan type mà người đó thực nhận

Paper kiểm tra balance trước treatment và event-study pre-trends khá kỹ, đây là điểm làm design đáng tin.

### Design 2: plan transition + diff-in-diff

Ba năm sau, bang loại bỏ mô hình FFS. Plan FFS còn lại bị buộc chuyển sang MMC nhưng vẫn giữ cùng insurer. Đây là một natural experiment thứ hai, rất hay vì:

- nó giữ cố định danh tính plan/insurer
- thứ thay đổi là coverage model từ FFS sang MMC
- cho phép so sánh trước-sau với các control plans không đổi

Thiết kế này giải quyết hai nghi ngờ:

- liệu kết quả ở design 1 chỉ phản ánh “nhóm auto-assignees đặc biệt” hay không
- liệu kết quả chỉ do các MMC plans cụ thể được bang chọn hay không

Việc hai design cho kết quả rất giống nhau là một điểm tăng độ tin cậy cực mạnh.

### Các outcome chính

- tổng chi tiêu y tế
- outpatient, inpatient, pharmacy spending
- high-value care và low-value care
- avoidable emergency department visits
- satisfaction đo bằng willingness-to-stay, tức xác suất ở lại plan được chỉ định

### Điểm mạnh phương pháp

- random assignment ở cấp cá nhân là cực hiếm trong health insurance
- có second design gần như replication trong cùng paper
- đo được mechanism, không chỉ reduced form
- institutional detail đủ rõ để giải thích tại sao pharmacy khác medical care

### Điểm dễ bị nghi ngờ

- satisfaction đo bằng switching là proxy hợp lý nhưng không phải welfare measure hoàn chỉnh
- LATE của auto-assignment không nhất thiết bằng ATE cho toàn bộ Medicaid population
- quality được đo qua một số utilization proxies, không phải health outcomes đầy đủ
- context là Louisiana đầu thập niên 2010, nên external validity cần thận trọng

## 6. Results and interpretation

### Kết quả tổng quát

Managed care làm giảm tổng spending khoảng 5,6%, tương đương khoảng 82 USD mỗi enrollee mỗi năm trong sample auto-assignees. Đây là effect đủ lớn để quan trọng về policy, nhưng không “khủng” đến mức phi thực tế.

### Savings đến từ đâu?

Câu trả lời mạnh nhất của paper là: chủ yếu từ pharmacy.

- Savings ở pharmacy xuất hiện mạnh sau khi pharmacy được carve-in vào trách nhiệm tài chính của MMC.
- MMC không làm giảm tổng số prescription theo kiểu “siết hết lại”, mà chủ yếu đẩy substitution từ brand sang generic và các lựa chọn rẻ hơn.
- Điều này rất quan trọng: spending giảm phần lớn nhờ composition change chứ không phải sheer quantity suppression.

### Phần medical care thì sao?

Medical spending giảm ít hơn nhiều. Outpatient giảm nhưng inpatient gần như không có effect rõ. Tác giả còn làm decomposition giá-lượng và cho thấy:

- price effects có tồn tại và giải thích phần lớn outpatient savings
- nhưng chúng chỉ chiếm khoảng một phần ba tổng savings
- phần savings lớn nhất vẫn nằm ở quantity/composition trong pharmacy

Điểm này khiến interpretation của paper rất sắc: managed care không “giỏi toàn diện” trong mọi mảng; nó đặc biệt có năng lực ở nơi công cụ quản trị phù hợp với công nghệ cung ứng, ở đây là pharmacy adjudication.

### Chất lượng và sử dụng dịch vụ

Paper không tìm thấy một bức tranh chất lượng đơn giản một chiều.

- Một số preventive/high-value measures không xấu đi rõ rệt.
- Nhưng recommended annual primary care visits giảm khoảng 2 điểm phần trăm.
- Avoidable ED visits tăng 1,17 điểm phần trăm, khoảng 14% so với mean.

Diễn giải kinh tế tự nhiên là managed care có thể đang đẩy bớt office-based primary care mà không tạo được replacement đủ tốt, khiến một phần care dịch sang emergency department cho những tình trạng không khẩn cấp. Nói cách khác, nếu private management làm triage hoặc hạn chế medical benefits theo cách gây friction quá lớn ở outpatient primary care, hệ thống có thể tiết kiệm trên một số margin nhưng tạo méo mó ở margin khác.

### Satisfaction và revealed preference

Đây là kết quả mình thấy rất quan trọng. Người được assign vào MMC có xác suất switch khỏi plan cao hơn rất mạnh, tăng 14,5 điểm phần trăm, tức hơn gấp ba lần tương đối so với FFS. Điều này cho thấy người thụ hưởng không thích trải nghiệm đó, dù plan có tiết kiệm tiền cho ngân sách.

Paper còn đưa ra một insight rất đẹp: dù enrollees dislike managed care, back-of-the-envelope cho thấy nếu chính họ là người nhận phần savings, có thể họ vẫn chọn nó. Đây là một cách diễn đạt rất “economics”: dissatisfaction observed không nhất thiết đồng nghĩa allocation là inefficient, vì private cost và social savings đang thuộc về các tác nhân khác nhau.

### Kết quả từ design 2

Khi FFS plan bị buộc chuyển thành MMC, authors lại thấy một pattern rất giống:

- pharmacy spending giảm mạnh
- substitution brand-to-generic lặp lại
- outpatient giảm mức tương tự
- primary care giảm và avoidable ED tăng

Điều này làm cho câu chuyện của paper đáng tin hơn rất nhiều, vì nó không phụ thuộc độc nhất vào một natural experiment.

## 7. What is special or elegant about the paper

Có ít nhất bốn điểm rất đẹp.

### 1. Nó biến một tranh luận ideologically noisy thành một câu hỏi empirical cụ thể

“Public hay private?” thường là một tranh luận nặng niềm tin. Paper này ép câu hỏi đó đi vào data và institutional details: dịch vụ nào, cơ chế nào, margin nào, welfare của ai.

### 2. Hai design nói cùng một câu chuyện

Một paper có một design mạnh đã tốt. Paper này có hai design bổ sung nhau và cùng chỉ về cùng một kết luận cốt lõi. Đây là kiểu bằng chứng khiến người đọc bớt lo rằng kết quả là artifact của một setting duy nhất.

### 3. Mechanism không bị mơ hồ

Rất nhiều paper policy dừng ở “có effect”. Bài này đi tiếp đến “effect xuất hiện vì real-time adjudication và denials trong pharmacy”. Đó là một bước nhảy lớn về scientific value.

### 4. Policy takeaway không cực đoan

Kết luận của paper không phải “privatize all” hay “public tốt hơn private”. Kết luận tinh hơn: outsourcing nên có chọn lọc theo loại benefit, vì năng lực quản trị của private plan khác nhau giữa pharmacy và medical care. Đây là một insight rất kinh tế học tổ chức.

## 8. Required background knowledge

### Medicaid, FFS, managed care

- `Fee-for-service (FFS)`: nhà chi trả công thanh toán trực tiếp cho provider theo dịch vụ phát sinh.
- `Managed care (MMC)`: plan tư nhân nhận capitation hoặc risk-bearing contract, rồi tự quản network, utilization management, prior authorization, claim processing.

Hiểu khác biệt này là nền tảng vì toàn paper xoay quanh việc incentive và administrative technology khác nhau như thế nào giữa hai mô hình.

### Capitation và residual claimant logic

Trong MMC, plan thường là residual claimant trên phần savings: nếu họ giảm được chi phí điều trị dưới mức capitation đã nhận, họ giữ lại phần chênh lệch. Điều này tạo động cơ mạnh để giảm spending, nhưng chưa đủ để biết họ có thể giảm bằng công cụ gì và với hậu quả nào.

### Carve-in và carve-out

- `Carve-in`: một loại benefit, như prescription drugs, được đưa vào trách nhiệm tài chính của managed care plan.
- `Carve-out`: benefit đó vẫn do public sector chi trả trực tiếp.

Paper cho thấy carve-in/out không chỉ là chi tiết hành chính; nó quyết định ai có quyền và có công cụ để quản trị utilization.

### IV / LATE

Vì assignment ngẫu nhiên không hoàn toàn ép enrollment thực tế, authors dùng IV. Người đọc cần hiểu:

- IV khai thác variation do instrument tạo ra
- effect thường là cho nhóm compliers
- IV ở đây hợp lý vì assignment rất rõ và first stage mạnh

### Difference-in-differences

Thiết kế thứ hai so sánh plan chuyển từ FFS sang MMC với control plans không đổi, trước và sau chính sách. Người đọc cần hiểu trực giác parallel trends và tại sao việc giữ cùng insurer làm design này mạnh hơn bình thường.

### High-value care, low-value care, avoidable ED

- `High-value care`: dịch vụ có lợi ích sức khỏe kỳ vọng cao tương đối so với chi phí.
- `Low-value care`: dịch vụ ít giá trị hoặc dễ lạm dụng.
- `Avoidable ED visits`: sử dụng khoa cấp cứu cho tình trạng không khẩn cấp, thường được xem là tín hiệu của access thất bại ở primary care.

## 9. Limitations and open questions

### 1. Một bang, một giai đoạn

Louisiana Medicaid đầu những năm 2010 có thể không đại diện cho các bang khác, càng không đại diện cho các nước khác. Institutional details rất quan trọng trong paper này, nên external validity phải đi cùng institutional comparison.

### 2. Satisfaction đo bằng switching

Switching là một proxy revealed preference thông minh, nhưng vẫn không phải welfare measure hoàn chỉnh. Người ta có thể switch vì confusion, search costs thấp, provider-specific reasons, hoặc information shocks.

### 3. Chất lượng được đo gián tiếp

Paper có nhiều utilization-based quality measures, nhưng chưa quan sát đầy đủ long-run health outcomes. Một số welfare costs có thể chưa lộ trong horizon nghiên cứu.

### 4. Pharmacy results có thể phụ thuộc mạnh vào substitutability

Cơ chế tiết kiệm ở pharmacy dựa khá nhiều vào khả năng chuyển từ brand sang generic hoặc sang therapeutics rẻ hơn. Trong các thị trường thuốc ít substitutability hơn, kết quả có thể khác.

### 5. Câu hỏi mở về optimal contract design

Nếu MMC tốt hơn ở pharmacy nhưng không rõ tốt hơn ở medical benefits, thì contract tối ưu nên chia trách nhiệm thế nào? Mixed contracts? Separate carve-outs? Hybrid management? Đây là câu hỏi policy rất đáng nghiên cứu tiếp.

## 10. Takeaways for a researcher

1. Nếu câu hỏi là “public hay private”, đừng dừng ở reduced form. Hãy hỏi private margin nào, công cụ nào, và technology quản trị nào thực sự tạo ra effect.
2. Một identification strategy mạnh là tốt; hai design bổ sung nhau mà kể cùng một câu chuyện thì paper lên một đẳng cấp khác.
3. Institutional detail không phải phần phụ. Trong paper này, hiểu carve-in/out và pharmacy adjudication gần như là hiểu nửa bài.
4. Savings không đồng nghĩa với welfare gain cho người dùng. Luôn tách budget savings, utilization changes, và consumer experience.
5. Khi có thể, hãy đo mechanism bằng dữ liệu hành chính “gần hành động” hơn, như denials, thay vì chỉ nhìn tổng spending.
6. Policy takeaway tốt thường không phải kết luận nhị phân, mà là một rule tinh hơn: outsource selectively, not blindly.

## 11. Vietnam relevance and extension

### Ý tưởng paper có hợp bối cảnh Việt Nam không?

Có, và khá hợp, dù không thể copy-paste nguyên xi. Việt Nam cũng đối mặt với câu hỏi gần tương tự:

- phần nào của bảo hiểm y tế nên do cơ quan công quản trị trực tiếp
- phần nào có thể giao cho bên thứ ba hoặc cơ chế quản trị mang tính “managed care” hơn
- quản lý drug formularies, prior authorization, e-claims, gatekeeping, referral system nên thiết kế ra sao

### Điểm tương đồng có ích

- Bảo hiểm y tế là chương trình công quy mô lớn, bao phủ nhóm dễ tổn thương.
- Dược phẩm là nơi công cụ quản lý theo quy tắc, danh mục, generic substitution, và claim adjudication có thể phát huy mạnh.
- Primary care và tuyến chuyển viện là nơi friction hành chính dễ tạo méo mó lớn nếu thiết kế không khéo.

### Điều kiện cần nếu triển khai nghiên cứu tương tự ở Việt Nam

- Dữ liệu claims BHYT đủ sạch ở cấp bệnh nhân-dịch vụ-thời gian.
- Thông tin chi tiết về thuốc brand/generic, giá thanh toán, từ chối thanh toán, điều kiện phê duyệt.
- Một policy change hoặc pilot đủ rõ để tạo variation exogenous.
- Nếu không có randomization, cần ít nhất một staggered rollout hoặc discontinuity đáng tin.

### Trở ngại chính

- Quyền lựa chọn plan ở Việt Nam khác Mỹ; khó tìm đúng contrast public-vs-private như Medicaid MMC.
- Dữ liệu denials và utilization management có thể chưa được chuẩn hóa hoặc dễ truy cập cho nghiên cứu.
- Provider behavior, referral rules, và quasi-market structure khác khá xa Louisiana Medicaid.

### Mình nghĩ paper này gợi mở gì cho Việt Nam?

Insight quan trọng nhất là không nên nghĩ quản trị bảo hiểm y tế như một khối đồng nhất. Ở Việt Nam, có thể câu hỏi đúng không phải là “có nên để bên ngoài tham gia quản lý bảo hiểm công hay không”, mà là:

- quản lý thuốc có nên số hóa và rule-based mạnh hơn không
- với outpatient và primary care, friction nào là đáng chấp nhận và friction nào gây hại
- phần nào của authorization nên làm real-time, phần nào không nên

### 1 đến 3 hướng nghiên cứu mới cho Việt Nam

1. `Drug management and generic substitution in BHYT`
   Nghiên cứu xem các thay đổi trong quy định generic substitution, e-prescription, hoặc electronic prior approval có làm giảm chi phí thuốc mà không giảm adherence hay không.

2. `Real-time claims adjudication và hành vi provider`
   Nếu một số nhóm dịch vụ hoặc thuốc được đưa vào cơ chế phê duyệt điện tử nhanh theo từng giai đoạn, có thể dùng staggered rollout để ước lượng tác động lên spending, prescribing patterns, và bệnh nhân quay lại tuyến cấp cứu.

3. `Primary care friction và avoidable hospital use`
   Nghiên cứu xem các thay đổi trong gatekeeping, referral rules, hoặc thanh toán ngoại trú có làm giảm chi phí nhưng đẩy bệnh nhân sang tuyến bệnh viện hay cấp cứu không.

## 12. Why this paper was chosen tonight

Mình chọn paper này cho lượt hôm nay vì ba lý do.

- Đây là một paper top-5 rất đúng chất applied micro: câu hỏi lớn, design mạnh, mechanism rõ.
- Paper còn rất “sống” về mặt policy: trang AEA đang để ở trạng thái forthcoming, nên nó vừa mới đối với vòng tranh luận hiện tại.
- So với nhiều paper chỉ cho biết outsourcing “có vẻ” tiết kiệm hay không, bài này chỉ ra rõ tiết kiệm xảy ra ở đâu và tại sao, nên đặc biệt hữu ích cho người học applied micro và public economics.

## 13. Honest storage note

Trong lượt chạy này, mình xác minh chắc được bài báo chính thức trên AEA và đọc sâu bằng bản NBER working paper công khai. Tuy nhiên, tuyến mạng shell/proxy của môi trường không tải được raw PDF nhị phân từ nguồn công khai, nên mình không coi PDF gốc là “đã lưu lên GitHub”. Vì vậy:

- đã lưu: `analysis.md`, `analysis.html`
- chưa lưu: `analysis.pdf`
- chưa lưu: raw PDF của paper
- Google Drive: bỏ qua

Điểm quan trọng là trạng thái này sẽ được giữ đúng y như vậy trong email summary, không nói quá khả năng thực tế của lượt chạy.