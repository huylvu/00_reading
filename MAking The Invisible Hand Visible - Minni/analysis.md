# MAking The Invisible Hand Visible: Managers and The Allocation of Workers to Jobs

- **Tác giả:** Virginia Minni
- **Journal:** The Quarterly Journal of Economics
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-05
- **Nguồn bài báo chính:** https://academic.oup.com/qje/advance-article/doi/10.1093/qje/qjag017/8537773
- **Nguồn PDF tốt nhất đã xác minh:** PDF accepted manuscript open access trên trang QJE của bài báo ở link nguồn chính, có nút PDF và mô tả rõ là accepted manuscript, published ngày 23 March 2026.
- **Nguồn PDF công khai dùng để đọc sâu:** BFI Working Paper No. 2025-122, September 2025: https://bfi.uchicago.edu/wp-content/uploads/2025/09/BFI_WP_2025-122.pdf
- **Nguồn PDF đối chiếu thêm:** IZA Discussion Paper 18137, September 2025: https://docs.iza.org/dp18137.pdf
- **Trạng thái lưu trên GitHub khi bắt đầu soạn:** sẽ lưu bắt buộc `analysis.md`; ưu tiên lưu thêm `analysis.html`; chỉ coi `analysis.pdf` là hoàn tất nếu vừa tạo được file PDF hợp lệ vừa upload được file đó; PDF gốc của paper chỉ coi là hoàn tất nếu tải và upload được file nhị phân thật.
- **Trạng thái Google Drive:** bỏ qua trong lượt này, vì chưa có tuyến tạo Google Doc và tracker đúng folder đích một cách nhất quán trong cùng lượt chạy.

## Executive summary

Paper này hỏi một câu rất căn bản nhưng thường bị bỏ qua trong labor và economics of organizations: vì sao manager lại quan trọng cho hiệu quả của doanh nghiệp. Câu trả lời của Virginia Minni không phải chỉ là manager giỏi tạo động lực tốt hơn hay giám sát chặt hơn. Luận điểm chính của bài là manager giỏi giúp **ghép đúng người vào đúng việc** trong thị trường lao động nội bộ của công ty, và chính việc phân bổ lại này tạo ra tác động dài hạn lên lương, thăng tiến, và năng suất.

Để trả lời câu hỏi đó, tác giả dùng dữ liệu nhân sự hành chính cực hiếm của một tập đoàn đa quốc gia lớn: hơn 200.000 nhân viên white-collar, 30.000 manager, trong 11 năm và 100 quốc gia. Bà đo "manager giỏi" bằng tốc độ thăng tiến của chính manager trong doanh nghiệp, rồi khai thác các đợt luân chuyển manager giữa các team để tạo biến thiên gần như ngoại sinh về việc một worker bất ngờ được chuyển sang báo cáo cho manager giỏi hay không.

Kết quả chính rất mạnh. Một lần được làm việc với high-flyer manager làm tăng lateral moves trong nội bộ công ty khoảng 40% sau 7 năm, tăng số lần tăng salary grade thêm 0,17, tương đương mức lương cao hơn khoảng 13%, tăng xác suất lên vị trí quản lý khoảng 31%, và với nhóm sales thì bonus chuẩn hóa tăng khoảng 0,35 độ lệch chuẩn. Điểm rất đáng chú ý là khi worker rời high-flyer manager thì hiệu ứng không đảo ngược. Điều này ủng hộ cơ chế "allocation/matching" hơn là cơ chế "motivation/monitoring".

Vì sao bài đáng đọc? Vì nó mở "hộp đen" bên trong doanh nghiệp bằng một design rất đẹp, biến một câu chuyện tưởng như mềm về talent management thành causal evidence khá sắc. Đây là paper rất đáng học cho applied micro về labor, personnel economics, và cả misallocation.

## Research question and motivation

### Câu hỏi nghiên cứu trung tâm

Manager tạo ra giá trị cho doanh nghiệp bằng kênh nào, và cụ thể hơn, liệu manager giỏi có cải thiện kết quả nghề nghiệp của worker chủ yếu nhờ **phân bổ worker vào job phù hợp hơn trong nội bộ firm** hay không?

