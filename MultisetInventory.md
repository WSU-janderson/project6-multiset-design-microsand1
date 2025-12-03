
# Inventory System using Multiset Design
---
## Introduction to the setting

### The context for this inventory design is related to the game, the game this inventory will be implemented into is Top down Traditional roguelike. the setting will be a military complex set in the far future. the player character is a fully atonamized mech built to scale the complex. my inventory will need multiple features such as:

* ### multiple items
* ### same name items
* ### Expandable
* ### retractable
* ### sorting
* ### search function

### therefore my design needs to store items with the same name with information such as item amount and needs to be expandable and retractable, for this reaon i'll be using **Sequence\<string>\**
---
## Why Sequence

### The reason I am using Sequence is for an easier faster implementation within the project

### Because my inventory needs to be expandable and retractable i feel that a Sequence set would be easist to modify the size of throughout the game, using A sequence would lower the development time of my project by a signifigant amount

### This Sequence will be used and interacted by the user, The in


