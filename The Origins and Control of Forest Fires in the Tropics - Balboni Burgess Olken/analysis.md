# The Origins and Control of Forest Fires in the Tropics

- **Tác giả:** Clare Balboni, Robin Burgess, Benjamin A. Olken
- **Journal:** The Review of Economic Studies
- **Năm:** 2025
- **Ngày agent chạy:** 2026-04-29
- **Nguồn bài báo chính:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdaf088/8275590
- **Nguồn PDF tốt nhất đã xác minh:** bản working paper trên trang MIT Economics, ngày 5 May 2023: https://economics.mit.edu/sites/default/files/2023-05/Forest_Fires_Paper_0.pdf
- **Trạng thái lưu trên GitHub:** `analysis.md` và `analysis.html` đã lưu thành công trong repo `huylvu/00_reading` tại thư mục `The Origins and Control of Forest Fires in the Tropics - Balboni Burgess Olken/`
- **Trạng thái lưu trên Google Drive:** bỏ qua trong lượt chạy này vì chưa có tuyến tạo Google Doc và tracker đúng folder đích một cách nhất quán

## Executive summary

Bài nghiên cứu hỏi một câu rất nền tảng trong environmental economics: khi một công nghệ rẻ nhưng gây ngoại tác lớn, các firm có thực sự internalize phần thiệt hại mà họ gây ra cho người khác hay không, và nhà nước có thể kìm hãm hành vi đó tới đâu. Bối cảnh cụ thể là việc dùng lửa để dọn đất trong rừng nhiệt đới Indonesia, một công nghệ rẻ nhưng có rủi ro cháy lan rất lớn.

Để trả lời, tác giả xây dựng một dataset cực kỳ ấn tượng từ 15 năm dữ liệu vệ tinh hằng ngày, truy vết hơn 107.000 vụ cháy, xác định vị trí khởi phát và phần diện tích cháy lan, rồi ghép với dữ liệu ranh giới concession, phân loại đất, rừng bảo tồn, đất ngoài forest estate và mật độ dân số. Điểm nhận dạng trung tâm là kết hợp variation theo thời tiết làm thay đổi rủi ro cháy lan với variation theo loại đất xung quanh, từ đó tách xem firm phản ứng với private risk và external risk khác nhau thế nào.

Kết quả chính rất sắc nét. Firms đặc biệt “coi nhẹ” nguy cơ cháy lan khi vùng có thể bị ảnh hưởng là đất productive forest chưa được lease của nhà nước, tức nơi property rights yếu nhất. Ngược lại, họ tránh dùng lửa rõ rệt khi nguy cơ cháy lan sang khu dân cư ngoài forest estate. Nếu firms đối xử với mọi vùng đất xung quanh giống như cách họ đối xử với đất ngoài forest estate, số vụ khởi cháy sẽ giảm khoảng 55-58%. Bài còn cho thấy giữa các private concession lân cận, hành vi lại gần với logic Coase: firms đối xử rủi ro cháy lan sang concession tư nhân bên cạnh gần giống như rủi ro lên chính đất của mình. Đây là một paper rất đáng đọc vì nó đưa externalities, Coase và Pigou từ textbook xuống một setting thực địa cực lớn, với design thực nghiệm vừa trực quan vừa thuyết phục.

## Research question and motivation

### Câu hỏi nghiên cứu trung tâm

Paper hỏi ba điều liên kết chặt với nhau:

1. Liệu các firm sử dụng fire-clearing có internalize phần thiệt hại do cháy lan gây ra cho người khác không.
2. Mức độ internalization này có thay đổi theo loại đất và cấu trúc property rights xung quanh không.
3. Các cơ chế kiểm soát externality nào có vẻ hiệu quả hơn trong thực tế: thỏa thuận kiểu Coase giữa các private parties hay sanctions kiểu Pigou từ nhà nước.

### Bối cảnh học thuật và thực tiễn

