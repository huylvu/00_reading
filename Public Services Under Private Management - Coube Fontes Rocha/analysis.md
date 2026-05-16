# Public Services Under Private Management

- **Tác giả:** Maíra Coube, Luiz Felipe Fontes, Rudi Rocha
- **Journal:** The Quarterly Journal of Economics (accepted manuscript, open access)
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-16
- **Nguồn bài báo chính:** https://academic.oup.com/qje/advance-article/doi/10.1093/qje/qjag028/8676724
- **Nguồn PDF:** https://academic.oup.com/qje/advance-article-pdf/doi/10.1093/qje/qjag028/68275289/qjag028.pdf
- **Trạng thái lưu trên GitHub:** Chưa lưu tại thời điểm soạn bản cục bộ; sẽ cập nhật sau khi thử thao tác GitHub trong lượt này.
- **Trạng thái lưu trên Google Drive:** Chưa thực hiện; chỉ làm nếu tạo được Google Doc đúng folder đích một cách đáng tin cậy.
- **Ghi chú về PDF:** Đây là accepted manuscript open-access của QJE. Môi trường shell trong lượt này không tải được file nhị phân trực tiếp từ nguồn ngoài do lỗi proxy, nên phần đọc sâu bám vào nội dung PDF truy cập được qua công cụ web tích hợp.

## Executive summary

Bài này hỏi một câu rất thực tế nhưng cũng rất "QJE": có thể giao **quản lý** dịch vụ công cho tư nhân mà vẫn giữ **quyền sở hữu tài sản và quyền hưởng phần dư** ở phía nhà nước, để lấy hiệu quả mà không đánh đổi chất lượng hay công bằng hay không?

Trong bối cảnh bệnh viện công ở Brazil, tác giả nghiên cứu mô hình `OSS` (Organizações Sociais de Saúde), nơi bệnh viện vẫn là bệnh viện công, vẫn phục vụ phổ cập, nhưng khâu quản trị được giao cho tổ chức tư nhân phi lợi nhuận dưới các hợp đồng có chỉ tiêu hiệu suất. Dùng dữ liệu hành chính cực rộng về bệnh viện, nhân sự y tế, nhập viện và tử vong giai đoạn 2005-2022, bài dùng `staggered difference-in-differences` kết hợp matching để so sánh các bệnh viện chuyển sang OSS với các bệnh viện công tương đồng còn do nhà nước quản lý.

Kết quả chính rất mạnh: số ca nhập viện tăng khoảng 40% so với baseline; productivity của bệnh viện tăng rõ, thể hiện qua bed turnover tăng 23%, occupancy tăng 14%, thời gian nằm viện giảm; nhưng không thấy xấu đi ở mortality nội trú, readmission hay profile bệnh nhân. Quan trọng hơn, bài cho thấy các bệnh viện OSS mở rộng tiếp cận điều trị cho dân địa phương và gắn với giảm khoảng 3% mortality ở cấp municipality. Cơ chế chính không phải là đổ thêm nhiều vốn hay thiết bị, mà là **quản trị tốt hơn**: linh hoạt hơn trong nhân sự, dùng nhiều hợp đồng theo hiệu suất hơn, tuyển bác sĩ chuyên môn cao hơn, và tỷ lệ rời đi cao hơn tập trung ở nhóm bác sĩ productivity thấp.

Đây là paper đáng đọc vì nó không chỉ nói "tư hay công tốt hơn", mà chỉ ra rằng **thiết kế governance** mới là mấu chốt. Khi private manager không giữ residual claimant rights và bị ràng buộc bởi mục tiêu công cùng universal access, trade-off quen thuộc giữa quantity và quality có thể dịu đi đáng kể.

## Research question and motivation

### Câu hỏi nghiên cứu trung tâm

Liệu outsourcing quản lý dịch vụ công sang khu vực tư nhân có thể cải thiện hiệu quả mà **không** làm giảm chất lượng và công bằng, đặc biệt trong những ngành như y tế nơi chất lượng khó contract và khó quan sát?

### Bối cảnh học thuật và thực tiễn

