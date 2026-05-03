# The Confederate Diaspora

- **Tác giả:** Samuel Bazzi, Andreas Ferrara, Martin Fiszbein, Thomas P. Pearson, Patrick A. Testa
- **Journal:** *The Review of Economic Studies*
- **Năm:** 2026
- **Ngày agent chạy:** 2026-05-03
- **Nguồn bài báo chính:** https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdag027/8653240
- **Nguồn PDF dùng để phân tích sâu:** NBER Working Paper 31331, June 2023, Revised May 2025: https://www.nber.org/system/files/working_papers/w31331/w31331.pdf
- **Ghi chú về phiên bản:** Bài đã xuất hiện trên *The Review of Economic Studies* ngày 13-04-2026 dưới dạng accepted manuscript. Phân tích dưới đây bám chủ yếu vào bản NBER revised May 2025 vì đây là bản PDF toàn văn công khai và gần với bản xuất bản nhất mà lượt chạy này xác minh được.
- **Trạng thái lưu GitHub:** Trong lượt chạy này đã lưu được `analysis.md`; `analysis.html` sẽ được lưu nếu bước tạo file văn bản HTML thành công; `analysis.pdf` chưa được tính là thành công cho tới khi thực sự upload được file PDF hợp lệ; PDF gốc của paper mới xác minh được nguồn công khai, chưa được lưu raw binary vào repo nếu không có bước tải và upload thực sự thành công.
- **Trạng thái Google Drive:** Bỏ qua trong lượt chạy này vì chưa có tuyến tạo Google Doc và tracker đúng folder đích một cách nhất quán.

## Executive Summary

Paper này hỏi một câu rất lớn nhưng được triển khai theo cách cực kỳ cụ thể: khi nào người di cư không chỉ đồng hóa với nơi đến, mà còn mang văn hóa của mình sang và tái định hình chuẩn mực, tổ chức, và thể chế ở nơi đó? Nhóm tác giả dùng làn sóng người da trắng miền Nam rời khỏi vùng Confederacy sau Nội chiến Mỹ để trả lời câu hỏi này.

Lập luận trung tâm là ảnh hưởng của migrant group không chỉ phụ thuộc vào số lượng, mà phụ thuộc vào hai điều kiện: cường độ ý thức hệ của người di cư và mức độ “mềm” của cấu trúc quyền lực ở nơi đến. Trong trường hợp này, Confederate migrants có cả hai: họ mang theo một hệ tư tưởng mạnh gắn với slavery, secession, thất bại quân sự, và resentment hậu chiến; đồng thời họ đến nhiều nơi frontier hoặc các cộng đồng đang định hình thể chế nên có nhiều cửa để chen vào quyền lực.

Về phương pháp, paper kết hợp linked historical Census data, dữ liệu lưu trữ mới về tượng đài, place names, chapter của UDC và KKK, lynching, nghề nghiệp, incarceration, segregation, và đặc biệt là một shift-share IV để nhận dạng ảnh hưởng nhân quả của Confederate diaspora ở cấp county. Kết quả chính cho thấy một nhóm di cư khá nhỏ đã có ảnh hưởng rất lớn lên Confederate memorialization, UDC, KKK, lynchings, segregation, wage gaps, sundown towns, và Black incarceration ngoài miền Nam.

Đây là bài đáng đọc vì nó nối ba mảng văn liệu thường tách rời nhau: migration, culture, và institutions. Điểm hay nhất là paper không chỉ nói “văn hóa quan trọng” mà chỉ ra một logic rất rõ: migrant influence mạnh lên khi migrants có ideological intensity cao, đi vào places có power structure còn malleable, rồi khuếch đại ảnh hưởng qua civil society, neighborhood spillovers, và public authority.

## 1. Research Question and Motivation

### Câu hỏi nghiên cứu trung tâm

Paper hỏi: **khi nào và bằng cách nào người di cư có thể tái định hình văn hóa ở nơi đến thay vì chỉ đồng hóa vào đó?** Trường hợp được nghiên cứu là Confederate diaspora: những người da trắng rời miền Nam Hoa Kỳ sau Nội chiến và mang theo Lost Cause ideology cùng các chuẩn mực racial hierarchy.

