# code-learning
**code-learning** là một repo chứa các bài tập code của một số ngôn ngữ lập trình.
# Giới thiệu một số ngôn ngữ lập trình và các IDE được sử dụng để code những bài tập trong repo này:
## C/C++ và Dev-Cpp
Hướng dẫn cài Dev-Cpp:

**Bước 1:** Truy cập đường link https://github.com/Embarcadero/Dev-Cpp/releases

**Bước 2:** Tìm phiên bản mong muốn và chọn file tải xuống trong Assets.

Giải thích các file trong Assets:
- No_Compiler: Không chứa trình biên dịch, chỉ dùng để viết code.
- TDM-GCC_9.2: Đã tích hợp trình biên dịch gcc phiên bản 9.2, có thể viết code và chạy chương trình.
- Portable.7z: tải về, giải nén và dùng, không cần cài đặt.
- Setup.exe: tải về, cài đặt và dùng (dành cho Windows).
- Setup.zip: tải về, giải nén, cài đặt và dùng.
## Java và JDK + Eclipse
Dùng JDK + Eclipse để code và chạy chương trình java.

**Bước 1: Cài JDK**
- Dành cho Windows:
    - **Bước 1.1:** Truy cập đường link https://www.oracle.com/java/technologies/downloads/
    - **Bước 1.2:** Chọn phiên bản, chọn hệ điều hành Windows và bấm chọn file tải xuống (thường có đuôi `.exe`).
    - **Bước 1.3:** Nhấn đúp chuột vào file có đuôi `.exe` vừa tải để cài.
    - **Bước 1.4:** Kiểm tra đã cài thành công chưa: Mở Terminal, gõ hai lệnh `java -version` và `javac -version`. Nếu hai lệnh đều trả về số phiên bản thì đã cài thành công.
- Dành cho Linux Mint 22.3 - Cinnamon 64-bit:
    - **Bước 1.1:** Mở Terminal, gõ `sudo apt update` để cập nhật danh sách phần mềm. Sau đó, gõ `sudo apt install openjdk-<so_phien_ban>-jdk` (ví dụ: `sudo apt install openjdk-26-jdk`).
    - **Bước 1.2:** Kiểm tra đã cài thành công chưa: Mở Terminal, gõ hai lệnh `java -version` và `javac -version`. Nếu hai lệnh đều trả về số phiên bản thì đã cài thành công.

**Bước 2: Cài Eclipse**
- **Bước 2.1:** Truy cập đường link https://www.eclipse.org/downloads/packages/
- **BƯớc 2.2:** Tìm package có tên "Eclipse IDE for Java Developers".
- **Bước 2.3:** Chọn kiến trúc hệ điều hành và bấm nút `Download`.
- **Bước 2.4:** Giải nén file và tiến hành cài.

## Python và Visual Code + Extension "Python"
**Bước 1: Cài Python**
- Dành cho Windows:
    - **Bước 1.1:** Vào Microsoft Store, gõ vào thanh tìm kiếm "Python", tìm phần mềm Python, nhấn nút cài.
    - **Bước 1.2:** Kiểm tra Python đã cài thành công chưa: Mở Terminal, gõ `python --version`. Nếu trả về số phiên bản thì đã cài thành công.
- Dành cho Linux Mint 22.3 - Cinnamon 64-bit: Thường đã tích hợp sẵn python, vào Terminal, gõ `python3 --version` để kiểm tra lại.

**Bước 2: Cài Visual Code**

Truy cập đường link đề tải về và cài đặt: https://code.visualstudio.com/

## SQL và SQL Server + SSMS
Dùng SQL Server + SSMS để code và chạy chương trình sql.

**Bước 1:** Truy cập đường link https://www.microsoft.com/en-us/download/details.aspx?id=42299

**Bước 2:** Bấm nút `Download`, chọn file SQLEXPR_x64_ENU.exe + SQLManagementStudio_x64_ENU.exe

**Bước 3:** Chạy file SQLEXPR_x64_ENU.exe trước, rồi chạy file SQLManagementStudio_x64_ENU.exe sau.