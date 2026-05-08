# Selection in Surveys: Using Randomized Incentives to Detect and Account for Nonresponse Bias

- **Tác giả:** Deniz Dutz, Ingrid Huitfeldt, Santiago Lacouture, Magne Mogstad, Alexander Torgovitsky, Winnie van Dijk
- **Journal:** The Review of Economic Studies
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-08
- **Nguồn bài báo chính:** https://academic.oup.com/restud/advance-article-abstract/doi/10.1093/restud/rdag003/8494738
- **Nguồn PDF dùng để phân tích:** NBER Working Paper 29549, bản `December 2021, Revised July 2025` tại https://www.nber.org/system/files/working_papers/w29549/w29549.pdf
- **Trạng thái lưu trên GitHub:** sẽ cập nhật ở cuối lượt chạy sau khi upload thực tế
- **Trạng thái lưu trên Google Drive:** chưa thử trong thời điểm soạn bản cục bộ này

## Executive summary

Bài này hỏi một câu rất căn bản nhưng thường bị xem nhẹ trong applied micro: khi ta dùng survey để đo outcome, liệu những người chịu trả lời survey có khác một cách có hệ thống so với những người không trả lời hay không, và nếu có thì ta phát hiện rồi sửa thiên lệch đó bằng cách nào. Câu trả lời của paper là: có, sự khác biệt đó có thể lớn; hơn nữa, tăng incentive để kéo response rate lên không nhất thiết làm bias nhỏ đi, thậm chí có thể làm bias nặng hơn nếu nó hút vào đúng một nhóm “marginal respondents” khác biệt mạnh với dân số mục tiêu.

Về thiết kế, tác giả dùng survey “Norway in Corona Times” do Statistics Norway triển khai trong giai đoạn đầu COVID-19. Từ dân số trưởng thành của Na Uy, họ rút mẫu ngẫu nhiên, randomize incentive trả lời survey, rồi nối survey với administrative data của toàn bộ dân số để có một “ground truth” rất hiếm: họ quan sát được outcomes lao động không chỉ của người trả lời mà cả của người không trả lời. Nhờ vậy họ vừa đo trực tiếp nonresponse bias, vừa kiểm định các phương pháp hiệu chỉnh phổ biến.

Kết quả chính rất mạnh. Participant khác nonparticipant khá lớn về earnings và employment, và reweighting theo observables không xóa được khác biệt này. So sánh mean responses giữa các incentive arms cho thấy survey responses bản thân chúng cũng bị bias. Nhiều phương pháp chuẩn để sửa selection on unobservables hoặc cho ra bounds quá rộng, hoặc cho point estimates/bounds lệch khỏi ground truth. Đóng góp kỹ thuật nổi bật của paper là mô hình hai chiều về participation: một chiều phản ánh mức nhạy với incentive, một chiều phản ánh khả năng thực sự nhìn thấy email/reminder. Mô hình này giải thích vì sao các correction một chiều thất bại, và cho estimates gần ground truth hơn đáng kể.

Đây là bài rất đáng đọc vì nó buộc applied researchers phải coi survey design là một phần của identification chứ không chỉ là logistics. Paper cũng rất đẹp ở chỗ nó kết nối design-based randomization, missing-data logic, IV intuition, partial identification, và practical survey operations trong cùng một khung thống nhất.

## 1. Research question and motivation

Câu hỏi trung tâm của paper là: làm sao phát hiện và hiệu chỉnh nonresponse bias trong survey khi participation phụ thuộc vào những yếu tố mà nhà nghiên cứu không quan sát được nhưng lại có liên quan trực tiếp tới outcome cần đo.

Động lực của bài đến từ hai thực tế. Thứ nhất, survey vẫn là đầu vào cực quan trọng cho cả policy lẫn empirical economics. Thứ hai, kinh tế học hiện đại ngày càng ám ảnh đúng đắn với selection và missing data trong causal inference, nhưng paradox là trong survey-based research, nonresponse bias thường vẫn bị đối xử khá hời hợt. Paper cho thấy gần một nửa các bài survey-based mà họ review không bàn gì về nonresponse bias, dù response rates thường không hề cao.