### Động lực học thuật

Phần lớn văn liệu về migration nhấn mạnh assimilation. Paper này đảo chiều câu hỏi: có những trường hợp small migrant groups lại thay đổi destination culture một cách rất mạnh. Vậy điều gì khiến chuyện đó xảy ra?

### Động lực thực tiễn

Paper gắn câu hỏi này với một puzzle lịch sử và hiện đại: vì sao tượng đài và biểu tượng Confederate lại lan rộng vượt xa miền Nam; và vì sao racial inequality ngoài miền Nam vẫn có nhiều dấu vết bền bỉ trong labor markets, housing, policing, và incarceration? Paper cho rằng một phần câu trả lời nằm ở dòng di cư hậu Nội chiến.

## 2. Main Contribution

### Đóng góp ý tưởng

Paper đưa ra một framework khá gọn nhưng giàu sức khái quát về migrant influence. Hai điều kiện nền là:

1. **Ideological intensity của migrant group**
2. **Malleability của power structure ở nơi đến**

Ba channel chính là:

1. **Cultural spillovers**
2. **Organizational mobilization**
3. **Institutional leverage**

Điều này làm paper vượt khỏi một case study lịch sử thuần túy; nó trở thành một framework có thể dùng cho các setting khác.

### Đóng góp dữ liệu

Paper ghép nhiều nguồn dữ liệu lịch sử rất ấn tượng:

- linked Census records để theo dõi migrant flows và background
- thông tin về slaveholding households
- dữ liệu về Confederate memorialization và place names
- UDC chapters, KKK chapters, lynchings
- nghề nghiệp và authority positions
- Denver, Indiana, Arizona KKK membership records để soi micro-level transmission
- outcome dài hạn về wage gaps, segregation, sundown towns, incarceration

### Đóng góp thực nghiệm

Paper không dừng ở correlation lịch sử. Nó cố gắng nhận dạng causal effect của Confederate diaspora bằng shift-share IV ở cấp county, rồi bổ sung một loạt heterogeneity và micro evidence để kể một câu chuyện cơ chế khá chặt.

### Vì sao quan trọng trong applied micro / development

Tuy bối cảnh là economic history của Mỹ, paper rất “applied micro” ở tinh thần: câu hỏi lớn, dữ liệu giàu, thiết kế nhận dạng rõ, cơ chế được bóc tách, và outcome có ý nghĩa policy lẫn welfare. Nó cũng gần development economics ở chỗ nhấn mạnh nation-building, elite capture, path dependence, và sự tương tác giữa culture với institutions trong quá trình hình thành bất bình đẳng dài hạn.

## 3. Identification or Methodology

### Framework khái niệm

Paper bắt đầu bằng một framework về migrant influence. Trực giác là thế này:

- không phải migrant nào cũng có ảnh hưởng lớn
- ảnh hưởng mạnh hơn khi migrants có ideology rõ và intense
- ảnh hưởng dễ xảy ra hơn ở nơi đến mà cấu trúc quyền lực chưa “đóng”
- để biến presence thành lasting impact, migrants cần các channel truyền ảnh hưởng như tổ chức, lan tỏa xã hội, và chiếm lĩnh vị trí quyền lực

Đây là framework rất hữu ích vì nó làm cho phần empirical có logic rõ thay vì chỉ là một collection of facts.

### Dữ liệu và đo lường treatment

Treatment chính là tỷ trọng Confederate diaspora trong county ngoài miền Nam vào khoảng 1900. Paper dùng linked records để ước lượng ai rời vùng Confederacy, họ đi đâu, background của họ là gì, và nhóm nào có liên hệ trực tiếp với slaveholding.

### Outcome chính

Ở giai đoạn đầu, paper đo “Confederate culture” qua:

- memorials, place names, street names gắn với Confederate leaders
- UDC chapters
- KKK chapters
- Black lynchings

Paper còn xây một **Confederate Culture Index (CCI)** để gom các outcome văn hóa - tổ chức - bạo lực này lại.

Ở giai đoạn dài hạn, outcome gồm:

- Black-white wage gaps
- residential segregation
- sundown towns / Black depopulation
- Black incarceration