Environmental economics từ lâu xoay quanh câu hỏi tại sao private decision không phản ánh social cost. Nhưng phần lớn bằng chứng thực nghiệm thường đo hậu quả của externality hoặc hiệu quả của policy, chứ ít đi thẳng vào quyết định vi mô của tác nhân khi external cost thay đổi. Ở đây, Indonesia là một setting gần như lý tưởng: fire-clearing là hành vi phổ biến, rẻ hơn cơ giới hóa, bị cấm nhưng vẫn diễn ra; ranh giới quyền sở hữu trong forest estate lại rất chắp vá; và chi phí xã hội từ cháy rừng là khổng lồ, từ phát thải, mất rừng, thiệt hại sức khỏe tới haze xuyên biên giới.

### Khoảng trống mà bài muốn lấp vào

Khoảng trống lớn mà paper xử lý là thiếu bằng chứng trực tiếp về việc mức độ “ngoại tác hóa” thay đổi hành vi private ra sao. Nói cách khác, khi cùng là nguy cơ cháy lan, người đốt có phản ứng khác nếu thiệt hại rơi vào đất của họ, đất của một firm khác, đất nhà nước yếu bảo vệ, hay khu vực có dân cư sinh sống hay không. Đây là một đóng góp vừa về thực chứng vừa về tư duy thiết kế nghiên cứu.

## Main contribution

### Đóng góp 1: biến một externality khó quan sát thành một đối tượng đo lường vi mô

Paper không chỉ đo “có cháy” hay “không có cháy”, mà xây dựng hẳn thuật toán truy vết ignition area và spread area từ dữ liệu MODIS hằng ngày. Nhờ vậy, tác giả không chỉ thấy nơi cháy bắt đầu mà còn thấy phần diện tích thiệt hại bị đẩy sang bên ngoài concession. Đây là nền tảng dữ liệu rất mạnh.

### Đóng góp 2: nối literature về externalities với literature về property rights

Điểm hay nhất là bài không coi externality như một đại lượng đồng nhất. External damage phụ thuộc vào việc lửa có thể cháy sang loại đất nào. Kết quả cho thấy externality lớn nhất xuất hiện khi land rights yếu nhất, đặc biệt ở unleased productive forest do nhà nước sở hữu nhưng bảo vệ lỏng lẻo. Nghĩa là không chỉ “externality” quan trọng, mà cấu trúc quyền sở hữu quyết định externality ấy được internalize đến đâu.

### Đóng góp 3: cho phép so sánh Coase và Pigou trong cùng một setting

Rất ít paper có thể vừa kiểm tra private bargaining kiểu Coase, vừa soi được government deterrence kiểu Pigou trong cùng một hành vi. Ở đây, khi lửa có nguy cơ lan giữa hai private concession, firms cư xử gần như đã internalize đầy đủ. Khi nguy cơ liên quan tới đất công yếu bảo vệ, externality rõ rệt. Còn khi nguy cơ chạm vào khu dân cư hoặc protected forest, pattern avoidance lại phù hợp hơn với sanctions từ nhà nước.

### Vì sao đóng góp này quan trọng cho micro applied/development

Đây là applied micro rất “đẹp” vì nó dùng variation tự nhiên và dữ liệu chi tiết để trả lời một câu hỏi lý thuyết rất cổ điển bằng một setting phát triển rất thật. Đồng thời, nó là development economics theo nghĩa mạnh: thể chế đất đai, enforcement capacity, state weakness, industrial land conversion và environmental governance đều nằm ở trung tâm câu chuyện.

## Identification or methodology

### Dữ liệu và đơn vị quan sát

Paper dùng 15 năm dữ liệu hotspot MODIS hằng ngày từ October 2000 tới January 2016, xây được hơn 107.000 fire events trong forest estate Indonesia. Sau khi tập trung vào hành vi land clearing có chủ đích của firms, mẫu phân tích chính là 39.189 fires bắt đầu trong wood fiber và palm oil concessions trên các đảo rừng lớn. Đơn vị quan sát cho phân tích ignition là pixel 1 km vuông theo month-year.

