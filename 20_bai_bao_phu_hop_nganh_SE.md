# Danh sách 20 bài báo phù hợp với sinh viên ngành Software Engineering

> Mục đích: tài liệu này dùng để giao cho sinh viên ngành Software Engineering đọc, làm literature matrix, tái hiện prototype, xây baseline, thiết kế experiment và phát triển thành bài báo nghiên cứu ứng dụng.  
> Nội dung abstract bên dưới là bản tóm tắt/diễn giải tiếng Việt, không phải bản dịch nguyên văn toàn bộ abstract.

---

## 1. Large Language Models for Software Engineering: A Systematic Literature Review

- **Link bài báo:** https://arxiv.org/abs/2308.10620  
- **Link ACM/TOSEM:** https://dl.acm.org/doi/10.1145/3695988  
- **Năm:** 2023 preprint; bản journal ACM TOSEM 2024/2025 tùy phiên bản xuất bản.
- **Tác giả:** Xinyi Hou, Yanjie Zhao, Yue Liu, Zhou Yang, Kailong Wang, Li Li, Xiapu Luo, David Lo, John Grundy, Haoyu Wang.
- **Loại bài:** Systematic Literature Review.
- **Lĩnh vực:** LLM for Software Engineering.
- **Phù hợp:** Kỳ 5, 6, 7, 8.
- **Từ khóa:** Large Language Models, Software Engineering, SLR, LLM4SE, code tasks.
- **Metadata đáng chú ý:**
  - Phân tích khoảng 395 bài nghiên cứu từ 2017 đến 01/2024.
  - Có repository artifact: https://github.com/xinyi-hou/LLM4SE_SLR
- **Abstract tiếng Việt:**  
  Bài báo tổng quan có hệ thống về việc sử dụng mô hình ngôn ngữ lớn trong ngành Software Engineering. Tác giả phân tích cách LLM được dùng trong các nhiệm vụ SE, từ xử lý dữ liệu, tiền xử lý, tối ưu, đánh giá đến các tác vụ như sinh mã, sửa lỗi, kiểm thử, bảo trì và hỗ trợ quy trình phát triển phần mềm. Bài báo phù hợp làm tài liệu nền để sinh viên hiểu bức tranh tổng thể LLM4SE, tìm hướng nghiên cứu nhỏ hơn và xác định gap.

---

## 2. A Survey on Large Language Models for Software Engineering

- **Link bài báo:** https://arxiv.org/abs/2312.15223  
- **Link Springer:** https://link.springer.com/article/10.1007/s11432-025-4670-0  
- **Năm:** 2023 preprint; bản journal 2026.
- **Tác giả:** Quanjun Zhang, Chunrong Fang, Yang Xie, Yaxin Zhang, Yun Yang, Weisong Sun, Shengcheng Yu, Zhenyu Chen.
- **Loại bài:** Survey.
- **Lĩnh vực:** LLM for Software Engineering.
- **Phù hợp:** Kỳ 5, 6, 7, 8.
- **Từ khóa:** Code LLM, SE workflow, code generation, testing, maintenance.
- **Metadata đáng chú ý:**
  - Tổng hợp 62 Code LLM.
  - Phân tích 15 pre-training objectives.
  - Bao phủ 16 downstream tasks trong 5 nhóm nhiệm vụ SE.
  - Repository: https://github.com/iSEngLab/AwesomeLLM4SE
- **Abstract tiếng Việt:**  
  Bài khảo sát hệ thống hóa các mô hình LLM dùng trong Software Engineering, bao gồm kiến trúc mô hình, mục tiêu tiền huấn luyện, các nhóm nhiệm vụ trong quy trình phát triển phần mềm và các vấn đề như benchmark, bảo mật, độ tin cậy, domain tuning, nén mô hình. Bài này phù hợp để sinh viên xây literature map và chọn đề tài cụ thể như code generation, testing, requirement hoặc maintenance.

---

## 3. Large Language Model-Based Agents for Software Engineering: A Survey

