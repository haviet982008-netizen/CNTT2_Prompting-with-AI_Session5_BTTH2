1. Quy trình 

Quy trình gồm ba lượt riêng biệt: phân tích khách hàng → lập dàn ý → viết bài PR. Không yêu cầu AI thực hiện cả ba bước trong một lượt.

Quy định chung: viết bằng tiếng Việt, giọng điệu chuyên nghiệp và tin cậy. Không tự tạo số liệu hiệu quả, khách hàng tiêu biểu, chứng nhận hoặc tính năng chưa được cung cấp.

2. Prompt 1: Phân tích khách hàng và pain points

Bạn là chuyên viên nghiên cứu khách hàng cho sản phẩm AI Chatbot doanh nghiệp.

Đầu vào bắt buộc: 
- Tên sản phẩm, doanh nghiệp cung cấp và mô tả AI Chatbot.
- Tính năng, lợi ích và giới hạn đã được xác nhận.
- Tài liệu sản phẩm, dữ liệu khách hàng hoặc nghiên cứu thị trường hiện có.
- Từ khóa chính, từ khóa phụ và hành động CTA mong muốn.
- Kênh liên hệ hoặc đường dẫn CTA đã xác nhận.

Nhiệm vụ:
 
  1. Đọc thông tin sản phẩm và tài liệu được cung cấp. Xác định nhóm khách hàng mục tiêu, người quyết định mua và nhu cầu sử dụng.
  2. Xác định 3–5 pain points chính. Với mỗi pain point, nêu biểu hiện, ảnh hưởng đến doanh nghiệp và tính năng đã xác nhận có thể hỗ trợ giải quyết.
  3. Phân biệt thông tin có nguồn với giả thuyết cần kiểm chứng. Không trình bày suy đoán về thị trường như sự thật.
  4. Chọn nhóm khách hàng trọng tâm và thông điệp chính cho bài PR. Nếu thiếu dữ liệu thiết yếu về sản phẩm, hỏi bổ sung và chưa chuyển bước.

3.Prompt 2: Xây dựng dàn ý chi tiết

Bạn là biên tập viên nội dung PR sản phẩm công nghệ.

Đầu vào bắt buộc:

[OUTPUT_PROMPT_1], là toàn bộ JSON đã kiểm tra từ Prompt 1.

Nhiệm vụ:
  1. Dựa trên nhóm khách hàng, pain points và thông điệp đã xác định để lập dàn ý cho bài khoảng 1.200 từ, trong giới hạn 1.000–1.500 từ.
  2. Xây dựng một Headline chứa từ khóa chính tự nhiên; Lead mở bằng vấn đề của khách hàng; các mục H2, H3 triển khai vấn đề, giải pháp, cách ứng dụng và giới hạn; kết thúc bằng CTA đã xác nhận.
  3. Mỗi mục cần có mã riêng, luận điểm, mã pain point liên quan, thông tin sản phẩm được dùng và từ khóa phù hợp. Tránh hai mục cùng lặp lại một ý.
  4. Phân bổ dung lượng: Lead 120 từ, bốn mục H2 mỗi mục 250 từ, CTA 80 từ. Nội dung H3 nằm trong dung lượng H2 cha, không cộng thêm. Tổng phần nội dung là 1.200 từ.
  5. Không biến giả thuyết thành khẳng định hoặc bổ sung tính năng ngoài dữ liệu bước 1.

4.Prompt 3: Viết bài PR và tối ưu SEO

Bạn là người viết bài PR về giải pháp AI Chatbot cho doanh nghiệp.

Đầu vào bắt buộc: 

[OUTPUT_PROMPT_2], gồm dàn ý và trường research chứa toàn bộ kết quả bước 1. Nếu thiếu dàn ý hoặc ngữ cảnh sản phẩm, yêu cầu cung cấp lại trước khi viết.

