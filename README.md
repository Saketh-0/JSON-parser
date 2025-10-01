# C++ JSON Parser

This is a simple JSON parser built in **C++**.  
It is designed to parse **basic dictionary-style JSON objects** (key-value pairs) from a single line and display the parsed data.

---

##  How It Works

- The parser expects a **single-line JSON-like dictionary**.  
- Rules:
  - Keys and values must be **strings wrapped in double quotes** (`"example"`).
  - The entire object must be enclosed in **curly braces `{}`**.
  - Key-value pairs are separated by a **colon `:`**.
  - Multiple pairs are separated by a **comma `,`**.

###  Example Input
```json
{"name":"Alice","age":"25","city":"New York"}

# Output
Key: name, Value: Alice
Key: age, Value: 25
Key: city, Value: New York
