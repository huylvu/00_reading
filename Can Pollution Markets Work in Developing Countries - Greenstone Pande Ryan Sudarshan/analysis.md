# Can Pollution Markets Work in Developing Countries? Experimental Evidence from India

- **Tác giả:** Michael Greenstone, Rohini Pande, Nicholas Ryan, Anant Sudarshan
- **Journal:** The Quarterly Journal of Economics
- **Năm:** 2025, Volume 140, Issue 2, May 2025, pages 1003-1060
- **Ngày agent chạy:** 2026-05-17 (Asia/Saigon)
- **Nguồn bài báo chính:** https://academic.oup.com/qje/article/140/2/1003/8002857
- **DOI:** https://doi.org/10.1093/qje/qjaf009
- **Nguồn PDF tốt nhất đã xác minh để đọc sâu:** bản working paper công khai tại J-PAL https://www.povertyactionlab.org/sites/default/files/research-paper/Greenstone%2C%20et%20al.%202023%20%2522Can%20Pollution%20Markets%20Work%20in%20Developing%20Countries%3F%20Experimental%20Evidence%20from%20India%2522.pdf và trang IDEAS/RePEc xác minh nguồn Warwick TWERPS 1453 tại https://ideas.repec.org/p/wrk/warwec/1453.html
- **Trạng thái lưu trên GitHub:** `analysis.md` và `analysis.html` đã lưu thành công trong repo `huylvu/00_reading` tại thư mục `Can Pollution Markets Work in Developing Countries - Greenstone Pande Ryan Sudarshan/`
- **Trạng thái lưu trên Google Drive:** bỏ qua trong lượt này vì khả năng hiện có chưa cho phép vừa tạo Google-native file vừa bảo đảm đặt đúng vào folder đích `1uNTnzxL4y8_8VQiNa2FPPRMCe6LTHEWm` một cách đáng tin cậy
- **Trạng thái PDF gốc trên GitHub:** chưa lưu; mới xác minh được nguồn PDF công khai
- **Trạng thái analysis.pdf:** chưa tạo

## 1. Metadata

- **Tiêu đề:** Can Pollution Markets Work in Developing Countries? Experimental Evidence from India
- **Tác giả:** Michael Greenstone, Rohini Pande, Nicholas Ryan, Anant Sudarshan
- **Journal:** The Quarterly Journal of Economics
- **Năm:** 2025
- **Field:** Development economics, environmental economics, applied microeconomics
- **Top 5 status:** Có. QJE là top 5 economics journal.
- **Nguồn chính thức:** https://academic.oup.com/qje/article/140/2/1003/8002857
- **Nguồn PDF dùng để phân tích:** working paper public version dated January 27, 2023 trên J-PAL, đối chiếu với metadata của bản QJE 2025 và trang công bố của Rohini Pande
- **Lưu ý phiên bản:** phân tích bên dưới bám chủ yếu vào working paper public PDF, sau đó đối chiếu lại title, journal, năm, và abstract của bản QJE 2025. Những con số headline và framing chính khớp nhau giữa các nguồn đã xác minh.

## 2. Executive summary

Bài này hỏi một câu rất quan trọng cho development economics: liệu một thị trường quyền phát thải có thật sự vận hành được trong bối cảnh nhà nước có năng lực thực thi hạn chế, nơi việc giám sát và cưỡng chế môi trường vốn thường yếu. Đây là một câu hỏi có ý nghĩa lớn vì nhiều nước đang phát triển ô nhiễm rất nặng, nhưng lại chủ yếu dựa vào kiểu regulation command-and-control trên giấy tờ, trong khi compliance thực tế thấp.

Các tác giả trả lời câu hỏi đó bằng một thí nghiệm chính sách quy mô lớn tại Surat, Gujarat, Ấn Độ. 317 nhà máy được đưa vào hạ tầng giám sát phát thải bụi; 162 nhà máy được randomize vào hệ thống emissions trading market cho particulate matter, còn nhóm còn lại tiếp tục ở chế độ chuẩn cũ. Nhờ vậy, paper không chỉ nói về một market design đẹp trên lý thuyết, mà đo được trực tiếp market hoạt động ra sao, phát thải thay đổi thế nào, và chi phí giảm ô nhiễm chênh ra sao.

