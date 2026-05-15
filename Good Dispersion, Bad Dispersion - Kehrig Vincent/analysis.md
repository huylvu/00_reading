# Good Dispersion, Bad Dispersion

- Tác giả: Matthias Kehrig, Nicolas Vincent
- Journal và năm: The Review of Economic Studies, 2026
- Ngày agent chạy: 2026-05-15
- Nguồn bài báo chính: https://academic.oup.com/restud/article/93/2/1103/8166644
- DOI: https://doi.org/10.1093/restud/rdaf042
- Nguồn PDF tốt nhất đã xác minh: article PDF / accepted-public PDF trên Oxford Academic tại https://academic.oup.com/restud/article-pdf/93/2/1103/63565479/rdaf042.pdf
- Nguồn PDF công khai dùng để đọc sâu trong lượt chạy: CES Working Paper March 2024 tại https://www2.census.gov/ces/wp/2024/CES-WP-24-13.pdf
- Trạng thái GitHub cuối lượt này:
  - Nếu bạn đang đọc file này trong repo `huylvu/00_reading`, thì `analysis.md` đã được lưu thành công.
  - `analysis.html` được tạo như bản dễ đọc đi kèm và được lưu cùng thư mục khi bước GitHub thành công.
  - `analysis.pdf`: chưa tạo, chưa lưu.
  - PDF gốc của paper chỉ được coi là đã lưu khi file nhị phân thật sự được upload lên GitHub; lượt này ghi rõ trạng thái thực tế ở phần cuối.
- Trạng thái Google Drive: bỏ qua trong lượt chạy này nếu không thể tạo Google Doc và tracker đúng folder đích một cách chắc chắn.

## 1. Metadata

- Tiêu đề paper: *Good Dispersion, Bad Dispersion*
- Tác giả: Matthias Kehrig, Nicolas Vincent
- Journal: *The Review of Economic Studies*
- Năm: 2026
- Volume / issue / pages: Volume 93, Issue 2, March 2026, pages 1103-1136
- Link bài báo hoặc trang nguồn chính: https://academic.oup.com/restud/article/93/2/1103/8166644
- DOI: https://doi.org/10.1093/restud/rdaf042
- Link PDF đã xác minh:
  - Bản gần phiên bản xuất bản nhất: Oxford article PDF
  - Bản công khai đọc sâu trong lượt chạy: CES Working Paper 24-13, March 2024

Ghi chú nguồn: Phân tích sâu bên dưới bám chủ yếu vào CES working-paper version tháng 3/2024 vì đây là bản full-text công khai và đọc ổn định trong lượt chạy. Metadata xuất bản và top-line framing được đối chiếu lại với ReStud 2026. Về logic lý thuyết, kết quả định tính, và các magnitudes lớn, working paper và published version rất gần nhau.

## 2. Executive summary

Paper đặt một câu hỏi rất cơ bản nhưng lại đụng đúng trái tim của misallocation literature: liệu dispersion trong marginal revenue products của inputs giữa các production units luôn là dấu hiệu “xấu” của méo mó phân bổ, hay đôi khi dispersion cao lại phản ánh một allocation tốt hơn?

Câu trả lời của Kehrig và Vincent là: không phải mọi dispersion đều xấu. Trong môi trường multi-plant firms có internal capital markets và external finance đắt đỏ, firm tối ưu có thể chủ động *stagger investment* giữa các plants qua thời gian. Điều đó làm marginal revenue products của capital phân tán hơn giữa các plants tại một thời điểm, nhưng lại giúp output và efficiency cao hơn. Nói cách khác, dispersion có thể là byproduct của một second-best allocation tốt hơn, chứ không nhất thiết là dấu hiệu misallocation nặng hơn.