### Chiến lược nhận dạng

Phần cốt lõi là **shift-share IV (SSIV)**. Ý tưởng là kết hợp:

- **share:** historical migrant networks từ miền Nam tới từng county ngoài miền Nam ở giai đoạn đầu
- **shift:** predicted outmigration flows từ các origin counties miền Nam trong giai đoạn 1870-1900

Sau đó, paper dùng variation này để tách ảnh hưởng riêng của Confederate diaspora khỏi việc county nào vốn đã có nhiều Southern-born whites hay vốn hấp dẫn migrants nói chung.

### Trực giác nhận dạng

Nếu một county ngoài miền Nam có historical links mạnh hơn với những vùng miền Nam sau chiến tranh có outmigration lớn, county đó sẽ nhận nhiều Confederate migrants hơn vì chain migration. Miễn là conditional on controls, variation này không chỉ phản ánh sẵn một “taste for racism” ở destination, thì ta có thể dùng nó để nhận dạng ảnh hưởng của migrant inflow.

### Điểm mạnh

- Dữ liệu lịch sử cực giàu giúp định nghĩa treatment không quá thô.
- SSIV phù hợp với bối cảnh historical migration.
- Paper làm rất tốt phần mechanism và heterogeneity, nên câu chuyện không chỉ dựa vào one-shot IV coefficient.
- Có micro evidence rất hay từ KKK membership và occupational sorting.

### Điểm dễ bị nghi ngờ

- Shift-share designs luôn nhạy với concern rằng shares có thể phản ánh unobserved destination affinity.
- “Confederate culture” là latent object, nên mọi proxy như memorials, KKK, lynchings đều có noise riêng.
- Một số bằng chứng cơ chế, nhất là authority channel, mang tính mô tả nhiều hơn là causal.
- Working paper cho thấy nhóm tác giả rất ý thức các lo ngại này và làm nhiều robustness checks, nhưng đây vẫn là loại paper mà người đọc nên giữ cảnh giác với endogenous sorting.

## 4. Results and Interpretation

### Kết quả chính về ảnh hưởng văn hóa trực tiếp

Paper cho thấy Confederate diaspora có causal effect dương lên các biểu hiện vật chất và tổ chức của Confederate culture ngoài miền Nam. Theo phần introduction của bản NBER revised May 2025:

- Confederate migrants chỉ chiếm khoảng **2.2% dân số** ở các destination counties năm 1900
- nhưng tăng diaspora từ 0 lên mức trung bình làm xác suất có **KKK activity** tăng khoảng **8 điểm phần trăm**, so với mean khoảng 35%
- tác động lên **post-1900 lynchings** còn nổi bật hơn: tăng khoảng **4 điểm phần trăm**, so với mean khoảng 5%

Điểm kinh tế ở đây là: một nhóm nhỏ nhưng ideologically intense có thể tạo externality văn hóa cực lớn nếu đi vào đúng institutional environment.

### Heterogeneity theo ideological intensity

Paper cho thấy migrant influence mạnh hơn khi migrants đến từ:

- **Deep South** hơn là Upper South
- nơi gắn sâu hơn với **slavery**
- nơi chịu **war destruction** nặng hơn
- nơi có **Reconstruction / Union occupation** mạnh hơn

Đây là phần rất quan trọng vì nó giúp giải thích mechanism: không phải “Southern migrants” nói chung, mà là những migrants mang grievance và ideology mạnh nhất mới là động cơ chính.

### Vai trò của former slaveholders

Former slaveholders chỉ là thiểu số trong diaspora, nhưng lại đặc biệt quan trọng. Paper cho thấy họ overrepresented trong các public-facing authority positions và có vai trò lớn trong việc đẩy Confederate culture vào local institutions. Đây là chỗ paper chạm rất mạnh vào vấn đề elite capture.

### Vai trò của destination conditions

Paper cho thấy ảnh hưởng lớn hơn ở:

- frontier communities
- nơi population density thấp hơn
- nơi Union presence yếu hơn
- nơi transport links yếu hơn
- nơi local population kém cohesive hơn

Diễn giải rất đẹp: migrants dễ định hình culture hơn khi đến nơi “state and society are still being assembled”.

