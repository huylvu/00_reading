# Complete Pass-Through in Levels

- **Tác giả:** Kunal Sangani
- **Journal:** The Quarterly Journal of Economics
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-13
- **Nguồn bài báo chính:** https://academic.oup.com/qje/article/141/2/1077/8497409
- **Nguồn PDF dùng để phân tích:** https://kunalsangani.com/files/complete_passthrough_live.pdf
- **Ghi chú về PDF:** Bản PDF công khai dùng để đọc sâu là author PDF dài 107 trang trên website tác giả. Bài đã xuất bản chính thức trên QJE, nhưng trong lượt chạy này môi trường không tải được raw PDF bytes từ nguồn ngoài về cục bộ để lưu lại như file nhị phân.
- **Trạng thái lưu trên GitHub:** `analysis.md` và `analysis.html` đã được lưu thành công trong thư mục `Complete Pass-Through in Levels - Sangani/` của repo `huylvu/00_reading`; `analysis.pdf` không được tạo trong lượt này; PDF gốc của paper đã xác minh được nguồn nhưng chưa tải và chưa lưu lại như file nhị phân.
- **Trạng thái lưu trên Google Drive:** Bỏ qua có chủ đích trong lượt chạy này vì chưa có workflow đủ chắc để tạo Google Doc và tracker đúng folder đích mà không báo cáo quá mức.

## Executive summary

Paper hỏi một câu rất cơ bản nhưng cũng rất khó chịu đối với trực giác quen thuộc trong macro và IO: khi chi phí đầu vào tăng, doanh nghiệp thực sự truyền phần tăng chi phí đó sang giá bán theo logic nào. Văn liệu thường đo pass-through bằng phần trăm, rồi kết luận rằng pass-through là không hoàn toàn. Sangani cho rằng cách đo này che lấp một quy luật khác quan trọng hơn: trong nhiều thị trường, doanh nghiệp gần như truyền chi phí theo **mức tuyệt đối**, tức là tăng 1 đô la chi phí thì tăng khoảng 1 đô la giá bán.

Để trả lời câu hỏi đó, bài ghép rất cẩn thận đơn vị giữa chi phí đầu vào và giá bán đầu ra, rồi đo pass-through trong retail gasoline, nhiều mặt hàng thực phẩm, và panel manufacturing industries. Kết quả xuyên suốt là pass-through in levels thường rất gần 1, trong khi pass-through in logs lại thấp hơn 1. Sự kết hợp này phù hợp với một thế giới có **additive markups** hay fixed unit margins hơn là fixed percentage markups.

Bài đáng đọc vì nó làm ba việc cùng lúc. Thứ nhất, nó chỉ ra rằng một stylized fact lâu nay có thể đã bị diễn giải sai vì chọn sai thước đo. Thứ hai, nó nối dữ liệu vi mô về giá với câu hỏi lý thuyết về dạng cầu và markup. Thứ ba, nó đưa kết quả vi mô đó lên một ứng dụng vĩ mô rất hay: giải thích vì sao các cú sốc commodity có thể tạo ra bất bình đẳng lạm phát theo thu nhập ngay cả trong cùng một ngành hàng.

## Research question and motivation

### Câu hỏi trung tâm

Khi một cú sốc chi phí chung tác động lên toàn bộ doanh nghiệp trong một thị trường, doanh nghiệp pass through chi phí đó sang giá theo phần trăm hay theo mức tuyệt đối? Và cách đo đúng sẽ kéo theo diễn giải nào về markup, demand curvature, profits, entry, cũng như động học lạm phát?

### Động lực học thuật

Một khối lớn văn liệu macro, trade, và pass-through đo phản ứng giá bằng log changes. Theo thước đo này, 10 phần trăm tăng chi phí thường dẫn tới mức tăng giá nhỏ hơn 10 phần trăm, từ đó sinh ra kết luận quen thuộc rằng pass-through là incomplete. Nhưng nếu giá bán ban đầu vốn đã cao hơn marginal cost vì doanh nghiệp có margin dương, thì cùng một thay đổi 1 đô la sẽ tạo ra phần trăm thay đổi nhỏ hơn ở giá bán so với ở chi phí. Nghĩa là incomplete log pass-through chưa chắc đồng nghĩa với incomplete pass-through về mặt kinh tế học thực chất.

