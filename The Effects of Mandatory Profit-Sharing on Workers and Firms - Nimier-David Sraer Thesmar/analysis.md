# The Effects of Mandatory Profit-Sharing on Workers and Firms: Evidence from France

- Tác giả: Elio Nimier-David, David Sraer, David Thesmar
- Journal: *The Quarterly Journal of Economics* (accepted manuscript / advance article)
- Năm: 2026
- Ngày agent chạy: 2026-04-26
- Nguồn chính đã xác minh: https://academic.oup.com/qje/advance-article/doi/10.1093/qje/qjag022
- Nguồn PDF dùng để phân tích: https://www.nber.org/system/files/working_papers/w31804/w31804.pdf
- Ghi chú về phiên bản PDF: PDF công khai tốt nhất mình dùng để đọc sâu là NBER Working Paper 31804, bản `Revised August 2025`. Trang QJE xác nhận bài đã xuất hiện dưới dạng accepted manuscript ngày 24/04/2026, nhưng PDF chính thức của QJE không mở công khai trong môi trường này.
- Trạng thái lưu trên GitHub:
  - `analysis.md`: đã lưu
  - `analysis.html`: đã lưu
  - `analysis.pdf`: chưa lưu, vì lượt chạy này không có đường xuất và upload PDF nhị phân đủ chắc chắn để coi là hoàn tất
  - PDF gốc của paper: chưa lưu lên GitHub; mình mới xác minh được nguồn PDF công khai đáng tin cậy và dùng chính nguồn đó để phân tích
- Trạng thái lưu trên Google Drive: bỏ qua trong lượt chạy này để tránh làm nửa vời; lưu trữ chính được thực hiện trên GitHub

## Executive summary

Paper hỏi một câu rất cơ bản nhưng lâu nay khó trả lời sạch: khi nhà nước buộc doanh nghiệp chia một phần lợi nhuận cho người lao động, ai thực sự hưởng lợi và doanh nghiệp có bị méo mó mạnh hay không? Bối cảnh là nước Pháp, nơi từ năm 1967 các công ty trên 100 lao động phải chia một phần “excess profits” cho nhân viên; từ năm 1991 ngưỡng này hạ từ 100 xuống 50 lao động.

Điểm hay của paper là tác giả khai thác đúng cú thay đổi ngưỡng này để tạo ra một thiết kế quasi-experiment rất thuyết phục. Họ kết hợp dữ liệu hành chính cấp doanh nghiệp với dữ liệu employer-employee linked data để nhìn được cả phía firm lẫn phía worker. Kết luận trung tâm là mandatory profit-sharing chủ yếu là một công cụ phân phối lại lợi nhuận từ chủ sở hữu sang người lao động, đặc biệt là lao động kỹ năng thấp và trung bình, chứ không phải một công cụ làm tăng năng suất. Labor share tăng khoảng 1.8 điểm phần trăm, profit share giảm khoảng 1.4 điểm phần trăm, nhưng đầu tư và productivity hầu như không đổi.

Bài đáng đọc vì nó nói rất rõ một điều hay bị lẫn trong tranh luận chính sách: một chính sách “share profits with workers” không nhất thiết hoạt động qua kênh khuyến khích năng suất. Nó có thể chủ yếu là một dạng thuế tương đối ít méo mó đánh vào lợi nhuận rồi chuyển trực tiếp cho lao động trong cùng doanh nghiệp. Với applied micro, đây là một paper rất đẹp về cách nối labor, public finance, firm behavior, và incidence trong cùng một design.

## Research question and motivation

### Câu hỏi nghiên cứu trung tâm

Paper theo đuổi ba câu hỏi gắn với nhau:

1. Mandatory profit-sharing có thực sự làm tăng thu nhập của người lao động, hay doanh nghiệp chỉ bù trừ bằng cách giảm lương cơ bản?
2. Chính sách này có làm tăng productivity nhờ “align incentives” giữa worker và owner hay không?
3. Nếu chính sách làm tăng chi phí doanh nghiệp, doanh nghiệp phản ứng như thế nào: giảm đầu tư, né ngưỡng quy định, hay điều chỉnh theo cách khác?

