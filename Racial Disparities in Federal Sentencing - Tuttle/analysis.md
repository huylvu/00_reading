# Racial Disparities in Federal Sentencing: Evidence from Drug Mandatory Minimums

- **Tác giả:** Cody Tuttle
- **Journal:** The Review of Economic Studies
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-08
- **Nguồn bài báo chính:** https://academic.oup.com/restud/advance-article-abstract/doi/10.1093/restud/rdag037/8667658
- **Nguồn PDF dùng để phân tích:** https://codytuttle.github.io/tuttle_mandatory_minimums.pdf
- **Ghi chú về PDF:** Bản ghi đọc sâu trong lượt này là public author manuscript tháng 10/2025 trên trang tác giả. Trang ReStud xác minh bài đã được xuất bản online ngày 05/05/2026 dưới DOI `10.1093/restud/rdag037`, nhưng môi trường shell của lượt chạy này không tải được raw binary PDF từ nguồn ngoài do lỗi `403`, nên chưa thể coi việc lưu PDF gốc lên GitHub là hoàn tất.
- **Trạng thái lưu trên GitHub:** `analysis.md` và `analysis.html` đã lưu; `analysis.pdf` chưa lưu; PDF gốc của paper chưa lưu.
- **Trạng thái lưu trên Google Drive:** Bỏ qua trong lượt này vì chưa có tuyến tạo Google Doc và tracker trong đúng folder đích với mức độ chắc chắn đủ cao.

## 1. Metadata

- **Tiêu đề paper:** Racial Disparities in Federal Sentencing: Evidence from Drug Mandatory Minimums
- **Tác giả:** Cody Tuttle
- **Journal:** The Review of Economic Studies
- **Năm:** 2026
- **DOI:** `10.1093/restud/rdag037`
- **Link bài báo:** https://academic.oup.com/restud/advance-article-abstract/doi/10.1093/restud/rdag037/8667658
- **Link PDF đã dùng để phân tích:** https://codytuttle.github.io/tuttle_mandatory_minimums.pdf
- **Phiên bản PDF:** Author manuscript, tháng 10/2025
- **Lĩnh vực:** Applied micro, economics of crime, discrimination, law and economics
- **Top 5 status:** Có. ReStud là top 5 journal economics.

## 2. Executive Summary

Paper hỏi một câu rất sắc: khi luật nâng ngưỡng crack-cocaine để kích hoạt mandatory minimum 10 năm từ 50g lên 280g theo Fair Sentencing Act năm 2010, liệu các tác nhân trong hệ thống tư pháp có điều chỉnh hành vi để tiếp tục đẩy bị cáo qua ngưỡng án nặng hay không, và nếu có thì điều đó có khác nhau theo chủng tộc không.

Tuttle trả lời bằng cách nhìn vào hiện tượng “bunching” đúng tại ngưỡng 280g sau cải cách. Ý tưởng cốt lõi là nếu lượng ma túy dùng trong sentencing chỉ phản ánh hành vi phạm tội thực, phân phối lượng ma túy quanh ngưỡng mới không nên đột ngột phình ra đúng 280g. Nhưng nếu prosecutor hay các tác nhân khác chiến lược “xây” hồ sơ để đẩy vụ án lên ngưỡng mandatory minimum, ta sẽ thấy quá nhiều vụ nằm đúng vùng 280-290g sau 2010. Tác giả kết hợp dữ liệu sentencing của USSC với dữ liệu case management của EOUSA, dữ liệu seizure, survey về drug use/selling, hồ sơ bang Florida, và một measure state-level racial animus từ Google Trends.

