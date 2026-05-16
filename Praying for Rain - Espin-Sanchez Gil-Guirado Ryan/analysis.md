# Praying for Rain

- **Tác giả:** José-Antonio Espín-Sánchez, Salvador Gil-Guirado, Nicholas Ryan
- **Journal:** The Quarterly Journal of Economics
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-16
- **Nguồn bài báo chính:** https://academic.oup.com/qje/advance-article/doi/10.1093/qje/qjag026/8676046
- **Nguồn PDF dùng để phân tích:** https://academic.oup.com/qje/advance-article-pdf/doi/10.1093/qje/qjag026/68269215/qjag026.pdf
- **Trạng thái lưu trên GitHub tại thời điểm soạn file:** `analysis.md` và `analysis.html` đã được chuẩn bị để lưu lên repo `huylvu/00_reading`; `analysis.pdf` chưa tạo; PDF gốc đã xác minh nguồn nhưng chưa tải và chưa lưu được dưới dạng file nhị phân trong môi trường này
- **Trạng thái lưu trên Google Drive tại thời điểm soạn file:** bỏ qua trong lượt này nếu không tạo được Google Doc và tracker một cách nhất quán

## 1. Metadata

- **Tiêu đề paper:** Praying for Rain
- **Tác giả:** José-Antonio Espín-Sánchez, Salvador Gil-Guirado, Nicholas Ryan
- **Journal:** The Quarterly Journal of Economics
- **Năm:** 2026
- **Link bài báo:** https://academic.oup.com/qje/advance-article/doi/10.1093/qje/qjag026/8676046
- **Link PDF tốt nhất đã xác minh:** https://academic.oup.com/qje/advance-article-pdf/doi/10.1093/qje/qjag026/68269215/qjag026.pdf
- **Ghi chú về file PDF gốc:** đã xác minh được PDF QJE chính thức open access, nhưng môi trường chạy bị chặn tải file nhị phân trực tiếp qua mạng ngoài nên chưa thể lưu raw PDF vào GitHub trong lượt này.

## 2. Executive summary

Paper hỏi một câu rất đẹp và khá táo bạo: nếu cầu mưa thực ra không làm mưa, vì sao niềm tin vào cầu mưa vẫn có thể bền vững trong rất nhiều xã hội? Thay vì xem đây chỉ là chuyện "mê tín", tác giả xây dựng một mô hình trong đó niềm tin mang tính công cụ có thể tồn tại khi nghi lễ được thực hiện trong một môi trường khí hậu khiến nó **trông có vẻ hiệu quả**.

Paper trả lời bằng hai lớp bằng chứng. Thứ nhất, tác giả nghiên cứu rất sâu dữ liệu lịch sử hằng ngày về các đợt cầu mưa ở Murcia, Tây Ban Nha từ 1600 đến 1836, ghép hồ sơ nhà thờ với ghi chép mưa từ hội đồng thành phố. Thứ hai, tác giả tự xây một bộ dữ liệu mới về việc 1.208 nhóm sắc tộc trên thế giới có thực hành nghi lễ cầu mưa hay không, rồi nối dữ liệu đó với đặc tính của quá trình mưa tại địa bàn tổ tiên của từng nhóm.

Kết quả chính là: cầu mưa phổ biến hơn đáng kể ở những nơi mà **hazard của mưa tăng lên sau một đợt khô hạn dài**, tức xác suất có mưa càng tăng khi hạn càng kéo dài. Trong setting đó, nếu lãnh đạo tôn giáo bắt đầu cầu đúng lúc, mưa dễ đến sau nghi lễ hơn, từ đó tạo cảm giác rằng nghi lễ "có tác dụng". Ở Murcia, cầu mưa trong tháng trước dự báo xác suất có một trận mưa đáng kể trong ngày cao hơn 71% so với xác suất trung bình; ở dữ liệu toàn cầu, các nhóm sống trong môi trường có increasing hazard có xác suất thực hành cầu mưa cao hơn khoảng 14 điểm phần trăm, tức khoảng 47% cao hơn so với nhóm đối chứng cơ sở.

