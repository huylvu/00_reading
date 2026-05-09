# Globalization and the Ladder of Development: Pushed to the Top or Held at the Bottom?

- **Tác giả:** David Atkin, Arnaud Costinot, Masao Fukui
- **Journal:** The Review of Economic Studies
- **Năm:** 2025
- **Ngày agent chạy:** 2026-05-09
- **Nguồn bài báo chính:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdaf077/8244483
- **Nguồn PDF dùng để phân tích:** bản public manuscript trên MIT Economics `mutvc LATEST.pdf` tại https://economics.mit.edu/sites/default/files/publications/mutvc%20LATEST.pdf
- **Ghi chú về PDF:** Bản PDF phân tích là working/manuscript version ghi `November 2021`, nhưng nội dung khung bài, câu hỏi, mô hình, chiến lược thực nghiệm, và kết luận lớn khớp rõ với bản ReStud corrected proof năm 2025 từ trang Oxford Academic.
- **Trạng thái lưu trên GitHub:** `analysis.md` và `analysis.html` đã được lưu lên repo `huylvu/00_reading` tại thư mục `Globalization and the Ladder of Development - Atkin Costinot Fukui/`.
- **Trạng thái lưu trên Google Drive:** Bỏ qua trong lượt chạy này vì chưa có tuyến tạo Google Doc và tracker trong đúng folder đích với độ chắc chắn đủ cao.

## 1. Metadata

- **Tiêu đề paper:** Globalization and the Ladder of Development: Pushed to the Top or Held at the Bottom?
- **Tác giả:** David Atkin, Arnaud Costinot, Masao Fukui
- **Journal:** The Review of Economic Studies
- **Tình trạng xuất bản:** Corrected proof trên Oxford Academic
- **Ngày published trên nguồn journal:** 30 August 2025; corrected and typeset 26 September 2025
- **DOI:** 10.1093/restud/rdaf077
- **Link bài báo:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdaf077/8244483
- **Link PDF đã dùng để đọc:** https://economics.mit.edu/sites/default/files/publications/mutvc%20LATEST.pdf
- **Phân loại lĩnh vực:** Development economics giao với international trade và quantitative applied work
- **Top 5 status:** Có. ReStud là top 5 journal kinh tế.

## 2. Executive summary

Paper hỏi một câu rất nền tảng nhưng thường bị nói bằng ẩn dụ hơn là bằng mô hình: thương mại quốc tế có thật sự giúp các nước "leo thang phát triển" hay không. Cụ thể hơn, nếu một nước dịch chuyển sang các ngành phức tạp hơn thì liệu điều đó có làm tăng tích lũy năng lực sản xuất, và khi thế giới mở cửa thương mại thì lực cạnh tranh quốc tế có đẩy các nước về phía những ngành "tốt" đó hay ngược lại.

Các tác giả trả lời bằng cách kết hợp một mô hình thương mại động kiểu Ricardian với một chiến lược thực nghiệm đo `complexity` của hàng hóa, `capability` của quốc gia, rồi ước lượng xem thay đổi ngoại sinh trong cơ cấu chuyên môn hóa có làm tăng capability growth hay không. Nút nhận dạng chính là dùng thời điểm các nước khác gia nhập WTO như một cú sốc ngoại sinh làm thay đổi competition và từ đó làm thay đổi average complexity của cơ cấu ngành ở từng nước.

Kết quả trung tâm có hai nửa, và chính sự căng giữa hai nửa này làm paper hay. Một mặt, dữ liệu ủng hộ ý rằng dịch chuyển lao động sang các ngành phức tạp hơn làm tăng tăng trưởng capability, tức là quả thật có những "ngành tốt" theo nghĩa động. Nhưng mặt khác, các ngành phức tạp hơn trong dữ liệu lại không phải là những ngành có cạnh tranh quốc tế mềm hơn; ngược lại, chúng thường bị nhiều nước sản xuất và xuất khẩu hơn. Vì vậy, cơ chế "trade pushes everyone toward better sectors" của ẩn dụ chiếc thang không được dữ liệu ủng hộ.

Diễn giải cuối cùng của paper khá sắc: thương mại vẫn có static gains quen thuộc, nhưng nếu nhìn qua lăng kính tích lũy capability thì dynamic effects không nhất thiết tích cực và thậm chí có thể là tổn thất lan rộng. Trong các phản thực nghiệm của paper, median dynamic loss là khoảng 2.5%, còn một số nước đang phát triển, đặc biệt ở châu Phi, chịu thiệt động đáng kể hơn.