### Bối cảnh học thuật và thực tiễn

Kinh tế học lao động truyền thống tập trung nhiều vào matching giữa worker và firm trên thị trường lao động bên ngoài. Nhưng phần lớn đời sống nghề nghiệp của lao động trong các tập đoàn lớn lại diễn ra **bên trong doanh nghiệp**, nơi manager chứ không phải price mechanism quyết định ai làm việc gì, ở team nào, trên dự án nào, và khi nào nên chuyển.

Điều này nối paper với ba mạch văn liệu lớn:

1. Văn liệu về internal labor markets, vốn mô tả khá rõ chuyện lương và chuyển việc nội bộ nhưng còn thiếu bằng chứng nhân quả về vai trò của manager.
2. Văn liệu về manager effects, nơi nhiều bài đã cho thấy manager khác nhau tạo ra outcome khác nhau cho worker, nhưng thường khó tách bạch manager giỏi vì allocation hay vì incentives/monitoring.
3. Văn liệu rộng hơn về misallocation, nơi việc phân bổ sai lao động sang task không phù hợp có thể làm mất năng suất ngay cả khi firm không sa thải hay tuyển mới.

### Khoảng trống mà paper muốn lấp vào

Paper nói rất rõ một khoảng trống: chúng ta biết manager matter, nhưng chưa biết đủ rõ **manager matter because they match workers to jobs**. Muốn kiểm định điều này phải có cùng lúc ba thứ rất khó:

1. Dữ liệu nhân sự đủ chi tiết để nhìn được career trajectories ngang và dọc trong firm.
2. Một measure của manager quality không dựa trực tiếp trên outcome của worker mà manager đang quản lý.
3. Một nguồn biến thiên đủ thuyết phục về việc worker gặp manager nào.

Paper này có cả ba.

## Main contribution

### 1. Đóng góp khái niệm

Đây là đóng góp quan trọng nhất. Paper đặt trọng tâm vào **allocation of workers to jobs inside the firm** như một cơ chế nền tảng của manager effects. Đây là một thay đổi góc nhìn khá mạnh. Thay vì hỏi manager có ép effort tốt hơn không, bài hỏi manager có giúp doanh nghiệp "khám phá" và "đặt" đúng kỹ năng của worker vào đúng vị trí không.

### 2. Đóng góp dữ liệu

Dữ liệu là một tài sản lớn của paper:

1. Universe của hơn 224.000 regular full-time white-collar workers.
2. Khoảng 30.000 manager.
3. Panel 11 năm, 100 quốc gia.
4. Dữ liệu nối worker với manager theo thời gian.
5. Dữ liệu lương, bonus, salary grade, promotion, lateral moves, exits.
6. Dữ liệu phụ về sales productivity, time use từ Microsoft, skill platform nội bộ, flexible project platform, và phỏng vấn định tính.

Với standards của personnel economics, đây là một data environment rất hiếm.

### 3. Đóng góp nhận dạng

Paper dùng tốc độ thăng tiến của manager để định nghĩa high-flyer manager và nhấn mạnh lợi thế của cách đo này: measure được xác định **ex ante**, trước khi manager gặp worker, và ở một unit khác với unit mà worker đang ở. Điều đó giúp tránh circularity kiểu "manager giỏi là manager có worker outcome tốt".

Sau đó paper dùng các đợt manager rotation giữa các team như một quasi-experiment. Đây là bước then chốt đưa bài từ descriptive personnel data sang causal inference.

### 4. Đóng góp cho labor và organization economics

Paper cho thấy internal reallocation có thể tạo ra gains lớn mà không cần firing, hiring, hay training lớn ngay lập tức. Ý tưởng này rất quan trọng vì nó nói rằng một phần productivity gains đến từ **tái bố trí nguồn lực sẵn có** chứ không phải luôn từ đầu tư mới.

## Identification or methodology

### Bối cảnh thể chế