Đây là bài đáng đọc vì nó làm ba việc cùng lúc: đưa ra một lý thuyết sắc về sự hình thành niềm tin công cụ, xây được dữ liệu gốc rất khó, và kiểm định được cùng một cơ chế ở cả một case lịch sử vi mô lẫn mặt cắt toàn cầu. Với người làm applied micro hay development, paper này là một ví dụ rất mạnh về cách nối theory, historical micro-data, climate process và comparative data vào cùng một design thống nhất.

## 3. Research question and motivation

### Câu hỏi nghiên cứu trung tâm

Vì sao con người duy trì niềm tin vào các thực hành tôn giáo mang tính công cụ, cụ thể là cầu mưa, dù bản thân nghi lễ không thật sự tạo ra mưa?

### Bối cảnh học thuật và thực tiễn

Paper đứng ở giao điểm của economic history, development economics, economics of religion và anthropology. Câu hỏi lớn phía sau là: môi trường tự nhiên định hình niềm tin và thể chế như thế nào? Văn liệu trước đã chỉ ra khí hậu và địa lý ảnh hưởng đến phát triển kinh tế, thiết chế chính trị, mức độ gắn bó với truyền thống hay tôn giáo. Nhưng vẫn còn thiếu một cơ chế cụ thể giải thích **vì sao một niềm tin công cụ cụ thể lại có vẻ đáng tin**.

Trong cách nói của paper, văn liệu đã nói khá nhiều về việc tôn giáo hữu ích ra sao sau khi đã tồn tại; còn paper này muốn lùi lại một bước và hỏi: điều gì khiến người ta thấy hợp lý để tin ngay từ đầu?

### Khoảng trống mà paper lấp vào

- Thiếu một lý thuyết rõ ràng về **formation of instrumental belief**, chứ không chỉ lợi ích của tôn giáo sau khi niềm tin đã được thiết lập.
- Thiếu kiểm định thực nghiệm trực tiếp về việc một nghi lễ như cầu mưa có trở nên "thuyết phục" hơn trong một số môi trường khí hậu nhất định hay không.
- Thiếu dữ liệu so sánh có hệ thống trên quy mô toàn cầu về thực hành cầu mưa giữa các nhóm sắc tộc.

## 4. Main contribution

### Đóng góp chính so với văn liệu trước

Đóng góp cốt lõi của paper là chuyển câu chuyện từ "tôn giáo có thể hữu ích" sang "niềm tin công cụ xuất hiện và được duy trì khi nào". Đây là một chuyển động rất quan trọng. Tác giả không tranh luận rằng cầu mưa thật sự gây mưa; thay vào đó, paper nói cầu mưa bền vững ở nơi mà quá trình mưa khiến nghi lễ dễ **được hiểu là thành công**.

### Điểm mới về dữ liệu, mô hình, và cách đặt câu hỏi

- Một mô hình thuyết phục trong đó lãnh đạo tôn giáo chọn thời điểm cầu nguyện; niềm tin phụ thuộc vào khoảng cách giữa xác suất mưa "khi có cầu nguyện" và xác suất mưa mà người dân suy ra từ các giai đoạn không cầu nguyện.
- Một case study cực mạnh ở Murcia với dữ liệu hằng ngày trong hơn hai thế kỷ về thời điểm cầu mưa, cầu tạ ơn, và các sự kiện mưa đáng kể.
- Một bộ dữ liệu mới do tác giả tự thu thập về thực hành cầu mưa cho 1.208 nhóm sắc tộc, dựa trên 370 nguồn nhân học.
- Một biến khí hậu rất tinh: không phải mức mưa trung bình, mà là **dấu của đạo hàm hazard rate của mưa sau một đợt hạn**.

### Vì sao đóng góp này quan trọng trong applied micro/development