Các lớp dữ liệu được ghép vào gồm:

- ranh giới concession của logging, palm oil và wood fiber
- phân loại đất trong và ngoài forest estate
- protected forest và productive forest
- dân số xung quanh
- dữ liệu thời tiết: mưa, gió, nhiệt độ
- dữ liệu mất rừng từ vệ tinh
- dữ liệu điều tra doanh nghiệp sau đợt cháy lớn 2015

### Logic nhận dạng trung tâm

Paper dựa trên một intuition rất mạnh: weather làm thay đổi xác suất lửa cháy lan, nhưng mức social cost của cháy lan phụ thuộc vào việc vùng xung quanh thuộc về ai và được bảo vệ ra sao. Nếu firms thật sự internalize external costs, thì vào những ngày “nguy hiểm” hơn, họ sẽ giảm dùng lửa mạnh hơn ở các pixel nơi phần thiệt hại do spread có khả năng rơi lên đất mà họ phải quan tâm.

Nói ngắn gọn, design là:

1. Dùng thời tiết để tạo variation theo thời gian và không gian trong spread risk.
2. Dùng composition của đất trong vòng đệm 6 km quanh từng pixel để đo ai là người gánh thiệt hại nếu lửa lan.
3. Xem xác suất ignition phản ứng thế nào với interaction giữa spread risk và neighboring land type.

### Các specification chính

Paper đi theo ba bước:

1. Mô tả chéo giữa neighboring land type và xác suất ignition.
2. Ước lượng specification với interaction giữa weather-induced spread risk và land composition, kèm month/year fixed effects và nhiều controls cố định của pixel/concession để tăng sức thuyết phục nhận dạng.
3. Mở rộng sang test Coasian bargaining, reputational constraints, certification, và government sanctions.

Một kết quả nền rất quan trọng là weather thực sự dự báo độ lan của cháy. Điều này làm cho interaction design có ý nghĩa kinh tế chứ không chỉ là thủ thuật thống kê.

### Điểm mạnh của phương pháp

- Dữ liệu rất giàu và đúng bài toán: ignition, spread, land type, weather và enforcement cùng xuất hiện trong một hệ thống.
- Externality được đo bằng cấu trúc không gian cụ thể thay vì proxy rất xa.
- Weather variation giúp tăng tính thuyết phục cho câu chuyện nhân quả.
- Bài không dừng ở reduced-form mà còn đối chiếu hai cơ chế policy kinh điển: Coase và Pigou.

### Điểm dễ bị nghi ngờ hoặc cần đọc cẩn thận

- Weather-induced spread risk phải thực sự exogenous với các yếu tố khác ảnh hưởng đến fire-setting; paper xử lý khá tốt nhưng đây vẫn là giả định nền.
- Phân loại ignition và tracing spread từ MODIS không thể hoàn hảo 100%, nhất là với các đám cháy phức tạp.
- Neighboring land composition có thể correlated với những yếu tố không quan sát được về profitability, monitoring, terrain hoặc market access; interaction với weather giúp giảm lo ngại này nhưng không xóa sạch hoàn toàn.
- Bằng chứng “Coase” là suggestive hơn là quan sát trực tiếp bargaining. Paper suy ra từ pattern hành vi chứ không thấy hợp đồng hay side payments.

## Results and interpretation

### 1. Nhiều vụ cháy là do con người chủ động dùng để dọn đất

Đây không phải một paper về “natural wildfire” theo nghĩa thông thường. Tác giả cho thấy fires tập trung mạnh ở palm oil và wood fiber concessions, nơi cần clear-cut rồi trồng lại, và xác suất cháy cao hơn rất nhiều so với logging concessions. Thêm nữa, tăng tỷ lệ pixel bị deforest từ 0 lên 100% làm xác suất cháy năm sau tăng khoảng 285%. Điều này giúp đóng khung lửa như một input rẻ của quá trình land conversion.

