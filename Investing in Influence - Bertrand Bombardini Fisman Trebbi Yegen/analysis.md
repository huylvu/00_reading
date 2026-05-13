# Investing in Influence: Investors, Portfolio Firms, and Political Giving

- **Tác giả:** Marianne Bertrand, Matilde Bombardini, Raymond Fisman, Francesco Trebbi, Eyub Yegen
- **Journal:** *The Review of Economic Studies* (advance article)
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-13
- **Nguồn chính:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdag010/8440167
- **Nguồn PDF dùng để phân tích:** Public manuscript trên Boston University, bản tháng 6/2024: https://www.bu.edu/econ/files/2024/07/investing-in-influence-investors-portfolio-firms.pdf
- **Nguồn PDF đối chiếu thêm:** NBER Working Paper 30876, tháng 1/2023: https://www.nber.org/system/files/working_papers/w30876/w30876.pdf
- **Lý do chọn:** Đây là một paper top 5 rất mới trong applied micro/political economy. Bài đặt ra một câu hỏi lớn nhưng đo bằng một empirical design rất gọn: institutional investors có khuếch đại political influence của chính họ thông qua portfolio firms hay không.
- **Trạng thái lưu trên GitHub:** `analysis.md` và `analysis.html` đã được lưu trong repo `huylvu/00_reading` tại thư mục `Investing in Influence - Bertrand Bombardini Fisman Trebbi Yegen/`. `analysis.pdf` chưa tạo. PDF gốc của paper chưa được lưu dưới dạng file nhị phân trong repo.
- **Trạng thái lưu trên Google Drive:** Bỏ qua trong lượt chạy này vì bộ công cụ hiện có không cho phép mình tạo Google Doc và tracker trong đúng folder đích một cách đủ chắc chắn.

## Executive summary

Paper hỏi liệu khi một institutional investor mua một cổ phần đủ lớn trong một công ty niêm yết, corporate PAC của công ty đó có bắt đầu cho tiền theo mẫu chính trị giống investor hơn hay không. Thay vì nhìn governance qua voting, compensation, hay product market behavior, bài nhìn vào political giving như một cửa sổ để quan sát việc quyền lực sở hữu có được chuyển thành ảnh hưởng chính trị hay không.

Câu trả lời chính là có. Sau khi một investor mua stake lớn, PAC giving của firm trở nên giống PAC giving của investor hơn một cách có ý nghĩa kinh tế và thống kê. Trong specification ưa thích của tác giả, xác suất firm PAC cho tiền một chính trị gia mà investor PAC cũng ủng hộ tăng khoảng 31% sau acquisition. Kết quả này vẫn xuất hiện trong các acquisition do stock index inclusion tạo ra, tức là trong một setting gần exogenous hơn.

Điểm đáng đọc nhất là bài không dừng ở một correlation đẹp. Tác giả cố đi thêm ba bước: dùng index-inclusion acquisitions để xử lý selection, dùng cosine-similarity dynamics để lập luận rằng firm điều chỉnh về phía investor chứ không phải ngược lại, và khai thác heterogeneity để cho thấy influence này có vẻ gắn với political preferences riêng của investor managers hơn là tối đa hóa lợi nhuận cho firm.

## Research question and motivation

### Câu hỏi trung tâm

Institutional investors có ảnh hưởng lên political strategy của portfolio firms hay không, và nếu có thì influence đó phản ánh tối đa hóa lợi nhuận cho firm hay phản ánh political preferences của chính các investor managers?

### Bối cảnh học thuật và thực tiễn

Văn liệu governance gần đây quan tâm rất mạnh tới sự trỗi dậy của institutional ownership. Một nhánh nhấn mạnh concentrated ownership có thể cải thiện monitoring. Nhánh khác lo ngại về common ownership, agency problems của asset managers, và việc một số ít fund managers kiểm soát lượng phiếu bầu rất lớn trong nền kinh tế.

Paper này đẩy cuộc tranh luận sang political economy. Nếu asset managers có thể làm portfolio firms điều chỉnh political giving theo ý mình, thì quyền lực kinh tế không chỉ tập trung trong product markets hay shareholder voting, mà còn lan sang influence-seeking trong chính trị.