Kết quả chính là sau 2010, tỷ lệ vụ crack-cocaine nằm ở 280-290g tăng vọt, và mức tăng này lớn hơn rõ rệt với bị cáo Black và Hispanic so với White. Tác giả lần lượt loại trừ giải thích do khác biệt thật trong drug involvement, do offender response, do police/federal agents, rồi dồn trọng tâm về prosecutorial discretion. Bằng chứng từ EOUSA cho thấy bunching xuất hiện ngay trong case files của prosecutor, và khoảng 20-30% prosecutor dường như là nguồn chính của hiện tượng này. Hơn nữa, bunching giảm sau phán quyết *Alleyne v. United States* năm 2013, khi tiêu chuẩn chứng cứ cho tình tiết làm tăng mandatory minimum trở nên chặt hơn. Racial disparity còn lại cũng tương quan mạnh với measure racial animus ở cấp bang.

Đây là bài rất đáng đọc vì nó biến một câu hỏi vốn thường bị mắc kẹt trong “unobservables” thành một design cực trực quan: thay vì cố đo bias trực tiếp, tác giả tận dụng một thay đổi ngưỡng pháp lý để phát hiện hành vi chiến lược, rồi truy vết ai là người tạo ra nó. Paper vừa có design gọn, vừa có logic institutionally informed, lại vừa cho thấy cách đi từ một reduced-form pattern đến một lập luận rất cụ thể về cơ chế.

## 3. Research Question and Motivation

### Câu hỏi nghiên cứu trung tâm

Paper hỏi ba lớp câu hỏi lồng vào nhau:

1. Sau khi Fair Sentencing Act nâng ngưỡng mandatory minimum 10 năm cho crack-cocaine từ 50g lên 280g, có xuất hiện excess mass đúng quanh ngưỡng mới hay không.
2. Nếu có, excess mass đó có lớn hơn cho bị cáo Black và Hispanic so với White hay không.
3. Ai trong chuỗi thực thi pháp luật tạo ra hiện tượng này, và liệu racial disparity quan sát được có phù hợp hơn với prosecutorial discretion và discrimination hay với những giải thích lành tính hơn.

### Bối cảnh học thuật và thực tiễn

Racial disparities trong sentencing là một chủ đề cũ nhưng khó. Phần lớn tranh luận luôn mắc ở chỗ: khác biệt observed outcomes có thể phản ánh khác biệt thật trong offense severity, criminal history, plea bargaining, quality of defense, prosecutorial strategy, judge behavior, hay outright discrimination. Trong môi trường như criminal justice, rất nhiều biến cốt lõi không quan sát được sạch. Vì vậy, ngay cả khi ta thấy Black defendants nhận án nặng hơn White defendants, vẫn khó chỉ ra chính xác “nút” nào của hệ thống tạo ra chênh lệch đó.

Paper này đặt câu hỏi theo cách hẹp hơn nhưng mạnh hơn. Mandatory minimum tạo ra các ngưỡng pháp lý rời rạc. Nếu người thực thi có discretion trong cách xác định drug quantity phục vụ sentencing, họ có động cơ tập trung vụ án đúng tại ngưỡng. Khi ngưỡng được dời từ 50g lên 280g, phản ứng chiến lược lộ ra rất rõ hơn là trong trạng thái tĩnh. Nói cách khác, policy change tạo ra một phép thử gần như tự nhiên cho discretion.

### Khoảng trống mà bài muốn lấp

Văn liệu trước đã chỉ ra racial disparities trong sentencing và vai trò của prosecutor, nhưng ít paper truy vết được một cơ chế rất cụ thể: strategic manipulation quanh mandatory minimum thresholds. Điểm còn thiếu là một setting trong đó threshold mới tạo ra “dấu vết” quan sát được, cho phép phân biệt giữa:

- khác biệt thật trong hành vi phạm tội,
- phản ứng của offender hay police,
- và phản ứng của prosecutor.

Paper lấp chỗ trống đó bằng một thiết kế thực nghiệm dựa trên threshold shift và bunching.

## 4. Main Contribution

### Đóng góp thực chất

Đóng góp lớn nhất của paper là biến prosecutorial discretion từ một khái niệm rộng, khó đo, thành một object có thể quan sát thông qua distributional response quanh threshold. Tác giả không chỉ nói “prosecutor quan trọng”; paper cho thấy chính xác một dạng hành vi chiến lược: đẩy case vào vùng vừa đủ để kích hoạt mandatory minimum.

