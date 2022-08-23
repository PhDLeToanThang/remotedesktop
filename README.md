# remotedesktop
remotedesktop server for client A to remote client b or smartphone
**How does RustDesk work?**
https://github.com/rustdesk/rustdesk/wiki/How-does-RustDesk-work%3F
<IMG  src="https://user-images.githubusercontent.com/71636191/170462028-9b481abb-40bd-49df-8c05-8019325761ee.png"  alt="image"/>

<IMG  src="https://user-images.githubusercontent.com/71636191/170487506-8ef1f025-ad42-47f9-8d82-b49d0ec759ad.png"  alt="170462043-c4aefda1-3fb6-43e8-a54b-d3dec1590930"/>

<IMG  src="https://user-images.githubusercontent.com/99897242/172282341-7ec04806-6c7f-4848-a41f-93937c0c1093.png"  alt="image"/>

 **rustdesk / doc.rustdesk.com:**
https://github.com/rustdesk/doc.rustdesk.com
We need your help to translate this document to your native language

Tham khảo:  
Install hugo first

git clone https://github.com/matcornic/hugo-theme-learn themes/hugo-theme-learn
hugo serve

**dinger1986 / rustdeskinstall:**
https://github.com/dinger1986/rustdeskinstall/blob/master/install.sh

-------------
Install RustDesk Remote Desktop on Ubuntu 22.04|20.04|18.04
https://techviewleo.com/install-rustdesk-remote-desktop-on-ubuntu/

--------------------------------------------------------------------
**Lệnh để chạy thủ tục cài RemoteDesktop Server trên nền Ubuntu Linux:**
https://raw.githubusercontent.com/PhDLeToanThang/remotedesktop/main/rustdeskinstall.sh && sudo bash rustdeskinstall.sh

**Một số bước thực hiện và chuẩn bị cho dịch vụ Remote Desktop Server làm trên Ubuntu Linux Server:**
![image](https://user-images.githubusercontent.com/106635733/186059882-c699bf05-5870-42ad-be19-1a6e709098fe.png)

**Dừng ở bước hỏi IPv4 hay là DNS:**
![image](https://user-images.githubusercontent.com/106635733/186061077-fdbd8487-8863-432f-a705-32e66e595e52.png)

Theo tôi, bạn nên chọn DNS vì trong 2 tình huống bạn đều có lợi thế không phải thay đổi địa chỉ của Client/ Server nếu như các máy trạm bạn đã công bố sử dụng cho người dùng nhiều, từ xa, thậm trí cả thiết bị di động ... thì thật là phiền phức khi bị thay đổi địa chỉ ip.(Cấu hình ipv4 ở đây chỉ mang tính hỗ trợ thử nghiệm, làm trong mạng VPN/openVPN hoặc mạng LAN).

Thực chất đây là WAN IPv4/ WAN DNS của dịch vụ này vì nếu bạn dùng cho từ internet để có thể remote P2P giữa các máy client ở internet thì IPv4 phải là public ở tầng internet (WAN IP4/DNS) nhé.

![image](https://user-images.githubusercontent.com/106635733/186064570-43743e68-0f39-4a38-9f25-b6fd44dea062.png)

và khi hỏi đến các bước cuối về việc có Download Config của các bản Remote Client cho Windows / Linux Client và kết nối qua HTTP
![image](https://user-images.githubusercontent.com/106635733/186067946-26dcdaaa-9d58-44f4-bf06-71b1f1793ea7.png)

**Khi chọn : 1**
Hệ thống sẽ tạo ra chữ ký số, User: Admin và Mật khẩu Random,
Địa chỉ web HTTP://DNS:8000
![image](https://user-images.githubusercontent.com/106635733/186069419-d611744c-0984-411d-a9d1-1e25b9c98b74.png)

**Kết quả truy cập web:**

![image](https://user-images.githubusercontent.com/106635733/186070552-17e396da-bb46-4e9a-aebb-2d275ad4dcdf.png)