Điểm hay của paper là nó cho thấy "môi trường" không chỉ tác động lên kinh tế qua năng suất hay disease burden, mà còn qua tính thuyết phục của niềm tin và qua đó ảnh hưởng đến cấu trúc xã hội, quyền lực tôn giáo, và persistence của văn hóa. Đây là kiểu đóng góp rất hợp với development economics hiện đại: tìm một cơ chế vi mô cụ thể nối environment với beliefs, institutions và long-run outcomes.

## 5. Identification or methodology

## 5.1 Mô hình lý thuyết

Paper xây một mô hình trong đó một lãnh đạo tôn giáo không thể làm mưa thật, nhưng có thể chọn **thời điểm bắt đầu cầu mưa**. Người dân quan sát mưa sau khi nghi lễ bắt đầu và so sánh với xác suất mưa mà họ suy ra từ các giai đoạn không cầu nguyện. Nếu cầu nguyện thường bắt đầu đúng lúc xác suất mưa đang tăng, nghi lễ sẽ có vẻ hiệu quả.

Khái niệm trung tâm là **rainfall hazard**: xác suất có mưa hôm nay, điều kiện trên số ngày đã trôi qua kể từ trận mưa trước. Kết quả lý thuyết cốt lõi là chỉ trong môi trường mà hazard tăng lên sau một đợt hạn dài thì lãnh đạo tôn giáo mới có thể thuyết phục được người dân rằng lời cầu có tác dụng. Trong phần mở rộng, paper còn cho phép lợi ích hữu hình của mưa và chi phí thực hành nghi lễ đi vào quyết định ủng hộ nghi lễ.

### Trực giác nhận dạng của mô hình

- Nếu hazard phẳng hoặc giảm, cầu nguyện không tạo được "seeming efficacy" ổn định.
- Nếu hazard tăng sau hạn dài, bắt đầu cầu đúng lúc sẽ khiến mưa đến sau nghi lễ với xác suất cao hơn.
- Qua quá trình cultural evolution, các thực hành có vẻ thành công sẽ tồn tại lâu hơn và trở nên phổ biến hơn.

## 5.2 Phần thực nghiệm 1: Murcia, Tây Ban Nha

Đây là phần gần causal nhất theo nghĩa paper kiểm tra trực diện cơ chế timing.

- Dữ liệu cầu mưa và cầu tạ ơn đến từ hồ sơ nhà thờ.
- Dữ liệu mưa đáng kể đến từ ghi chép độc lập của hội đồng thành phố.
- Mẫu chính chạy từ 1600 đến 1836; tác giả dừng trước giai đoạn quyền lực và tài chính của giáo hội thay đổi mạnh vì cải cách tịch thu tài sản và bãi bỏ thập phân.

Tác giả ước lượng hazard mưa ở Murcia thật linh hoạt bằng **cubic spline cho log cumulative hazard theo maximum likelihood**, và đối chiếu với Nelson-Aalen nonparametric hazard. Kết quả cho thấy hazard của mưa ở Murcia giảm lúc đầu sau cơn mưa gần nhất, chạm đáy khoảng hai tháng sau, rồi tăng trở lại sau những đợt khô dài. Đây đúng là môi trường mà mô hình dự đoán nghi lễ có thể trở nên thuyết phục.

Sau đó tác giả chạy distributed-lag regressions ở cấp ngày:

- Biến phụ thuộc là có ghi nhận một trận mưa đáng kể hay không, hoặc có lời cầu tạ ơn hay không.
- Biến giải thích chính là có lời cầu mưa nào trong 30 ngày gần nhất hay không.
- Có month fixed effects và các độ trễ của lời cầu để tách seasonality đơn thuần khỏi timing chiến lược.
- Standard errors dùng Newey-West để xử lý tự tương quan.

### Điểm mạnh

- Dữ liệu timing rất hiếm và rất hợp với cơ chế.
- Có nguồn ghi mưa độc lập với nhà thờ, giảm bớt lo ngại "ghi mưa để hợp thức hóa phép màu".
- Có kiểm tra Granger causality với các độ trễ của chính rainfall.