### Đóng góp về thiết kế thực nghiệm

Paper áp dụng logic difference-in-bunching vào law and economics theo cách rất đẹp. Threshold mới 280g đặc biệt hữu ích vì trước 2010 đó là vùng hầu như không có bunching tự nhiên, nên khi thấy spike xuất hiện sau cải cách thì diễn giải dễ thuyết phục hơn nhiều so với những threshold vốn đã là focal point từ trước. Đây là một ví dụ rất hay về việc policy design tạo ra identification leverage.

### Đóng góp về dữ liệu

Paper không dừng ở dữ liệu sentencing. Tác giả còn kéo thêm:

- EOUSA case management data để nhìn giai đoạn prosecutor xử lý vụ án,
- seizure records và survey data để loại trừ offender/police responses,
- dữ liệu bang Florida để kiểm tra shifting từ state sang federal court,
- Google Trends racial animus measure để xem spatial heterogeneity của disparity.

Chính việc kết nối nhiều tầng dữ liệu giúp paper không chỉ phát hiện pattern mà còn đi khá xa trong việc quy trách nhiệm cơ chế.

### Vì sao quan trọng trong applied micro

Trong applied micro, nhiều paper tốt không nằm ở việc ước lượng một hiệu ứng lớn, mà ở chỗ chỉ ra một margin của behavior previously hidden. Paper này rất mạnh ở điểm đó. Nó dạy ta rằng institutional rules rời rạc, khi thay đổi đúng cách, có thể làm lộ ra behavior của bureaucrats và legal agents. Đây là bài học vượt xa bối cảnh criminal justice.

## 5. Identification or Methodology

### Trực giác thiết kế

Fair Sentencing Act 2010 tăng ngưỡng crack-cocaine để nhận mandatory minimum 10 năm từ 50g lên 280g. Nếu phân phối charged amount không bị can thiệp chiến lược, ta không kỳ vọng một spike bất thường đúng 280-290g sau 2010. Nếu spike xuất hiện, đó là dấu hiệu các case bị “định vị” đúng trên ngưỡng.

Tác giả định nghĩa “bunched” là case có charged amount trong khoảng 280-290g. Sau đó so sánh xác suất một case rơi vào vùng này trước và sau cải cách. Đây là dạng linear probability model rất đơn giản nhưng intuition cực rõ:

- `After2010` đo xem post-reform có nhiều case rơi vào 280-290g hơn không.
- Tương tác `After2010 × race` đo xem mức tăng đó khác nhau theo race hay không.

### Difference-in-bunching

Cốt lõi của identification là dùng pre-2010 distribution làm empirical counterfactual cho post-2010 distribution trong trường hợp không có strategic response tại threshold mới. Theo logic của Kleven-style bunching, mass tăng ở 280-290g phải đi kèm missing mass ở các bins khác, và pattern missing mass cho biết case bị kéo từ đâu tới.

Điểm rất hay là threshold 280g trước 2010 gần như không có ý nghĩa pháp lý lớn, nên pre-period quanh điểm này là counterfactual khá tự nhiên. Đây là lý do design này gọn hơn nhiều so với những nghiên cứu phải tranh luận gay gắt về baseline distribution.

### Kiểm tra “conditional racial disparity”

Một câu hỏi then chốt là: có thể Black/Hispanic defendants thật ra vốn có drug involvement cao hơn, nên post-2010 chỉ đơn giản là họ gần 280g hơn không. Tác giả xử lý bằng hai bước:

1. Kiểm tra xem pre-2010 distribution từ 60-280g có khác nhau theo race không.
   - Kết quả là hầu như không khác; Kolmogorov-Smirnov test cho p-value `0.792`.
2. Kiểm tra theo từng 10g bin liệu post-2010 Black/Hispanic cases có “dịch chuyển ra khỏi” các bin 60-280g nhiều hơn White cases không.

