# Đây là cấu trúc của CLB Sinno 

# I. Structure
1. Bộ quản trị: chứa cấu trúc của đầu não quản lý CLB Sinno
2. Môi trường CLB: chứa cấu trúc tổ chức của môi trường CLB.

Bộ quản trị và Môi trường CLB là hai thành phần tồn tại song song với nhau. Hai thành phần này phụ thuộc lẫn nhau.
* Bộ quản trị: điều khiển __VẬN HÀNH__ và __PHÁT TRIỂN__ môi trường CLB.
* Môi trường CLB: quyết định sự tồn tại của bộ quản trị.

Tại sao lại chia như vậy? kinh nghiệm quản lý CLB của tôi cho thấy hai thành phần này trước kia thường không được phân tách rõ ràng. Ban quản trị và Môi trường CLB luôn rât xa rời nhau. Điều đó dẫn tới việc __VẬN HÀNH__ và __PHÁT TRIỂN__ môi trường CLB trở nên sai lệch, thiếu thực tế với Môi trường CLB. Hậu qủa là sự sụp đổ không thể tránh khỏi của Môi trường CLB và cuối cùng là sự sụp đổ của Ban quản trị. Bộ quản trị quyết định môi trường CLB và môi trường CLB quyết định bộ quản trị. Đây là hai thực thể ngang bằng nhau và không thể tách rời.

Ban đầu bộ quản trị CLB làm như thế nào? Bộ quản trị quyết định môi trường CLB theo một cách áp đặt từ trên xuống. Liệu có ai chịu tìm hiểu môi trường CLB? lười biếng, ảo tưởng là đã hiểu, .... Thực tế là chả có ai tìm hiểu môi trường CLB rõ ràng cả. Điều này đã được chứng minh rất rõ ràng và rất nhiều lần qua các quyết định rất xa vời thực tế dẫn tới sự sụp đổ của ban chuyên môn, sự rời rạc ngày một mạnh mẽ giữa các ban. Bộ quản trị - một cai chủ vọt những đòn roi xuống người nô lệ - môi trường CLB - một cách dã man. Người nô lệ không thể bê được 50kg bông nhưng cai chủ cứ vụt để ép người nô lê bê được 50kg. Kết cục sẽ ra sao ư? hoặc là sự nổi dậy chống lại bất công của người nô lệ, hoặc là cái chết của người nô lệ. Đây là thực trạng đớn đau của CLB Sinno.

Bây giờ phải thay đổi, Bộ quản trị và Môi trường CLB là hai thực thể quyền lực ngang bằng nhau. Bộ quản trị phải hiểu Môi trường CLB để đưa ra các chính sách phù hợp. Khi đó, Môi trường CLB mới làm theo.

# II. Index
1. Bộ quản trị 
    * Mô hình quản trị
    * Con người quản trị
2. Môi trường CLB
    * Cách xác định những người không hiểu môi trường CLB.
    * Cách xác định những người hiểu môi trường CLB.
    * Core values
    * Các ban trong CLB

# III. Bộ quản trị


# IV. Môi trường CLB
1. Cách xác định những người không hiểu môi trường CLB
* Bất kỳ ai khẳng định mình hiểu CLB: "tôi hiểu CLB", "CLB đang hoạt động ổn", "CLB đang hoạt động không ổn", ...
* Bất kỳ ai chỉ ngồi nói những thứ hoang đường.

2. Cách xác định những người hiểu môi trường CLB.
* Bất kỳ ai đưa ra được nhận định sâu: "Ban chuyên môn có hoạt động seminar fail là tại vì cơ bản mọi người vào CLB là để được thử sức với các dự án, sử dụng các kiến thức trên trường họ đã học. Seminar do đó không phù hợp với tâm nguyện của các thành viên. Hơn nữa, chả ai thích ghi chép cả. Hoạt động seminar sẽ fail không sớm thì muộn".
* Bất kỳ ai thừa nhận họ không hiểu hết CLB: "tôi vẫn chưa hiểu đủ môi trường CLB", ...
* Bất kỳ ai làm, thay vì chỉ ngồi nói.
