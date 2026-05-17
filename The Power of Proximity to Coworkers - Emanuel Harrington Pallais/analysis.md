# The Power of Proximity to Coworkers

- Tác giả: Natalia Emanuel, Emma Harrington, Amanda Pallais
- Journal: The Quarterly Journal of Economics
- Năm: 2026
- Trạng thái bài báo: accepted manuscript / research article published online ngày 12-05-2026
- Ngày agent chạy: 2026-05-17
- Nguồn bài báo chính: https://doi.org/10.1093/qje/qjag027
- Nguồn PDF tốt nhất đã xác minh: accepted-manuscript PDF chính thức của QJE tại https://academic.oup.com/qje/advance-article-pdf/doi/10.1093/qje/qjag027/68269215/qjag027.pdf
- Nguồn PDF công khai dùng để đọc sâu trong lượt chạy này: NBER Working Paper 31880 tại https://www.nber.org/system/files/working_papers/w31880/w31880.pdf
- Ghi chú phiên bản: public NBER PDF có tiêu đề dài hơn, `The Power of Proximity to Coworkers: Training for Tomorrow or Productivity Today?`, nhưng nội dung cốt lõi về câu hỏi, design, và kết quả khớp với accepted-manuscript abstract trên QJE.
- Trạng thái lưu trên GitHub: `analysis.md` dự kiến lưu trong lượt này; `analysis.html` sẽ lưu nếu bước tạo file văn bản thành công; `analysis.pdf` không được coi là đã lưu nếu chưa có upload nhị phân thật sự.
- Trạng thái lưu trên Google Drive: bỏ qua trong lượt này do chưa có tuyến tạo Google-native outputs đúng folder đích với độ chắc chắn đủ cao.

## Executive summary

Paper hỏi một câu đang rất thời sự nhưng bài làm lại cực kỳ kinh tế học: proximity với coworkers thực sự tạo ra giá trị gì, và trade-off giữa làm việc gần nhau với làm việc phân tán nằm ở đâu? Thay vì tranh luận chung chung về remote work, bài tách riêng một cơ chế rất cụ thể: proximity làm tăng mentorship và learning, nhưng mentorship này có chi phí ngắn hạn lên output hiện tại.

Bối cảnh là software engineers tại một Fortune 500 firm. Trước COVID-19, một số teams ngồi trọn trong một building, số khác bị tách qua hai buildings cách nhau vài blocks. Khi offices mở, teams đa-building đã vận hành giống “remote-lite”; khi offices đóng vì COVID, mọi teams đều trở nên fully distributed. Tác giả dùng chính cú sốc này làm difference-in-differences để đo causal effect của proximity.

Kết quả chính rất đẹp. Khi offices còn mở, engineers ngồi cùng building với toàn bộ teammates nhận nhiều online feedback hơn 22%. Nhưng proximity lại làm programming output giảm: DiD estimate cho thấy output giảm khoảng 24%, và hiệu ứng này đặc biệt lớn với senior engineers, những người làm phần lớn mentoring. Nói cách khác, ngồi gần nhau không phải là “free lunch”; nó đổi output hôm nay lấy training cho ngày mai.

Điều làm paper đáng đọc hơn nữa là kết quả dài hạn. Junior engineers được “đào tạo” trên one-building teams về sau có khả năng nhận pay raises cao hơn khi offices đóng, và họ cũng có xác suất cao hơn rời firm để sang các jobs lương cao hơn. Paper vì vậy đưa ra một thông điệp rất sắc: remote work có thể tốt cho short-run production, nhưng có nguy cơ làm scar human-capital accumulation của workers cần học hỏi nhiều nhất.

## Research question and motivation

### Câu hỏi nghiên cứu trung tâm

Proximity với coworkers tạo ra value gì trong công việc trí óc, và value đó đến qua kênh collaboration hiện tại hay kênh human-capital accumulation tương lai?

### Bối cảnh học thuật và thực tiễn

Sau COVID, remote work chuyển từ fringe arrangement thành một thay đổi cấu trúc của labor market. Nhưng phần lớn tranh luận công khai lại xoay quanh một câu hỏi khá hẹp: remote work làm productivity tăng hay giảm? Paper này chỉ ra câu hỏi đó chưa đủ tốt. Nếu proximity làm tăng training, thì một measured productivity gain ngắn hạn khi mọi người ở xa nhau có thể phải trả bằng mất mát learning trong dài hạn.