Logic của hai bài test này rất quan trọng. Paper không nói tuyệt đối rằng pre-2010 charged amount là “true drug involvement”, mà nói rằng dưới các giả định hợp lý, nếu pre-2010 distributions ngang nhau thì racial disparity tại 280g khó có thể chỉ do underlying involvement.

### Truy cơ chế theo stage

Paper loại trừ ba kênh trước prosecutor:

1. **Offender response:** người phạm tội Black/Hispanic có thay đổi hành vi theo luật mới không.
2. **Selection into federal court:** state/local authorities có đẩy các vụ nặng hơn lên federal court sau 2010 không.
3. **Law enforcement response:** police/federal agents có bắt đầu tạo drug amount gần 280g nhiều hơn không.

Sau đó tác giả dùng EOUSA case management data để xem bunching có xuất hiện ngay trong hồ sơ prosecutor hay không. Nếu có, và nếu seizure records không cho thấy bunching ở giai đoạn trước, thì prosecutor là mắt xích hợp lý nhất.

### Heterogeneity across prosecutors

Một điểm methodological rất đẹp là tác giả không dừng ở average effect. Paper ước lượng propensity bunching theo từng prosecutor, rồi dùng nhiều cách để đánh giá xem đó chỉ là noise hay phản ánh real heterogeneity:

- phân loại prosecutor “bunching” theo share cases ở 280-290g,
- outlier detection theo Ridgeway and MacDonald / Hoekstra and Sloan,
- Bayesian shrinkage theo Goncalves and Mello.

Các cách này đều cho con số na ná nhau: khoảng 22-30% prosecutors là nguồn chính của bunching.

### Difference-in-discontinuities quanh Alleyne

Paper còn tận dụng phán quyết *Alleyne v. United States* tháng 6/2013, vốn nâng chuẩn chứng cứ cho facts làm tăng mandatory minimum. Nếu bunching thực sự là sản phẩm của prosecutorial maneuvering dựa trên facts chưa đủ cứng, thì Alleyne phải làm bunching giảm. Đây là một test cơ chế rất mạnh. Kết quả đúng như dự đoán: fraction cases ở 280-290g giảm rời rạc sau phán quyết.

### Điểm mạnh của phương pháp

- Design cực trực quan, dễ giải thích nhưng vẫn sắc.
- Có counterfactual pre-period hợp lý nhờ threshold change.
- Không lệ thuộc vào một dataset duy nhất.
- Có nhiều falsification và mechanism checks.
- Nối được reduced form với institutional mechanism.

### Điểm dễ bị nghi ngờ

- Pre-2010 distribution vẫn là counterfactual dựa trên giả định, không phải randomized benchmark.
- Charged quantity không phải true quantity, nên mọi suy luận về “conditional disparity” vẫn cần cẩn trọng.
- Prosecutor assignment không random, nên phần heterogeneity across prosecutors không thể diễn giải hoàn toàn như causal effect của “loại prosecutor”.
- State-level racial animus measure là suggestive evidence, không phải smoking gun.

## 6. Results and Interpretation

### Kết quả chính 1: bunching mạnh ở 280g sau 2010

Sau khi ngưỡng mới được áp dụng, tỷ lệ crack-cocaine cases nằm trong vùng 280-290g tăng rõ rệt. Đây là bằng chứng trực tiếp nhất rằng threshold mới tạo ra strategic response. Quan trọng hơn, mass ở 280g không đi cùng với sự tăng tương xứng ở vùng trên 290g, điều này phù hợp hơn với “đẩy case đúng vừa đủ qua ngưỡng” hơn là “toàn bộ distribution dịch lên”.

Diễn giải kinh tế ở đây là các tác nhân trong hệ thống không chỉ phản ứng với mức hình phạt kỳ vọng, mà phản ứng chính xác với discontinuity của rule. Đây là kiểu behavioral response rất quen trong public finance, nhưng xuất hiện ở đây trong bối cảnh criminal procedure.

### Kết quả chính 2: racial disparity trong bunching