### 2. Externalities lớn nhất xuất hiện ở nơi property rights yếu nhất

Kết quả cốt lõi là firms dùng lửa nhiều hơn khi rủi ro cháy lan rơi vào unleased productive forest của nhà nước. Trực giác ở đây rất mạnh: đó là đất “của nhà nước” trên giấy tờ, nhưng không có chủ thể cụ thể nào đủ mạnh để bảo vệ hoặc thương lượng. Chính vùng đó tạo ra khoảng trống lớn nhất giữa private cost và social cost.

Ngược lại, firms tránh dùng lửa hơn khi nguy cơ lan sang land outside the forest estate, nơi người dân sinh sống. Điều này vừa có thể phản ánh social pressure, vừa phản ánh enforcement mạnh hơn, vừa phản ánh rằng thiệt hại ở đây dễ bị quan sát và trừng phạt hơn.

### 3. Magnitude rất lớn: số vụ cháy có thể giảm 55-58%

Ước lượng phản thực của paper cho thấy nếu firms đối xử với tất cả đất xung quanh giống như cách họ đối xử với đất ngoài forest estate, số ignitions trong wood fiber và palm oil concessions sẽ giảm khoảng 55-58%. Đây là một con số rất lớn. Nó cho thấy phần “không internalize externality” không phải là chi tiết biên, mà là một lực đẩy lớn của toàn bộ hiện tượng.

### 4. Bằng chứng đẹp cho logic Coase giữa các private concession

Khi vùng xung quanh chỉ gồm chính concession của firm và đúng một neighboring private concession, paper không tìm thấy bằng chứng cho externality theo nghĩa thông thường: firms đối xử rủi ro cháy lan sang concession lân cận gần giống như rủi ro lên đất của chính mình. Kết quả này còn giữ được khi tách phần đất đã và chưa bị deforest. Cách đọc hợp lý là giữa private actors có thể tồn tại bargaining, repeated interaction, hoặc một cơ chế tương tự làm cho externality được internalize tốt hơn.

Đây là chỗ rất hay: Coase ở đây không cần phải được quan sát trực tiếp dưới dạng contract. Chỉ cần pattern hành vi cho thấy border giữa “my land” và “your concession” gần như biến mất trong quyết định đốt, paper đã tạo ra bằng chứng rất thuyết phục.

### 5. Reputational constraints và certification có vẻ yếu hơn nhiều

Paper kiểm tra liệu firms lớn hơn, firms có nhiều concession hơn, hoặc firms tham gia sustainability certification có cư xử “đẹp” hơn ở chỗ internalize external damage hay không. Kết luận chung là các cơ chế private này không mạnh bằng người ta có thể hy vọng. Chúng có thể gắn với ít đốt hơn trên average, nhưng không xóa được externality ở nơi property rights yếu.

### 6. Sanctions của nhà nước có tác dụng, nhưng theo pattern rất cụ thể

Khai thác danh sách firms bị điều tra sau đợt cháy 2015, paper cho thấy government investigations tập trung mạnh hơn vào fires lan sang khu vực có dân cư và protected forest. Các vụ cháy lan vào unleased productive forest lại không bị đối xử khác đáng kể so với cháy trong chính concession. Pattern này khớp khá tốt với pattern avoidance của firms: họ đặc biệt né những kiểu thiệt hại mà chính quyền có xu hướng chú ý nhất. Điều đó gợi ý một logic Pigouvian deterrence có thật, dù cường độ thực tế có thể còn xa optimum vì enforcement chưa chắc và nhiều án phạt không được thu đủ.

## What is special or elegant about the paper

### Nó biến một lý thuyết textbook thành một object đo được

Externality, Coase và Pigou thường được dạy như khung lý thuyết rất sạch. Paper này khiến chúng trở nên “sờ được” bằng dữ liệu không gian: cùng một hành vi đốt, nhưng social cost thay đổi theo bản đồ đất xung quanh, và decision rule của firm thay đổi theo đúng bản đồ ấy.