Văn liệu kinh tế về ownership và incomplete contracts từ Hart, Shleifer, Vishny, Besley-Ghatak đặt ra một tension rất rõ. Tư nhân có thể mạnh hơn về động lực cắt giảm lãng phí và tổ chức sản xuất, nhưng cũng có thể cắt nhầm vào quality hoặc loại bỏ đối tượng "khó phục vụ" khi hợp đồng không viết hết được mọi chiều chất lượng.

Y tế là bài test đặc biệt khó vì:

- đầu ra vừa nhiều chiều vừa khó đo lường
- chất lượng lâm sàng không thể contract hóa đầy đủ
- bệnh viện có thể tăng volume nhưng làm xấu quality hoặc equity
- bệnh nhân nghèo, ca nặng, ca ít lợi nhuận dễ bị ảnh hưởng nếu incentive sai

Vì vậy, câu hỏi không còn là "privatize hay không", mà là **privatize phần nào, với quyền gì, hợp đồng gì, residual claimant là ai**.

### Khoảng trống mà bài muốn lấp vào

Lý thuyết ownership rất giàu, nhưng bằng chứng thực nghiệm về những mô hình governance lai giữa nhà nước và tư nhân trong dịch vụ công phức tạp vẫn còn mỏng. Nhiều nghiên cứu trước trong healthcare nhấn mạnh mặt trái của tư nhân hóa khi private operator có quyền mạnh về surplus hoặc khi quality phi hợp đồng hóa. Paper này lấp khoảng trống bằng cách xét một setting nơi:

- quản lý được giao cho tư nhân phi lợi nhuận
- tài sản và funding vẫn công
- bệnh viện vẫn universal-access, không thu phí, không cạnh tranh để chọn bệnh nhân
- surplus rights vẫn do nhà nước giữ

Tức là bài test đúng một cấu hình governance mà theory dự đoán có thể cho kết quả khác với privatization kiểu đầy đủ.

## Main contribution

### 1. Đóng góp vào tranh luận state versus market theo cách tinh hơn

Đóng góp lớn nhất của bài là chỉ ra rằng ranh giới "công" và "tư" không nên được hiểu theo nhị phân. Cái quan trọng là phân bổ quyền kiểm soát, quyền hưởng phần dư, độ linh hoạt quản trị, và các mục tiêu contractible được gắn vào operator. Đây là một đóng góp rất mạnh cho applied micro lẫn political economy of public service delivery.

### 2. Bằng chứng nhân quả quy mô lớn trong healthcare public management

Bài xây một bộ dữ liệu hành chính mới cho Brazil và khai thác 127 bệnh viện công chuyển từ state management sang OSS trong giai đoạn 2005-2022. Đó là một setting thực tế, quy mô lớn, và rất phù hợp để nói về external validity cho cải cách công.

### 3. Mở "hộp đen" cơ chế quản trị

Nhiều paper chỉ dừng ở chuyện outcome tốt hơn hay xấu hơn. Bài này đi sâu hơn:

- cơ cấu bác sĩ thay đổi ra sao
- hợp đồng lao động thay đổi ra sao
- ai bị thay thế, ai được giữ lại
- productivity ở cấp worker thay đổi thế nào
- managerial experience của tổ chức quản lý có tạo ra heterogeneity hay không

Đây là phần làm paper mạnh lên rất nhiều, vì nó nối kết outcome aggregate với organizational economics thực sự.

### 4. Nêu bật vai trò của managerial capacity

Không chỉ "private management" nói chung mới quan trọng. Bài cho thấy bệnh viện do OSS nhiều kinh nghiệm quản lý đạt gain lớn hơn rõ rệt; ngược lại, OSS ít kinh nghiệm dựa nhiều hơn vào mở rộng capacity và tạo ra productivity gain yếu hơn. Đây là một kết quả rất đáng giá cho policy design.

## Identification or methodology

### Setting thể chế

Mô hình `OSS` ở Brazil giao phần **quản lý bệnh viện công** cho tổ chức tư nhân phi lợi nhuận, nhưng:

- bệnh viện vẫn thuộc sở hữu công
- tài trợ vẫn công
- bệnh viện không thu phí và vẫn phổ cập
- hợp đồng gắn với chỉ tiêu output và quality có thể đo được
- tổ chức quản lý không được giữ budgetary surplus để phân phối cho mình; phần dư phải tái đầu tư vào cải thiện dịch vụ

Điểm này cực kỳ quan trọng. Nó làm setting khác hẳn với privatization đơn thuần, nơi operator giữ residual claimant rights và có động cơ mạnh để cắt chi phí bằng cách hy sinh chiều chất lượng khó đo.

### Dữ liệu

Paper dùng dữ liệu hành chính rất phong phú:

- dữ liệu admissions và outcomes của toàn hệ thống y tế công
- dữ liệu input bệnh viện từ `CNES`
- dữ liệu nhân sự y tế, loại hợp đồng, tenure, chuyên môn
- dữ liệu định danh bác sĩ để đo kinh nghiệm và specialty
- dữ liệu municipality-level mortality

Khoảng thời gian là 2005-2022. Tác giả ban đầu nhận diện 236 bệnh viện OSS, sau đó giữ lại **127 switchers** thực sự chuyển từ direct public administration sang OSS và loại các trường hợp always-OSS hay thiếu pre-period. Nhóm đối chứng xuất phát từ gần **2,800 bệnh viện công** vẫn do nhà nước quản lý.

### Chiến lược nhận dạng

Thiết kế chính là:

1. match từng bệnh viện treated với một control hospital tương đồng theo propensity score
2. dùng `staggered DiD` vì thời điểm chuyển sang OSS khác nhau giữa các bệnh viện
3. ước lượng theo khung `Callaway and Sant'Anna (2021)` để tránh các vấn đề của two-way fixed effects khi treatment timing khác nhau và effect dị biệt theo cohort/event time

Matching dùng trung bình 5 năm pre-treatment của các biến như:

- số bệnh nhân
- số giường
- số nhân viên
- thiết bị
- macro-region

Tác giả cố ý không match theo vị trí quá gần để giảm nguy cơ spillover trực tiếp, và sau đó còn kiểm tra spillover riêng.

### Giả định cốt lõi

Giả định nền là `conditional parallel trends`: sau khi điều kiện hóa theo region, size, patient volume và matching covariates, treated và control sẽ có xu hướng outcome giống nhau nếu không có OSS.

### Vì sao chiến lược này mạnh

- policy rollout có variation theo thời gian và giữa bệnh viện
- matching làm donor pool hợp lý hơn
- event-study/pre-trend checks giúp đánh giá giả định
- dữ liệu outcome rất gần với hoạt động thực tế, không chỉ là survey
- paper kiểm tra robustness với control groups khác, điều chỉnh trend theo covariates, patient characteristics theo thời gian, và phân tích ở mức dân số

### Điểm dễ bị nghi ngờ

- adoption OSS không phải random; dù pre-trends và robustness khá thuyết phục, luôn còn khả năng các bệnh viện chuyển đổi có lãnh đạo địa phương năng động hơn hoặc chịu áp lực cải cách khác
- quality trong y tế vẫn khó đo hết; mortality và readmission là tốt nhưng chưa bao trùm toàn bộ patient experience hay long-run health
- chi phí không phải outcome trung tâm có dữ liệu causal tốt như output và quality; phần cost-effectiveness vẫn còn chủ yếu là bằng chứng gợi ý

## Results and interpretation

### 1. Output tăng mạnh

Kết quả headline là admissions tăng khoảng **40%** so với baseline sau khi chuyển sang OSS. Đây là mức rất lớn và nhất quán giữa nhiều loại chăm sóc, kể cả các điều kiện ít defer được.

Diễn giải kinh tế: trước cải cách có vẻ tồn tại slack rất lớn trong vận hành bệnh viện công. OSS giúp "mở nút thắt" quản trị hơn là chỉ tăng nguồn lực.

### 2. Productivity tăng, không chỉ capacity tăng

Các chỉ số productivity cho thấy:

