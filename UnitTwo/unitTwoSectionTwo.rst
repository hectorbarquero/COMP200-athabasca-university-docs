.. I'm on page 214/274 right now <-- NOT STARTED
.. No challenge work for this chapter
.. assignment 2 was submitted on 18 JAN 2025 - ID 129181


Unit two, section two
++++++++++++++++++++++
Computer systems organization




Assignment 2 (chapter two, section two)
========================================
.. this is technically part 2/2 for assignment 2. The first part is in the previous chapter, unitTwoSectionOne.rst

1. *Explain what use read-only memory (ROM) serves in the design of a computer system. What type of information is kept in ROM, and how does that information originally get into the memory?* (Chapter 5, page 270)


Read-only memory (ROM)
~~~~~~~~~~~~~~~~~~~~~~~
ROM serves an important role in computers. Unlike RAM, ROM is non-volatile meaning that the memory persists even after prolonged power interruptions or non-use. Because of this, it can hold important boot instructions which a user needs to have reliably available whenever they power on their workstation.

Unlike RAM which can be modified at active run-time, ROM can't be changed so easily. It's written onto the device during the manufacturing process and therefore immutable, although there are variants like electronically erasable programmable read-only memory (EEPROM), usually available in smaller computers like microcontrollers which can be re-programmed by a user. These exceptions are hybrids of RAM and ROM, and the textbook focuses mostly on ROM.

ROM plays an important part in computing because the type of information stored in ROM. ROM contains boot sequences, firmware, and hardware initialization instructions. The data is intended to not be easily lost or overwritten since it includes the system BIOS, or UEFI firmware in newer computers. 

If these contents were to not be available, the system could be made unusable, which is why they're stored in ROM and not in RAM.


Works cited
~~~~~~~~~~~~
Schneider, G. Michael, and Judith Gersting. Invitation to Computer Science. 6th ed., Cengage Learning, 2013.