Doanh nghiệp trong bài là một consumer-goods multinational rất lớn, có cấu trúc phân cấp từ work-level 1 đến work-level 6. Nhân viên ở work-level 2 trở lên được xem là có vai trò quản lý. Trong công ty này có chính sách luân chuyển manager lateral giữa các team trong cùng sub-function để manager tích lũy kinh nghiệm đa dạng và để firm sàng lọc ai sẽ tiếp tục lên level cao hơn.

Điều này tạo ra môi trường khá đặc biệt: worker không ngẫu nhiên bị xáo trộn giữa firm, nhưng manager có thể được chuyển ngang giữa các team theo một logic tương đối độc lập với outcome trước đó của từng worker cụ thể.

### Đo manager quality

Manager giỏi được đo bằng việc họ có phải **high-flyer** hay không, tức được thăng lên work-level 2 ở độ tuổi rất trẻ so với chuẩn của firm. Trực giác của tác giả là tốc độ thăng tiến là một proxy holistic cho việc firm đánh giá manager đó là đặc biệt mạnh.

Ưu điểm của measure này:

1. Không định nghĩa manager quality bằng outcome của subordinate.
2. Được xác lập trước khi manager quản lý worker đang phân tích.
3. Có tương quan dương với các chỉ dấu performance ex post như tăng lương tương lai, xác suất lên level 3, performance ratings, và upward feedback từ worker.

Điểm yếu cần nhớ là đây vẫn là proxy. Có thể có measurement error, và chính tác giả nói nếu proxy nhiễu thì kết quả nhiều khả năng bị bias về 0 hơn là bị thổi phồng.

### Chiến lược nhận dạng

Chiến lược chính là event study quanh **first manager transition** của worker. Tác giả chỉ giữ những chuyển đổi manager đến từ manager rotation ngang giữa teams, không dùng những thay đổi do worker được thăng chức, worker transfer, hay manager được đôn lên vị trí khác.

Các transition types được chia thành:

1. LtoH: từ low-flyer sang high-flyer manager.
2. LtoL: từ low-flyer sang low-flyer manager.
3. HtoL: từ high-flyer sang low-flyer manager.
4. HtoH: từ high-flyer sang high-flyer manager.

Hiệu ứng chính được đo bằng:

1. `LtoH - LtoL` cho tác động của việc **gain a high-flyer manager**.
2. `HtoL - HtoH` cho tác động của việc **lose a high-flyer manager**.

Mô hình có worker fixed effects và year-month fixed effects, với standard errors cluster ở level manager. Cửa sổ event study chạy từ 24 tháng trước đến 84 tháng sau transition.

### Giả định cốt lõi

Giả định trung tâm là trước transition, worker trong các nhóm transition khác nhau đi trên quỹ đạo outcome tương tự nhau, tức pre-trends song song. Paper thuyết phục ở chỗ không chỉ nói bằng lời mà kiểm tra trực tiếp:

1. Pre-trends của lateral moves và salary-grade increases trước event nhìn rất phẳng.
2. Past team performance, inequality, transfer rates, team diversity trong 2 năm trước đó không dự báo được incoming manager type.
3. Không có bằng chứng rõ rằng share of high-flyers chỉ phản ánh local positive shocks ở cấp establishment hay function-country.

### Vì sao design này khá đẹp

Đây không phải random assignment thuần, nên vẫn cần cẩn trọng. Nhưng nó có hai điểm rất mạnh:

1. Manager quality được đo ex ante ở đơn vị khác, nên bớt lo reverse causality.
2. Transition đến từ rotation policy của firm, nên bớt lo direct sorting của worker vào manager giỏi.

### Điểm dễ bị nghi ngờ

1. Rotation không phải do đồng xu quyết định, nên sorting tinh vi vẫn có thể tồn tại ở mức nào đó.
2. High-flyer measure có thể trộn lẫn innate talent với political skill hay fit với văn hóa công ty.
3. External validity tự nhiên bị giới hạn bởi đây là một large MNE white-collar setting.

Nhưng với dữ liệu loại này, design của paper là rất thuyết phục.

