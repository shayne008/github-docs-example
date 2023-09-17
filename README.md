# Let's Write Good Documenation

## Step 1 - Using Codeblocks.

Codeblocks in markdown makes it *easier* for others to **copy, paste and share** code.
Cloud Engineers uses codeblocks whenever possible.

It allows others to replicate and reseacrh issues.

- In order to create codeblocks uses backticks ``` and not quotations (')


### Example Codeblock with Go
```
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

- When you can apply syntax highlighting to your codeblocks.


```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

- Make note of backtick key button is located, on the tidle key.
- Above tab key.


<img width="200px" src="https://github.com/shayne008/github-docs-example/assets/49353061/13f84e04-961f-4f80-a1ae-5e6199ac7896" /> 



Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.


```bash
panic: runtime error: integer divide by zero
```

> Here is an example of a codeblock for an error that appears in bash.

## Step -3 Use GitHub Flavored Task Lists

GitHub extends Markdown to include check off lists. [<sup>[1]</sup>](#references)

- [x] Finish Step 1
- [] Finish Step 2
- [x] Finish Step 3
- [x] Finish Step 4
- [x] Finish Step 5

  
# Step 4 - Use Emojis

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Face in Clouds | `face_in_clouds:` | 😶‍🌫️: |

# Step 5 - How To Create A Table

You can use the example markdown to create tables. [<sup>[2]</sup>](#references)

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Face in Clouds | `face_in_clouds:` | 😶‍🌫️: |
```



## References

- [Getting started with writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
- [GFM - Tables(with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
