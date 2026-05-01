# Identification of Time-Inconsistent Models: The Case of Insecticide-Treated Nets

- **Tác giả:** Aprajit Mahajan, Christian Michel, Alessandro Tarozzi
- **Journal:** The Review of Economic Studies
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-02 (+07)
- **Nguồn bài báo chính:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdag018/8504516
- **Nguồn PDF dùng để phân tích:** bản manuscript công khai trên ReStud tại https://www.restud.com/wp-content/uploads/2026/02/restud.pdf; đối chiếu thêm với NBER Working Paper 27198, bản revised May 2023 tại https://www.nber.org/system/files/working_papers/w27198/revisions/w27198.rev1.pdf
- **Trạng thái lưu trên GitHub:** dự kiến lưu `analysis.md` và `analysis.html`; `analysis.pdf` chưa tạo trong lượt này; PDF gốc của paper mới dừng ở mức xác minh nguồn công khai cho tới khi có bước upload file nhị phân thành công
- **Trạng thái lưu trên Google Drive:** bỏ qua trong lượt chạy này vì bộ công cụ hiện có không hỗ trợ chắc chắn việc tạo đúng Google Doc và tracker trong đúng folder đích

## 1. Metadata

- **Tiêu đề paper:** Identification of Time-Inconsistent Models: The Case of Insecticide-Treated Nets
- **Tác giả:** Aprajit Mahajan, Christian Michel, Alessandro Tarozzi
- **Journal:** The Review of Economic Studies
- **Năm:** 2026
- **Link bài báo:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdag018/8504516
- **Link PDF đã xác minh:** https://www.restud.com/wp-content/uploads/2026/02/restud.pdf
- **Ghi chú về PDF:** đã xác minh được nguồn PDF công khai rất tốt để đọc sâu, nhưng trong giai đoạn đầu của lượt chạy này chưa mặc định coi là đã lưu file PDF gốc lên GitHub; điều đó chỉ được xem là hoàn tất nếu bước upload file nhị phân thực sự thành công.

## 2. Executive summary

Paper hỏi một câu vừa behavioral vừa development rất hay: liệu việc hộ nghèo không mua hoặc không bảo dưỡng insecticide-treated nets (ITNs) có phản ánh present bias và time inconsistency hay không, và nếu có thì ta nhận dạng được loại tác nhân nào, ở mức độ nào?

Bài trả lời bằng hai bước. Bước một là xây dựng một dynamic discrete choice model với nhiều loại tác nhân không quan sát được, cho phép vừa có người time-consistent, vừa có người time-inconsistent, lại còn phân biệt giữa sophisticated và naive. Bước hai là đem mô hình đó xuống dữ liệu thực địa về mua và tái xử lý màn chống muỗi ở Odisha, Ấn Độ, nơi tác giả có dữ liệu panel ba kỳ, dữ liệu beliefs, và proxy về time preferences.

Kết quả chính rất mạnh. Bài cho thấy khoảng hai phần ba mẫu là time-inconsistent; xấp xỉ một phần ba là time-consistent, khoảng một nửa là naive inconsistent, và khoảng một phần sáu là sophisticated inconsistent. Cả naive lẫn sophisticated đều present-biased khá mạnh. Counterfactuals cho thấy under-investment do present bias gây ra chi phí kỳ vọng về malaria rất lớn, cỡ khoảng bốn lần giá một chiếc ITN trong bản ReStud.

Đây là paper đáng đọc vì nó kết hợp được ba thứ hiếm khi đi cùng nhau: một bài toán nhận dạng rất khó trong structural econometrics, một ứng dụng development economics thật sự có ý nghĩa sức khỏe cộng đồng, và một kết quả behavioral không rơi vào kiểu kể chuyện mơ hồ mà đi tới đo lường cụ thể phân bố type và welfare cost.

## 3. Research question and motivation

### Câu hỏi trung tâm

Paper muốn biết:

1. Có thể nhận dạng được time-preference parameters trong dynamic choice model có time inconsistency và unobserved heterogeneity hay không?
2. Nếu có, trong bối cảnh đầu tư phòng ngừa sức khỏe ở vùng nghèo, tỷ trọng các loại tác nhân time-consistent, naive inconsistent, và sophisticated inconsistent là bao nhiêu?
3. Present bias làm thay đổi quyết định mua ITN, mua gói cam kết re-treatment, và hành vi re-treatment về sau đến mức nào?

### Bối cảnh học thuật và thực tiễn