Đây là bài rất đáng đọc vì nó làm ba việc cùng lúc: formalize một ẩn dụ phát triển rất phổ biến, đo lường nó bằng dữ liệu quốc tế dài hạn, và buộc người đọc phải nghĩ nghiêm túc hơn về industrial policy, complexity, và trade không chỉ ở biên tĩnh mà còn ở biên động.

## 3. Research question and motivation

### Câu hỏi nghiên cứu trung tâm

Câu hỏi lõi là: **thương mại quốc tế có đẩy các quốc gia lên những bậc cao hơn của "development ladder" hay giữ họ ở những nấc thấp hơn?** Nói theo ngôn ngữ formal hơn, khi một nước chuyên môn hóa vào các ngành phức tạp hơn, liệu nước đó có tích lũy năng lực sản xuất nhanh hơn không; và nếu có, liệu mở cửa thương mại có khiến hầu hết các nước dịch chuyển theo đúng hướng đó không.

### Bối cảnh học thuật và thực tiễn

Paper đi vào một tranh luận rất cũ nhưng vẫn còn nóng trong development và trade:

- Truyền thống Ricardian nói rằng trade patterns phản ánh comparative advantage đã có sẵn; phát triển đi trước, cơ cấu xuất khẩu đi sau.
- Truyền thống industrial policy và learning-by-doing nhấn mạnh chiều ngược lại: chuyên môn hóa vào những ngành "đúng" có thể tự nó tạo ra phát triển về sau.
- Văn liệu về economic complexity, product space, và export sophistication nhiều năm qua gợi ý rằng "what you produce matters", nhưng thường chưa gắn chặt phần trực giác đó vào một mô hình trade động đủ rõ.

Về mặt thực tiễn, câu hỏi này liên quan trực tiếp tới chuyện các nước đang phát triển có nên chỉ "theo comparative advantage hiện tại" hay chủ động đẩy nguồn lực sang các ngành phức tạp hơn. Nó cũng liên quan tới cách hiểu tác động của các cú sốc lớn như WTO accession hay sự trỗi dậy của Trung Quốc.

### Khoảng trống mà bài muốn lấp vào

Khoảng trống chính là thiếu một framework thống nhất nối ba thứ:

- cấu trúc thương mại quốc tế
- khác biệt về độ phức tạp của hàng hóa và capability của quốc gia
- tăng trưởng động thông qua spillovers từ specialization

Paper không chỉ muốn nói "complex sectors may matter" mà muốn hỏi kỹ hơn: **trong equilibrium thương mại thật, các nước có bị đẩy vào các ngành đó hay không?** Chính câu hỏi equilibrium này là điểm paper vượt lên so với nhiều tranh luận policy vốn dừng ở trực giác.

## 4. Main contribution

### Đóng góp chính so với văn liệu trước

Đóng góp lớn nhất là paper formalize ẩn dụ "development ladder" thành một mô hình trade động có thể kiểm định, rồi đem nó ra dữ liệu theo cách đủ tham vọng để kết luận về welfare động chứ không chỉ về correlation.

So với văn liệu trước, bài có ba đóng góp rõ:

1. **Đóng góp khái niệm:** Biến ẩn dụ "nước ở nấc cao sản xuất hàng phức tạp" thành một cấu trúc với `capability`, `complexity`, competition, và dynamic spillovers.
2. **Đóng góp đo lường:** Xây được thước đo capability của nước và complexity của hàng hóa từ dữ liệu thương mại rất rộng, rồi dùng chúng để tính average complexity của industry mix.
3. **Đóng góp định lượng và policy:** Chuyển kết quả reduced-form thành đánh giá dynamic gains/losses from trade, thay vì chỉ dừng ở ước lượng dấu của spillover.

### Điểm mới về dữ liệu, mô hình, và cách đặt câu hỏi

- Dữ liệu thương mại quốc tế rất dài, phủ 146 nước từ 1962 đến 2014.
- Mô hình cho phép capability của quốc gia tiến hóa theo cơ cấu ngành mà nước đó sản xuất, tức là có growth feedback từ specialization.
- IV tận dụng WTO entry timing của các nước khác như một shift-share style shifter cho average complexity của một nước.
- Phần định lượng không chỉ mô phỏng autarky-trade tĩnh mà còn mô phỏng đường đi capability dưới trade và autarky để tách static với dynamic gains.

