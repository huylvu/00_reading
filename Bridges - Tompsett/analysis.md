# Bridges

- **Tác giả:** Anna Tompsett
- **Journal:** The Review of Economic Studies
- **Năm:** 2025
- **Ngày agent chạy:** 2026-05-01
- **Nguồn bài báo chính:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdaf104/8402958
- **Nguồn PDF tốt nhất đã xác minh:** PDF chính thức từ trang Oxford Academic của bài báo qua nút PDF trên trang bài báo, cùng DOI https://doi.org/10.1093/restud/rdaf104
- **Trạng thái lưu GitHub trong lượt chạy này:** `analysis.md` và `analysis.html` đã được cập nhật trong repo `huylvu/00_reading`; `analysis.pdf` chưa được tạo/lưu; PDF gốc của paper mới dừng ở mức xác minh nguồn PDF chính thức chứ chưa tải và upload được file nhị phân vào repo
- **Trạng thái Google Drive:** bỏ qua trong lượt chạy này vì chưa có tuyến tạo Google Doc và tracker đúng folder đích một cách nhất quán

## 1. Metadata

- **Tiêu đề paper:** Bridges
- **Tác giả:** Anna Tompsett
- **Journal:** The Review of Economic Studies
- **Năm / trạng thái xuất bản:** published 23 December 2025; corrected and typeset 13 January 2026
- **Link bài báo:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdaf104/8402958
- **DOI:** https://doi.org/10.1093/restud/rdaf104
- **Nguồn xác minh bổ sung:** website tác giả xác nhận đây là bài ReStud open access: https://www.annatompsett.com/home/research
- **Replication package:** https://doi.org/10.5281/zenodo.17085642
- **Ghi chú về PDF:** trong lượt chạy này mình xác minh được nguồn PDF chính thức, nhưng môi trường shell không tải ổn định raw PDF bytes từ Oxford; vì vậy hiện chưa coi PDF gốc là đã lưu lên GitHub

## 2. Executive summary

Paper hỏi một câu rất cơ bản nhưng thường bị trả lời quá nhanh trong kinh tế hạ tầng: giao thông đường bộ có thực sự làm tăng hoạt động kinh tế, hay ta chỉ đang nhìn thấy giao thông được đặt ở nơi vốn dĩ đã phát triển hơn? Tompsett tách câu hỏi này thành hai lớp. Ở quy mô rất cục bộ, tác giả hỏi việc ở gần một nút hạ tầng giao thông hơn có làm khu vực đó giàu hơn theo đầu người hay không. Ở quy mô dài hạn hơn, tác giả hỏi khi kết nối giao thông được cải thiện mạnh nhờ cầu mới, kinh tế địa phương thay đổi ra sao trong nhiều thập kỷ sau đó.

Điểm mạnh của bài là không dựa vào một thiết kế duy nhất. Thiết kế thứ nhất tận dụng quy luật địa lý tại các điểm hợp lưu phụ lưu để giải thích vì sao cầu thường nằm ở phía thượng lưu hơn là hạ lưu, từ đó tạo khác biệt cục bộ trong mức độ kết nối. Thiết kế thứ hai dùng thời điểm khai thông cầu lớn trên sông Mississippi và Ohio như những cú sốc làm thay đổi khoảng cách tới cầu ở cấp quận trong giai đoạn 1860-2010. Hai chiến lược này cho phép tác giả đọc tác động của hạ tầng ở hai thang đo không gian và thời gian khác nhau.

Kết quả chính vừa thú vị vừa dễ gây nhầm nếu chỉ nhìn dữ liệu cắt ngang. Gần hạ tầng giao thông hơn có thể làm **thu nhập bình quân đầu người ở quy mô rất nhỏ thấp hơn**, nhưng đồng thời làm **mật độ dân cư và tổng hoạt động kinh tế ở quy mô lớn cao hơn**. Cụ thể, sau khi một quận trải qua giảm 50% khoảng cách tới cầu, giá trị đất nông nghiệp tăng tích lũy khoảng 9% và dân số tăng thêm khoảng 5% sau 30-40 năm. Cách dung hòa hai kết quả tưởng như trái nhau là: hạ tầng tạo lợi thế năng suất, thúc đẩy hình thành đô thị và chuyển dịch cơ cấu; sau đó quá trình suburbanization và sorting trong nội đô làm khu vực sát tuyến giao thông trở thành khu đông đúc hơn nhưng không nhất thiết giàu hơn theo đầu người.