### Bối cảnh học thuật và thực tiễn

Lập luận ủng hộ profit-sharing thường dựa trên hai ý. Một là fairness: khi doanh nghiệp có lợi nhuận cao, người lao động nên cùng hưởng. Hai là efficiency: nếu compensation gắn với lợi nhuận thì worker sẽ nỗ lực hơn, ít vắng mặt hơn, ít xung đột hơn, và cuối cùng năng suất tăng. Vấn đề là hầu hết bằng chứng trước đây dựa trên quan sát tự chọn: doanh nghiệp nào tự nguyện dùng profit-sharing có thể vốn đã khác doanh nghiệp không dùng.

Paper nhấn mạnh hai khó khăn lớn của văn liệu cũ. Thứ nhất là endogeneity trong việc doanh nghiệp chọn có áp dụng profit-sharing hay không. Thứ hai là data limitation: để nghiên cứu nghiêm túc cần ghép được thông tin profit-sharing với dữ liệu kế toán cấp firm và, tốt hơn nữa, dữ liệu cấp worker.

### Khoảng trống paper muốn lấp vào

Khoảng trống chính là thiếu bằng chứng quasi-experimental quy mô lớn về incidence và real effects của profit-sharing bắt buộc. Paper này lấp vào khoảng trống đó bằng cách khai thác một reform rất phù hợp cho causal inference và dùng dữ liệu hành chính đủ rộng để không rơi vào vấn đề sample nhỏ.

## Main contribution

### 1. Đóng góp về identification

Đóng góp lớn nhất là biến một thay đổi ngưỡng chính sách của Pháp thành một thí nghiệm tự nhiên. Việc ngưỡng bắt buộc giảm từ 100 xuống 50 lao động năm 1991 tạo ra một treatment group rất tự nhiên: các firm cỡ vừa trước reform trở thành firm bắt buộc phải chia lợi nhuận sau reform.

### 2. Đóng góp về dữ liệu

Paper dùng universe of corporate tax files có chứa trực tiếp thông tin profit-sharing và ghép với linked employer-employee panel covering khoảng 4% lực lượng lao động khu vực tư. Nhờ vậy, tác giả không chỉ nói được “firm trả nhiều hơn” mà còn nói được “ai trong firm hưởng lợi”.

### 3. Đóng góp về nội dung kinh tế

Kết quả của paper đặt lại trọng tâm tranh luận. Chính sách này không cho thấy tác động năng suất đáng kể. Thay vào đó, nó hoạt động chủ yếu như một công cụ phân phối lại trong nội bộ firm, với lợi ích tập trung vào lao động kỹ năng thấp và trung bình. Đây là một kết quả rất quan trọng vì nó tách bạch rõ equity effect và efficiency effect.

### 4. Đóng góp về policy design

Paper cũng chỉ ra rằng profit-sharing bắt buộc khác corporate income tax ở vài điểm quan trọng. Vì worker có động cơ theo dõi lợi nhuận báo cáo khi thu nhập của họ gắn với nó, avoidance ở intensive margin có thể thấp hơn ta tưởng. Ngược lại, avoidance xuất hiện mạnh hơn ở extensive margin, tức là doanh nghiệp né ngưỡng quy mô.

## Identification or methodology

## Bối cảnh thể chế

Luật của Pháp yêu cầu firm trên ngưỡng quy mô phải dành một khoản `RSP` để chia cho worker. Công thức cốt lõi lấy một phần excess profits, tức là lợi nhuận ròng vượt quá 5% book equity, rồi scale theo labor share của firm. Paper nhấn mạnh intuition của công thức này: 5% được xem như “mức lợi nhuận công bằng” cho shareholder; phần vượt trên mức đó thì worker cũng nên được hưởng.