### Vì sao đóng góp này quan trọng trong development economics

Development economics quan tâm sâu tới structural transformation, learning, và long-run productivity growth. Paper này quan trọng vì nó đưa một trực giác rất "development" vào môi trường trade equilibrium nghiêm ngặt. Nó cũng rất hữu ích cho người học nghiên cứu vì cho thấy cách đi từ metaphor -> model -> measurement -> identification -> welfare.

## 5. Identification or methodology

## 5.1. Xương sống lý thuyết

Paper xây một mô hình Ricardian động nhiều nước, nhiều ngành:

- Mỗi nước có một mức **capability**.
- Mỗi hàng hóa/ngành có một mức **complexity**.
- Capability và complexity cùng quyết định phân bố productivity theo nước-ngành.
- Capability ở kỳ sau phụ thuộc một phần vào **average complexity của output mix hiện tại**, tức là chuyên môn hóa vào ngành phức tạp hơn có thể tạo ra learning spillovers và nâng capability.

Trong phiên bản benchmark gọi là **pure ladder economy**, các hàng hóa phức tạp hơn được sản xuất bởi ít nước hơn, tức chủ yếu bởi các nước capability cao hơn. Khi đó, mở cửa thương mại làm competition mạnh hơn ở các ngành thấp trên thang, khiến mọi nước bị đẩy sang các ngành tương đối phức tạp hơn mà họ vẫn làm được; nếu các ngành này có spillover dương thì tất cả cùng hưởng dynamic gains.

Đây là một insight lý thuyết đẹp: dynamic gains from trade không nhất thiết zero-sum. Chúng có thể cùng chiều cho tất cả nếu cấu trúc competition đúng kiểu "ladder".

## 5.2. Đo lường capability và complexity

Phần thực nghiệm sau đó cố đưa chiếc thang này xuống dữ liệu. Intuition là:

- Nếu một nước capability cao thì xác suất nó xuất khẩu được hàng phức tạp sẽ cao hơn.
- Nếu một hàng hóa phức tạp thì các nước capability cao sẽ xuất khẩu nó với xác suất lớn hơn.

Capability của nước và complexity của hàng hóa được ước lượng như một fixed point nhất quán với hai loại quan sát trên trong dữ liệu thương mại. Từ đó tác giả xây biến **average complexity của industry mix** cho từng nước-năm.

Điểm hay là complexity ở đây không chỉ là nhãn cảm tính kiểu "máy móc cao hơn dệt may", mà là một object suy ra từ pattern thương mại toàn cầu. Điều này giúp paper giữ được kết nối giữa theory và measurement.

## 5.3. Phương trình động và ý nghĩa của tham số chính

Phần reduced-form động của paper hồi quy tăng trưởng capability vào average complexity của cơ cấu ngành. Tham số quan trọng nhất là hệ số đo xem một cú dịch chuyển sang các ngành phức tạp hơn có làm capability tăng nhanh hơn hay không.

Nếu hệ số này dương:

- trade-induced shifts toward more complex sectors có thể tạo ra gains động
- industrial composition không chỉ phản ánh phát triển, mà còn góp phần tạo ra phát triển

Nếu hệ số này âm hoặc bằng 0:

- toàn bộ trực giác "good sectors" sẽ yếu đi đáng kể

## 5.4. Chiến lược nhận dạng

Đây là phần applied rất đáng học. Vấn đề nội sinh là các cú sốc trong nước như policy tốt, cải cách giáo dục, hoặc rent-seeking có thể vừa làm economy dịch chuyển sang ngành phức tạp hơn vừa ảnh hưởng capability growth, nên không thể đọc hệ số OLS như causal.

Paper xử lý bằng cách dùng **việc các nước khác gia nhập WTO** làm cú sốc ngoại sinh cho competition và từ đó cho cơ cấu ngành của nước đang xét. Logic là:

- Khi nước `c` gia nhập WTO, nước đó được hưởng lower tariffs từ các thành viên hiện hữu.
- Việc này thay đổi demand for labor across sectors ở các nước còn lại.
- Mức thay đổi của average complexity ở nước `i` phụ thuộc vào việc các ngành phức tạp của `i` trùng nhiều hay ít với export mix của `c`, cả theo goods lẫn destination.

