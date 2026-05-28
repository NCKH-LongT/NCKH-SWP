# KỲ 5 — READ & REPRODUCE  
## Hướng dẫn sinh viên tự nghiên cứu khoa học trong ngành Software Engineering

---

## 1. Mục tiêu của kỳ 5

Kỳ 5 là giai đoạn **làm quen với nghiên cứu khoa học**. Sinh viên chưa cần tạo ra đóng góp nghiên cứu lớn, nhưng phải biết:

1. Đọc và hiểu một bài báo khoa học cơ bản.
2. Xác định vấn đề mà bài báo giải quyết.
3. Tái hiện lại một phần hệ thống, mô hình hoặc ý tưởng trong bài báo.
4. Làm prototype nhỏ có thể chạy được.
5. Viết báo cáo nghiên cứu ngắn theo cấu trúc khoa học.

Mục tiêu cuối kỳ:

> Sinh viên hiểu được một vấn đề nghiên cứu, đọc được bài báo liên quan, làm lại một phần giải pháp, và trình bày được kết quả bằng báo cáo + demo.

---

## 2. Tư duy chính của kỳ 5

Ở kỳ này, sinh viên không làm project theo kiểu “em làm một app”, mà phải học cách diễn đạt thành:

```text
Vấn đề là gì?
Ai gặp vấn đề này?
Bài báo trước đã giải quyết như thế nào?
Em tái hiện lại phần nào?
Kết quả chạy thử ra sao?
Hạn chế còn lại là gì?
```

Ví dụ:

| Làm project thông thường | Chuyển thành hướng nghiên cứu |
|---|---|
| Làm chatbot hỏi đáp PDF | Tái hiện hệ thống RAG đơn giản cho tài liệu môn học |
| Làm dashboard IoT | Tái hiện hệ thống giám sát cảm biến và cảnh báo |
| Làm app quản lý bài tập | Phân tích workflow hỗ trợ quản lý học tập nhóm |
| Làm web quản lý sinh viên | Xây prototype hỗ trợ learning analytics cơ bản |

---

## 3. Kỹ thuật nghiên cứu cần học

### 3.1. Đọc bài báo khoa học

Mỗi nhóm cần đọc tối thiểu **5 bài báo**.

Khi đọc một bài báo, không cần dịch toàn bộ. Chỉ cần trả lời các câu hỏi:

| Thành phần | Câu hỏi cần trả lời |
|---|---|
| Title | Bài này nói về vấn đề gì? |
| Abstract | Mục tiêu, phương pháp, kết quả chính là gì? |
| Introduction | Vì sao vấn đề này quan trọng? |
| Related Work | Các hướng trước đó là gì? |
| Method | Tác giả làm bằng cách nào? |
| Experiment | Tác giả kiểm tra bằng dữ liệu/metric gì? |
| Result | Kết quả tốt ở điểm nào? |
| Limitation | Bài còn hạn chế gì? |

### 3.2. Tái hiện ý tưởng

Kỳ 5 chỉ cần tái hiện một phần nhỏ. Ví dụ:

| Loại bài báo | Phần có thể tái hiện |
|---|---|
| RAG/Chatbot | Upload PDF, chunking, embedding, hỏi đáp |
| IoT | Đọc dữ liệu sensor giả lập, hiển thị dashboard |
| AI grading | Chấm thử một bài bằng rubric đơn giản |
| Bug classification | Phân loại bug bằng keyword hoặc ML đơn giản |
| Learning analytics | Dashboard thống kê điểm, tiến độ, cảnh báo |

### 3.3. Viết báo cáo nghiên cứu ngắn

Báo cáo không cần dài, nhưng phải có cấu trúc nghiên cứu:

```text
1. Introduction
2. Problem Statement
3. Related Work Summary
4. Reproduced Method
5. Prototype Design
6. Demo and Initial Result
7. Limitation
8. Conclusion
```

---

## 4. Input sinh viên cần chuẩn bị