Trong văn liệu behavioral, present bias thường được dùng để giải thích vì sao người nghèo đầu tư quá ít vào những hoạt động có lợi dài hạn như tiết kiệm, phòng bệnh, hay giáo dục. Nhưng nói như vậy thì dễ; chứng minh được bằng dữ liệu hành vi động thì khó hơn nhiều. Vấn đề lớn là ngay cả discount factor chuẩn trong dynamic discrete choice còn thường không được nhận dạng, nên với mô hình beta-delta có time inconsistency thì bài toán còn khó hơn.

Về mặt thực tiễn, ITNs là một công nghệ phòng malaria rất rẻ so với lợi ích kỳ vọng, nhưng nhiều hộ vẫn không mua hoặc không duy trì re-treatment dù tin rằng màn có hiệu quả. Điều này tạo ra một setting rất phù hợp để kiểm tra xem present bias có thật sự là một cơ chế quan trọng hay không.

### Khoảng trống bài muốn lấp

Khoảng trống chính có hai lớp:

1. Văn liệu structural về time inconsistency thiếu các kết quả nhận dạng đủ mạnh khi agent type là không quan sát được và preferences dị biệt.
2. Văn liệu development/health có nhiều bằng chứng reduced-form về under-adoption của preventive technology, nhưng ít bài đo lường trực tiếp phân bố loại time preferences và lượng hóa welfare cost của present bias trong một bài toán thực địa cụ thể.

## 4. Main contribution

### Đóng góp lý thuyết - nhận dạng

Đây là đóng góp lớn nhất của paper. Tác giả chỉ ra điều kiện để:

- point-identify được type probabilities và preference parameters cho time-consistent và sophisticated agents;
- có sharp set-identification cho naive và partially sophisticated agents trong trường hợp tổng quát;
- và có thể point-identify rộng hơn nếu thêm các giả định bổ sung quen thuộc.

Điểm hay ở đây là paper không né khó khăn nhận dạng bằng cách giả sử chỉ có một type hay giả sử type được quan sát trực tiếp. Thay vào đó, họ cho phép có nhiều unobserved types và vẫn đi tới kết quả đủ sắc.

### Đóng góp về dữ liệu và thiết kế thực nghiệm

Paper tận dụng dữ liệu rất "may đo" cho bài toán nhận dạng:

- panel decisions qua ba kỳ;
- dữ liệu elicited beliefs về evolution của state variables;
- proxy về time preferences;
- lựa chọn giữa standard contract và commitment contract;
- quyết định re-treatment thực tế sau đó.

Những thành phần này không chỉ làm dữ liệu phong phú hơn, mà còn trực tiếp đóng vai trò trong chiến lược nhận dạng.

### Đóng góp applied micro/development

Trong ứng dụng Odisha, bài cho thấy present bias không chỉ là một câu chuyện tâm lý chung chung. Nó có thể giải thích một phần lớn under-investment vào phòng bệnh và tạo ra chi phí malaria đáng kể. Ngoài ra, kết quả rằng commitment product không nhất thiết được sophisticated agents ưa thích hơn là một đóng góp behavioral rất đáng nhớ, vì nó cảnh báo chống lại suy luận ngược quá đơn giản từ lựa chọn commitment sang "ý thức tự kiểm soát".

## 5. Identification or methodology

### Khung mô hình

Paper xây dựng một dynamic discrete choice model với finite action space và finite state space, tối thiểu cần ba periods để time inconsistency kiểu beta-delta có thể bộc lộ trong hành vi. Tác nhân có thể là:

- **time-consistent**
- **time-inconsistent sophisticated**: biết mình sẽ bị present bias ở tương lai
- **time-inconsistent naive**: không nội suy đúng sự present bias của chính mình trong tương lai

Type là không quan sát được hoàn toàn, nhưng có thể có proxy không hoàn hảo.

### Logic nhận dạng

Trở ngại xuất phát từ kết quả kinh điển: discount parameters trong dynamic choice thường không tự nhận dạng được từ behavior quan sát đơn thuần. Bài vượt qua trở ngại này bằng hai exclusion restrictions cốt lõi:

1. Có biến `z` chỉ ảnh hưởng current utility thông qua perceived value của future states.
2. Có biến `r` là proxy tín hiệu về type; conditional on type và observables, `r` không mang thêm thông tin trực tiếp về choice.

Trong ứng dụng:

- `z` được gắn với elicited beliefs về evolution của state variables;
- `r` là các chỉ báo survey về time preferences.

Tác giả còn yêu cầu `r` đủ informative về types theo một điều kiện kiểu monotone likelihood ratio. Điểm quan trọng là paper không cần `r` map một-một sang type. Điều này hợp lý hơn nhiều về mặt thực nghiệm.

### Ứng dụng thực địa

