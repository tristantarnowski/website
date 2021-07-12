---
title: "Test Page"
date: 2070-01-01T00:00:00
publishDate: 1970-01-01T00:00:00
draft: true
featuredImage: ../pcb.png
---

This page contains all of the Markdown formatting elements from the [CommonMark help page](https://commonmark.org/help/). It can be used to check that everything is formatted as desired.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Horizontal rule:

---

These items are in the same paragraph    
*Italic*  
**Bold**  
~~Strikethrough~~

# H1
## H2
### H3
#### H4
##### H5
###### H6

![Image with caption](https://dummyimage.com/1920x1080 "Image caption")
![Image without caption](https://dummyimage.com/256x256)
![Big image](https://dummyimage.com/3840x2160)

> Block quote
> > Nested block

- Unordered list
- Item 2
  - Nested
    - Double nested

1. Ordered list
2. Item 2  
   1. Nested

Mattis ullamcorper velit sed ullamcorper morbi tincidunt ornare massa eget. Magna eget est lorem ipsum dolor sit amet. Commodo viverra maecenas accumsan lacus.

- **Spaced** Vestibulum mattis ullamcorper velit sed ullamcorper morbi. Nunc aliquet bibendum enim facilisis gravida neque convallis a cras.

- **Out** Velit dignissim sodales ut eu sem integer vitae. Ullamcorper malesuada proin libero nunc consequat interdum.

- **List** Libero volutpat sed cras ornare. Mauris augue neque gravida in fermentum et sollicitudin. Aenean sed adipiscing diam donec. Quis auctor elit sed vulputate mi sit.

Inline `code` block

```
for i = 1 to 10
    print i
end
```

```html
<!DOCTYPE HTML>
<html>
<head>
    <title>Title</title>
</head>
<body>
    <p>Content</p>
    <!-- Comment -->
</body>
</html>
```

```c++
#include <iostream>

int main(int argc, char const *argv[])
{
    for (int i = 0; i < 10; i++>) {
        std::cout << i << '\n';
        std::cout << "This is a longer line of code" << '\n';
    }
    return 0;
}
```

```matlab
x = -pi:0.01:pi;
plot(x,cos(x));
grid on
```

```python
adj = ["red", "big", "tasty"]
fruits = ["apple", "banana", "cherry"]

for x in adj:
  for y in fruits:
    print(x, y) 
```

```js
if ((time < 10) && true) {
  greeting = "Good morning";
} else if ((time < 20) || false) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```

| Column 1 | Column 2 | Column 3 |
| -------- | :------: | -------: |
| Left     |  Center  |    Right |
| Yay      |          |   Tables |

A Youtube video, using Hugo's `youtube` shortcode:

{{< youtube >}}