# Danh sách thêm 20 bài báo uy tín khác phù hợp với ngành Software Engineering

> Bộ này **không trùng** với danh sách 20 bài trước.  
> Mục tiêu: dùng cho sinh viên Software Engineering đọc, làm literature matrix, chọn baseline, xây prototype, thiết kế experiment và phát triển thành đề tài nghiên cứu.  
> Abstract tiếng Việt bên dưới là bản tóm tắt/diễn giải, không phải bản dịch nguyên văn toàn bộ abstract.

---

## 1. CodeBERT: A Pre-Trained Model for Programming and Natural Languages

- **Link bài báo:** https://aclanthology.org/2020.findings-emnlp.139/  
- **Link arXiv:** https://arxiv.org/abs/2002.08155  
- **Năm:** 2020.
- **Tác giả:** Zhangyin Feng, Daya Guo, Duyu Tang, Nan Duan, Xiaocheng Feng, Ming Gong, Linjun Shou, Bing Qin, Ting Liu, Daxin Jiang, Ming Zhou.
- **Venue/Nguồn:** Findings of EMNLP 2020.
- **Loại bài:** Model paper.
- **Lĩnh vực:** Code intelligence, code search, code summarization.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** CodeBERT, code representation, code search, documentation generation, NL-PL.
- **Metadata đáng chú ý:**
  - Mô hình tiền huấn luyện song phương giữa ngôn ngữ tự nhiên và ngôn ngữ lập trình.
  - Hỗ trợ các tác vụ như natural language code search và code documentation generation.
  - Có thể dùng làm baseline cho bài toán truy xuất code, sinh mô tả code hoặc phân loại code.
- **Abstract tiếng Việt:**  
  Bài báo giới thiệu CodeBERT, một mô hình tiền huấn luyện cho cả ngôn ngữ tự nhiên và mã nguồn. Mục tiêu là học biểu diễn chung giữa mô tả bằng tiếng người và đoạn code, từ đó hỗ trợ các tác vụ như tìm kiếm code theo mô tả, sinh tài liệu cho code và hiểu quan hệ giữa comment và chương trình. Đây là bài nền rất tốt cho sinh viên muốn làm các đề tài về code search, code documentation hoặc code understanding.

---

## 2. GraphCodeBERT: Pre-training Code Representations with Data Flow

- **Link bài báo:** https://arxiv.org/abs/2009.08366  
- **Năm:** 2020.
- **Tác giả:** Daya Guo, Shuo Ren, Shuai Lu, Zhangyin Feng, Duyu Tang, Shujie Liu, Long Zhou, Nan Duan, Alexey Svyatkovskiy, Shengyu Fu, Michele Tufano, Shao Kun Deng, Colin Clement, Dawn Drain, Neel Sundaresan, Jian Yin, Daxin Jiang, Ming Zhou.
- **Venue/Nguồn:** arXiv; thường được dùng rộng rãi trong nghiên cứu code intelligence.
- **Loại bài:** Model paper.
- **Lĩnh vực:** Code representation learning.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** GraphCodeBERT, data flow, code representation, code search, clone detection, code refinement.
- **Metadata đáng chú ý:**
  - Mở rộng CodeBERT bằng cách đưa thông tin data flow vào pre-training.
  - Đánh giá trên code search, clone detection, code translation và code refinement.
  - Phù hợp làm baseline mạnh hơn CodeBERT trong các bài toán hiểu code.
- **Abstract tiếng Việt:**  
  Bài báo cho rằng code không nên chỉ được xem như chuỗi token, vì cấu trúc ngữ nghĩa của code rất quan trọng. GraphCodeBERT đưa data flow vào quá trình học biểu diễn, giúp mô hình hiểu biến nào sinh ra giá trị nào và quan hệ giữa các biến trong chương trình. Đây là hướng quan trọng cho sinh viên muốn nghiên cứu code understanding, defect detection hoặc code repair có khai thác cấu trúc chương trình.

---

## 3. UniXcoder: Unified Cross-Modal Pre-training for Code Representation