### Điểm dễ bị nghi ngờ

- Đây vẫn là một case study duy nhất.
- Biến mưa "đáng kể" từ nguồn lịch sử có thể bị chọn lọc theo mức độ đáng chú ý.
- "Prayer Granger-causes rain" ở đây là ngôn ngữ predictive, không phải causal effect vật lý.

## 5.3 Phần thực nghiệm 2: mặt cắt toàn cầu

Paper mở rộng ra toàn cầu bằng cách augment Ethnographic Atlas:

- mã hóa thực hành cầu mưa cho 1.208/1.290 nhóm sắc tộc,
- dùng 370 nguồn nhân học,
- ghép từng nhóm với trạm khí tượng gần nhất để suy ra đặc điểm hazard của mưa tại địa bàn tổ tiên.

Regression chính ở cấp ethnic group:

`RainRitual_i = beta_1 HazardIncreasing_i + controls + continent FE + error_i`

Controls gồm:

- climate controls: trung bình và độ lệch chuẩn của nhiệt độ, lượng mưa;
- geography controls: vĩ độ, kinh độ, khoảng cách tới biển, sông lớn, hồ lớn;
- topography controls: độ cao và ruggedness;
- continent fixed effects;
- Conley standard errors để xử lý spatial correlation.

Paper còn thêm các test tinh hơn:

- tách hazard tăng trong growing season và ngoài growing season;
- kiểm tra vai trò của độ dài đợt hạn;
- thêm proxy demand từ mức phụ thuộc vào nông nghiệp;
- placebo outcome với niềm tin vào "high gods".

### Điểm mạnh

- Cơ chế kiểm định rất cụ thể, không chỉ nói "nơi khô hơn thì cầu mưa nhiều hơn".
- Robustness tốt với spatial inference.
- Có phân biệt rõ persuasion channel và demand channel.

### Điểm dễ bị nghi ngờ

- Cross-section toàn cầu khó loại bỏ hoàn toàn omitted variables rất sâu về văn hóa hay lịch sử.
- Việc mã hóa từ nguồn nhân học luôn có nguy cơ sai lệch đo lường.
- Ghép weather station hiện đại vào ancestral homelands là hợp lý nhưng không hoàn hảo.

## 6. Results and interpretation

## 6.1 Kết quả Murcia

Murcia là một nơi có increasing hazard sau hạn dài, nên theo mô hình cầu mưa có thể trở nên thuyết phục. Dữ liệu xác nhận đúng pattern đó.

Kết quả nổi bật nhất:

- Cầu mưa trong tháng trước làm xác suất có mưa đáng kể trong ngày cao hơn khoảng **0.144 điểm phần trăm** so với xác suất nền **0.203 điểm phần trăm**, tức tăng khoảng **71%**.
- Nếu dùng lời cầu tạ ơn như proxy đầy đủ hơn cho việc "mưa đã đến", hiệu ứng còn mạnh hơn nữa.
- Lời cầu từ 3 đến 12 tháng trước không còn sức dự báo, nghĩa là tín hiệu nằm ở timing gần, không phải tương quan mơ hồ dài hạn.
- Prayer vẫn có sức dự báo ngay cả khi đã kiểm soát month fixed effects, nên đây không chỉ là chuyện cầu nguyện vào mùa mưa.

Diễn giải kinh tế ở đây rất hay: nghi lễ không cần thật sự hiệu quả để được duy trì; nó chỉ cần được đặt vào một thời điểm mà outcome tốt nhiều khả năng sẽ tới ngay sau đó. Nếu người dân học từ chuỗi quan sát như vậy qua nhiều thế hệ, niềm tin có thể bền vững hoàn toàn bằng logic cập nhật sai phảnfactual.

## 6.2 Kết quả toàn cầu

Ở dữ liệu ethnic-group toàn cầu:

- 39% nhóm trong mẫu được mã hóa là có thực hành cầu mưa.
- Các nhóm sống trong môi trường có increasing hazard có xác suất cầu mưa cao hơn khoảng **14 điểm phần trăm**.
- Mức nền ở nhóm có decreasing hazard là khoảng **30%**, nên 14 điểm phần trăm tương đương khoảng **47% tăng thêm**.
- Hiệu ứng này rất ổn định khi thêm climate, geography và topography controls.
- Khi tách theo mùa, hazard chỉ có sức dự báo khi nó tăng trong **growing season**, đúng lúc nhu cầu mưa cao nhất.
- Mean rainfall, rainfall volatility, hay độ dài đợt hạn tự thân không còn giải thích được khi đã kiểm soát increasing hazard.

Kết quả demand side cũng mạnh:

- Nhóm phụ thuộc vào nông nghiệp có xác suất cầu mưa cao hơn khoảng **9.7 điểm phần trăm**.
- Với agriculture dependence đo liên tục, mức phụ thuộc càng cao thì xác suất cầu mưa càng lớn.
- Nhóm làm **intensive irrigated agriculture** có xác suất cầu mưa cao hơn rất mạnh, hệ số khoảng **0.37**.

### Kết quả nào thật sự nổi bật

Điểm nổi bật nhất không phải chỉ là "khí hậu có liên quan", mà là paper chốt được **đúng đặc tính khí hậu mà mô hình dự đoán**. Không phải nơi khô hơn, không phải nơi mưa biến động hơn, mà là nơi hazard tăng sau hạn dài, nhất là trong mùa cây trồng cần nước. Đây là một kiểu "over-identification by mechanism" rất đẹp.

## 7. What is special or elegant about the paper

Có ít nhất bốn điểm làm bài này đáng nhớ.

Thứ nhất, paper biến một câu hỏi tưởng như quá mềm của anthropology thành một câu hỏi applied micro rất sắc: nghi lễ có trở nên đáng tin khi nào?

Thứ hai, biến giải thích trung tâm không phải level của khí hậu mà là **shape của một stochastic process**. Chỉ riêng việc nghĩ ra rằng "đạo hàm của hazard sau hạn dài" mới là đối tượng đúng để đo perceived efficacy đã là một đóng góp ý tưởng rất mạnh.

Thứ ba, bài không dừng ở một narrative case study. Tác giả dùng Murcia để nhìn thấy cơ chế bằng kính hiển vi, rồi đưa đúng cơ chế đó lên mặt cắt toàn cầu bằng dữ liệu mới.

Thứ tư, paper có tính "đẹp" ở chỗ theory và empirics khóa vào nhau rất chặt. Kết quả mạnh nhất cũng là kết quả đúng nhất theo mô hình: hazard tăng trong growing season, chứ không phải bất kỳ proxy khí hậu na ná nào.

## 8. Required background knowledge

Để đọc paper này trơn tru, người đọc nên có mấy nền sau.

### 8.1 Hazard function

Hazard ở đây là xác suất có mưa hôm nay, với điều kiện đã không có mưa trong một số ngày trước đó. Một hazard tăng nghĩa là càng hạn lâu thì khả năng mưa hôm nay càng cao. Đây là khái niệm quen thuộc trong duration/survival analysis, nhưng paper dùng nó cho weather process.

### 8.2 Counterfactual reasoning và perceived efficacy

Người dân không quan sát được phảnfactual: nếu hôm đó không cầu mưa thì trời có mưa không? Nếu họ so sánh sai giữa "sau khi cầu" và "một xác suất nền không đúng", họ có thể kết luận sai rằng nghi lễ hiệu quả. Paper về bản chất là một bài về inference under missing counterfactual.

### 8.3 Cultural evolution