Điểm paper bổ sung cho văn liệu là nó nối ba mảng thường tách rời nhau:

1. remote work và communication
2. coworker learning / mentorship
3. career dynamics và human capital

### Khoảng trống paper muốn lấp

Trước paper này, ta có nhiều bằng chứng về peer effects và về remote communication, nhưng thiếu bằng chứng causal khá sạch về việc ngồi gần coworkers có thật sự tăng mentorship hay không, mentorship đó có cost ngắn hạn nào không, và cuối cùng nó có để lại dấu ấn dài hạn lên careers không.

## Main contribution

### 1. Biến proximity thành một treatment có thể nhận dạng

Paper dùng setup hai-building rất thông minh. Một số teams ngồi trọn trong một building; số khác có ít nhất một teammate ở building khác. Nhờ COVID closure, tác giả có before-after variation rất mạnh để tách effect của physical proximity khỏi các khác biệt cố hữu giữa teams.

### 2. Đo trực tiếp mentorship bằng code-review comments

Trong software engineering, code reviews được ghi lại online. Tác giả dùng số lượng comments, follow-up questions, độ dài review, và mentions của các online conversations như proxy cho mentorship. Đây là điểm dữ liệu cực mạnh vì nó biến một khái niệm thường rất mơ hồ thành thứ có thể đếm.

### 3. Chỉ ra trade-off thật sự giữa output ngắn hạn và training dài hạn

Paper không kể câu chuyện một chiều kiểu “office good” hay “remote good”. Nó cho thấy proximity tăng feedback nhưng giảm output hiện tại, nhất là với senior engineers. Đây là trade-off rất thật chứ không phải difference in taste đơn thuần.

### 4. Nêu bật heterogeneity theo gender và seniority

Hiệu ứng proximity lớn hơn rõ rệt với women và junior workers ở phía nhận mentorship, còn senior engineers ở phía cho mentorship chịu cost output lớn hơn. Điều này làm paper vừa policy-relevant vừa giàu nội dung tổ chức.

## Identification or methodology

### Setting và data

Sample chính gồm 1.055 engineers trong firm, viết khoảng 29.959 pieces of code và nhận 174.424 peer comments trong main code-base. Main campus có hai buildings cách nhau vài blocks. Teams một-building gặp trực tiếp hàng ngày; teams đa-building thường đã họp online ngay cả trước COVID.

### Thiết kế chính

Paper dùng difference-in-differences:

- so sánh one-building teams với multi-building teams khi offices còn mở
- rồi xem differential change khi COVID khiến tất cả teams trở nên distributed

Parallel-trends assumption ở đây là one-building và multi-building teams bị sốc bởi pandemic theo cách tương tự, ngoài việc one-building teams mất nhiều proximity hơn. Tác giả hỗ trợ assumption này bằng cách cho thấy engineers làm software tương tự có đặc điểm khá giống nhau và kết quả robust khi cho pandemic effects khác nhau theo software type hay observables.

### Outcomes chính

- feedback / comments per code review
- số commenters, follow-up questions, review length
- programming output: programs per month, lines of code, files changed
- pay raises
- quits
- heterogeneity theo junior/senior và gender

### Kiểm tra cơ chế và externalities

Paper còn làm hai điều rất hay:

1. placebo check: ngồi gần teammates không làm comments từ non-teammates tăng, nên effect không chỉ là coder cần nhiều feedback hơn nói chung
2. externality test: chỉ cần một distant teammate cũng làm feedback giữa những người còn lại cùng building giảm; điều này gợi ý hybrid teams có thể phá cả tương tác giữa những người vẫn cùng chỗ

### Điểm mạnh

- treatment có trực giác rõ
- outcomes đo được ở độ phân giải rất cao
- cơ chế mentorship được đo trực tiếp hơn đa số papers về remote work
- có dynamic career outcomes, không chỉ short-run output

### Điểm dễ bị nghi ngờ

- đây là một firm duy nhất
- output measure không quan sát code quality hoàn hảo
- COVID là shock lớn nên luôn có khả năng đi kèm các thay đổi khác ngoài locational choice
- paper chủ yếu đo software engineers, một occupation vốn đã rất digital

## Results and interpretation

### 1. Proximity làm feedback tăng mạnh