- `bed turnover` tăng khoảng **23%**
- `occupancy rate` tăng khoảng **14%**
- `length of stay` giảm

Đây là pattern rất đáng chú ý. Nếu admissions tăng chỉ vì thêm giường hoặc thêm thiết bị, ta không nhất thiết thấy turnover và occupancy cùng cải thiện như vậy. Bài cho thấy tăng capacity có tồn tại, nhưng chỉ giải thích **một phần nhỏ** của output growth.

### 3. Chất lượng và công bằng không xấu đi

Paper không tìm thấy bằng chứng rằng OSS làm xấu:

- risk-adjusted inpatient mortality
- readmission rates
- acute-case outcomes
- profile bệnh nhân theo tuổi, giới, income, risk indicators

Điểm này cực kỳ quan trọng. Nó làm cho câu chuyện "admissions tăng" không bị hiểu là do cherry-picking bệnh nhân dễ điều trị hoặc chạy theo chỉ tiêu bằng cách đẩy chất lượng xuống.

### 4. Hiệu ứng lan sang population health

Ở cấp municipality, các bệnh viện OSS làm tăng tiếp cận hospital care cho dân địa phương, đặc biệt ở khu vực underserved, và gắn với giảm khoảng **3% mortality toàn bộ**. Đây là một bước rất mạnh trong logic paper: họ không chỉ cải thiện chỉ số nội bộ của bệnh viện, mà còn tạo hệ quả y tế ở cấp dân số.

### 5. Cơ chế chính là quản trị nhân sự

OSS dường như thay đổi mạnh "technology of management":

- nhân sự tăng, nhưng nhìn theo số giường thì mức tăng không lớn, cho thấy không phải đơn thuần bơm thêm lao động
- bệnh viện OSS tuyển bác sĩ có chuyên môn cao hơn
- dịch chuyển sang hợp đồng linh hoạt hơn, đặc biệt independent contracting tăng gần **65%**
- separation tăng tập trung ở nhóm bác sĩ productivity thấp
- output trên mỗi bác sĩ tăng

Đây là phần rất đẹp của bài: productivity gain không được kể như một hộp đen, mà được nối trực tiếp với personnel reallocation.

### 6. Managerial experience tạo ra heterogeneity có ý nghĩa

Những OSS có nhiều kinh nghiệm quản lý bệnh viện tạo ra gain lớn hơn nhiều về output, productivity và giảm mortality. Trong khi đó, OSS ít kinh nghiệm dựa nhiều hơn vào mở rộng capacity. Hàm ý là private participation tự nó chưa đủ; chất lượng của organization được giao quản lý mới là điểm quyết định.

### 7. Spillover âm không phải động cơ chính

Bài không tìm thấy bằng chứng rõ rằng bệnh viện OSS hút bác sĩ hay nguồn lực từ bệnh viện lân cận để tạo thành tích cho mình. Điều này giúp lập luận về scalability đáng tin hơn.

## What is special or elegant about the paper

Điểm đẹp nhất của paper là nó làm sáng rõ một ý rất kinh tế học: **không phải cứ "tư nhân hóa" là một treatment đồng nhất**. Phân bổ quyền residual claimant, contractible targets, và autonomy trong human-resource management mới là thứ quyết định equilibrium.

Paper cũng rất thanh lịch ở chỗ:

- bắt đầu từ một tranh luận lý thuyết kinh điển về incomplete contracts
- tìm được một institutional setting gần như "designed experiment" cho tranh luận đó
- dùng dữ liệu hành chính đủ sâu để mở cơ chế
- đi từ hospital outcomes tới population outcomes
- thêm heterogeneity theo managerial capacity, nên paper không kết thúc ở một average treatment effect đơn giản

Về mặt craft, đây là kiểu paper mà người đọc học được cách biến một câu hỏi tưởng như normative thành một bài applied micro có identification rõ và policy bite mạnh.

## Required background knowledge

### 1. Incomplete contracts và ownership