Ý tưởng là các nghi lễ không tồn tại ngẫu nhiên. Những nghi lễ nào có vẻ thành công hơn sẽ được lặp lại, được hợp thức hóa và được truyền qua nhiều thế hệ. Đây là cách paper nối micro-updating của niềm tin với persistence dài hạn của văn hóa.

### 8.4 Spatial econometrics và Conley standard errors

Trong dữ liệu toàn cầu, các nhóm gần nhau có thể chia sẻ khí hậu và lịch sử tương tự, nên residuals có tương quan theo không gian. Conley standard errors là cách điều chỉnh inference cho tương quan không gian đó, tránh overstate precision.

### 8.5 Ethnographic Atlas và historical data work

Paper dựa nhiều vào việc mã hóa định tính từ tài liệu nhân học và tư liệu lịch sử. Người đọc nên quen với việc biến narrative sources thành structured variables, cũng như hiểu rằng thách thức lớn nhất nằm ở measurement và coding consistency.

## 9. Limitations and open questions

### Hạn chế chính

- Murcia là một case rất giàu dữ liệu nhưng vẫn chỉ là một case.
- Phần toàn cầu là cross-section; dù controls rất nhiều, vẫn khó loại bỏ hoàn toàn historical confounders.
- Mã hóa "có cầu mưa hay không" từ 370 nguồn chắc chắn vẫn có measurement error, đặc biệt với những nhóm ít được mô tả.
- Hazard hiện đại tại vùng tổ tiên là proxy hợp lý nhưng không hoàn hảo cho climate beliefs lịch sử.

### Giả định nhạy cảm

- Người dân và lãnh đạo tôn giáo phản ứng đủ nhiều với timing để ritual selection hoạt động.
- Ghi chép mưa và cầu nguyện ở Murcia phản ánh timing thực khá trung thực.
- Increasing hazard đo ở phần đuôi dài của dry spell mới là đối tượng đúng; paper có robustness cho chuyện này, nhưng kết quả phụ thuộc vào việc xác định đuôi hazard đủ chính xác.

### Câu hỏi mở

- Từ rainmaking có đi xa hơn sang các hình thức niềm tin công cụ khác như chữa bệnh, chống dịch, hay fertility rituals không?
- Khi nào seeming efficacy chuyển hóa thành quyền lực chính trị hoặc fiscal extraction mạnh hơn của tổ chức tôn giáo?
- Formal insurance, irrigation infrastructure hay weather forecasting hiện đại có làm suy yếu rainmaking theo đúng kênh mà paper gợi ý không?

## 10. Takeaways for a researcher

1. Một câu hỏi lớn về văn hóa hay niềm tin vẫn có thể trở thành một paper applied micro rất sạch nếu tìm được một cơ chế đủ cụ thể và đo được.
2. Thay vì dùng level của biến môi trường, đôi khi thứ thật sự quan trọng là **shape của quá trình động**.
3. A good paper often uses one setting for mechanism visibility and another for external validity. Murcia làm việc thứ nhất, dữ liệu ethnic-group toàn cầu làm việc thứ hai.
4. Dữ liệu mới không nhất thiết phải là administrative data hiện đại; coding nghiêm túc từ nguồn lịch sử và nhân học vẫn có thể tạo ra đóng góp lớn.
5. Robustness tốt nhất là robustness theo cơ chế: paper không chỉ thêm controls, mà còn chứng minh đúng lúc, đúng mùa, đúng tail của hazard mới quan trọng.
6. Placebo outcome rất đáng học. Việc hazard không dự báo niềm tin vào high gods giúp paper nói rõ mình đang đo cái gì và không đo cái gì.

## 11. Vietnam relevance and extension

### Ý tưởng này có liên quan gì tới Việt Nam?

Có, và theo mình là khá nhiều. Việt Nam có lịch sử nông nghiệp phụ thuộc mạnh vào mưa, thủy lợi, mùa vụ và tín ngưỡng dân gian rất phong phú. Vì vậy, câu hỏi "môi trường nào khiến một niềm tin công cụ trở nên có vẻ đáng tin" hoàn toàn có thể được đặt lại trong bối cảnh Việt Nam.