- **Link bài báo:** https://arxiv.org/abs/2409.02977  
- **Năm:** 2024.
- **Tác giả:** Junwei Liu, Kaixin Wang, Yixuan Chen, Xin Peng, Zhenpeng Chen, Lingming Zhang, Yiling Lou.
- **Loại bài:** Survey.
- **Lĩnh vực:** LLM-based Agent for Software Engineering.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** LLM agents, Software Engineering, tool use, multi-agent, human-agent collaboration.
- **Metadata đáng chú ý:**
  - Phân tích 106 bài về LLM-based agents cho SE.
  - Repository: https://github.com/FudanSELab/Agent4SE-Paper-List
- **Abstract tiếng Việt:**  
  Bài báo khảo sát cách các agent dựa trên LLM được ứng dụng vào Software Engineering. Khác với LLM đơn lẻ, agent có thể dùng công cụ, truy cập tài nguyên bên ngoài, phối hợp nhiều vai trò và tương tác với con người. Bài báo phân loại các nghiên cứu theo góc nhìn nhiệm vụ SE và góc nhìn kiến trúc agent, đồng thời chỉ ra thách thức và hướng nghiên cứu mới cho agent trong phát triển phần mềm.

---

## 4. Agents in Software Engineering: Survey, Landscape, and Vision

- **Link bài báo:** https://arxiv.org/abs/2409.09030  
- **Năm:** 2024.
- **Tác giả:** Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng.
- **Loại bài:** Survey / Vision paper.
- **Lĩnh vực:** Agentic Software Engineering.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** LLM-based agents, perception, memory, action, SE automation.
- **Metadata đáng chú ý:**
  - Đề xuất framework agent trong SE gồm 3 module: perception, memory, action.
  - Repository: https://github.com/DeepSoftwareAnalytics/Awesome-Agent4SE
- **Abstract tiếng Việt:**  
  Bài báo trình bày toàn cảnh nghiên cứu về agent trong Software Engineering, đặc biệt là các agent dựa trên LLM. Tác giả xây dựng khung phân tích gồm nhận thức, bộ nhớ và hành động để mô tả cách agent xử lý đầu vào, lưu trữ kinh nghiệm và thực hiện hành động như suy luận, truy xuất, chỉnh sửa mã hoặc chạy công cụ. Bài phù hợp cho nhóm muốn làm multi-agent SDLC, agent hỗ trợ coding, testing, code review hoặc requirement.

---

## 5. Generative AI and Empirical Software Engineering: A Paradigm Shift

- **Link bài báo:** https://arxiv.org/abs/2502.08108  
- **Năm:** 2025.
- **Tác giả:** Christoph Treude, Margaret-Anne Storey.
- **Loại bài:** Perspective / Empirical Software Engineering.
- **Lĩnh vực:** Generative AI in Empirical Software Engineering.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** Generative AI, empirical software engineering, research methods, validity.
- **Metadata đáng chú ý:**
  - Tập trung vào thay đổi phương pháp nghiên cứu thực nghiệm khi GenAI tham gia vào quy trình SE.
  - Phù hợp để hướng dẫn sinh viên viết phần methodology và threats to validity.
- **Abstract tiếng Việt:**  
  Bài báo bàn về cách Generative AI đang làm thay đổi nghiên cứu thực nghiệm trong Software Engineering. Khi AI không chỉ là công cụ hỗ trợ mà còn tham gia vào quá trình tạo artifact, vai trò của developer, user, agent và researcher trở nên chồng lấn. Bài báo phân tích các hiện tượng nghiên cứu mới, loại dữ liệu mới, phương pháp nghiên cứu mới và các mối đe dọa tới tính hợp lệ khi nghiên cứu SE trong bối cảnh GenAI.

---

## 6. SWE-bench: Can Language Models Resolve Real-World GitHub Issues?