Khoảng trống mà bài muốn lấp là khoảng trống giữa survey methodology và applied economics. Survey literature từ lâu đã lo về nonresponse, nhưng nhiều applied papers trong economics vẫn dựa vào hai phản xạ quen thuộc: hoặc mặc định missing at random conditional on observables, hoặc coi response rate cao hơn là tự động tốt hơn. Paper cho thấy cả hai phản xạ này đều có thể sai nghiêm trọng.

## 2. Main contribution

Đóng góp đầu tiên là một idea thiết kế rất gọn mà rất mạnh: randomize participation incentives và dùng chênh lệch mean responses giữa incentive groups như một test trực tiếp cho nonresponse bias. Nếu incentives không tác động trực tiếp lên câu trả lời, mà chỉ làm thay đổi composition của người trả lời, thì khác biệt giữa các arms chính là bằng chứng selection.

Đóng góp thứ hai là dữ liệu. Đây là một setting rất hiếm nơi survey được nối với administrative records của toàn bộ population mục tiêu. Nhờ đó tác giả không chỉ nói “có thể có bias”, mà đo được bias thật sự của participants so với dân số, rồi đem các correction methods ra chấm điểm bằng ground truth.

Đóng góp thứ ba là conceptual. Paper chỉ ra rằng participation trong survey không nên bị hình dung như một chiều “willingness to respond” duy nhất. Có ít nhất hai cơ chế khác nhau: active nonresponse, tức thấy lời mời nhưng không thấy đủ đáng để trả lời; và passive nonresponse, tức thực ra không nhìn thấy email hay chỉ nhìn thấy sau reminder. Hai cơ chế này có thể kéo sample composition theo hai hướng ngược nhau.

Đóng góp thứ tư là methodological. Từ insight hai chiều đó, tác giả xây dựng một participation model kết hợp incentive variation với reminder timing. Mô hình này cho phép tạo bounds hoặc point estimates cho population mean dưới các shape restrictions hợp lý hơn, và trên dữ liệu của họ thì nó hoạt động tốt hơn hẳn các cách chuẩn.

Với applied micro, bài này quan trọng vì nó biến survey implementation thành một nguồn variation có giá trị nhận dạng. Với development economics, nó đặc biệt đáng chú ý vì rất nhiều nghiên cứu dựa nặng vào phone survey, panel attrition, field follow-up, hay endline survey trong các bối cảnh response thấp và contact quality không đồng đều.

## 3. Identification or methodology

### 3.1 Setting và experimental design

Survey được triển khai tại Na Uy để đo tác động lao động tức thời của đợt lockdown đầu COVID-19. Population mục tiêu là toàn bộ cư dân từ 18 tuổi trở lên tính đến ngày 1/4/2020. Từ population này, Statistics Norway rút mẫu ngẫu nhiên 10.000 người. Bài tập trung vào nhánh online survey, chiếm 93% mẫu.

Invitation được gửi qua email khi có địa chỉ email, và qua thư thường nếu không có; đồng thời nhiều người còn nhận được SMS thông báo. Survey mở từ 20/4/2020 đến 22/5/2020, với sáu reminder messages trong quá trình thu thập.

Điểm then chốt là randomization incentives. Người được mời được phân vào 5 nhóm với xác suất trúng prepaid card trị giá 1.000 NOK lần lượt là 0%, 1%, 5%, 7%, và 10%. Kỳ vọng tiền thưởng dao động từ khoảng 1,1 USD đến 11 USD. Trong phân tích chính, tác giả gộp các arms này thành ba nhóm `no`, `low`, và `high` để tăng precision. Response rate tăng khoảng 2 điểm phần trăm từ `no` sang `low`, và tăng thêm khoảng 4 điểm phần trăm từ `low` sang `high`. Tổng cộng, kỳ vọng thưởng khoảng 10 USD làm participation tăng khoảng 6 điểm phần trăm, tương đương khoảng 13%.

### 3.2 Logic nhận dạng của bài test nonresponse bias