## Results and interpretation

### 1. High-flyer managers làm tăng lateral reallocation trong nội bộ firm

Kết quả rõ nhất là worker được chuyển từ low-flyer sang high-flyer manager có nhiều lateral moves hơn. Sau 28 quarters, số lateral moves cao hơn **0,10**, tương đương **40% tăng** so với nhóm đối chứng `LtoL`.

Điểm mình thấy hay ở đây là tác giả không chỉ dừng ở số moves. Bài cho thấy:

1. Không phải một vài worker đổi việc liên tục, mà là nhiều worker có xác suất làm ít nhất một lateral move cao hơn.
2. Moves tăng ở nhiều margin: within team, across teams within function, và across functions.
3. Cross-functional moves xuất hiện chậm hơn, phù hợp với việc chi phí điều chỉnh lớn hơn.

Diễn giải kinh tế: high-flyer managers không chỉ đẩy worker sang chỗ khác cho bớt tắc nghẽn. Họ dường như biết mở đường để worker khám phá vị trí mới phù hợp hơn với kỹ năng.

### 2. Các lateral moves này là moves có ý nghĩa về task, không chỉ đổi tên job

Paper còn đi xa hơn bằng cách đo **task distance** giữa job cũ và job mới bằng data O*NET về cường độ cognitive, routine, social tasks. Sau manager change, cumulative task distance tăng dần và có ý nghĩa sau khoảng 7 quý.

Ý nghĩa của kết quả này là lateral reallocation ở đây không phải cosmetic reshuffling. Worker thực sự dịch chuyển sang công việc khác hơn về mặt nội dung kỹ năng.

### 3. Không có bằng chứng worker bị "đẩy ra khỏi công ty"

Đây là một kết quả nhỏ nhưng quan trọng. Paper không tìm thấy tác động đáng kể lên quit hay layoff exits. Nghĩa là high-flyer managers không tạo ra kết quả bằng cách loại bỏ worker yếu ra khỏi firm. Thay vào đó, họ **tìm deployment tốt hơn bên trong firm**.

Điều này giúp cơ chế allocation đáng tin hơn hẳn.

### 4. Career progression tăng mạnh và bền

Khi chuyển sang high-flyer manager, sau 28 quarters worker có số lần tăng salary grade cao hơn **0,17**. Tác giả diễn giải điều này tương đương với **mức lương cao hơn khoảng 13%** sau 7 năm. Với U.S. workers trong sample, đó là khoảng **11.962 USD mỗi năm**.

Đây là effect lớn. Tác giả còn tính present discounted value của pay và ước lượng rằng chỉ một lần exposure kéo dài trung bình 2 năm với high-flyer manager có thể làm tăng PDV thu nhập nghề nghiệp thêm khoảng **167,6% của mức lương năm trung bình**.

Diễn giải kinh tế: nếu manager chỉ làm worker chăm hơn trong ngắn hạn thì khó có effect kéo dài kiểu này. Kết quả hợp hơn với câu chuyện rằng manager đặt worker vào quỹ đạo tốt hơn.

### 5. Xác suất lên vị trí quản lý tăng

Work-level promotions từ level 1 lên level 2 cao hơn **0,02**, tương đương **31% tăng** sau 7 năm. Hiệu ứng này chỉ rõ nét từ khoảng 3 năm sau transition trở đi.

Điều này cực hợp logic. Nếu high-flyer managers giúp worker tìm đúng job để phát huy kỹ năng, thì không chỉ lương tăng mà xác suất bước vào nhánh quản lý cũng tăng.

### 6. Productivity thật sự tăng, không chỉ compensation

Với subsample 5.604 field sales workers ở 15 quốc gia, standardized sales bonus cao hơn **0,347 độ lệch chuẩn** sau 12 quarters, với p-value sát ngưỡng 5%. Dù sample con này noisier, nó rất có giá trị vì cho thấy tăng pay không chỉ là do compensation policy hay favoritism, mà gắn với performance.

### 7. Hiệu ứng bất đối xứng là bằng chứng rất mạnh cho allocation channel

