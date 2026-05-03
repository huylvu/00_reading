# Digital Distractions with Peer Influence: The Impact of Mobile App Usage on Academic and Labor Market Outcomes

- **Tác giả:** Panle Jia Barwick, Siyu Chen, Chao Fu, Teng Li
- **Journal:** The Quarterly Journal of Economics
- **Năm:** 2026
- **Số / trang:** Volume 141, Issue 1, February 2026, Pages 1-49
- **Ngày agent chạy:** 2026-05-04 (Asia/Saigon)
- **Nguồn bài báo chính:** https://academic.oup.com/qje/article/141/1/1/8292650
- **DOI:** https://doi.org/10.1093/qje/qjaf048
- **PDF tốt nhất đã xác minh:** PDF chính thức từ QJE tại https://academic.oup.com/qje/advance-article-pdf/doi/10.1093/qje/qjaf048/64738934/qjaf048.pdf
- **Nguồn PDF đối chiếu thêm:** NBER Working Paper 33054, revised September 2025, https://www.nber.org/system/files/working_papers/w33054/w33054.pdf
- **Trạng thái lưu trên GitHub:** `analysis.md` và `analysis.html` được lưu trong repo `huylvu/00_reading`, thư mục `Digital Distractions with Peer Influence - Barwick Chen Fu Li/`; `analysis.pdf` chưa được lưu; PDF gốc của paper mới dừng ở mức xác minh nguồn công khai, chưa lưu được file nhị phân vào repo trong lượt chạy này.
- **Trạng thái lưu trên Google Drive:** bỏ qua trong lượt chạy này vì chưa có tuyến tạo Google Doc và tracker đúng folder đích một cách nhất quán.

## Executive Summary

Paper này hỏi một câu rất thời sự nhưng khó làm nghiêm túc: dùng app trên điện thoại trong thời đại smartphone có thực sự làm hỏng tích lũy vốn nhân lực của sinh viên không, và nếu có thì thiệt hại chỉ nằm ở bản thân người dùng hay còn lan sang bạn cùng phòng? Bài trả lời câu hỏi đó bằng một bộ dữ liệu hiếm: ghép hồ sơ hành chính của ba khóa sinh viên tại một trường đại học Trung Quốc với dữ liệu dùng app điện thoại, dữ liệu GPS trong khuôn viên trường, dữ liệu bạn bè trước đại học, và kết quả việc làm lúc tốt nghiệp.

Điểm mạnh nhất của paper là nó không chỉ ước lượng “tự mình dùng app nhiều thì GPA kém hơn” theo kiểu tương quan. Tác giả kết hợp random dorm assignment để xử lý chọn bạn cùng phòng, cú sốc ra mắt game bom tấn `Yuanshen/Genshin Impact`, và chính sách hạn chế game cho người vị thành niên ở Trung Quốc để tạo biến thiên gần ngoại sinh trong mức dùng app. Nhờ vậy, paper vừa ước lượng được tác động nhân quả của app usage lên học tập, sức khỏe thể chất, và lương khởi điểm, vừa tách được peer effect thành hai phần: behavioral peer effect và contextual peer effect.

Kết quả chính rất mạnh. Một độ lệch chuẩn tăng trong app usage của chính sinh viên làm GPA các môn bắt buộc giảm khoảng 36.2% độ lệch chuẩn trong cùng cohort-major và làm lương khởi điểm giảm 2.3%. App usage của roommate còn kéo kết quả xấu đi thêm qua hai kênh: lây hành vi dùng app và phá vỡ môi trường học tập trong phòng. Tổng tác động của roommate app usage lên GPA vượt quá một nửa tác động của own usage. Với labor market outcomes, roommate effect nhỏ hơn nhưng vẫn có ý nghĩa kinh tế.

Đây là bài rất đáng đọc cho applied micro vì nó nối ba văn liệu thường tách rời nhau: digital addiction, peer effects, và human capital formation. Nó cũng đáng đọc cho development vì bối cảnh là một đại học Trung Quốc, dùng dữ liệu hành chính rất giàu, và đưa ra một cách định lượng chi phí vốn nhân lực của digital distraction trong một nền kinh tế đang phát triển nhanh.