### Nó tận dụng spatial structure cực kỳ khéo

Điểm đẹp không chỉ là có dữ liệu vệ tinh, mà là biết hỏi đúng câu hỏi với dữ liệu đó. Tác giả không hỏi “nơi nào cháy nhiều hơn” theo kiểu descriptive đơn giản. Họ hỏi: “khi spread risk tăng lên do thời tiết, decision to ignite thay đổi thế nào tùy ai là người chịu thiệt nếu lửa lan?”. Đó là một framing rất mạnh.

### Nó cho phép so sánh hai cơ chế governance trong cùng một hành vi

Ít paper làm được việc vừa đọc ra dấu vết của private bargaining, vừa đọc ra dấu vết của public enforcement, rồi đặt chúng cạnh nhau. Bài này làm được điều đó mà không cần gượng ép.

### Bài học nghiên cứu rất đáng học

Nếu một câu hỏi lớn nghe có vẻ trừu tượng, nhiều khi chìa khóa là tìm một environment nơi social cost được “mã hóa” vào geography, institutions hoặc transaction structure. Paper này là ví dụ mẫu mực cho cách biến theory thành empirics.

## Required background knowledge

### 1. Externalities và internalization

Người đọc cần nắm rõ externality là chênh lệch giữa private cost và social cost. Ở đây, fire-clearing rẻ cho firm nhưng nếu cháy lan sang đất người khác thì phần thiệt hại đó không được firm tính đủ vào quyết định.

### 2. Coase theorem

Coase nói rằng nếu property rights rõ và transaction costs thấp, các bên có thể bargain để internalize externality. Trong paper này, neighboring private concessions là nơi gần nhất với bối cảnh đó. Kết quả “không thấy externality giữa private concessions” là cách diễn giải theo tinh thần Coase.

### 3. Pigouvian deterrence

Pigou nhấn mạnh việc dùng tax, fine hay sanction để đưa private incentives gần social optimum hơn. Trong paper này, because burning is already illegal, biến gần nhất với Pigouvian policy là expected sanctions: firms né những loại thiệt hại mà họ nghĩ dễ bị nhà nước điều tra và xử hơn.

### 4. Spatial econometrics trực giác

Không cần nắm kỹ mô hình không gian phức tạp, nhưng cần hiểu rằng “neighboring land composition” là một biến kinh tế có ý nghĩa. Một pixel giống hệt nhau về lợi nhuận đốt có thể dẫn tới decision khác nếu quanh nó là đất của mình, đất của firm khác, protected forest hay khu dân cư.

### 5. Reduced-form identification với interaction term

Phần khó nhất về econometrics là hiểu tại sao interaction giữa spread risk và land composition giúp nhận dạng externality. Intuition là: weather shock tạo variation ngắn hạn trong độ nguy hiểm của việc đốt; nếu cùng một pixel mà hành vi đốt phản ứng khác trên ngày risky hơn tùy loại đất xung quanh, đó là dấu vết của việc người đốt đang cân nhắc ai gánh chi phí khi cháy lan.

### 6. Remote sensing và event construction

Paper dựa nhiều vào việc biến hotspot data thành fire events, ignition area và spread area. Người đọc không cần biết hết thuật toán, nhưng nên hiểu rằng đây là bước đo lường trung tâm: nếu không tách được nơi khởi cháy và nơi cháy lan thì không thể nói gì nghiêm túc về externality.

## Limitations and open questions

### Hạn chế 1: không quan sát trực tiếp bargaining

Paper cho bằng chứng rất đẹp “consistent with Coase”, nhưng không quan sát side payments, hợp đồng hay cơ chế thỏa thuận cụ thể giữa firms. Vì vậy, cách diễn giải hợp lý nhất là suggestive evidence of internalization among private neighbors, không nên đọc quá thành “đã chứng minh bargaining xảy ra”.