Tác giả hiệu chỉnh đơn giản và cho thấy đây là một policy khá lớn về lượng: với median firm, mandatory profit-sharing tương đương khoảng 9.5% pre-tax income; trong dữ liệu, với firm subject to regulation và có excess profits dương, khoản này trung bình bằng khoảng 10.5% pre-tax income.

## Thiết kế nhận dạng chính

Paper không dùng RD quanh ngưỡng vì firm có thể chủ động kiểm soát vị trí của mình quanh threshold. Thay vào đó, paper dùng intent-to-treat difference-in-differences.

### Treatment và control

- Treatment group: firm có 55-85 lao động trong 1989-1990. Nếu không đổi mạnh employment, các firm này sẽ bắt đầu bị bắt buộc share profits sau reform 1991.
- Small control group: firm có 35-45 lao động, khó bị quy định chạm tới.
- Large control group: firm có 120-300 lao động, đã nằm trên ngưỡng cả trước lẫn sau reform.

Tác giả cố ý loại firm quá gần ngưỡng 50 và 100 để tránh contamination từ né luật hoặc bunching nội sinh.

### Assumption cốt lõi

Giả định chính là parallel trends: nếu không có reform, outcomes của nhóm 55-85 sẽ diễn biến tương tự hai nhóm control. Paper cho thấy trước 1991 các trend giữa treated và controls nhìn khá song song cho các outcomes chính.

### Vì sao design này mạnh

- Có cú policy shock rõ về thời gian: 1991.
- Có treatment intensity khá sạch theo quy mô doanh nghiệp trước reform.
- Có hai control groups ở hai phía quy mô để giảm lo ngại rằng kết quả chỉ phản ánh size-specific business cycle effects.
- Có thể dùng shock này làm instrument cho actual profit-sharing trong TSLS để đi từ ITT sang LATE cho compliers.

## Bunching analysis

Trước khi vào DiD, paper làm một revealed-preference exercise rất hay: nếu policy này thật sự có lợi cho firm, ta không nên thấy firm cố ở dưới ngưỡng. Nhưng dữ liệu cho thấy trước reform có excess density 22.3% ở khoảng 95-99 lao động, và bunching này biến mất sau khi ngưỡng hạ xuống 50. Điều này là bằng chứng trực tiếp rằng firm nhìn mandatory profit-sharing như một chi phí ròng đáng kể.

Paper còn kiểm tra xem bunching là “thật” hay chỉ do under-reporting employment:

- Không thấy discontinuity của labor cost per employee quanh ngưỡng 100.
- So sánh với measure employment từ payroll tax data cho thấy không có bằng chứng under-reporting đủ lớn để giải thích toàn bộ bunching.
- Firm ngay dưới ngưỡng còn có profitability cao hơn, phù hợp với câu chuyện firm profitable có động cơ né luật mạnh hơn.

Đây là một phần rất đẹp vì nó không chỉ hỗ trợ identification, mà còn tự nó trả lời một câu hỏi kinh tế quan trọng: policy có tạo ra distortion ở margin nào.

## Outcomes và cơ chế ước lượng

Paper xét:

- profit-sharing response
- labor share, wage share, total compensation share, profit share
- productivity như TFP
- investment, capital growth, capital-labor ratio
- softer outcomes như sick days và extra hours
- worker-level wages và total compensation theo nhóm kỹ năng

Ngoài reduced-form DiD, tác giả còn dùng TSLS để ước lượng tác động của actual profit-sharing, và thêm triple-difference theo mức excess profits trước reform để đo “exposure” dị biệt của firm đối với policy.

## Điểm mạnh và điểm dễ bị nghi ngờ

### Điểm mạnh

- Policy shock rất rõ và hợp logic kinh tế.
- Kết hợp firm-level và worker-level data.
- Có hai control groups thay vì một.
- Có bunching evidence như một validation mạnh cho economic bite của regulation.
- Có cả reduced-form, IV, và triple-difference, nên không chỉ dựa vào một specification duy nhất.

### Điểm dễ bị nghi ngờ hoặc cần cẩn trọng

