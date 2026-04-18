# Link And File Attributes


- `href`
  Example: `<a href="auth/forgot-password.html">Forgot password?</a>`
  Example: `<link rel="stylesheet" href="assets/css/base.css">`
  Meaning: tells the browser where a link or file points.
  Cái này báo browser file hoặc link này trỏ tới đâu.
  Note: `href` is the path to another page or file.
  `href` là đường dẫn tới trang hay file khác.

- `rel`
  Example: `<link rel="stylesheet" href="assets/css/base.css">`
  Meaning: describes the relationship between the current page and the linked file.
  Cái này nói file được link có liên quan kiểu gì với trang hiện tại.
  Note: `rel="stylesheet"` means the linked file is CSS.
  `rel="stylesheet"` nghĩa là file link vào là CSS.

- Relative path example
  `href="assets/css/base.css"`
  Meaning: start from the current folder, then go into `assets/css`.
  Bắt đầu từ folder hiện tại rồi chui vào `assets/css`.

- Relative path example with `..`
  `href="../assets/css/base.css"`
  Meaning: go up one folder first, then go into `assets/css`.
  Lùi lên một folder trước, rồi mới vào `assets/css`.

- Path note
  `..` means "go up one folder".
  `..` nghĩa là lùi lên một folder.
