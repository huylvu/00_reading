# Technology Sophistication Across Establishments

- **Tác giả:** Xavier Cirera, Diego Comin, Marcio Cruz
- **Journal:** The Quarterly Journal of Economics
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-02
- **Nguồn bài báo chính:** https://academic.oup.com/qje/advance-article/doi/10.1093/qje/qjag018/8537769
- **Nguồn PDF dùng để phân tích:** NBER Working Paper 33358 tại https://www.nber.org/system/files/working_papers/w33358/w33358.pdf
- **Trạng thái lưu trên GitHub:** `analysis.md`, `analysis.html`, và `analysis-style.css` đã được lưu trong repo `huylvu/00_reading` tại thư mục `Technology Sophistication Across Establishments - Cirera Comin Cruz/`; `analysis.pdf` chưa được tạo trong lượt này; PDF gốc của paper mới xác minh được nguồn công khai nhưng chưa tải và chưa upload được file nhị phân.
- **Trạng thái Google Drive:** bỏ qua trong lượt này vì chưa có tuyến tạo Google Doc và tracker đúng folder đích một cách chắc chắn.

## 1. Metadata

- **Tiêu đề paper:** Technology Sophistication Across Establishments
- **Tác giả:** Xavier Cirera, Diego Comin, Marcio Cruz
- **Journal:** The Quarterly Journal of Economics
- **Năm:** 2026
- **DOI / trang nguồn chính:** https://doi.org/10.1093/qje/qjag018
- **PDF công khai tốt nhất dùng để đọc sâu:** NBER Working Paper No. 33358, January 2025, https://www.nber.org/system/files/working_papers/w33358/w33358.pdf
- **Nguồn đối chiếu thêm:** World Bank Policy Research Working Paper 11051 / Open Knowledge Repository, https://hdl.handle.net/10986/42738
- **Tình trạng xác minh:** đã xác minh chắc tiêu đề, tác giả, journal và thời điểm xuất bản QJE từ trang Oxford Academic; phần đọc sâu dựa trên public working-paper PDF rất sát với bản accepted manuscript QJE.

## 2. Executive summary

Paper hỏi một câu rất cơ bản nhưng lâu nay đo khá kém: khi ta nói một doanh nghiệp ở nước nghèo hay nước giàu “dùng công nghệ tốt hơn”, chính xác là ta đang nói tới cái gì. Tác giả lập luận rằng chỉ nhìn xem doanh nghiệp có “sở hữu” một công nghệ tiên tiến nào đó là chưa đủ. Điều quan trọng hơn là công nghệ nào được dùng rộng rãi nhất trong từng khâu sản xuất và vận hành.

Để trả lời câu hỏi này, paper xây một “technology grid” rất tham vọng: 163 business functions và 305 công nghệ, rồi triển khai trong khảo sát FAT trên hơn 21.000 cơ sở ở 15 quốc gia, trong đó có nhiều nước đang phát triển như Việt Nam, Bangladesh, Ghana, Kenya, Senegal, Ethiopia, Cambodia. Từ đó paper tạo ra hai khái niệm trung tâm: `MAX` là công nghệ tinh vi nhất mà cơ sở có trong một business function, còn `MOST` là công nghệ được dùng nhiều nhất trong function đó.

Kết quả lớn nhất là khoảng cách giữa `MAX` và `MOST` rất phổ biến và không chỉ là chuyện tạm thời. Nhiều cơ sở đã “chạm tay” vào công nghệ tốt hơn nhưng chưa biến nó thành công nghệ chủ đạo. Chính `MOST`, chứ không phải `MAX`, mới liên hệ mạnh hơn với năng suất. Chênh lệch về mức độ tinh vi công nghệ giải thích khoảng 31% phân tán năng suất giữa các cơ sở, và hơn một nửa productivity gap của nông nghiệp giữa nhóm nước thu nhập cao và thấp. Bài đáng đọc vì nó thay đổi cách ta nghĩ về khoảng cách công nghệ: vấn đề không chỉ là adoption ở biên, mà là diffusion và cường độ sử dụng bên trong doanh nghiệp.

## 3. Research question and motivation

### Câu hỏi trung tâm

Paper muốn biết:

1. Làm sao đo mức độ tinh vi công nghệ của một cơ sở sản xuất hay dịch vụ theo cách bao quát hơn các thước đo truyền thống.
2. Trong cùng một cơ sở, công nghệ tiên tiến nhất và công nghệ được dùng nhiều nhất có khác nhau không.
3. Sự khác nhau đó có giúp giải thích khoảng cách năng suất giữa doanh nghiệp, giữa ngành, và giữa quốc gia hay không.

### Động lực học thuật

Văn liệu đo lường công nghệ ở cấp doanh nghiệp thường dựa trên việc doanh nghiệp có hay không có một vài công nghệ “frontier”, như robot, internet, ERP, CAD/CAM, hay một số ICT cụ thể. Cách đo này hữu ích nhưng quá hẹp. Nó bỏ qua phần lớn các business functions thực sự cấu thành hoạt động của cơ sở, không đo được doanh nghiệp còn lại đang dùng công nghệ gì nếu họ không có công nghệ frontier, và cũng không đo được mức độ sử dụng nội bộ của công nghệ đã được adopted.

Điểm mà paper nhấn mạnh là một cơ sở có thể đã “adopt” một công nghệ hiện đại nhưng vẫn vận hành chủ yếu bằng công nghệ cũ. Nếu vậy, đo công nghệ bằng presence của frontier technology sẽ thổi phồng mức độ tinh vi thực sự.

### Động lực thực tiễn

Đây là câu hỏi rất quan trọng cho development economics. Khoảng cách năng suất giữa nước giàu và nước nghèo có thể đến từ:

1. các nước nghèo không tiếp cận được công nghệ tốt,
2. các doanh nghiệp nghèo có công nghệ tốt nhưng không dùng rộng,
3. công nghệ tốt không thật sự “appropriate” trong bối cảnh thiếu bổ trợ về kỹ năng, vốn, quản trị hay hạ tầng.

Paper giúp tách bạch các kênh này tốt hơn.

## 4. Main contribution

### Đóng góp 1: một cách đo công nghệ thực sự ở cấp establishment

Đóng góp lớn nhất là xây được một khung đo công nghệ có tính hệ thống. Grid của paper phủ cả chiều ngang là business functions và chiều dọc là các công nghệ có thể dùng cho từng function, sắp từ đơn giản tới frontier. Đây là một bước tiến lớn so với cách đếm vài công nghệ nổi bật.

### Đóng góp 2: tách biệt adoption với intensity / internal diffusion

Khái niệm `MAX` và `MOST` là ý tưởng đẹp nhất của paper. `MAX` đo công nghệ tốt nhất mà doanh nghiệp có thể tiếp cận trong function đó. `MOST` đo công nghệ thực sự chi phối vận hành hằng ngày. Nhờ vậy paper chỉ ra rằng adoption và diffusion trong nội bộ doanh nghiệp là hai quá trình khác nhau.

### Đóng góp 3: đưa công nghệ trở lại trung tâm của câu chuyện productivity dispersion

Paper cho thấy khác biệt về technology sophistication có liên hệ rất mạnh với năng suất, ngay cả khi đã kiểm soát human capital, capital intensity, management quality và markups. Điều này giúp nối văn liệu firm productivity với văn liệu technology adoption bằng một biến đo sắc hơn.

### Đóng góp 4: thách thức trực giác “appropriate technology” kiểu bi quan

Một lập luận phổ biến là công nghệ tiên tiến có thể ít hiệu quả ở nước nghèo do thiếu complements. Paper không bác bỏ hoàn toàn ý tưởng đó ở cấp lý thuyết, nhưng bằng chứng của họ cho thấy độ dốc productivity-theo-technology sophistication không nhỏ hơn ở nhóm nước thu nhập thấp. Điều này hàm ý trở ngại có thể nằm nhiều ở chi phí áp dụng và khuếch tán hơn là ở chỗ công nghệ cao “không hợp”.

## 5. Identification or methodology

### Dữ liệu và cách đo

Paper triển khai Firm Adoption of Technology (FAT) survey trên hơn 21.000 establishments ở 15 quốc gia, bao trùm cả nông nghiệp, chế biến, bán buôn bán lẻ, tài chính, vận tải và y tế. Grid của paper có:

1. **163 business functions** gồm 7 general business functions dùng chung và 56 sector-specific functions trải trên 12 sectors.
2. **305 technologies** được xếp hạng theo mức độ tinh vi cho từng function.

Ở mỗi business function, survey ghi:

1. doanh nghiệp có dùng function đó in-house không,
2. các công nghệ nào đang có mặt,
3. công nghệ nào là công nghệ được dùng nhiều nhất.