### Có triển khai nghiên cứu tương tự ở Việt Nam được không?

Có thể, nhưng sẽ khó hơn Murcia vì dữ liệu hằng ngày về nghi lễ và outcome thường phân tán hơn. Một thiết kế khả thi sẽ cần ít nhất:

- tư liệu địa phương hoặc văn khắc về lễ cầu mưa, lễ cầu đảo, lễ tạ ơn, hoặc nghi lễ nông nghiệp;
- dữ liệu khí tượng lịch sử hoặc proxy khí hậu đủ chi tiết theo không gian;
- bản đồ vùng canh tác, cây trồng và mùa vụ;
- nếu làm contemporary setting, có thể dùng survey hoặc ethnographic fieldwork kết hợp dữ liệu weather station.

### Trở ngại chính ở Việt Nam

- Dữ liệu lịch sử phân tán giữa đình, chùa, thần tích, địa chí và lưu trữ hành chính.
- Khó mã hóa thống nhất ritual practice giữa các vùng.
- Khó nối ritual timing với outcome khí tượng nếu không có nhật ký hoặc biên niên đủ dày.

### Hướng mở rộng phù hợp hơn với Việt Nam

- Không nhất thiết bám đúng "cầu mưa". Có thể mở sang nghi lễ liên quan tới lũ, xâm nhập mặn, thủy thần, mùa màng hoặc sức khỏe vật nuôi.
- Có thể nghiên cứu tác động của hệ thống thủy lợi hiện đại, dự báo thời tiết, hoặc bảo hiểm nông nghiệp lên persistence của niềm tin công cụ.
- Có thể nối sang economy of adaptation: nơi có climate risk cao nhưng infrastructure bảo vệ yếu thì vai trò của ritual có tăng không?

### 1 đến 3 research design / research question ở Việt Nam

1. **Ritual và hazard của lũ/mưa ở đồng bằng sông Cửu Long:** các địa phương có pattern khí hậu nào duy trì mạnh hơn các nghi lễ liên quan đến nước và mùa vụ?
2. **Thủy lợi hiện đại và suy giảm tín ngưỡng công cụ:** việc mở rộng hồ chứa, đê điều, hay hệ thống dự báo thời tiết có làm giảm tần suất các nghi lễ cầu thời tiết cực đoan không?
3. **So sánh vùng lúa mưa trời với vùng tưới chủ động:** mức phụ thuộc vào rainfed agriculture có dự báo khác biệt trong persistence của tín ngưỡng nông nghiệp hay không?

## 12. Vì sao chọn paper này cho lượt hôm nay

Mình chọn paper này vì ba lý do.

- Đây là **QJE top-5** và rất mới: published online ngày **11/05/2026**.
- Paper nằm đúng vùng giao giữa development, applied micro, economic history và political-cultural foundations của development.
- Thiết kế nghiên cứu rất đáng học: một mô hình cơ chế rõ, một case lịch sử cực sâu để nhìn timing, rồi một bộ dữ liệu toàn cầu tự xây để kiểm tra external validity.

## 13. Trạng thái lưu trữ và giới hạn của lượt chạy

- `analysis.md`: đã tạo cục bộ và sẵn sàng cho bước lưu GitHub.
- `analysis.html`: đã tạo cục bộ từ nội dung này và sẵn sàng cho bước lưu GitHub.
- `analysis.pdf`: chưa tạo trong lượt này.
- `paper.pdf` gốc: đã xác minh được nguồn PDF chính thức QJE, nhưng chưa tải được file nhị phân về môi trường chạy do truy cập ngoài bị chặn `403`, nên chưa thể lưu raw PDF lên GitHub.
- Google Drive: trong lượt này chỉ thực hiện nếu thật sự tạo được Google Doc dễ đọc và tracker một cách nhất quán; nếu không sẽ bỏ qua hoàn toàn và ghi rõ trong email.