Đây là bài đáng đọc vì nó dạy một bài học lớn trong micro applied và development: tác động của hạ tầng không chỉ là “tăng bao nhiêu” mà còn là “dịch chuyển cái gì đi đâu”. Nếu bỏ qua relocation effects, ta rất dễ diễn giải sai cả tác động phân bố lẫn tác động tổng thể.

## 3. Research question and motivation

### Câu hỏi trung tâm

Paper muốn đo tác động nhân quả của hạ tầng giao thông đường bộ lên hoạt động kinh tế. Nhưng tác giả làm điều đó theo một cách tinh tế hơn câu hỏi thông thường:

1. Gần hạ tầng giao thông hơn có làm một nơi giàu hơn không?
2. Tác động đó khác nhau thế nào giữa quy mô cục bộ và quy mô vùng?
3. Qua thời gian, hạ tầng làm tăng tổng hoạt động kinh tế, hay chủ yếu tái phân bố hoạt động kinh tế giữa các nơi?

### Động lực học thuật

Văn liệu về transport infrastructure từ lâu gặp vấn đề endogeneity: đường sá, đường sắt, cầu cống thường được xây ở nơi đã có tiềm năng tăng trưởng, khiến tương quan giữa hạ tầng và phát triển khó diễn giải nhân quả. Ngoài ra, nhiều bài trước hoặc tập trung vào một “natural experiment” rất hẹp, hoặc đo tác động ở một thang đo duy nhất, ví dụ giữa các vùng hay trong nội đô, chứ chưa nối được hai lớp đó lại với nhau.

Tompsett nhấn mạnh rằng ngay cả khi đã loại bớt selection effects, sự khác biệt giữa nơi kết nối tốt và nơi kết nối kém vẫn phản ánh đồng thời hai lực: tác động trực tiếp của hạ tầng lên năng suất và chi phí giao dịch, và relocation effects, tức sự dịch chuyển dân cư và hoạt động kinh tế qua không gian. Nếu không nhìn cả hai lực, người nghiên cứu rất dễ kết luận sai rằng hạ tầng ở gần người nghèo nên “không giúp phát triển”, hoặc ngược lại rằng hạ tầng làm nơi nào đó tăng trưởng mà không nhận ra tăng trưởng ấy phần nào đến từ việc hút bớt hoạt động từ nơi khác.

### Động lực thực tiễn

Hạ tầng giao thông là trung tâm của chính sách phát triển, cả ở Mỹ lịch sử lẫn ở các nước đang phát triển hôm nay. Nhưng policy question thực ra không chỉ là “có nên đầu tư hay không” mà còn là đầu tư ở đâu, tác động phân bố sẽ ra sao, và cần chuẩn bị gì cho quá trình đô thị hóa và tái sắp xếp dân cư mà hạ tầng tạo ra.

## 4. Main contribution

### Đóng góp 1: dữ liệu lịch sử rất hiếm và rất có giá trị

Tác giả tự xây một dataset bao phủ **mọi cầu đường sắt hoặc đường bộ từng được xây qua Mississippi và Ohio**, kéo dài từ cây cầu đầu tiên tới năm 2010. Chỉ riêng việc chọn “bridges over major rivers” làm object nghiên cứu đã rất thông minh: cầu là mắt xích hiếm nhưng quan trọng trong network, nên thay đổi ở cầu tạo ra thay đổi kết nối đủ sắc để nhận dạng.

### Đóng góp 2: hai chiến lược nhận dạng mới, bổ sung cho nhau

Paper không đặt cược hết vào một design.