### Khoảng trống mà paper lấp vào

Bài này lấp ba khoảng trống. Một là, nó biến ý tưởng pass-through in levels từ vài bối cảnh riêng lẻ thành một regularity có hệ thống ở nhiều thị trường. Hai là, nó cho thấy stylized fact này xung đột trực diện với workhorse models dùng homothetic demand và multiplicative markups. Ba là, nó chỉ ra hệ quả phân phối rất cụ thể của regularity đó đối với inflation inequality.

## Main contribution

### 1. Đổi đơn vị đo, đổi hẳn diễn giải

Đóng góp quan trọng nhất là cho thấy nhiều bằng chứng “incomplete pass-through” thật ra là complete pass-through nếu đo bằng levels. Đây không phải trò chơi ngôn ngữ. Nó thay đổi luôn benchmark mà ta dùng để đánh giá mô hình pricing.

### 2. Kết nối vi mô giá với dạng markup

Nếu doanh nghiệp giữ fixed percentage markup, pass-through in levels của common cost shock thường phải lớn hơn 1 khi markup dương. Ngược lại, nếu doanh nghiệp giữ fixed additive markup, pass-through in levels tự nhiên gần 1. Bài cho thấy dữ liệu nghiêng mạnh về vế thứ hai.

### 3. Dùng nhiều bối cảnh dữ liệu để kiểm tra cùng một logic

Bài không chỉ dựa vào một market. Nó đi từ gas stations ở Perth, sang six staple food products của Mỹ, rồi tới manufacturing industries. Khi cùng một pattern lặp lại ở nhiều nơi, độ tin cậy của stylized fact tăng lên đáng kể.

### 4. Nối vi mô sang vĩ mô và phân phối

Paper không dừng ở reduced-form pricing. Nó xây dựng lớp demand systems shift-invariant để rationalize pass-through in levels, rồi nhúng intuition đó vào input-output model. Ứng dụng cuối cùng về inflation inequality làm cho paper không chỉ đẹp về mặt pricing, mà còn giàu ý nghĩa chính sách.

## Identification or methodology

## Khung thực nghiệm chung

Ý tưởng xuyên suốt là đo:

- **Pass-through in levels:** giá đầu ra tăng bao nhiêu đô la khi chi phí đầu vào tăng 1 đô la.
- **Pass-through in logs:** giá đầu ra tăng bao nhiêu phần trăm khi chi phí đầu vào tăng 1 phần trăm.

Nếu doanh nghiệp có công thức giá kiểu `p = c + w + m`, với `m` là additive markup cố định, thì pass-through in levels sẽ gần 1 nhưng log pass-through có thể thấp hơn 1 do tồn tại khoảng chênh giữa price và cost. Đây là intuition cốt lõi của paper.

## Retail gasoline

Với gasoline, tác giả dùng dữ liệu hàng tuần về gần như toàn bộ trạm xăng ở Perth, Australia và ước lượng distributed-lag regression của thay đổi giá bán theo thay đổi chi phí wholesale qua nhiều độ trễ. Vì wholesale prices rất persistent, bài làm việc trên first differences thay vì levels/log-levels để tránh suy luận giả từ chuỗi gần unit root. Tác giả còn kiểm tra Granger causality để bảo vệ chiều nhân quả từ upstream cost sang downstream price.

Điểm mạnh ở đây là đầu vào và đầu ra được match gần như hoàn hảo về đơn vị: bao nhiêu cent tăng ở wholesale gasoline thì retail gasoline tăng bao nhiêu cent. Đây là một setting rất sạch để đo pass-through in levels.

## Food products

Với food products, khó hơn nhiều vì cần biết chính xác bao nhiêu commodity input đi vào một đơn vị hàng bán lẻ. Tác giả ghép Average Price Data của BLS với IMF commodity prices và dùng tài liệu USDA cùng văn liệu trước để xây conversion factors từ commodity units sang retail units. Sáu mặt hàng match được đủ rõ là roasted ground coffee, sugar, ground beef, white rice, all-purpose flour, và frozen orange juice concentrate.

Sau đó, tác giả mở rộng sang NielsenIQ scanner data để xem dị biệt giữa các UPC trong cùng category. Ở đây, unit price của sản phẩm được dùng như proxy cho non-commodity costs cộng markup. Nếu logic additive markup đúng, sản phẩm đắt hơn sẽ có log pass-through thấp hơn, nhưng level pass-through vẫn nên giống nhau.