### Organizational mobilization và spillovers

Một phần rất hay là paper không dừng ở county-level outcomes mà đi vào **KKK membership microdata**.

Trong Denver metro area:

- white men sinh ở miền Nam có xác suất là KKK member cao hơn non-Southern whites
- second-generation men có bố hoặc mẹ gốc miền Nam cũng có xác suất cao hơn
- non-Southern whites ở cạnh hàng xóm thuộc first- hoặc second-generation diaspora có xác suất vào KKK cao hơn khoảng **2 điểm phần trăm**, tương đương khoảng **8%**
- tăng 1 điểm phần trăm diaspora share trong enumeration district đi kèm tăng khoảng **0.5 đến 0.8 điểm phần trăm** KKK membership ở non-Southern whites

Phần này không phải bằng chứng hoàn hảo về one-way transmission, nhưng nó cho thấy một kênh lan truyền xã hội rất thuyết phục.

### Institutional leverage

Paper cho thấy cả first-generation lẫn second-generation diaspora đều overrepresented trong governance, civil society, politics, và local media. Chẳng hạn, second-generation migrants được mô tả là:

- cao hơn **47%** trong governance
- **17%** trong civil society
- **7%** trong political office
- **20%** trong newspaper leadership

Quan trọng hơn, khi county có Confederate migrants overrepresented trong authority occupations, tác động lên Confederate Culture Index lớn hơn rõ rệt. Paper khá cẩn trọng: đây là bằng chứng mô tả phù hợp với institutional leverage channel, chứ không khẳng định causal as cleanly as baseline SSIV.

### Hệ quả dài hạn đối với bất bình đẳng chủng tộc

Phần cuối là nơi paper chuyển từ culture sang welfare-relevant outcomes:

- tăng 1 điểm phần trăm diaspora share gắn với **giảm 2.6%** thu nhập tương đối của Black workers
- tăng **5%** residential segregation năm 1940
- tăng **20%** số sundown towns trong county
- tăng **2.6 điểm phần trăm** xác suất một non-Southern town từng có ít nhất 25 cư dân Black năm 1870 trở thành town có **zero Black residents** sau 1900
- tăng **45%** Black incarceration rate năm 1920

Đây là kết quả rất mạnh, vì nó cho thấy cultural transmission không chỉ dừng ở symbols hay memory politics mà biến thành exclusion kinh tế - xã hội thật sự.

## 5. What Is Special or Elegant About the Paper

Điểm đẹp nhất của paper là nó không xem culture như một residual khó nắm bắt. Tác giả biến nó thành một object nghiên cứu có cấu trúc:

- ai là carriers của culture
- khi nào culture lan mạnh
- lan qua channel nào
- và cuối cùng nó để lại hệ quả kinh tế nào

Paper cũng rất đẹp ở chỗ kết hợp macro historical narrative với micro evidence. Nhiều paper economic history dừng ở county maps và regression tables; paper này đi thêm một tầng nữa bằng KKK membership records, occupational sorting, intergenerational transmission, và neighborhood exposure.

Một điểm rất đáng học là cách paper nối **symbolic outcomes** với **material outcomes**. Nó không xem tượng đài, place names, KKK chapters, lynching, wage gaps, segregation, và incarceration là những thứ rời nhau; nó xem chúng như các biểu hiện khác nhau của cùng một cultural-institutional equilibrium.

## 6. Required Background Knowledge

### Shift-share IV

Người đọc nên nắm intuition của shift-share designs: dùng pre-existing settlement shares kết hợp shocks ở origin để tạo ra variation “quasi-exogenous” trong migrant inflows ở destination. Quan trọng là hiểu cả sức mạnh lẫn tranh cãi của design này, đặc biệt về sorting và identifying assumptions.

### Culture and institutions

Paper đứng trên văn liệu nói rằng culture và institutions cùng tiến hóa. Ở đây culture không chỉ là preference riêng tư; nó được củng cố qua organizations, public authority, schooling, policing, local media, và civic rituals.

### Lost Cause ideology