### Hạn chế 2: enforcement expectations chỉ được suy ra gián tiếp

Tác giả dùng investigations sau năm 2015 để suy ra government punishment function. Đây là một bước rất sáng tạo, nhưng vẫn là indirect inference. Kỳ vọng của firms về enforcement có thể hình thành từ nhiều tín hiệu khác nữa.

### Hạn chế 3: kết quả gắn mạnh với setting Indonesia

Indonesia có cấu trúc forest estate, concession system, decentralization và land governance rất đặc thù. Cơ chế tổng quát của bài có thể đi xa, nhưng magnitude của các coefficient khó có thể mang nguyên sang nước khác.

### Hạn chế 4: weather có thể ảnh hưởng nhiều margin cùng lúc

Weather không chỉ ảnh hưởng spread risk mà có thể còn ảnh hưởng cost/benefit của việc đốt, visibility, detectability, hay timing của land clearing. Paper xử lý khá thuyết phục, nhưng đây luôn là chỗ người đọc applied micro nên rà kỹ.

### Câu hỏi mở

- Điều gì chính xác tạo ra “Coasian” internalization giữa neighboring firms: repeated relationships, ownership links, reputation, informal threat hay legal arrangements?
- Nếu nhà nước cải thiện rights over unleased productive forest, externality sẽ giảm mạnh đến đâu?
- Liệu satellite-based real-time monitoring kết hợp sanctions tự động có thể thay thế phần nào enforcement truyền thống?

## Takeaways for a researcher

1. Một câu hỏi lý thuyết lớn có thể được nhận dạng bằng dữ liệu cực kỳ cụ thể nếu ta tìm đúng environment và đúng margin hành vi.
2. Spatial variation không chỉ để làm bản đồ đẹp; nó có thể là trung tâm của identification strategy.
3. Khi đo externalities, đừng coi “others” là một nhóm đồng nhất. Ai là người chịu thiệt, và quyền của họ mạnh hay yếu, là phần cốt lõi của economics.
4. Một paper mạnh thường không chỉ cho reduced-form result mà còn đặt các cơ chế governance cạnh nhau để người đọc hiểu policy implications sâu hơn.
5. Nếu muốn làm applied micro hay hơn, hãy tìm cách quan sát được decision margin chứ không chỉ outcome cuối cùng.
6. Matching data kỹ lưỡng giữa remote sensing, administrative boundaries, institutional categories và enforcement records có thể mở ra những câu hỏi tưởng như trước đây không đo được.

## Vietnam relevance and extension

### Liên hệ với Việt Nam

Việt Nam không có mô hình concession forest giống Indonesia ở cùng quy mô, nhưng có nhiều bài toán gần về land conversion, cháy rừng, quản lý đất lâm nghiệp, rừng sản xuất, rừng phòng hộ, giao đất giao rừng, và khoảng cách lớn giữa quyền sở hữu trên giấy với enforcement trên thực địa. Vì thế, intuition trung tâm của paper rất hợp với Việt Nam: hành vi gây hại môi trường thường thay đổi mạnh theo việc ai là người chịu thiệt và ai có quyền hay khả năng phản ứng.

### Điều kiện cần nếu muốn làm bài kiểu này ở Việt Nam

- dữ liệu hotspot/fire từ MODIS hoặc VIIRS ở tần suất đủ dày
- shapefile ranh giới rừng, loại rừng, đất lâm nghiệp, đất giao khoán, protected areas
- dữ liệu về chủ quản lý hoặc đơn vị nhận khoán đủ chi tiết để đo neighboring ownership
- dữ liệu dân cư, hạ tầng, hoặc giá trị kinh tế quanh vùng rừng
- dữ liệu xử phạt, kiểm lâm, hoặc hồ sơ điều tra các vụ cháy

### Trở ngại chính