Mức tăng bunching sau 2010 lớn hơn hẳn với bị cáo Black và Hispanic. Paper nhấn mạnh đây không chỉ là disparity trong outcomes cuối cùng, mà là disparity ngay tại điểm mà discretion có giá trị lớn nhất: quyết định liệu một case có vượt qua threshold mandatory minimum hay không.

Nói cách khác, nếu threshold là một “lever” để đẩy sentence lên, thì lever này được dùng thường xuyên hơn với minority defendants.

### Kết quả chính 3: disparity không dễ giải thích bằng underlying drug involvement

Pre-2010 distribution từ 60-280g gần như giống nhau giữa White và Black/Hispanic defendants, với KS p-value `0.792`. Ngoài ra, seizure records và inmate surveys không gợi ý minority defendants tăng seized quantity, drug use, hay drug selling sau 2010 theo cách đủ để giải thích bunching. Điều này không chứng minh tuyệt đối không có khác biệt unobserved, nhưng làm cho câu chuyện “họ vốn gần 280g hơn” yếu đi đáng kể.

### Kết quả chính 4: prosecutor là mắt xích trung tâm

EOUSA data cho thấy bunching xuất hiện ngay trong case files. Tỷ lệ cases ở 280-290g trong EOUSA tăng khoảng `7.8` điểm phần trăm sau 2010 nếu chỉ nhìn non-missing values; khi xử lý missing conservatively thì cỡ tăng còn khoảng `2.4` điểm phần trăm, khá khớp với sentencing data.

Ở cấp prosecutor, paper ước lượng rằng:

- khoảng `29.7%` prosecutors có bunching cao hơn mức “bình thường” theo định nghĩa đơn giản,
- khoảng `22-27%` bị gắn cờ bởi outlier methods,
- khoảng `30%` theo Bayesian shrinkage.

Kết quả này rất quan trọng. Nó nói rằng hiện tượng không phải do “toàn hệ thống hơi nghiêng một chút”, mà có vẻ tập trung ở một nhóm prosecutors nhất định.

### Kết quả chính 5: Alleyne làm bunching giảm

Sau phán quyết *Alleyne* ngày 17/06/2013, fraction cases 280-290g giảm rời rạc. Đây là một piece of evidence rất thuyết phục cho cơ chế: khi việc dùng facts để nâng exposure lên mandatory minimum phải đáp ứng standard chứng cứ chặt hơn, strategic bunching bị kiềm lại.

Điều này đặc biệt đẹp vì nó không chỉ nói prosecutor discretion tồn tại, mà còn cho thấy discretion đó nhạy với institutional constraints về evidence.

### Kết quả chính 6: disparity liên quan đến racial animus

Paper xem xét nhiều giải thích thay thế như observable characteristics, quality of defense, chi phí phát triển case, statistical discrimination, và taste-based discrimination. Tác giả không tuyên bố đã “chứng minh” taste-based discrimination hoàn toàn, nhưng cho thấy racial disparity phần lớn có thể được giải thích bởi state-level racial animus measure từ Google searches. Đây là bằng chứng mang tính suggestive nhưng mạnh về hướng diễn giải.

### Kết quả cuối cùng về sentencing

Một điểm rất hay là Fair Sentencing Act trên ròng vẫn làm sentence giảm, nhưng strategic response của prosecutors làm giảm bớt hiệu quả của cải cách. Vì minority defendants bị bunching nhiều hơn, sentence của họ giảm ít hơn so với White defendants trong nhóm có nguy cơ chạm mandatory minimum 10 năm. Nói cách khác, reform giúp, nhưng discretion làm nó giúp ít hơn cho đúng nhóm lẽ ra cần được hưởng nhiều hơn.

## 7. What Is Special or Elegant About the Paper

Điểm đẹp nhất của paper là dùng một thay đổi pháp lý rất cụ thể để “soi” vào một hành vi vốn thường vô hình. Không phải paper nào về discrimination cũng có được một empirical object sạch như spike ở 280g. Ở đây threshold mới giống như bật đèn trong một căn phòng tối: thay vì tranh luận trừu tượng về bias, tác giả cho ta thấy dấu chân của strategic behavior ngay trong distribution.

