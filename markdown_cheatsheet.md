# Headers
This is for **heading 1** </br>
This is also for ~~heading 1~~

## Heading 2
This is for *heading 2*

### Heading 3
This is for ***heading 3***


# List

This is how you list items in markdown.

1. Member 1
    * Team Leader
        * Project Owner
2. Member 2
    * Hardware
3. Member 3
    * Software
3. Member 4
    * Cheerleader

# Inserting an Image2

To insert an image, you will need to drag + hold shift + drop

![alt text](download.jpeg)

[Click here to link](https://www.google.com)

[CLick here to jump to test.md](/test/test.md)

# Code Block

To highlight or insert a particular section of code, you can do the following

1. In rapberry pi, if you want to update you will `sudo apt update`

```
from tkinter import*

main = Tk()

main.mainloop()
```

# Qoutes

A famous qoute by **Sir Isaac Newton**
> For every action, there will be a reaction.

# Tables

This is how you insert tables

|Header A|Header B|Header C|
|------:|--------|----------:|
|Row 1| Data A| Data B|
|Row 2|Data C|Data D|

```
|---:| this is to justify right
```

# Horizontal Rule

This is how you insert a section line

---


# Flowchart

```mermaid 
graph TD

A[Sensor 1] --GPIO 17--> B
B[Raspberry Pi] --> C
C[L-Acoustics K2 </br> Linear Line Array] --> A
A --> D
D --> C
```


```mermaid 
graph LR

A[Sensor 1] --GPIO 17--> B
B[Raspberry Pi] --> C
C[L-Acoustics K2 </br> Linear Line Array] --> A
A --> D
D --> C
```

```mermaid
graph LR
A[Microphone 1] --XLR--> B[Digital Audio</br>Console]
C[Microphone 2] --XLR--> B
D[Microphone 3] --XLR--> B
E[Microphone 4] --XLR--> B
B --CAT6--> F[Power Amplifier]
F --NL4--> G[Passive Speakers]
B --XLR--> H[Active Speaker]
```

# Sequence Diagram

```mermaid
sequenceDiagram;

Alice ->> Bob: Hello Bob, how are you?
Bob -->> Alice: I am good, thanks!
Alice ->> Charlie: Have you eaten?
Charlie -->> Alice: Nope, I have not!
```