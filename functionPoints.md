# Function Points

### A tracking system for beer warehouse inventory keeps track of what good are stored in a warehouse. As boxes of beer enter the warehouse, bar codes on the boxes that identify their contents are scanned and a record for each box is entered into a database of stored merchandise. As boxes leave the warehouse, their bar codes are scanned again by a different reader in order to remove them from the database. The bar code indicates the kind of beer and kind of container to be found in the box; a table of codes and meanings determines the correspondence between code and box contents. A user can query the inventory database for the presence or absence of particular kinds of boxes in the warehouse, Base upon the description calculate the function points of this project.

| Domain                  | Number | Multiplyer | FP  |
| ----------------------- | ------ | ---------- | --- |
| External Inputs         | 2      | 3          | 6   |
| External Outputs        | 1      | 4          | 4   |
| External Inquiries      | 1      | 2          | 2   |
| Internal Logical Files  | 2      | 10         | 20  |
| External Interfaces     | 0      | 0          | 0   |
| **Total UFP**           |        |            |**32**|