| Input | Yêu cầu |
|---|---|
| Chủ đề nghiên cứu | Do nhóm chọn trong danh sách gợi ý hoặc đề xuất riêng |
| 3 bài báo liên quan | Ưu tiên bài có hệ thống, mô hình, ứng dụng rõ |
| Dataset nhỏ | Có thể dùng dữ liệu giả lập, dữ liệu public, dữ liệu tự tạo |
| Starter code | Có thể dùng framework web/API/notebook |
| Template báo cáo | Theo mẫu của giảng viên |
| GitHub repository | Mỗi nhóm có một nhánh riêng |

---

## 5. Output cuối kỳ

Mỗi nhóm phải nộp:

| Output | Mô tả |
|---|---|
| `problem_statement.md` | Mô tả vấn đề, người dùng, bối cảnh |
| `literature_matrix.xlsx` hoặc `.md` | Bảng tổng hợp 3–5 bài báo |
| `prototype/` | Source code chạy được |
| `demo_video_link.md` | Link video demo 3–5 phút |
| `mini_research_report.md` | Báo cáo 5–8 trang |
| `reflection.md` | Nhóm tự đánh giá học được gì, hạn chế gì |

---

## 6. Chủ đề gợi ý cho kỳ 5

### 6.1. AI for Education

| Mã đề tài | Chủ đề | Mô tả |
|---|---|---|
| K5-EDU-01 | Chatbot hỏi đáp tài liệu môn học | Sinh viên upload PDF môn học, hệ thống trả lời câu hỏi |
| K5-EDU-02 | Dashboard tiến độ học tập | Hiển thị điểm, deadline, task, cảnh báo trễ |
| K5-EDU-03 | AI gợi ý tài liệu học | Gợi ý tài liệu theo chủ đề sinh viên yếu |
| K5-EDU-04 | Phân loại feedback sinh viên | Phân loại feedback theo chủ đề/tích cực/tiêu cực |

### 6.2. AI for Software Engineering

| Mã đề tài | Chủ đề | Mô tả |
|---|---|---|
| K5-SE-01 | Phân loại bug đơn giản | Dùng keyword hoặc ML cơ bản để phân loại bug |
| K5-SE-02 | Tool kiểm tra requirement | Phát hiện requirement thiếu actor, action, object |
| K5-SE-03 | Sinh test case cơ bản | Dùng template hoặc LLM để sinh test case |
| K5-SE-04 | Code complexity dashboard | Đọc source code và hiển thị complexity đơn giản |

### 6.3. AIoT / Smart System

| Mã đề tài | Chủ đề | Mô tả |
|---|---|---|
| K5-IOT-01 | Dashboard giám sát sensor | Hiển thị nhiệt độ, độ ẩm, cảnh báo |
| K5-IOT-02 | Cảnh báo threshold | Nếu sensor vượt ngưỡng thì cảnh báo |
| K5-IOT-03 | Smart farm mini | Theo dõi nhiệt độ, pH, độ ẩm giả lập |
| K5-IOT-04 | Energy monitoring dashboard | Theo dõi điện năng tiêu thụ giả lập |

### 6.4. RAG / Document AI

| Mã đề tài | Chủ đề | Mô tả |
|---|---|---|
| K5-RAG-01 | RAG hỏi đáp quy chế | Hỏi đáp tài liệu quy chế/syllabus |
| K5-RAG-02 | Tóm tắt PDF môn học | Upload PDF và tóm tắt nội dung |
| K5-RAG-03 | Tìm kiếm semantic tài liệu | Tìm đoạn liên quan bằng embedding |
| K5-RAG-04 | Hỏi đáp FAQ khoa/ngành | Tạo chatbot FAQ đơn giản |

---

## 7. Timeline 15 tuần

| Tuần | Việc cần làm | Output |
|---|---|---|
| 1 | Giới thiệu nghiên cứu khoa học ứng dụng trong SE | Nhóm được tạo |
| 2 | Chọn chủ đề và vai trò nhóm | `team_profile.md` |
| 3 | Tìm 3 bài báo liên quan | Danh sách paper |
| 4 | Đọc và tóm tắt bài báo 1 | `paper_1_summary.md` |
| 5 | Đọc và tóm tắt bài báo 2–3 | `paper_2_summary.md`, `paper_3_summary.md` |
| 6 | Làm literature matrix | `literature_matrix.md` |
| 7 | Viết problem statement | `problem_statement.md` |
| 8 | Thiết kế prototype | Architecture draft |
| 9 | Cài đặt prototype lần 1 | Source code version 1 |
| 10 | Cài đặt prototype lần 2 | Source code version 2 |
| 11 | Chạy demo thử | Demo internal |
| 12 | Ghi nhận kết quả ban đầu | `initial_result.md` |
| 13 | Viết mini report | Draft report |
| 14 | Peer review giữa các nhóm | Review comments |
| 15 | Final demo và nộp | Full package |

