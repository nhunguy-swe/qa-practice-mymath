[English](README.md) | Tiếng Việt

# MyMath - Luyện tập TDD

Dự án thư viện C# tập trung luyện tập **Test-Driven Development (TDD)** và tối ưu hóa thuật toán.

## Công nghệ sử dụng

- **Ngôn ngữ:** C# (.NET Core)
- **Framework kiểm thử:** NUnit / MSTest
- **Công cụ:** Visual Studio Test Explorer

## Quy trình phát triển (TDD)

Dự án áp dụng chu trình **Red-Green-Refactor** để xây dựng phương thức `SquareRoot`:

1. **Red (Đỏ):** Viết unit test trước khi cài đặt bất kỳ logic nào.
2. **Green (Xanh):** Viết đoạn code tối thiểu đủ để các test pass.
3. **Refactor (Tái cấu trúc):** Tối ưu thuật toán bằng phương pháp **Newton-Raphson**, đồng thời đảm bảo tất cả test vẫn pass.

## Các kịch bản kiểm thử

- **Phạm vi giá trị:** Kiểm chứng thuật toán trên dải giá trị rộng, từ $1e^{-8}$ đến $1e^{+8}$.
- **Xử lý lỗi:** Ném ra `ArgumentOutOfRangeException` khi gặp giá trị âm.
- **Độ phủ code (Code Coverage):** Đảm bảo mọi nhánh logic và điểm quyết định đều được unit test kiểm tra.

## Cách chạy

1. Mở file `.sln` bằng **Visual Studio**.
2. Mở **Test Explorer** (`Ctrl + E, T`).
3. Nhấn **Run All** (`Ctrl + R, A`) để chạy toàn bộ bộ test.

---

*Dự án được thực hiện như một bài luyện tập thực hành về Đảm bảo chất lượng phần mềm (QA) và nguyên lý TDD.*