Ba kết quả headline rất mạnh. Thứ nhất, thị trường thật sự chạy được: trade diễn ra thường xuyên, compliance gần như hoàn hảo, và hai doanh nghiệp không nộp đủ permit ở kỳ đầu bị phạt xong thì compliance về sau gần như tuyệt đối. Thứ hai, nhóm treatment giảm phát thải bụi khoảng 20% đến 30% so với nhóm control, tùy cách xử lý missing CEMS data. Thứ ba, khi so sánh ở cùng mức phát thải, market giảm variable abatement cost khoảng 11% ở mức phát thải treatment và khoảng 14% nếu cố định ở mức phát thải control. Phần benefit-cost cho thấy lợi ích sức khỏe vượt chi phí ít nhất khoảng 25 lần.

Đây là bài rất đáng đọc vì nó lật ngược một nghi ngờ phổ biến trong development: công cụ market-based regulation có thể quá tinh vi để dùng trong môi trường state capacity thấp. Kết quả của paper không nói rằng markets luôn thắng, nhưng nói rằng nếu đo phát thải đủ tin cậy và enforcement đủ credible, thì thị trường không chỉ khả thi mà còn có thể làm tốt hơn cách quản lý truyền thống.

## 3. Research question and motivation

### Câu hỏi trung tâm

Liệu pollution permit markets có thể hoạt động hiệu quả trong các nước đang phát triển, nơi:

- đo phát thải khó và dễ thiếu dữ liệu
- compliance với environmental standards vốn thấp
- regulator không phải lúc nào cũng đủ năng lực để cưỡng chế
- transaction costs và institutional frictions có thể lớn

### Bối cảnh học thuật và thực tiễn

Trong các mô hình kinh điển, emissions trading đạt được mục tiêu môi trường với chi phí thấp nhất bằng cách equalize marginal abatement costs giữa firms. Nhưng lập luận đó thường dựa trên vài giả định mạnh: emissions đo được, firms buộc phải surrender permit chính xác, trading friction thấp, và nhà nước bảo đảm được giá trị của permit như một nghĩa vụ pháp lý thật.

Ở các nước đang phát triển, chính những giả định đó lại là chỗ dễ vỡ nhất. Nhiều nghiên cứu trước trong environmental economics và development cho thấy monitoring yếu, auditor có thể không trung thực, enforcement không nhất quán, và standards trên giấy không đồng nghĩa với compliance ngoài đời. Vì vậy, khoảng trống mà paper này xử lý không chỉ là “market tốt hơn command-and-control không”, mà là “market có sống nổi trong institutional environment khó hay không”.

### Khoảng trống paper lấp vào

Paper lấp đồng thời ba khoảng trống:

1. Thiếu bằng chứng causal rõ ràng về một emissions market trong bối cảnh đang phát triển.
2. Thiếu một counterfactual thực nghiệm sạch để so sánh market với status quo regulation.
3. Thiếu bằng chứng vi mô về chi phí giảm phát thải trong môi trường ô nhiễm cao, nơi người ta thường nghi ngờ rằng pollution reduction sẽ rất đắt.

## 4. Main contribution

### Đóng góp học thuật chính

Đóng góp lớn nhất của paper là biến một ý tưởng policy rất “textbook” thành một randomized policy experiment ngoài đời, rồi đo cả ba thứ quan trọng nhất:

- market có vận hành không
- phát thải có giảm không
- chi phí có thấp hơn không

Đây là đóng góp hiếm vì phần lớn đánh giá về emissions markets ở Mỹ hoặc châu Âu phải dựa nhiều vào counterfactual model-based và không có treatment-control design rõ như ở đây.

### Điểm mới về dữ liệu và design

- Dữ liệu CEMS tần suất cao để đo PM emissions theo thời gian.
- Dữ liệu survey trước và sau can thiệp để nhìn vào capital expenditure và broader input costs.
- Toàn bộ universe of bids and trades trong thị trường permit để recover plant-specific marginal abatement cost curves.
- Random assignment 162 plants vào treatment market, phần còn lại ở command-and-control.

### Vì sao đóng góp này quan trọng trong micro applied và development

Paper là applied micro rất đẹp vì nó dựa trên randomization ở cấp doanh nghiệp để nhận dạng causal effect của một policy regime phức tạp. Đồng thời nó là development economics đúng nghĩa vì câu hỏi không chỉ là efficiency, mà là institutional feasibility dưới năng lực nhà nước hạn chế. Nói cách khác, bài không áp một công cụ của textbook vào developing world một cách ngây thơ; nó kiểm tra chính xác chỗ mà textbook dễ thất bại.

## 5. Identification or methodology

### Thiết kế thực nghiệm