- **Link bài báo:** https://arxiv.org/abs/2203.03850  
- **Link ACL:** https://aclanthology.org/2022.acl-long.499/  
- **Năm:** 2022.
- **Tác giả:** Daya Guo, Shuai Lu, Nan Duan, Yanlin Wang, Ming Zhou, Jian Yin.
- **Venue/Nguồn:** ACL 2022.
- **Loại bài:** Model paper.
- **Lĩnh vực:** Code representation, code understanding, code generation.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** UniXcoder, cross-modal pre-training, code representation, AST, code comment.
- **Metadata đáng chú ý:**
  - Hỗ trợ cả tác vụ hiểu code và sinh code.
  - Tận dụng code, comment và AST.
  - Đánh giá trên nhiều tác vụ và dataset code-related.
- **Abstract tiếng Việt:**  
  UniXcoder là mô hình tiền huấn luyện thống nhất cho các tác vụ liên quan đến code, bao gồm cả hiểu và sinh code. Bài báo đề xuất cách điều khiển attention để mô hình có thể hoạt động theo nhiều chế độ khác nhau, đồng thời khai thác thông tin đa phương thức như comment và AST. Bài phù hợp cho nhóm sinh viên muốn so sánh các mô hình code representation hoặc xây hệ thống code search/code generation nâng cao.

---

## 4. CodeXGLUE: A Machine Learning Benchmark Dataset for Code Understanding and Generation

- **Link bài báo:** https://arxiv.org/abs/2102.04664  
- **Link Microsoft Research:** https://www.microsoft.com/en-us/research/publication/codexglue-a-machine-learning-benchmark-dataset-for-code-understanding-and-generation/  
- **Năm:** 2021.
- **Tác giả:** Shuai Lu, Daya Guo, Shuo Ren, Junjie Huang, Alexey Svyatkovskiy, Ambrosio Blanco, Colin Clement, Dawn Drain, Daxin Jiang, Duyu Tang, Ge Li, Lidong Zhou, Linjun Shou, Long Zhou, Michele Tufano, Ming Gong, Ming Zhou, Nan Duan, Neel Sundaresan, Shao Kun Deng, Shengyu Fu, Shujie Liu.
- **Venue/Nguồn:** arXiv / Microsoft Research.
- **Loại bài:** Benchmark paper.
- **Lĩnh vực:** Code understanding and generation benchmark.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** CodeXGLUE, benchmark, code intelligence, code understanding, code generation.
- **Metadata đáng chú ý:**
  - Gồm 10 tác vụ trên 14 dataset.
  - Có baseline theo kiểu BERT-style, GPT-style và Encoder-Decoder.
  - Phù hợp để sinh viên chọn dataset và metric có sẵn.
- **Abstract tiếng Việt:**  
  CodeXGLUE là benchmark lớn cho các bài toán hiểu và sinh code. Bài báo cung cấp tập hợp nhiều tác vụ như clone detection, defect detection, code search, code summarization, code generation và code translation. Đây là tài liệu rất phù hợp cho sinh viên vì có dataset, baseline và metric rõ ràng, giúp chuyển project thành nghiên cứu thực nghiệm.

---

## 5. CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models for Code Understanding and Generation

- **Link bài báo:** https://arxiv.org/abs/2109.00859  
- **Link ACL:** https://aclanthology.org/2021.emnlp-main.685/  
- **Năm:** 2021.
- **Tác giả:** Yue Wang, Weishi Wang, Shafiq Joty, Steven C. H. Hoi.
- **Venue/Nguồn:** EMNLP 2021.
- **Loại bài:** Model paper.
- **Lĩnh vực:** Code understanding, code generation.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** CodeT5, identifier-aware, encoder-decoder, code summarization, code generation.
- **Metadata đáng chú ý:**
  - Sử dụng kiến trúc encoder-decoder.
  - Có nhiệm vụ pre-training nhận diện và khôi phục identifier.
  - Đánh giá trên nhiều tác vụ hiểu và sinh code.