Điểm đẹp thứ hai là cấu trúc lập luận rất micro-applied:

1. Phát hiện một pattern reduced-form mạnh.
2. Kiểm tra liệu pattern đó có thể do underlying composition không.
3. Loại trừ các stage khác trong production process.
4. Dùng dữ liệu nội bộ hơn để truy về actor có khả năng tạo ra pattern.
5. Tận dụng thêm một legal shock khác để kiểm tra cơ chế.

Đây là một template nghiên cứu rất đáng học. Nhiều paper có kết quả hay nhưng thiếu “logic of narrowing down”. Paper này ngược lại: nó khiến người đọc thấy từng cánh cửa giải thích lần lượt bị đóng lại.

Điểm đẹp thứ ba là sự kết hợp giữa institutional detail và econometric design. Nếu không hiểu federal drug sentencing, prosecutor discretion, hay cách drug quantity được xác định trong hồ sơ, tác giả sẽ không nghĩ ra design này. Bài học là nhiều identification tốt không đến từ kỹ thuật mới, mà từ hiểu thể chế đủ sâu để nhìn ra một margin có thể đo được.

## 8. Required Background Knowledge

### Mandatory minimum sentencing là gì

Mandatory minimum là mức án tối thiểu mà luật buộc tòa phải áp dụng nếu vụ án thỏa một số điều kiện, ở đây là drug quantity vượt ngưỡng. Khi có mandatory minimum, việc dịch case từ ngay dưới lên ngay trên ngưỡng có thể làm sentence tăng nhảy cóc.

### Bunching là gì

Bunching là hiện tượng phân phối của một biến có mass bất thường quanh một ngưỡng do tác nhân tối ưu hóa theo rule. Trong thuế, ta hay thấy taxable income bunch ở kink hay notch. Paper này mang logic đó sang criminal justice: charged drug amount bunch ở legal threshold.

### Difference-in-bunching

Khác với bunching thuần túy trong một cross-section, difference-in-bunching so sánh trước và sau khi rule thay đổi. Điều đó giúp counterfactual tốt hơn: mình không chỉ thấy có spike, mà thấy spike xuất hiện đúng sau khi threshold dời chỗ.

### Conditional racial disparity

Khái niệm này quan trọng hơn disparity thô. Nếu hai nhóm có underlying offense severity khác nhau, chênh lệch outcomes chưa chắc là discriminatory treatment. “Conditional disparity” cố hỏi: với mức độ involvement tương tự, minority defendants có bị đối xử khác không.

### Prosecutorial discretion

Prosecutor không chỉ quyết định có truy tố hay không; họ còn ảnh hưởng đến charges, plea bargaining, cách mô tả conduct, và trong setting này là lượng ma túy được ghi nhận phục vụ sentencing. Trong rất nhiều hệ thống pháp luật, discretion kiểu này lớn hơn nhiều so với người ngoài ngành thường nghĩ.

### Outcome tests và giới hạn của chúng

Paper có nhắc đến điểm Canay, Mogstad, Mountjoy: chỉ nhìn chênh lệch outcome theo race không đủ để kết luận taste-based discrimination, vì còn dính selection và unobservables. Bài này hay ở chỗ không dựa hoàn toàn vào benchmark outcome test, mà cố neo suy luận vào behavior tại threshold và vào các institutional responses.

### Difference-in-discontinuities / RD intuition

Khi paper dùng Alleyne như một cơ chế kiểm định bổ sung, intuition gần với RD theo thời gian kết hợp difference. Nếu policy hay legal standard thay đổi đột ngột tại một date, và outcome quanh date cũng nhảy, ta có bằng chứng về cơ chế liên quan.

## 9. Limitations and Open Questions

### Hạn chế 1: charged quantity không phải true quantity