Paper đi theo một logic rất đẹp. Đầu tiên, authors chỉ ra bằng dữ liệu U.S. Census rằng gần hai phần ba dispersion của marginal revenue products of capital xảy ra **bên trong firms**, giữa các plants cùng firm, chứ không phải giữa firms. Điều này đã đủ để khiến người đọc phải dừng lại, vì phần lớn misallocation literature quen nghĩ ở level market giữa firms. Sau đó, họ xây một model multi-plant firm với plant-level adjustment frictions và firm-level financing constraints. Trong mô hình này, internal capital markets cho phép firm dồn vốn vào một số plants trước, rồi luân phiên sang plants khác ở các kỳ sau. Chính sự luân phiên này tạo ra “good dispersion”.

Kết quả định lượng rất mạnh. Khi “tắt” internal capital markets, aggregate capital giảm khoảng 12% và output giảm khoảng 8%, dù variance của marginal products lại thấp hơn khoảng 40%. Nghĩa là dispersion giảm nhưng allocation tệ đi. Từ đây, paper kết luận rằng dùng dispersion như một sufficient statistic cho misallocation là rất nguy hiểm. Hệ quả development quan trọng là: vì emerging economies có ít scope hơn cho good dispersion, nên chênh lệch misallocation giữa emerging và developed economies có thể còn lớn hơn những gì literature trước đây ước tính.

## 3. Research question and motivation

### Câu hỏi nghiên cứu trung tâm

Paper hỏi ba điều gắn chặt với nhau:

1. Dispersion trong marginal revenue products có phải lúc nào cũng phản ánh bad misallocation hay không?
2. Tại sao within-firm dispersion lại lớn đến vậy nếu firms được kỳ vọng là planners phân bổ vốn nội bộ?
3. Nếu một phần dispersion là “good”, thì cách ta suy ra output losses từ misallocation, đặc biệt khi so sánh developing và developed economies, cần sửa lại như thế nào?

### Bối cảnh học thuật

Sau Hsieh-Klenow, một phần lớn literature coi dispersion trong revenue products là dấu vết của wedges và distortions. Từ dispersion đó, researchers thường suy ra potential gains from reallocation. Đây là một framework rất mạnh, nhưng nó ngầm dựa vào một trực giác một chiều: dispersion cao hơn nghĩa là allocation tệ hơn.

Paper này đụng trực diện vào giả định đó. Nếu firms có cấu trúc tổ chức nhiều plants và có thể dùng internal capital markets để đối phó với external financing frictions, thì quan hệ giữa frictions và dispersion không còn monotonic. Có những tình huống nới lỏng một friction làm output tăng **và** dispersion tăng.

### Động lực thực tiễn

Điểm thực tiễn rất quan trọng là multi-plant firms chiếm phần lớn output và investment trong U.S. manufacturing. Nếu hầu hết dispersion nằm trong các firms như vậy, thì không thể tiếp tục nói về misallocation mà bỏ qua organizational structure của firm. Paper này vì thế không chỉ là một bài về productivity; nó còn là một bài về bản chất kinh tế của doanh nghiệp như một internal planner.

## 4. Main contribution

### Đóng góp 1: phân biệt “good dispersion” với “bad dispersion”

Đây là đóng góp khái niệm lớn nhất. Paper không phủ nhận bad dispersion; ngược lại, nó nói rằng observable dispersion là hỗn hợp của:

- **bad dispersion**: dispersion do frictions làm allocation tệ đi
- **good dispersion**: dispersion phát sinh từ cách firm tối ưu nội bộ trong second-best world

Điểm này thay đổi cách đọc cả một literature.

### Đóng góp 2: chỉ ra vai trò kinh tế của within-firm allocation

Paper cho thấy gần hai phần ba overall dispersion trong marginal revenue products of capital xảy ra giữa plants thuộc cùng firm. Đây là một empirical fact rất nặng ký, vì nó chuyển unit of analysis từ market-wide allocation sang internal organization of firms.

### Đóng góp 3: model multi-plant firm có staggered investment

Model của bài kết hợp:

- fixed và convex adjustment costs ở level plant
- external financing constraints ở level firm
- khả năng pool và reallocate funds qua internal capital markets