## Research Question and Motivation

### Câu hỏi trung tâm

Paper muốn biết:

1. Dùng mobile apps nhiều hơn có làm giảm thành tích học tập, sức khỏe thể chất, và kết quả lao động ban đầu của sinh viên hay không.
2. App usage có tính lây lan giữa peers hay không.
3. Nếu có peer effects, phần nào đến từ hành vi thực tế của peers, phần nào chỉ phản ánh đặc điểm nền của peers.
4. Một chính sách hạn chế game có thể mang lại lợi ích kinh tế lớn đến đâu khi tính cả spillover giữa sinh viên.

### Động lực học thuật

Văn liệu trước về social media hay digital addiction thường gặp ba điểm yếu. Thứ nhất, dữ liệu về usage thật và long-run outcomes rất hiếm. Thứ hai, app usage nội sinh mạnh vì stress, ability, mental health, hay discipline đều có thể cùng ảnh hưởng cả usage lẫn outcomes. Thứ ba, peer effects rất khó nhận dạng do reflection problem kiểu Manski và do peers thường được chọn có chủ đích.

Paper này được đặt đúng vào lỗ hổng đó. Tác giả muốn đi xa hơn những bài chỉ cho thấy correlation giữa smartphone use và outcomes, hoặc chỉ xem một can thiệp ngắn hạn trong lớp học. Họ muốn biết chi phí vốn nhân lực tích lũy của app usage trong nhiều năm đại học là bao nhiêu, và đặc biệt là chi phí xã hội qua peers là bao nhiêu.

### Động lực thực tiễn

Chủ đề này có relevance chính sách rất cao. Từ Trung Quốc đến Mỹ, các chính phủ và trường học đều đang bàn về phone bans, game restrictions, hay quản lý social media cho thanh thiếu niên. Nhưng tranh luận thường đi trước bằng chứng. Paper này cung cấp một cầu nối rất hiếm giữa debate chính sách hiện hành và causal evidence đủ mạnh để nói điều gì đáng lo nhất.

## Main Contribution

Mình thấy paper có bốn đóng góp chính.

### 1. Đóng góp về dữ liệu

Tác giả ghép được:

- hồ sơ tuyển sinh và điểm thi đầu vào CEE
- transcript đại học theo từng học kỳ
- dữ liệu app usage theo tháng ở cấp cá nhân
- dữ liệu vị trí GPS tần suất cao trên campus
- dữ liệu việc làm và lương khởi điểm sau tốt nghiệp
- survey về sức khỏe, stress, hành vi tìm việc, và nhận thức về gaming

Đây là loại data architecture rất hiếm trong economics, nhất là khi đi từ hành vi vi mô rất nhỏ đến labor market outcome sau tốt nghiệp.

### 2. Đóng góp về identification

Paper không dựa vào một nguồn biến thiên duy nhất. Nó chồng nhiều lớp nhận dạng:

- random dorm assignment để tạo peer groups gần ngẫu nhiên
- cú sốc ra mắt `Yuanshen` để tạo tăng usage mạnh hơn ở những người có pre-college usage cao
- chính sách hạn chế game cho minors để tạo giảm usage mạnh hơn ở những người có nhiều bạn pre-college đang dưới 18 tuổi

Thiết kế này cho phép giải quyết đồng thời câu chuyện own causal effect và peer causal effect.

### 3. Đóng góp về peer-effects methodology

Đây là phần mình thấy “đẹp” nhất của bài. Tác giả không dừng ở reduced-form roommate effect mà cố tách:

- **behavioral peer effect:** roommates dùng app nhiều hơn làm mình dùng app nhiều hơn
- **contextual peer effect:** đặc điểm định trước của roommates ảnh hưởng đến outcome của mình ngay cả khi không thông qua hành vi hiện tại của họ

Kết quả cho thấy trong bối cảnh này, behavioral effect mới là phần lớn câu chuyện; contextual effect nhỏ và không có ý nghĩa thống kê. Điều này rất quan trọng cho policy design, vì nếu spillover đi qua hành vi chứ không phải đặc điểm nền, thì can thiệp nhắm vào usage thực tế có thể có social multiplier.