- **Link bài báo:** https://arxiv.org/abs/2310.06770  
- **Link OpenReview:** https://openreview.net/forum?id=VTF8yNQM66  
- **Năm:** 2023 preprint; ICLR 2024.
- **Tác giả:** Carlos E. Jimenez, John Yang, Alexander Wettig, Shunyu Yao, Kexin Pei, Ofir Press, Karthik Narasimhan.
- **Loại bài:** Benchmark / Empirical Evaluation.
- **Lĩnh vực:** Automated Software Engineering, GitHub issue resolution.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** SWE-bench, GitHub issues, bug fixing, benchmark, code agents.
- **Metadata đáng chú ý:**
  - Gồm 2,294 vấn đề từ 12 Python repositories.
  - Task: model nhận issue + codebase và phải tạo patch sửa lỗi.
  - Repository/dataset: https://github.com/swe-bench/SWE-bench
- **Abstract tiếng Việt:**  
  Bài báo giới thiệu SWE-bench, một benchmark dùng để đánh giá khả năng của mô hình ngôn ngữ trong việc xử lý issue thực tế trên GitHub. Khác với bài toán sinh code ngắn, SWE-bench yêu cầu model hiểu codebase lớn, chỉnh sửa nhiều file, chạy test và tạo patch đúng. Kết quả cho thấy các model hiện đại vẫn gặp nhiều khó khăn với các vấn đề phần mềm thực tế, do đó benchmark này rất phù hợp cho nghiên cứu agent sửa bug.

---

## 7. SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering

- **Link bài báo:** https://arxiv.org/abs/2405.15793  
- **Link NeurIPS:** https://proceedings.neurips.cc/paper_files/paper/2024/hash/5a7c947568c1b1328ccc5230172e1e7c-Abstract-Conference.html  
- **Năm:** 2024.
- **Tác giả:** John Yang, Carlos E. Jimenez, Alexander Wettig, Kilian Lieret, Shunyu Yao, Karthik Narasimhan, Ofir Press.
- **Loại bài:** System / Agent / Empirical Evaluation.
- **Lĩnh vực:** Software Engineering Agent.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** SWE-agent, agent-computer interface, repository navigation, code editing, tests.
- **Metadata đáng chú ý:**
  - Đề xuất khái niệm Agent-Computer Interface.
  - Đánh giá trên SWE-bench và HumanEvalFix.
  - Repository: https://github.com/SWE-agent/SWE-agent
- **Abstract tiếng Việt:**  
  Bài báo đề xuất SWE-agent, một hệ thống cho phép agent dựa trên mô hình ngôn ngữ thao tác với máy tính để giải quyết tác vụ phần mềm. Trọng tâm của bài không chỉ là model mạnh, mà là thiết kế giao diện giữa agent và môi trường phát triển: tìm file, xem file, chỉnh sửa, quản lý context và chạy test. Bài phù hợp để sinh viên nghiên cứu cách thiết kế tool-use cho agent sửa lỗi hoặc hỗ trợ lập trình.

---

## 8. ChatDev: Communicative Agents for Software Development

- **Link bài báo:** https://arxiv.org/abs/2307.07924  
- **Link ACL Anthology:** https://aclanthology.org/2024.acl-long.810/  
- **Năm:** 2023 preprint; ACL 2024.
- **Tác giả:** Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun.
- **Loại bài:** Multi-agent system.
- **Lĩnh vực:** LLM agents for software development.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** ChatDev, communicative agents, multi-agent collaboration, software development.
- **Metadata đáng chú ý:**
  - Mô phỏng công ty phần mềm với nhiều agent chuyên vai trò.
  - Repository: https://github.com/OpenBMB/ChatDev
- **Abstract tiếng Việt:**  
  Bài báo giới thiệu ChatDev, một framework phát triển phần mềm dựa trên nhiều agent giao tiếp với nhau. Các agent đảm nhận vai trò trong quy trình như thiết kế, lập trình và kiểm thử, sử dụng hội thoại làm cơ chế phối hợp. Bài này phù hợp cho nhóm sinh viên muốn làm hệ thống multi-agent mini mô phỏng SDLC hoặc nghiên cứu cách phân vai agent trong phát triển phần mềm.