Từ tổ hợp này, authors rút ra cơ chế staggered investment: firm không đầu tư đều ở tất cả plants cùng lúc, mà luân phiên tập trung nguồn lực vào vài plants, tạo dispersion nội bộ bền vững.

### Đóng góp 4: hàm ý development / emerging economies

Paper lập luận rằng nếu U.S. dispersion có một phần “good” nhờ multi-plant firms và internal capital markets, còn emerging economies có ít scope cho good dispersion hơn, thì khoảng cách misallocation thật sự giữa emerging và developed economies bị đánh giá thấp trong literature trước đó. Authors thậm chí gợi ý previous work có thể đã bỏ lỡ từ một phần mười đến một nửa output gains from reallocation.

## 5. Identification or methodology

### Empirical fact nền tảng

Tác giả bắt đầu bằng một fact cực quan trọng từ U.S. Economic Census: gần hai phần ba dispersion của marginal revenue products of capital nằm **trong nội bộ firms**, giữa plants cùng firm, thay vì giữa firms. Fact này vừa là động lực, vừa là discipline device cho model: bất kỳ lý thuyết nào cũng phải giải thích tại sao firms “chịu đựng” dispersion nội bộ lớn như vậy.

### Mô hình lý thuyết

Framework là một quantitative model của multi-plant firm. Mỗi plant đối mặt với technological frictions như fixed/convex adjustment costs. Ở level firm, có external financing constraints khiến việc gọi vốn bên ngoài đắt đỏ. Firm có thể dùng internal capital markets để pool funds và phân bổ lại giữa plants.

Trong môi trường này, allocation tối ưu không phải là ép tất cả plants về cùng marginal revenue product tại mỗi thời điểm. Thay vào đó, firm có thể tối ưu bằng cách:

1. dồn internal funds vào một số plants trước,
2. trì hoãn plants khác sang kỳ sau,
3. luân phiên investment qua thời gian.

Chính sách staggered này làm dispersion nội bộ tăng, nhưng giảm external finance costs và nâng output.

### Calibration và dữ liệu

Model được calibrated bằng moments từ U.S. Annual Survey of Manufactures và các parameter chuẩn trong investment literature. Ở phần empirics, paper dùng plant-level Census data để kiểm tra các predictions về level và dispersion của revenue products, về nhu cầu external funds, và về cross-plant investment dynamics.

### Proxy cho internal capital market frictions

Một thủ pháp empirical rất hay của paper là dùng **geographic distance giữa plants trong cùng firm** làm proxy cho mức độ friction trong internal capital markets. Intuition là khi plants ở xa nhau hơn, headquarters khó gather information, evaluate capital needs, và reshuffle cash flows hiệu quả hơn. Authors cho thấy khi within-firm distance tăng, các patterns trong dữ liệu di chuyển đúng hướng model dự đoán.

### Điểm mạnh của phương pháp

- Paper có một motivating fact rất sắc và rất khó bỏ qua.
- Model nói đúng chỗ empirical fact yêu cầu: giải thích within-firm dispersion.
- Empirical exercise không chỉ test một sign; nó kiểm tra whole mechanism, từ dispersion tới external funds và investment correlations.

### Điểm dễ bị nghi ngờ

- Distance giữa plants là một proxy hợp lý nhưng không hoàn hảo cho frictions nội bộ.
- Kết quả định lượng phụ thuộc vào model structure và calibration.
- “Good dispersion” là một object khái niệm suy ra từ model-data fit; nó không quan sát trực tiếp như một biến độc lập.

## 6. Results and interpretation

### Kết quả 1: phần lớn dispersion là within-firm

Đây là kết quả mở đầu nhưng cũng là một trong những kết quả quan trọng nhất. Paper chỉ ra gần **hai phần ba** overall dispersion trong marginal revenue products of capital phát sinh giữa plants cùng firm. Điều này ngụ ý rằng nếu ta chỉ nhìn dispersion như một market-level pathology thì ta đang bỏ lỡ phần lớn hiện tượng kinh tế cần giải thích.

