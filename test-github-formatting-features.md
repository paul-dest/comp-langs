This is a piece of **Java** code:
```java
public class MyType {
    int myField;
}
```

This is a piece of **Ruby** code:
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

This is a piece of **Python** code:
```python
a_list = [1, 'a', True]
for an_object in a_list:
    print(f"Hello, my {an_object}!")
```

<table>
<tr> <th>Java</th> <th>Python</th> </tr>

<tr>
<td><pre lang="java">
try (BufferedReader br = new BufferedReader(new FileReader(path))) {
    return br.readLine();
}
</pre></td>

<td><pre lang="python">
with open(path, 'r') as f:
    return f.readline()
</pre></td>
</tr>
</table>

Unfortunately, there is no comfy way to combine markdown and multiline code blocs / syntax highlighting in a table. Is that true??\
**FIXIT**: If you know a solution (besides using HTML as done above), fix it!
| Piece of code | Description |
| --- | --- |
| ```java
for (int i = 0; i < 10; ++i) { println(i); }``` | a classic C-style loop |
| `git diff` | Show file differences that **haven't been** staged |