Dữ liệu đến từ 621 households ở 47 villages nơi BISWA cho khách hàng microfinance cơ hội mua ITNs trả chậm. Sau loại trừ những quan sát không phù hợp, mẫu phân tích còn 566 households.

Intervention có hai hợp đồng:

- **Contract b**: mua ITN trên tín dụng, rồi sau 6 và 12 tháng nếu muốn re-treatment thì trả thêm tiền mặt tại thời điểm đó.
- **Contract c**: mua ITN kèm luôn hai lần re-treatment trong cùng gói tín dụng, tức là một dạng commitment contract.

Theo paper, giá tín dụng của contract b là Rs. 173 cho single net và Rs. 223 cho double net; contract c là Rs. 203 và Rs. 259. Re-treatment dưới contract b tốn thêm Rs. 15 hoặc Rs. 18 mỗi lần.

Thiết kế thời gian cũng quan trọng:

- baseline survey: March-April 2007
- information campaign và bán ITNs: September-November 2007
- revisit bán lần hai sau khoảng 1 tháng
- re-treatment lần một: khoảng 6 tháng sau
- re-treatment lần hai: khoảng 12 tháng sau

### Điểm mạnh của phương pháp

1. Paper nối chặt phần theory và phần empirics. Dữ liệu beliefs và proxy type không chỉ là "thêm biến kiểm soát", mà là phần sống còn của nhận dạng.
2. Cho phép multiple unobserved types, nên vừa thực tế hơn, vừa cho ra object rất đáng quan tâm về policy: phân bố type trong dân số.
3. Ứng dụng lên hành vi thực địa giàu tính động, thay vì chỉ dựa vào survey choices hay lab tasks.

### Điểm dễ bị nghi ngờ

1. Hai exclusion restrictions là hợp lý nhưng về bản chất khó kiểm định trực tiếp.
2. Proxy `r` cho time preference có thể lẫn với những thứ khác như perceived returns hay kỳ vọng income, nên dù paper đã xử lý cẩn thận, đây vẫn là nơi người đọc nên đặt dấu hỏi.
3. Mô hình ba kỳ là tối thiểu để nhận dạng, nhưng cũng là một abstraction khá gọn của một quá trình ra quyết định thực tế có thể kéo dài và phức tạp hơn.

## 6. Results and interpretation

### Các sự kiện thực nghiệm quan trọng

Ngay ở dữ liệu mô tả, paper đã cho thấy một pattern rất phù hợp với câu chuyện commitment:

- khoảng gần một nửa mẫu không mua ITNs dù malaria burden cao;
- sau 6 tháng, khoảng **92%** ITNs mua với contract c được re-treated;
- con số tương ứng với contract b chỉ khoảng **36%**;
- sau 12 tháng, re-treatment dưới contract c vẫn cao, còn contract b giảm thêm gần một nửa.

Chênh lệch này cho thấy vấn đề không chỉ nằm ở adoption ban đầu, mà còn ở maintenance sau đó, tức đúng kiểu quyết định liên thời gian mà present bias có thể phá vỡ.

### Kết quả structural cốt lõi

Ước lượng ưa thích nhất của paper cho thấy:

- khoảng **1/3** respondents là **time-consistent**
- khoảng **1/2** là **naive inconsistent**
- khoảng **1/6** là **sophisticated inconsistent**

Paper còn cho thấy present bias rất mạnh ở hai nhóm inconsistent:

- beta của naive agents khoảng **0.06**
- beta của sophisticated agents khoảng **0.16**

Điều này có nghĩa là không chỉ có time inconsistency phổ biến, mà cường độ present bias cũng lớn. Trong khi đó, discount factor của consistent agents được ước lượng gần 1.

### Commitment không đơn giản như textbook intuition

Một kết quả rất hay là **commitment products không đặc biệt hấp dẫn hơn đối với sophisticated agents**. Thậm chí paper cho thấy việc mua commitment contract lại cao hơn ở các hộ naive. Đây là một cú nhắc mạnh rằng:

- không nên suy từ "chọn commitment" sang "agent sophisticated";
- choice data đơn lẻ có thể che lấp heterogeneity về beliefs, income expectations, hay perceived returns.

### Welfare cost và counterfactuals

Paper lượng hóa chi phí malaria phát sinh thêm do present bias gây ra under-investment vào ITNs và re-treatment. Ở median household, **tổng chi phí kỳ vọng không chiết khấu** do present bias gây thêm vào khoảng:

- **Rs. 488** nếu dùng ước lượng protective power của ITNs từ meta-analysis
- **Rs. 812** nếu dùng elicited beliefs của households