Paper còn dùng exchange-rate shocks và weather shocks như nguồn variation bổ sung cho coffee commodity prices trong appendix, giúp tăng độ tin cậy rằng quan hệ không đơn thuần do đồng biến cầu.

## Manufacturing industries

Ở cấp industry, bài dùng panel manufacturing industries và xây input price index như weighted average của các thành phần chi phí đầu vào. Đây là bước quan trọng vì nó cho thấy stylized fact không chỉ đúng ở retail markets có commodity input rõ nét, mà còn hiện lên ở cấp ngành sản xuất rộng hơn.

Specification tương tác giữa input price inflation và cost share được thiết kế để phân biệt giữa log pass-through và level pass-through. Nếu level pass-through gần 1, thì coefficient tương tác với input-cost share phải tái tạo được logic đó.

## Lớp lý thuyết và quantitative application

Sau phần reduced-form, bài chứng minh rằng homothetic demand systems quen thuộc là scale-invariant, vì vậy dưới conduct assumptions chuẩn chúng ngụ ý complete log pass-through của common shocks chứ không sinh ra complete pass-through in levels. Để giải thích dữ liệu, tác giả đưa ra lớp **shift-invariant demand systems**. Đây là contribution lý thuyết quan trọng: bài không chỉ nói mô hình cũ sai, mà còn chỉ ra một hướng mô hình hóa thay thế.

Cuối cùng, bài nhúng pricing rule này vào một calibrated input-output model của kinh tế Mỹ, với BEA input-output tables, PPI price indices, wage data, và industry-specific Calvo adjustment frequencies.

## Điểm mạnh và điểm dễ bị nghi ngờ

### Điểm mạnh

- Match đơn vị giữa input cost và output price cực kỳ cẩn thận.
- Pattern lặp lại ở nhiều market và nhiều cấp dữ liệu.
- Reduced-form, cross-sectional tests, industry margins, entry, và quantitative model đều nói cùng một câu chuyện.
- Bài không chỉ bác bỏ benchmark cũ mà còn đưa ra lớp demand systems mới để thay thế.

### Điểm dễ bị nghi ngờ

- Pass-through in levels có thể đúng cho **common shocks** nhưng chưa chắc đúng cho idiosyncratic shocks.
- Mapping commodity input into retail unit luôn cần giả định kỹ thuật; nếu conversion factors sai đáng kể thì estimates có thể lệch.
- Một số cơ chế thay thế khác ngoài additive markups vẫn có thể rationalize data, ví dụ search costs, value-added markups, kinked demand, hay managerial heuristics.
- Manufacturing evidence ở cấp ngành rộng hơn nên sạch về external validity nhưng kém “structural purity” hơn retail gasoline.

## Results and interpretation

## 1. Gasoline: level pass-through gần như đúng bằng 1

Đây là phát hiện punchline đầu tiên. Ở Perth, long-run pass-through của wholesale unleaded price sang retail price ở horizon 8 tuần là khoảng **0.991** với standard error **0.038**; với premium unleaded là **0.985** với standard error **0.036**. Trong khi đó, log pass-through chỉ khoảng **0.899** và **0.887**. Nói cách khác, nếu đo bằng phần trăm ta thấy incomplete pass-through; nếu đo bằng cents-per-gallon thì gần như one-for-one.

Diễn giải kinh tế ở đây rất mạnh: doanh nghiệp không nhất thiết giữ markup như một tỉ lệ cố định trên cost. Họ có vẻ giữ một khoảng chênh tuyệt đối ổn định hơn. Điều này khiến cùng một tăng chi phí tuyệt đối được truyền gần trọn vẹn sang giá, nhưng vì giá ban đầu lớn hơn chi phí nên phần trăm thay đổi của giá thấp hơn phần trăm thay đổi của cost.

## 2. Food products: 5 trên 6 mặt hàng cho cùng pattern

Tác giả cho thấy với năm trong sáu staple food products, pass-through in levels không phân biệt thống kê với 1. Đây là kết quả rất quan trọng vì food products đa dạng hơn gasoline nhiều, nhưng vẫn cho cùng một regularity.

