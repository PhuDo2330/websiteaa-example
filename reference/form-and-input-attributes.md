# Form And Input Attributes



- `action`
  Example: `<form action="app/index.html">`
  Meaning: tells the form where to go after submission.
  Cái này báo form gửi xong thì đi đâu.
  Note: `action` is the destination.
  `action` là địa chỉ nó sẽ tới.

- `for`
  Example: `<label for="email">Email</label>`
  Meaning: connects a label to a specific input.
  Cái này nói label này thuộc về input nào.
  Note: the `for` value must match an input `id`.
  Giá trị `for` phải giống với `id` của input.

- `id`
  Example: `<input id="email" type="email">`
  Meaning: gives one element a unique name on the page.
  Cái này đặt tên riêng cho một phần tử.
  Note: `id` tells which field it is.
  `id` cho biết đây là ô nào.

- `type`
  Example: `<input type="email">`
  Meaning: tells the browser what kind of input or button it is.
  Cái này báo browser biết ô này là loại gì.
  Note: `type` controls behavior.
  `type` điều khiển cách nó hoạt động.

- Common `type` values
  `type="text"` = normal text field
  Ô nhập chữ bình thường.
  `type="email"` = email field
  Ô nhập email.
  `type="password"` = hidden text field
  Ô nhập mật khẩu, chữ bị ẩn đi.
  `type="checkbox"` = checkbox
  Ô tick chọn.
  `type="submit"` = sends the form
  Nút này bấm là gửi form.

- `placeholder`
  Example: `<input placeholder="you@example.com">`
  Meaning: shows light hint text inside the input box.
  Cái này hiện chữ gợi ý mờ mờ trong ô nhập.
  Note: `placeholder` is only a hint, not actual input.
  Nó chỉ là gợi ý thôi, không phải dữ liệu thật.

- `required`
  Example: `<input required>`
  Meaning: makes the field mandatory before the form can be submitted.
  Cái này bắt buộc người dùng phải nhập.
  Note: the user must fill it in.
  Bỏ trống là không gửi được.

 