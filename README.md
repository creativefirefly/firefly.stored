# Firefly Store

## Hệ thống quản lý kho/cửa hàng
Hệ thống quản lý kho/cửa hàng là một hệ thống cơ sở, cơ bản. Nhưng là một nền tảng cần thiết các hệ thống khác xây dựng ở lớp cao hơn(top layer)

Bất kỳ một hệ thống nào liên quan đến hoạt động kinh doanh các sản phẩm hiện hữu, đều cần quản lý kho/cửa hàng. Tuy nhiên tùy vào quy mô của dự án mà người ta quyết định có đưa nó vào hay không.

## Target dự án
Firefly store là một dự án quản lý kho/cửa hàng cơ bản. Với mục đích là một hệ thống dạng module có thể phù hợp với bất kỳ ngành hàng nào. 
Là một hệ thống dạng Open source. Bạn có thể sử dụng nó cho bất kỳ lý do cá nhân hoặc kinh doanh nào. 
Dễ dàng tích hợp với các hệ thống khác qua API hoặc Message Queue. 
Có khả năng mở rộng tùy theo nhu cầu.
Là một hệ thống dạng module, nên có thể dễ dàng tích hợp với các hệ thống khác như một module con trong một ecosytem hoặc chạy độc lập như một hệ thống hoàn chỉnh

## Các thành phần chính
Các thành phần của hệ thống quản lý kho khá đơn giản bao gồm
 - Order Management(Quản lý đơn hàng) Hiểu đơn giản là khi mua bất kỳ thứ gì trong kho hàng, phải có đơn hàng được tạo. Đơn hàng sẽ bao gồm các thông tin liên quan đến sản phẩm, số lượng, đơn giá, chiết khấu.
 - Vendor Management(Quản lý người bán) Một đơn hàng được xuất từ kho, hoặc cửa hàng chỉ định nào đó. Việc quản lý kho, cửa hàng cũng như các thông tin riêng biệt của họ sẽ nằm ở module này
 - Item/Product Management(Quản lý sản phẩm) Sản phẩm là một unit nhỏ nhất trong hệ thống. Phần này sẽ quản lý danh mục sản phẩm, cũng như các đặc đính của sản phẩm(phần này có thể mở rộng đặc tính)
 - Báo cáo (Report) 