- Vì treatment gắn với size thresholds, luôn còn lo ngại size-related confounders.
- ITT không đo được long-run equilibrium effects quá xa; chính tác giả thừa nhận hạn chế này.
- Worker-level data không quan sát trực tiếp khoản profit-sharing nhận được cho từng worker, nên phải suy từ wage và total compensation ở level phù hợp.
- Một số diễn giải về wage rigidity là hợp lý nhưng vẫn là diễn giải cơ chế, không phải chứng minh cơ chế hoàn toàn trực tiếp.

## Results and interpretation

## 1. Policy thực sự làm profit-sharing tăng

Sau reform, tỷ lệ firm treated báo cáo profit-sharing dương tăng mạnh, từ khoảng 10% trước 1990 lên khoảng 40% sau đó, trong khi hai nhóm control không có break tương tự. Đây là first-stage rất mạnh.

## 2. Incidence ở cấp firm: worker hưởng, owner chịu

Kết quả headline là total compensation share tăng khoảng 1.8 điểm phần trăm. Wage share không tăng tương ứng, nghĩa là phần tăng này đến từ profit-sharing bổ sung, không phải lương cơ bản. Đồng thời profit share giảm khoảng 1.4 điểm phần trăm. Trong phần kết luận, paper nhấn mạnh hơn 3/4 phần tăng labor cost được gánh bởi owner thông qua profits thấp hơn.

Diễn giải kinh tế ở đây rất quan trọng: nếu firm có thể hoàn toàn bù trừ bằng cách hạ base wages, ta đã không thấy total compensation của worker tăng và profit share của owner giảm mạnh như vậy. Paper cho thấy incidence chủ yếu rơi vào shareholder, không phải worker.

## 3. Không có bằng chứng productivity gains đáng kể

Một trong những lập luận kinh điển ủng hộ profit-sharing là worker sẽ nỗ lực hơn. Nhưng paper không thấy điều này:

- TFP không tăng một cách có ý nghĩa thống kê.
- Sick days không giảm.
- Xác suất làm extra hours không tăng.

Tức là kênh “alignment of interests” trong bối cảnh này dường như yếu hơn nhiều so với rhetoric chính sách.

## 4. Không có bằng chứng đầu tư giảm mạnh

Paper cũng không tìm thấy tác động rõ lên investment ratio, capital growth, hay capital-labor ratio. Các point estimates thường hơi âm nhưng nhỏ và không có ý nghĩa thống kê. Điều này cũng hợp với simple model calibration của paper: wedge lên user cost of capital chỉ cỡ 0.43 điểm phần trăm, tức rất nhỏ tương đối so với standard user cost.

Thông điệp là policy này không tạo ra cú bóp méo đầu tư lớn trong intensive margin của firm đã ở trên ngưỡng.

## 5. Distortion nằm ở extensive margin: né ngưỡng quy mô

Trong khi intensive margin khá yên, extensive margin lại phản ứng thật. Firm quanh ngưỡng 100 trước reform và quanh ngưỡng 50 sau reform có xác suất ở lại dưới ngưỡng hoặc rơi xuống dưới ngưỡng cao hơn sau khi regulation bắt đầu ràng buộc. Tức là policy tạo incentive cho firm tránh lớn lên quá một mốc nào đó.

Đây là một kết quả rất đáng nhớ: cùng một chính sách có thể “non-distortive” trong investment/productivity conditional on being treated, nhưng lại distort firm size distribution ở margin entry/expansion quanh threshold.

## 6. Dị biệt theo kỹ năng: đây là phần hay nhất của paper

Worker-level analysis cho thấy bức tranh rất không đồng nhất:

- High-skill workers có base wage giảm để bù gần như hết phần profit-sharing họ nhận.
- Low-skill và medium-skill workers không bị base wage offset tương tự.
- Trong TSLS, profit-sharing làm total compensation tăng khoảng 3.5% cho toàn bộ worker sample.
- Hiệu ứng tích cực này tập trung ở low- and medium-skill workers; với average high-skill worker, tác động lên total compensation không khác 0 về mặt thống kê.