Toàn bộ logic của paper xoay quanh charged amount dùng trong sentencing, trong khi object này đã là outcome của quá trình bargaining và fact construction. Điều đó là sức mạnh của paper, nhưng cũng là giới hạn: ta khó biết chính xác “true” drug involvement.

### Hạn chế 2: chưa thể tách hoàn toàn statistical discrimination khỏi taste-based discrimination

Measure racial animus rất gợi ý, nhưng vẫn không phải bằng chứng dứt khoát. Một số khác biệt về local institutions, norms, defense quality, hay prosecutorial objectives có thể đồng biến với animus measure.

### Hạn chế 3: prosecutor assignment không ngẫu nhiên

So sánh bunching và non-bunching prosecutors có thể bị nhiễu bởi case assignment. Paper đã cố xử lý phần nào bằng controls, district comparisons, attorney moves, và alternative estimators, nhưng đây vẫn không phải randomized prosecutor design.

### Hạn chế 4: external validity

Setting là federal crack-cocaine cases, một bối cảnh rất đặc thù của US criminal justice. Câu hỏi mở là mức độ tổng quát sang:

- các loại drug khác,
- state courts,
- các threshold pháp lý khác,
- hoặc các legal systems ngoài Mỹ.

### Câu hỏi mở

- Khi threshold thay đổi theo hướng khác, prosecutors có điều chỉnh đối xứng không.
- Những prosecutors bunching nhiều hơn có khác gì về career incentives, training, ideology, hay office culture.
- Những institutional reforms nào thật sự bó được margin này: evidentiary rules, disclosure rules, audit, hay data transparency.

## 10. Takeaways for a Researcher

1. Một thay đổi thể chế nhỏ nhưng sắc có thể tạo ra identification mạnh hơn rất nhiều so với một câu hỏi rộng nhưng dữ liệu mờ.
2. Khi nghiên cứu discrimination, đừng chỉ nhìn mean outcome gaps; hãy tìm các decision margins nơi discretion có giá trị lớn và để lại distributional fingerprints.
3. Paper mạnh thường đi từ pattern sang mechanism bằng nhiều lớp dữ liệu, chứ không trông chờ một regression “ôm hết sự thật”.
4. Hiểu thể chế sâu là một lợi thế phương pháp. Không có hiểu biết chi tiết về federal sentencing rules thì khó mà nhìn ra ngưỡng 280g như một empirical lever.
5. Một reduced-form đẹp chưa đủ; điều làm paper này nổi bật là chuỗi falsification và mechanism checks.
6. Heterogeneity across agents có thể là trung tâm của câu chuyện chính sách. Average treatment trong paper này không đủ; chính việc hiện tượng tập trung ở khoảng 20-30% prosecutors mới tạo ra insight chính.
7. Nếu làm policy paper, hãy hỏi không chỉ “reform có tác động không” mà còn “hệ thống có nội sinh phản ứng để vô hiệu hóa một phần reform không”.

## 11. Vietnam Relevance and Extension

### Ý tưởng này có liên quan tới Việt Nam không

Có, nhưng không phải theo kiểu bê nguyên bài sang làm ngay. Điều đáng học ở đây không phải crack-cocaine hay Fair Sentencing Act, mà là cách dùng các ngưỡng pháp lý hoặc hành chính để phát hiện strategic behavior trong hệ thống thực thi.

Ở Việt Nam, những bối cảnh có thể gợi mở gồm:

- các ngưỡng lượng hóa trong xử lý hình sự hoặc hành chính,
- các cutoff trong eligibility của chương trình an sinh,
- các threshold về đất đai, xây dựng, bảo hiểm xã hội, hay thuế,
- các tiêu chí định lượng làm thay đổi mạnh chế tài hoặc quyền lợi.

Nếu người thực thi có discretion trong cách ghi nhận, đo lường, hoặc phân loại hồ sơ, ta có thể quan sát bunching quanh ngưỡng tương tự.

### Điều kiện cần để triển khai ở Việt Nam

