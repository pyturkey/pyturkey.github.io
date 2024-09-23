# Welcome to pyturkey web page

<p>
This is paragraph
</p>
Also this is paragraph

- list1
- list2

### following did not work :D
1. numberlist1
2. numberlist2
3. numberlist3


> this is quote

- This is `let x=10;`
```json
{
    "username": "adnankaya",
    "password": "password"
}
```
following line
---
a

---
a

---

<div class="grid cards" markdown>

- :fontawesome-brands-html5: __HTML__ for content and structure
- :fontawesome-brands-js: __JavaScript__ for interactivity
- :fontawesome-brands-css3: __CSS__ for text running out of boxes
- :fontawesome-brands-python: __Python__ for backend for rapid development!

</div>

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

| Method      | Description                          |
| ----------- | ------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```
=== "Python"
    ```python
    print("Hello world")
    ```

```python
class TeaSectionManager:
    def __enter__(self):
        print("Preparing the exclusive tea section...")  # Setup tasks
        # Code to set the right tea temperature, adjust lighting, etc.
        return self

    def __exit__(self, exc_type, exc_value, traceback):
        print("Reverting tea section setup...")  # Cleanup tasks
        # Code to clean and reset the section back to normal

# Using the context manager
with TeaSectionManager():
    print("Guests are enjoying the exclusive tea section.")

```

[Subscribe to our newsletter](#){ .md-button }

!!! note

    This is note

??? note

    This is note2

???+ info "my very important info"

    This is info