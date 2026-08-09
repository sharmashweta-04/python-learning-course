# 📂 Chapter 05 - Dictionary & Sets

<div align="center">

[![Status](https://img.shields.io/badge/Status-Not%20Started-lightgrey?style=for-the-badge)](#)
[![Files](https://img.shields.io/badge/Files-0-blue?style=for-the-badge)](#)

---

This chapter introduces key-value mapping with Python Dictionaries and unordered collections of unique elements using Sets. It covers properties, operations, and common built-in methods.

</div>

## 📓 Core Topics Covered
* **Dictionaries**: Mutable collections of key-value pairs (unordered, indexed, and no duplicate keys).
  * *Properties*: Keys are unique, immutable, and map to values.
  * *Dictionary Methods*:
    * `.items()` — Returns a list of (key, value) tuples.
    * `.keys()` — Returns a list containing dictionary keys.
    * `.values()` — Returns a list containing dictionary values.
    * `.update({key: val})` — Updates/inserts key-value pairs.
    * `.get(key)` — Safely retrieves value (returns `None` instead of throwing `KeyError` if key is missing).
* **Sets**: Collection of non-repetitive (unique) elements.
  * *Properties*: Unordered, unindexed, elements cannot be changed, no duplicate values.
  * *Operations on Sets*:
    * `.add(val)` — Adds an element to the set.
    * `len()` — Gets set cardinality.
    * `.remove(val)` — Deletes element from the set (raises error if element not found).
    * `.discard(val)` — Safely deletes element from the set.
    * `.clear()` — Empties the set.
    * `.union(set2)` — Returns new set with elements from both sets.
    * `.intersection(set2)` — Returns new set with common elements.

---

## 📝 Practice Exercises (Planned)
* [ ] Create a translation dictionary (Hindi to English lookup)
* [ ] Input eight numbers and display all unique numbers
* [ ] Can we have a set with `18` (int) and `"18"` (str) as values in it?
* [ ] What is the length of set containing integers, floats and string values?
* [ ] Create an empty dictionary and allow friends to enter their favorite programming languages
* [ ] If names of two friends are same, what will happen in the dictionary?
* [ ] If favorite languages of two friends are same, what will happen?
* [ ] Can you change the values inside a list which is contained in a set?