Paper cũng diễn giải rằng đây tương đương khoảng **3-5 ngày công bị mất** do malaria. So với giá một chiếc ITN, chi phí này là rất lớn.

Về counterfactual pricing, paper cho thấy:

- tăng giá re-treatment làm giảm rõ re-treatment dưới standard contract;
- gần như không ảnh hưởng tới re-treatment dưới commitment contract;
- và có thể làm households rời khỏi commitment purchase sang không mua gì cả;
- trong khi giảm giá re-treatment lại cải thiện re-treatment và tăng hấp dẫn của phương án commitment.

Ý nghĩa kinh tế ở đây là present bias không chỉ làm méo hành vi hiện tại, mà còn tương tác mạnh với cấu trúc pricing và timing của hợp đồng.

## 7. What is special or elegant about the paper

Có ba điểm khiến paper này rất đáng nhớ.

### Một bài structural nhưng không "bay khỏi mặt đất"

Nhiều bài structural behavioral hoặc rất đẹp về mặt theory nhưng xa dữ liệu, hoặc có dữ liệu hay nhưng identification lỏng. Paper này làm được cả hai: phần nhận dạng chặt, còn phần ứng dụng lại bám vào một vấn đề development rất thực.

### Dùng dữ liệu beliefs theo cách thật sự có nội dung

Trong applied micro, elicited beliefs đôi khi chỉ được thêm vào cho "đủ giàu". Ở đây, beliefs là một phần thật sự của identification strategy. Đó là điểm rất đẹp về thiết kế nghiên cứu.

### Phá vỡ một shortcut suy luận phổ biến

Nhiều người quen nghĩ rằng "ai chọn commitment product thì hẳn là sophisticated". Paper này cho thấy suy luận đó quá đơn giản. Đây là một bài học rất quan trọng cho empirical behavioral IO/labor/development: cùng một observed action có thể đến từ nhiều latent types khác nhau.

## 8. Required background knowledge

Để đọc paper này thoải mái, người đọc nên có nền tảng ở bốn cụm kiến thức sau.

### Time inconsistency và present bias

Mô hình beta-delta nói rằng agent discount tương lai theo hai thành phần:

- `delta`: mức patience tiêu chuẩn giữa các kỳ tương lai
- `beta`: mức bias chống lại việc trì hoãn chi phí hoặc ưa trì hoãn đầu tư khi quyết định hôm nay

Nếu `beta < 1`, agent present-biased. Nếu agent biết điều đó về "bản thân tương lai", agent là sophisticated; nếu không, agent là naive.

### Dynamic discrete choice

Đây là lớp mô hình trong đó tác nhân chọn giữa một số hành động rời rạc qua thời gian, và payoff hiện tại lẫn state tương lai đều phụ thuộc vào hành động hiện tại. Vấn đề chính là behavior hôm nay phản ánh cả utility hiện tại lẫn continuation value.

### Identification với unobserved heterogeneity

Khi type không quan sát được, observed choices là một mixture của nhiều decision rules khác nhau. Muốn tách chúng ra cần thêm structure hoặc thêm nguồn biến thiên có nội dung. Bài này dùng exclusion restrictions và type proxies để làm việc đó.

### Bối cảnh health economics/development

ITNs là công nghệ phòng malaria đã được chứng minh hiệu quả. Nhưng hiệu quả thực tế phụ thuộc không chỉ vào mua ban đầu mà còn vào sử dụng và bảo dưỡng về sau. Vì thế bài toán ở đây là một bài toán adoption-and-maintenance chứ không chỉ take-up một lần.

## 9. Limitations and open questions

### Hạn chế chính

1. **Exclusion restrictions khó kiểm định trực tiếp.** Đây là đánh đổi quen thuộc của structural work: muốn nhận dạng sâu thì phải chấp nhận một số giả định mạnh hơn reduced-form work.
2. **External validity có giới hạn.** Setting là Odisha, ITNs, microfinance client households, và một loại quyết định preventive health cụ thể.
3. **Proxy contamination.** Các câu trả lời survey dùng làm proxy cho time preference có thể còn phản ánh literacy, expectations, hoặc perceived returns.
4. **Mô hình rút gọn thời gian thành ba kỳ.** Điều này cần cho nhận dạng, nhưng có thể bỏ sót một số dynamic margin tinh hơn của hành vi thực tế.

### Câu hỏi mở

1. Phân bố types này có ổn định qua sản phẩm và domain khác không, hay chỉ đặc trưng cho preventive health?
2. Nếu cho households tiếp cận nudges, reminders, hay small liquidity support thì present bias sẽ biểu hiện khác thế nào?
3. Có thể kết hợp data kiểu paper này với administrative health records hoặc passive usage data để giảm phụ thuộc vào self-reports không?