Hay hơn nữa, cross-section của sản phẩm trong cùng category cho đúng prediction của additive-markup logic. Ví dụ với rice trong đợt commodity price run-up năm 2008, sản phẩm rẻ có inflation rate cao hơn nhiều so với sản phẩm đắt, nhưng absolute price increase giữa các nhóm lại khá giống nhau. Đây là một minh họa rất đẹp cho việc vì sao level pass-through và log pass-through có thể kể hai câu chuyện khác nhau.

## 3. Manufacturing: incomplete log pass-through nhưng level pass-through vẫn gần 1

Trong panel manufacturing industries, khi input cost chỉ gồm materials, một tăng 1 phần trăm của input price index đi cùng tăng khoảng **0.69 phần trăm** ở output prices. Nếu chỉ nhìn con số này, nhiều người sẽ kết luận pass-through là incomplete. Nhưng specification phân rã cho thấy `rho_level` xấp xỉ 1, trong khi các tham số còn lại phù hợp với logic additive markup. Khi mở input costs sang materials cộng energy, rồi thêm cả production labor, kết quả định tính vẫn giữ nguyên.

Ý nghĩa là stylized fact không chỉ là đặc sản của gasoline hay coffee. Nó có vẻ là một quy luật rộng hơn của pricing under common cost shocks.

## 4. Profits, margins, và entry không ủng hộ multiplicative markups

Nếu firms giữ fixed percentage markup, rising input costs phải làm tăng per-unit profits; với demand khá inelastic, phần tăng này phải hiện ra ở operating margins hoặc entry. Nhưng bài không thấy điều đó. Thay vào đó, rising input prices làm gross margins giảm, còn operating margins và entry gần như không tăng có ý nghĩa. Đây là một “overidentifying pattern” rất thuyết phục vì nó dùng một lát cắt dữ liệu khác để kiểm tra cùng hypothesis.

## 5. Inflation inequality là hệ quả phân phối nổi bật nhất

Vì additive markup ngụ ý low-price products có mức lạm phát phần trăm cao hơn khi commodity costs tăng, households thu nhập thấp, vốn mua các hàng rẻ hơn trong cùng category, sẽ chịu inflation cao hơn. Trong food-at-home giai đoạn 2020-2023, paper ước lượng rằng nếu không có cơ chế pass-through kiểu này, khoảng cách lạm phát giữa nhóm thu nhập thấp và cao chỉ còn khoảng một phần ba quy mô thực tế. Đây là điểm paper đặc biệt đáng nhớ: một regularity tưởng như thuần IO lại dẫn tới một kết luận phân phối rất sắc.

## What is special or elegant about the paper

### 1. Cái đẹp nằm ở việc đổi benchmark

Nhiều paper tốt không thắng bằng dữ liệu mới hoàn toàn, mà bằng việc chỉ ra rằng cả văn liệu đang đo sai biến quan trọng. Paper này thuộc loại đó. Nó khiến người đọc phải hỏi lại: “ta có đang gọi một hiện tượng là incomplete chỉ vì ta đang nhìn qua log changes không?”

### 2. Cùng một ý tưởng giải thích nhiều facts khác nhau

Một idea mạnh là idea có sức nén cao. Ở đây, complete pass-through in levels cùng lúc giải thích:

- incomplete log pass-through,
- heterogeneity của log pass-through theo markup,
- động học gross margins,
- sự ổn định tương đối của operating profits và entry,
- inflation inequality trong cùng category.

Đây là dấu hiệu của một paper rất “gọn về mặt tư duy”.

### 3. Đi từ reduced-form đến model discipline

Paper không dừng ở chỗ “data nói vậy”. Nó còn dùng data để discipline class of demand systems nào là hợp lý. Điều này đặc biệt hay cho người làm research: empirics mạnh nhất thường không phải empirics đứng riêng, mà là empirics buộc lý thuyết phải co lại.

## Required background knowledge

## 1. Pass-through

Pass-through là mức độ doanh nghiệp chuyển cú sốc chi phí đầu vào sang giá bán. Nếu chi phí tăng 1 và giá tăng 1, ta gọi là complete pass-through in levels. Nếu chi phí tăng 10 phần trăm và giá tăng 7 phần trăm, log pass-through là 0.7.

## 2. Additive markup vs multiplicative markup