Khi offices còn mở, engineers trên one-building teams nhận 22% nhiều comments hơn engineers trên multi-building teams. Gap này phần lớn biến mất khi offices đóng. Đây là bằng chứng trực tiếp rằng proximity giúp mentorship xảy ra dễ hơn.

Paper còn cho thấy effect đi qua follow-up questions và clarifications: ngồi gần nhau khiến junior engineers thấy dễ hỏi thêm hơn. Nói cách khác, proximity không chỉ thay thế online communication bằng face-to-face; nó còn làm online mentoring itself hoạt động tốt hơn.

### 2. Proximity có externalities mạng lưới

Một distant teammate không chỉ ảnh hưởng người đó với đồng đội. Nó còn làm feedback giữa những người vẫn ở cùng building giảm khoảng 17%. Paper đọc kết quả này như bằng chứng rằng chỉ một thành viên remote cũng có thể đẩy cả team sang meeting mode và interaction mode khác. Đây là insight rất mạnh cho các thiết kế hybrid work.

### 3. Mentorship có opportunity cost thật

Proximity làm programming output giảm. Trong raw comparison khi offices mở, one-building teams submit ít programs hơn; DiD estimate cho thấy proximity làm output giảm khoảng 24%, tương đương khoảng 0,41 programs mỗi tháng. Với senior engineers, cost còn lớn hơn: output giảm khoảng 30%, và chênh lệch trước closure có thể tới 39% trong số programs viết ra.

Kết quả này rất quan trọng về mặt diễn giải. Nó nói mentorship không free. Senior workers dành thời gian review code, giải thích reasoning, và trả lời follow-ups thay vì viết code của chính họ. Junior workers cũng tốn thời gian hấp thụ feedback và sửa code.

### 4. Trade-off ngắn hạn và dài hạn xuất hiện ở pay raises

Khi offices còn mở, junior workers trên one-building teams ít có pay raise hơn khoảng 5 điểm phần trăm, phù hợp với việc short-run output của họ thấp hơn. Nhưng sau khi offices đóng và differential mentoring biến mất, chính những workers đã từng được “train” trên one-building teams lại có xác suất được raise cao hơn khoảng 7 điểm phần trăm. Điều này đặc biệt gợi ý rằng mentorship trước đó tích lũy thành human capital thật.

### 5. Quits cũng nói cùng một câu chuyện

Sau khi remote jobs bùng lên, workers từng được train trên one-building teams có mức tăng quits lớn hơn, khoảng 1,2 điểm phần trăm, và họ có xu hướng chuyển sang các jobs lương cao hơn ở firms khác. Đây là một chỉ báo gián tiếp nhưng rất mạnh rằng training từ proximity có giá trị market ngoài firm, không chỉ trong nội bộ công ty.

### 6. Heterogeneity theo gender rất đáng chú ý

Female engineers trên one-building teams nhận nhiều feedback hơn hẳn: trước closure, chênh lệch lên tới 40% so với female engineers có distant teammates, gấp đôi gap của nam. Khi offices đóng, lost proximity làm feedback của women giảm thêm khoảng 21% so với men. Paper diễn giải điều này chủ yếu qua comfort in asking for clarifications khi ở gần colleagues. Đồng thời senior women cũng chịu cost output lớn hơn vì họ làm nhiều mentoring hơn.

### Diễn giải kinh tế tổng quát

Paper gợi một logic rất sắc:

- proximity tăng informal learning và mentorship
- mentorship làm output hôm nay chậm đi
- nhưng mentorship tích lũy human capital cho ngày mai

Vì vậy, đo remote work bằng productivity ngắn hạn thôi là thiếu. Một firm có thể thấy output hôm nay tăng khi mọi người bớt bị làm phiền, nhưng đồng thời đang âm thầm làm yếu skill accumulation của junior workers.

## What is special or elegant about the paper

Điểm đẹp nhất của bài là nó đổi khung tranh luận. Thay vì hỏi “remote có tốt không”, paper hỏi “office làm được điều gì mà remote khó tái tạo?”. Câu trả lời không phải chỉ là collaboration nói chung, mà là mentorship và learning.

Ba điều đáng học:

1. chọn đúng industry nơi mentorship để lại digital traces, nên cơ chế đo được
2. dùng COVID closure như một shock làm cho variation trước đó trở nên có ý nghĩa causal hơn
3. theo outcomes đủ dài để thấy long-run payoffs của short-run output losses