### Kết quả 2: tắt internal capital markets làm output giảm dù dispersion cũng giảm

Trong model, shutting down internal capital markets làm:

- aggregate capital giảm khoảng **12%**
- output giảm khoảng **8%**
- variance của marginal products giảm khoảng **40%**

Đây là punchline của bài. Một allocation tệ hơn lại đi cùng dispersion thấp hơn. Vì vậy dispersion không thể là monotonic statistic cho misallocation.

### Kết quả 3: cơ chế staggered investment

Khi firm bị external finance constraints nhưng vẫn còn internal capital markets, nó sẽ không chia vốn đều. Thay vào đó, nó tập trung funds vào một số plants trước rồi chuyển sang plants khác ở kỳ sau. Kết quả là:

- investment rates giữa plants bớt đồng bộ
- marginal revenue products phân tán hơn
- dispersion này persistent trong stochastic equilibrium

Ý nghĩa kinh tế là firm đang tối ưu second-best, không phải behaving irrationally.

### Kết quả 4: empirical support cho mechanism

Paper cho thấy khi internal capital market frictions lớn hơn, đo bằng khoảng cách địa lý giữa các plants trong cùng firm, thì:

- level và dispersion của revenue products
- nhu cầu external funds
- cross-plant investment dynamics

đều biến động theo đúng hướng model dự đoán. Đây là phần rất quan trọng vì nó nối good dispersion từ lý thuyết về dữ liệu thật, thay vì chỉ dừng ở một calibration exercise đẹp.

### Kết quả 5: hàm ý cho emerging economies

Authors nhấn mạnh rằng scope cho good dispersion nhỏ hơn ở emerging economies. Nếu vậy, khi so China/India với U.S., phần dispersion “tốt” của U.S. phải được trừ đi trước khi suy ra bad misallocation thuần. Từ đó, chênh lệch misallocation thực sự giữa emerging và developed economies còn lớn hơn nhìn bề ngoài. Quantitatively, paper gợi ý literature trước có thể đã bỏ sót khoảng **10% đến 50%** output benefits from reallocation.

### Diễn giải kinh tế

Bài này không nói dispersion nhìn chung là tốt. Nó nói rằng observable dispersion là một object pha trộn, và muốn suy ra distortions từ nó thì phải hiểu organization of the firm. Đây là một subtle but deep point: cùng một số đo thống kê có thể đi lên vì economy tệ hơn, nhưng cũng có thể đi lên vì firm đang dùng internal allocation để đối phó tốt hơn với một friction khác.

## 7. What is special or elegant about the paper

Điểm đẹp nhất của paper là nó đảo chiều một trực giác đã thành phản xạ trong macro-development-productivity literature: “dispersion cao => misallocation cao”. Authors không bác bỏ trực giác đó bằng lời, mà bằng một model cực kỳ trực diện và một empirical fact cực khó chối là dispersion chủ yếu nằm trong firms.

Điểm đẹp thứ hai là cách bài gắn organization theory vào misallocation. Rất nhiều paper nói về firms như black boxes. Paper này mở chiếc hộp ra và nói: firms là planners, nhưng planners trong một second-best world với frictions riêng của họ. Khi đã nhìn như vậy, within-firm dispersion không còn là chuyện kỳ lạ nữa.

Điểm đẹp thứ ba là hàm ý development rất gọn nhưng mạnh. Chỉ một insight “U.S. có nhiều scope cho good dispersion hơn emerging economies” đã làm thay đổi cách diễn giải cả một literature so sánh misallocation giữa nước giàu và nước nghèo.

## 8. Required background knowledge

### Misallocation literature

Người đọc nên quen với trực giác của Hsieh-Klenow: dispersion trong revenue products thường được diễn giải như evidence của wedges làm marginal products không bằng nhau, từ đó gây output losses. Paper này đối thoại trực tiếp với framework đó.