Từ đó paper định nghĩa:

1. **MAX:** mức tinh vi của công nghệ tiên tiến nhất có mặt trong function.
2. **MOST:** mức tinh vi của công nghệ được dùng nhiều nhất trong function.

Sau đó các thước đo function-level được gộp lên establishment-level bằng cách lấy trung bình đơn giản qua các functions liên quan.

### Logic nhận dạng và phương pháp suy luận

Paper này không phải causal paper theo nghĩa quen thuộc của micro applied như RCT, IV, RD hay diff-in-diff. Nó là một paper đo lường và thực chứng mô tả sâu, kết hợp:

1. thiết kế đo lường mới,
2. thống kê mô tả có cấu trúc,
3. productivity regressions giàu kiểm soát,
4. các bài kiểm tra theo nhóm nước, theo sector, theo quy mô, theo human capital để soi giả thuyết “appropriate technology”.

Hồi quy năng suất cơ bản dùng log sales per worker làm outcome, kết hợp fixed effects theo country-sector và controls cho capital per worker, tỷ lệ lao động có bằng đại học, management quality, exporter status, multinational status, multi-establishment status và markups.

### Giả định cốt lõi

Paper dựa trên vài giả định quan trọng:

1. Thứ bậc sophistication trong mỗi function là hợp lý và so sánh được.
2. Self-reported technology use trong FAT phản ánh tương đối đúng công nghệ vận hành.
3. Trung bình đơn giản qua functions là một proxy chấp nhận được cho establishment-level sophistication.
4. Trong productivity regressions, phần còn lại của omitted variables không đủ lớn để đảo ngược kết luận chính về vai trò của technology sophistication.

### Điểm mạnh phương pháp

1. Đo lường chi tiết chưa từng có ở cấp function.
2. Tách riêng công nghệ “có” với công nghệ “dùng chủ đạo”.
3. Phạm vi đa quốc gia giúp nói chuyện development nghiêm túc hơn nhiều study chỉ trong một nước.
4. Có thể so sánh trong nước, giữa nước, giữa sectors, và giữa quy mô doanh nghiệp.

### Điểm dễ bị nghi ngờ

1. Đây vẫn chủ yếu là bằng chứng tương quan, chưa xác định được tăng sophistication sẽ gây tăng năng suất bao nhiêu.
2. Việc xếp hạng sophistication trong grid có yếu tố chủ quan dù được thiết kế cẩn thận.
3. Gộp function-level sophistication bằng trung bình đơn giản có thể bỏ qua trọng số kinh tế khác nhau của từng function.
4. Sales per worker là outcome hợp lý nhưng chưa phải productivity measure hoàn hảo.

## 6. Results and interpretation

### Kết quả 1: MAX và MOST khác nhau một cách có hệ thống

Kết quả nền tảng là `MOST` thường thấp hơn `MAX`. Nói cách khác, nhiều establishments đã tiếp cận công nghệ tốt hơn nhưng vẫn chưa sử dụng nó làm công nghệ chủ lực. Paper diễn giải đây là bằng chứng rằng adoption ở biên và internal diffusion là hai quá trình khác nhau. Đây không phải khoảng cách ngắn hạn; paper nhấn mạnh gap này là persistent.

Diễn giải kinh tế rất quan trọng: để tăng productivity, chưa chắc chỉ cần giúp doanh nghiệp “mua” hay “sở hữu” công nghệ mới. Cần hiểu vì sao họ không chuyển trọng tâm vận hành sang công nghệ đó.

### Kết quả 2: variation rất lớn cả giữa nước lẫn trong nước

Technology sophistication biến thiên mạnh across establishments, không chỉ giữa các quốc gia mà cả trong cùng country và cùng sector. Điều này làm suy yếu một cách nhìn quá vĩ mô rằng khác biệt năng suất chủ yếu là câu chuyện giữa quốc gia; paper cho thấy ngay trong cùng môi trường thể chế vẫn có dispersion công nghệ rất lớn.

Paper cũng cho thấy dispersion này lớn hơn ở các nước giàu, đặc biệt với MOST, hàm ý khi nền kinh tế phát triển hơn thì doanh nghiệp tách xa nhau hơn về cách vận hành công nghệ chủ đạo.

### Kết quả 3: sophistication gắn mạnh với nhiều đặc điểm “năng lực tổ chức”