- **Abstract tiếng Việt:**  
  Bài báo giới thiệu CodeT5, mô hình encoder-decoder thống nhất cho cả code understanding và code generation. Điểm quan trọng là mô hình chú ý đến identifier do lập trình viên đặt, vì tên biến, tên hàm và tên lớp chứa nhiều thông tin ngữ nghĩa. Bài này phù hợp để sinh viên làm đề tài sinh mô tả code, sinh code từ mô tả, phát hiện defect hoặc clone detection.

---

## 6. CodeT5+: Open Code Large Language Models for Code Understanding and Generation

- **Link bài báo:** https://arxiv.org/abs/2305.07922  
- **Năm:** 2023.
- **Tác giả:** Yue Wang, Hung Le, Akhilesh Deepak Gotmare, Nghi D. Q. Bui, Junnan Li, Steven C. H. Hoi.
- **Venue/Nguồn:** EMNLP 2023.
- **Loại bài:** Code LLM paper.
- **Lĩnh vực:** Open code LLM, code understanding, code generation.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** CodeT5+, code LLM, instruction tuning, code generation, code retrieval.
- **Metadata đáng chú ý:**
  - Đánh giá trên hơn 20 benchmark code-related.
  - Có các thiết lập zero-shot, fine-tuning và instruction-tuning.
  - Phù hợp làm model nền cho nhóm nghiên cứu code generation hoặc code search.
- **Abstract tiếng Việt:**  
  CodeT5+ mở rộng CodeT5 theo hướng mô hình ngôn ngữ lớn cho code, có thể kết hợp linh hoạt các module encoder-decoder và nhiều mục tiêu huấn luyện. Bài báo hướng đến việc cải thiện nhiều tác vụ khác nhau như code generation, code completion, text-to-code retrieval và instruction-based coding. Đây là bài phù hợp cho nhóm mạnh muốn làm thực nghiệm với open code LLM.

---

## 7. StarCoder: May the Source Be With You!

- **Link bài báo:** https://arxiv.org/abs/2305.06161  
- **Năm:** 2023.
- **Tác giả:** Raymond Li, Loubna Ben Allal, Yangtian Zi, Niklas Muennighoff, Denis Kocetkov, Chenghao Mou, Marc Marone, Christopher Akiki, Jia Li, Jenny Chim, Qian Liu, và cộng sự BigCode.
- **Venue/Nguồn:** Transactions on Machine Learning Research, 2023.
- **Loại bài:** Open code LLM paper.
- **Lĩnh vực:** Code generation, responsible open code models.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** StarCoder, BigCode, code LLM, The Stack, HumanEval.
- **Metadata đáng chú ý:**
  - Mô hình 15.5B tham số.
  - Huấn luyện trên The Stack với dữ liệu GitHub có giấy phép cho phép.
  - Có thảo luận về PII redaction, license và responsible release.
- **Abstract tiếng Việt:**  
  Bài báo giới thiệu StarCoder và StarCoderBase, các mô hình ngôn ngữ lớn cho code do cộng đồng BigCode phát triển. Ngoài hiệu năng sinh code, bài nhấn mạnh khía cạnh phát hành có trách nhiệm, dữ liệu có giấy phép, xử lý thông tin cá nhân và minh bạch. Đây là bài tốt để sinh viên học cả kỹ thuật code LLM lẫn vấn đề đạo đức/dữ liệu khi dùng mã nguồn mở để huấn luyện.

---

## 8. Code Llama: Open Foundation Models for Code

- **Link bài báo:** https://arxiv.org/abs/2308.12950  
- **Link Meta AI:** https://ai.meta.com/research/publications/code-llama-open-foundation-models-for-code/  
- **Năm:** 2023.
- **Tác giả:** Baptiste Rozière, Jonas Gehring, Fabian Gloeckle, Sten Sootla, Itai Gat, Xiaoqing Ellen Tan, Yossi Adi, Jingyu Liu, Romain Sauvestre, Tal Remez, và cộng sự.
- **Venue/Nguồn:** arXiv / Meta AI.
- **Loại bài:** Foundation model paper.
- **Lĩnh vực:** Code LLM, code completion, code infilling.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** Code Llama, foundation model, code generation, infilling, instruction following.
- **Metadata đáng chú ý:**
  - Có nhiều biến thể: base, Python-specialized, instruction-following.
  - Hỗ trợ context dài và code infilling.
  - Có thể dùng làm model nền cho prototype local hoặc evaluation.
