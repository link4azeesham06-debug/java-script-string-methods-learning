# java-script-string-methods-learning
# JavaScript String Methods
# 1️⃣ **toUpperCase()**

 Definition
Converts all letters to **CAPITAL letters**.
 Syntax
JavaScript
string.toUpperCase()
 Why We Use It
To standardize text or compare strings ignoring case differences.
 Example
javascript
let text = "hello";
console.log(text.toUpperCase());
 Output
HELLO
 2️⃣ **toLowerCase()**

 Definition
Converts all letters to **small letters**.
 Syntax
JavaScript
string.toLowerCase()
javascript
let text = "HELLO";
console.log(text.toLowerCase());
Output
hello
 3️⃣ **trim()**
 Definition
Removes **extra spaces** from the beginning and end.
 Syntax
javascript
string.trim()
 Example
javascript
let text = "   hello   ";
console.log(text.trim());

 Output
hello
 Practice

Clean `"   JavaScript   "`.

---
4️⃣ **slice()**
  Definition

Extracts part of a string.
 Syntax
JavaScript
string.slice(start, end)
 Example
javascript
let text = "JavaScript";
console.log(text.slice(0, 4));
 Output
Java

# 5️⃣ **substring()**

### Definition

Also extracts part of a string (similar to slice).

### Syntax

```javascript
string.substring(start, end)
```

### Why We Use It

Same use as slice (older method).

### Example

```javascript
let text = "JavaScript";
console.log(text.substring(4, 10));
```

### Output

```
Script
```



# 6️⃣ **replace()**

### Definition

Replaces part of a string with something else.

### Syntax

```javascript
string.replace("old", "new")
```

### Why We Use It

To update or modify text.

### Example

```javascript
let text = "I like cats";
console.log(text.replace("cats", "dogs"));
```

### Output

```
I like dogs
```

# 7️⃣ **includes()**

### Definition

Checks if a string **contains** something.

### Syntax

```javascript
string.includes("word")
```

### Why We Use It

Validation, searching text.

### Example

```javascript
let text = "hello world";
console.log(text.includes("world"));
```

### Output

```
true
```

### Step-by-Step

* Checks if `"world"` exists
* Returns true


 8️⃣ **indexOf()**

### Definition

Finds the **position (index)** of a word.

### Syntax

```javascript
string.indexOf("word")
```

### Why We Use It

To locate text inside a string.

### Example

```javascript
let text = "hello world";
console.log(text.indexOf("world"));
```

### Output

```
6
```

# 9️⃣ **split()**

### Definition

Splits a string into an **array**.

### Syntax

```javascript
string.split("separator")
```

### Why We Use It

To break text into parts (words, letters).

### Example

```javascript
let text = "hello world";
console.log(text.split(" "));
```

### Output

```
["hello", "world"]
```


# 🔟 **concat()**

### Definition

Joins two or more strings.

### Syntax

```javascript
string1.concat(string2)
```

### Why We Use It

To combine strings (though `+` is more common).

### Example

```javascript
let first = "Hello";
let second = "World";

console.log(first.concat(" ", second));
```

### Output

```
Hello World
```

#

* Combines `"Hello"` + `" "` + `"World"`

#