Đây là một kết quả cực quan trọng. Nó cho thấy cùng một policy “chia lợi nhuận cho worker” nhưng không phải worker nào cũng hưởng như nhau. Trong institutional setting của Pháp, phần tiến bộ của policy đến từ chỗ wage rigidity mạnh hơn ở đáy phân phối kỹ năng.

## What is special or elegant about the paper

Có ít nhất năm điểm khiến paper này rất đẹp.

### 1. Nó nối một policy rất “thể chế” với một câu hỏi incidence rất cơ bản

Paper không hỏi một câu hào nhoáng. Nó hỏi ai thực sự được lợi khi buộc firm chia profits. Nhưng nhờ chọn đúng setting, câu hỏi đơn giản này trở thành một đóng góp rất có trọng lượng.

### 2. Bunching không chỉ là kiểm tra phụ, mà là một phần của lập luận kinh tế

Nhiều paper coi bunching như ancillary evidence. Ở đây, bunching trực tiếp trả lời liệu firm có xem policy là costly hay không. Nó làm cho phần institutional economics và revealed preference gắn chặt vào nhau.

### 3. Thiết kế rất “applied micro đúng chất”

Không cố nhồi một mô hình quá nặng. Không cố diễn giải mọi thứ bằng một con số duy nhất. Họ đi từ institution -> descriptive economic bite -> DiD -> IV -> heterogeneity -> interpretation. Nhịp paper rất chặt.

### 4. Kết quả chính là một kết quả “anti-romantic”

Policy không làm miracles. Nó không boost productivity. Nhưng nó vẫn có giá trị vì phân phối lại lợi nhuận tương đối trực tiếp và ít méo ở nhiều margin. Đây là loại kết quả rất đáng tin vì nó không cố kể một câu chuyện quá đẹp.

### 5. Paper dạy cách đọc distortion theo nhiều margin

Một bài học nghiên cứu rất hay ở đây là đừng hỏi “policy có distort hay không” theo nghĩa chung chung. Hãy hỏi distort ở margin nào. Paper cho thấy intensive margin và extensive margin có thể cho hai câu trả lời rất khác nhau.

## Required background knowledge

## 1. Incidence trong public finance và labor economics

Để hiểu paper, cần nắm khái niệm incidence: về mặt pháp lý policy có thể buộc firm trả, nhưng về mặt kinh tế burden cuối cùng có thể rơi vào worker, shareholder, consumer, hay một kết hợp. Ở đây câu hỏi incidence là liệu profit-sharing có được bù trừ bằng lower wages hay không.

## 2. Difference-in-differences

DiD so sánh thay đổi theo thời gian giữa nhóm bị tác động và nhóm không bị tác động. Mấu chốt là giả định parallel trends: nếu không có reform, outcomes của hai nhóm sẽ biến động giống nhau.

## 3. Intent-to-treat và LATE / TSLS

Không phải mọi firm trong treatment bucket sau reform đều thực sự chia lợi nhuận với cùng cường độ. Vì vậy paper báo cáo cả ITT và IV/LATE. ITT đo tác động của việc “bị đưa vào vùng policy”. LATE đo tác động trên compliers, tức các firm thật sự thay đổi behavior vì policy shock.

## 4. Bunching

Bunching là hiện tượng density của một biến nhảy vọt ngay dưới một ngưỡng chính sách. Trong applied micro, bunching thường được dùng để phát hiện phản ứng tối ưu hóa khi có kink/notch hoặc size-dependent regulation.

## 5. Wage rigidity

Wage rigidity là việc lương, nhất là lương cơ bản, không điều chỉnh linh hoạt xuống dưới dù firm có incentive làm vậy. Ở Pháp, paper lập luận rigidity cao do collective agreements phủ rộng và minimum wage ràng buộc. Đây là chìa khóa để hiểu vì sao low-skill workers thực sự hưởng lợi.

## 6. Extensive margin versus intensive margin

