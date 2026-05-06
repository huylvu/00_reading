# Slum Upgrading and Long-Run Urban Development: Evidence from Indonesia

- Tác giả: Mariaflavia Harari, Maisy Wong
- Journal: The Review of Economic Studies
- Năm: 2025
- Ngày agent chạy: 2026-05-07 (Asia/Saigon)
- Trang bài báo chính: https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdaf090/8287039
- Nguồn PDF tốt nhất đã xác minh để phân tích: manuscript công khai của tác giả, bản `September 2024`, https://faculty.wharton.upenn.edu/wp-content/uploads/2016/11/HarariWong_SlumUpgrading_Sept2024.pdf
- Ghi chú về PDF chính thức: Oxford Academic có corrected proof xuất bản ngày 15 October 2025 và corrected/typeset ngày 11 November 2025, nhưng môi trường chạy này không tải trực tiếp file PDF chính thức về cục bộ được
- Trạng thái lưu trên GitHub trong lượt chạy này: đã lưu `analysis.md` và `analysis.html` vào repo `huylvu/00_reading` trong thư mục `Slum Upgrading and Long-Run Urban Development - Harari Wong/`; chưa lưu `analysis.pdf`; chưa lưu raw PDF gốc của paper
- Trạng thái lưu trên Google Drive trong lượt chạy này: bỏ qua, vì bộ công cụ hiện có không cho phép mình tạo Google Doc và Google Sheet tracker trong đúng folder Drive đích một cách đáng tin cậy trong cùng lượt chạy

## Executive summary

Paper hỏi một câu rất quan trọng trong urban/development economics: nâng cấp khu ổ chuột tại chỗ có giúp thành phố phát triển tốt hơn về dài hạn, hay lại vô tình giữ đất ở trạng thái phi chính thức quá lâu và làm chậm tái phát triển ở những vị trí đất rất đắt?

Harari và Wong trả lời câu hỏi đó bằng cách nghiên cứu Kampung Improvement Program (KIP) ở Jakarta, một chương trình khổng lồ giai đoạn 1969-1984 đã nâng cấp hạ tầng cơ bản cho khoảng 5 triệu người, phủ tới 25% diện tích đất thành phố. Họ kết hợp bản đồ chính sách chi tiết, dữ liệu giá đất, chiều cao công trình, cadastral maps, ảnh Google Street View và ảnh điều tra thực địa để so sánh các khu được nâng cấp với các kampung lịch sử không được nâng cấp nhưng tương đồng về không gian.

Kết quả cốt lõi là khá phản trực giác nếu chỉ nhìn bằng lăng kính phúc lợi ngắn hạn. Về dài hạn, các khu KIP ngày nay có giá đất thấp hơn, nhà thấp tầng hơn, mức độ phi chính thức cao hơn, đất bị chia nhỏ hơn và mật độ hộ cao hơn. Hiệu ứng âm mạnh nhất tập trung gần trung tâm thành phố, nơi chi phí cơ hội của việc duy trì đất phi chính thức là lớn nhất. Trong mô hình cân bằng không gian, nếu “gỡ” cú sốc KIP hiện tại trên toàn thành phố, phúc lợi toàn thành phố tăng khoảng 3.3%; khoảng 78% phần tăng này đến từ khu trung tâm. Nhưng lợi ích đó không trung tính phân phối: nhóm kỹ năng cao được lợi, còn nhóm kỹ năng thấp chịu thiệt do bị đẩy khỏi các vị trí hấp dẫn hơn.

Vì sao bài này đáng đọc? Vì nó làm rất tốt ba việc cùng lúc: đưa ra bằng chứng nhân quả dài hạn cho một chính sách phát triển đô thị kinh điển; chỉ ra một trade-off hiệu quả-phân phối rất thật thay vì nói chung chung; và gắn reduced-form evidence với một spatial equilibrium model đủ chặt để nói về “nên formalize chỗ nào trước” chứ không chỉ “có hiệu ứng hay không”.

## Research question and motivation

Câu hỏi trung tâm là: slum upgrading tại chỗ có tạo ra lợi ích bền vững cho thành phố, hay có thể làm chậm formalization và tái phát triển ở những nơi mà đất lẽ ra nên chuyển sang sử dụng hiệu quả hơn?

