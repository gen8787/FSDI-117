# Function Points

### A tracking system for beer warehouse inventory keeps track of what good are stored in a warehouse. As boxes of beer enter the warehouse, bar codes on the boxes that identify their contents are scanned and a record for each box is entered into a database of stored merchandise. As boxes leave the warehouse, their bar codes are scanned again by a different reader in order to remove them from the database. The bar code indicates the kind of beer and kind of container to be found in the box; a table of codes and meanings determines the correspondence between code and box contents. A user can query the inventory database for the presence or absence of particular kinds of boxes in the warehouse, Base upon the description calculate the function points of this project.
                                    num, mult, FP
external inputs (EI) - user inputs - 2, 3, 6
external outputs (EO) - user outputs - 1, 4, 4
external inquiries (EQ) - sw response - 1, 2, 2
internal logical files (ILF) - 2, 10, 20
external interfaces - ttl num external files that connect w sw - 0, 0, 0

easy, avg, complex
low, avg, high


UFP = 32
------------------------

0 - 5 deg of influence
ttl deg of i = 19


VAF = (tdi * 0.01) + 0.65
Adj FP = f(VAF * UFP) = 26.88

COCOMO
a(KLOC)^b = effort
2.5(effort)^d = time for dev