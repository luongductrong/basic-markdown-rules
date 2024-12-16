# BASIC MARKDOWN RULES
---

## 1. Headings

- Use `#` for headings, ranging from `#` (largest) to `######` (smallest).

```
# Heading 1
## Heading 2
### Heading 3
```

## 2. Bold, Italic, Strikethrough

- **Bold:** Use `**text**` or `__text__`.
- *Italic:* Use `*text*` or `_text_`.
- ~~Strikethrough:~~ Use `~~text~~`.

```
**Bold**, *italic*, or ~~strikethrough~~.
```

## 3. Lists

- **Unordered list:** Use `-`, `*`, or `+`.
- **Ordered list:** Use numbers (`1.`, `2.`).

<table>
  <tr>
    <th>Unordered List</th>
    <th>Ordered List</th>
  </tr>
  <tr>
    <td>
      <ul>
        <li>Item 1</li>
        <li>Item 2
          <ul>
            <li>Sub-item 1</li>
            <li>Sub-item 2
              <ul>
                <li>Sub-item 1</li>
                <li>Sub-item 2</li>
              </ul>
            </li>
          </ul>
        </li>
      </ul>
    </td>
    <td>
      <ol>
        <li>Item 1</li>
        <li>Item 2
          <ol>
            <li>Sub-item 1</li>
            <li>Sub-item 2
              <ol>
                <li>Sub-item 1</li>
                <li>Sub-item 2</li>
              </ol>
            </li>
          </ol>
        </li>
      </ol>
    </td>
  </tr>
</table>

```
- Item 1
- Item 2
    - Sub-item 1
1. Item 1
2. Item 2
    1. Sub-item 1
```

## 4. Links and Images