- **Abstract tiếng Việt:**  
  Code Llama là họ mô hình nền tảng cho code dựa trên Llama 2. Bài báo trình bày các biến thể phục vụ nhiều mục đích như sinh code tổng quát, sinh code Python và làm theo chỉ dẫn lập trình. Bài phù hợp để sinh viên tìm hiểu cách benchmark code LLM, đánh giá HumanEval/MBPP hoặc xây trợ lý lập trình cục bộ.

---

## 9. Evaluating Large Language Models Trained on Code

- **Link bài báo:** https://arxiv.org/abs/2107.03374  
- **Năm:** 2021.
- **Tác giả:** Mark Chen, Jerry Tworek, Heewoo Jun, Qiming Yuan, Henrique Ponde de Oliveira Pinto, Jared Kaplan, Harri Edwards, Yuri Burda, Nicholas Joseph, Greg Brockman, và cộng sự.
- **Venue/Nguồn:** arXiv / OpenAI.
- **Loại bài:** Empirical evaluation / benchmark.
- **Lĩnh vực:** Code generation, Codex, HumanEval.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** Codex, HumanEval, pass@k, code synthesis, GitHub Copilot.
- **Metadata đáng chú ý:**
  - Giới thiệu Codex và benchmark HumanEval.
  - Đo functional correctness bằng pass@k.
  - Là bài nền quan trọng cho nghiên cứu code generation.
- **Abstract tiếng Việt:**  
  Bài báo giới thiệu Codex, một mô hình GPT được fine-tune trên dữ liệu code công khai, và đánh giá khả năng sinh code Python từ docstring. Bài cũng giới thiệu HumanEval, benchmark đo khả năng sinh chương trình đúng chức năng bằng unit test. Đây là bài rất quan trọng cho sinh viên muốn hiểu cách đánh giá code generation một cách định lượng.

---

## 10. A Systematic Evaluation of Large Language Models of Code

- **Link bài báo:** https://arxiv.org/abs/2202.13169  
- **Năm:** 2022.
- **Tác giả:** Frank F. Xu, Uri Alon, Graham Neubig, Vincent J. Hellendoorn.
- **Venue/Nguồn:** arXiv.
- **Loại bài:** Empirical evaluation.
- **Lĩnh vực:** Code LLM evaluation.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** PolyCoder, Codex, GPT-Neo, GPT-J, multilingual code models.
- **Metadata đáng chú ý:**
  - So sánh nhiều mô hình code LLM trên nhiều ngôn ngữ.
  - Giới thiệu PolyCoder, mô hình mã nguồn mở huấn luyện trên nhiều ngôn ngữ lập trình.
  - Phù hợp cho đề tài so sánh model coding local/open-source.
- **Abstract tiếng Việt:**  
  Bài báo đánh giá có hệ thống các mô hình ngôn ngữ lớn cho code, bao gồm Codex và các mô hình mã nguồn mở như GPT-J, GPT-Neo, GPT-NeoX và CodeParrot. Tác giả chỉ ra khoảng trống về mô hình code đa ngôn ngữ mã nguồn mở, đồng thời giới thiệu PolyCoder. Đây là bài phù hợp để sinh viên học cách thiết kế benchmark cho code LLM và phân tích khác biệt giữa các ngôn ngữ lập trình.

---

## 11. Defects4J: A Database of Existing Faults to Enable Controlled Testing Studies for Java Programs

- **Link ACM:** https://dl.acm.org/doi/10.1145/2610384.2628055  
- **Link GitHub:** https://github.com/rjust/defects4j  
- **DOI:** 10.1145/2610384.2628055
- **Năm:** 2014.
- **Tác giả:** René Just, Darioush Jalali, Michael D. Ernst.
- **Venue/Nguồn:** ISSTA 2014.
- **Loại bài:** Dataset / benchmark paper.
- **Lĩnh vực:** Software testing, fault localization, program repair.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** Defects4J, real bugs, Java, testing benchmark, program repair.
- **Metadata đáng chú ý:**
  - Benchmark lỗi thật rất phổ biến trong testing và automated program repair.
  - Cung cấp phiên bản lỗi, phiên bản sửa và test suite.
  - Rất phù hợp làm dataset cho sinh viên thực nghiệm.