Các establishments có technology sophistication cao hơn thường:

1. lớn hơn,
2. có lao động trình độ cao hơn,
3. có management practices tốt hơn,
4. là exporter,
5. là multinational hoặc thuộc hệ thống nhiều cơ sở.

Điều này cho thấy công nghệ không đứng một mình. Nó đi cùng năng lực tổ chức, quản trị, kỹ năng và hội nhập thị trường.

### Kết quả 4: technology sophistication giải thích mạnh productivity dispersion

Kết quả nổi bật nhất về mặt định lượng là khác biệt technology sophistication giải thích khoảng **31%** phân tán năng suất giữa các establishments. Tỷ lệ này đặc biệt lớn trong nông nghiệp, nơi paper cho rằng nó giải thích khoảng **50%** chênh lệch năng suất giữa các cơ sở và hơn một nửa agricultural productivity gap giữa nhóm nước thu nhập cao và thấp.

Đây là một con số rất lớn. Nó không chứng minh hoàn toàn quan hệ nhân quả, nhưng đủ mạnh để nói rằng công nghệ vận hành ở cấp cơ sở là một phần cốt lõi của câu chuyện năng suất.

### Kết quả 5: MOST quan trọng hơn MAX cho năng suất

Một phát hiện rất đẹp là `MOST` liên hệ với productivity mạnh hơn `MAX`. Điều này có nghĩa là công nghệ được dùng thường xuyên mới là cái “sống” trong hàm sản xuất, chứ không phải công nghệ tốt nhất chỉ tồn tại ở rìa. Đây là một chỉnh sửa quan trọng với nhiều mô hình hay chỉ số vốn tập trung vào frontier adoption.

### Kết quả 6: công nghệ tinh vi không kém “appropriate” ở nước nghèo

Paper kiểm tra giả thuyết appropriate technology bằng cách xem độ dốc giữa productivity và sophistication có thấp hơn ở nhóm nước thu nhập thấp không. Kết luận của họ là không. Điều này gợi ý vấn đề không nằm ở chỗ công nghệ tinh vi vô ích ở nước nghèo, mà có thể nằm ở rào cản triển khai, complementary inputs, finance, management, training, hoặc diffusion nội bộ.

## 7. What is special or elegant about the paper

### Ý tưởng hay nhất: đổi câu hỏi từ “có công nghệ gì” sang “thực sự dùng công nghệ gì”

Đây là điểm làm paper đáng nhớ. Nhiều nghiên cứu adoption đo “presence” của công nghệ frontier. Paper này nhắc rằng doanh nghiệp có thể mua máy tốt, cài phần mềm tốt, hay có một dây chuyền hiện đại, nhưng nếu hoạt động hàng ngày vẫn dựa vào quy trình cũ thì productivity effect sẽ hạn chế. Việc tách `MAX` và `MOST` làm hiện ra chính xác điểm đó.

### Cái đẹp thứ hai: micro-foundation rất trực quan cho development gaps

Paper cho ta một mô tả vi mô của development: không chỉ các nước nghèo ở xa frontier, mà nhiều doanh nghiệp ngay cả khi đã nhìn thấy frontier vẫn chưa kéo hoạt động chính của mình lên gần frontier. Điều này rất hợp với trực giác của người làm field work: adoption bề mặt và usage thực chất là hai chuyện khác nhau.

### Cái đẹp thứ ba: nối measurement với policy

Bài không chỉ tạo chỉ số mới rồi dừng ở đó. Nó cho thấy chỉ số này nói được điều gì về productivity, sectoral gaps, agricultural development, và câu hỏi appropriate technology. Nghĩa là innovation về đo lường ở đây không tách rời câu hỏi kinh tế lớn.

## 8. Required background knowledge

### 8.1. Technology adoption vs diffusion

`Adoption` là việc doanh nghiệp bắt đầu có hoặc tiếp cận một công nghệ. `Diffusion` là quá trình công nghệ đó lan rộng, được dùng nhiều hơn, thay thế công nghệ cũ trong vận hành thực tế. Paper này nhấn mạnh internal diffusion trong nội bộ doanh nghiệp.

### 8.2. Task-based view of production

Thay vì coi sản xuất là một khối đồng nhất, cách nhìn task-based chia hoạt động doanh nghiệp thành nhiều tasks hay business functions. Mỗi function có thể được thực hiện bằng các công nghệ khác nhau, từ thủ công tới tự động hóa cao. Đây là nền tảng để xây “grid”.