Ý cơ bản: hợp đồng không thể mô tả và enforce mọi chiều chất lượng. Khi private operator giữ quyền hưởng phần dư, họ có thể có động lực cắt giảm chi phí quá tay ở các chiều không đo được. Hart, Shleifer, Vishny là nền tảng quan trọng cho trực giác này.

### 2. Residual claimant rights

Ai giữ "phần còn lại" sau khi thu chi được quyết toán sẽ có động lực khác nhau. Nếu operator giữ surplus, họ sẽ nội hóa lợi ích của cắt chi phí. Nếu nhà nước giữ surplus và operator chỉ bị ràng buộc bởi contract targets, incentive có thể nghiêng nhiều hơn về hoàn thành nhiệm vụ công.

### 3. Staggered difference-in-differences

Khi các đơn vị nhận treatment ở các thời điểm khác nhau, TWFE cổ điển có thể trộn lẫn các comparison không mong muốn. Callaway-Sant'Anna giúp ước lượng effect theo cohort-event time một cách sạch hơn.

### 4. Matching như design choice

Matching ở đây không thay thế identification, nhưng làm nhóm control gần với treated hơn trước khi chạy DiD. Điều này giúp comparison dễ tin hơn trong một setting mà treated hospitals khác control khá xa về quy mô và vị trí.

### 5. Risk adjustment trong y tế

Khi so sánh mortality/readmission giữa bệnh viện, phải điều chỉnh case mix. Nếu không, bệnh viện nhận bệnh nặng hơn có thể bị đánh giá oan là quality thấp.

### 6. Organizational economics và quản trị nhân sự

Paper nằm ở giao điểm giữa public economics, health economics và organizational economics. Để hiểu paper sâu, nên nắm ý niệm rằng productivity không chỉ do capital hay technology, mà còn do cách tổ chức con người, contract, tuyển chọn và sa thải.

## Limitations and open questions

### Hạn chế chính

1. Dù identification mạnh, đây vẫn là cải cách không random.
2. Quality trong bệnh viện được đo tốt hơn nhiều paper khác, nhưng vẫn chưa bao trùm mọi khía cạnh như patient satisfaction, continuity of care, hay long-run morbidity.
3. Dữ liệu chi phí còn hạn chế; bằng chứng về efficiency rất thuyết phục, nhưng cost-benefit toàn phần vẫn chưa đóng lại hoàn toàn.
4. Setting là Brazil và một mô hình OSS khá đặc thù; external validity cần đi qua cấu trúc pháp lý và labor institutions của từng nước.
5. Bài là accepted manuscript chứ chưa phải bản typeset cuối cùng; nội dung cốt lõi có thể giữ nguyên nhưng trình bày cuối cùng có thể khác nhẹ.

### Câu hỏi mở

- Hiệu ứng còn giữ được khi scale lớn hơn nhiều hay không?
- Governance nào của contract là quan trọng nhất: target design, monitoring, provider selection, hay personnel autonomy?
- Có nguy cơ mission drift trong horizon dài hơn 5-10 năm không?
- Tác động lên các nhóm bệnh chuyên khoa khó đo chất lượng hơn có khác không?
- Liệu mô hình này có hiệu quả như nhau khi áp dụng cho các dịch vụ công khác ngoài hospital care?

## Takeaways for a researcher

1. Đừng đóng khung câu hỏi kiểu "public versus private". Hãy viết treatment theo ngôn ngữ của quyền kiểm soát, incentive, và governance design.
2. Một paper applied mạnh thường thắng ở chỗ mở được cơ chế. Ở đây, worker-level personnel data là chìa khóa.
3. Khi treatment rollout bị staggered, cần rất cẩn thận với estimator; chọn đúng công cụ econometrics là một phần của contribution.
4. Policy relevance mạnh hơn nhiều khi nối được intermediate outcomes với welfare-relevant outcomes ở cấp dân số.
5. Heterogeneity theo manager/provider quality thường không phải phụ lục; nhiều khi đó mới là insight trung tâm cho policy.
6. Trong public-service settings, một kết quả "output tăng mà quality không giảm" vẫn chưa đủ; phải kiểm tra cả equity và spillovers.

