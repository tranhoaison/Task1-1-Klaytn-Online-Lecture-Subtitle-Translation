# 5. Front-end để phát triển mở rộng các trò chơi Klaytn
 
## 5.1 Cài đặt


Bây giờ bạn đã tạo ra một hợp đồng sẽ được sử dụng cho BApp trong các lớp học trước, hãy phát triển front-end. 
Trước tiên, hãy tiến hành cấu hình cơ bản. 
Trong hướng dẫn này, tôi sẽ tải về Node.js, NPM, Truffle framework và visual studio code. 
Node.js là một nền tảng server-side JavaScript, mà chúng thực sự cần cho BApp của chúng ta. 
NPM được cài đặt cùng với Node.js, đó là cần thiết để tải về công cụ và thư viện trong khi đang phát triển. 
Truffle framework chúng ta sẽ cài đặt cũng cần được tải về thông qua NPM. 
Nếu bạn đã có Node.js và NPM cài đặt, kiểm tra phiên bản và bỏ qua phần này nếu Node.js là phiên bản 8 trở lên và NPM là phiên bản 5 trở lên.


Vui lòng truy cập https://nodejs.org và cài đặt phiên bản 10.15.3 LTS.
tôi đã cài đặt nó và tôi bỏ qua bước này.
Sau khi cài đặt, chúng ta sẽ kiểm tra nếu node.js đã được cài đặt trên PowerShell. 
Gõ lệnh Node-v và kiểm tra phiên bản. và cũng kiểm tra npm. Npm -v, Tất nhiên nó được cài đặt chính xác.

Cuối cùng, tôi sẽ cài đặt Truffle. 
Truffle là một framework giúp bạn dễ dàng phát triển BApp. 
Nó cho phép bạn biên dịch, kiểm thử, và khởi chạy hợp đồng thông minh.
nó là một framework rất phổ biến. 
Phiên bản Truffle đã được cập nhật lên 5 gần đây.
Tuy nhiên,  Klaytn được phát triển với phiên bản 4, tôi sẽ sử dụng phiên bản Truffle 4. 
Nếu bạn có các phiên bản khác, việc đầu tiên bạn cần là xóa nó trước.
Gỡ cài đặt bằng cách gõ `npm uninstall -g truffle` trên PowerShell. 
Sau đó cài đặt ‘npm install -g truffle@4.1.15’ tôi sẽ có được phiên bản 4.



Nếu bạn đã tải xuống mọi thứ, kiểm tra phiên bản của truffle. 
Nó là 4.1.15 và trình biên dịch solidity được gọi là phiên bản 0.4.25.
Solidity là một ngôn ngữ lập trình để viết hợp đồng thông minh. Cuối cùng, hãy tải xuống phần mềm chỉnh sửa code, Visual Studio code. tải nó tại đây: ‘https://code.visualstudio.com/’ . 
Tôi đã cài đặt xong nên phần này tôi bỏ qua.
Nếu bạn tải xuống hãy cài đặt nó.
Visual Studio code hỗ  trợ đa nền tảng, bạn có thể  chạy nó trên Linux, Windows, Mac và bao gồm một số tính năng tiện dụng như hỗ trợ gỡ lỗi, kiểm soát git, làm rõ cú pháp và hơn thế nữa.




Bây giờ hãy nhấp vào tab Tiện ích mở rộng dưới đây để cài đặt phần mở rộng để hỗ trợ các ngôn ngữ solidity. Xin vui lòng gõ 'Solidity' và chọn một trong những lúc đầu. 
Nhấp vào cài đặt. Phần mở rộng này cung cấp các màu sắc nổi bật cho mỗi ngữ pháp vững chắc và cho phép bạn biên dịch. 
Cài đặt xong. Tôi sẽ kết thúc phiên định cấu hình đó là cần thiết cho sự phát triển của lối vào.
