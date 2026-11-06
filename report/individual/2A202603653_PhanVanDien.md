Bài toán bốn thế hệ AI lọc tin nhắn rác
Phần 0 cài đặt & khám phá dữ liệu
phần 1 machine learning: "người chọn feature máy học trọng số"
-vector hóa (bag-of-words)
-sigmoid & dự đoán xác suất
- huấn luyện bằng gradient descent 
- accuracy chưa đủ khi dữ liệu lệch 
phần 2 deep learning : mạng nơ-ron tựu học đặc trưng
- logistic regression
-pytorch
- train 30 epoch theo dõi train loss & val loss
- bỏ ReLU
phần 3 embedding : biến câu thành" điểm trên bản đồ nghĩa"
Model: sentence-transformers/all-MiniLM-L6-v2 (~90MB, encoder-only như BERT )
-cosine similarity
-tìm k tin nhắn gần nghĩa nhất 
- tìm kiếm theo nghĩa
- knn: "hàng xóm gần nhất bỏ phiếu"
Phần 4 llm không train , chỉ cần prompt
CHỌN NHÀ CUNG CẤP LLM: "openai" | "anthropic" | "gemini" | "groq" | "openrouter" | "ollama"
call_openai (cùng tên + tham số với template LLM API)
Prompt phân loại (zero-shot / few-shot)
Đọc nhãn từ câu trả lời (LLM không phải lúc nào cũng nghe lời!)
Phân loại cả loạt + đo chi phí

Dùng 2 model của provider bạn chọn (mặc định gpt-6.1-terra vs gpt-6-luna)

Phần 5: Tổng hợp & nộp bài 
biểu đồ đánh đổi: 1-F1 <-> độ trễ
stress test : 50 case khó 
viết test case 