Từ đó tác giả xây hai instrument dựa trên thay đổi complexity dự báo bởi:

- sector-level price effects
- aggregate-level price effects

Assumption cốt lõi là **timing WTO accession của các nước khác là orthogonal với capability shocks của nước `i`**. Đây không phải assumption nhẹ, nhưng nó có vẻ hợp lý hơn nhiều so với việc tin rằng thay đổi cơ cấu ngành của từng nước là tự nhiên ngoại sinh.

## 5.5. Điểm mạnh của phương pháp

- Kết nối cực chặt giữa theory và IV design; instrument không phải thứ gắn thêm cho có.
- Cú sốc WTO entry là economically meaningful và cross-country đủ rộng để tạo variation.
- Paper không dừng ở reduced form mà còn dùng estimates để làm welfare decomposition.
- Có sensitivity analysis đi ngược quy trình baseline để kiểm tra xem kết quả có phụ thuộc mạnh vào cách định nghĩa complexity hay không.

## 5.6. Điểm dễ bị nghi ngờ hoặc cần thận trọng

- WTO accession không hoàn toàn ngẫu nhiên theo nghĩa lịch sử chính trị; paper dựa vào việc accession của **các nước khác** là orthogonal với shock capability của nước đang xét, nhưng vẫn cần tin exclusion restriction khá mạnh.
- Capability là latent object được suy ra từ trade data; bất kỳ measurement error hay model dependence nào ở bước này đều có thể lan sang phần định lượng sau.
- Mapping từ reduced-form spillovers sang long-run welfare là ambitious; kết quả policy nên đọc như "disciplined quantitative interpretation" hơn là đo lường chính xác tuyệt đối.

## 6. Results and interpretation

### 6.1. Có bằng chứng rằng ngành phức tạp hơn là "ngành tốt"

Kết quả IV baseline cho thấy khi một cú sốc ngoại sinh làm employment shift về phía các ngành có average complexity cao hơn, capability growth tăng lên. Paper cũng nhấn mạnh rằng các dịch chuyển như vậy đi kèm với tăng real GDP per capita có ý nghĩa thống kê.

Ý nghĩa kinh tế ở đây rất quan trọng: ít nhất một phần của development ladder metaphor là đúng. Chuyên môn hóa không chỉ là kết quả của phát triển; nó còn có thể là một đầu vào của phát triển thông qua learning và spillovers.

### 6.2. Nhưng các ngành "tốt" đó lại không phải nơi cạnh tranh quốc tế mềm hơn

Đây là cú bẻ lái lớn của paper. Khi nhìn vào dữ liệu thương mại thế giới, các tác giả thấy các hàng hóa phức tạp hơn thường:

- được sản xuất bởi **nhiều** nước hơn, không phải ít hơn
- khi đã được xuất khẩu thì còn được bán tới **nhiều destination hơn**

Nói gọn: complex sectors là sectors có foreign competition mạnh hơn, không phải nhẹ hơn. Điều này đối nghịch trực diện với cấu trúc cần có để trade tự động đẩy mọi nước về phía "better sectors".

### 6.3. Hệ quả welfare động

Khi nhúng các kết quả thực nghiệm này trở lại mô hình, paper kết luận rằng:

- **static gains from trade** vẫn dương như lý thuyết chuẩn
- nhưng **dynamic gains** không còn lan rộng theo nghĩa tích cực
- trong baseline, dynamic effects trở thành **dynamic welfare losses mang tính pervasive**, dù median country chỉ chịu mất mát tương đối nhỏ

Con số paper nhấn mạnh là **median dynamic loss khoảng 2.5%**; với input-output linkages, average và median dynamic loss lần lượt khoảng **13.2%** và **2.5%**. Một số nước đang phát triển, đặc biệt ở châu Phi, chịu tổn thất động lớn hơn nhiều.

### 6.4. Vai trò của Trung Quốc

Paper còn dùng cùng framework để hỏi riêng về sự trỗi dậy của Trung Quốc. Kết luận định tính là sự xuất hiện của một nước lớn như Trung Quốc có thể kéo một số nước khác ra khỏi các ngành phức tạp nhất của họ, đặc biệt khi Trung Quốc cạnh tranh mạnh ở đúng các ngành ấy, và đẩy họ về các ngành đơn giản hơn. Với một số nước châu Phi, điều này đồng nghĩa với capability growth bị kìm lại.