Setting là Surat, một thành phố công nghiệp lớn ở Gujarat. 317 plants trong airshed của thành phố bị mandate lắp Continuous Emissions Monitoring Systems để theo dõi particulate matter. Baseline cho thấy gần một phần ba plant không tuân thủ standard concentration cũ, dù hầu như tất cả đều đã lắp air pollution control devices.

Treatment gồm 162 plants được chuyển sang một emissions market, nơi permit tương ứng với từng kilogram particulate matter. Control plants tiếp tục ở status quo command-and-control regime với concentration standard truyền thống.

### Treatment thực chất thay đổi cái gì

Regulatory bundle ở treatment khác control ở ba chiều:

1. Nghĩa vụ compliance trở thành tradable.
2. Chuẩn quản lý dựa trên pollution load, không chỉ concentration tại một thời điểm.
3. Stringency trên thực tế có thể khác vì cap được đặt và điều chỉnh theo thời gian.

Điểm này rất quan trọng cho cách đọc kết quả. Treatment effect không chỉ là “trade hay không trade”, mà là hiệu ứng của cả một regime mới gồm market + load-based monitoring + enforcement logic mới + stringency path mới.

### Dữ liệu

Paper dùng ba nguồn dữ liệu chính:

1. Hai vòng plant survey, một trước market launch và một khoảng một năm sau.
2. Dữ liệu pollution gồm manual baseline measurements và CEMS high-frequency data trong toàn bộ thời gian vận hành market.
3. Universe of bids and trades từ market operator, gồm cả bids không khớp lệnh.

### Estimation của pollution effect

Ở phần reduced-form, authors ước lượng treatment effect trên log plant-month PM emissions với year-month fixed effects. Vì CEMS reporting bị missing, họ chạy nhiều specification:

- drop missing observations
- inverse-probability reweighting theo khả năng plant báo cáo
- hai rule imputation khác nhau cho missing emissions

Điểm mạnh ở đây là authors không trốn tránh vấn đề missing data. Họ cho người đọc thấy kết quả thay đổi trong một dải hợp lý, thay vì pretending rằng measurement hoàn hảo.

### Estimation của cost effect

Survey data cho thấy gần như không có thay đổi rõ trong capital hay boiler-house input costs. Nhưng authors không dừng ở đó vì họ cho rằng survey khó đo đúng “chi phí cận biên của giảm phát thải”.

Phần đẹp nhất về mặt methodology nằm ở chỗ này: dùng permit bids để recover marginal abatement cost curves ở cấp plant-period. Trong market cạnh tranh, willingness to pay for permits phản ánh marginal abatement cost. Từ variation trong bids theo các mức emissions khác nhau của cùng một plant và period, họ fit heterogeneous MAC curves, rồi dùng chúng để tính chi phí phảnfactual dưới market và dưới các command-and-control counterfactuals.

### Giả định cốt lõi

- Permit bids phản ánh hợp lý marginal abatement costs trong market đủ cạnh tranh.
- Transaction costs của trading đủ nhỏ để bids/trades nói điều gì đó thật về costs.
- Các rule imputation cho missing CEMS data không đảo ngược qualitative result.
- Counterfactual command-and-control regimes được mô hình hóa đủ gần với actual status quo để so sánh meaningful.

### Điểm mạnh của chiến lược nhận dạng

- Randomization làm cho phần pollution effect rất sạch.
- Họ quan sát được cả compliance behavior lẫn market microdata.
- Họ không chỉ đo emissions mà còn đi tới cost-based welfare logic.
- Thị trường được triển khai thật, không phải lab experiment hay stated preference.

### Điểm dễ bị nghi ngờ

- Treatment là bundle, nên khó tách riêng phần nào do tradability, phần nào do load-based regulation, phần nào do stricter cap.
- Missing CEMS data là vấn đề thật; dù authors xử lý cẩn thận, đây vẫn là điểm nhạy.
- Cost savings đến từ structural/revealed-preference model, nên phụ thuộc vào việc bids có phản ánh true MAC hay không.

## 6. Results and interpretation

### Kết quả 1: Thị trường vận hành được

Đây là kết quả underrated nhưng cực quan trọng. Market không bị chết vì institutions yếu. Plants trade nhiều, permit holdings cuối kỳ khác đáng kể so với initial allocation, và unused permits không bị bỏ phí nhiều. Hai doanh nghiệp fail compliance ở kỳ đầu bị regulator phạt, sau đó compliance gần như hoàn hảo. Điều này cho thấy thứ market cần nhất không phải một nhà nước hoàn hảo, mà là một mức enforcement đủ credible để các tác nhân tin rằng permit obligation là thật.