- **Links:** `[text](url)`.
- **Images:** `![Alt text](image-url)`.

  [Google](https://www.google.com)

  ![Logo](https://www.google.com/favicon.ico)

```
[Google](https://www.google.com)
![Logo](https://www.google.com/favicon.ico)
```

## 5. Blockquote and Code

- **Blockquote:** Use `>` for quotes.
- **Inline code:** Use `` `code` ``.

> This is a blockquote.

`Inline code`

```
> This is a blockquote.
`Inline code`
```

## 6. Line Breaks

- **Separate paragraphs:** Leave a blank line between paragraphs.
- **Horizontal line:** Use `---` or `***`.

```
---
```

## 7. Tables

- Use `|` to create tables.

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Value 1  | Value 2  | Value 3  |

```
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Value 1  | Value 2  | Value 3  |
```

## 8. Task Lists

- Use `- [ ]` for unchecked tasks and `- [x]` for checked tasks.

```
- [ ] Task 1
- [x] Task 2
```

## 9. Embedding HTML (Optional)

- Markdown allows embedding HTML if needed.

```
<div style="color: red;">HTML Content</div>

<table>
  <tr>
    <th>Column 1</th>
    <th>Column 2</th>
  </tr>
  <tr>
    <td>Value 1</td>
    <td>Value 2</td>
  </tr>
</table>
```
---

# References
- [CommonMark Specification](https://spec.commonmark.org/0.31.2/): A basic standard for Markdown designed to ensure consistency across different Markdown parsers.
- [Markdown Guide](https://www.markdownguide.org/): Detailed guidance from beginner to advanced, with practical examples.
- [GitHub Flavored Markdown (GFM)](https://github.github.com/gfm/): Official GitHub documentation on the Markdown extensions supported by GitHub.

#### You can practice Markdown in VS Code, which offers various extensions to enhance your writing experience. Start by creating a new Markdown file and use `Ctrl + Shift + V` to open Markdown Preview in VS Code.

---
---

# QUY TẮC VIẾT MARKDOWN CƠ BẢN
---
## 1. Tiêu đề (Headings)

- Dùng dấu # để tạo tiêu đề, từ `#` (lớn nhất) đến `######` (nhỏ nhất).

```
# Tiêu đề 1
## Tiêu đề 2
### Tiêu đề 3
```
## 2. In đậm, in nghiêng, gạch ngang

- **In đậm:** Dùng `**text**` hoặc `__text__`.
- *In nghiêng:* Dùng `*text*` hoặc `_text_`.
- ~~Gạch ngang:~~ Dùng `~~text~~`.

```
**In đậm** và *in nghiêng* hoặc ~~gạch ngang~~.
```
## 3. Danh sách

- **Danh sách không thứ tự:** Dùng `-`, `*`, hoặc `+`.
- **Danh sách có thứ tự:** Dùng số (`1.`, `2.`).

<table>
  <tr>
    <th>Danh sách không thứ tự</th>
    <th>Danh sách có thứ tự</th>
  </tr>
  <tr>
    <td>
      <ul>
        <li>Mục 1</li>
        <li>Mục 2
          <ul>
            <li>Mục con 1</li>
            <li>Mục con 2
              <ul>
                <li>Mục con 1</li>
                <li>Mục con 2</li>
              </ul>
            </li>
          </ul>
        </li>
      </ul>
    </td>
    <td>
      <ol>
        <li>Mục 1</li>
        <li>Mục 2
          <ol>
            <li>Mục con 1</li>
            <li>Mục con 2
              <ol>
                <li>Mục con 1</li>
                <li>Mục con 2</li>
              </ol>
            </li>
          </ol>
        </li>
      </ol>
    </td>
  </tr>
</table>

```
- Mục 1
- Mục 2
    - Mục con
1. Mục 1
2. Mục 2
```

## 4. Link và hình ảnh

- **Link:** `[text](url)`.
- **Hình ảnh:** `![Logo](image-url)`.

  [Google](https://www.google.com)

  ![Logo](https://www.google.com/favicon.ico)

```
[Google](https://www.google.com)
![Logo](https://www.google.com/favicon.ico)
```
## 5. Blockquote và code

- **Blockquote:** Dùng `>` để trích dẫn.
- **Code inline:** Dùng `` `code` ``.

> Đây là một blockquote.

`Code inline`

```
> Đây là một blockquote.
`Code inline`
```
## 6. Chia đoạn

- **Chia đoạn:** Để dòng trống giữa các đoạn.
- **Dòng kẻ ngang:** Dùng `---` hoặc `***`.

```
---
```
## 7. Bảng

- Tạo bảng bằng cách dùng dấu `|`.

| Cột 1 | Cột 2 | Cột 3 |
|-------|-------|-------|
| Giá trị 1 | Giá trị 2 | Giá trị 3 |

```
| Cột 1 | Cột 2 | Cột 3 |
|-------|-------|-------|
| Giá trị 1 | Giá trị 2 | Giá trị 3 |
```
## 8. Task List

- Dùng `- [ ]` cho task chưa hoàn thành và `- [x]` cho task đã hoàn thành.

```
- [ ] Task 1
- [x] Task 2
```
## 9. Chèn HTML (Tuỳ chọn)

- Markdown hỗ trợ chèn HTML nếu cần.

```
<div style="color: red;">Chèn HTML</div>

<table>
  <tr>
    <th>Cột 1</th>
    <th>Cột 2</th>
  </tr>
  <tr>
    <td>
      Giá trị 1
    </td>
    <td>
      Giá trị 2
    </td>
  </tr>
</table>
```
---

# Tài liệu tham khảo
- [CommonMark Specification:](https://spec.commonmark.org/0.31.2/) Tiêu chuẩn cơ bản của Markdown, được thiết kế để đảm bảo tính nhất quán giữa các trình biên dịch Markdown.

- [Markdown Guide:](https://www.markdownguide.org/) Hướng dẫn chi tiết từ cơ bản đến nâng cao, với các ví dụ thực tế.

- [GitHub Flavored Markdown (GFM):](https://github.github.com/gfm/) Tài liệu chính thức của GitHub về các mở rộng Markdown hỗ trợ bởi GitHub.

#### Bạn có thể luyện tập viết Markdown trên VS Code, với nhiều tuỳ chọn extension tiện ích hỗ trợ. Bạn có thể bắt đầu bằng việc tạo mới một file markdown, sử dụng tổ hợp phím `Ctrl + Shift + V` để mở chế độ Preview Markdown ngay trên VS Code.