Đây là điểm mình thấy đẹp nhất trong toàn paper. Khi worker **mất** high-flyer manager, outcome không đảo ngược theo chiều âm. Ước lượng gần 0 và không có ý nghĩa thống kê.

Nếu kênh chính là motivation hoặc monitoring, ta kỳ vọng khi rời manager giỏi thì worker xuống phong độ. Nhưng nếu kênh chính là allocation, thì một khi worker đã được đặt vào vị trí tốt hơn rồi, lợi ích vẫn giữ lại được. Kết quả bất đối xứng này là một bằng chứng cơ chế rất đẹp.

### 8. Mediation analysis gợi ý lateral transfers là một phần rất lớn của salary effect

Paper làm mediation analysis và thấy lateral transfers giải thích khoảng **64%** của total effect lên salary increases. Tác giả cẩn trọng nói đây có lẽ còn là lower bound, vì measure này chưa tính:

1. Những worker không đổi job vì đã ở đúng match rồi.
2. Vertical transfers.
3. Task reallocations không hiện thành job change chính thức.

Nói cách khác, allocation channel có lẽ còn quan trọng hơn con số 64% cho thấy.

### 9. Manager behavior và worker behavior đều phù hợp với cơ chế allocation

High-flyer managers:

1. Dành nhiều hơn khoảng **0,63 giờ/tuần** cho one-on-one với subordinates, tức khoảng **19% tăng**.
2. Giao tiếp dày hơn, multitask nhiều hơn, ít block thời gian uninterrupted hơn.

Workers dưới high-flyer managers:

1. Có khả năng hoàn thành profile trên flexible project platform cao hơn **9,7%**.
2. Có khả năng apply vào project roles cao hơn **15,4%**.
3. Apply nhiều project hơn **50,5%**.
4. Post nhiều skills hơn **0,66**, tức khoảng **10% tăng**.

Diễn giải: good managers ở đây không chỉ chấm điểm hay thưởng phạt. Họ là active coordinators, mentors, và matchmakers.

## What is special or elegant about the paper

### 1. Paper thật sự mở "hộp đen" của firm

Rất nhiều bài về labor market coi firm như black box. Paper này nhìn thẳng vào bên trong: ai báo cáo cho ai, ai chuyển ngang, ai được tăng grade, ai lên quản lý. Đó là một bước rất đáng nhớ.

### 2. Cơ chế được kiểm định chứ không chỉ được kể

Nhiều paper có "mechanism section" khá tượng trưng. Ở đây, allocation channel được hỗ trợ bởi:

1. Lateral moves tăng.
2. Task distance tăng.
3. Cross-functional mobility tăng.
4. No exit effect.
5. Asymmetric loss result.
6. Mediation analysis.
7. Time-use và project-platform data.

Tức là mechanism không nằm ở phần thảo luận suông mà được đóng đinh bởi nhiều mảnh bằng chứng khác nhau.

### 3. Cách đo manager quality rất thông minh

Đo bằng speed of promotion không hoàn hảo, nhưng rất hợp bài toán. Nó tách manager quality khỏi subordinate outcomes, giảm circularity, và lại rất portable sang context khác.

### 4. Tư duy "zero-cost productivity gain" rất đáng học

Một thông điệp rất mạnh của paper là năng suất có thể tăng lớn chỉ từ việc **tái phân bổ người đang có**, không cần capex hay firing/hiring quy mô lớn. Đây là insight rất có giá trị cho cả theory of the firm lẫn policy về management practices.

## Required background knowledge

### 1. Internal labor markets

Cần biết internal labor market là thị trường lao động bên trong firm, nơi worker có thể đổi team, đổi job title, thăng bậc lương, hay lên level mà không cần rời doanh nghiệp. Đây là khung quan trọng để hiểu tại sao manager có thể ảnh hưởng lớn đến career trajectories.

### 2. Personnel economics

Personnel economics nghiên cứu incentive schemes, promotions, monitoring, tuyển dụng, tổ chức công việc, và behavior trong doanh nghiệp. Paper này nằm đúng giao điểm giữa personnel economics và labor economics.