Bối cảnh học thuật và thực tiễn rất mạnh. Nhiều thành phố ở các nước đang phát triển đang phải hấp thụ tăng trưởng dân số đô thị cực lớn trong điều kiện quyền tài sản yếu, thị trường đất bị phân mảnh, và chính trị của giải tỏa cưỡng bức rất nhạy cảm. Chính sách nâng cấp khu ổ chuột có sức hút vì nó giúp cải thiện điều kiện sống mà không cần di dời hàng loạt. Nhưng đúng chỗ mạnh đó cũng có thể là điểm yếu dài hạn: một khi khu ổ chuột được nâng cấp và người dân tin rằng họ sẽ không bị đuổi đi, khu vực đó có thể “ổn định” ở trạng thái phi chính thức lâu hơn, khiến chi phí gom đất, hợp thức hóa và xây dựng lại tăng lên sau này.

Khoảng trống mà paper muốn lấp là thiếu bằng chứng định lượng dài hạn, ở độ phân giải không gian rất cao, về việc một chương trình nâng cấp khu ổ chuột quy mô lớn ảnh hưởng thế nào đến quỹ đạo phát triển đô thị hàng chục năm sau. Văn liệu trước có nhiều thảo luận chuẩn tắc và case study, nhưng ít nghiên cứu có thể nói vừa nhân quả vừa dài hạn.

## Main contribution

Đóng góp thứ nhất là bằng chứng nhân quả dài hạn về KIP khi Jakarta đang “mọc ra khỏi” trạng thái phi chính thức. Đây không chỉ là đo tác động ngắn hạn của hạ tầng cơ bản, mà là xem 30-40 năm sau các khu được nâng cấp đã trở thành gì trong cấu trúc đô thị.

Đóng góp thứ hai là dữ liệu. Bài ghép được bản đồ ranh giới chương trình chi tiết, giá đất hành chính, chiều cao nhà, dữ liệu đăng ký thửa đất, và một photographic informality index được xây từ ảnh Google Street View cộng với ảnh điều tra thực địa. Phần đo lường informality này rất đáng chú ý vì nó lấp khoảng trống khi dữ liệu hành chính thường không phản ánh tốt “độ chính thức” thực tế của khu dân cư.

Đóng góp thứ ba là khung phân tích. Paper không dừng ở reduced-form estimates mà nhúng kết quả vào một spatial equilibrium model với hai nhóm hộ và hai phân khúc nhà ở formal/informal. Nhờ vậy, tác giả mới trả lời được câu hỏi chính sách sâu hơn: nếu formalize thì lợi ích ở đâu lớn nhất, ai được lợi, ai chịu chi phí, và có thể thiết kế bundle policy nào để giảm displacement của người nghèo.

Trong micro applied và development economics, đây là một đóng góp quan trọng vì nó nối identification, đo lường, và counterfactual policy design trong một setting có relevance rất cao cho các đô thị đang phát triển.

## Identification or methodology

### Thiết kế thực nghiệm reduced-form

Paper dùng ba lớp so sánh chính.

Thứ nhất, trong toàn mẫu thành phố, tác giả so sánh các location được KIP và không được KIP trong cùng một hamlet. Ý tưởng là trong cùng một đơn vị vi mô, nhiều yếu tố nền tảng khó quan sát đã gần nhau hơn.

Thứ hai, tác giả thu hẹp mẫu vào các historical kampungs có trước KIP, rồi so sánh kampung được xử lý với kampung không được xử lý trong cùng locality. Bước này xử lý mạnh hơn lo ngại rằng KIP vốn nhắm vào các khu slum tệ hơn từ đầu.

Thứ ba, bài dùng boundary discontinuity design trong phạm vi 200 mét quanh ranh giới KIP. Giả định nhận dạng cốt lõi là chất lượng không quan sát được thay đổi trơn qua ranh giới này sau khi đã kiểm soát các yếu tố địa lý và fixed effects liên quan.

Điểm mạnh của bộ design là không lệ thuộc vào một chiến lược duy nhất. Khi cùng một pattern xuất hiện trong full sample, historical-kampung sample và boundary design, độ tin cậy của diễn giải tăng lên đáng kể.

### Biến kết quả và đo lường

Các outcome chính gồm:

- log giá đất định giá hành chính
- xác suất có nhà cao trên 3 tầng và log số tầng
- chỉ số informality dựa trên xếp hạng ảnh
- tỷ trọng thửa đất chưa đăng ký
- mật độ thửa đất và mật độ hộ

Phần đo lường hình ảnh là điểm rất hay. Tác giả dùng ảnh Google Street View cho khoảng 90% mẫu ảnh, và cử điều tra viên đi chụp thực địa cho các điểm mà Street View không vào được. Cách làm này đặc biệt phù hợp với slums vì nhiều khía cạnh “phi chính thức” hiện ra rõ hơn ở góc nhìn mặt đất so với dữ liệu vệ tinh hay hồ sơ hành chính.

