---
permalink: /
title: "Tự động hóa quy trình trong thiết kế vi mạch (Flow Automation in IC Design)"
excerpt: "About me"
author_profile: true
redirect_from:

- /about/
- /about.html

---

# 1. THÔNG TIN CHUNG

| Tên Môn Học   | Tự động hóa quy trình trong thiết kế vi mạch <br/>Flow Automation in IC Design |
|---------------|:------:|
| Môn học trước |   Thiết kế Luận lý Số, Thiết kế hệ thống số với HDL   |

# 2. MÔ TẢ MÔN HỌC

**Môn học bao gồm các nội dung sau:**

* Trình bày tổng quan về phương pháp và công cụ được sử dụng trong quy trình thiết kế vi mạch hướng ASIC.
* Cung cấp các kiến thức nền tảng về môi trường thực thi của các công cụ thực hiện các khâu chính trong luồng thiết kế.
* Phân tích quy trình thực hiện và tối ưu hóa thiết kế sử dụng công cụ tổng hợp thiết kế.
* Phân tích quy trình kiểm tra và đánh giá định thời tĩnh thiết kế.

# 3. MỤC TIÊU MÔN HỌC

**Sau khi hoàn thành môn học này, sinh viên có thể:**

* Có kỹ năng tìm hiểu và nghiên cứu giải quyết các bài toán có tính khoa học
* Có kỹ năng phân tích, tổng hợp và tư duy hệ thống
* Kỹ năng giao tiếp thông qua thuyết trình hoặc báo cáo dự án
* Có thái độ và kỹ năng xây dựng ý tưởng, thiết kế, xây dựng và triển khai ứng dụng trong lĩnh vực Kỹ thuật máy tính

# 4. CHUẨN ĐẦU RA MÔN HỌC

| CĐRMH [1] | Mô tả CĐRMH (Mục tiêu cụ thể) [2]                                                                                                | Mức độ giảng dạy[3] |
|-----------|:---------------------------------------------------------------------------------------------------------------------------------|:-------------------:|
| G1.1      | Hiểu được luồng thực hiện thiết kế hướng ASIC sử dụng các công cụ tương ứng, giải quyết được bài toán đặt ra trong thiết kế ASIC |         IT          |
| G1.2      | Có thái độ tích cực trong việc nghiên cứu giải quyết bài toán thiết kế vi mạch                                                   |         IT          |
| G2        | Phân tích định thời tĩnh, kết quả mô phỏng trong quy trình tổng hợp và kiểm tra định thời thiết kế tiêu biểu với ASIC            |         ITU         |
| G3        | Nắm được thuật ngữ chuyên môn, trình bày tài liệu chuyên ngành trong luồng thiết kế vi mạch hướng ASIC.                          |         IT          |
| G4        | Có kỹ năng thiết kế, xây dựng được mạch số theo hướng ASIC]                                                                      |         IT          |

# NỘI DUNG MÔN HỌC, KẾ HOẠCH GIẢNG DẠY
## A. LÝ THUYẾT
### Chương 1: Tìm Hiểu Tổng Quan (Overview)
* 1.1. Quy trình thiết kế vi mạch số
* 1.2. Tổng quan về các công cụ thiết kế số
  * a. VCS + DVE
  * b. Design Compiler
  * c. TestMAX DFT
  * d. Formality
  * e. PrimeTime
  * f. IC Compliler II
  * g. StarRC
  * h. IC Validator

### Chương 2: Mô Phỏng Thiết Kế Luận Lý (Logic Simulation)
* 1.1. VCS + Verdi
* 1.2. UVM

### Chương 3: Tổng Hợp Thiết Kế (Logic Synthesis)
* 3.1. Tổng quan về tổng hợp thiết kế
* 3.2. Design Compiler (DC)
* 3.3. Ràng buộc thiết kế
* 3.4. Thư viện công nghệ
* 3.5. Đọc hiểu reports

### Chương 4: Thiết Kế Vật Lý (Physical Design)
* 4.1. Tổng quan về thiết kế ở mức vật lý
* 4.2. IC Compiler (ICC II)
* 4.3. Floorplanning
* 4.4. Placement
* 4.5. Routing
* 4.6. StarRC

### Chương 5: Phân Tích Định Thời Tĩnh (Static Timing Analysis - STA)
* 5.1 Giới Thiệu
* 5.2 Khái niệm về STA và quy trình thực hiện trong công cụ PrimeTime

### Chương 6: Kiểm tra sau layout (Post-layout Verification)
* 6.1. Tổng quan về kiểm tra thiết kế sau layout
* 6.2. Mô phỏng sau layout
* 6.3. Kiểm tra timing
* 6.4. Kiểm tra khác

### Chương 7: Một số quy trình và công cụ bổ trợ trong thiết kế ASIC
* 7.1. Formality
* 7.2. TestMAX
* 7.3. IC Validator 

## B. THỰC HÀNH
#### [Lab 1: Logic Simulation](labs/lab1-logic-simulator)
#### [Lab 2: Logic Synthesis. Design Compiler](labs/lab2-logic-synthesis) 
#### [Lab 3: Physical Design](labs/lab3-physical-design-icc-ii)
#### [Lab 4: Static Timing Analysis](labs/lab4-sta)
#### [Lab 5: Post Layout Verification](labs/lab5-post-layout-verification)
#### [Lab 6: Flow Automation](labs/lab6-flow-automation)
# TÀI LIỆU HỌC TẬP, THAM KHẢO
* V.Taraate. Digital Logic Design Using Verilog: Coding and RTL Synthesis. Springer; 2016
* A. Reis, R. Drechsler. Advanced Logic Synthesis. Springer. 2017
*  M. Morris, R. Mano, Michael D. Ciletti. Digital Design: With an Introduction to the Verilog HDL, VHDL, and SystemVerilog. 2017
* B. Vranesic. Fundamentals of Digital Logic with VHDL Design. 2017

# CÔNG CỤ HỖ TRỢ THỰC HÀNH
* [Synopsys EDA tools](#)