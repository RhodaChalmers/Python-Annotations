# Python-Annotations
# Learning how to annotate Python for GitHub
# This is based upon https://docs.github.com/en/contributing/writing-for-github-docs/annotating-code-examples

# you can't see it but
# I used ```python before the next bit of text and ended with ``` after the last bit of text
```python
# Function to print string variables
def assignment4() -> None:
  # Define string variables
    a: str = "What codes can be used to program servers with?"
    b: str = "Java"
    c: str = "JavaScript"
    d: str = "Python"
    e: str = "According to Infrastructure as Code"
  # Print string variables sequentially
    print(a)
    print("\t", b)
    print("\t", c)
    print("\t", d)
    print(e)
    
# Run function
assignment4()
```