### Logic cơ chế

Paper đặt ra vài kênh then chốt:

- nâng cấp làm khu slum hấp dẫn hơn để ở
- bảo đảm không cưỡng chế di dời làm cư dân tin hơn vào quyền chiếm hữu
- cư dân ở lại lâu hơn, đất bị chia nhỏ hơn, mật độ tăng
- chi phí gom đất và formalization tăng
- vì vậy khu KIP bị chậm tái phát triển so với khu tương tự không nhận KIP

Tác giả cũng kiểm tra xem có phải chênh lệch ngày nay chỉ do cường độ hạ tầng KIP ban đầu khác nhau hay không. Họ không tìm thấy bằng chứng mạnh rằng loại hay cường độ đầu tư ban đầu giải thích chênh lệch land values hiện nay; điều này phù hợp với việc bản thân các nâng cấp cơ bản có tuổi thọ hữu ích tương đối ngắn, trong khi cái bền hơn là cấu trúc tenure và land assembly.

### Mô hình cấu trúc

Spatial equilibrium model có hai loại cư dân:

- nhóm kỹ năng cao sống trong phân khúc formal
- nhóm kỹ năng thấp sống trong phân khúc informal

Cư dân chọn nơi ở, nơi làm việc và lượng nhà ở; thu nhập bị chiết khấu bởi commuting costs; tiện ích phụ thuộc vào amenities, rents và housing consumption. Phía cung gồm đất formal và informal, với một “formalization tax” đại diện cho frictions khi chuyển đất từ informal sang formal. Các wedge giữa khu KIP và non-KIP trong land values và building heights được diễn giải là khác biệt về amenities và chi phí formalization.

Điểm mạnh lớn của mô hình là nó đủ tối giản để minh bạch intuition nhưng vẫn đủ giàu để nói về displacement, spillovers và aggregate welfare. Điểm dễ bị nghi ngờ là như mọi mô hình cân bằng không gian, kết quả welfare phụ thuộc vào calibration và cách ánh xạ reduced-form wedges sang primitives của model.

## Results and interpretation

### Kết quả reduced-form chính

Trong manuscript September 2024, tác giả tóm tắt baseline estimates như sau:

- KIP areas có giá đất thấp hơn khoảng 10%
- xác suất có tòa nhà trên 3 tầng thấp hơn 7 điểm phần trăm
- số tầng của công trình thấp hơn khoảng 9%

Những hiệu ứng này khá lớn: ít nhất cỡ 40% của control-group means theo phần giới thiệu của paper. Diễn giải kinh tế là KIP không chỉ “để lại” chênh lệch hình thức bề ngoài; nó liên quan tới việc các khu này chuyển đổi chậm hơn sang các dạng sử dụng đất có mật độ và giá trị cao hơn.

### Informality và fragmentation

KIP areas “phi chính thức” hơn theo nhiều thước đo. Chỉ số informality dựa trên ảnh cao hơn khoảng 0.27 đến 0.32 điểm tùy specification, trong khi control-group mean xấp xỉ 1-1.1. Tỷ trọng thửa đất chưa đăng ký cao hơn khoảng 2 đến 3 điểm phần trăm trong full và historical samples. Parcel density cao hơn khoảng 9 đến 13 parcels mỗi pixel; household density cũng cao hơn rõ rệt, với ước lượng full-sample ngụ ý khoảng 14 hộ nhiều hơn mỗi pixel so với đối chứng.

Điều này rất quan trọng cho diễn giải cơ chế. Nếu KIP chỉ làm tăng phúc lợi cư trú mà không ảnh hưởng đến trajectory của khu đất, ta không nhất thiết phải thấy fragmentation và density tăng mạnh như vậy về dài hạn. Pattern quan sát được phù hợp hơn với câu chuyện “residents stay, land subdivides, assembly gets harder”.

### Heterogeneity theo vị trí trong thành phố

Paper cho thấy average effect che lấp heterogeneity rất lớn. Hiệu ứng âm mạnh nhất nằm gần CBD. Với land values, hệ số KIP x Center là khoảng -0.14; KIP x Middle khoảng -0.10; KIP x Periphery khoảng -0.09. Với log building heights, các hệ số tương ứng khoảng -0.13, -0.06, và -0.04.