- **Abstract tiếng Việt:**  
  Defects4J là cơ sở dữ liệu lỗi thật trong các dự án Java mã nguồn mở, giúp nghiên cứu kiểm thử, định vị lỗi và sửa lỗi tự động trong môi trường có kiểm soát. Bài báo cung cấp framework để truy cập phiên bản lỗi, phiên bản đã sửa và test suite tương ứng. Đây là dataset nền tảng cho sinh viên muốn làm đề tài testing, fault localization hoặc automated repair.

---

## 12. Bugs.jar: A Large-Scale, Diverse Dataset of Real-World Java Bugs

- **Link ACM:** https://dl.acm.org/doi/10.1145/3196398.3196473  
- **Link GitHub:** https://github.com/bugs-dot-jar/bugs-dot-jar  
- **DOI:** 10.1145/3196398.3196473
- **Năm:** 2018.
- **Tác giả:** Ripon K. Saha, Yingjun Lyu, Hiroaki Yoshida, Mukul R. Prasad.
- **Venue/Nguồn:** MSR 2018.
- **Loại bài:** Dataset / benchmark paper.
- **Lĩnh vực:** Automated debugging, testing, patching.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** Bugs.jar, Java bugs, automated debugging, program repair, testing.
- **Metadata đáng chú ý:**
  - Gồm 1,158 bugs và patches từ 8 dự án Java lớn.
  - Quy mô lớn hơn Defects4J ở thời điểm công bố.
  - Hợp cho nghiên cứu so sánh bug dataset hoặc repair/test generation.
- **Abstract tiếng Việt:**  
  Bugs.jar là dataset lớn gồm lỗi thật và bản vá từ các dự án Java mã nguồn mở. Bài báo hướng tới việc cung cấp dữ liệu đa dạng hơn cho nghiên cứu automated debugging, testing và patch generation. Với sinh viên, Bugs.jar có thể dùng để xây đề tài phân tích bug report, sửa lỗi tự động, đo hiệu quả test hoặc so sánh với Defects4J.

---

## 13. BugSwarm: Mining and Continuously Growing a Dataset of Reproducible Failures and Fixes

- **Link bài báo:** https://arxiv.org/abs/1903.06725  
- **Link dự án:** https://www.bugswarm.org/  
- **Năm:** 2019.
- **Tác giả:** David A. Tomassi, Naji Dmeiri, Yichen Wang, Antara Bhowmick, Yen-Chuan Liu, Premkumar Devanbu, Bogdan Vasilescu, Cindy Rubio-González.
- **Venue/Nguồn:** ICSE 2019.
- **Loại bài:** Dataset / infrastructure paper.
- **Lĩnh vực:** Reproducible failures, CI, software testing.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** BugSwarm, CI failures, reproducibility, Docker, software testing.
- **Metadata đáng chú ý:**
  - Thu thập fail-pass pairs từ CI.
  - Đóng gói lỗi trong container để tái hiện.
  - Phù hợp với đề tài DevOps + testing + reproducibility.
- **Abstract tiếng Việt:**  
  BugSwarm đề xuất cách khai thác dữ liệu từ hệ thống CI để tạo dataset lỗi có thể tái hiện. Thay vì chỉ lưu commit lỗi, BugSwarm lưu cả môi trường chạy bằng container, giúp đảm bảo khả năng tái lập trong tương lai. Bài này rất phù hợp cho sinh viên nghiên cứu CI/CD, lỗi build, regression testing hoặc reproducible software engineering.

---

## 14. On the Rise and Fall of Simple Stupid Bugs: A Life-Cycle Analysis of SStuBs

