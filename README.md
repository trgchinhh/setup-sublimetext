# HƯỚNG DẪN BUILD NEW SYSTEM TRÊN SUBLIME TEXT 

## Tải tại đây: [Sublimetext - 4180](https://download.sublimetext.com/sublime_text_build_4180_x64_setup.exe)
## Tải bản mới nhất: [Sublimetext - 4200](https://www.sublimetext.com/download)

## BƯỚC 1 
- Chọn vào Tool -> Build System -> New Build System
- Xóa hết chữ trên file mới
- Hoặc nếu vào bằng file explorer thì theo đường dẫn sau : C:\Users\ADMIN\AppData\Roaming\Sublime Text\Packages\User

![image](https://github.com/user-attachments/assets/a4c7e339-f389-4b92-86c2-95c7ecb2c5b0)

- Sau khi vào folder thì tạo file theo dạng <ngôn ngữ>.sublime-build

## BƯỚC 2 
- Copy và dán nội dung vào file mới tạo
- Hoặc cut và copy file mới tải vào folder ở đường dẫn trên

![image](https://github.com/user-attachments/assets/58a2b71a-30b0-41f0-b9b0-5268db7b56ac)


## BƯỚC 3 
- Kiểm tra lại các bước và lưu
- Vào Tool -> Build System -> New Build System kiểm tra có hiện tên file mới build chưa
- Nếu có là thành công

![image](https://github.com/user-attachments/assets/21b8b16a-8c35-4d46-8796-033c5f2768cc)

## Bước 4 
- Cài gợi ý cho sublime text tùy vào ngôn ngữ
  + Bước 1: Vào Preferences -> Package Control -> Install Package
  + Bước 2: Tìm Lsp và cài đặt
  + Bước 3: Tìm 'Lsp-...' tùy theo ngôn ngữ bạn code
- (*) Vd như C++ là Lsp-clangd, Python là Lsp-pyright, ...
- Riêng C++ thì phải cài clangd thông qua mingw64
- Lệnh cài: `pacman -S mingw-w64-ucrt-x86_64-clang-tools-extra`

## CHÚC CÁC BẠN SETUP THÀNH CÔNG !!!