### 8.3. Productivity dispersion

Ngay trong cùng ngành, năng suất giữa các doanh nghiệp thường chênh lệch rất lớn. Văn liệu productivity dispersion cố giải thích vì sao có những firms hoạt động rất hiệu quả và những firms rất kém hiệu quả. Paper này đặt công nghệ vận hành vào trung tâm của dispersion đó.

### 8.4. Appropriate technology

Đây là ý tưởng cho rằng công nghệ tốt nhất về mặt kỹ thuật chưa chắc tốt nhất trong một môi trường cụ thể, vì nó cần kỹ năng, vốn, quản trị, điện, logistics, chuẩn hóa đầu vào hay thị trường đầu ra tương thích. Paper kiểm tra gián tiếp ý tưởng này bằng cách xem lợi ích gắn với sophistication có thấp hơn ở nước nghèo không.

### 8.5. Omitted variable bias trong productivity regressions

Khi thấy công nghệ tinh vi đi cùng năng suất cao, ta phải cẩn thận: có thể doanh nghiệp tốt hơn về quản trị, tài chính hay năng lực vô hình vừa dùng công nghệ tốt hơn vừa có năng suất cao hơn. Paper cố kiểm soát khá nhiều biến, nhưng đây vẫn là điểm cần giữ trong đầu khi đọc.

## 9. Limitations and open questions

### Hạn chế 1: chưa phải identification nhân quả

Kết quả về productivity chủ yếu là liên hệ điều kiện, không phải causal effect sạch. Một bước tiếp theo tự nhiên là khai thác shocks, phased rollouts, subsidies, hoặc supply disruptions để đo causal effect của việc nâng MOST hay thu hẹp gap giữa MAX và MOST.

### Hạn chế 2: measurement ranking có thể gây tranh luận

Việc xếp công nghệ từ kém tinh vi tới tinh vi hơn trong từng function là rất hữu ích nhưng không tránh khỏi judgment calls. Với một số settings, công nghệ “đơn giản” có thể tối ưu vì scale nhỏ hoặc đầu vào không ổn định.

### Hạn chế 3: aggregation lên cấp establishment còn thô

Chính tác giả thừa nhận việc lấy trung bình đơn giản qua functions là shortcut hợp lý cho mục tiêu mô tả, nhưng chưa có nền tảng lý thuyết đủ mạnh cho weighting tối ưu giữa các functions. Một improvement quan trọng là xây trọng số theo cost share hoặc value relevance của từng function.

### Hạn chế 4: cơ chế đằng sau MAX-MOST gap vẫn còn mở

Paper cho thấy gap tồn tại và có ý nghĩa, nhưng chưa chốt được vì sao:

1. thiếu training,
2. resistance của tổ chức,
3. chi phí thay đổi quy trình,
4. thiếu complementary inputs,
5. rủi ro vận hành,
6. tài chính,
7. hay market incentives chưa đủ mạnh.

### Hạn chế 5: sales per worker chưa phải productivity “thuần”

Dù đã kiểm soát nhiều thứ, sales per worker vẫn chịu ảnh hưởng của prices, demand conditions và market power. Dùng quantity-based productivity hoặc data chi tiết hơn về value added sẽ giúp chắc tay hơn.

## 10. Takeaways for a researcher

1. Đừng đồng nhất adoption với use intensity. Nếu chỉ đo firm có một công nghệ hay không, rất có thể bạn đang bỏ lỡ phần quan trọng nhất.
2. Một innovation về measurement có thể là đóng góp lớn nếu nó mở được câu hỏi substantive mà chỉ số cũ không trả lời được.
3. Khi nghiên cứu development gaps, nên nhìn vào within-country heterogeneity chứ không chỉ cross-country averages.
4. Cần nghĩ về complementarities giữa technology, skills, management và organization như một hệ thống chung.
5. Nếu muốn làm causal paper tiếp theo, khoảng cách giữa `MAX` và `MOST` là outcome hoặc mechanism rất hứa hẹn.
6. Paper này là ví dụ tốt về cách biến một survey instrument thành đóng góp học thuật top-5, miễn là instrument đó gắn với một câu hỏi kinh tế thật sự lớn.

## 11. Vietnam relevance and extension

### Tại sao paper này rất hợp với Việt Nam

Việt Nam là một bối cảnh gần như lý tưởng cho logic của paper:

1. có nhiều firms vừa và nhỏ,
2. có chênh lệch rất lớn giữa domestic firms, FDI firms, exporters và non-exporters,
3. có thúc đẩy mạnh về chuyển đổi số và upgrading công nghiệp,
4. có câu hỏi lớn về vì sao nhiều doanh nghiệp “có công nghệ” nhưng năng suất vẫn không bứt lên.

### Một cách đọc theo bối cảnh Việt Nam

Nhiều doanh nghiệp Việt Nam có thể đã mua ERP, máy móc mới, phần mềm quản lý kho, hay hệ thống QC hiện đại, nhưng công nghệ cũ vẫn là cái vận hành chính. Nếu đúng vậy, chính sách hỗ trợ “đầu tư công nghệ” đơn thuần có thể ít hiệu quả hơn kỳ vọng. Điều cần là hỗ trợ adoption đi kèm training, redesign quy trình, middle-management capability và incentive nội bộ.

### Điều kiện cần để triển khai nghiên cứu tại Việt Nam

1. một survey instrument kiểu FAT được nội địa hóa theo ngành ở Việt Nam,
2. dữ liệu establishment-level đủ chi tiết về sales, labor, capital, management practices, export status và ownership,
3. hợp tác với Tổng cục Thống kê, Bộ Kế hoạch và Đầu tư, các hiệp hội ngành, hoặc khu công nghiệp,
4. khả năng xây sector-specific technology grids cho các ngành trọng điểm như dệt may, da giày, điện tử, chế biến thực phẩm, logistics, bán lẻ, y tế.

### Trở ngại chính ở Việt Nam

1. self-reported data có thể noisy nếu doanh nghiệp không hiểu technology categories giống nhau,
2. khu vực SME và informal / quasi-formal rất khó đo chuẩn,
3. dữ liệu năng suất và cost structure thường không sạch,
4. cần đầu tư lớn để xây grid đủ sát thực tế ngành.

### Các hướng mở rộng rất đáng làm

1. **FDI spillovers và MOST:** FDI có giúp doanh nghiệp nội địa nâng `MOST`, hay chỉ giúp họ nâng `MAX` mà chưa đổi được vận hành chính?
2. **Chuyển đổi số ở SME:** các chương trình hỗ trợ số hóa có làm giảm gap giữa `MAX` và `MOST` không?
3. **Management training như một complement của technology adoption:** đào tạo quản trị có giúp công nghệ đã mua trở thành công nghệ được dùng chủ đạo không?

### 3 research questions khả thi cho Việt Nam

1. Trong doanh nghiệp sản xuất Việt Nam, phần nào của productivity gap giữa exporters và non-exporters được giải thích bởi chênh lệch `MOST` thay vì `MAX`?
2. Các gói hỗ trợ digital transformation cho SME có làm tăng mức độ sử dụng thực tế của công nghệ đã adopted không?
3. Trong chuỗi cung ứng có FDI, internal diffusion của công nghệ trong doanh nghiệp nội địa bị chặn chủ yếu bởi kỹ năng lao động, middle management hay finance?

## Vì sao bài này được chọn hôm nay

Paper này phù hợp rất sát tiêu chí của lượt chạy:

1. là **top 5 journal economics** và rất mới trên QJE, published online ngày **23 March 2026**;
2. nằm đúng giao điểm giữa **applied micro, firm productivity, technology adoption và development**;
3. có đóng góp rõ ràng, dễ nhớ và có thể dùng được cho nghiên cứu thực địa;
4. có public PDF đủ chắc để đọc sâu;
5. có liên hệ rất mạnh với bối cảnh doanh nghiệp và năng suất ở Việt Nam.

## Ghi chú trung thực về giới hạn của lượt chạy

- Mình đã xác minh được public PDF rất tốt và dùng nó để phân tích sâu.
- Tuy nhiên, trong môi trường chạy này, tải trực tiếp file PDF nhị phân từ nguồn công khai sang shell tiếp tục gặp lỗi `403`, nên trạng thái cuối cần hiểu là **chưa tải được và chưa lưu được raw PDF gốc lên GitHub**.
- `analysis.pdf` không được tạo trong lượt này vì chưa có nhu cầu bắt buộc và cũng không nên hứa lưu khi chưa đi hết được bước upload.
- Google Drive được bỏ qua để tránh tạo kết quả nửa vời không đúng folder hoặc không cập nhật được tracker.