Đây là chỗ paper thực sự hay: nó không nói “slum upgrading luôn xấu về dài hạn”, mà nói chi phí cơ hội của việc duy trì informality phụ thuộc rất mạnh vào vị trí. Ở khu trung tâm, nơi chênh lệch lợi nhuận giữa dùng đất formal và informal là lớn nhất, cùng một chính sách có thể tạo ra misallocation đáng kể hơn nhiều.

### Amenities không phải lời giải thích chính

Tác giả không tìm thấy bằng chứng rằng khác biệt hiện nay đến từ việc khu KIP được đầu tư vật chất “kém hơn” hay “tốt hơn” theo từng hạng mục hạ tầng ban đầu. Ngoài ra, đến nay access tới school, hospital, police station, bus stop khá tương đồng giữa KIP và non-KIP; thứ khác biệt hơn là formal amenities như retail density và office density thấp hơn ở KIP areas.

Điều đó làm cho lập luận paper sắc hơn: vấn đề không phải “KIP xây hạ tầng tệ nên khu đó kém phát triển”, mà là KIP có thể làm thay đổi incentive và frictions của quá trình formalization về dài hạn.

### Kết quả welfare từ mô hình

Trong counterfactual benchmark “lift KIP everywhere”, nhóm H gain khoảng 5.2%, nhóm L lose khoảng 2.1%, và phúc lợi toàn thành phố tăng khoảng 3.3%; dân số thành phố tăng ròng khoảng 2.5%. Đây là một kết quả rất giàu ý nghĩa chính sách: formalization tạo aggregate gains, nhưng không Pareto-improving.

Quan trọng hơn, khoảng 78% city-wide gains đến từ việc lift KIP ở khu trung tâm. Nếu lift KIP chỉ ở center, phúc lợi toàn thành phố tăng khoảng 2.6%; middle chỉ khoảng 0.4%; periphery khoảng 0.1%. Tức là misallocation chủ yếu nằm ở những nơi KIP lại hiện diện nhiều nhất trong đô thị lõi.

Paper còn chỉ ra vài cách giảm trade-off hiệu quả-phân phối. Một package kết hợp bỏ KIP ở trung tâm và nới hạn chế chiều cao có thể giữ lợi ích cho nhóm formal mà giảm displacement cho nhóm informal. Ngoài ra, phân phối lại khoảng 5% formal land surplus cho nhóm kỹ năng thấp có thể khiến cả hai nhóm cùng được lợi trong counterfactual của model.

## What is special or elegant about the paper

Điểm đẹp nhất của paper là tác giả không chọn một framing đạo đức quá dễ. Slum upgrading thường được nhìn như chính sách “pro-poor” và formal redevelopment thường bị xem là lực đẩy người nghèo ra ngoài. Paper không phủ nhận điều đó, nhưng buộc người đọc thấy rằng một chính sách nhân văn ở horizon ngắn có thể tạo ra inefficiency lớn ở horizon dài, nhất là trên đất trung tâm cực kỳ khan hiếm.

Điểm đẹp thứ hai là cách nối từ urban morphology sang welfare economics. Từ lower land values, shorter buildings, fragmented parcels và informality, paper đi tới một welfare question có cấu trúc: khi nào “preserving shelter” biến thành “preserving misallocation”?

Điểm đẹp thứ ba là chiến lược đo informality. Việc dùng ảnh mặt đất để xây rank-based index nghe có vẻ thủ công, nhưng thực ra rất thông minh trong bối cảnh mà administrative records và remote sensing đều thiếu hụt cho câu hỏi này.

Một bài học nghiên cứu rất đáng học là cách tác giả không chỉ chạy robustness checks cho có. Họ dùng staggered rollout, placebo borders, persistence logic, spatial decay, và phân rã heterogeneity để xử lý từng mối nghi ngờ đúng bản chất của setting.

## Required background knowledge

### 1. Slum upgrading và formalization

Người đọc cần biết slum upgrading khác với slum clearance hay relocation. Upgrading là cải thiện hạ tầng và điều kiện sống tại chỗ, thường kèm một mức độ bảo đảm cư trú nào đó. Formalization là quá trình chuyển khu đất và nhà ở sang trạng thái có quyền tài sản và quy hoạch chính thức rõ ràng hơn.

### 2. Spatial misallocation

Đây là ý tưởng rằng đất hoặc các yếu tố sản xuất không được dùng ở nơi mang lại giá trị kinh tế cao nhất, do frictions như quyền tài sản yếu, holdout, quy hoạch, hay chi phí giao dịch. Trong paper này, misallocation xuất hiện khi đất trung tâm vẫn bị “kẹt” trong trạng thái informal thấp tầng.