- **Multiplicative markup:** `p = μ x mc`, với `μ > 1`. Giá luôn là một tỉ lệ cố định trên marginal cost.
- **Additive markup:** `p = mc + m`. Giá bằng marginal cost cộng một khoảng chênh tuyệt đối.

Khác biệt này nhỏ về hình thức nhưng cực lớn về hệ quả. Với multiplicative markup, level pass-through thường lớn hơn 1 khi markup dương. Với additive markup, level pass-through tự nhiên gần 1.

## 3. Scale invariance và shift invariance

Đây là phần lý thuyết cốt lõi của paper.

- **Scale-invariant demand:** nếu mọi giá trong một market cùng tăng theo một tỉ lệ, cầu thay đổi theo một cách có thể chuẩn hóa bằng scale. Homothetic demand systems quen thuộc thuộc nhóm này.
- **Shift-invariant demand:** nếu mọi giá cùng tăng một mức tuyệt đối, cấu trúc cầu giữ một tính bất biến thích hợp. Loại demand này phù hợp hơn với complete pass-through in levels.

Người đọc không cần thuộc lòng định nghĩa hình thức, nhưng cần hiểu intuition: dạng cầu quyết định liệu markup tối ưu được giữ theo phần trăm hay theo mức tuyệt đối.

## 4. Super-elasticity of demand

Super-elasticity đo độ nhạy của demand elasticity khi giá thay đổi. Văn liệu pass-through kiểu Bulow-Pfleiderer hay Weyl-Fabinger cho thấy pass-through của idiosyncratic cost shocks liên quan chặt tới curvature này. Paper nhấn mạnh rằng common cost shocks lại phụ thuộc vào một statistic khác rộng hơn, nên không thể bê nguyên intuition của idiosyncratic shocks sang.

## 5. Distributed-lag regressions và persistent regressors

Vì commodity prices rất persistent, nếu chạy regression ngây thơ ở levels hay long differences, ta dễ bị inference méo. Distributed-lag on first differences là cách chuẩn để đo long-run pass-through trong bối cảnh này.

## 6. Inflation inequality within category

Khái niệm này khác với bất bình đẳng lạm phát do khác basket shares across categories. Paper nhấn mạnh rằng ngay cả trong cùng category, households nghèo và giàu vẫn có thể đối mặt mức lạm phát khác nhau vì họ mua các điểm khác nhau trên quality-price ladder.

## Limitations and open questions

### 1. Common shocks khác idiosyncratic shocks

Bài rất thuyết phục cho aggregate commodity cost shocks hay common shocks trong market. Nhưng câu hỏi lớn còn lại là liệu cùng logic có đúng khi shock chỉ đánh vào một subset firms hay không. Chính tác giả cũng nhấn mạnh đây là một open question.

### 2. Cơ chế sâu đằng sau additive-markup behavior chưa được đóng hoàn toàn

Paper bác bỏ nhiều benchmark quen thuộc và đưa ra shift-invariant demand như một lớp mô hình hợp lý. Nhưng nó chưa chốt một cơ chế kinh tế duy nhất là “đúng”. Search costs, value-added pricing, kinked demand, hay pricing heuristics vẫn còn là các ứng viên.

### 3. Mapping units trong food data vẫn cần giả định

Đây là phần bài làm rất tốt nhưng vẫn không thể hoàn toàn thoát giả định. Với các thị trường processed goods phức tạp hơn, việc đo đúng mức commodity input cho mỗi retail unit có thể khó hơn nhiều.

### 4. External validity cho các thị trường dịch vụ hoặc digital goods

Stylized fact này nhiều khả năng mạnh nhất ở bối cảnh có input commodity rõ, cost shocks chung, và production technology đủ đơn giản. Liệu nó có mở rộng sang services, healthcare, education, hay software không vẫn là câu hỏi mở.

## Takeaways for a researcher

1. Đừng xem thước đo là chuyện phụ. Nhiều khi kết luận thực nghiệm đổi hẳn chỉ vì ta đo bằng log thay vì level.
2. Một paper mạnh thường match institutional detail rất kỹ. Ở đây, việc đổi commodity units sang retail units là phần lao động thủ công nhưng quyết định sức nặng của kết quả.
3. Hãy tìm “auxiliary implications” cho giả thuyết chính. Sangani không chỉ đo pass-through mà còn nhìn profits, margins, và entry để kiểm tra consistency.
4. Nếu muốn challenge một benchmark lớn trong lý thuyết, tốt nhất là đưa ra một benchmark mới chứ không chỉ nói benchmark cũ sai.
5. Cross-sectional heterogeneity thường giúp phân biệt giữa các cơ chế tốt hơn là chỉ nhìn average treatment effect.
6. Một kết quả IO tốt có thể có payoff lớn ở macro và public economics nếu ta nghĩ tiếp đến phân phối và price indices.