1. **Where bridges are built:** dùng discontinuity trong chi phí xây cầu tại các điểm hợp lưu phụ lưu.
2. **When bridges are built:** dùng timing mở cầu như cú sốc gần-đột-ngột lên khả năng kết nối, trong khi quá trình lên kế hoạch xây cầu diễn ra rất chậm.

Cặp design này rất đẹp vì chúng đo được hai thứ khác nhau: tác động rất dài hạn ở quy mô nhỏ, gần dạng within-city; và động học vài thập kỷ sau cú sốc ở quy mô county, gần dạng between-place.

### Đóng góp 3: một cách đọc tinh tế về hạ tầng và economic geography

Nhiều bài infrastructure hỏi hạ tầng có làm GDP hay dân số tăng không. Bài này đi xa hơn: **cùng một hạ tầng có thể làm tăng hoạt động kinh tế ở quy mô lớn nhưng giảm thu nhập đầu người ở quy mô cục bộ gần tuyến**. Đó không phải mâu thuẫn; đó là hệ quả của urbanization, structural transformation, và sorting giữa city center với suburb.

### Đóng góp 4: mở rộng toolbox cho applied micro và development

Bridge placement around tributary confluences là một ý tưởng nhận dạng có thể dùng ở các bối cảnh khác, đặc biệt nơi sông lớn là rào cản vật lý mạnh. Timing-based distributed lag với cú sốc network cũng là một khung hữu ích cho nghiên cứu hạ tầng kéo dài nhiều thập kỷ.

## 5. Identification or methodology

### 5.1. Bối cảnh dữ liệu và trực giác ban đầu

Trước khi vào causal design, tác giả mô tả một pattern rất quan trọng trong dữ liệu hiện đại của Mỹ: thu nhập bình quân đầu người theo khoảng cách tới tuyến giao thông lớn có dạng **hump-shaped**. Rất xa hạ tầng thì nghèo, nhưng quá gần hạ tầng cũng không phải nơi giàu nhất; thu nhập đạt đỉnh khoảng vài km cách tuyến giao thông.

Đây chính là “empirical puzzle” mở đầu paper. Nếu chỉ nhìn tương quan, ta không biết hạ tầng gây ra pattern đó, hay planner đặt hạ tầng vào nơi vốn khác biệt, hay nơi có lợi thế giao thông thu hút người và doanh nghiệp rồi sau đó người giàu lại tránh ở quá gần tuyến.

### 5.2. Design 1: where bridges are built

**Ý tưởng.** Chi phí xây cầu tăng theo lưu lượng nước. Ở điểm một phụ lưu đổ vào dòng chính, lưu lượng nước tăng đột ngột ngay phía hạ lưu, khiến việc xây cầu ở phía hạ lưu đắt hơn phía thượng lưu. Hệ quả là cầu có xu hướng nằm ở phía thượng lưu các hợp lưu hơn là hạ lưu.

**Thực thi.** Tác giả so sánh các census tract upstream và downstream của hợp lưu gần nhất, với nearest-tributary fixed effects, kiểm soát khoảng cách dọc sông tới hợp lưu, tương tác cần thiết, trọng số kernel tam giác, và loại các tract quá xa hợp lưu.

**Assumption cốt lõi.** Nếu upstream và downstream quanh cùng một hợp lưu chỉ khác nhau một cách có hệ thống ở khả năng tiếp cận cầu/hạ tầng đất liền, thì chênh lệch kết quả giữa hai phía có thể đọc như tác động nhân quả của access.

**Điểm mạnh.** Trực giác địa lý rất rõ; so sánh rất cục bộ; tác giả bàn trực tiếp objection quan trọng rằng hợp lưu tự thân có thể là water-transport hub, nên paper kiểm soát khoảng cách tới hợp lưu và nhấn mạnh lợi thế của hợp lưu nên đối xứng upstream/downstream nếu chỉ có kênh đường thủy.

**Điểm dễ bị nghi ngờ.** Vẫn có thể còn khác biệt vi mô không đối xứng upstream/downstream; hiệu ứng khoảng cách tới cầu ở đây khá nhỏ về mặt tuyệt đối, nên dễ bị attenuation nếu đo lường không tốt; design này tốt để đo effect cục bộ dài hạn nhưng không tự nó kể được động học qua thời gian.