### 6.5. Cách nên diễn giải kết quả

Paper không nói rằng trade "xấu" theo nghĩa tổng quát hay rằng autarky tốt hơn. Điều paper nói tinh tế hơn:

- gains tĩnh là có thật
- gains động không thể suy ra chỉ từ ẩn dụ ladder
- muốn trade thúc đẩy long-run development, cần nhìn xem cấu trúc competition thực tế có đang đẩy nguồn lực vào các ngành có spillover dương hay không

Đây là một thông điệp rất hữu ích cho debate về industrial policy: câu hỏi không phải chỉ là "ngành phức tạp có tốt không", mà còn là "equilibrium trade có tự đưa nước vào các ngành đó không".

## 7. What is special or elegant about the paper

Điểm đẹp nhất của paper là nó bắt đầu từ một ẩn dụ mà rất nhiều nhà policy và development hay dùng, rồi không để ẩn dụ đứng yên ở mức rhetoric. Tác giả hỏi rất nghiêm: nếu ta tin vào ẩn dụ đó, nó đòi hỏi những điều gì về competition, specialization, và growth? Và khi kiểm tra những điều kiện ấy trong dữ liệu, ta học được gì?

Một số điểm đặc biệt đáng nhớ:

- **Formalization cực gọn mà giàu ý nghĩa.** "Ladder" nghe mơ hồ, nhưng vào paper này thì nó trở thành một set điều kiện kiểm định được.
- **Half-right result.** Kết quả không phải "ẩn dụ sai hoàn toàn" mà là "một nửa đúng, một nửa sai". Đây thường là dấu hiệu của paper tốt: nó không chỉ đảo chiều một niềm tin, mà cho ta hiểu niềm tin đó đúng ở đoạn nào và hỏng ở đâu.
- **Theory và empirics nói chuyện thật với nhau.** Instrument, measurement, counterfactual welfare, và policy interpretation đều mọc ra từ cùng một logic.
- **Bài học về câu hỏi nghiên cứu.** Thay vì hỏi thẳng "trade tốt hay xấu", paper hỏi "trade có dịch chuyển nguồn lực vào các ngành tạo capability growth hay không". Câu hỏi này sắc hơn nhiều.

## 8. Required background knowledge

Để đọc paper này trọn vẹn, người đọc nên có vài mảng nền sau.

### 8.1. Ricardian trade models

Cần nắm intuition cơ bản của mô hình Ricardian:

- các nước khác nhau về productivity tương đối
- thương mại khiến họ chuyên môn hóa theo comparative advantage
- gains from trade chuẩn thường là gains tĩnh: tiêu dùng được bundle tốt hơn với cùng nguồn lực

Paper này mở rộng truyền thống đó bằng cách cho comparative advantage hôm nay ảnh hưởng capability ngày mai.

### 8.2. Learning-by-doing và dynamic externalities

Đây là ý rằng sản xuất trong một số ngành có thể tạo:

- tích lũy know-how
- spillovers công nghệ
- năng lực tổ chức hay managerial capability

Nếu firm cá thể không internalize lợi ích này, equilibrium thị trường có thể under-invest vào những ngành đó. Đây là nền tảng lý thuyết cho industrial policy trong nhiều mô hình development.

### 8.3. Economic complexity và product space

Người đọc nên biết sơ bộ văn liệu kiểu Hausmann-Hidalgo:

- nước phát triển hơn thường xuất khẩu rổ hàng hóa "khó" hơn
- cơ cấu hàng xuất khẩu có thể mang thông tin về productive capabilities tiềm ẩn

Paper này không bê nguyên product space vào, nhưng dùng đúng tinh thần đó để đo capability và complexity.

### 8.4. Shift-share IV và exclusion restriction

Chiến lược thực nghiệm của paper gần với logic shift-share:

- shares ban đầu xác định ai phơi nhiễm với shock nào
- shocks ở đây đến từ WTO accession timing của các nước khác

Người đọc nên thoải mái với câu hỏi nhận dạng kiểu:

- shock có thật sự ngoại sinh không
- shares có đang phản ánh lựa chọn nội sinh sâu hơn không
- instrument đang thay đổi biến nội sinh qua kênh nào