## Vietnam relevance and extension

## Vì sao paper này liên quan tới Việt Nam

Việt Nam là một nền kinh tế thường xuyên chịu cú sốc giá hàng hóa đầu vào: xăng dầu, thức ăn chăn nuôi, gạo, cà phê, thép, phân bón. Trong thảo luận chính sách, ta hay hỏi “doanh nghiệp có pass-through hay không” và “lạm phát đánh vào người nghèo nhiều hơn hay không”. Paper này cho một khung rất hữu ích để đặt lại hai câu hỏi đó.

## Có thể triển khai ở Việt Nam không

Có, nhưng cần data và setting phù hợp.

### Dữ liệu cần có

- Dữ liệu giá bán lẻ theo barcode hoặc SKU từ chuỗi siêu thị, cửa hàng tiện lợi, hoặc nền tảng bán lẻ lớn.
- Dữ liệu giá đầu vào upstream đủ chi tiết: xăng dầu, gạo nguyên liệu, cà phê nhân, lúa mì nhập khẩu, thức ăn chăn nuôi, phân bón.
- Conversion factors giữa input units và retail units.
- Nếu muốn làm inflation inequality: dữ liệu household purchases đủ chi tiết trong cùng category, hoặc ít nhất scanner data ghép với survey tiêu dùng.

### Setting đặc biệt hứa hẹn

- Xăng dầu bán lẻ với những đợt điều chỉnh giá cơ sở.
- Cà phê rang xay và đồ uống cà phê đóng gói.
- Gạo bán lẻ theo phân khúc chất lượng trong bối cảnh biến động giá gạo thế giới.
- Thực phẩm chế biến có đầu vào nhập khẩu lớn khi tỷ giá hoặc giá hàng hóa thế giới tăng mạnh.

## Trở ngại chính ở Việt Nam

- Dữ liệu vi mô về giá và quantity thường khó tiếp cận.
- Chất lượng hàng hóa và thay đổi quy cách đóng gói có thể làm unit matching khó hơn Mỹ.
- Nhiều thị trường chịu đồng thời regulation, administered prices, và khuyến mại phức tạp nên pass-through đo được có thể là hỗn hợp của nhiều cơ chế.
- Household-level within-category consumption data đủ giàu để đo inflation inequality thường hiếm.

## Một vài hướng mở rộng cho bối cảnh Việt Nam

### 1. Pass-through của cú sốc giá gạo và bất bình đẳng lạm phát lương thực

Liệu hộ nghèo chịu lạm phát gạo cao hơn hộ giàu không chỉ vì tỷ trọng chi tiêu lớn hơn, mà còn vì họ mua đúng các dòng gạo có log inflation cao hơn trong cùng category?

### 2. Xăng dầu và pass-through tới vận tải hoặc thực phẩm tươi sống

Có thể hỏi liệu các doanh nghiệp downstream ở Việt Nam giữ markup theo phần trăm hay theo mức tuyệt đối khi giá nhiên liệu tăng mạnh.

### 3. Imported-input shocks và quality ladder

Với thực phẩm chế biến, sữa, hoặc hàng tiêu dùng nhanh, liệu hàng phân khúc thấp chịu inflation phần trăm cao hơn hàng phân khúc cao khi giá đầu vào nhập khẩu tăng?

## Kết luận ngắn cho người đọc nghiên cứu

Đây là một paper rất đáng học vì nó làm đúng thứ applied micro ở trình độ cao nên làm: bắt đầu từ một câu hỏi đo lường tưởng như hẹp, nhưng đẩy nó thành một challenge thực sự cho benchmark lý thuyết, rồi kéo tiếp sang hệ quả vĩ mô và phân phối. Điểm đáng học nhất không chỉ là kết quả “pass-through in levels gần 1”, mà là cách tác giả khiến kết quả đó trở thành trung tâm của cả một research agenda về pricing, markup, và inflation inequality.