### 3. Event study với staggered treatment

Người đọc nên nắm intuition cơ bản của event study:

1. So outcome trước và sau event.
2. Kiểm tra pre-trends để xem assumption parallel trends có hợp lý không.
3. Với treatment timing khác nhau giữa worker, cần cẩn thận với cohort effects. Paper có làm robustness bằng estimator của Sun và Abraham.

### 4. Misallocation

Misallocation không chỉ là capital bị phân sai giữa firms. Bên trong firm cũng có misallocation: người giỏi việc A nhưng bị đặt vào việc B. Paper này nói manager giỏi làm giảm dạng misallocation đó.

### 5. Mediation analysis

Mediation analysis cố tách total effect của treatment thành phần đi qua mediator và phần còn lại. Ở đây mediator là lateral move. Tác giả khá cẩn trọng rằng phương pháp này đòi hỏi giả định mạnh, nên nên hiểu kết quả như bằng chứng định lượng gợi ý chứ không phải chân lý tuyệt đối.

## Limitations and open questions

### 1. External validity bị giới hạn

Đây là một large multinational white-collar firm. Kết quả có thể không mang nguyên xi sang factory workers, SMEs, khu vực công, hay labor markets ở nước thu nhập thấp.

### 2. Measure của manager quality vẫn là proxy

Dù speed of promotion hợp lý, nó có thể phản ánh nhiều thứ khác ngoài pure managerial matching ability, như political skill, sponsor quality, hay fit với culture của firm.

### 3. Rotation chưa phải random assignment hoàn hảo

Paper làm rất nhiều checks để bác bỏ sorting và common shocks, nhưng vì đây không phải RCT nên residual concern vẫn còn. Ví dụ firm có thể ngầm gửi manager tốt đến team đang được chú ý chiến lược mà các controls không nắm bắt hết.

### 4. Chưa nhìn trực tiếp được skill mapping ở mức vi mô nhất

Paper suy ra rằng manager giỏi khám phá worker aptitude và gán vào specialized jobs phù hợp hơn, nhưng ta vẫn chưa thấy trực tiếp "worker X có skill Y nên được chuyển sang task Z". Dữ liệu platform và task distance giúp rất nhiều, nhưng chưa phải full direct observation của latent skill match.

### 5. Cơ chế đào tạo và cơ chế allocation có thể cùng tồn tại

Paper nghiêng mạnh về allocation channel, và asymmetric effects là bằng chứng đẹp. Nhưng mình nghĩ không nên đọc quá cứng rằng teaching channel bằng 0. Thực tế good managers có thể vừa giỏi đặt người đúng chỗ vừa giỏi làm họ học nhanh hơn. Paper có mô hình hóa điều này trong appendix và kết luận dữ liệu phù hợp với allocation là chính, không nhất thiết phủ định hoàn toàn teaching.

### Câu hỏi mở

1. Liệu firms có thể huấn luyện manager để giỏi matching hơn không, hay đây chủ yếu là năng lực khó đào tạo?
2. AI-based talent matching có thể thay thế hay bổ sung manager judgment đến đâu?
3. Hiệu ứng này mạnh hơn ở giai đoạn tái cấu trúc công nghệ hay khủng hoảng hay không?
4. Liệu good manager effects mạnh hơn trong firms có nhiều job ladders và cross-functional options hơn?

## Takeaways for a researcher

1. Khi muốn chứng minh một cơ chế, hãy gom nhiều loại bằng chứng vừa định lượng vừa thể chế, thay vì chỉ thêm một subsection bàn luận.
2. Một proxy tốt không cần hoàn hảo; quan trọng là nó được xác lập ex ante, hợp với theory, và đi cùng nhiều validation checks.
3. Bằng chứng bất đối xứng đôi khi có sức mạnh cơ chế lớn hơn cả hệ số reduced-form chính.
4. Internal labor markets là một mỏ nghiên cứu còn rất giàu, nhất là khi có linked employer-employee data.
5. Productivity gains không nhất thiết đến từ tuyển người giỏi hơn; nhiều khi đến từ đặt người hiện có vào đúng chỗ hơn.
6. Với dữ liệu hiếm, thiết kế "quasi-experiment + mechanism-rich evidence" có thể tạo ra paper rất thuyết phục ngay cả khi không có shock chính sách kinh điển.