Về mặt kinh tế học thể chế, đây là insight lớn: state capacity không cần hoàn hảo trên mọi margin; chỉ cần đủ để bảo vệ “giá trị pháp lý” của permit thì market có thể tự tổ chức phần còn lại.

### Kết quả 2: Phát thải giảm rõ

Treatment làm giảm PM emissions khoảng 20% đến 30% so với control, tùy cách xử lý missing data. Một specification không imputation cho treatment effect khoảng -0.193 log points; với imputation rules, effect lên tới khoảng -0.282 đến -0.316 log points.

Diễn giải đúng ở đây là:

- market không chỉ reshuffle compliance trên giấy
- nó kéo phát thải thực xuống
- và mức giảm không nhỏ chút nào

Authors cũng khá trung thực rằng effect này phản ánh cả improved compliance lẫn việc cap bị điều chỉnh xuống trong những kỳ đầu. Tức là market giúp thực thi tốt hơn, nhưng nó cũng đi kèm một regulatory path có thể nghiêm hơn status quo.

### Kết quả 3: Survey không thấy cost tăng đáng kể

Capital expenditures cho pollution control devices và broader boiler-house costs không tăng có ý nghĩa thống kê. Không nên đọc kết quả này là “abatement free”. Cách đọc đúng hơn là:

- nhiều plants đã có sẵn thiết bị kiểm soát ô nhiễm từ trước
- vấn đề nằm ở vận hành, compliance, và allocation của abatement effort
- survey measures quá coarse để bắt được chi phí cận biên thật

### Kết quả 4: Market giảm abatement costs khi so ở cùng mức phát thải

Đây là phần kinh tế học đẹp nhất của paper. Khi dùng MAC curves suy ra từ permit bids:

- ở mức phát thải treatment, market giảm variable abatement costs khoảng 11% so với command-and-control
- ở mức phát thải control, cost saving khoảng 14%
- authors còn nhấn mạnh rằng ở mức phát thải 170 tons, chi phí trong command-and-control cao hơn khoảng 12% so với market

Trực giác rất chuẩn: market cho phép plants có MAC thấp abate nhiều hơn và plants có MAC cao abate ít hơn, thay vì bắt mọi plant “đều đều” chạy theo một standard cứng.

### Kết quả 5: Lợi ích sức khỏe vượt chi phí rất xa

Benefit-cost analysis cho thấy health benefits vượt costs ít nhất khoảng 25 lần theo các giả định authors coi là plausible. Dù con số này phụ thuộc vào mapping từ emissions sang mortality benefits, thông điệp định tính vẫn rất mạnh: trong setting ô nhiễm nặng, marginal social benefit của giảm bụi cao tới mức ngay cả moderate efficiency gains cũng có giá trị lớn.

### Điều thật sự nổi bật

Điều nổi bật nhất không phải chỉ là “market tiết kiệm chi phí”, mà là:

- market hoạt động được trong low-capacity setting
- market kéo compliance lên rất mạnh
- và việc giảm ô nhiễm hóa ra không đắt như nhiều người ngại

Nói ngắn gọn: bài cho thấy constraint có thể nằm ở institutions và incentives nhiều hơn là ở công nghệ giảm phát thải thuần túy.

## 7. What is special or elegant about the paper

### Sự đẹp của ý tưởng

Paper đẹp ở chỗ nó nối ba lớp thường bị tách rời:

1. Institutional design: làm sao market tồn tại được trong bối cảnh enforcement yếu.
2. Reduced-form causal evidence: randomization cho thấy market giảm phát thải.
3. Welfare logic: dùng bid data để ước lượng lại chi phí cận biên và đo efficiency gain.

Rất nhiều paper chỉ làm tốt một trong ba lớp này. Paper này làm khá thuyết phục cả ba.

### Sự đẹp của execution

- Không dừng ở “proof of concept” nhỏ.
- Không chỉ đo thái độ hay willingness-to-pay.
- Không chỉ so trước-sau.
- Không chỉ kể case study policy.

Nó là một policy experiment thật, với regulator thật, firms thật, compliance thật, và data thị trường thật.

### Bài học nghiên cứu đáng nhớ

Một bài học hay là khi policy treatment phức tạp, đôi khi cách tốt nhất không phải ép tách treatment thành từng atom ngay từ đầu, mà là đo trung thực performance của whole regime, rồi giải thích cơ chế bằng microdata bổ sung. Paper này làm đúng điều đó.