Logic rất đơn giản mà mạnh. Do incentive được randomize, các arms là ex ante comparable. Nếu không có nonresponse bias, thì dù participation rate có khác nhau, mean responses của những người trả lời trong các arms lẽ ra vẫn phải giống nhau, miễn là incentive không trực tiếp làm thay đổi câu trả lời. Vì vậy, khác biệt mean responses giữa incentive groups là dấu hiệu trực tiếp của selection vào sample trả lời.

Paper dùng administrative outcomes để đo trực tiếp khoảng cách giữa participants và toàn population, sau đó dùng survey responses để chạy “test nội sinh” mà một researcher thông thường cũng có thể làm ngay cả khi không có admin linkage. Đây là phần rất thực dụng của bài: họ không chỉ nói về một theorem đẹp, mà đưa ra một diagnostic có thể nhúng vào survey design thật.

### 3.3 Đo selection trên observables và unobservables

Trước hết, tác giả so sánh participant means với population means bằng administrative data. Sau đó họ thử các cách reweighting bằng municipality-level và individual-level observables. Khi chênh lệch vẫn lớn sau reweighting, đó là bằng chứng rằng selection on observables không đủ.

Tiếp theo, họ dùng IV-style decomposition để tách `inframarginal participants` và `marginal participants`. Inframarginal là những người sẽ trả lời cả khi không có incentive; marginal là những người chỉ trả lời khi incentive cao hơn. Nếu marginal khác inframarginal mạnh về outcomes nhưng không khác mấy về observables cơ bản, đó là dấu hiệu rất rõ của selection on unobservables.

### 3.4 Các phương pháp correction được đem ra kiểm tra

Paper lần lượt thử:

1. worst-case bounds kiểu Manski
2. bounds tận dụng random assignment của incentive
3. bounds thêm monotonicity hoặc monotone instrumental variable style restrictions
4. selection model một chiều dựa trên latent willingness to respond
5. mô hình hai chiều mới của tác giả, kết hợp incentive với thời điểm reminder

Lợi thế cực lớn của setting này là từng phương pháp có thể bị chấm điểm bằng ground truth. Không nhiều paper làm được chuyện đó.

### 3.5 Mô hình hai chiều

Đây là phần đẹp nhất về mặt ý tưởng. Tác giả cho rằng participation phụ thuộc vào hai latent dimensions:

- `V_i`: mức kháng cự với incentive, tức muốn nói “nếu tôi thấy lời mời, incentive có đủ hấp dẫn để tôi trả lời không”
- `S_i`: thời điểm cá nhân thực sự nhìn thấy invitation hoặc reminder, tức mức độ awareness hay reachability

Với mô hình một chiều, người không trả lời khi incentive cao chỉ bị xem là “rất unwilling”. Nhưng trong thực tế, một số người không trả lời vì họ chưa từng thấy email. Gộp hai loại này vào chung một latent dimension làm bài toán extrapolation từ responders sang nonresponders bị méo mạnh. Reminder timing tạo ra variation để nhận dạng chiều thứ hai này.

### 3.6 Điểm mạnh và điểm dễ bị nghi ngờ

Điểm mạnh:

- randomization của incentive rất sạch
- population sample là random sample từ registry gần như bao phủ toàn bộ dân số trưởng thành
- admin linkage tạo benchmark hiếm có
- bài không né phần khó: họ cho thấy method nào fail, fail ở đâu, và vì sao fail

Điểm dễ bị chất vấn:

- key exclusion restriction là incentive không trực tiếp đổi câu trả lời, chỉ đổi composition người trả lời
- mô hình hai chiều vẫn cần auxiliary shape restrictions để đi từ partial identification sang estimates gọn hơn
- reminder timing không hoàn toàn là random treatment; nó được dùng như nguồn variation cấu trúc trong mô hình, nên interpretation phải cẩn thận
- context là một survey khủng hoảng ở Na Uy giai đoạn đầu COVID-19; external validity sang các setting khác cần cân nhắc

## 4. Results and interpretation

### 4.1 Bias trong administrative outcomes là lớn và bền

