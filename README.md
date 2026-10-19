TỔNG QUAN
=========

Bộ dữ liệu này (ml-latest-small) mô tả hoạt động đánh giá phim theo thang 5 sao và gắn thẻ bằng văn bản tự do trên MovieLens (http://movielens.org), một dịch vụ gợi ý phim. Bộ dữ liệu gồm 100.836 lượt đánh giá và 3.683 lượt gắn thẻ cho 9.742 bộ phim. Dữ liệu được tạo bởi 610 người dùng trong khoảng thời gian từ ngày 29/03/1996 đến ngày 24/09/2018. Bộ dữ liệu được tạo ra vào ngày 26/09/2018.

Những người dùng được chọn ngẫu nhiên để đưa vào bộ dữ liệu. Mỗi người dùng được chọn đều đã đánh giá ít nhất 20 bộ phim. Bộ dữ liệu không chứa thông tin nhân khẩu học. Mỗi người dùng chỉ được biểu diễn bằng một mã định danh (ID), không có thêm thông tin nào khác.

Dữ liệu được lưu trong các tệp `links.csv`, `movies.csv`, `ratings.csv` và `tags.csv`. Nội dung và cách sử dụng từng tệp được trình bày chi tiết ở các phần bên dưới.

Đây là bộ dữ liệu dành cho mục đích *phát triển*. Do đó, nội dung có thể thay đổi theo thời gian và không phù hợp để sử dụng làm bộ dữ liệu chuẩn khi công bố những kết quả nghiên cứu cần so sánh. Nếu có mục đích đó, hãy tham khảo những bộ dữ liệu *benchmark* (chuẩn đánh giá) hiện có.

Có thể tải miễn phí công khai bộ dữ liệu này và các bộ dữ liệu GroupLens khác tại: http://grouplens.org/datasets/


GIẤY PHÉP SỬ DỤNG
=================

Đại học Minnesota cũng như các nhà nghiên cứu tham gia không bảo đảm tính chính xác của dữ liệu, mức độ phù hợp của dữ liệu cho bất kỳ mục đích cụ thể nào, hoặc tính hợp lệ của các kết quả thu được từ việc sử dụng bộ dữ liệu. Bộ dữ liệu có thể được sử dụng cho mục đích nghiên cứu với các điều kiện sau:

* Người sử dụng không được tuyên bố hoặc ngụ ý rằng Đại học Minnesota hay Nhóm nghiên cứu GroupLens chứng thực hoặc ủng hộ công trình của mình.
* Người sử dụng phải ghi nhận việc sử dụng bộ dữ liệu trong những ấn phẩm được tạo ra từ bộ dữ liệu này (xem thông tin trích dẫn bên dưới).
* Người sử dụng được phép phân phối lại bộ dữ liệu, kể cả các phiên bản đã biến đổi, với điều kiện vẫn áp dụng các điều khoản giấy phép này.
* Người sử dụng không được dùng thông tin này cho bất kỳ mục đích thương mại hoặc tạo doanh thu nào nếu chưa được một giảng viên thuộc Dự án nghiên cứu GroupLens tại Đại học Minnesota cho phép.
* Các tập lệnh phần mềm thực thi được cung cấp theo nguyên trạng ("as is"), không kèm bất kỳ bảo đảm nào, dù rõ ràng hay ngụ ý, bao gồm nhưng không giới hạn ở bảo đảm ngụ ý về khả năng thương mại và sự phù hợp cho một mục đích cụ thể. Người sử dụng tự chịu toàn bộ rủi ro liên quan đến chất lượng và hiệu năng của các tập lệnh này. Nếu chương trình có lỗi, người sử dụng tự chịu mọi chi phí bảo trì, sửa chữa hoặc khắc phục cần thiết.

Trong mọi trường hợp, Đại học Minnesota, các đơn vị liên kết hoặc nhân viên của trường không chịu trách nhiệm đối với bất kỳ thiệt hại nào phát sinh từ việc sử dụng hoặc không thể sử dụng những chương trình này (bao gồm nhưng không giới hạn ở việc mất dữ liệu hoặc dữ liệu trở nên không chính xác).

Nếu có câu hỏi hoặc ý kiến, vui lòng gửi email tới: grouplens-info@umn.edu


TRÍCH DẪN
=========

Khi sử dụng bộ dữ liệu trong các công bố khoa học, vui lòng trích dẫn bài báo sau:

> F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. https://doi.org/10.1145/2827872


THÔNG TIN THÊM VỀ GROUPLENS
===========================

GroupLens là một nhóm nghiên cứu thuộc Khoa Khoa học Máy tính và Kỹ thuật, Đại học Minnesota. Kể từ khi thành lập vào năm 1992, các dự án nghiên cứu của GroupLens đã tìm hiểu nhiều lĩnh vực, bao gồm:

* Hệ thống gợi ý
* Cộng đồng trực tuyến
* Công nghệ di động và công nghệ hiện diện khắp nơi (ubiquitous computing)
* Thư viện số
* Hệ thống thông tin địa lý địa phương

GroupLens Research vận hành MovieLens, một hệ thống gợi ý phim dựa trên lọc cộng tác (collaborative filtering), cũng chính là nguồn cung cấp bộ dữ liệu này. Bạn có thể truy cập http://movielens.org để trải nghiệm! Nếu có ý tưởng thú vị về những nghiên cứu thử nghiệm có thể thực hiện trên MovieLens, hãy gửi email đến grouplens-info@cs.umn.edu. Nhóm luôn quan tâm đến việc hợp tác với các đối tác bên ngoài.


NỘI DUNG VÀ CÁCH SỬ DỤNG CÁC TỆP
================================

Định dạng và mã hóa
-------------------

Các tệp dữ liệu có định dạng CSV (các giá trị phân cách bằng dấu phẩy: http://en.wikipedia.org/wiki/Comma-separated_values), với một dòng tiêu đề ở đầu tệp. Những trường chứa dấu phẩy (`,`) được đặt trong dấu nháy kép (`"`). Các tệp sử dụng bảng mã UTF-8. Nếu các ký tự có dấu trong tên phim hoặc giá trị thẻ (ví dụ: Misérables, Les (1995)) hiển thị sai, hãy đảm bảo trình soạn thảo văn bản, cửa sổ dòng lệnh hoặc chương trình đọc dữ liệu được thiết lập sử dụng UTF-8.


Mã người dùng (User IDs)
-----------------------

Người dùng MovieLens được chọn ngẫu nhiên để đưa vào bộ dữ liệu. Mã định danh của họ đã được ẩn danh. Mã người dùng nhất quán giữa `ratings.csv` và `tags.csv`, nghĩa là một mã giống nhau trong hai tệp sẽ chỉ cùng một người dùng.


Mã phim (Movie IDs)
------------------

Bộ dữ liệu chỉ bao gồm những bộ phim có ít nhất một lượt đánh giá hoặc một thẻ. Mã phim nhất quán với mã được sử dụng trên trang web MovieLens (ví dụ: mã `1` tương ứng với https://movielens.org/movies/1). Mã phim cũng nhất quán giữa `ratings.csv`, `tags.csv`, `movies.csv` và `links.csv`, nghĩa là một mã giống nhau trong cả bốn tệp sẽ chỉ cùng một bộ phim.


Cấu trúc dữ liệu đánh giá (ratings.csv)
--------------------------------------

Tất cả lượt đánh giá được lưu trong tệp `ratings.csv`. Mỗi dòng sau dòng tiêu đề thể hiện một lượt đánh giá của một người dùng đối với một bộ phim, theo định dạng:

    userId,movieId,rating,timestamp

Các dòng được sắp xếp trước tiên theo `userId`, sau đó theo `movieId` trong phạm vi mỗi người dùng.

Điểm đánh giá sử dụng thang 5 sao, với bước tăng 0,5 sao (từ 0,5 đến 5,0 sao).

`timestamp` biểu thị số giây tính từ 00:00:00 ngày 01/01/1970 theo giờ Phối hợp Quốc tế (UTC).


Cấu trúc dữ liệu thẻ (tags.csv)
------------------------------

Tất cả thẻ được lưu trong tệp `tags.csv`. Mỗi dòng sau dòng tiêu đề thể hiện một thẻ do một người dùng gắn cho một bộ phim, theo định dạng:

    userId,movieId,tag,timestamp

Các dòng được sắp xếp trước tiên theo `userId`, sau đó theo `movieId` trong phạm vi mỗi người dùng.

Thẻ (tag) là dữ liệu mô tả phim do người dùng tạo ra. Mỗi thẻ thường là một từ hoặc một cụm từ ngắn. Ý nghĩa, giá trị và mục đích của thẻ do từng người dùng quyết định.

`timestamp` biểu thị số giây tính từ 00:00:00 ngày 01/01/1970 theo giờ Phối hợp Quốc tế (UTC).


Cấu trúc dữ liệu phim (movies.csv)
---------------------------------

Thông tin phim được lưu trong tệp `movies.csv`. Mỗi dòng sau dòng tiêu đề thể hiện một bộ phim, theo định dạng:

    movieId,title,genres

Tên phim được nhập thủ công hoặc nhập từ https://www.themoviedb.org/ và có kèm năm phát hành trong ngoặc đơn. Các tên phim có thể tồn tại lỗi hoặc sự không nhất quán.

Các thể loại được ngăn cách bằng ký tự gạch đứng (`|`). Danh sách các thể loại gồm:

* Action — Hành động
* Adventure — Phiêu lưu
* Animation — Hoạt hình
* Children's — Thiếu nhi
* Comedy — Hài
* Crime — Tội phạm
* Documentary — Phim tài liệu
* Drama — Chính kịch / Tâm lý
* Fantasy — Kỳ ảo
* Film-Noir — Phim đen (Film Noir)
* Horror — Kinh dị
* Musical — Phim ca nhạc
* Mystery — Bí ẩn
* Romance — Lãng mạn
* Sci-Fi — Khoa học viễn tưởng
* Thriller — Giật gân
* War — Chiến tranh
* Western — Cao bồi / Miền Tây
* (no genres listed) — Chưa liệt kê thể loại

Lưu ý: Phần trước dấu gạch ngang là nhãn thể loại gốc trong CSV, cần giữ nguyên khi đọc và xử lý dữ liệu bằng code.


Cấu trúc dữ liệu liên kết (links.csv)
------------------------------------

Các mã định danh để liên kết phim với những nguồn dữ liệu khác được lưu trong tệp `links.csv`. Mỗi dòng sau dòng tiêu đề thể hiện một bộ phim, theo định dạng:

    movieId,imdbId,tmdbId

`movieId` là mã phim được sử dụng trên https://movielens.org. Ví dụ: phim Toy Story có đường dẫn https://movielens.org/movies/1.

`imdbId` là mã phim được sử dụng trên http://www.imdb.com. Ví dụ: phim Toy Story có đường dẫn http://www.imdb.com/title/tt0114709/.

`tmdbId` là mã phim được sử dụng trên https://www.themoviedb.org. Ví dụ: phim Toy Story có đường dẫn https://www.themoviedb.org/movie/862.

Việc sử dụng các nguồn dữ liệu nói trên phải tuân thủ điều khoản của từng nhà cung cấp.


KIỂM ĐỊNH CHÉO (CROSS-VALIDATION)
================================

Những phiên bản MovieLens trước đây có kèm các tập dữ liệu chia sẵn để kiểm định chéo (cross-folds) hoặc các tập lệnh thực hiện việc chia dữ liệu này.
Hiện nay, GroupLens không còn đưa kèm những thành phần đó vì hầu hết bộ công cụ hiện đại đã tích hợp sẵn chức năng tương ứng. Nếu muốn tìm hiểu các phương pháp chia dữ liệu kiểm định chéo tiêu chuẩn để đánh giá hệ thống gợi ý, bạn có thể tham khảo LensKit (http://lenskit.org) để xem công cụ, tài liệu hướng dẫn và các ví dụ mã nguồn mở.
