# JAVA SCRIPT
**compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments**

# - JavaScript type conversions

|Left operand  |operator |right operand |result|
---------------|---------|--------------|------|
|[](empty array)|  +      |[] (empty array)|"" (empty string)
|[] (empty array)|+      |{} (empty object)	|"[object Object]" (string)
|false (boolean)	|+      |[] (empty array)	|"false" (string)
|"123"(string)	|+        |1 (number)	      |"1231" (string)
|"123" (string)	|-        |1 (number)	|122 (number)