Participant khác population khá xa. Population mean về monthly earnings trước lockdown là khoảng 3.095 USD, còn participant mean tăng dần từ khoảng 3.667 USD ở arm không incentive lên khoảng 4.030 USD ở arm high incentive. Với employment trước lockdown, population mean là 0,567 còn participant means nằm quanh 0,629 đến 0,675. Nói ngắn gọn: người chịu trả lời survey có vị thế lao động tốt hơn dân số mục tiêu một cách đáng kể.

Quan trọng hơn, reweighting theo observables không giải quyết được tận gốc. Ở nhiều outcome, individually reweighted participant means vẫn lệch đáng kể khỏi ground truth; thậm chí ở một số biến về thay đổi sau lockdown, reweighting còn làm relative bias tệ hơn. Đây là bằng chứng rất khó chịu cho thói quen “đã control/reweight rồi thì chắc ổn”.

### 4.2 Survey responses cũng bị bias trực tiếp

Khi nhìn vào chính survey responses, pattern rất rõ: high-incentive respondents báo cáo bị ảnh hưởng nặng hơn low/no-incentive respondents. Ví dụ, tỷ lệ báo đã apply unemployment insurance là khoảng 7,5% ở no-incentive arm nhưng khoảng 10,4% ở high-incentive arm. Tương tự, high-incentive respondents có xác suất cao hơn trong việc trở thành furloughed/unemployed, không còn làm full-time, và giảm giờ làm. Với tất cả các outcome survey chính, tác giả bác bỏ joint equality giữa các incentive groups.

Diễn giải kinh tế ở đây rất quan trọng: nếu policymaker dùng một sample giống arm không incentive, họ sẽ đánh giá mức độ distress thấp hơn đáng kể so với khi dùng sample giống arm incentive cao. Bias không phải là chuyện “hơi sai một chút”, mà có thể kéo theo kết luận chính sách khác hẳn.

### 4.3 Marginal respondents khác inframarginal respondents rất mạnh

IV decomposition cho thấy marginal participants do incentive kéo vào khác rõ với inframarginal participants. Chẳng hạn, marginal participants có earnings trước lockdown cao hơn nhiều, xác suất earnings loss trên 20% lớn hơn, xác suất employment loss lớn hơn, và trong survey họ báo reduction in work hours hay becoming furloughed/unemployed cao hơn nhiều. Nhưng các observable background characteristics cơ bản như tuổi, giới, immigrant status, years of schooling lại không khác đáng kể.

Đây là chỗ paper đánh rất trúng applied intuition: vấn đề không chỉ là “sample khác population”, mà còn là “chính intervention nhằm tăng response đang chọn thêm một kiểu người rất khác về outcome nhưng không lộ ra ở observables”.

### 4.4 Các correction chuẩn thường không cứu được

Worst-case bounds quá rộng nên ít hữu ích khi response rate chỉ ở mức trung bình. Thêm monotone restrictions có thu hẹp bounds, nhưng nhiều bounds vẫn không chứa nổi population mean thật. Selection model một chiều kiểu latent willingness to respond nghe hợp lý hơn, nhưng khi áp vào dữ liệu này thì point estimates hoặc bounds vẫn lệch đáng kể.

Thông điệp không phải là các phương pháp đó “sai trong mọi trường hợp”, mà là trong một setting có active và passive nonresponse cùng tồn tại, các assumptions tưởng nhẹ có thể sai theo cách rất có hệ thống.

### 4.5 Mô hình hai chiều cải thiện đáng kể

Khi cho phép participation phụ thuộc cả vào sensitivity với incentive lẫn thời điểm thực sự nhìn thấy email/reminder, estimates tiến gần ground truth hơn hẳn. Dưới các assumptions bổ sung hợp lý, bounds từ mô hình hai chiều chứa true value cho 5/6 administrative outcomes, trong khi bản một chiều không làm được chuyện đó. Khi thêm covariates vào specification tốt nhất, paper thu được point estimates cho 5/6 outcomes và bounds hẹp cho outcome còn lại; nhìn chung các estimates này gần ground truth hơn reweighting ở gần như mọi outcome.