Nhiệm vụ:
- Triển khai lần lượt Headline, Lead, các H2/H3 và CTA đúng thứ tự dàn ý. Viết bài hoàn chỉnh trong khoảng 1.000–1.500 từ, hướng đến 1.200 từ; quy ước đếm theo đơn vị phân cách bằng khoảng trắng.
- Dùng tiêu đề H1 cho Headline, H2/H3 cho các phần nội dung. Lead cần nêu pain point trọng tâm và dẫn vào giải pháp.
- Đặt từ khóa chính tự nhiên trong Headline, Lead, ít nhất một H2 và phần kết; phân bổ từ khóa phụ đúng ngữ cảnh, không nhồi nhét.
- Giữ nguyên giọng chuyên nghiệp, tin cậy; thống nhất tên sản phẩm và cách gọi khách hàng. Mỗi phần phát triển một ý riêng, có liên kết với phần trước.
- Chỉ dùng tính năng và bằng chứng đã xác nhận. Nếu đưa tình huống giả định, phải ghi rõ là ví dụ minh họa. Không hứa hẹn hiệu quả tuyệt đối hoặc bịa số liệu để tăng sức thuyết phục.
- CTA cuối bài nêu rõ hành động và kênh thực hiện từ dữ liệu đầu vào; không tạo đường dẫn mới.
- Trước khi kết thúc, rà soát độ dài, cấu trúc SEO, ý trùng lặp, dữ kiện và giọng điệu. Chỉ xuất bài viết Markdown, không thêm báo cáo kiểm tra hoặc lời dẫn ngoài bài.

5. Ràng buộc

Khi viết bài, lưu dàn ý, toàn bộ phần đã nhận, mục đang viết và vị trí ký tự bị ngắt. Dùng lệnh sau để tiếp tục Prompt 3 khi bị ngắt quãng, không tạo thêm bước nội dung mới:

Tiếp tục bài PR đang bị ngắt với ngữ cảnh sau:
- Dàn ý và nghiên cứu đã duyệt: [OUTPUT_PROMPT_2].
- Toàn bộ văn bản đã nhận, giữ nguyên ký tự cuối: [VĂN_BẢN_ĐÃ_CÓ].
- Mục đang viết: [MÃ_MỤC].
- Số từ đã viết: [SỐ_TỪ_ĐÃ_VIẾT].
Chỉ xuất phần văn bản còn thiếu để nối trực tiếp sau ký tự cuối của bản hiện tại. Nếu đang dở câu hoặc dở từ, hoàn thành đúng phần còn thiếu trước khi viết tiếp. Không lặp đoạn đã có, không mở đầu bằng “Tiếp theo”, không chèn lại tiêu đề đang viết và không tự thêm xuống dòng tại điểm nối.

Giữ nguyên tên sản phẩm, dữ kiện, từ khóa, dàn ý và giọng chuyên nghiệp, tin cậy. Hoàn thành các phần chưa viết, chỉ đặt CTA ở cuối bài. Tổng bài sau khi ghép phải đạt 1.000–1.500 từ, không phải riêng phần viết tiếp. Nếu thiếu văn bản cuối hoặc không xác định được điểm nối, yêu cầu gửi lại, không tự đoán.

Sau khi ghép, kiểm tra câu tại điểm nối để loại bỏ từ trùng, từ thiếu, khoảng trắng hoặc dấu câu sai; đối chiếu lại tiêu đề và độ dài toàn bài. Chỉ dùng lệnh “tiếp tục” mà không cung cấp ngữ cảnh không đủ bảo đảm nối đúng.

Quy trình gồm ba lượt riêng biệt: phân tích khách hàng → lập dàn ý → viết bài PR. Không thực hiện cả ba bước trong một lượt.

Quy định chung: viết bằng tiếng Việt, giọng điệu chuyên nghiệp và tin cậy. Không tự tạo số liệu hiệu quả, khách hàng tiêu biểu, chứng nhận hoặc tính năng chưa được cung cấp.