### Multi-plant firms

Cần có intuition rằng firm nhiều plants không chỉ là “nhiều nhà máy đặt chung tên”. Nó là một tổ chức có thể phân bổ capital, cash flow, managerial attention, và headquarters support giữa các units. Điều đó tạo ra một tầng allocation mà models giữa-firms thường bỏ qua.

### Internal vs external finance

Ý tưởng cốt lõi là external funds đắt, nên firm cố tận dụng internal funds trước. Một khi internal funds khan hiếm, firm phải chọn plants nào được đầu tư ngay và plants nào phải chờ. Đó là gốc của staggered investment.

### Adjustment costs

Fixed và convex adjustment costs khiến investment không thể được frictionlessly spread đều qua các plants. Nếu không có các costs này, logic good dispersion sẽ yếu đi nhiều.

## 9. Limitations and open questions

### Hạn chế chính

1. Good dispersion là một insight rất mạnh nhưng cũng khá model-dependent; cường độ của nó phụ thuộc vào cấu trúc frictions mà authors chọn.
2. Distance giữa plants không chỉ phản ánh information frictions; nó còn có thể correlated với nhiều thứ khác về organization.
3. Paper tập trung vào U.S. manufacturing multi-plant firms, nên external validity sang services, digital firms, hay các nước nghèo hơn cần thận trọng.

### Giả định nhạy cảm

- internal capital markets thật sự hoạt động như kênh bù đắp external finance frictions
- staggered investment là cơ chế chi phối thay vì chỉ là một behavior phụ
- measures của marginal revenue products đủ tốt để nói chuyện về dispersion theo nghĩa kinh tế

### Câu hỏi mở

- Trong sectors nơi intangible capital quan trọng hơn physical capital, good dispersion có còn lớn như vậy không?
- Ở các nước đang phát triển, internal capital markets của business groups có tạo ra good dispersion tương tự hay lại chủ yếu sinh ra bad dispersion do tunneling và agency problems?
- Có thể tách empirical good dispersion và bad dispersion trực tiếp hơn, thay vì chủ yếu dựa vào structure-implied decomposition, không?

## 10. Takeaways for a researcher

1. Đừng quá tin một reduced-form statistic nếu chưa hiểu institution nào tạo ra nó.
2. Một empirical fact tốt có thể buộc cả một literature phải điều chỉnh câu hỏi của mình; trong bài này, đó là fact “two-thirds dispersion is within-firm.”
3. Khi lý thuyết nói một object quan sát được là mixture của nhiều forces, công việc nghiên cứu không chỉ là đo object đó giỏi hơn, mà là giải mixture đó.
4. Organization of the firm không phải phần phụ; nó có thể thay đổi cả welfare interpretation của một statistic aggregate.
5. Đây là ví dụ rất đáng học về cách làm paper “phản biện văn liệu” mà vẫn xây thứ gì đó tích cực và mới, thay vì chỉ nói literature cũ sai.

## 11. Vietnam relevance and extension

### Liên hệ với Việt Nam

Paper này rất liên quan tới Việt Nam ở giao điểm productivity, firm organization, và development.

Thứ nhất, nếu muốn hiểu misallocation ở Việt Nam, ta không thể chỉ nhìn khác biệt giữa firms. Rất nhiều conglomerates, business groups, và firms nhiều cơ sở sản xuất có internal allocation decisions quan trọng. Nếu internal capital markets ở các firms này hoạt động tốt, một phần observed dispersion có thể là good dispersion chứ không phải thuần bad misallocation.

Thứ hai, ngược lại, trong bối cảnh institutional quality và agency problems khác với Mỹ, internal capital markets ở Việt Nam có thể vừa là thuốc vừa là bệnh. Chúng có thể giúp firms vượt qua credit frictions, nhưng cũng có thể bị lạm dụng. Vì vậy ý tưởng good dispersion đặc biệt đáng nghiên cứu ở Việt Nam.