Đây là narrative hậu Nội chiến cố tái diễn giải Confederacy theo hướng “honorable,” giảm nhẹ vai trò của slavery và tôn vinh trật tự da trắng. Không hiểu điều này thì khó thấy vì sao memorials, UDC, hay KKK lại là outcome có ý nghĩa.

### Elite capture và state formation

Một ý nền rất quan trọng là places với institutions còn non trẻ dễ bị nhóm có organization và ideology mạnh capture. Đây là logic rất quen trong development economics, chỉ khác là setting ở đây là frontier America.

### Intergenerational transmission

Paper dựa nhiều vào trực giác rằng values, identity, và political norms có thể truyền trong gia đình và neighborhood chứ không chỉ qua thị trường hay formal schooling.

## 7. Limitations and Open Questions

### Hạn chế 1: đo lường culture vẫn không hoàn hảo

CCI và các proxy như memorials, KKK, UDC, lynchings rất giàu thông tin, nhưng culture luôn là khái niệm rộng hơn những thứ đo được. Một phần “Confederate culture” chắc chắn vẫn nằm ngoài dữ liệu.

### Hạn chế 2: authority channel chưa clean như baseline causal design

Paper khá trung thực rằng occupational overrepresentation evidence chủ yếu là descriptive. Nó rất thuyết phục về mặt narrative, nhưng chưa phải causal evidence gọn như main SSIV coefficients.

### Hạn chế 3: nguy cơ sorting không bao giờ biến mất hoàn toàn

Dù paper làm nhiều robustness checks, historical migration vẫn khiến người đọc phải hỏi: liệu những destination nào đón Confederate migrants nhiều hơn có vốn đã có social conditions thuận lợi cho racial exclusion? Bài thuyết phục rằng đây không phải toàn bộ câu chuyện, nhưng concern này không thể bị xóa hoàn toàn.

### Hạn chế 4: external validity của framework

Framework có vẻ portable, nhưng mức độ nó áp dụng tốt tới các migrant groups khác phụ thuộc vào bối cảnh. Không phải mọi migrant group có ideology mạnh đều gặp destinations đủ malleable hay có access tới power.

### Câu hỏi mở

- Có thể tách rõ hơn relative importance của spillovers, organizations, và institutions không?
- Khi nào migrant influence làm society tốt hơn chứ không xấu hơn?
- Vai trò của countervailing organizations ở destination là gì?
- So với later Southern white migration hay Black Great Migration, cái gì là similar mechanism và cái gì là fundamentally different?

## 8. Takeaways for a Researcher

1. Một paper mạnh thường không chỉ có “interesting setting” mà còn có **portable framework**. Đây là điều paper này làm rất tốt.
2. Nếu nghiên cứu culture, đừng chỉ dừng ở attitudes survey hoặc one-shot symbols; hãy nối culture với **organizations, institutions, và economic outcomes**.
3. Heterogeneity không chỉ để “làm đẹp” bảng kết quả. Ở đây heterogeneity theo Deep South, slavery exposure, frontier conditions chính là phần giúp mechanism trở nên đáng tin.
4. Historical microdata có thể cực mạnh khi ghép được nhiều nguồn và khi câu hỏi nghiên cứu đủ sắc.
5. Một chiến lược nhận dạng tốt thường cần được “bồi” bằng qualitative-historical logic và micro evidence về channels, thay vì chỉ sống bằng coefficient chính.
6. Cần phân biệt rõ đâu là **causal core** và đâu là **suggestive mechanism evidence**. Paper này là ví dụ tốt về sự kỷ luật đó.

## 9. Vietnam Relevance and Extension

### Liên quan tới Việt Nam ở mức ý tưởng

Bối cảnh Việt Nam dĩ nhiên rất khác, nhưng logic của paper lại khá gần với nhiều câu hỏi ở Việt Nam:

- khi nào migrant groups mang theo norms và networks rồi tái định hình nơi đến
- vai trò của local elites trong việc khuếch đại hoặc chặn những norms đó
- sự tương tác giữa frontier / đô thị hóa nhanh / tái định cư với institutional formation

### Có thể triển khai ở Việt Nam không?

Có thể, nhưng sẽ khó hơn về dữ liệu. Để làm một paper “theo tinh thần” này ở Việt Nam cần ít nhất:

- dữ liệu di cư đủ chi tiết theo origin-destination
- dữ liệu lịch sử hoặc hành chính về local leadership, tổ chức xã hội, trường học, công an, mặt trận, hội đoàn, hay các thiết chế tương tự
- outcome phản ánh norms hoặc exclusion theo địa bàn
- một shock hoặc nguồn quasi-exogenous variation đủ thuyết phục để tách migrant influence khỏi sorting thuần túy

### Trở ngại lớn

- linked historical microdata ở Việt Nam khó hơn nhiều
- đo “culture” ở cấp địa phương khó và dễ gây tranh cãi
- nhiều outcome nhạy cảm về chính trị hoặc không sẵn dữ liệu công khai
- local institutions ở Việt Nam có cấu trúc tập trung hơn nên logic “malleable frontier power structure” có thể vận hành khác

### Hướng mở rộng hợp lý cho Việt Nam

1. **Di cư tái định cư và chuẩn mực xã hội tại nơi đến:** các chương trình tái định cư, kinh tế mới, hoặc đô thị hóa mạnh có làm thay đổi social norms, trust, gender norms, hay local political participation không?
2. **Elite migrants và institutional influence:** khi nhóm đến có human capital, political ties, hoặc organizational capacity cao hơn, họ có chiếm lĩnh thiết chế địa phương và tái định hình phân bổ cơ hội không?
3. **Intergenerational transmission tại các khu công nghiệp và đô thị mới:** migrant parents có truyền khác biệt về aspiration, school choice, civic behavior, hay network formation sang thế hệ con và hàng xóm bản địa không?

### Một vài research question cụ thể

1. Liệu các đợt di dân kinh tế mới hoặc tái định cư thủy điện ở Việt Nam có để lại dấu ấn lâu dài lên school governance, land conflict, hay ethnic relations ở nơi đến không?
2. Liệu lao động nhập cư quy mô lớn vào các tỉnh công nghiệp có làm thay đổi local norms về nữ lao động, hôn nhân, hay đầu tư giáo dục không?
3. Trong các huyện đang đô thị hóa nhanh, liệu nhóm nhập cư có network với bộ máy hành chính hay doanh nghiệp địa phương có ảnh hưởng lớn hơn tới cách hình thành thiết chế phi chính thức không?

## 10. Vì Sao Bài Này Đáng Đọc

Đây là một paper rất “đã” cho người làm applied micro vì nó cho thấy cách biến một câu hỏi lớn, hơi trừu tượng, thành một design thực nghiệm chặt chẽ. Nó cũng là bài rất tốt cho người quan tâm development và political economy vì nó nhấn mạnh rằng inequality dài hạn không chỉ đi qua luật lệ hay tài sản, mà còn đi qua migration, culture, elite organization, và institutional capture.

Nếu đọc kỹ, người nghiên cứu học được không chỉ một kết quả lịch sử quan trọng, mà còn học được cách:

- xây framework trước khi chạy regressions
- dùng dữ liệu lịch sử để kể một causal story giàu cơ chế
- nối symbolic politics với material inequality
- và giữ kỷ luật trong việc phân biệt evidence mạnh với evidence gợi ý

## 11. Notes on Verification and Limits

- **Điều đã xác minh chắc:** tiêu đề, tác giả, journal, DOI, ngày xuất hiện trên *The Review of Economic Studies*, và sự tồn tại của public full-text PDF gần nhất ở NBER revised May 2025.
- **Điều suy ra hợp lý từ nguồn công khai:** các con số và diễn giải trong briefing bám theo bản full-text NBER revised May 2025, vốn rất gần accepted manuscript nhưng vẫn có thể khác nhẹ ở câu chữ hoặc đánh số bảng/phần so với bản journal sau cùng.
- **Giới hạn của lượt chạy:** môi trường hiện tại xác minh và đọc được PDF qua web, nhưng không tải raw binary PDF từ nguồn ngoài vào shell một cách ổn định. Vì vậy, nếu cuối cùng không lưu được PDF gốc lên GitHub thì trạng thái đúng phải hiểu là **đã xác minh nguồn PDF**, chưa phải **đã lưu raw PDF gốc**.