- **Link bài báo:** https://arxiv.org/abs/2103.09604  
- **Link dataset ManySStuBs4J:** https://zenodo.org/records/3653444  
- **Năm:** 2021.
- **Tác giả:** Bence Mosolygó, Norbert Vándor, Gábor Antal, Péter Hegedűs.
- **Venue/Nguồn:** MSR 2021.
- **Loại bài:** Empirical study.
- **Lĩnh vực:** Bug lifecycle, simple bugs, software maintenance.
- **Phù hợp:** Kỳ 6, 7.
- **Từ khóa:** SStuBs, simple bugs, bug lifecycle, Java, program repair.
- **Metadata đáng chú ý:**
  - Dựa trên dataset ManySStuBs4J.
  - Phân tích vòng đời của các lỗi đơn giản trong dự án Java.
  - Phù hợp cho sinh viên mới làm bug mining hoặc empirical SE.
- **Abstract tiếng Việt:**  
  Bài báo nghiên cứu vòng đời của các lỗi đơn giản trong mã nguồn Java, thường là lỗi một câu lệnh do bất cẩn. Tác giả phân tích các lỗi này tồn tại bao lâu, ai sửa, lỗi xuất hiện khi thêm code mới hay sửa code cũ. Bài này phù hợp để sinh viên học mining software repositories, phân tích lịch sử commit và làm đề tài bug pattern.

---

## 15. A Systematic Literature Review on Fault Prediction Performance in Software Engineering

- **Link thông tin bài:** https://research.lancaster-university.uk/en/publications/a-systematic-literature-review-on-fault-prediction-performance-in/  
- **DOI:** 10.1109/TSE.2011.103
- **Năm:** 2012.
- **Tác giả:** Tracy Hall, Sarah Beecham, David Bowes, David Gray, Steve Counsell.
- **Venue/Nguồn:** IEEE Transactions on Software Engineering.
- **Loại bài:** Systematic Literature Review.
- **Lĩnh vực:** Software fault prediction.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** fault prediction, defect prediction, software metrics, machine learning.
- **Metadata đáng chú ý:**
  - Review 208 nghiên cứu từ 2000 đến 2010.
  - Phân tích 36 nghiên cứu có đủ thông tin định lượng/ngữ cảnh.
  - Là bài nền kinh điển cho defect prediction.
- **Abstract tiếng Việt:**  
  Bài báo tổng quan có hệ thống về hiệu năng của các mô hình dự đoán lỗi phần mềm. Tác giả phân tích vai trò của ngữ cảnh, biến độc lập, loại metric và mô hình dự đoán đối với hiệu quả phát hiện module dễ lỗi. Bài phù hợp cho sinh viên muốn làm đề tài defect prediction bằng machine learning, đặc biệt khi cần hiểu baseline truyền thống trước khi dùng deep learning hoặc LLM.

---

## 16. Deep Learning Based Vulnerability Detection: Are We There Yet?

- **Link bài báo:** https://arxiv.org/abs/2009.07235  
- **Năm:** 2020.
- **Tác giả:** Saikat Chakraborty, Rahul Krishna, Yangruibo Ding, Baishakhi Ray.
- **Venue/Nguồn:** IEEE Transactions on Software Engineering / ICSE Journal First.
- **Loại bài:** Empirical study.
- **Lĩnh vực:** Software vulnerability detection.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** vulnerability detection, deep learning, software security, generalization.
- **Metadata đáng chú ý:**
  - Kiểm tra tính tổng quát của các phương pháp deep learning phát hiện lỗ hổng.
  - Chỉ ra các vấn đề về dữ liệu huấn luyện, trùng lặp dữ liệu và phân phối không thực tế.
  - Phù hợp để dạy sinh viên về leakage và validity trong thực nghiệm.
- **Abstract tiếng Việt:**  
  Bài báo đánh giá nghiêm túc các phương pháp deep learning cho phát hiện lỗ hổng phần mềm. Dù nhiều nghiên cứu báo cáo accuracy rất cao, bài này cho thấy khi đánh giá trong bối cảnh thực tế hơn, hiệu năng giảm mạnh. Nguyên nhân đến từ dữ liệu thiếu thực tế, trùng lặp, phân phối nhãn không hợp lý và mô hình học nhầm artifact thay vì nguyên nhân lỗi. Đây là bài rất tốt để sinh viên học cách thiết kế thực nghiệm chống bias/leakage.