- Extensive margin ở đây là quyết định giữ firm dưới threshold quy mô.
- Intensive margin là điều chỉnh profits, wages, investment, productivity conditional on hoạt động ở một size nhất định.

Phân biệt hai margin này là cốt lõi để hiểu toàn bộ paper.

## Limitations and open questions

### 1. Long-run effects chưa được chốt hoàn toàn

Paper khá thuyết phục về short- và medium-run, nhưng với very long-run equilibrium effects thì chính tác giả cũng dè dặt. Theo thời gian, firm có thể đổi size bucket, thay composition lao động, hay thay contracting practices theo cách ITT khó theo dõi trọn vẹn.

### 2. Cơ chế wage rigidity chủ yếu là diễn giải hợp lý

Paper có bằng chứng dị biệt theo skill rất phù hợp với wage rigidity, nhưng đó vẫn chưa phải kiểm định cơ chế trực tiếp ở cấp bargaining table hay contract-level clauses.

### 3. External validity phụ thuộc thể chế lao động

Kết quả có thể rất khác trong môi trường lao động linh hoạt hơn Pháp. Ở nơi wage-setting mềm hơn, firm có thể offset profit-sharing mạnh hơn, làm worker hưởng ít hơn.

### 4. Policy evaluation chưa bao trùm mọi welfare margin

Paper rất mạnh về wages, profits, investment, productivity, nhưng ít hơn ở các margin như turnover chất lượng cao, morale lâu dài, intra-firm cooperation, hay political economy của worker voice.

### 5. Threshold effects luôn gợi câu hỏi về firm dynamics

Nếu policy tạo động cơ tránh tăng quy mô, câu hỏi mở là chi phí aggregate của misallocation này lớn đến đâu trong dài hạn, nhất là khi nhiều regulation khác cũng gắn với thresholds.

## Takeaways for a researcher

1. Nếu muốn thuyết phục về incidence, chỉ nhìn wage bill ở cấp firm thường chưa đủ; linked employer-employee data cho phép thấy ai trong firm thực sự hưởng lợi.
2. Một policy có thể rất ít méo ở intensive margin nhưng vẫn tạo distortion đáng kể ở extensive margin. Đừng gộp mọi margin vào một kết luận chung chung.
3. Bunching evidence có thể làm nhiều hơn vai trò “descriptive appendix”; nó có thể là một phần trung tâm của economic argument.
4. Khi treatment gắn với size thresholds, dùng hai control groups ở hai phía quy mô là một cách rất hay để giảm lo ngại rằng bạn chỉ đang nhặt size trends.
5. Heterogeneity theo skill hay bargaining power thường không phải phần phụ. Trong paper này, đó là nơi bản chất phân phối của policy lộ ra rõ nhất.
6. Câu chuyện cơ chế nên bám chặt vào institutions. Ở đây wage rigidity không phải một buzzword; nó gắn với minimum wage, collective agreements, và bối cảnh lao động Pháp.
7. Một paper applied micro rất mạnh không nhất thiết cần kết quả “positive” về efficiency. Một null result đáng tin về productivity đôi khi lại chính là đóng góp lớn nhất.

## Vietnam relevance and extension

## Paper này có liên quan gì tới Việt Nam?

Rất có. Việt Nam cũng là một nền kinh tế nơi tranh luận về “chia sẻ thành quả tăng trưởng”, thưởng theo hiệu quả, và quan hệ giữa tiền lương với lợi nhuận doanh nghiệp vẫn rất sống động. Dù không có một chế độ mandatory profit-sharing giống Pháp, ý tưởng cốt lõi của paper chạm đúng những câu hỏi lớn ở Việt Nam:

- Khi doanh nghiệp tăng lợi nhuận, người lao động có được hưởng không?
- Các khoản thưởng, chia sẻ lợi nhuận, hay quỹ phúc lợi có thay thế cho lương cơ bản hay không?
- Chính sách buộc doanh nghiệp chia sẻ lợi ích có làm méo đầu tư hoặc quy mô doanh nghiệp không?

