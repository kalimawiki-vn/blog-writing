---
title: "AI Trong Dược Phẩm: Những Công Cụ Đang Thay Đổi Cuộc Chơi"
date: 2025-07-09T18:54:39+07:00
draft: false
tags: ["AI", "Nghiên cứu dược phẩm", "DeepChem", "RDKit", "ChemBERTa", "SMILES Transformer", "GraphConv", "AutoDock Vina", "Schrödinger Suite", "IBM RXN", "GENTRL", "scape-DB"]
cover:
  image: "https://res.cloudinary.com/dxyptrt7m/image/upload/v1752061702/pzyap2w306huzmtzyair.jpg"
  alt: "AI thiết kế phân tử thuốc mới trong phòng thí nghiệm công nghệ cao"
---

## Giới thiệu

Trong những năm gần đây, trí tuệ nhân tạo (AI) đang dần trở thành một “trợ lý đắc lực” trong ngành nghiên cứu dược phẩm. Nhờ khả năng phân tích nhanh, học hỏi từ dữ liệu khổng lồ và thậm chí tự “sáng tạo” ý tưởng mới, AI đang giúp các nhà khoa học rút ngắn thời gian phát triển thuốc – từ nhiều năm xuống chỉ còn vài tháng.

Từ việc hiểu cấu trúc phân tử, dự đoán tính chất hóa học, đến thiết kế thuốc mới và mô phỏng phản ứng trong cơ thể – AI đang hỗ trợ ở hầu hết mọi giai đoạn của quá trình nghiên cứu. Bài viết này sẽ giới thiệu những công cụ AI nổi bật đang được sử dụng rộng rãi trong lĩnh vực phát triển thuốc, theo cách dễ hiểu và gần gũi nhất với bạn đọc.

## 1. DeepChem & RDKit – Thư viện mã nguồn mở giúp máy tính hiểu phân tử

Trong nghiên cứu phát triển thuốc hiện đại, việc mô phỏng và dự đoán tính chất của phân tử bằng máy tính là bước quan trọng giúp tiết kiệm thời gian và chi phí thử nghiệm. Hai công cụ nổi bật hỗ trợ việc này là **DeepChem** và **RDKit** – đều là thư viện mã nguồn mở, được cộng đồng khoa học sử dụng rộng rãi.

**DeepChem – Giúp AI học về phân tử**

DeepChem là một thư viện phần mềm giúp xây dựng các mô hình trí tuệ nhân tạo để phân tích và dự đoán tính chất hóa học hoặc sinh học của các phân tử. Với sự hỗ trợ của DeepChem, máy tính có thể:

- Dự đoán độ độc, khả năng hấp thu, độ hòa tan của phân tử;

- Phân tích cấu trúc phân tử dưới dạng “đồ thị” (tưởng tượng như một mạng lưới các nguyên tử liên kết với nhau);

- Học từ các bộ dữ liệu nghiên cứu lớn, giúp cải thiện độ chính xác của mô hình.

Nhờ DeepChem, các nhà nghiên cứu có thể nhanh chóng đánh giá một phân tử có tiềm năng trở thành thuốc hay không – mà không cần phải thử nghiệm trong phòng thí nghiệm ngay từ đầu.

**RDKit – Công cụ xử lý “ngôn ngữ hóa học” của máy tính**

RDKit là một công cụ mạnh mẽ giúp máy tính hiểu được cấu trúc hóa học. Nếu ví các phân tử như ngôn ngữ riêng của hóa học, thì RDKit chính là “từ điển” và “công cụ dịch” giúp máy tính đọc hiểu và phân tích ngôn ngữ đó.

Với RDKit, các nhà nghiên cứu có thể:

- Tạo mô hình cấu trúc phân tử từ chuỗi ký hiệu SMILES (dạng ngắn gọn của phân tử);

- Tính toán các đặc tính như trọng lượng phân tử, độ phân cực, khả năng hòa tan, v.v.;

- So sánh và tìm kiếm phân tử tương tự nhau, hỗ trợ trong sàng lọc hợp chất tiềm năng.