---

## 8. Cấu trúc thư mục GitHub

```text
K5_GROUP_<class>_<group_id>/
├── README.md
├── team_profile.md
├── 01_problem/
│   └── problem_statement.md
├── 02_literature/
│   ├── paper_1_summary.md
│   ├── paper_2_summary.md
│   ├── paper_3_summary.md
│   └── literature_matrix.md
├── 03_prototype/
│   ├── architecture.md
│   └── src/
├── 04_result/
│   └── initial_result.md
├── 05_report/
│   └── mini_research_report.md
└── 06_demo/
    └── demo_video_link.md
```

---

## 9. Template problem statement

```markdown
# Problem Statement

## 1. Background
Mô tả bối cảnh của vấn đề.

## 2. Target Users
Ai là người dùng chính?

## 3. Problem
Người dùng đang gặp khó khăn gì?

## 4. Existing Solutions
Các bài báo/hệ thống trước đã làm gì?

## 5. Limitation of Existing Solutions
Các hướng trước còn hạn chế gì?

## 6. Proposed Prototype
Nhóm dự kiến tái hiện hoặc xây dựng prototype gì?

## 7. Expected Output
Prototype sẽ nhận input gì và trả output gì?
```

---

## 10. Template literature matrix

| Paper | Year | Problem | Method | Dataset | Metric | Result | Limitation | Ý tưởng nhóm học được |
|---|---:|---|---|---|---|---|---|---|
| Paper 1 | 2024 |  |  |  |  |  |  |  |
| Paper 2 | 2023 |  |  |  |  |  |  |  |
| Paper 3 | 2022 |  |  |  |  |  |  |  |

---

## 11. Rubric đánh giá kỳ 5

| Tiêu chí | Điểm |
|---|---:|
| Hiểu vấn đề và bài báo | 20 |
| Literature matrix rõ ràng | 15 |
| Problem statement hợp lý | 15 |
| Prototype chạy được | 25 |
| Demo rõ ràng | 10 |
| Báo cáo có cấu trúc nghiên cứu | 15 |
| Tổng | 100 |

---

## 12. Checklist trước khi nộp

- [ ] Có ít nhất 3 bài báo liên quan.
- [ ] Có literature matrix.
- [ ] Có problem statement rõ.
- [ ] Prototype chạy được.
- [ ] Có README hướng dẫn chạy.
- [ ] Có demo video.
- [ ] Có báo cáo 5–8 trang.
- [ ] Có nêu hạn chế trung thực.
- [ ] Có mô tả hướng phát triển cho kỳ 6.

---

## 13. Chuẩn đầu ra kỳ 5

Sau kỳ 5, nhóm cần đạt được năng lực:

```text
Đọc hiểu bài báo cơ bản
Tóm tắt được vấn đề và phương pháp
Tái hiện được một phần hệ thống
Làm prototype chạy được
Viết báo cáo nghiên cứu ngắn
Nhận diện được hạn chế/gap ban đầu
```

---

## 14. Điều kiện để nhóm được khuyến khích lên mức viết paper sớm

Nhóm kỳ 5 có thể được chọn làm paper sớm nếu đạt các điều kiện:

| Điều kiện | Mức yêu cầu |
|---|---|
| Prototype | Chạy ổn định |
| Dataset | Có dữ liệu thật hoặc dữ liệu tự thu thập tốt |
| Related work | Từ 5 bài trở lên |
| Kết quả | Có bảng đo thử ban đầu |
| Đề tài | Có tính ứng dụng rõ |
| Nhóm | Có khả năng viết và tiếp tục phát triển |

Nếu đạt, nhóm có thể chuyển sang hướng kỳ 6 nâng cao: thêm baseline, metric và experiment.
