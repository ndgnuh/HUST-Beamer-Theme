# HUST beamer theme

Template beamer không chính thức của Đại học Bách khoa Hà Nội.

Xem [slide mẫu](https://github.com/ndgnuh/HUST-Beamer-Theme/blob/master/example.pdf)

## Cách dùng

- Copy các file `*.sty` và thư mục `res` vào project LaTeX
- Trong file `slide.tex`, thêm dòng:
```latex
\usetheme{hust}
```

## Build slide ví dụ
Slide ví dụ dùng `lualatex` để compile, dùng `pdflatex` sẽ gây lỗi

```shell
lualatex example.tex
bibtex example
lualatex example.tex
lualatex example.tex
```