### 4. Đóng góp về policy relevance

Paper đưa ra một back-of-the-envelope policy calculation rất rõ: nếu mở rộng mức trần chơi game 3 giờ mỗi tuần cho nhóm college students, lương khởi điểm có thể tăng khoảng 0.9%. Đây không phải là một bài policy evaluation đầy đủ, nhưng nó chuyển các hệ số hồi quy thành một đại lượng mà người làm chính sách hiểu ngay.

## Identification or Methodology

## Bối cảnh dữ liệu và setting

Bài dùng dữ liệu của 7,479 sinh viên thuộc ba khóa freshman 2018-2020 tại một đại học cỡ vừa, tầm trung ở miền Nam Trung Quốc. Trong số này, 6,430 sinh viên được match thành công với dữ liệu phone usage từ một nhà mạng lớn phủ khoảng 75% dân số trong tỉnh. Phân tích GPA chạy trên student-semester panel, loại học kỳ xuân 2020 vì COVID làm sinh viên rời campus. Phân tích wage tập trung vào hai khóa 2018 và 2019 đã tốt nghiệp năm 2022 và 2023.

Sinh viên trong từng major được chia ngẫu nhiên vào các “class” hành chính, rồi trong từng class-gender cell, trường phân dorm ngẫu nhiên vào các phòng đơn giới tính 4-8 người. Paper cho thấy roommates không tương quan về pre-college usage, CEE, demographics, hay SES trong các cell này, nên random assignment khá thuyết phục.

## Đo lường biến chính

- **Own app usage / roommate app usage:** thời lượng dùng app theo tháng, phân theo total apps, games, game + video, social media.
- **Academic outcomes:** GPA các môn bắt buộc là outcome chính để tránh strategic course selection; ngoài ra có PE grades.
- **Labor outcomes:** lương khởi điểm khi tốt nghiệp, đo nhờ hợp đồng việc làm student-employer-university.
- **Mechanisms:** thời gian ở study hall, dorm, đi học muộn, vắng mặt, sleep duration, late sleep, late wake-up, stress, job-search effort.

## Bước 1: Reduced-form peer effects

Nhờ random roommate assignment, tác giả ước lượng reduced-form effect của pre-determined roommate characteristics lên own outcomes. Đây là bước tạo nền để biết peers matter hay không.

## Bước 2: Behavioral peer effect

Để tách behavioral effect, bài dùng biến thiên từ chính sách game restriction cho minors tương tác với số bạn pre-college dưới 18 tuổi của roommates. Intuition là: nếu roommate có nhiều bạn vị thành niên trước đại học, policy shock làm mạng chơi game xã hội của roommate bị ảnh hưởng mạnh hơn, kéo usage hiện tại của roommate xuống; từ đó mình bị ảnh hưởng gián tiếp qua roommate behavior.

Đây là ý tưởng rất tinh: instrument tác động vào peers nhưng không tác động trực tiếp vào focal student, nên giúp đối diện reflection problem.

## Bước 3: Contextual peer effect

Sau khi có reduced-form peer effect và behavioral peer effect, tác giả “net out” behavioral component để phục hồi contextual effect. Họ giả định:

- linear-in-means peer effects
- homogeneous peer treatment effects

Đây là giả định mạnh nhưng chuẩn trong nhiều mô hình peer-effects applied.

## Own causal effects trên GPA và wages

Để xử lý endogeneity của app usage, bài dùng hai nhóm IV:

1. `Yuanshen shock × pre-college app usage`
2. `Minors’ game restriction policy × số bạn pre-college dưới 18 tuổi`

Ý tưởng là người có pre-college usage cao bị tác động mạnh hơn khi game bom tấn ra mắt; người có nhiều bạn vị thành niên bị tác động mạnh hơn khi gaming restrictions được siết. Với student fixed effects và controls giàu, các cú sốc này được coi là chỉ ảnh hưởng outcomes thông qua current app usage.

### Điểm mạnh của phương pháp