---

## 17. Machine Learning-Enhanced Requirements Engineering: A Systematic Literature Review

- **Link thông tin bài:** https://investigacion.ucuenca.edu.ec/en/publications/machine-learning-enhanced-requirements-engineering-a-systematic-l-2/  
- **Link PDF:** https://www.scitepress.org/Papers/2024/126881/126881.pdf  
- **Năm:** 2024.
- **Tác giả:** A. G. Núñez và cộng sự.
- **Venue/Nguồn:** SciTePress / ICEIS-related publication.
- **Loại bài:** Systematic Literature Review.
- **Lĩnh vực:** Requirements Engineering, Machine Learning, NLP.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** requirements engineering, machine learning, NLP, classification, prioritization.
- **Metadata đáng chú ý:**
  - Review các nghiên cứu từ 2012 đến 06/2023.
  - Lọc 74 bài từ 1,219 bài trong các nguồn như Scopus, WoS, IEEE, ACM và ProQuest.
  - Bao phủ elicitation, extraction, validation, prioritization và classification.
- **Abstract tiếng Việt:**  
  Bài báo tổng quan các phương pháp machine learning trong Requirements Engineering. Tác giả phân tích cách ML/NLP được dùng để trích xuất, phân loại, ưu tiên, kiểm tra và quản lý yêu cầu phần mềm. Đây là bài phù hợp để sinh viên làm đề tài phân loại requirement, phát hiện requirement mơ hồ, tách functional/non-functional requirement hoặc gợi ý use case.

---

## 18. Software Engineering for AI-Based Systems: A Survey

- **Link bài báo:** https://arxiv.org/abs/2105.01984  
- **Link ACM:** https://dl.acm.org/doi/10.1145/3487043  
- **DOI:** 10.1145/3487043
- **Năm:** 2021 preprint; ACM TOSEM 2022.
- **Tác giả:** Silverio Martínez-Fernández, Justus Bogner, Xavier Franch, Marc Oriol, Julien Siebert, Adam Trendowicz, Anna Maria Vollmer, Stefan Wagner.
- **Venue/Nguồn:** ACM Transactions on Software Engineering and Methodology.
- **Loại bài:** Survey / systematic mapping study.
- **Lĩnh vực:** Software Engineering for AI-based systems.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** AI-based systems, software engineering, testing, quality, data management, dependability.
- **Metadata đáng chú ý:**
  - Phân tích 248 nghiên cứu từ 2010 đến 03/2020.
  - Xác định các thách thức phổ biến như testing, quality, data management.
  - Phù hợp cho các đề tài SE for AI, MLOps, AI quality assurance.
- **Abstract tiếng Việt:**  
  Bài báo khảo sát cách Software Engineering được áp dụng cho hệ thống có thành phần AI. Tác giả phân loại các hướng nghiên cứu theo SWEBOK và chỉ ra rằng testing, software quality, dependability và safety là các chủ đề nổi bật, trong khi maintenance còn ít được nghiên cứu. Đây là bài nền tốt cho sinh viên muốn làm đề tài kiểm thử AI, quản lý dữ liệu ML, MLOps hoặc chất lượng phần mềm AI.

---

## 19. Hidden Technical Debt in Machine Learning Systems

- **Link bài báo:** https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-syst  
- **Link Google Research:** https://research.google/pubs/hidden-technical-debt-in-machine-learning-systems/  
- **Năm:** 2015.
- **Tác giả:** D. Sculley, Gary Holt, Daniel Golovin, Eugene Davydov, Todd Phillips, Dietmar Ebner, Vinay Chaudhary, Michael Young, Jean-François Crespo, Dan Dennison.
- **Venue/Nguồn:** NeurIPS 2015.
- **Loại bài:** Position / experience / system design paper.
- **Lĩnh vực:** Technical debt, ML systems, maintainability.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** technical debt, ML systems, maintainability, data dependency, entanglement.
- **Metadata đáng chú ý:**
  - Bài kinh điển về technical debt trong hệ thống ML.
  - Phân tích boundary erosion, entanglement, hidden feedback loops và undeclared consumers.
  - Phù hợp cho đề tài MLOps, ML system monitoring, maintainability.