### Khoảng trống mà paper lấp vào

Phần lớn nghiên cứu trước đó nhìn political spending của firms như một công cụ theo đuổi lợi ích kinh doanh của chính firm. Paper này đặt lại giả định đó: political voice của firm có thể không hoàn toàn là “voice of the firm”, mà còn là voice của những người đang nắm quyền kiểm soát ownership phía sau firm.

## Main contribution

1. Bài đưa ra một framing rất mạnh: rise of institutional ownership có thể dẫn tới concentration of political influence.
2. Tác giả ghép ownership data của 13-F institutional investors với dữ liệu PAC giving của cả investors lẫn firms trong giai đoạn dài 1980-2018, rồi xây dựng investor-firm-politician panel để xem sau một block acquisition, pattern cho tiền có hội tụ không.
3. Paper dùng acquisitions gắn với stock index inclusions như một nguồn variation gần exogenous hơn. Đây là nước đi rất đẹp, vì nếu một index fund buộc phải mua firm do firm được thêm vào index, thì acquisition đó ít bị driven bởi political alignment sẵn có hơn nhiều so với acquisitions thông thường.
4. Bài không chỉ chứng minh “có effect” mà còn bóc tách motivation và channel. Kết quả nghiêng về cách hiểu rằng managers của firms cater to investors khi cần support trong proxy fights, còn investors thì có vẻ đẩy political alignment vì political tastes của họ, chứ không đơn thuần vì business strategy của firm.

## Identification or methodology

### Dữ liệu và đơn vị quan sát

Mẫu chính gồm các institutional investors thuộc diện 13-F và các firms niêm yết trong danh mục của họ trong giai đoạn 1980-2018. Public manuscript cho biết authors quan sát các block purchases khi investor lần đầu nắm hơn 1% cổ phần của firm, rồi ghép với PAC giving theo politician và election cycle.

Đơn vị quan sát cốt lõi trong main specification là investor-firm-congressional district-election cycle. Ý tưởng là rất trực diện: nếu investor cho tiền vào politician A, thì sau acquisition, firm có bắt đầu cho tiền vào politician A nhiều hơn trước không?

### Main empirical design

Thiết kế cơ bản là staggered event-style diff-in-diff quanh thời điểm investor lần đầu mua large stake trong firm. Outcome là PAC giving của firm tới politician hoặc các measure về similarity giữa PAC giving của investor và firm. Tác giả dùng nhiều tầng fixed effects, và specification ưa thích là một bản rất “saturated”, nhằm hấp thụ tối đa heterogeneity cố định theo investor, firm, cycle, và district.

Trực giác của coefficient chính là: sau acquisition, slope giữa investor giving và firm giving có dốc hơn không. Nếu có, và nếu effect không chỉ phản ánh selection, ta có bằng chứng rằng ownership đi kèm influence lên political activity.

### Chiến lược nhận dạng quan trọng nhất

Lo ngại lớn nhất là omitted variables: investor có thể chọn mua những firms vốn đã có political agenda giống mình; hoặc cả investor và firm cùng phản ứng với một shock chính trị chung. Bài xử lý điều này bằng cách:

1. Thu hẹp sang passive investors.
2. Tập trung vào acquisitions do stock index inclusions tạo ra.
3. So sánh dynamic pattern trước và sau acquisition.
4. Kiểm tra divestment cho một đối xứng ngược chiều.

Nếu effect xuất hiện cả ở index-induced acquisitions, lập luận “investor mua vì đã cùng màu chính trị từ trước” yếu đi đáng kể.

### Investor influences firm, hay firm influences investor?

Đây là chỗ paper khéo. Correlation tăng lên sau acquisition chưa cho biết ai điều chỉnh theo ai. Tác giả xây dựng cosine similarity của mỗi tổ chức qua hai election cycles liên tiếp. Nếu investor influence firm, thì pattern giving của firm phải “gãy” hơn quanh acquisition, còn pattern của investor ổn định hơn. Kết quả đi đúng hướng đó: firm thay đổi nhiều hơn investor quanh acquisition.

### Mechanisms

