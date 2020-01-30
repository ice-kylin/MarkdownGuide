# Markdown代码

> 在一些技术性文本中，我们会遇到一些片段代码或代码区块。在 Markdown 文本中，我们可以使这些特殊文本有特殊的样式，让它们看上去更像代码。

## 片段代码

段落上的单个函数或片段代码两段添加 `` ` 即可

### 代码示例

```markdown
`print()`函数
```

### 效果展示

`print()`函数

## 代码区块

- 在每一行前使用 4 个空格或者一个制表符（`Tab` 键）

- 用 ```` ` 包裹一段代码，并指定一种语言（也可不指定）

### 代码示例

```markdown
	package main
	import "fmt"
	func main() {
		fmt.Println("Hello, 世界")
	}

​```go
package main
import "fmt"
func main() {
	fmt.Println("Hello, 世界")
}
​```
```

### 效果展示

	package main
	import "fmt"
	func main() {
		fmt.Println("Hello, 世界")
	}

```go
package main
import "fmt"
func main() {
	fmt.Println("Hello, 世界")
}
```