### 3. Boundary discontinuity design

BDD so sánh các điểm ở rất gần hai phía của một ranh giới chính sách. Intuition là nếu ta đứng đủ gần biên, hai bên giống nhau ở nhiều mặt khó quan sát; khác biệt outcome có thể gán nhiều hơn cho treatment. Nhưng thiết kế này luôn nhạy với spillovers qua biên và chuyện ranh giới có bám theo features vật lý hay không.

### 4. Spatial equilibrium model

Đây là mô hình trong đó households và firms/developers phản ứng với rents, wages, commuting costs và amenities, khiến tác động ở một khu lan ra toàn thành phố. Nếu chỉ nhìn reduced-form local effects, ta bỏ lỡ displacement, price adjustments và resorting across space. Paper dùng mô hình để chuyển từ “local treatment effect” sang “city-wide welfare and distribution”.

### 5. Holdout và land assembly

Khi tái phát triển một khu dày đặc với rất nhiều claimants, mỗi người nắm một mảnh quyền lợi nhỏ có thể trì hoãn thương lượng để đòi phần cao hơn. Điều này làm chi phí gom đất tăng lên mạnh, đặc biệt trong các khu informal mà hồ sơ pháp lý vốn đã không rõ.

## Limitations and open questions

Hạn chế thứ nhất là reduced-form outcomes được đo ở một lát cắt dài hạn hiện đại, nên paper mạnh về long-run endpoint nhưng yếu hơn về động học giữa đường. Ta không quan sát rõ khi nào reversal xảy ra: sau 5 năm, 15 năm hay 30 năm.

Hạn chế thứ hai là welfare exercise dựa trên một mô hình tĩnh. Chính tác giả cũng nói rõ rằng họ không thể từ đây suy ra phúc lợi tích lũy toàn bộ của KIP kể từ lúc chương trình bắt đầu. Để trả lời câu hỏi “ex ante KIP có đáng làm không”, cần cộng cả benefits ngắn hạn nhiều thập niên với costs dài hạn, và cần dữ liệu lịch sử tốt hơn về displaced residents lẫn quality-of-life gains ban đầu.

Hạn chế thứ ba là ánh xạ từ reduced-form wedges sang amenities và formalization costs là hợp lý nhưng không duy nhất. Một số cơ chế khác, như politics địa phương, developer expectations, hay regulatory complementarities, có thể cùng vận hành.

Hạn chế thứ tư là tính ngoại suy. Jakarta là megacity rất đặc thù: trung tâm đắt, tăng trưởng mạnh, property market năng động, và KIP phủ diện rất lớn. Kết quả rằng center mới là chỗ misallocation lớn nhất có thể không map một-một sang các thành phố nhỏ hơn hoặc ở giai đoạn đô thị hóa sớm hơn.

Các câu hỏi mở rất hay gồm:

- intergenerational effects của việc ở lại kampung được nâng cấp là gì?
- nếu có compensation scheme tốt hơn, trade-off efficiency-equity thay đổi ra sao?
- khi climate risk làm trung tâm Jakarta mất giá trị tương đối, kết luận dynamic efficiency có đảo chiều không?
- trong những thành phố mới đô thị hóa, threshold nào đánh dấu lúc upgrading nên nhường chỗ cho redevelopment?

## Takeaways for a researcher

1. Đừng chỉ hỏi một chính sách có cải thiện outcome hiện tại không; hãy hỏi nó thay đổi quỹ đạo tái phân bổ nguồn lực về dài hạn thế nào.
2. Heterogeneity theo không gian có thể là toàn bộ câu chuyện. Average treatment effect ở đây hữu ích, nhưng insight chính sách thật sự nằm ở trung tâm so với ngoại vi.
3. Đo lường tốt có thể là đóng góp nhận dạng quan trọng không kém design. Photographic informality index ở đây tạo ra một outcome mà dữ liệu chuẩn thường không có.
4. Khi policy can create shelter and lock-in at the same time, hãy tách kênh amenity khỏi kênh formalization/assembly costs.
5. Reduced-form và structural không nhất thiết là hai thế giới tách biệt. Nếu reduced-form moments được dùng có kỷ luật, structural layer có thể trả lời những câu local regressions không trả lời được.
6. Với place-based policy, phải nghĩ nghiêm túc về distributional incidence. Aggregate gains có thể đi cùng displacement đủ lớn để làm policy rất khó chấp nhận nếu thiếu compensation.