### 8.5. Welfare decomposition trong quantitative trade

Paper còn đi thêm bước định lượng welfare. Không cần nắm mọi chi tiết tính toán, nhưng nên hiểu:

- static gain = lợi ích trade với capability giữ nguyên
- dynamic gain/loss = phần chênh thêm do đường đi capability khác nhau dưới trade so với autarky

Chính decomposition này giúp paper nối reduced form với policy interpretation.

## 9. Limitations and open questions

### Hạn chế chính

1. **Capability là latent variable.** Nó được suy ra từ pattern thương mại, nên độ tin cậy phụ thuộc vào cấu trúc model và chất lượng đo lường trade data.
2. **Exclusion restriction không nhẹ.** Dù dùng WTO accession của nước khác là khá thông minh, vẫn có thể lo rằng các đợt accession lớn đi cùng những thay đổi địa chính trị hoặc demand shifts rộng hơn.
3. **Khái niệm complexity vẫn là reduced-form object.** Nó hữu ích nhưng không nói rõ spillover đến từ công nghệ, managerial learning, standards, hay network effects.
4. **Counterfactual autarky hơi xa hiện thực.** Nó là benchmark chuẩn để tách static và dynamic effects, nhưng policy inference thực tế thường là về marginal reforms chứ không phải autarky hoàn toàn.

### Những câu hỏi mở

- Tại sao trong dữ liệu, các ngành phức tạp lại bị nhiều nước cạnh tranh hơn? Đây là kết quả của diffusion công nghệ, industrial policy lịch sử, hay measurement của complexity?
- Có những institutional conditions nào khiến một nước vẫn leo lên được trong môi trường complex sectors cạnh tranh khốc liệt?
- Nếu thêm firm heterogeneity, global value chains, hoặc task-level specialization, kết quả dynamic losses còn mạnh như vậy không?
- Kết quả có thay đổi khi capability được đo bằng dữ liệu sản xuất, patent, hay occupational structure thay vì trade flows không?

## 10. Takeaways for a researcher

1. **Một ẩn dụ phổ biến có thể trở thành paper rất mạnh nếu bạn formalize nó đủ nghiêm.** Nhiều ý hay trong development nằm ở các câu nói tưởng như quá quen.
2. **Đừng chỉ hỏi một cơ chế có tồn tại hay không; hãy hỏi equilibrium có đẩy nền kinh tế theo cơ chế đó không.** Đây là nâng cấp rất lớn trong cách đặt câu hỏi.
3. **Khi theory mạnh, instrument tốt nhất thường là instrument mọc ra từ chính theory.** WTO-entry IV của paper là ví dụ đẹp.
4. **Đo lường latent object không phải điểm yếu nếu nó là phần trung tâm của research design và được dùng nhất quán từ đầu đến cuối.**
5. **Reduced-form result và welfare implication không nên bị tách rời.** Nếu có thể nối chúng bằng một quantitative framework có kỷ luật, giá trị của paper tăng mạnh.
6. **Một kết quả "half-right" thường giàu insight hơn một kết quả hoàn toàn xác nhận hay hoàn toàn bác bỏ trực giác ban đầu.**

## 11. Vietnam relevance and extension

### Vì sao paper này có relevance cho Việt Nam

Việt Nam là case gần như tự nhiên cho câu hỏi của paper:

- tăng trưởng mạnh gắn với hội nhập thương mại sâu
- cơ cấu xuất khẩu đã chuyển lên các ngành phức tạp hơn ở một số giai đoạn
- nhưng mức độ nội địa hóa, capability nội sinh, và learning spillovers vẫn là câu hỏi mở

Nói cách khác, Việt Nam rất phù hợp để hỏi: **xuất khẩu công nghệ cao hơn có thực sự đi kèm capability growth nội địa không, hay chỉ phản ánh assembly trong chuỗi giá trị toàn cầu?**

### Liệu ý tưởng paper có triển khai được ở Việt Nam không

Có, nhưng sẽ cần dữ liệu và framing thực tế hơn ở cấp vi mô hoặc meso.

Những thứ cần có:

- dữ liệu hải quan firm-level hoặc product-level đủ dài
- dữ liệu doanh nghiệp về năng suất, việc làm, wages, ownership, input sourcing
- thông tin về các cú sốc hội nhập hoặc policy shocks đủ ngoại sinh
- nếu muốn đi theo hướng capability, cần proxy tốt hơn cho learning như product switching, supplier upgrading, occupational mix, hoặc domestic value added