---

## 9. A Survey on Large Language Models for Code Generation

- **Link bài báo:** https://arxiv.org/abs/2406.00515  
- **Link ACM:** https://dl.acm.org/doi/10.1145/3747588  
- **Năm:** 2024 preprint; ACM TOSEM 2025.
- **Tác giả:** Juyong Jiang, Fan Wang, Jiasi Shen, Sungju Kim, Sunghun Kim.
- **Loại bài:** Survey.
- **Lĩnh vực:** Code generation.
- **Phù hợp:** Kỳ 5, 6, 7, 8.
- **Từ khóa:** LLM, code generation, HumanEval, MBPP, BigCodeBench.
- **Metadata đáng chú ý:**
  - Có taxonomy cho LLM code generation.
  - So sánh thực nghiệm trên HumanEval, MBPP và BigCodeBench.
  - Repository: https://github.com/juyongjiang/CodeLLMSurvey
- **Abstract tiếng Việt:**  
  Bài khảo sát toàn diện về LLM cho sinh mã nguồn từ mô tả ngôn ngữ tự nhiên. Bài phân tích dữ liệu huấn luyện, tiến bộ mô hình, phương pháp đánh giá, vấn đề đạo đức, tác động môi trường và ứng dụng thực tế. Đây là bài nền tốt cho sinh viên nghiên cứu code generation, đánh giá code do AI sinh và khoảng cách giữa benchmark học thuật với phát triển phần mềm thực tế.

---

## 10. A Survey on LLM-based Code Generation for Low-Resource and Domain-Specific Programming Languages

- **Link bài báo:** https://arxiv.org/abs/2410.03981  
- **Link ACM:** https://dl.acm.org/doi/10.1145/3770084  
- **Năm:** 2024 preprint; ACM TOSEM 2025.
- **Tác giả:** Sathvik Joel, Jie JW Wu, Fatemeh H. Fard.
- **Loại bài:** Survey.
- **Lĩnh vực:** Code generation, Low-resource programming languages, DSL.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** Low-resource programming languages, domain-specific languages, LLM code generation.
- **Metadata đáng chú ý:**
  - Lọc 111 bài từ hơn 27,000 nghiên cứu giai đoạn 2020–2024.
  - Repository: https://github.com/jie-jw-wu/Survey-CodeLLM4LowResource-DSL
- **Abstract tiếng Việt:**  
  Bài báo tập trung vào vấn đề LLM sinh code cho ngôn ngữ lập trình ít tài nguyên và ngôn ngữ chuyên biệt theo miền. Tác giả chỉ ra các khó khăn như thiếu dữ liệu, cú pháp đặc thù, benchmark chưa chuẩn và chiến lược cải thiện còn phân tán. Bài phù hợp cho nhóm muốn nghiên cứu code generation trong bối cảnh domain-specific, ví dụ DSL cho giáo dục, workflow, IoT hoặc business rules.

---

## 11. Automating Code Review Activities by Large-Scale Pre-training

- **Link bài báo:** https://arxiv.org/abs/2203.09095  
- **Link ACM:** https://dl.acm.org/doi/10.1145/3540250.3549081  
- **Năm:** 2022.
- **Tác giả:** Zhiyu Li, Shuai Lu, Daya Guo, Nan Duan, Shailesh Jannu, Grant Jenks, Deep Majumder, Jared Green, Alexey Svyatkovskiy, Shengyu Fu, Neel Sundaresan.
- **Loại bài:** Model / Benchmark / Empirical Evaluation.
- **Lĩnh vực:** Automated Code Review.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** CodeReviewer, code review, pre-training, review comment generation, code refinement.
- **Metadata đáng chú ý:**
  - Đề xuất mô hình CodeReviewer.
  - Xử lý 3 tác vụ: ước lượng chất lượng code change, sinh review comment, refinement.
  - Artifact/dataset: https://zenodo.org/records/6900648