Kết quả này không chứng minh rằng mô hình hai chiều là “giải pháp phổ quát”, nhưng nó chứng minh rất thuyết phục rằng chẩn đoán đúng cơ chế participation quan trọng hơn việc cố vặn thêm assumptions vào một mô hình participation sai dạng.

## 5. What is special or elegant about the paper

Điểm hay nhất của paper là nó biến một thao tác vận hành survey rất đời thường, tức randomize incentive và theo dõi reminder timing, thành variation mang giá trị khoa học thật sự. Không cần một policy shock hoành tráng, paper khai thác chính hạ tầng thu thập dữ liệu như một experimental design.

Điểm đẹp thứ hai là cách paper dùng ground truth. Rất nhiều bài về missing data hoặc selection nghe có vẻ hợp lý, nhưng hiếm khi có benchmark để biết method nào thực sự hoạt động. Ở đây tác giả có admin data cho toàn population nên họ có thể “chấm bài” từng correction method.

Điểm đẹp thứ ba là sự khiêm tốn trí tuệ của bài. Họ không cố tuyên bố một estimator thần kỳ. Thay vào đó, họ cho thấy khi assumptions quá yếu thì bounds sẽ rộng; khi assumptions sai dạng thì estimator có thể lệch; còn khi structure phù hợp hơn với mechanism thật thì estimates cải thiện. Đó là một bài học nghiên cứu rất đáng giá.

## 6. Required background knowledge

### 6.1 Nonresponse bias

Đây là chênh lệch giữa mean outcome trong sample trả lời survey và mean outcome của population mục tiêu, do participation không ngẫu nhiên. Nếu người thất nghiệp có xác suất trả lời khác người đang có việc, thì cả mô tả thống kê lẫn estimated treatment effects từ survey đều có thể méo.

### 6.2 Selection on observables và selection on unobservables

`Selection on observables` nghĩa là sau khi conditioning trên các biến quan sát được như tuổi, giới, học vấn, participation có thể xem như ngẫu nhiên. Khi giả định này đúng, reweighting hay inverse probability weighting có thể sửa bias. `Selection on unobservables` nghĩa là ngay cả sau khi control các biến quan sát được, participation vẫn còn liên quan tới outcome tiềm ẩn. Đây là lúc các correction chuẩn thường hụt hơi.

### 6.3 IV và compliers

Tư duy marginal/inframarginal trong paper vay mượn trực giác từ instrumental variables. Incentive đóng vai trò instrument cho participation. Những người chỉ tham gia khi incentive cao hơn tương tự như `compliers`. So sánh họ với `always-takers` giúp soi composition change khi tăng response rate.

### 6.4 Partial identification và bounds

Khi không muốn áp một mô hình parametric quá mạnh, ta có thể chấp nhận rằng tham số cần tìm chỉ được xác định trong một khoảng. Paper cho thấy bounds là cách trung thực để phản ánh thiếu thông tin, nhưng nếu response rate thấp hoặc assumptions quá yếu thì khoảng này có thể rộng tới mức ít hữu ích.

### 6.5 Monotone selection model và marginal response function

Mô hình một chiều của paper dựa trên ý tưởng mỗi cá nhân có một latent resistance to respond. Marginal survey response function mô tả outcome kỳ vọng của người nằm ở từng quantile của latent resistance đó. Muốn suy từ responders sang nonresponders tức là phải extrapolate dọc theo hàm này. Nếu participation thực chất có nhiều chiều, extrapolation một chiều sẽ dễ sai dạng.

### 6.6 Active versus passive nonresponse

Đây là insight kinh tế học hành vi vận hành survey nhưng được formalize rất đẹp. Có người thấy survey nhưng từ chối; có người không thấy hoặc chỉ thấy sau reminder. Hai loại này có thể khác nhau về outcome theo hai hướng đối nghịch. Nếu không tách chúng ra, nhà nghiên cứu dễ dùng sai structure correction.

## 7. Limitations and open questions