Paper chia mechanisms thành hai lớp:

1. **Tại sao firm managers nghe theo investor?** Khi firm đối mặt với shareholder proposal votes hoặc ESG crises, managers cần sự ủng hộ của large investors hơn. Tác giả cho thấy post-acquisition co-movement mạnh hơn rõ trong các giai đoạn như vậy.
2. **Tại sao investor muốn influence political giving?** Nếu vì firm profit maximization, ta kỳ vọng giving sẽ hướng nhiều hơn tới các politician có strategic relevance với firm. Nhưng bài lại tìm thấy bằng chứng nghiêng về hướng ngược lại: giving dịch ra xa các “business-relevant politicians”, effect mạnh hơn ở investors có partisan giving cao hơn, và firm PAC giving còn đồng chuyển mạnh với individual political donations của employees/managers bên investor.

### Điểm mạnh và điểm dễ bị nghi ngờ

- Câu hỏi khó quan sát được biến thành một design khá đo trực tiếp.
- Index inclusion là một nguồn variation nhận dạng rất hợp lý.
- Có nhiều bài test cơ chế thay vì dừng ở main effect.
- Đây vẫn là staggered adoption design, nên luôn có rủi ro từ bad comparisons trong two-way fixed effects.
- Index inclusion không phải “random tuyệt đối”; vẫn có thể đi kèm thay đổi về visibility, investor base, hay scrutiny.
- PAC giving chỉ là một lát cắt của political influence; nó quan trọng nhưng không bao trùm lobbying, access, agenda setting, hay informal pressure.

## Results and interpretation

### Kết quả chính

Kết quả headline là sau khi investor mua một large stake, PAC giving của firm đồng chuyển mạnh hơn với PAC giving của investor. Trong preferred specification, xác suất firm PAC donate tới một politician mà investor PAC cũng hỗ trợ tăng khoảng 31%.

Khi dùng cosine similarity ở cấp investor-firm pair, sự giống nhau trong pattern giving cũng tăng rõ sau acquisition. Trong event-study, similarity tăng từ acquisition period và còn tăng thêm trong các cycle sau đó.

### Kết quả nhận dạng mạnh hơn

Ở subsample acquisitions do stock index inclusions, effect vẫn còn. Đây là một piece of evidence rất quan trọng, vì nó nói rằng convergence không chỉ là do politically aligned investors chọn politically aligned firms.

### Kết quả về chiều ảnh hưởng

Firm dường như là phía điều chỉnh mạnh hơn. Bằng chứng từ changes in cosine similarity qua các cycle cho thấy giving của investor ổn định hơn, còn giving của firm “bẻ” theo acquisition hơn.

### Kết quả về cơ chế

- Co-movement mạnh hơn nhiều khi firm có shareholder proposal vote.
- Co-movement cũng mạnh hơn trong thời kỳ ESG-related pressure/crisis.
- Effect lớn hơn ở investors mang tính partisan cao hơn.
- Effect lớn hơn ở privately owned investors.
- Khi investor có board seat tại firm, alignment còn mạnh hơn.
- Firm PAC giving đồng chuyển mạnh với individual political donations của employees/managers bên investor, thậm chí mạnh hơn tương quan với investor PAC trong một số specification.

### Diễn giải kinh tế

Diễn giải hợp lý nhất là large investors có thể dùng quyền lực sở hữu và quyền lực bỏ phiếu để làm managers chú ý tới political preferences của họ. Managers, nhất là khi đang cần investor support, có động cơ “cater”. Kết quả không giống một câu chuyện firm profit-maximizing political strategy thuần túy, mà giống một governance distortion trong đó resources của firm bị kéo sang political objectives của người kiểm soát ownership.

Điều nổi nhất là bài không chỉ nói firm “thêm” politicians mới theo ý investor, mà còn cho thấy composition của giving nghiêng ra xa các politicians có strategic relevance với business của firm. Đây là chi tiết làm lập luận “không phải chỉ vì shareholder value” mạnh lên rất nhiều.

## What is special or elegant about the paper

