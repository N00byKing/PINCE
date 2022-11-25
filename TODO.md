
---
**2022/11/24 -- Fix scrolling via the vertical scrollbar in memoryview**

+ Currently using the vertical scrollbar to scroll the disassembled instructions
in the memoryview results in endless scrolling.

---

---
**2022/11/24 -- Hex and Ascii Models in Memory View Don't show the proper values**

[fixed] + Currently the Hex and Ascii Viewer are showing black squares, or <?>, it should
  show the hex value (in the hex view) and the Ascii value (or a . for non-ascii).

[fixed] + Additionally, the hex digits are not showing two digits per entry (eg 12 34, instead of 1 3)

+ Ascii text-view has <?> for non-printable characters, this needs to be changed to .

---