## 10. Takeaways for a researcher

1. Nếu muốn nghiên cứu present bias bằng dữ liệu thực địa, chỉ có observed choices thường là chưa đủ; cần dữ liệu beliefs, type proxies, hoặc institutional variation có nội dung nhận dạng.
2. Một commitment product không tự động "đo" sophistication. Cần rất cẩn thận khi suy latent type từ một hành vi duy nhất.
3. Khi nghiên cứu low adoption của preventive technologies, nên tách riêng decision ban đầu và decision maintenance sau đó.
4. Một applied paper mạnh thường thành công vì dữ liệu được thiết kế từ đầu cho câu hỏi nhận dạng, chứ không chỉ vì econometrics tinh vi.
5. Đừng xem heterogeneity là nuisance parameter. Trong paper này, chính distribution of types là một kết quả policy-relevant.
6. Structural work thuyết phục nhất khi gắn được estimated parameters với welfare-relevant counterfactuals, như chi phí malaria hay ngày công bị mất ở đây.

## 11. Vietnam relevance and extension

### Liên hệ với Việt Nam

Việt Nam hiện không còn là bối cảnh malaria đại trà như nhiều vùng ở Ấn Độ hay châu Phi, nhưng ý tưởng của paper vẫn rất hợp với applied micro ở Việt Nam nếu dịch sang những quyết định đầu tư phòng ngừa có chi phí nhỏ hôm nay và lợi ích lớn về sau.

Các ví dụ gần hơn với Việt Nam:

- tái mua hoặc bảo trì màn/tấm lọc ở vùng sốt rét cục bộ hoặc vùng rừng núi
- tiêm nhắc lại, khám định kỳ, hay preventive maternal-child health
- gia hạn bảo hiểm y tế hộ gia đình hoặc bảo hiểm vi mô
- đầu tư vào water filters, nhà tiêu hợp vệ sinh, hay xử lý nước
- tuân thủ các khoản chi nhỏ nhưng lặp lại để duy trì hiệu quả của một chương trình công

### Điều kiện cần nếu làm ở Việt Nam

1. Cần panel data theo thời gian về decision ban đầu và maintenance.
2. Cần một thiết kế có variation về contract timing, giá, hoặc bundling để nhìn thấy behavioral margin.
3. Nếu muốn đi theo tinh thần paper này, cần thu thêm elicited beliefs và proxy về time preferences thay vì chỉ đo outcomes.
4. Cần đối tác triển khai đủ mạnh, như trung tâm y tế, tổ chức vi mô, doanh nghiệp phân phối công nghệ sức khỏe, hoặc chính quyền địa phương.

### Trở ngại chính

1. Dữ liệu beliefs chất lượng cao rất khó thu nếu survey design không tốt.
2. Attrition và measurement error sẽ đặc biệt nguy hiểm trong bài toán dynamic choice.
3. Một số sản phẩm ở Việt Nam có external validity khác hẳn ITNs; present bias có thể trộn với trust, misinformation, hoặc liquidity constraints mạnh hơn.

### Hướng mở rộng cho bối cảnh Việt Nam

1. **Preventive health maintenance:** Liệu households có present bias trong việc duy trì các khoản đầu tư sức khỏe nhỏ nhưng định kỳ, như nước sạch, thuốc phòng, hay khám định kỳ?
2. **Insurance renewal and commitment design:** Việc bundle chi phí gia hạn hoặc thiết kế auto-renew có làm tăng duy trì bảo hiểm ở nhóm lao động phi chính thức không?
3. **Education and child investment:** Trong các khoản đầu tư nhỏ nhưng lặp lại cho trẻ em, như lớp phụ đạo, vitamin, hay di chuyển đến trường, present bias của phụ huynh biểu hiện ra sao?

## 12. Đánh giá cuối cùng

Đây là một paper rất mạnh và khá hiếm theo nghĩa "đúng top 5 applied/development nhưng còn dạy được cách làm research". Nếu đọc để học một ý tưởng, đó là: behavioral frictions chỉ thật sự thuyết phục khi ta gắn chúng với một bài toán nhận dạng rõ ràng và một môi trường dữ liệu được thiết kế có chủ đích.

Nếu đọc để học một bài học lớn hơn, đó là: trong các quyết định phòng ngừa của hộ nghèo, vấn đề không chỉ là "có tiền hay không", mà còn là cấu trúc thời gian của chi phí, sự hiện diện của maintenance margin, và cách heterogeneity ẩn trong dân số làm cho observed choices trở nên dễ bị hiểu sai.
