# Development

## Design (Part 1)
---

![IPO Diagram](images/ipo.jpg "Input-Process-Output Diagram")

The IPO diagram is a result of three prototype implementations:
1. main.c
2. u4test.c
3. 06test.c

Each file demonstrates key features the application will have (see below).

<!--- ![Random Text Input Design](images/data.gif) -->
### main.c (Generate Random Text)
---
* retrieve random words
* print words within column constraints
<img src="images/data.gif" alt="Random Text Input Design" width=600>

<!--- ![Keyboard IPO Design](images/kbd.gif) -->
### u4test.c (Keyboard I/O)
---
* char comparison feedback (green=correct, red=incorrect)
* prompt clearing on segment completion
* segment locking after completion (cannot backspace into completed segments)
<img src="images/kbd.gif" alt="Keyboard IPO Design" width=600>

<!--- ![UI Layout Design](images/ui.gif) -->
### 06test.c (UI Layout)
---
* dynamic resizing
* scrollable text region
<img src="images/ui.gif" alt="UI Layout Design" width=600>
