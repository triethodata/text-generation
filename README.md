# Text Generation Project
## Mô tả project
Text Generation là một trong các dạng bài toán thuộc lĩnh vực xử lý ngôn ngữ tự nhiên hiện đang rất được cộng đồng quan tâm, với khả năng tạo ra các câu từ mới dựa trên dữ liệu đầu vào. Chính bởi các kết quả trả về mang tính "sáng tạo", đáp ứng được các nhu cầu bài toán khác nhau từ mô hình này mà nó đã và đang được ứng dụng vào các sản phẩm nổi tiếng hiện nay, điển hình nhất chính là ChatGPT, một ứng dụng Chatbot đã tạo nên cơn sốt trên toàn thế giới thời gian qua.
![image](https://github.com/triethodata/text-generation/assets/128765957/5a469660-19e2-4fed-b9e9-10cadd2a730b)

## Bài toán Sinh thơ theo thể ngũ ngôn
Trong project này, chúng ta sẽ cùng triển khai một chương trình sử dụng mô hình Text Generation với chủ đề sinh thơ theo thể thơ ngũ ngôn (thơ 5 chữ) Tiếng Việt dựa vào một dòng thơ đầu vào từ người dùng.

Như vậy, Input/Output của chương trình là:
- Input: Một chuỗi gồm 5 từ (tượng trưng cho dòng đầu tiên của bài thơ).
- Output: n dòng thơ tiếp theo (n tùy chọn).
- Với mô hình sinh thơ, ta sẽ xây dựng theo mô hình transformer (sử dụng cả 2 phần encoder và decoder).

Kiến trúc mô hình transformer được mô tả theo ảnh dưới đây:
![image](https://github.com/triethodata/text-generation/assets/128765957/bd668297-4cc0-4efb-9809-389379ee1b9b)