## Vietnam relevance and extension

### Liên hệ với Việt Nam

Paper này rất gợi mở cho Việt Nam, nhất là trong bối cảnh nhiều doanh nghiệp lớn, ngân hàng, tập đoàn bán lẻ, viễn thông, FDI suppliers, và doanh nghiệp nhà nước đang mở rộng nhưng thường quản trị nhân sự nội bộ theo cách khá hành chính.

Ở Việt Nam, một vấn đề phổ biến không hẳn là thiếu người tài tuyệt đối, mà là:

1. Đặt người chưa đúng vị trí.
2. Luân chuyển nhiều nhưng thiếu thông tin để luân chuyển hiệu quả.
3. Promotion dựa nhiều vào tenure hoặc quan hệ hơn là matching quality.
4. Internal mobility platforms còn yếu.

Nếu logic của paper đúng, thì cải thiện năng lực manager trong việc khám phá skill và mở đường cho internal mobility có thể tạo productivity gains đáng kể mà không cần tăng headcount lớn.

### Có triển khai nghiên cứu tương tự ở Việt Nam được không?

Có, nhưng cần đối tác dữ liệu mạnh. Những setting khả thi nhất có thể là:

1. Tập đoàn đa ngành hoặc ngân hàng lớn có dữ liệu HR panel theo worker-manager.
2. MNCs hoặc FDI firms có formal job ladders và internal transfers.
3. Khu vực công hoặc doanh nghiệp nhà nước có chính sách rotation cán bộ tương đối đều.

### Điều kiện cần có ở Việt Nam

1. Dữ liệu nối worker với manager theo thời gian.
2. Dữ liệu lương, tăng bậc, transfer, promotion, exit.
3. Một measure ex ante của manager quality.
4. Một nguồn biến thiên về manager assignment đủ đáng tin, như rotation policy hoặc centralized assignment.

### Trở ngại chính

1. Dữ liệu HR ở Việt Nam thường phân mảnh và khó nối panel.
2. Rotation có thể không orthogonal với political considerations.
3. Nhiều doanh nghiệp chưa có job architecture đủ rõ để phân biệt lateral move, vertical move, và task change.

### Một số hướng nghiên cứu mới cho Việt Nam

1. **Manager rotation trong ngân hàng hoặc tập đoàn bán lẻ có cải thiện internal mobility và doanh số của nhân viên không?**
2. **Khi doanh nghiệp Việt Nam áp dụng internal talent marketplace, liệu manager quality còn quan trọng như trước hay AI matching thay thế được một phần?**
3. **Trong khu vực công, luân chuyển cán bộ có thực sự tạo better matching hay chủ yếu là administrative reshuffling?**

## Ghi chú trung thực về trạng thái lưu trữ trong lượt này

Mình xác minh được nguồn PDF tốt nhất là accepted-manuscript PDF open access trên trang QJE của bài, và có thêm hai nguồn working-paper PDF công khai rất gần bản xuất bản để đọc sâu. Tuy vậy, môi trường shell của lượt chạy này tiếp tục bị chặn `403` khi tải raw PDF bytes trực tiếp từ nguồn ngoài. Vì vậy:

1. Nếu cuối lượt chỉ upload được `analysis.md` và `analysis.html`, thì đó là trạng thái đúng phải báo.
2. `analysis.pdf` chỉ được coi là thành công nếu vừa tạo được file PDF hợp lệ vừa upload thành công lên GitHub.
3. PDF gốc của paper chỉ được coi là đã lưu nếu thật sự tải được file nhị phân và upload được lên repo.

Tại thời điểm soạn bản phân tích này, các bước nhị phân đó vẫn là phần cần kiểm tra tiếp, không được mặc định coi là đã xong.