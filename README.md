# Android-CTF

![android-re](https://github.com/MinhNhatTran/Android-CTF/blob/master/android.jpg)

## Hệ điều hành:
Windows hay Linux đều cài đặt được các tool và môi trường.

## Danh sách các tool sử dụng:
- [Java 8u241](https://java.com/en/download/manual.jsp): đa số các tool cho android viết bằng java, bản thân app android cũng viết bằng java. Cài môi trường java 8u241 để dùng được cả các phần mềm Cr@cK, bản java cao hơn không dùng được. 
- [Virtualbox](https://www.virtualbox.org/wiki/Downloads): máy ảo để chạy genymotion, chỉ cần cài virtualbox để cài genymotion là được. Tải riêng bằng link này, hoặc trong link tải genymotion chọn phần "download with virtualbox".
- [Genymotion](https://www.genymotion.com/download/): tạo giả lập android.
- ADB: Android Debug Brige - công cụ giúp kết nối với máy ảo Android. ADB có sẵn trong thư mục tools của genymotion, đường dẫn mặc định trên windows là **C:/Program Files/Genymobile/Genymotion/tools**.
- [Apktool](https://ibotpeaches.github.io/Apktool/install/): decompile và build file apk.
- [Dex2jar](https://github.com/pxb1988/dex2jar): chuyển file .dex sang file .class (chuyển file apk sang file jar - có thể đọc được code).
- [JD-gui](http://java-decompiler.github.io/): đọc code file jar.
- [Bytecode Viewer](https://bytecodeviewer.com/): "hợp thể" của Dex2jar và JD-gui.
- [Frida](https://frida.re/): hook function, phục vụ cho phân tích động.
- Burp Suite: dùng bản community hoặc tìm các bản Cr@cK trên mạng. Chạy burp Cr@cK bằng java 8u241, bản community dùng java nào cũng được.
- [SQlite browser](https://sqlitebrowser.org/): xem sqlite databases - DB local của android app.
- Text editor: sử dụng các text editor hỗ trợ đọc file .smali và .xml tốt (đề nghị dùng [VScode](https://code.visualstudio.com/download) + cài thêm các extension highlight code).

## Writeup cho các bài Android CTF:
- Picoctf 2019:
  - [Droids0](https://github.com/MinhNhatTran/Android-CTF/blob/master/pico2019/zero/writeup.md)
  - [Droids1](https://github.com/MinhNhatTran/Android-CTF/blob/master/pico2019/one/writeup.md)
  - [Droids2](https://github.com/MinhNhatTran/Android-CTF/blob/master/pico2019/two/writeup.md)
  - [Droids3](https://github.com/MinhNhatTran/Android-CTF/blob/master/pico2019/three/writeup.md)
  - [Droids4](https://github.com/MinhNhatTran/Android-CTF/blob/master/pico2019/four/writeup.md)
- EVBASv4:
  - [Level 1](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-1---debug-me)
  - [Level 2](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-2---file-access)
  - [Level 3](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-3---strings)
  - [Level 4](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-4---resource)
  - [Level 5](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-5---shares-and-preferences)
  - [Level 6](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-6---db-leak)
  - [Level 7](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-7---export)
  - [Level 8](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-8---decode)
  - [Level 9](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-9---smali-injection)
  - [Level 10](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-10---intercept)
  - [Level 11](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-11---custom-perm)
  - [Level 12](https://github.com/MinhNhatTran/Android-CTF/blob/master/EVABS/writeup.md#level-12---instrument) [x]
- KGB messenger:
  - [Alert (trung bình)](https://github.com/MinhNhatTran/Android-CTF/blob/master/KGB%20messenger/writeup.md#alert-trung-b%C3%ACnh)
  - [Login (dễ)](https://github.com/MinhNhatTran/Android-CTF/blob/master/KGB%20messenger/writeup.md#login-d%E1%BB%85)
  - [Social Engineering (khó)](https://github.com/MinhNhatTran/Android-CTF/blob/master/KGB%20messenger/writeup.md#social-engineering-kh%C3%B3)
- [UnCrackable Level 1](https://github.com/MinhNhatTran/Android-CTF/blob/master/UnCrackable%20Level%201/writeup.md)