- **Abstract tiếng Việt:**  
  Bài báo đề xuất CodeReviewer, mô hình tiền huấn luyện dành riêng cho hoạt động code review. Tác giả thu thập dữ liệu code changes và review từ các dự án mã nguồn mở ở nhiều ngôn ngữ, sau đó thiết kế các tác vụ tiền huấn luyện để model hiểu diff và comment review. Bài phù hợp để sinh viên làm đề tài code review assistant, so sánh static analysis với LLM hoặc sinh feedback cho bài code của sinh viên.

---

## 12. Quality Assurance of LLM-generated Code: Addressing Non-Functional Quality Characteristics

- **Link bài báo:** https://arxiv.org/abs/2511.10271  
- **Link ScienceDirect:** https://www.sciencedirect.com/science/article/abs/pii/S0164121226001184  
- **Năm:** 2025 preprint; bản journal 2026.
- **Tác giả:** Xin Sun, Daniel Ståhl, Kristian Sandahl, Christoph Kessler.
- **Loại bài:** Systematic review + workshop + empirical study.
- **Lĩnh vực:** Quality assurance for LLM-generated code.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** LLM-generated code, ISO/IEC 25010, maintainability, security, performance.
- **Metadata đáng chú ý:**
  - Dựa trên ISO/IEC 25010.
  - Review 108 bài.
  - Có workshop với practitioner và phân tích empirical trên patch thực tế.
- **Abstract tiếng Việt:**  
  Bài báo nghiên cứu chất lượng phi chức năng của code do LLM sinh ra. Thay vì chỉ kiểm tra code có pass test hay không, tác giả xem xét các khía cạnh như bảo mật, maintainability, readability và hiệu năng. Kết quả cho thấy code đúng chức năng vẫn có thể tạo nợ kỹ thuật hoặc suy giảm chất lượng ở các chiều khác. Bài rất phù hợp cho đề tài QA pipeline cho AI-generated code.

---

## 13. Bridging Generation and Training: A Systematic Review of Quality Issues in LLMs for Code

- **Link bài báo:** https://arxiv.org/abs/2605.05267  
- **Năm:** 2026.
- **Tác giả:** Kaifeng He, Xiaojun Zhang, Peiliang Cai, Mingwei Liu, Yanlin Wang, Chong Wang, Kaifeng Huang, Bihuan Chen, Xin Peng, Zibin Zheng.
- **Loại bài:** Systematic Literature Review.
- **Lĩnh vực:** Code quality, training data quality, LLM for code.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** code quality, training data, generated code, data-centric AI, code defects.
- **Metadata đáng chú ý:**
  - Review 114 nghiên cứu chính.
  - Đề xuất taxonomy 9 chiều cho lỗi chất lượng code sinh ra.
  - Repository: https://github.com/SYSUSELab/From-Data-to-Code
- **Abstract tiếng Việt:**  
  Bài báo phân tích mối liên hệ giữa chất lượng dữ liệu huấn luyện và lỗi trong code do LLM sinh ra. Thay vì chỉ xem lỗi code là hạn chế của model, bài này chỉ ra nhiều lỗi có nguồn gốc từ dữ liệu huấn luyện kém chất lượng. Tác giả đề xuất taxonomy, cơ chế lan truyền lỗi và các hướng phát hiện/giảm thiểu trong toàn bộ vòng đời dữ liệu, mô hình và generation. Đây là bài nền tốt cho hướng data-centric code LLM.

---

## 14. SWE-Dev: Building Software Engineering Agents with Training and Inference Scaling