1. Bài lấy một vấn đề rất lớn là institutional investors có quyền lực chính trị không rồi biến nó thành một object quan sát được: sự đồng chuyển trong PAC giving sau acquisition.
2. Logic direction-of-influence rất khéo. Thay vì chỉ chứng minh similarity tăng lên, tác giả còn hỏi ai là bên dịch chuyển nhiều hơn quanh acquisition.
3. Chuỗi bằng chứng rất nhất quán: main effect, index-inclusion subsample, divestment, direction-of-adjustment test, shareholder-vote heterogeneity, employee-giving correlation, board-seat channel.
4. Paper không overclaim về welfare; authors chỉ ra vì sao tập bằng chứng này collectively khó hòa giải với story profit maximization.

## Required background knowledge

- **13-F filings:** báo cáo holdings của các institutional investment managers lớn tại Mỹ.
- **Corporate PACs:** kênh hợp pháp để tổ chức huy động và phân bổ political contributions trong khuôn khổ luật Mỹ.
- **Stock index inclusions:** khi một firm được thêm vào một index lớn như S&P 500 hoặc Russell 2000, các passive index funds theo index đó bị “cưỡng bức” phải nắm firm; đây là nguồn variation gần exogenous quen thuộc trong applied micro/finance.
- **Staggered difference-in-differences:** treatment xảy ra ở nhiều thời điểm khác nhau cho các investor-firm pairs khác nhau; rất mạnh nhưng cần cẩn trọng với bias trong two-way fixed effects.
- **Cosine similarity:** thước đo mức độ giống nhau giữa hai vector phân bổ, ở đây là pattern PAC giving.
- **Managerial catering:** managers có thể chiều ý investors không nhất thiết vì investors ra lệnh công khai, mà vì managers biết mình cần votes và support từ những owners lớn.

## Limitations and open questions

1. PAC giving chỉ là một phần của political influence; còn lobbying, access, agenda setting, hay soft influence không được đo trực tiếp.
2. Board seats và proxy-vote pressure là suggestive, nhưng paper không quan sát trực tiếp các conversations giữa investors và managers.
3. Bối cảnh Mỹ có PAC system, disclosure rules, và institutional investor landscape rất đặc thù; mang nguyên xi kết quả sang nơi khác sẽ nguy hiểm.
4. Ngay cả khi influence phản ánh personal preferences, vẫn còn câu hỏi mở là mức độ welfare loss cụ thể là bao nhiêu, ai chịu chi phí, và có những trường hợp nào investor influence lại có external benefits hay không.
5. Các câu hỏi tiếp theo rất hay gồm: effect có lan sang lobbying hay không, governance nội bộ của asset managers có làm effect khác đi không, và pass-through voting hoặc disclosure reform có bó được channel này không.

## Takeaways for a researcher

1. Một research question mạnh thường đến từ việc nối hai literatures vốn nói chuyện với nhau chưa đủ: ở đây là governance và political economy.
2. Nếu outcome chính khó causal, hãy tìm một setting buộc actors phải hành động, như index inclusions.
3. Một paper thuyết phục không chỉ cần main effect; nó cần cả “who moves”, “when it is stronger”, và “why this likely reflects mechanism X rather than Y”.
4. Heterogeneity có giá trị nhất khi nó thực sự phân biệt competing explanations.
5. Sau bài này, corporate political giving khó còn được xem đơn giản là lựa chọn của firm mà thôi.

## Vietnam relevance and extension

### Mức độ liên quan

Bối cảnh Việt Nam khác Mỹ rất xa ở campaign finance, PACs, và thị trường vốn. Nhưng intuition cốt lõi của paper vẫn rất liên quan: khi ownership hoặc quyền kiểm soát tập trung vào một số định chế lớn, preferences của họ có thể lan vào các quyết định “phi sản xuất” của doanh nghiệp.

### Có thể triển khai ở Việt Nam không?

Có thể, nhưng không nên bê nguyên outcome. Ở Việt Nam, thay vì PAC giving, nên nghĩ tới:

- đóng góp vào các quỹ, hiệp hội, hay chương trình có yếu tố chính sách,
- lựa chọn tham gia business associations,
- hành vi CSR hoặc tài trợ có hàm ý xây dựng quan hệ,
- phân bổ lobbying mềm thông qua gặp gỡ, kiến nghị, hoặc hợp tác với cơ quan công quyền.