**🤝 Sự kết hợp mạnh mẽ**

Trong nhiều dự án nghiên cứu, RDKit thường được dùng để xử lý và “hiểu” dữ liệu phân tử, sau đó DeepChem sẽ áp dụng trí tuệ nhân tạo để phân tích sâu hơn hoặc dự đoán các đặc tính quan trọng. Sự kết hợp này tạo ra một quy trình hiệu quả, từ việc nhập dữ liệu đến ra quyết định, góp phần thúc đẩy nhanh chóng quá trình phát triển thuốc mới.

## 2. ChemBERTa & SMILES Transformer – Khi AI "đọc hiểu" cấu trúc phân tử như ngôn ngữ

Khi con người nhìn vào một chuỗi phân tử, như chuỗi SMILES (một cách viết tắt cấu trúc hóa học), chúng ta có thể khó hình dung nó nói lên điều gì. Nhưng với trí tuệ nhân tạo hiện nay, các mô hình AI hiện đại đã có thể **“đọc hiểu” các chuỗi này như đang đọc một đoạn văn**, từ đó rút ra những thông tin quan trọng về tính chất và khả năng hoạt động của phân tử.

**ChemBERTa – Dạy AI “đọc” phân tử như đọc sách** 

ChemBERTa được xây dựng dựa trên mô hình BERT – một loại trí tuệ nhân tạo nổi tiếng trong xử lý ngôn ngữ tự nhiên, từng được dùng để dịch ngôn ngữ, viết nội dung và trả lời câu hỏi. Thay vì đọc tiếng Anh hay tiếng Việt, **ChemBERTa được “huấn luyện” để đọc các chuỗi phân tử dạng SMILES**.

Khi đã “học” đủ nhiều, ChemBERTa có thể:

- Dự đoán một phân tử có độc hại không;
 
- Hiểu xem phân tử có thể tương tác với protein trong cơ thể ra sao;

- Phân loại các nhóm phân tử theo đặc tính hoạt tính sinh học.

Nói cách khác, ChemBERTa giúp nhà nghiên cứu “giao tiếp” với phân tử thông qua ngôn ngữ máy tính, để khai thác các đặc tính tiềm ẩn bên trong.

**SMILES Transformer – Dịch chuỗi phân tử thành hiểu biết sâu** 

SMILES Transformer cũng là một mô hình AI học từ các chuỗi SMILES, nhưng được thiết kế đặc biệt để **mã hóa thông tin phân tử thành dạng số hóa sâu sắc hơn** – gọi là “embedding”. Các biểu diễn này không chỉ gói gọn thông tin về cấu trúc mà còn cho biết **cách phân tử có thể hoạt động trong môi trường sinh học**.

Mô hình này đặc biệt hữu ích trong các ứng dụng như:

- Thiết kế phân tử mới có cấu trúc tương tự phân tử đã biết;

- Sàng lọc nhanh các hợp chất có tiềm năng dược lý cao;

- Kết hợp với các mô hình AI khác để dự đoán hiệu quả thuốc.

**💡 Tại sao điều này quan trọng?**

Trước đây, để hiểu phân tử hoạt động thế nào, các nhà khoa học phải thử nghiệm trong phòng thí nghiệm – một quá trình tốn thời gian và chi phí. Giờ đây, nhờ các mô hình như ChemBERTa và SMILES Transformer, máy tính có thể “hiểu” phân tử chỉ bằng cách đọc ký hiệu, và từ đó gợi ý cho con người những hướng đi có khả năng thành công cao nhất.

## 3. GraphConv – Khi AI nhìn phân tử như một “bản đồ kết nối”

Trong hóa học, một phân tử không chỉ là tập hợp của các nguyên tử, mà là *mạng lưới kết nối chặt chẽ giữa các nguyên tử và liên kết hóa học*. Để giúp máy tính hiểu được cấu trúc này, các nhà khoa học đã phát triển một phương pháp đặc biệt gọi là *Graph Neural Networks* – mạng thần kinh xử lý dữ liệu dạng đồ thị.