Thứ ba, paper gợi ý rằng khi so misallocation giữa Việt Nam và các nước phát triển, ta có thể đang bỏ sót vai trò của organizational form. Nếu developed economies có nhiều multi-plant firms vận hành internal markets hiệu quả hơn, thì phần dispersion “tốt” của họ cao hơn. Khi đó chênh lệch bad misallocation thật sự giữa Việt Nam và họ còn lớn hơn nhìn bề ngoài.

### Có triển khai được ở Việt Nam không?

Có thể, nhưng sẽ khó và rất đáng giá. Cần:

- dữ liệu plant-level hoặc establishment-level linked to firms
- thông tin về capital allocation, investment timing, và ownership structure
- khả năng nhận diện multi-plant firms và distances / frictions giữa units

### Trở ngại chính

- dữ liệu firm-plant linkage ở Việt Nam không sẵn như U.S. Census
- thông tin chi tiết về nội bộ tập đoàn, luồng vốn nội bộ, và cash reallocation khó tiếp cận
- đo marginal revenue products ở quality đủ cao là thách thức lớn

### Hướng mở rộng cho Việt Nam

1. Nghiên cứu xem dispersion trong revenue products giữa nhà máy cùng một công ty ở Việt Nam lớn đến đâu so với dispersion giữa firms.
2. Kiểm tra xem business groups và tập đoàn nội địa có dùng internal capital markets để stagger investment giữa plants hay không.
3. So sánh firms tư nhân lớn, FDI, và SOEs: ở đâu good dispersion có thể tồn tại, ở đâu bad dispersion lấn át.

### Một vài research question mới cho bối cảnh Việt Nam

1. Trong manufacturing Việt Nam, chênh lệch productivity dispersion giữa multi-plant và single-plant firms nói gì về role của internal capital markets?
2. Liệu các business groups ở Việt Nam đang mitigate hay magnify misallocation khi phân bổ vốn giữa các subsidiaries và plants?
3. Nếu số hóa kế toán-quản trị giúp headquarters theo dõi plants tốt hơn, liệu điều đó làm giảm “bad dispersion” nhưng có thể tăng “good dispersion” theo cơ chế tối ưu second-best hay không?

## 12. Vì sao chọn paper này hôm nay

Mình chọn paper này vì nó thỏa đồng thời nhiều tiêu chí của agent:

- là bài trên **ReStud 2026**, tức top 5 journal economics
- nằm ở giao điểm applied micro về firms/productivity và development qua hàm ý cho emerging economies
- có một conceptual twist rất đáng học
- có public PDF đủ tốt để đọc sâu mà không phải dựa vào nguồn mơ hồ
- quan trọng hơn, sau khi kiểm tra trực tiếp trên repo đích, bài này chưa xuất hiện ở `00_reading`

## 13. Trạng thái lưu trữ và giới hạn thực thi

- GitHub là nơi lưu trữ chính của lượt chạy này.
- Mục tiêu bắt buộc là lưu `analysis.md`; mục tiêu ưu tiên bổ sung là `analysis.html`.
- `analysis.pdf` không phải điều kiện bắt buộc và lượt này không coi là hoàn tất nếu chưa có file PDF thật sự.
- PDF gốc của paper chỉ được coi là đã lưu nếu raw binary file được upload thành công lên repo.
- Nếu môi trường không chuyển được raw PDF vào GitHub trong cùng lượt chạy, trạng thái cuối phải ghi là đã xác minh nguồn PDF nhưng chưa lưu file PDF gốc.
- Google Drive bị bỏ qua nếu không thể chắc chắn tạo đúng Google Doc và tracker trong đúng folder đích.

Trạng thái thực tế của lượt chạy này sẽ được phản ánh trung thực ở GitHub commit, trong email tóm tắt, và trong báo cáo cuối cùng của agent.