### Các trở ngại chính nếu áp dụng ở Việt Nam

1. **Đo capability khó hơn nhiều ở cấp quốc gia nhỏ.** Nền kinh tế Việt Nam vừa hội nhập vừa chịu vai trò lớn của FDI, nên complexity của hàng xuất khẩu có thể không map thẳng vào capability nội địa.
2. **Cú sốc policy ngoại sinh không nhiều và không sạch bằng WTO cross-country setting.** Các FTA, thay đổi tariff, hay các cú sốc China competition cần xử lý cẩn thận.
3. **Vai trò của GVC rất lớn.** Một ngành "phức tạp" ở dữ liệu thương mại chưa chắc là nơi spillover nội địa mạnh nếu khâu giá trị cao nằm ngoài Việt Nam.

### Hướng cập nhật để hợp hơn với Việt Nam

- Chuyển trọng tâm từ country-level capability sang **firm capability** hoặc **province-industry capability**.
- Kết hợp trade data với enterprise surveys để phân biệt giữa:
  - complexity do FDI enclave tạo ra
  - complexity có đi kèm domestic upgrading thật
- Đo "good sectors" không chỉ bằng export complexity mà còn bằng mức lan tỏa sang suppliers nội địa, occupational upgrading, hoặc adoption of standards.

### 1 đến 3 research design có thể phát triển từ paper này trong bối cảnh Việt Nam

1. **China shock và capability upgrading của doanh nghiệp Việt Nam**
   - Hỏi xem cạnh tranh từ Trung Quốc đẩy doanh nghiệp Việt Nam ra khỏi các dòng sản phẩm phức tạp hơn hay buộc họ nâng cấp.
   - Có thể dùng variation theo pre-period product overlap với Trung Quốc.

2. **FTA accession và sectoral complexity shifts**
   - Dùng các hiệp định như CPTPP hoặc EVFTA để xem sectors nào được đẩy lên, rồi nối sang firm productivity, supplier upgrading, hay wage structure.
   - Đây là phiên bản Việt Nam của logic trade-cost shock -> sector mix -> capability growth.

3. **FDI-led exports có tạo dynamic spillovers cho firms nội địa không**
   - Hỏi xem các địa phương/ngành được kéo vào exports phức tạp hơn nhờ FDI có thật sự tích lũy capability nội địa hay không.
   - Kết hợp customs, firm census, và supplier linkages sẽ rất mạnh.

## 12. Vì sao mình chọn paper này trong lượt chạy

Mình chọn paper này vì ba lý do.

Thứ nhất, đây là **top 5 journal** và đúng giao điểm giữa development economics với international trade, một vùng rất quan trọng cho applied work dài hạn.

Thứ hai, paper có một **research design đáng học thật sự**: bắt đầu từ một hình ảnh phát triển rất quen, formalize thành mô hình, xây object đo lường, rồi dùng WTO-entry instruments để đọc ra implication nhân quả.

Thứ ba, paper có **giá trị đặc biệt cho người làm nghiên cứu ở Việt Nam** vì nó buộc ta phân biệt giữa "xuất khẩu trông có vẻ phức tạp hơn" và "năng lực nội sinh thật sự đang tăng lên".

## 13. Ghi chú trung thực về lưu trữ và giới hạn

- Trong lượt chạy này, `analysis.md` và `analysis.html` đã được lưu lên repo GitHub `huylvu/00_reading` tại thư mục `Globalization and the Ladder of Development - Atkin Costinot Fukui/`.
- Mình **chưa coi** PDF gốc của paper là đã lưu trên GitHub chỉ vì đã xác minh được link PDF công khai. Trạng thái đúng là: **đã xác minh nguồn PDF công khai đáng tin cậy, chưa chắc đã lưu được raw PDF binary lên GitHub trong lượt này**.
- `analysis.pdf` không được coi là bắt buộc. Nếu không có tuyến tạo và chuyển file nhị phân đủ chắc, trạng thái cuối phải là **chưa tạo/chưa lưu**.
- Google Drive được **bỏ qua có chủ đích** vì chưa có workflow đủ chắc để tạo Google Doc và tracker trong đúng folder đích mà vẫn giữ báo cáo trung thực.