Một trong những mô hình tiêu biểu thuộc loại này là **GraphConv**.

**GraphConv – Dạy AI hiểu phân tử như đọc một sơ đồ**

Hãy tưởng tượng mỗi nguyên tử trong một phân tử là một nút (node), và mỗi liên kết hóa học là một đường nối (edge). Khi đó, cả phân tử sẽ giống như một bản đồ mạng lưới nhỏ. Mô hình **GraphConv được thiết kế để “đọc” những mạng lưới như vậy và rút ra đặc điểm của từng phân tử thông qua cách các nguyên tử kết nối với nhau.**

Với khả năng này, GraphConv có thể giúp:

- Dự đoán độ độc, khả năng tan trong nước, hoặc khả năng tương tác với protein;

- So sánh sự khác biệt giữa hai phân tử dựa trên cấu trúc;

- Tìm ra phân tử có cấu trúc tương đồng với thuốc hiện tại nhưng hiệu quả hơn hoặc ít tác dụng phụ hơn.

**Vì sao GraphConv hiệu quả?**

So với những mô hình truyền thống chỉ dựa trên chuỗi ký hiệu phân tử (như SMILES), GraphConv **khai thác tốt hơn “hình dạng” và “cấu trúc kết nối” của phân tử**, nhờ đó có thể:

- Hiểu được tác động tổng thể của cấu trúc đến tính chất sinh học;

- Nhận biết những chi tiết nhỏ trong cấu trúc có thể làm thay đổi cách thuốc hoạt động.

**🚀 Ứng dụng trong phát triển thuốc**

GraphConv đang được sử dụng rộng rãi trong các công ty công nghệ sinh học để:

- Sàng lọc hàng triệu phân tử chỉ trong vài giờ;

- Tìm ra hợp chất có khả năng gắn kết mạnh với protein đích, giúp phát triển thuốc chính xác hơn;

- Giảm thời gian nghiên cứu từ vài năm xuống còn vài tháng.

GraphConv là một ví dụ điển hình cho việc **máy tính không chỉ “đọc” mà còn “nhìn” được cấu trúc hóa học**, nhờ đó mở ra một cách tiếp cận hoàn toàn mới trong phát triển dược phẩm bằng trí tuệ nhân tạo.

## 4. AutoDock Vina – Giúp máy tính “dự đoán” cách thuốc gắn vào protein

Trong quá trình phát triển thuốc, một trong những câu hỏi quan trọng là: *Liệu phân tử thuốc có gắn đúng vào mục tiêu (protein) trong cơ thể hay không*? Để trả lời điều đó, các nhà khoa học thường phải làm các thí nghiệm phức tạp trong phòng lab.

Tuy nhiên, với sự hỗ trợ của công nghệ mô phỏng bằng máy tính – gọi là **docking phân tử** – chúng ta có thể **dự đoán trước cách thuốc và protein tương tác với nhau**. Một trong những công cụ phổ biến và mạnh mẽ nhất để làm việc này là **AutoDock Vina**.

**AutoDock Vina là gì?**

AutoDock Vina là một phần mềm mã nguồn mở được phát triển để **mô phỏng quá trình một phân tử nhỏ (như thuốc) gắn vào một phân tử lớn hơn (thường là protein)**. Công cụ này sử dụng các thuật toán tối ưu hóa để tìm ra:

- Vị trí phù hợp nhất để phân tử gắn vào protein;

- Cách thức phân tử “xoay, gập, uốn cong” để vừa với vị trí đó;

- Độ mạnh của sự gắn kết (binding affinity) – yếu tố quan trọng trong hiệu quả điều trị.

**Ưu điểm nổi bật**

- **Nhanh chóng và chính xác:** AutoDock Vina có thể xử lý hàng ngàn phân tử trong thời gian ngắn, giúp các nhà nghiên cứu sàng lọc nhiều hợp chất một cách hiệu quả.

- **Dễ sử dụng, phổ biến toàn cầu:** Được sử dụng bởi hàng trăm phòng thí nghiệm và công ty dược trên thế giới.