### Điều kiện cần

- Dữ liệu ownership đủ chi tiết theo thời gian, nhất là institutional blocks.
- Dữ liệu về board seats, đại diện sở hữu, hoặc quyền biểu quyết.
- Một outcome quan sát được phản ánh non-market strategy của firm.
- Một shock đủ sạch, chẳng hạn index inclusion, room changes, SCIC transactions, regulatory reclassification, hoặc một chương trình thoái vốn/niêm yết tạo thay đổi ownership tương đối exogenous.

### Trở ngại chính

- Thiếu dữ liệu công khai tương đương PAC giving.
- Quan hệ chính trị thường đi qua kênh ít disclosure hơn.
- Institutional investor ecosystem ở Việt Nam còn khác nhiều so với Mỹ.
- Ownership nhà nước và ownership gia đình có thể quan trọng hơn asset managers trong nhiều ngành.

### Hướng mở rộng cho Việt Nam

1. **Institutional ownership và non-market strategy của firms niêm yết:** dùng index changes hoặc room shocks để xem firms có đổi hành vi CSR, sponsorship, hay membership trong các hiệp hội ngành theo hướng giống owners lớn hơn không.
2. **State capital representatives và chiến lược quan hệ của doanh nghiệp:** thay investor tư nhân bằng đại diện vốn nhà nước, xem việc thay đổi đại diện hoặc cấu trúc sở hữu có kéo theo thay đổi trong hành vi quan hệ với cơ quan quản lý hoặc đối tác công không.
3. **Board interlocks như kênh influence:** nếu có dữ liệu hội đồng quản trị tốt, có thể kiểm tra liệu board representation của cổ đông lớn có làm doanh nghiệp điều chỉnh các khoản chi “ngoài core business” theo hướng ưu tiên của owner hay không.

### Một số research questions khả thi

1. Khi một quỹ lớn hoặc cổ đông tổ chức vượt qua một ngưỡng sở hữu trong doanh nghiệp Việt Nam, doanh nghiệp có thay đổi pattern tài trợ, CSR, hoặc hiệp hội theo hướng giống nhóm cổ đông đó hơn không?
2. Các cú shock index inclusion trên HOSE/HNX có làm firms điều chỉnh non-market strategies theo cấu trúc investor base mới không?
3. Board representation của cổ đông lớn có làm doanh nghiệp dịch nguồn lực khỏi hoạt động có strategic relevance trực tiếp sang hoạt động quan hệ hoặc xây dựng ảnh hưởng hay không?

## Kết luận ngắn

Đây là một applied paper rất đáng học vì nó làm ba việc cùng lúc: đặt ra một câu hỏi lớn, tìm được outcome quan sát phù hợp cho câu hỏi đó, và xây một chuỗi bằng chứng đủ dày để tách influence khỏi selection. Cái đẹp của paper không nằm ở một regression duy nhất, mà ở cách authors khiến người đọc thấy rằng sự tập trung ownership có thể đồng thời là sự tập trung political voice.

## Storage notes

- **GitHub repo đích:** `huylvu/00_reading`
- **GitHub folder:** `Investing in Influence - Bertrand Bombardini Fisman Trebbi Yegen/`
- **`analysis.md`:** đã lưu trên GitHub tại `https://github.com/huylvu/00_reading/blob/main/Investing%20in%20Influence%20-%20Bertrand%20Bombardini%20Fisman%20Trebbi%20Yegen/analysis.md`
- **`analysis.html`:** đã lưu trên GitHub tại `https://github.com/huylvu/00_reading/blob/main/Investing%20in%20Influence%20-%20Bertrand%20Bombardini%20Fisman%20Trebbi%20Yegen/analysis.html`
- **`analysis.pdf`:** chưa tạo trong lượt chạy này.
- **PDF gốc của paper:** đã xác minh được nguồn PDF công khai phù hợp, nhưng chưa lưu file nhị phân lên GitHub.
- **Google Drive:** bỏ qua trong lượt này.