- **Link bài báo:** https://arxiv.org/abs/2506.07636  
- **Link ACL Findings:** https://aclanthology.org/2025.findings-acl.193/  
- **Năm:** 2025.
- **Tác giả:** Haoran Wang, Zhenyu Hou, Yao Wei, Jie Tang, Yuxiao Dong.
- **Loại bài:** Agent / Training data / Benchmark.
- **Lĩnh vực:** Software Engineering Agent.
- **Phù hợp:** Kỳ 8 hoặc nhóm mạnh kỳ 7.
- **Từ khóa:** SWE agent, inference scaling, training scaling, test synthesis, SWE-bench Verified.
- **Metadata đáng chú ý:**
  - Xây SWE agent dựa trên open-source LLM.
  - Tập trung vào sinh test case và agent trajectories.
  - Repository: https://github.com/THUDM/SWE-Dev
- **Abstract tiếng Việt:**  
  Bài báo giới thiệu SWE-Dev, một agent phần mềm dựa trên mô hình mã nguồn mở. Tác giả tập trung vào hai vấn đề quan trọng: thiếu dữ liệu huấn luyện chất lượng cao cho agent và thiếu test case đáng tin cậy để đánh giá patch. Bài đề xuất pipeline sinh test case, mở rộng agent trajectories và huấn luyện agent để cải thiện kết quả trên SWE-bench Verified. Phù hợp cho nhóm nghiên cứu agent sửa lỗi nâng cao.

---

## 15. Retrieval-Augmented Code Generation: A Survey with Focus on Repository-Level Approaches

- **Link bài báo:** https://arxiv.org/abs/2510.04905  
- **Năm:** 2025.
- **Tác giả:** Yicheng Tao, Yao Qin, Yepang Liu.
- **Loại bài:** Survey.
- **Lĩnh vực:** Retrieval-Augmented Code Generation, Repository-Level Code Generation.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** RAG, code generation, repository-level, retrieval, codebase understanding.
- **Metadata đáng chú ý:**
  - Tập trung vào sinh code cấp repository.
  - Phân tích retrieval modality, generation strategy, architecture, training và evaluation protocol.
- **Abstract tiếng Việt:**  
  Bài khảo sát về sinh code có tăng cường truy xuất, đặc biệt ở cấp repository. Tác giả chỉ ra rằng sinh code thực tế không chỉ là viết một hàm đơn lẻ mà cần hiểu nhiều file, module và quan hệ phụ thuộc trong toàn bộ codebase. RAG giúp model truy xuất ngữ cảnh liên quan để sinh code chính xác và nhất quán hơn. Bài phù hợp cho đề tài codebase assistant, repository QA hoặc RAG cho sửa lỗi trong repo.

---

## 16. Large Language Models (LLMs) for Requirements Engineering (RE): A Systematic Literature Review

- **Link bài báo:** https://arxiv.org/abs/2509.11446  
- **Năm:** 2025.
- **Tác giả:** Mohammad Amin Zadenoori, Jacek Dąbrowski, Waad Alhoshan, Liping Zhao, Alessio Ferrari.
- **Loại bài:** Systematic Literature Review.
- **Lĩnh vực:** Requirements Engineering.
- **Phù hợp:** Kỳ 6, 7, 8.
- **Từ khóa:** Requirements Engineering, LLM, elicitation, validation, requirements classification.
- **Metadata đáng chú ý:**
  - Review 74 nghiên cứu chính giai đoạn 2023–2024.
  - Phân tích RE activities, prompting strategies và evaluation methods.
- **Abstract tiếng Việt:**  
  Bài báo khảo sát việc ứng dụng LLM trong Requirements Engineering. Các nghiên cứu được phân tích theo hoạt động RE như elicitation, validation, defect detection, classification, test generation và kết nối với các tác vụ SE khác. Bài cho thấy GPT-based model, zero-shot và few-shot prompting xuất hiện nhiều, nhưng phần lớn vẫn được đánh giá trong môi trường kiểm soát, ít triển khai công nghiệp. Phù hợp cho đề tài requirement classification, ambiguity detection, use case generation hoặc NFR checking.

---

## 17. Application of Retrieval-Augmented Generation (RAG) Systems in Software Engineering Education: An Approach Based on Generative AI and DevOps