- Dữ liệu vi mô đủ chi tiết quanh ngưỡng.
- Có thay đổi rule hoặc cutoff đủ rõ theo thời gian.
- Có khả năng nối nhiều stage của quy trình hành chính hay tố tụng.
- Hiểu biết thể chế sâu để biết agent nào thực sự có discretion ở khâu nào.

### Trở ngại lớn

- Khó tiếp cận data linked across stages.
- Chất lượng administrative data và chuẩn hóa measurement có thể không ổn định.
- Tính minh bạch của record-keeping và khả năng external validation có thể hạn chế.
- Các yếu tố pháp lý và nhạy cảm chính trị khiến việc nghiên cứu enforcement disparities khó hơn.

### Hướng mở rộng phù hợp với Việt Nam

1. **Threshold manipulation trong thực thi hành chính.**
   - Ví dụ: các ngưỡng diện tích, giá trị tài sản, hay mức doanh thu làm thay đổi chế tài, nghĩa vụ, hoặc eligibility.
   - Câu hỏi: có bunching ngay trên hoặc dưới ngưỡng không, và nó tập trung ở đơn vị thực thi nào.

2. **Discretion trong nhắm trúng đối tượng của chương trình xã hội.**
   - Nếu một chương trình có cutoff thu nhập, nghèo đa chiều, hay điều kiện giấy tờ, có thể xem hồ sơ có bunching quanh ngưỡng không và liệu sự lệch đó khác nhau theo dân tộc, giới, hay địa phương.

3. **Nghiên cứu về local bureaucratic heterogeneity.**
   - Dùng variation across districts/provinces/offices để xem một nhóm nhỏ cán bộ hay đơn vị có tạo ra phần lớn distortion không, tương tự logic 20-30% prosecutors trong paper này.

### 1 đến 3 research questions mới cho bối cảnh Việt Nam

1. Khi tiêu chí định lượng của một chương trình hỗ trợ hộ nghèo được điều chỉnh, hồ sơ được xác nhận có bunching ngay sát ngưỡng mới hay không, và bunching đó có khác nhau theo dân tộc thiểu số so với đa số không?
2. Khi một quy định xử phạt hay cưỡng chế thay đổi ngưỡng giá trị hoặc quy mô vi phạm, liệu các biên bản sau cải cách có bị “đóng đinh” quanh cutoff nhiều hơn không, và variation này tập trung ở một nhóm đơn vị thực thi nào?
3. Trong các thủ tục đất đai hoặc cấp phép, liệu các chỉ tiêu kỹ thuật được ghi nhận có bunching tại các ngưỡng làm thay đổi nghĩa vụ tài chính hoặc khả năng được phê duyệt, và liệu điều đó phản ánh discretion ở cấp cán bộ hay ở cấp văn phòng?

## 12. Vì Sao Paper Này Được Chọn Hôm Nay

Mình chọn paper này vì ba lý do. Thứ nhất, đây là một bài top 5 rất mới: ReStud vừa đăng online ngày 05/05/2026. Thứ hai, paper nằm rất chắc trong applied micro với câu hỏi về discrimination, bureaucratic discretion, và institutional response, đồng thời có design đáng học thật sự chứ không chỉ có topical relevance. Thứ ba, có public author PDF đủ gần bản xuất bản để đọc sâu chắc tay, dù raw binary download trong môi trường shell vẫn bị chặn.

## 13. Storage Notes

- **GitHub folder:** `Racial Disparities in Federal Sentencing - Tuttle/`
- **Đã lưu trên GitHub:** `analysis.md`, `analysis.html`
- **Chưa lưu trên GitHub:** `analysis.pdf`, PDF gốc của paper
- **Lý do chưa lưu PDF gốc:** shell không tải được raw binary PDF từ nguồn ngoài trong lượt này do lỗi `403`; vì vậy mình chỉ xác minh chắc nguồn PDF công khai và dùng nó để đọc qua web/PDF viewer.
- **Drive:** Bỏ qua trong lượt này.