## Có thể triển khai ý tưởng này ở Việt Nam không?

Có thể, nhưng phải chọn setting khéo.

### Những điều kiện cần có

- Dữ liệu doanh nghiệp đủ chi tiết về lao động, quỹ lương, lợi nhuận, và ideally panel theo thời gian
- Nếu muốn làm mạnh như paper này, cần linked employer-employee data hoặc ít nhất dữ liệu payroll ở cấp người lao động
- Một policy shock rõ: ví dụ thay đổi quy định về thưởng, quỹ khen thưởng-phúc lợi ở khu vực DNNN, thay đổi luật lao động, hay thay đổi ngưỡng/quy tắc áp dụng chế độ chia sẻ lợi ích

### Trở ngại chính

- Dữ liệu linked employer-employee ở Việt Nam khó tiếp cận hơn nhiều
- Compensation ngoài lương cơ bản có thể ghi nhận không chuẩn hoặc không đầy đủ
- Compliance và reporting quality có thể thấp hơn, khiến distinction giữa real adjustment và misreporting khó hơn
- Nếu không có shock thể chế đủ rõ, causal identification sẽ yếu

## Các hướng mở rộng phù hợp với Việt Nam

### 1. Profit-sharing và wage incidence trong doanh nghiệp nhà nước hoặc doanh nghiệp cổ phần hóa

Một câu hỏi rất hợp Việt Nam là sau cổ phần hóa hay sau thay đổi quy chế thưởng, phần lợi nhuận giữ lại và phần trả cho lao động thay đổi thế nào, và ai hưởng trong firm.

### 2. Thưởng cuối năm, productivity bonuses, và wage rigidity ở khu công nghiệp

Ở các khu công nghiệp, rất nhiều khoản thu nhập ngoài lương cơ bản tồn tại dưới dạng thưởng, phụ cấp, hay bonus gắn với hiệu quả. Một research design tốt có thể hỏi liệu các khoản này bổ sung hay thay thế lương cơ bản, đặc biệt ở nhóm lao động lương thấp.

### 3. Size-dependent regulation và bunching của doanh nghiệp Việt Nam

Paper gợi một câu hỏi lớn hơn: bất kỳ quy định nào gắn theo ngưỡng lao động hay doanh thu ở Việt Nam có tạo bunching không? Nếu có, distortion aggregate lớn tới đâu?

## 3 research questions có thể phát triển từ paper này trong bối cảnh Việt Nam

1. Khi doanh nghiệp bị ràng buộc bởi một quy định mới về thưởng hoặc phúc lợi lao động, thu nhập thực của lao động có tăng hay doanh nghiệp bù lại bằng cách điều chỉnh lương cơ bản?
2. Các quy định lao động hoặc bảo hiểm gắn với ngưỡng số lao động có khiến doanh nghiệp Việt Nam bunch dưới ngưỡng hay không?
3. Các khoản thưởng hiệu quả ở doanh nghiệp sản xuất xuất khẩu có làm tăng năng suất thực sự, hay chủ yếu là công cụ phân phối lại rents trong firm?

## Vì sao mình chọn paper này hôm nay

Mình chọn paper này vì ba lý do. Thứ nhất, đây là một bài top 5 rất mới: trang QJE ghi accepted manuscript ngày 24/04/2026. Thứ hai, nó nằm đúng giao điểm của applied micro, labor, public finance, và firm behavior. Thứ ba, đây là loại paper có bài học phương pháp rất rõ cho người làm nghiên cứu: institutional detail tốt, identification sạch, heterogeneity có ý nghĩa kinh tế, và kết luận chính sách không bị phóng đại.

## Nguồn tham chiếu chính đã dùng

1. Trang bài báo QJE: https://academic.oup.com/qje/advance-article/doi/10.1093/qje/qjag022
2. PDF công khai dùng để đọc sâu: https://www.nber.org/system/files/working_papers/w31804/w31804.pdf
3. Trang NBER xác minh metadata working paper: https://www.nber.org/papers/w31804