- Kết hợp experimental-style variation và hành vi thực tế, không phải survey self-report đơn thuần.
- Giải quyết tương đối thuyết phục cả own endogeneity lẫn peer endogeneity.
- Có event-study để kiểm tra pre-trends và timing của shocks.
- Dùng required-course GPA làm outcome chính để giảm lo ngại endogenous course choice.

### Điểm dễ bị nghi ngờ

- Exclusion restriction của `Yuanshen` vẫn là giả định mạnh: có thể game bom tấn phản ánh broader zeitgeist thay vì chỉ app usage.
- Các contextual effects được suy ra dưới linearity và homogeneity, nên nếu peer interactions phi tuyến mạnh thì decomposition có thể nhạy cảm.
- Dữ liệu usage chỉ quan sát trên mobile phone, không phải toàn bộ thiết bị số.
- Wage outcome chỉ đo lúc rất sớm sau tốt nghiệp, chưa phải long-run earnings.

## Results and Interpretation

## 1. App usage là contagious

Kết quả behavioral peer effect cho thấy một độ lệch chuẩn tăng trong in-college app usage của roommates làm own usage tăng khoảng 5.8%. Đây là con số không nhỏ vì nó nói rằng peer contagion tồn tại ngay trong một hành vi thường bị nghĩ là “private”.

Điểm đáng chú ý là behavioral effect lớn hơn hẳn contextual effect; contextual effect nhỏ và không có ý nghĩa thống kê. Diễn giải kinh tế ở đây là: điều quan trọng không phải bạn ở cùng người “vốn đã nghiện game” về mặt đặc điểm, mà là bạn thực sự sống cạnh một người đang dùng app nhiều ngay lúc đó.

## 2. Tác động lên GPA rất lớn

Kết quả IV cho thấy:

- tăng 1 standard deviation trong own app usage làm GPA môn bắt buộc giảm khoảng **0.716 điểm**, tương đương **36.2% độ lệch chuẩn** trong within-cohort-major GPA
- tăng 1 standard deviation trong roommate app usage làm GPA của mình giảm trực tiếp khoảng **0.408 điểm**, tương đương **20.6% độ lệch chuẩn**
- sau khi cộng cả kênh contagion, total effect của roommate usage lên GPA là khoảng **0.450 điểm**, tức **22.7% độ lệch chuẩn**

Đây là kết quả rất mạnh. Nó nói rằng externality từ roommate app usage không hề nhỏ; thậm chí lớn hơn một nửa own effect.

## 3. Tác động lên sức khỏe thể chất còn lớn hơn

PE scores giảm mạnh khi own app usage tăng. Một độ lệch chuẩn tăng trong app usage làm PE scores giảm khoảng **2.74 điểm**, gần gấp bốn hiệu ứng trên required GPA. Roommate usage lại không có direct effect rõ lên PE, phù hợp với intuition rằng “noise and distraction in the dorm” phá học bài nhiều hơn phá hoạt động thể chất ngoài trời.

Diễn giải rất hay ở đây là paper tách được hai loại outcome:

- outcome đòi hỏi attention và study environment: GPA bị ảnh hưởng bởi cả own use lẫn roommate use
- outcome thiên về physical activity: PE chủ yếu bị ảnh hưởng bởi own use

## 4. Tác động lên labor market outcomes có ý nghĩa kinh tế

Ở wage regressions:

- doubling total app usage làm wages giảm khoảng **2%** theo IV
- quy đổi ra standard deviation, tăng 1 s.d. own app usage làm lương khởi điểm giảm **2.3%**
- tăng 1 s.d. roommate usage làm wage của mình giảm khoảng **0.9%**
- khi cộng cả indirect contagion channel, total roommate effect lên wages khoảng **1%**

Paper còn cho thấy nếu control cho cumulative GPA thì hiệu ứng của gaming lên wages giảm khoảng một phần ba. Điều đó hàm ý academic performance là một kênh quan trọng, nhưng không phải kênh duy nhất; job-search effort, sleep, stress, hay non-cognitive performance cũng đang đóng vai trò.

## 5. Mechanisms khá nhất quán

Ba nhóm bằng chứng cơ chế khớp với nhau rất đẹp.