- **Miễn phí, mã nguồn mở:** Ai cũng có thể tải về, sử dụng và tích hợp vào quy trình nghiên cứu.

**🧪 Ứng dụng trong thực tế**

AutoDock Vina thường được dùng trong giai đoạn tiền lâm sàng để:

- Tìm ra những phân tử có khả năng trở thành thuốc;

- Loại bỏ sớm các hợp chất không tiềm năng, tiết kiệm chi phí thử nghiệm;

- Hiểu rõ cơ chế hoạt động của thuốc ở cấp độ phân tử, từ đó cải tiến thiết kế thuốc.

Với sự trợ giúp của AutoDock Vina, **máy tính có thể đóng vai trò như một “phòng lab ảo”**, giúp các nhà khoa học thử nghiệm ý tưởng nhanh hơn rất nhiều so với cách truyền thống – mở đường cho những loại thuốc mới hiệu quả hơn và ra đời nhanh hơn.

![AI thiết kế các phân tử thuốc mới trong môi trường phòng thí nghiệm](https://res.cloudinary.com/dxyptrt7m/image/upload/v1752063677/rgsywovqyavll4yzjikn.jpg)

## 5. Schrödinger Suite – Bộ công cụ “phòng thí nghiệm ảo” để thiết kế thuốc  

Trong quá trình phát triển thuốc, việc hiểu rõ cách một phân tử tương tác với cơ thể – như *gắn vào protein, di chuyển trong máu, hay gây ra tác dụng phụ* – là cực kỳ quan trọng. Tuy nhiên, nếu làm tất cả các phân tích này bằng phương pháp truyền thống trong phòng thí nghiệm sẽ mất rất nhiều thời gian và chi phí.

Đó là lý do vì sao các công ty dược hiện nay sử dụng **Schrödinger Suite** – một bộ công cụ phần mềm mạnh mẽ giúp **mô phỏng, phân tích và thiết kế thuốc hoàn toàn bằng máy tính**.

**Schrödinger Suite là gì?**

Schrödinger Suite là một tập hợp các phần mềm khoa học tính toán được thiết kế để:

- Mô phỏng cấu trúc phân tử ở cấp độ nguyên tử;

- Dự đoán cách phân tử tương tác với protein trong cơ thể;

- Tính toán các đặc tính quan trọng như độ tan, độ bền, độ gắn kết với mục tiêu sinh học.

Nói cách khác, đây là **một “phòng thí nghiệm ảo” toàn diện**, nơi các nhà nghiên cứu có thể thử nghiệm ý tưởng, điều chỉnh cấu trúc phân tử và đánh giá hiệu quả – mà không cần đến ống nghiệm hay kính hiển vi.

**Các công cụ nổi bật trong Schrödinger Suite**

- **Maestro:** Giao diện chính, cho phép người dùng quan sát và thao tác trên cấu trúc phân tử 3D.

- **Glide:** Mô phỏng quá trình phân tử gắn vào protein – tương tự như công cụ AutoDock Vina, nhưng với độ chính xác rất cao.

- **Desmond:** Mô phỏng động lực học phân tử – tức là phân tử sẽ “chuyển động” trong môi trường ảo như thật, giúp phân tích hành vi của thuốc theo thời gian.

- **QikProp:** Dự đoán nhanh các đặc tính dược động học như độ hấp thu, khả năng vượt qua hàng rào máu não, độc tính,…

**🚀 Ứng dụng thực tiễn**

Schrödinger Suite được sử dụng bởi nhiều công ty dược lớn trên thế giới để:

- Thiết kế các phân tử thuốc mới trước khi tổng hợp thật trong phòng lab;

- Loại bỏ sớm các hợp chất không đạt yêu cầu, giúp tiết kiệm nhiều năm nghiên cứu và hàng triệu đô chi phí;

- Tối ưu hóa cấu trúc phân tử để tăng hiệu quả và giảm tác dụng phụ.

Với Schrödinger Suite, **quá trình phát triển thuốc trở nên nhanh hơn, thông minh hơn và ít rủi ro hơn**. Đây là minh chứng rõ ràng cho việc công nghệ đang giúp rút ngắn khoảng cách từ phòng thí nghiệm đến tay người bệnh.

## 6. IBM RXN for Chemistry – Dự đoán phản ứng hóa học bằng trí tuệ nhân tạo

Trong hóa học, để tạo ra một phân tử mới (như thuốc), các nhà khoa học phải trải qua *quá trình tổng hợp – tức là kết hợp các chất khác nhau theo một chuỗi phản ứng hóa học*. Tuy nhiên, việc thiết kế một chuỗi phản ứng hiệu quả không hề đơn giản, và đôi khi phải thử đi thử lại rất nhiều lần trong phòng thí nghiệm.

Đó là lý do vì sao IBM phát triển **IBM RXN for Chemistry** – một nền tảng sử dụng trí tuệ nhân tạo (AI) để **dự đoán các phản ứng hóa học**, giúp các nhà nghiên cứu rút ngắn đáng kể thời gian và công sức trong quá trình tổng hợp phân tử mới.

**IBM RXN là gì?**

IBM RXN là một công cụ trực tuyến, sử dụng các mô hình học sâu (deep learning) để:

- Dự đoán sản phẩm của một phản ứng hóa học – nếu bạn trộn A với B, công cụ sẽ cho biết sản phẩm C là gì;

- Gợi ý con đường tổng hợp phân tử – nếu bạn muốn tạo ra phân tử X, nó sẽ đề xuất bạn nên bắt đầu từ những chất nào, qua những bước nào;

- Tối ưu hóa quy trình tổng hợp, giúp tiết kiệm thời gian, hóa chất và chi phí.

**IBM RXN Hoạt động như thế nào?**

Công cụ này hoạt động giống như một **“Google Dịch” cho phản ứng hóa học**. Bạn chỉ cần nhập công thức hoặc tên chất đầu vào, AI sẽ “dịch” ra sản phẩm đầu ra hoặc ngược lại. Nó đã **được huấn luyện trên hàng triệu phản ứng thực tế từ các tài liệu khoa học**, nhờ đó có thể đưa ra dự đoán chính xác và hợp lý về mặt hóa học.

**✅ Lợi ích với ngành dược phẩm**

Trong lĩnh vực phát triển thuốc, IBM RXN giúp:

- Thiết kế con đường tổng hợp ngắn gọn và hiệu quả hơn cho các hợp chất tiềm năng;

- Tránh các phản ứng không mong muốn hoặc kém hiệu quả, từ đó tăng tỷ lệ thành công trong tổng hợp thực tế;

- Tiết kiệm thời gian thử nghiệm trong phòng lab, đặc biệt với những phân tử phức tạp.

IBM RXN for Chemistry là ví dụ điển hình cho việc AI không chỉ giúp dự đoán tính chất của phân tử, mà còn hỗ trợ ngay từ bước đầu – **tạo ra phân tử đó một cách thông minh hơn**. Đây là công cụ rất hữu ích cho các nhà hóa học, đặc biệt trong ngành dược phẩm, nơi mà thời gian và độ chính xác là yếu tố then chốt.

## 7. scape-DB – Kho dữ liệu “nền móng” cho trí tuệ nhân tạo trong nghiên cứu thuốc

Trí tuệ nhân tạo (AI) có thể học để dự đoán tính chất phân tử, thiết kế thuốc mới hay mô phỏng phản ứng hóa học – nhưng để làm được điều đó, AI cần được huấn luyện bằng dữ liệu. Giống như con người cần sách vở để học, *AI cũng cần một kho dữ liệu lớn, chất lượng cao để hiểu thế giới hóa học*.

Đó là lý do vì sao các nhà nghiên cứu đã xây dựng **scape-DB** – một cơ sở dữ liệu đồ sộ, được thiết kế chuyên biệt để phục vụ cho việc huấn luyện các mô hình AI trong lĩnh vực dược phẩm và hóa học tính toán.

**scape-DB là gì?**

scape-DB là một **ngân hàng dữ liệu phân tử** chứa hàng triệu phân tử và các thông tin liên quan như:

- Cấu trúc hóa học;

- Tính chất vật lý – hóa học (trọng lượng, độ tan, độ phân cực…);

- Hoạt tính sinh học (phân tử có hiệu quả trên loại bệnh nào, tương tác với protein nào…).

Các dữ liệu này được **chuẩn hóa, sắp xếp và dễ dàng truy cập**, giúp các mô hình AI học nhanh hơn, hiệu quả hơn.

**Tại sao cơ sở dữ liệu lại quan trọng?**

Trong AI, có một nguyên tắc: **“rác vào thì rác ra” (garbage in, garbage out)** – nếu dữ liệu huấn luyện không tốt, mô hình AI dù phức tạp đến đâu cũng sẽ đưa ra kết quả không chính xác. Ngược lại, nếu được huấn luyện bằng dữ liệu phong phú và chất lượng như trong scape-DB, AI có thể:

- Phân biệt được đâu là phân tử tiềm năng, đâu là hợp chất vô dụng;

- Hiểu mối liên hệ giữa cấu trúc và hoạt tính của phân tử;

- Tự học để đưa ra các gợi ý thiết kế thuốc mới.

**🧬 Vai trò của scape-DB trong phát triển thuốc**

Các nhà nghiên cứu AI trong ngành dược thường sử dụng scape-DB như:

- Nguồn dữ liệu chuẩn để huấn luyện các mô hình trí tuệ nhân tạo;

- Nền tảng để thử nghiệm và so sánh độ chính xác của các thuật toán mới;

- Bước đầu tiên để xây dựng quy trình phát triển thuốc thông minh, dựa vào máy tính.

Nói cách khác, scape-DB giống như **kho thư viện hóa học khổng lồ dành cho trí tuệ nhân tạo**, là nền móng vững chắc giúp các mô hình AI “trưởng thành” và hoạt động hiệu quả trong hành trình tìm ra những loại thuốc mới cho nhân loại.

## 8. GENTRL – AI “sáng tạo” phân tử thuốc mới bằng cách học từ thử và sai  

Một trong những bước quan trọng và cũng khó khăn nhất trong phát triển thuốc là *thiết kế ra phân tử hoàn toàn mới* – tức là chưa từng tồn tại trong tự nhiên – nhưng lại có khả năng điều trị bệnh hiệu quả. Đây là công việc thường tốn hàng năm trời thử nghiệm và điều chỉnh trong phòng thí nghiệm.

Tuy nhiên, với công nghệ hiện đại, giờ đây **AI không chỉ phân tích, dự đoán mà còn có thể “sáng tạo” ra phân tử mới**. Một trong những công cụ tiên phong cho khả năng đặc biệt này là **GENTRL**.

**GENTRL là gì?**

GENTRL (Generative Tensorial Reinforcement Learning) là một mô hình trí tuệ nhân tạo được phát triển để:

- Tự động tạo ra các phân tử thuốc mới từ đầu;

- Dựa trên các tiêu chí đặt ra như: an toàn, hiệu quả, khả năng tan trong nước, tương tác tốt với protein mục tiêu,…;

- Tối ưu dần thiết kế thông qua cơ chế học tăng cường – học từ thử và sai.

Nói một cách đơn giản, GENTRL giống như **một nhà phát minh phân tử ảo** – nó tạo ra hàng ngàn ý tưởng, tự đánh giá cái nào tốt, cái nào không, rồi tiếp tục cải tiến những ý tưởng khả thi.

**Cách hoạt động của GENTRL**

- Bắt đầu từ những phân tử mẫu đã biết (thuốc cũ, hợp chất tự nhiên…);

- Tạo ra biến thể mới bằng thuật toán “tưởng tượng” phân tử;

- Đánh giá từng phân tử bằng mô hình AI phụ (ví dụ: đo độ độc, khả năng gắn kết với protein,…);

- Giữ lại các phân tử tốt, loại bỏ những cái kém – giống như quá trình chọn lọc tự nhiên.

Qua nhiều vòng lặp như vậy, GENTRL có thể tạo ra những phân tử độc đáo, chưa từng được thử nghiệm, nhưng đầy tiềm năng.

**🚀 Ứng dụng thực tế**

- GENTRL đã từng được dùng để thiết kế thuốc chống xơ hóa (fibrosis), với kết quả thử nghiệm cho thấy hiệu quả rất hứa hẹn – và tất cả chỉ mất vài tuần, thay vì vài năm như cách truyền thống.

- Công cụ này đang được áp dụng để phát triển nhanh các thuốc mới cho ung thư, bệnh thần kinh, bệnh hiếm,…

Với GENTRL, trí tuệ nhân tạo không còn chỉ là công cụ hỗ trợ – mà trở thành **“đồng sáng tạo”** cùng con người trong hành trình tìm ra những loại thuốc tiên tiến, chính xác và hiệu quả hơn bao giờ hết.

![AI phân tích các cấu trúc phân tử trong nghiên cứu dược phẩm](https://res.cloudinary.com/dxyptrt7m/image/upload/v1752061626/ohxdxh1wbf2ojobuxysh.jpg)

## Kết luận

AI không còn là một công nghệ xa vời, mà đang trở thành trợ thủ đáng tin cậy của các nhà khoa học dược phẩm. Những công cụ như DeepChem, ChemBERTa, AutoDock Vina hay GENTRL đang thay đổi cách con người nghiên cứu, thiết kế và tối ưu hóa thuốc mới – theo hướng nhanh hơn, chính xác hơn và ít tốn kém hơn.

Với sự hỗ trợ của trí tuệ nhân tạo, ngành dược phẩm đang bước vào một kỷ nguyên mới – nơi những ý tưởng điều trị từng được xem là bất khả thi, nay có thể được khám phá và hiện thực hóa bằng tốc độ chưa từng có. Và biết đâu, những loại thuốc tương lai bạn sử dụng, đã từng được tạo ra… nhờ một dòng mã máy tính thông minh.

## 📌 Có thể bạn chưa biét

Để hiểu rõ hơn các công cụ AI trong bài viết, bên dưới là một số khái niệm như:

**🔹 Phân tử & Cấu trúc hóa học**

Một phân tử là tập hợp các nguyên tử liên kết với nhau. Ví dụ: phân tử nước (H₂O) gồm 2 nguyên tử hydro và 1 nguyên tử oxy. Cấu trúc của phân tử ảnh hưởng lớn đến cách nó hoạt động trong cơ thể.

**🔹 SMILES**

SMILES (Simplified Molecular Input Line Entry System) là cách viết tắt cấu trúc phân tử dưới dạng một chuỗi ký tự – giúp máy tính dễ dàng xử lý. Ví dụ, nước được biểu diễn là “O”.

**🔹 Mô hình AI**

Trong bài viết, mô hình AI thường là các chương trình được “huấn luyện” để học từ dữ liệu – chẳng hạn như dự đoán một phân tử có độc hay không, hoặc tự thiết kế ra phân tử mới.

**🔹 Docking phân tử**

Là phương pháp mô phỏng việc một phân tử (ví dụ thuốc) gắn vào một phân tử khác (thường là protein trong cơ thể). Việc này giúp dự đoán khả năng điều trị của thuốc.

**🔹 Mạng thần kinh đồ thị (Graph Neural Network)**

Đây là loại mô hình AI được thiết kế để hiểu các cấu trúc dạng mạng lưới, như phân tử (gồm các nguyên tử và liên kết). Mô hình GraphConv là một ví dụ tiêu biểu.

**🔹 Học tăng cường (Reinforcement Learning)**

Là phương pháp huấn luyện AI bằng cách “thưởng – phạt” sau mỗi lần thử. Mô hình sẽ tự điều chỉnh để ngày càng tốt hơn. GENTRL dùng kỹ thuật này để thiết kế phân tử mới hiệu quả.