importance: 4

---

# 创建一个列表

编写一个接口，根据用户输入生成一个列表。

每一个列表项：

1. 使用 `prompt` 询问用户输入的内容。
2. 创建 `<li>` 并添加到 `<ul>`。
3. 重复以上两步，直到用户输入取消指令（按下 `key:Esc` 或者 prompt 的 CANCEL）。

所有元素应该都是动态创建的。

如果把用户输入了 HTML 标签，就应该将其视为文本。

[demo src="solution"]