### Time allocation

Sau cú sốc `Yuanshen`, sinh viên đến study hall muộn hơn khoảng **18.2 phút** và về dorm sớm hơn khoảng **23.4 phút**. Sau policy restriction, hướng tác động đảo ngược: đến study hall sớm hơn khoảng **17.4 phút** và về dorm muộn hơn khoảng **19.8 phút**. Đồng thời lateness và absences tăng sau shock game và giảm sau shock chính sách.

### Sleep

Tăng 1 s.d. trong nighttime app usage gắn với:

- ngủ ít hơn khoảng **30 phút**
- xác suất ngủ muộn tăng **34 điểm phần trăm**
- xác suất dậy muộn tăng **4.5 điểm phần trăm**

### Surveys

Heavy users:

- báo cáo physical và mental health tệ hơn
- stress cao hơn
- ít có professional certificate hơn
- nộp ít job applications hơn
- kém hài lòng hơn với job offers
- vẫn nhận ra gaming có tính addictive, gợi ý đây là self-control problem chứ không phải ignorance

Theo mình, chuỗi cơ chế này làm paper thuyết phục hơn hẳn các bài chỉ có reduced-form main effects.

## What Is Special or Elegant about the Paper

Có ba điểm làm bài này rất đáng nhớ.

### 1. Tách behavioral và contextual peer effects trong một setting rất thật

Đây là phần methodological “đẹp” nhất. Nhiều bài peer effects nói chung chỉ dừng ở reduced-form hoặc chỉ ước lượng một composite social effect. Bài này cố gắng bóc cấu trúc bên trong của peer spillovers, rồi dùng decomposition đó để nói điều gì policy có thể tác động được.

### 2. Kết nối micro behavior với labor-market outcome

Rất nhiều tranh luận về smartphone addiction dừng ở mental health hay GPA. Bài này nối thẳng sang wages upon graduation. Việc đưa labor outcome vào làm chi phí kinh tế trở nên cụ thể hơn rất nhiều.

### 3. Bài học về “externality của distraction”

Một insight rất hay là digital distraction không chỉ là private self-control failure. Nó tạo ra externality trong shared environments như dorm rooms, classrooms, hay có thể rộng hơn là workplaces. Cách framing này mở rộng chủ đề từ behavioral econ sang policy econ và organizational design.

## Required Background Knowledge

## 1. Peer effects và reflection problem

Trong peer-effects literature, khó khăn lớn là hành vi của tôi ảnh hưởng bạn, đồng thời hành vi của bạn cũng ảnh hưởng tôi. Đây là `reflection problem` của Manski. Nếu không có variation ngoại sinh đi vào peers mà không đi thẳng vào tôi, ta rất khó nói causal direction.

## 2. Behavioral vs contextual peer effects

- **Behavioral/endogenous peer effect:** peers làm thay đổi hành vi hiện tại của tôi.
- **Contextual/exogenous peer effect:** đặc điểm có trước của peers ảnh hưởng outcome của tôi.

Ví dụ, sống cùng người ham học là contextual effect; sống cùng người chơi game to tiếng mỗi tối khiến tôi cũng chơi hoặc học kém đi là behavioral/disruption effect.

## 3. Instrumental variables

IV ở đây dùng khi app usage nội sinh. Một IV tốt phải:

- tương quan mạnh với app usage
- không ảnh hưởng trực tiếp đến GPA hay wages ngoài kênh app usage

Paper dùng hai cú sốc khác nhau để làm việc này, nên câu chuyện mạnh hơn hẳn nếu chỉ có một IV.

## 4. Student fixed effects

Trong panel GPA regressions, student fixed effects hấp thụ mọi yếu tố bất biến theo thời gian ở cấp sinh viên: ability nền, background, personality tương đối bền. Nhờ vậy nhận dạng chủ yếu đến từ biến động usage theo thời gian của cùng một người.

## 5. Shift-share style instrument

`Yuanshen release × pre-college usage` là một dạng intuition gần shift-share: một cú sốc chung đi qua “exposure share” riêng của từng người. Người vốn chơi nhiều trước đại học chịu shock mạnh hơn.