## Vietnam relevance and extension

### Vì sao paper này gợi ý mạnh cho Việt Nam

Việt Nam cũng có những căng thẳng rất giống bài này:

- bệnh viện công chịu nhiều ràng buộc hành chính
- nhu cầu nâng hiệu quả vận hành rất lớn
- câu chuyện tự chủ bệnh viện, liên doanh liên kết, thuê dịch vụ, khoán chi, hay trao quyền cho ban giám đốc luôn gây tranh luận
- nỗi lo lớn nhất vẫn là trade-off giữa efficiency với quality và công bằng tiếp cận

Paper này gợi ý rằng câu hỏi đúng cho Việt Nam không phải "nên tư nhân hóa bệnh viện công hay không", mà là:

- có thể trao quyền quản trị nhiều hơn ở khâu nào
- ai giữ quyền với phần dư tài chính
- chỉ tiêu nào nên contract hóa
- cơ chế kiểm soát equity và universal access ra sao
- chọn đơn vị quản lý theo năng lực thế nào

### Có triển khai nghiên cứu tương tự ở Việt Nam được không?

Có thể, nhưng cần điều kiện dữ liệu và thể chế khá khó:

- dữ liệu panel bệnh viện theo năm về admissions, bed occupancy, length of stay, mortality, readmission
- dữ liệu nhân sự bệnh viện ở cấp bác sĩ/điều dưỡng, loại hợp đồng, tenure, specialty
- biến thể chế đủ rõ về thời điểm một bệnh viện được trao autonomy hay chuyển sang mô hình quản trị khác
- khả năng nối hospital-level outcomes với district/province-level health outcomes

### Trở ngại chính ở Việt Nam

- dữ liệu hành chính thường phân tán giữa Bộ Y tế, BHYT, Sở Y tế, và từng bệnh viện
- thông tin về hợp đồng lao động và productivity cá nhân của bác sĩ có thể khó tiếp cận
- cải cách quản trị ở Việt Nam có thể ít "rạch ròi" hơn một switch institutionally clean như OSS
- measurement của quality và patient selection sẽ là thách thức lớn

### Hướng cập nhật hoặc làm mới cho Việt Nam

1. So sánh các bệnh viện công được trao mức tự chủ khác nhau về tài chính và nhân sự để xem output, quality, và equity thay đổi ra sao.
2. Nghiên cứu tác động của quyền linh hoạt nhân sự của ban giám đốc bệnh viện lên phân bổ bác sĩ, năng suất và kết quả điều trị.
3. Đánh giá liệu các mô hình thuê ngoài khâu quản trị hoặc vận hành cận lâm sàng có tạo productivity gain mà không làm xấu outcome cho bệnh nhân BHYT hay không.

### Một vài research question có thể phát triển ở Việt Nam

1. Trao quyền tuyển dụng và trả lương linh hoạt hơn cho bệnh viện công có làm tăng throughput và giảm thời gian chờ mà không làm xấu quality không?
2. Các bệnh viện công có mức tự chủ cao hơn có tái phân bổ bác sĩ theo hướng trọng dụng người năng suất cao và loại bớt bottleneck nhân sự hay không?
3. Nếu một số tỉnh áp dụng mô hình quản trị bệnh viện linh hoạt hơn sớm hơn, có thể dùng staggered reform design để đo tác động lên mortality tránh được hoặc utilization của người nghèo không?

## Notes on storage and execution limits

- Bản phân tích này hoàn thành dựa trên metadata và nội dung PDF đã được xác minh chắc từ QJE.
- Trong lượt chạy này, nguồn PDF chính thức đã được xác minh nhưng shell cục bộ không tải trực tiếp file nhị phân về do lỗi proxy `403 CONNECT tunnel failed`.
- `analysis.pdf` không phải artifact bắt buộc và chưa được tạo trong lượt này.
- Nếu GitHub hoặc email không đi qua được ở bước sau, trạng thái cuối cùng cần hiểu là chỉ hoàn thành bản phân tích cục bộ và chưa hoàn tất lưu trữ/phát hành tương ứng.