Bài này cũng là một ví dụ rất hay về applied micro trong tổ chức: design không hoa mỹ, nhưng rất mạnh vì measurement đúng thứ cần đo.

## Required background knowledge

### Human capital accumulation

Nếu skill được hình thành qua feedback, code reviews và day-to-day mentoring, thì workplace proximity có thể ảnh hưởng tới tốc độ tích lũy human capital, đặc biệt với junior workers.

### Difference-in-differences

Hiểu DiD là cần thiết để đọc paper: key idea là one-building teams mất nhiều proximity hơn multi-building teams khi offices đóng, nên differential change sau closure nhận dạng effect của proximity.

### Peer effects và mentorship

Paper này khác peer-effects thông thường ở chỗ nó nhấn mạnh vai trò của more experienced peers như mentors, chứ không chỉ “làm gần người giỏi thì bản thân giỏi hơn”.

### Short-run output versus long-run productivity

Một worker có thể viết ít code hơn hôm nay vì đang học, nhưng điều đó không có nghĩa worker đó kém hơn về dài hạn. Paper yêu cầu người đọc tách hai horizon này ra.

## Limitations and open questions

1. Bài dựa trên một firm và một occupation rất đặc thù; external validity sang các ngành khác cần cẩn thận.
2. Output được đo bằng lượng code hơn là code quality hoàn chỉnh.
3. COVID closure không phải một randomized experiment hoàn hảo; vẫn có nhiều stressors đồng thời.
4. Paper mới chỉ gợi ý về cách thiết kế hybrid work tối ưu; chưa trả lời chính xác cần bao nhiêu ngày in-office là đủ để giữ phần lớn mentorship benefits.

## Takeaways for a researcher

1. Một gain ngắn hạn về output có thể che giấu một loss dài hạn về human capital.
2. Muốn chứng minh cơ chế, hãy tìm setting nơi cơ chế đó để lại dữ liệu hành vi trực tiếp.
3. Hybrid work không chỉ là average remote share; chỉ một distant teammate cũng có thể làm hỏng interaction structure của cả team.
4. Heterogeneity theo seniority và gender không phải phụ lục; ở đây nó là chìa khóa để hiểu mechanism.
5. Với organizational economics, career outcomes và quits đôi khi nói nhiều hơn output contemporaneous.

## Vietnam relevance and extension

### Liên hệ với Việt Nam

Paper này rất liên quan với Việt Nam vì nhiều firms công nghệ, ngân hàng, dịch vụ số, BPO, và các tập đoàn lớn hiện cũng đang loay hoay với hybrid work. Câu hỏi không chỉ là “remote có tiết kiệm văn phòng không”, mà là “junior staff còn học được đủ nhanh không”.

### Có thể triển khai ý tưởng nghiên cứu này ở Việt Nam không?

Có thể, nhất là ở:

- software firms
- call centers / BPO
- ngân hàng số và product teams
- các doanh nghiệp có hệ thống ticketing, code review, CRM logs hoặc QA logs

### Điều kiện cần có

- dữ liệu team structure và thời gian làm việc on-site/remote
- digital traces của feedback, review hoặc mentoring
- outcome ngắn hạn và career outcomes dài hơn
- một shock hoặc policy variation đủ rõ để nhận dạng

### Trở ngại chính

- nhiều firms Việt Nam chưa lưu đủ dữ liệu interaction
- hybrid policies thường thay đổi cùng nhiều thứ khác
- khó đo quality của output trong nhiều ngành ngoài software

### Một vài research questions cho Việt Nam

1. Hybrid work ở các product teams Việt Nam có làm junior workers nhận ít feedback hơn không?
2. Các call-center hoặc operations teams ở Việt Nam có mất mentoring quality khi supervisor không còn ngồi gần trực tiếp không?
3. Có thể thiết kế lịch hybrid theo team-days để giữ mentorship benefits mà vẫn tiết kiệm chi phí văn phòng hay không?

## Storage status and limitations

- `analysis.md`: mục tiêu lưu trên GitHub trong lượt này
- `analysis.html`: sẽ lưu nếu bước tạo file văn bản thành công
- `analysis.pdf`: chưa được coi là đã lưu trên GitHub
- PDF gốc của paper: mới xác minh được nguồn công khai đáng tin cậy; chưa lưu file nhị phân vào GitHub trong lượt này
- Google Drive: bỏ qua có chủ đích để tránh báo cáo quá mức khi chưa tạo được Google-native files đúng folder đích