## Vietnam relevance and extension

Bài này có relevance rất cao với Việt Nam, đặc biệt ở các đô thị như Hà Nội, TP.HCM, Hải Phòng hay Đà Nẵng, nơi cùng lúc tồn tại:

- nhu cầu tái phát triển các khu dân cư cũ, ngõ hẹp, đất phân mảnh
- căng thẳng giữa chỉnh trang tại chỗ và tái thiết quy mô lớn
- quyền sử dụng đất tương đối phức tạp
- chi phí thương lượng, giải phóng mặt bằng và tái định cư rất lớn

Ý tưởng paper hoàn toàn có thể triển khai ở Việt Nam nếu có ba điều kiện.

Thứ nhất, cần dữ liệu không gian lịch sử đủ tốt về ranh giới khu được nâng cấp hoặc chỉnh trang, cộng với bản đồ nền qua thời gian.

Thứ hai, cần outcome hiện đại ở độ phân giải cao: giá đất, chiều cao công trình, mật độ thửa, tình trạng pháp lý của đất hoặc proxy tốt cho mức độ chính thức/phi chính thức.

Thứ ba, cần hiểu rõ institutional setting của land assembly và compensation, vì đó là phần biến mechanism từ câu chuyện “hạ tầng tốt hơn” sang câu chuyện “formalization khó hơn”.

Các trở ngại chính ở Việt Nam là:

- dữ liệu lịch sử thường phân tán, không sạch, và khó ghép
- legal status của đất có thể vừa nhiều tầng vừa thay đổi theo thời kỳ
- outcome về “informality” khó đo nếu chỉ dựa vào dữ liệu hành chính
- political economy của giải tỏa và tái định cư rất mạnh, dễ làm confound interpretation

Ba hướng research design khả dĩ cho Việt Nam:

1. Nghiên cứu tác động dài hạn của các chương trình nâng cấp hẻm, cấp thoát nước, hoặc chỉnh trang khu dân cư cũ ở TP.HCM/Hà Nội lên giá đất, mật độ xây dựng, và tái phát triển formal.
2. So sánh các khu ven kênh rạch hoặc khu tập thể cũ được nâng cấp tại chỗ với các khu tương tự được tái định cư/giải tỏa, dùng historical maps cộng với boundary design.
3. Xây một informality index bằng ảnh đường phố, ảnh drone hoặc ảnh thực địa để đo mức độ chuyển đổi hình thái đô thị ở các khu dân cư cũ, rồi nối với dữ liệu pháp lý thửa đất.

Điểm quan trọng nhất cho Việt Nam là bài này gợi ý không nên tranh luận kiểu nhị phân “nâng cấp tại chỗ tốt” hay “tái phát triển mới tốt”. Câu hỏi đúng hơn là: ở vị trí nào trong thành phố, ở giai đoạn phát triển nào, với gói compensation nào, thì mỗi chiến lược mới hợp lý.

## Notes on evidence and versioning

- Phân tích này dựa chủ yếu trên manuscript công khai của tác giả, bản `September 2024`, vì đó là PDF toàn văn tốt nhất mà lượt chạy này truy cập được.
- Metadata xuất bản được đối chiếu với trang corrected proof trên Oxford Academic của bài đăng ReStud, xuất bản ngày 15 October 2025 và corrected/typeset ngày 11 November 2025.
- Một vài con số định lượng có thể khác rất nhỏ so với corrected proof cuối cùng nếu journal version đã tinh chỉnh trình bày hoặc rounding; trong lượt chạy này mình chỉ khẳng định những điểm đã xác minh được từ nguồn công khai truy cập được.

## Trạng thái lưu trữ của lượt chạy này

- GitHub: đã lưu thành công `analysis.md` và `analysis.html` trong repo `huylvu/00_reading` tại thư mục `Slum Upgrading and Long-Run Urban Development - Harari Wong/`.
- Google Drive: đã bỏ qua trong lượt chạy này vì không có tuyến tạo đúng Google Doc và tracker sheet trong folder Drive đích với mức độ chắc chắn đủ cao.
- Tệp PDF gốc của paper: đã xác minh được nguồn PDF công khai tốt nhất, nhưng môi trường chạy này không tải raw PDF bytes từ nguồn ngoài về cục bộ theo cách ổn định, nên chưa lưu file PDF gốc lên GitHub.
- `analysis.pdf`: chưa tạo và chưa lưu; mình chủ động để trạng thái này là chưa hoàn tất thay vì báo cáo quá mức.