- **Abstract tiếng Việt:**  
  Bài báo cho rằng hệ thống machine learning có thể tạo ra nợ kỹ thuật nghiêm trọng hơn phần mềm truyền thống, vì ngoài code còn có dữ liệu, feature, model, pipeline và feedback loop. Các vấn đề như phụ thuộc dữ liệu ẩn, coupling giữa feature, boundary erosion và khó kiểm thử làm chi phí bảo trì tăng dần. Bài này rất phù hợp để sinh viên SE hiểu rằng xây hệ thống AI không chỉ là train model, mà còn là bài toán engineering dài hạn.

---

## 20. Machine Learning Operations (MLOps): Overview, Definition, and Architecture

- **Link bài báo:** https://arxiv.org/abs/2205.02302  
- **Năm:** 2022.
- **Tác giả:** Dominik Kreuzberger, Niklas Kühl, Sebastian Hirschl.
- **Venue/Nguồn:** arXiv; được trích dẫn rộng rãi trong MLOps.
- **Loại bài:** Overview / definition / architecture paper.
- **Lĩnh vực:** MLOps, DevOps for ML, AI system deployment.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** MLOps, CI/CD, ML pipeline, monitoring, automation, production ML.
- **Metadata đáng chú ý:**
  - Kết hợp literature review, tool review và expert interviews.
  - Đề xuất định nghĩa, nguyên tắc, vai trò, thành phần và kiến trúc MLOps.
  - Phù hợp cho đề tài triển khai AI/ML vào hệ thống phần mềm thật.
- **Abstract tiếng Việt:**  
  Bài báo tổng hợp khái niệm, định nghĩa và kiến trúc MLOps nhằm đưa mô hình ML vào môi trường production một cách tự động, có thể theo dõi và vận hành ổn định. Tác giả trình bày các thành phần như pipeline, versioning, automation, monitoring, CI/CD và vai trò của các nhóm liên quan. Đây là bài phù hợp cho sinh viên SE làm đề tài DevOps/MLOps, đặc biệt khi xây hệ thống AI ứng dụng có backend, model, monitoring và deployment.

---

# Gợi ý phân nhóm sử dụng cho sinh viên

## Nhóm A — Code Intelligence / Code LLM

Nên đọc:

1. CodeBERT  
2. GraphCodeBERT  
3. UniXcoder  
4. CodeXGLUE  
5. CodeT5  
6. CodeT5+  
7. StarCoder  
8. Code Llama  
9. Evaluating Large Language Models Trained on Code  
10. A Systematic Evaluation of Large Language Models of Code  

Hướng đề tài:

- Code search theo tiếng Việt.
- Sinh mô tả code tự động.
- So sánh mô hình code generation.
- Đánh giá code LLM trên bài tập sinh viên.
- RAG cho codebase môn học.

---

## Nhóm B — Testing / Bug Dataset / Program Repair

Nên đọc:

1. Defects4J  
2. Bugs.jar  
3. BugSwarm  
4. On the Rise and Fall of Simple Stupid Bugs  
5. A Systematic Literature Review on Fault Prediction Performance  
6. Deep Learning Based Vulnerability Detection  

Hướng đề tài:

- Bug classification.
- Defect prediction.
- Fault localization.
- Test generation.
- Patch suggestion.
- Phân tích lỗi từ GitHub commit.

---

## Nhóm C — Requirements / SE for AI / MLOps

Nên đọc:

1. Machine Learning-Enhanced Requirements Engineering  
2. Software Engineering for AI-Based Systems  
3. Hidden Technical Debt in Machine Learning Systems  
4. Machine Learning Operations: Overview, Definition, and Architecture  

Hướng đề tài:

- Requirement classification.
- Requirement ambiguity detection.
- AI system quality checklist.
- MLOps dashboard.
- Technical debt monitoring cho hệ thống AI.
- CI/CD pipeline cho model ML.