### 5.3. Design 2: when bridges are built

**Ý tưởng.** Thời điểm một cây cầu lớn thực sự mở thường chịu tác động của công nghệ, tài chính, quy hoạch, và thi công kéo dài hàng thập kỷ. Chính sự chậm chạp và nhiều trì hoãn idiosyncratic này khiến exact opening time của cầu có thể gần-exogenous với short-run deviation khỏi growth trend địa phương. Ngược lại, khi cầu mở, thay đổi trong feasible journeys và travel times có thể xuất hiện gần như ngay lập tức.

**Thực thi.** Tác giả xây panel county-level 1860-2010 cho 181 quận thuộc 14 bang dọc Mississippi và Ohio, remap toàn bộ về biên giới quận năm 1860 để tránh vấn đề thay đổi boundary. Sau đó paper ước lượng distributed lag model với year fixed effects, county fixed effects, county-specific quadratic trends, và lead/lags của thay đổi log distance to a bridge.

**Assumption cốt lõi.** Exact timing of changes in distance to a bridge là ngoại sinh với short-run deviations khỏi local long-run trends.

**Kiểm tra assumption.** Paper làm khá thuyết phục: lead coefficients gần zero; kết quả không bị driven bởi counties tự xây cầu; counties chỉ bị spillover từ cầu xây ở nơi khác cho kết quả tương tự; thêm flexible geographic time trends làm hiệu ứng nhỏ đi nhưng không đổi dấu hay timing; dùng simulation theo Borusyak and Hull để kiểm tra non-random exposure.

**Điểm mạnh.** Dữ liệu cực dài 150 năm cho phép thấy dynamic response thật chậm của population và land values. County-specific quadratic trends là cách bảo thủ để hấp thụ heterogeneity dài hạn.

**Điểm yếu / chỗ cần cẩn trọng.** Kết quả nhạy cảm với cách mô hình hóa trend, dù dấu hiệu tổng thể vẫn bền. Distance to bridge chỉ là proxy cho connectedness thật nên measurement error có thể đáng kể. Tác giả thừa nhận design này không thể đọc aggregate growth effect sạch nếu relocation giữa counties là lớn.

## 6. Results and interpretation

### 6.1. Kết quả cục bộ dài hạn: gần hơn nhưng nghèo hơn theo đầu người

Trong design upstream/downstream quanh hợp lưu, upstream tracts gần cầu hơn khoảng 60% và gần tuyến giao thông lớn hơn khoảng 27%. Nhưng đến năm 2010, các upstream tracts kết nối tốt hơn lại có **thu nhập bình quân đầu người thấp hơn khoảng 13%**.

Đây là kết quả dễ gây sốc nếu ta giữ trực giác “gần hạ tầng thì giàu hơn”. Tuy nhiên paper cho thấy đồng thời upstream tracts cũng có **mật độ dân cư cao hơn rõ rệt**. Nói cách khác, hạ tầng kéo hoạt động và dân cư tới, nhưng ở quy mô rất nhỏ, khu sát tuyến có thể trở thành khu dense, kiểu city-center, không phải khu giàu nhất.

### 6.2. Kết quả động theo thời gian: cầu mới làm activity tăng dần qua nhiều thập kỷ

Trong county panel, khi khoảng cách tới cầu giảm mạnh:

- **giá trị đất nông nghiệp** tăng ngay và tăng tích lũy khoảng **9% sau 30-40 năm**
- **dân số** tăng tích lũy khoảng **5% sau 30-40 năm**

Giá trị đất tăng mạnh hơn dân số cho thấy total activity tăng nhanh hơn population, tức per capita activity nhiều khả năng cũng tăng, nhưng tăng ít hơn total activity. Paper dùng land values như proxy cho total economic activity và chênh giữa log land value với log population như proxy thô cho per capita activity; kết quả cùng dấu nhưng nhỏ hơn, đúng trực giác.

### 6.3. Cơ chế: urbanization, structural transformation, suburbanization