- dữ liệu quyền quản lý đất/rừng ở Việt Nam có thể không sạch và không ổn định theo thời gian
- việc ghép dữ liệu enforcement với spatial fire events có thể khó hơn nhiều so với Indonesia
- nhiều vụ cháy ở Việt Nam có thể do hộ nhỏ lẻ, du canh hoặc sơ suất hơn là firm-scale land conversion, khiến interpretation khác đi

### Hướng mở rộng phù hợp hơn với Việt Nam

1. So sánh hành vi dùng lửa hoặc phá rừng ở nơi ranh giới quản lý chồng lấn giữa ban quản lý rừng, hộ dân và doanh nghiệp.
2. Đo xem nguy cơ cháy lan sang khu dân cư, rừng phòng hộ hay vùng du lịch sinh thái có làm thay đổi hành vi phát dọn bằng lửa hay không.
3. Kiểm tra liệu tăng cường giám sát bằng ảnh vệ tinh hoặc xử phạt công khai có thay đổi decision margin ở các khu vực property rights yếu không.

### Một vài research question khả thi cho Việt Nam

1. Khi rủi ro cháy lan sang rừng phòng hộ hoặc khu dân cư tăng lên do thời tiết, hộ hay doanh nghiệp có giảm hành vi đốt thực bì mạnh hơn không?
2. Các khu vực có cơ chế đồng quản lý rừng hoặc giao khoán rõ ràng có internalize fire risk tốt hơn các khu vực “đất công nhưng không ai thực sự bảo vệ” không?
3. Công bố công khai danh sách vi phạm và tăng xác suất phát hiện bằng remote sensing có tạo deterrence mạnh hơn ở những nơi enforcement truyền thống yếu không?

## Why this paper was selected tonight

Mình chọn paper này vì ba lý do. Thứ nhất, đây là paper top 5 rất mới trên ReStud và nằm đúng giao điểm giữa micro applied, development và environmental governance. Thứ hai, design của bài đặc biệt đáng học cho người làm nghiên cứu: câu hỏi lý thuyết cổ điển nhưng được trả lời bằng dữ liệu vi mô, không gian và thời tiết rất đẹp. Thứ ba, bài có liên hệ thực tiễn mạnh với các nước đang phát triển, bao gồm Việt Nam, nơi chất lượng quyền tài sản và năng lực enforcement thường quyết định rất lớn đến hiệu quả chính sách môi trường.

## Storage notes

- **GitHub:** `analysis.md` và `analysis.html` sẽ được lưu nếu thao tác tạo file thành công. `analysis.pdf` chỉ được ghi là có nếu tạo và lưu thành công. PDF gốc của paper chỉ được ghi là có nếu tải được file nhị phân thật và upload thành công.
- **Google Drive:** bỏ qua trong lượt này.
- **Email:** sẽ gửi dưới dạng briefing trong thân email. Nếu không có attachment thật sự tương thích, email sẽ nói rõ là không có tệp đính kèm.

## Final status update

- **GitHub analysis.md:** đã lưu thành công tại https://github.com/huylvu/00_reading/blob/main/The%20Origins%20and%20Control%20of%20Forest%20Fires%20in%20the%20Tropics%20-%20Balboni%20Burgess%20Olken/analysis.md
- **GitHub analysis.html:** đã lưu thành công tại https://github.com/huylvu/00_reading/blob/main/The%20Origins%20and%20Control%20of%20Forest%20Fires%20in%20the%20Tropics%20-%20Balboni%20Burgess%20Olken/analysis.html
- **GitHub analysis.pdf:** chưa tạo trong lượt này
- **GitHub paper PDF:** chưa lưu; mới xác minh được nguồn PDF công khai, nhưng môi trường chạy này chưa tải được raw PDF bytes từ nguồn ngoài để upload lại một cách ổn định
- **Google Drive:** skipped
- **Email sent:** đã gửi thành công tới `huymaeco@gmail.com` dưới dạng email văn bản không đính kèm; email đã nêu rõ link GitHub, trạng thái không có attachment, và giới hạn liên quan tới PDF gốc/Google Drive