Hạn chế đầu tiên là tính ngoại suy. Survey diễn ra trong một thời điểm rất đặc biệt: cú sốc COVID đầu tiên ở Na Uy. Thành phần marginal respondents khi đó có thể khác xa survey thường kỳ, survey ở nước thu nhập thấp, hay survey trong field experiments phát triển.

Hạn chế thứ hai là exclusion restriction của incentive. Paper có lập luận hợp lý rằng incentive làm đổi participation chứ không trực tiếp đổi câu trả lời, nhưng trong vài setting khác, incentive có thể khiến người tham gia trả lời vội hơn, kỹ hơn, hoặc “chiều lòng” survey hơn.

Hạn chế thứ ba là mô hình hai chiều vẫn cần shape restrictions như monotonicity, separability, hay cấu trúc đủ mượt ở chiều incentive resistance. Kết quả tốt trên dữ liệu này không có nghĩa các restrictions đó sẽ đúng rộng rãi.

Hạn chế thứ tư là survey contact infrastructure của Na Uy rất tốt: registry gần như đầy đủ, thông tin liên lạc cập nhật, và admin linkage giàu. Nhiều bối cảnh development không có luxury đó. Chính vì vậy, tính khả thi của full framework sẽ khác nhau đáng kể giữa các nước.

Các câu hỏi mở hấp dẫn:

- Có thể thiết kế incentives và reminders tối ưu để vừa tăng response vừa giảm bias không, thay vì chỉ randomize để chẩn đoán?
- Khi không có admin ground truth, liệu có thể dùng external benchmarks hoặc multi-mode contact data để học về active/passive nonresponse gần giống bài này không?
- Với treatment-effect estimation thay vì population means, random incentives có giúp correction attrition bias trong RCT endline surveys không?

## 8. Takeaways for a researcher

1. Response rate không phải thước đo đủ của data quality. Ai trả lời quan trọng hơn bao nhiêu người trả lời.
2. Nếu survey đã dùng incentive, hãy cân nhắc randomize incentive thay vì cố định một mức cho tất cả. Chi phí bổ sung có thể rất thấp nhưng giá trị chẩn đoán rất lớn.
3. Reweighting trên observables không nên được xem là nghi thức bắt buộc xong là yên tâm. Nó có thể giúp, không giúp, hoặc thậm chí làm bias tệ hơn ở vài estimand.
4. Hãy coi survey operations như một phần của research design. Timing của reminder, mode of contact, hay variation trong reachability đều có thể chứa thông tin nhận dạng.
5. Khi correction method cho câu trả lời rất gọn, hãy hỏi “gọn vì dữ liệu nói vậy” hay “gọn vì mô hình ép dữ liệu nói vậy”.
6. Với survey-based applied work, nên báo cáo sensitivity theo incentive arm, contact wave, hoặc response timing nếu có thể, thay vì chỉ nộp một pooled estimate.

## 9. Vietnam relevance and extension

Paper này rất liên quan với Việt Nam, đặc biệt ở ba mảng: labor surveys, enterprise/household follow-up surveys, và endline data collection trong impact evaluations. Ở Việt Nam, khác biệt về khả năng liên lạc, thói quen phản hồi điện thoại, mức độ tin cậy với survey, và mức độ bận rộn theo nghề nghiệp có thể khiến active và passive nonresponse còn trầm trọng hơn Na Uy.

### 9.1 Liệu có triển khai được ở Việt Nam không?

Có, nhưng mức độ đầy đủ sẽ phụ thuộc dữ liệu nền. Phiên bản nhẹ của ý tưởng rất khả thi:

- randomize incentive hoặc top-up phone credit cho phone survey
- randomize reminder schedule hoặc message framing
- so sánh outcome means giữa response arms như một diagnostic

Phiên bản mạnh như paper, tức nối survey với administrative microdata cho cả responders lẫn nonresponders, khó hơn nhiều nhưng không phải bất khả thi nếu có đối tác nhà nước, doanh nghiệp nền tảng, hoặc dữ liệu chương trình hành chính.

### 9.2 Điều kiện cần có