## 8. Required background knowledge

### Emissions trading / cap-and-trade

Ý tưởng cốt lõi là regulator đặt một tổng lượng phát thải cho phép, chia hoặc bán permit, rồi cho firms trade permit với nhau. Nếu market chạy tốt, marginal abatement costs sẽ được cân bằng tương đối giữa firms, từ đó đạt cùng mức giảm ô nhiễm với chi phí thấp hơn.

### Command-and-control regulation

Đây là kiểu regulation truyền thống: bắt firms lắp thiết bị, tuân một concentration standard, hoặc tuân các rule kỹ thuật cụ thể. Cách này dễ hiểu nhưng thường kém linh hoạt vì không tận dụng được khác biệt về chi phí giảm ô nhiễm giữa firms.

### Load standard vs concentration standard

- **Concentration standard** giới hạn nồng độ hạt bụi trong khí thải tại một điểm đo.
- **Load standard** quan tâm đến tổng khối lượng ô nhiễm thải ra.

Load standard thường gắn hơn với externality thực, nhưng cần measurement tốt hơn.

### Continuous Emissions Monitoring Systems

CEMS là hệ thống đo phát thải liên tục. Nó rất quan trọng cho paper này vì nếu không đo được emissions tương đối thường xuyên và đáng tin, permit market sẽ mất nền tảng.

### Marginal abatement cost

MAC là chi phí để giảm thêm một đơn vị ô nhiễm. Firms có MAC khác nhau. Nếu bắt mọi firm giảm giống nhau, tổng chi phí thường cao hơn trường hợp cho phép reallocation qua trading.

### Randomized controlled trial ở cấp doanh nghiệp/chính sách

RCT ở đây không phải phát voucher cho hộ dân, mà là randomize cả một regulatory regime ở cấp plant. Người đọc nên quen với ý tưởng treatment assignment ở cấp firm và measurement bằng admin/environmental data.

### Missing data and imputation

Vì CEMS data không hoàn hảo, authors phải dùng nhiều rule để xử lý missing emissions. Với người đọc econometrics, đây là chỗ đáng chú ý vì kết quả phải bền vững với cách xử lý data gaps.

## 9. Limitations and open questions

### 1. Treatment là một bundle

Ta không thể từ paper này nói thật sạch rằng “tradability tự nó” tạo ra bao nhiêu phần effect. Treatment đồng thời thay:

- compliance mechanism
- basis of regulation
- thực tế stringency

Nên paper cho hiệu quả của whole policy package hơn là decomposition cực sạch của từng thành phần.

### 2. Missing CEMS data là điểm nhạy

Authors làm rất đúng khi báo cáo nhiều specification, nhưng vấn đề reporting vẫn là chỗ người đọc cẩn thận phải theo dõi. Kết quả không biến mất, nhưng magnitude phụ thuộc vào imputation rule.

### 3. Cost estimates phụ thuộc vào bidding behavior

Nếu bids phản ánh strategic behavior mạnh, market power, hoặc các friction khác ngoài MAC, thì structural interpretation của cost savings có thể bị nhiễu.

### 4. External validity

Surat có một lịch sử hợp tác khá dài giữa nhóm nghiên cứu và regulator, có hạ tầng CEMS, và có thiết kế institutional hỗ trợ market. Không chắc mọi bang ở Ấn Độ hay mọi nước đang phát triển có thể copy nguyên xi.

### 5. Tác động dài hạn

Paper chủ yếu cho thấy medium-run performance của market. Câu hỏi mở là:

- firms có đầu tư công nghệ sạch hơn trong dài hạn không
- regulator có duy trì enforcement credibility không
- market có giữ thanh khoản nếu mở rộng phạm vi không

## 10. Takeaways for a researcher

1. Nếu câu hỏi policy đủ lớn, hãy nghĩ tới evaluation của cả regime chứ không chỉ một incentive nhỏ lẻ.
2. Randomization vẫn có thể dùng cho institutional reforms phức tạp, không chỉ cho household interventions.
3. Khi outcome chính có measurement problems, đừng che giấu; hãy biến nó thành một phần của design và robustness strategy.
4. Dữ liệu administrative hoặc market microdata thường cho insight sâu hơn survey khi mục tiêu là cost hoặc mechanism.
5. Một contribution rất mạnh là nối reduced-form causal evidence với welfare analysis có cấu trúc.
6. Những setting bị coi là “quá yếu thể chế để dùng công cụ tinh vi” đôi khi lại là nơi giá trị biên của thiết kế đúng lớn nhất.
7. Policy relevance mạnh nhất thường đến khi paper chỉ ra không chỉ “có hiệu quả” mà còn “vì sao trước đây công cụ này bị cho là không khả thi”.