## 6. Why required-course GPA matters

Nếu sinh viên có thể chọn môn dễ hoặc ít tín chỉ hơn khi chơi app nhiều, GPA tổng có thể phản ánh course choice chứ không chỉ effort hay learning. Dùng required-course GPA giúp giảm lo ngại đó.

## Limitations and Open Questions

## Hạn chế chính

### 1. External validity

Đây là một đại học cụ thể ở Trung Quốc, với dorm-based life rất đậm và mức sống tập thể cao. Spillovers qua roommates ở bối cảnh này có thể mạnh hơn nơi sinh viên sống phân tán hơn.

### 2. Exclusion restriction vẫn không thể “chứng minh”

Tác giả làm khá tốt, nhưng cuối cùng các IV vẫn dựa trên giả định. Ví dụ `Yuanshen` có thể đồng thời là cú sốc văn hóa số rộng hơn, không chỉ đơn thuần làm tăng app usage.

### 3. Đo usage trên mobile nhưng không thấy toàn bộ digital ecosystem

Nếu sinh viên chuyển sang PC/console hay device khác, measurement không hoàn hảo. Tác giả có đưa ra bằng chứng giảm bớt lo ngại này, nhưng không loại bỏ hoàn toàn.

### 4. Wage outcome còn sớm

Initial wage sau tốt nghiệp là biến rất có ý nghĩa, nhưng chưa chắc phản ánh full long-run effect. Có thể heavy users catch up later, hoặc ngược lại hiệu ứng còn lớn hơn về lâu dài.

### 5. Survey mechanisms chỉ mang tính suggestive

Phần survey chỉ có khoảng 24% response rate và không dùng IV do hạn chế power. Vì vậy phần cơ chế mềm như stress, job-search effort, self-control nên đọc như bằng chứng bổ sung, không phải smoking gun.

## Câu hỏi mở

1. Social media, video, và game khác nhau như thế nào về cơ chế gây hại.
2. Phone distraction có làm thay đổi sorting vào ngành nghề hay firm types không.
3. Liệu phone restrictions trong đại học có welfare-improving sau khi tính cả autonomy cost và enforcement cost không.
4. Peer multiplier có mạnh hơn trong classroom, workplace, hay online social networks so với dorm rooms không.

## Takeaways for a Researcher

1. Nếu câu hỏi liên quan đến hành vi số, dữ liệu hành chính cộng với digital trace data có thể mở ra loại causal design rất mạnh mà survey không thay thế được.
2. Khi nghiên cứu peer effects, cố gắng tách reduced-form, behavioral, và contextual components sẽ cho policy insight sâu hơn rất nhiều so với chỉ báo cáo một social effect tổng.
3. Những cú sốc tưởng như “công nghệ đời thường” như ra mắt một game bom tấn có thể trở thành quasi-experiment rất giá trị nếu ta hiểu exposure heterogeneity.
4. Outcome tốt không nhất thiết chỉ là outcome gần như GPA; nối thêm tới labor-market outcome làm paper mạnh hơn về economic significance.
5. Mechanism evidence nên đến từ nhiều nguồn khác nhau. Ở đây GPS, sleep proxy, và survey cùng kể một câu chuyện nhất quán nên paper thuyết phục hơn hẳn.
6. Một bài applied micro mạnh thường không chỉ có estimate chính; nó còn phải giải thích externality nằm ở đâu, magnitude lớn đến mức nào, và policy counterfactual nhìn ra sao.

## Vietnam Relevance and Extension

## Paper có liên quan tới Việt Nam không?

Rất liên quan. Việt Nam có ba đặc điểm khiến ý tưởng này đáng khai thác:

- smartphone penetration cao trong giới trẻ
- gaming, short-video, và social media usage rất mạnh ở sinh viên
- đời sống ký túc xá và nhà trọ sinh viên tạo ra môi trường peer spillovers khá giống logic của paper

Nếu đúng là digital distraction làm giảm human capital accumulation và lan sang peers, thì đây là một chủ đề vừa có ý nghĩa giáo dục, vừa có ý nghĩa năng suất lao động dài hạn.