Phần hay nhất của paper là Section 6, nơi tác giả không dừng ở “bridge causes growth” mà ghép hai nhóm kết quả thành một narrative kinh tế:

1. **Cities form around transport routes.** Sau cú sốc giảm distance to bridge, tăng dân số tập trung ở town/city; lao động rời nông nghiệp sang retail/wholesale, một phần sang manufacturing và services; construction employment tăng, gợi ý built-up area mở rộng.
2. **Cities expand outward.** Các tract gần hạ tầng hơn có tỷ trọng housing stock cũ hơn, ám chỉ lõi đô thị hình thành sớm quanh tuyến giao thông; khu downstream có nhà mới hơn, gắn với giai đoạn suburbanization sau đó.
3. **Sorting within cities đảo dấu gradient thu nhập đầu người ở cự ly ngắn.** Khu upstream đông hơn, ở nhà nhỏ hơn, nhiều apartment hơn, commute ngắn hơn, đi public transport nhiều hơn, ô nhiễm không khí cao hơn đôi chút. Khu downstream giống suburb hơn: nhà lớn hơn, đắt hơn, commute bằng ô tô nhiều hơn.

Khi ghép ba bước này lại, kết quả “gần hạ tầng hơn nhưng thu nhập bình quân thấp hơn ở cự ly ngắn” trở nên rất hợp lý: hạ tầng ban đầu tạo lợi thế sản xuất và đô thị hóa; nhưng sau nhiều thập kỷ, người giàu sort ra xa lõi giao thông hơn.

### 6.4. Diễn giải kinh tế

Paper nhắc ta rằng “tác động của hạ tầng” không có một con số duy nhất. Con số đó phụ thuộc vào spatial scale, time horizon, outcome variable, và mức độ relocation được phép xảy ra. Ở quy mô rộng và trong trung hạn dài, cầu làm economic activity tăng. Ở quy mô rất cục bộ và sau khi đô thị trưởng thành, khu sát hạ tầng có thể là nơi đông, productive theo aggregate sense, nhưng không phải nơi có income per capita cao nhất.

## 7. What is special or elegant about the paper

Điểm đẹp nhất của bài là sự kết hợp giữa **economic geography intuition** và **micro-identification discipline**.

1. **Chọn “bridge” làm object nghiên cứu là một ý tưởng cực đẹp.** Thay vì cố đo cả network đường bộ khổng lồ, tác giả bám vào một mắt xích hiếm nhưng then chốt.
2. **Hai design nói chuyện với nhau.** Một design cho local long-run spatial comparison; design kia cho dynamic response over decades. Nhờ đó paper kể được một câu chuyện hoàn chỉnh hơn.
3. **Không né kết quả trái trực giác.** Bài giữ nguyên sự căng thẳng giữa local per-capita effects âm và broader activity effects dương, rồi dùng economic narrative để giải thích.
4. **Paper không overclaim về aggregate welfare.** Tác giả rất cẩn thận: kết quả không đủ để suy ra tổng hiệu ứng tăng trưởng hay welfare nếu không có structural model, vì relocation effects làm counterfactual aggregate không rõ.

## 8. Required background knowledge

### 8.1. Transport infrastructure và market access

Ý tưởng nền là hạ tầng làm giảm trade costs, commuting costs, và tăng market access. Nhưng market access không tự động đồng nghĩa với local prosperity theo đầu người, vì dân cư và doanh nghiệp có thể di chuyển để tận dụng lợi thế ấy.

### 8.2. Economic geography và relocation effects

Đây là xương sống để hiểu paper. Khi chi phí vận tải giảm, doanh nghiệp có thể tập trung hơn ở vài nơi, dân cư có thể kéo đến nơi có cơ hội tốt hơn, và trong nội đô người giàu, người nghèo có thể chọn vị trí khác nhau. Vì thế observed difference across places luôn là tổ hợp của productivity effects và sorting effects.

### 8.3. Reduced-form identification

Người đọc cần quen với local comparison quanh quasi-discontinuity, fixed effects, distributed lag / event-study logic, pre-trend / lead coefficients, và robustness to alternative trend controls. Phần rất đáng học ở đây là paper không cần một policy shock clean theo nghĩa thường thấy; tác giả xây identification từ geography và timing.