- **Link bài báo:** https://www.ijcopi.org/ojs/article/view/1003  
- **DOI:** https://doi.org/10.61467/2007.1558.2025.v16i4.1003  
- **Năm:** 2025.
- **Tác giả:** Yazmin Valeria Valeria Morales, Blanca Dina Valenzuela Robles, René Santaolaya Salgado, Juan Gabriel González Serna, Noé Alejandro Castro Sánchez, Mirna Ariadna Muñoz Mata.
- **Tạp chí:** International Journal of Combinatorial Optimization Problems and Informatics, 16(4), 345–363.
- **Loại bài:** Systematic Literature Review.
- **Lĩnh vực:** RAG, Software Engineering Education, DevOps.
- **Phù hợp:** Kỳ 5, 6, 7, 8.
- **Từ khóa:** Artificial Intelligence, Software Engineering, Large Language Models, DevOps, Human-AI Interaction, Retrieval-Augmented Generation.
- **Metadata đáng chú ý:**
  - Phân tích 71 bài báo.
  - Tập trung vào RAG trong giáo dục, đặc biệt dạy SE và các ngành computing.
- **Abstract tiếng Việt:**  
  Bài báo tổng quan có hệ thống về ứng dụng RAG trong giáo dục, tập trung vào giảng dạy Software Engineering và các ngành liên quan đến computing. Tác giả tổng hợp bằng chứng từ case study, thực nghiệm học thuật và khảo sát giáo viên/sinh viên, đồng thời phân tích cách RAG có thể giảm hallucination, cải thiện tương tác người–AI và kết hợp với DevOps để hỗ trợ tự động hóa, cải tiến liên tục trong giáo dục.

---

## 18. Software Engineering Education in the Era of Conversational AI: Current Trends and Future Directions

- **Link bài báo:** https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2024.1436350/full  
- **Link PubMed Central:** https://pmc.ncbi.nlm.nih.gov/articles/PMC11391529/  
- **DOI:** https://doi.org/10.3389/frai.2024.1436350  
- **Năm:** 2024.
- **Tác giả:** C. Sengul, R. Neykova, G. Destefanis.
- **Tạp chí:** Frontiers in Artificial Intelligence.
- **Loại bài:** Review / Perspective.
- **Lĩnh vực:** Software Engineering Education, Conversational AI.
- **Phù hợp:** Kỳ 5, 6, 7, 8.
- **Từ khóa:** conversational AI, software engineering education, computing education, LLM.
- **Metadata đáng chú ý:**
  - Tổng hợp xu hướng AI hội thoại trong giáo dục SE.
  - Có thảo luận về tác động tới dạy, học và đánh giá.
- **Abstract tiếng Việt:**  
  Bài báo phân tích tác động của conversational AI đối với giáo dục Software Engineering. Tác giả bàn về xu hướng sử dụng công cụ như ChatGPT trong học tập và thực hành SE, các cơ hội trong hỗ trợ sinh viên, thiết kế bài tập, phản hồi tự động, cũng như các rủi ro liên quan đến đạo đức, đánh giá và năng lực thật của người học. Bài phù hợp cho đề tài AI tutor, AI feedback, AI-assisted assessment hoặc redesign môn học SE.

---

## 19. Enhancing Software Engineering Education through AI: An Empirical Study of Tree-Based Machine Learning for Defect Prediction

- **Link bài báo:** https://dl.acm.org/doi/abs/10.1145/3686852.3686881  
- **DOI:** https://doi.org/10.1145/3686852.3686881  
- **Năm:** 2024.
- **Tác giả:** Ensaf Alhazeem.
- **Nguồn:** ACM Digital Library.
- **Loại bài:** Empirical study.
- **Lĩnh vực:** Software Engineering Education, defect prediction, machine learning.
- **Phù hợp:** Kỳ 6, 7.
- **Từ khóa:** software engineering education, AI, defect prediction, tree-based machine learning.
- **Metadata đáng chú ý:**
  - Bài tập trung vào ứng dụng machine learning dạng tree-based cho defect prediction trong bối cảnh giáo dục SE.
  - Có thể dùng làm nền cho đề tài learning analytics hoặc defect prediction cho project sinh viên.
