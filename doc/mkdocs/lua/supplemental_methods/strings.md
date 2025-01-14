
Strings
=======

[TOC]

## String Manipulation

The following methods have been added to the built-in Lua [string library](https://www.lua.org/manual/5.3/manual.html#6.4).

---
### string.startsWith
<span style="color:green; font-weight:bold;">string.startsWith</span>(st, prefix)

- Checks if a string begins with a set of characters.
- Parameters:
    - ***st:*** The string to be checked.
    - ***prefix:*** The prefix to be compared with.
- Returns: `true` if `prefix` matches the beginning characters of `st`.
- Aliases:
    - <span style="color:green; font-style:italic;">string.beginsWith</span>

---
### string.endsWith
<span style="color:green; font-weight:bold;">string.endsWith</span>(st, suffix)

- Checks if a string ends with a set of characters.
- Parameters:
    - ***st:*** The string to be checked.
    - ***suffix:*** The suffix to be compared with.
- Returns: `true` if `suffix` matches then end characters of `st`.

---
### string.isNumber
<span style="color:green; font-weight:bold;">string.isNumber</span>(st)

- Checks if a string contains numeric characters only.
- Parameters:
    - ***st:*** The string to be checked.
- Returns: `true` if all characters are numeric, `false` otherwise.
- Aliases:
    - <span style="color:green; font-style:italic;">string.isNumeric</span>

---
### string.valueOf
<span style="color:green; font-weight:bold;">string.valueOf</span>(obj)

- Retrieves string value of an object.
- Parameters:
    - ***obj:*** Object instance to be converted.
- Returns: String value of object.

---
### string.trim
<span style="color:green; font-weight:bold;">string.trim</span>(st)

- Removes leading & trailing whitespace from a string.
- Parameters:
    - ***st:*** The string to be trimmed.
- Returns: Trimmed string.

---
### string.ltrim
<span style="color:green; font-weight:bold;">string.ltrim</span>(st)

- Removes leading whitespace from a string.
- Parameters:
    - ***st:*** The string to be trimmed.
- Returns: Trimmed string.

---
### string.rtrim
<span style="color:green; font-weight:bold;">string.rtrim</span>(st)

- Removes trailing whitespace from a string.
- Parameters:
    - ***st:*** The string to be trimmed.
- Returns: Trimmed string.

---
### string.builder
<span style="color:green; font-weight:bold;">string.builder</span>(st)

- Creates a new instance of [java.lang.StringBuilder][].
- Parameters:
    - ***st:*** (optional) String to append on instantiation.
- Returns: new StringBuilder instance.


[java.lang.StringBuilder]: https://docs.oracle.com/javase/8/docs/api/java/lang/StringBuilder.html