### 8.4. Dùng land values như proxy cho economic activity

Trong historical data, output hay income thường đo kém. Land values có thể phản ánh discounted value of productive opportunities, nên là proxy hữu ích cho total economic activity. Nhưng đây không phải proxy hoàn hảo: có measurement error, có thể understate urban land values, và interpretation phụ thuộc vào framework spatial equilibrium / monocentric city.

## 9. Limitations and open questions

### Hạn chế 1: aggregate effect chưa được point identify

Paper đo rất thuyết phục tác động tương đối giữa nơi kết nối tốt hơn và kém hơn. Nhưng nếu relocation lớn, ta chưa biết tổng tăng trưởng của toàn hệ thống là bao nhiêu. Một nơi tăng có thể partly là do hút activity từ nơi khác.

### Hạn chế 2: proxy outcome chưa hoàn hảo

Land values là lựa chọn hợp lý cho dữ liệu lịch sử, nhưng vẫn là proxy. Nếu urban land appreciation bị đo thiếu bởi agricultural land values, hiệu ứng total activity có thể đang bị underestimate.

### Hạn chế 3: trend specification là điểm nhạy cảm

County-specific quadratic trends có lý và bảo thủ, nhưng luôn có tradeoff: quá mềm thì lo pre-trend bias; quá chặt thì hút mất persistent treatment effects. Paper nói rõ điều này, nhưng nó vẫn là điểm người đọc cần giữ trong đầu.

### Hạn chế 4: mechanism chưa tách riêng

Paper kể một narrative rất thuyết phục về urbanization, industrialization, commuting, pollution, và sorting. Nhưng nó chưa tách riêng được kênh nào là chủ đạo: commuting cost, consumer market access, input market access, export opportunity, land use regulation, pollution disamenities, hay discriminatory policies như redlining.

### Câu hỏi mở

1. Nếu đưa bài này vào structural spatial model, aggregate welfare effect của bridge investment là bao nhiêu?
2. Liệu kết quả “gần hạ tầng nhưng nghèo hơn theo đầu người” có mạnh hơn ở các bối cảnh có suburbanization sâu, như Mỹ, so với châu Á?
3. Trong developing countries hiện nay, informal settlement quanh hạ tầng mới có phải là cơ chế tương tự nhưng ở một giai đoạn thể chế khác?

## 10. Takeaways for a researcher

1. **Đừng để outcome chính quyết định luôn đơn vị không gian.** Cùng một câu hỏi hạ tầng nhưng tract-level và county-level có thể cho hai sự thật khác nhau, đều đúng.
2. **Một design không đủ để kể hết câu chuyện.** Nếu có thể, hãy ghép nhiều nguồn variation bổ sung nhau thay vì ép một design làm mọi việc.
3. **Relocation effects là first-order concern trong applied spatial work.** Không phải nuisance nhỏ.
4. **Historical data construction có thể là đóng góp lớn ngang identification.** Dataset cầu qua Mississippi và Ohio chính là một phần quan trọng của paper.
5. **Kết quả trái dấu không phải tín hiệu paper yếu.** Nhiều khi đó là tín hiệu bạn đang chạm vào một cơ chế kinh tế thật.
6. **Event-study / distributed lag chỉ thuyết phục khi pre-trend được kiểm tra nghiêm túc và trend controls được bàn minh bạch.**
7. **Narrative mechanism tốt không thay thế causal identification, nhưng giúp biến reduced-form estimates thành insight có ích.**

## 11. Vietnam relevance and extension

Đây là phần paper đặc biệt gợi mở cho Việt Nam.

### Vì sao liên quan tới Việt Nam