## 11. Vietnam relevance and extension

### Paper này có liên quan gì với Việt Nam

Rất liên quan. Việt Nam cũng đối diện ba bài toán tương tự:

- ô nhiễm không khí và phát thải công nghiệp là vấn đề lớn ở một số cụm công nghiệp và đô thị
- command-and-control regulation có thể tồn tại trên giấy nhưng enforcement và monitoring không đồng đều
- chi phí quản lý môi trường thường được nhìn như trade-off với tăng trưởng công nghiệp

Paper này gợi ý rằng nếu Việt Nam đầu tư đúng vào measurement và enforcement credibility, thì market-based regulation không nhất thiết là một “xa xỉ thể chế”.

### Có triển khai ý tưởng này ở Việt Nam được không

Có thể, nhưng cần vài điều kiện tiền đề:

- có danh sách plant nguồn điểm đủ rõ
- có hạ tầng đo phát thải liên tục đủ đáng tin ở một sector hoặc một airshed cụ thể
- có cơ quan quản lý môi trường sẵn sàng dùng dữ liệu đó để gắn nghĩa vụ compliance thật
- có khung pháp lý cho permit, penalty, và dispute resolution
- có một thị trường hoặc platform giao dịch đủ đơn giản để doanh nghiệp dùng được

### Trở ngại chính nếu áp dụng ở Việt Nam

- chất lượng và chuẩn hóa dữ liệu đo phát thải
- năng lực audit thiết bị đo và xử lý non-reporting
- nguy cơ doanh nghiệp nhỏ gặp khó với compliance technology
- khó khăn pháp lý trong việc biến permit thành nghĩa vụ có thể cưỡng chế
- nỗi lo political economy nếu sector bị ảnh hưởng tập trung

### Hướng mở rộng phù hợp cho Việt Nam

1. **Pilot ở một cụm công nghiệp hoặc một ngành phát thải tập trung**, ví dụ vật liệu xây dựng, nhiệt điện quy mô vừa, hoặc cụm lò hơi công nghiệp.
2. **So sánh load-based regulation với concentration-based regulation** trước khi đi tới tradability đầy đủ.
3. **Kết hợp CEMS với third-party audit và cơ chế phạt cho missing data**, vì paper này cho thấy monitoring incentives là nút thắt then chốt.

### 1 đến 3 research questions cho bối cảnh Việt Nam

1. Liệu chuyển từ concentration standard sang load-based monitoring trong các cụm công nghiệp ở Việt Nam có tự nó đã nâng compliance ngay cả trước khi cho trade permit hay chưa?
2. Trong các ngành có heterogeneity lớn về MAC, permit trading có thể cắt giảm chi phí compliance bao nhiêu so với một uniform technical standard?
3. Cơ chế nào quan trọng hơn trong bối cảnh Việt Nam: increased enforcement credibility, better measurement, hay tradability itself?

## 12. Vì sao bài này được chọn hôm nay

Bài này được chọn vì hội đủ bốn tiêu chí cùng lúc:

- nằm trong top 5 journal economics
- thuộc đúng development/applied micro
- có thiết kế thực nghiệm và empirical strategy rất đáng học
- có hàm ý chính sách cực mạnh cho các nước thu nhập trung bình, trong đó có Việt Nam

So với nhiều bài top 5 khác rất mới nhưng thiên về theory hoặc không đủ gần development, paper này vừa chắc về mặt nguồn, vừa giàu nội dung để làm một morning briefing thật hữu ích.

## 13. Ghi chú trung thực về trạng thái lưu trữ

- `analysis.md`: đã lưu thành công lên GitHub
- `analysis.html`: đã lưu thành công lên GitHub
- `analysis.pdf`: chưa tạo
- **PDF gốc của paper:** chưa lưu lên GitHub trong lượt này. Tôi xác minh được nguồn PDF công khai rất tốt, nhưng chưa có raw PDF binary sẵn sàng để upload qua GitHub trong môi trường hiện tại.
- **Google Drive:** bị bỏ qua có chủ đích vì chưa có tuyến đặt file đúng folder đích với mức độ chắc chắn đủ cao.