- **Abstract tiếng Việt:**  
  Bài báo nghiên cứu cách AI, cụ thể là các mô hình học máy dạng cây, có thể hỗ trợ giáo dục Software Engineering thông qua bài toán dự đoán lỗi. Hướng này giúp sinh viên hiểu cách kết hợp dữ liệu phần mềm, metric và mô hình dự đoán để đánh giá chất lượng hoặc rủi ro lỗi trong quá trình phát triển. Bài phù hợp cho nhóm muốn làm thực nghiệm so sánh Decision Tree, Random Forest, XGBoost hoặc các baseline ML khác.

---

## 20. LLM-Based Multi-Agent Systems for Software Engineering: Literature Review, Vision and the Road Ahead

- **Link bài báo:** https://arxiv.org/abs/2404.04834  
- **Link ACM:** https://dl.acm.org/doi/10.1145/3712003  
- **Năm:** 2024 preprint; ACM 2025.
- **Tác giả:** Junda He, Christoph Treude, David Lo.
- **Loại bài:** Literature Review / Vision paper.
- **Lĩnh vực:** LLM-based Multi-Agent Systems for Software Engineering.
- **Phù hợp:** Kỳ 7, 8.
- **Từ khóa:** multi-agent systems, LLM, software engineering, SDLC, autonomous agents.
- **Metadata đáng chú ý:**
  - Review các hệ thống multi-agent dựa trên LLM trong nhiều giai đoạn SDLC.
  - Có case study và agenda nghiên cứu về năng lực agent, phối hợp agent và độ tin cậy.
- **Abstract tiếng Việt:**  
  Bài báo tổng quan và định hướng về hệ thống multi-agent dựa trên LLM cho Software Engineering. Tác giả phân tích cách nhiều agent chuyên biệt có thể phối hợp để xử lý các nhiệm vụ phức tạp trong SDLC như requirement, design, implementation, testing và maintenance. Bài cũng thảo luận các giới hạn hiện tại, case study và hướng phát triển để xây dựng hệ thống multi-agent tự động, mở rộng và đáng tin cậy hơn trong Software Engineering.

---

# Gợi ý dùng danh sách này cho sinh viên

## Kỳ 5

Nên chọn các bài số: 1, 2, 9, 17, 18.

Mục tiêu:

- Đọc tổng quan.
- Làm literature matrix 3–5 bài.
- Tái hiện prototype nhỏ: RAG môn học, AI tutor, dashboard hoặc code review đơn giản.

## Kỳ 6

Nên chọn các bài số: 6, 8, 11, 16, 19.

Mục tiêu:

- Xây baseline.
- Chọn metric.
- So sánh ít nhất 2 phương pháp.
- Viết short paper 4–6 trang.

## Kỳ 7

Nên chọn các bài số: 3, 4, 7, 10, 12, 15, 20.

Mục tiêu:

- Xây contribution.
- Làm proposed method.
- Có ablation study.
- Viết draft paper 6–8 trang.

## Kỳ 8

Nên chọn các bài số: 5, 6, 7, 12, 13, 14, 15, 20.

Mục tiêu:

- Hoàn thiện bài báo.
- Có experiment rõ.
- Có baseline, metric, threats to validity.
- Chuẩn bị submission package.

---

# Gợi ý nhóm chủ đề nghiên cứu từ danh sách bài báo

| Nhóm chủ đề | Bài nền nên đọc |
|---|---|
| RAG cho môn học SE | 17, 18, 15 |
| Code review assistant | 11, 12, 13 |
| Requirement analysis bằng LLM | 16, 1, 2 |
| Multi-agent SDLC | 3, 4, 8, 20 |
| SWE agent sửa issue | 6, 7, 14 |
| Code generation | 9, 10, 15 |
| AI-generated code quality | 12, 13 |
| SE education + AI | 17, 18, 19 |