Việt Nam đang ở đúng giai đoạn mà đầu tư giao thông lớn có thể tái tổ chức không gian kinh tế: cao tốc Bắc - Nam, vành đai đô thị lớn, cầu vượt sông ở Đồng bằng sông Cửu Long, hạ tầng cảng, logistics, và đường kết nối khu công nghiệp. Trong bối cảnh này, câu hỏi không chỉ là “đường mới có làm huyện đó tăng trưởng không”, mà còn là activity tăng ở đâu và giảm ở đâu, đất đai và dân cư dịch chuyển ra sao, ai hưởng lợi, ai bị đẩy ra xa, informal housing hay phân tầng không gian có tăng không.

### Có triển khai được ở Việt Nam không?

Có, nhưng cần dữ liệu tốt và một setting hợp lý. Những điều kiện cần gồm dữ liệu GIS về cầu, đường, thời điểm mở tuyến; dữ liệu dân số, đất đai, giá đất hoặc proxy activity theo không gian nhỏ; dữ liệu doanh nghiệp/cơ sở sản xuất hoặc ảnh viễn thám ban đêm, built-up area, land use; và boundary harmonization qua thời gian.

### Trở ngại chính

1. Dữ liệu lịch sử không gian nhỏ ở Việt Nam khó đồng nhất hơn Mỹ.
2. Quy hoạch, giải tỏa, zoning, và đất đai nhà nước làm endogenous placement khó hơn.
3. Giá đất bị ảnh hưởng mạnh bởi thể chế và hành vi đầu cơ, nên interpretation cần cẩn thận.
4. Migration và đăng ký hộ khẩu có thể làm số liệu dân cư đo trễ hoặc đo lệch.

### Những hướng mở rộng hợp với Việt Nam

1. **Bridges and delta development:** tác động của các cầu lớn ở Đồng bằng sông Cửu Long lên chuyển dịch khỏi phà, lên market access nông sản, và lên cấu trúc thị trấn ven sông.
2. **Expressways and peri-urban sorting:** cao tốc và vành đai có làm khu gần nút giao trở nên productive hơn nhưng nghèo hơn theo đầu người do housing sorting và lao động nhập cư không.
3. **Infrastructure and informal settlement:** khu gần hạ tầng mới có hút mạnh nhà trọ, khu ở tự phát, hay lao động di cư hơn không; nếu có, welfare effect ròng là gì?

### Một số research question cụ thể cho Việt Nam

1. Việc mở cầu thay phà trên các tuyến huyết mạch ở Đồng bằng sông Cửu Long có làm tăng tổng activity của huyện kết nối tốt hơn, hay chủ yếu tái phân bổ activity từ bờ bên kia?
2. Các nút giao cao tốc mới quanh Hà Nội và TP.HCM có tạo gradient “gần hạ tầng nhưng không giàu nhất” tương tự suburbanization pattern mà paper tìm thấy không?
3. Nếu kết hợp dữ liệu quy hoạch hạ tầng với ảnh vệ tinh và dữ liệu giá đất, ta có thể tách được productivity gains khỏi speculative land gains hay không?

## 12. Đánh giá cuối

Đây là một bài rất đáng đọc cho người làm applied micro liên quan tới hạ tầng, spatial economics, urban-development interface, hay long-run development. Giá trị lớn nhất của paper không nằm ở một con số tác động duy nhất mà ở cách nó buộc người đọc phải nghĩ lại về meaning của “tác động của hạ tầng”.

Nếu phải gói gọn bài trong một câu: **hạ tầng giao thông có thể làm kinh tế phát triển hơn bằng cách tái tổ chức không gian kinh tế, và chính quá trình tái tổ chức ấy có thể khiến nơi sát hạ tầng không phải là nơi giàu nhất theo đầu người.**

## 13. Trạng thái lưu trữ của lượt chạy này

- `analysis.md`: đã cập nhật lên GitHub trong thư mục paper này
- `analysis.html`: được ưu tiên cập nhật cùng để đọc dễ hơn
- `analysis.pdf`: chưa tạo trong lượt chạy này; trạng thái cuối phải hiểu là chưa tạo và chưa lưu
- **PDF gốc của paper:** đã xác minh được nguồn PDF chính thức từ Oxford Academic, nhưng chưa coi là đã lưu lên GitHub vì chưa tải và upload được file nhị phân thật sự
- **Google Drive:** bỏ qua