## Có thể triển khai nghiên cứu tương tự ở Việt Nam không?

Có thể, nhưng cần điều kiện dữ liệu và đối tác khá nặng.

### Những gì cần có

- dữ liệu hành chính từ trường đại học: điểm, lớp, ngành, lịch học, tình trạng ký túc xá
- dữ liệu phân phòng ký túc xá hoặc nhà ở đủ gần để xác định peers
- dữ liệu digital trace từ app blocker, campus Wi-Fi, telecom partner, hoặc MDM-style phone logs với consent rõ ràng
- nếu muốn labor outcome: dữ liệu việc làm sau tốt nghiệp hoặc graduate survey chất lượng cao

### Trở ngại chính

- bảo mật dữ liệu và consent sẽ là rào cản số một
- nhiều trường ở Việt Nam không có hệ thống lưu trữ và ghép dữ liệu đủ sạch
- sinh viên ngoài ký túc xá có môi trường peers kém xác định hơn
- data sharing với telecoms gần như là bài toán thể chế, không chỉ là bài toán kỹ thuật

## Có thể “làm mới” ý tưởng cho Việt Nam thế nào?

Mình nghĩ có ít nhất ba hướng tốt.

### 1. Ký túc xá và chất lượng học tập

Nếu một trường có phân phòng ngẫu nhiên trong ký túc xá, ta có thể nghiên cứu:

- roommate phone usage và GPA
- roommate short-video usage và attendance
- sự khác biệt giữa first-year students và final-year students

### 2. Phone restrictions trong lớp hoặc trong campus

Nếu một số khoa hoặc giảng viên áp dụng phone-ban nghiêm hơn các nơi khác, có thể khai thác staggered adoption để đo:

- attendance
- điểm giữa kỳ / cuối kỳ
- stress và sleep

### 3. Digital addiction và labor-market readiness

Ở Việt Nam, outcome rất đáng quan tâm là:

- số lượng đơn xin việc
- xác suất có internship
- mức lương offer đầu tiên
- kỹ năng mềm và discipline được employer đánh giá

### 3 research questions khả thi cho bối cảnh Việt Nam

1. `Random roommate assignment trong ký túc xá có cho thấy peer spillovers của TikTok/game usage lên GPA và attendance của sinh viên năm nhất không?`
2. `Các chính sách cấm điện thoại trong lớp ở đại học hoặc THPT có cải thiện kết quả học tập và sleep quality, đặc biệt ở nhóm heavy users trước can thiệp, hay không?`
3. `Digital distraction trong năm cuối đại học có làm giảm job-search intensity, internship conversion, và lương offer đầu tiên của sinh viên Việt Nam hay không?`

## Why This Paper Was Chosen

Mình chọn paper này vì ba lý do.

1. Đây là paper **top 5 journal** rất mới trong **QJE 2026**, đúng applied micro, lại chạm mạnh sang development qua bối cảnh Trung Quốc và chủ đề tích lũy vốn nhân lực.
2. Thiết kế thực nghiệm rất đáng học: random roommate assignment cộng với hai quasi-experimental shocks và decomposition behavioral/contextual peer effects.
3. Chủ đề vừa mới vừa có policy relevance rất cao, và có cả PDF chính thức lẫn working paper công khai đủ tốt để phân tích chắc tay.

## Storage and Execution Notes

- Trong lượt chạy này, phần bắt buộc trên GitHub được hoàn tất với `analysis.md` và `analysis.html`.
- `analysis.pdf` không được ghi là đã lưu vì chưa có đường đi nhị phân đủ chắc để upload thành công lên repo trong cùng lượt.
- PDF gốc của paper được xác minh chắc từ QJE và NBER, nhưng chưa được lưu lại như file nhị phân trong repo vì giới hạn tải và upload file PDF từ môi trường hiện tại.
- Google Drive được bỏ qua thay vì làm nửa vời.
- Email briefing được gửi dưới dạng email văn bản không đính kèm; thân email là bản đọc chính và sẽ nêu rõ nơi lưu trên GitHub cùng trạng thái không có attachment.
