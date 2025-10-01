C++ JSON Parser


This is a simple JSON parser built with C++. It's designed to read a basic dictionary format (key-value pairs) from a single line and show you the parsed data.

How It Works
The parser expects a single-line, JSON-like dictionary. The rules are simple:

Keys and values must be strings wrapped in double quotes (e.g., "name").

The whole thing must be enclosed in curly braces {}.

Key-value pairs are separated by a colon :, and different pairs are separated by commas ,.

Example 
✅ Successful Run
If you give it valid input, it'll work like this:

Input:

JSON

{"name":"Alice","age":"25","city":"Wonderland"}

Output:

Your Data:
name: Alice
age: 25
city: Wonderland


❌ Error Handling
If the format's wrong (like a missing quote or brace), it'll let you know.

Output:

Error: Invalid JSON format.**