- sampling frame đủ rõ và có contact information tương đối tốt
- khả năng randomize incentive và lưu lại log contact/reminder sạch
- dữ liệu nền trước can thiệp hoặc benchmark hành chính để kiểm tra selection
- quy trình quản trị dữ liệu đủ chặt để link survey với admin hoặc roster có sẵn

### 9.3 Trở ngại chính ở Việt Nam

- contact information thiếu ổn định, đặc biệt với lao động phi chính thức và di cư
- nhiều survey dựa vào enumerator adaptation tại hiện trường nên protocol thực thi không đồng nhất
- administrative linkage khó vì quyền truy cập dữ liệu hạn chế
- incentive có thể ảnh hưởng không chỉ participation mà cả mức độ cẩn trọng khi trả lời, nhất là trong phone surveys ngắn

### 9.4 Hướng mở rộng phù hợp hơn với Việt Nam

Một hướng rất hứa hẹn là kết hợp random incentives với paradata từ CATI hoặc smartphone surveys: số lần gọi, thời điểm bắt máy, thời lượng, ai là người nghe máy đầu tiên, có phải callback hay không. Những dữ liệu vận hành này có thể đóng vai trò gần giống reminder timing trong paper.

Một hướng khác là đặt bài toán trong evaluation settings. Ở Việt Nam, nhiều RCT hoặc quasi-experiments có endline survey bị attrition. Randomizing airtime incentives, reminder intensity, hoặc survey mode ở endline có thể tạo ra variation để chẩn đoán attrition bias tốt hơn nhiều so với chỉ báo cáo attrition rates.

### 9.5 Một số research questions mới cho bối cảnh Việt Nam

1. Trong phone surveys về lao động phi chính thức sau cú sốc thu nhập, random top-up điện thoại có làm tăng response rate nhưng đồng thời thay đổi composition người trả lời theo hướng nào?
2. Trong các chương trình social assistance hoặc training, timing và framing của reminder có giúp tách active khỏi passive nonresponse để sửa attrition bias ở endline hay không?
3. Với doanh nghiệp siêu nhỏ và hộ kinh doanh, liệu multi-mode follow-up gồm phone, Zalo, và in-person callback có thể được dùng như một participation model nhiều chiều để ước lượng outcomes đáng tin hơn không?

## 10. Vì sao bài này đáng đọc lúc này

Đây là một paper rất “applied micro core”: câu hỏi nghe có vẻ hạ tầng, nhưng thực ra đụng vào nền móng của measurement, external validity, và policy inference. Nó nhắc rằng trước khi hỏi estimator nào tốt hơn, ta phải hỏi dữ liệu mình quan sát thực chất đang đến từ cơ chế chọn mẫu nào. Với thời đại economics ngày càng lệ thuộc vào online surveys, phone surveys, administrative augmentation, và rapid-response data, bài này có giá trị vượt xa đúng bối cảnh COVID ở Na Uy.

## 11. Ghi chú thực thi và giới hạn của lượt chạy này

- Paper được chọn vì đây là bài **top 5 journal** rất mới trong ReStud 2026, nằm chắc trong applied micro/econometrics ứng dụng cho survey data, có public PDF gần bản xuất bản, và chưa xuất hiện trong danh sách paper gần đây của agent.
- Bản PDF công khai tốt nhất mà agent xác minh được là **NBER Working Paper 29549, Revised July 2025**. Đây không phải PDF chính thức của ReStud, nhưng là working paper công khai gần bản xuất bản nhất mà agent truy cập được ổn định qua web trong lượt chạy này.
- Môi trường hiện tại cho phép agent **đọc và xác minh nội dung PDF qua web**, nhưng việc tải raw binary PDF từ nguồn ngoài về shell tiếp tục bị chặn `403`. Vì vậy, trừ khi có thay đổi ở bước sau, trạng thái trung thực mặc định là **đã xác minh nguồn PDF công khai nhưng chưa lưu được file PDF gốc vào GitHub**.
- Google Drive chưa được dùng trong bản cục bộ này; nếu bỏ qua ở cuối lượt chạy thì điều đó sẽ được ghi rõ thay vì mô tả mập mờ như thể đã lưu thành công.
