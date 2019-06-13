# Data-Quality-Checker
I'll put notes here. Feel free to give feedback... or snacks

[More Details](https://docs.google.com/document/d/1fem53kzp4PkXbNiEpmJCJsC1mjv_ELOK9bDdLi_UksA/edit?ts=5cffd8a1)

## Progress so far
[6/12]
* Can now create Unit Dictionary
    * Configuration file or Read sample Excel File
* Can now create Header format
    * Same as above

[6/13]
* Cleaning up DIFF script
    * Should now work through Terminal
      * Prints out differences in Terminal and outputs Excel file
        * Green = New
        * Red with arrow = Changed
        * Grey = Dropped
      * Keyword arguments:
        * argv[1] = Old File
        * argv[2] = New File
* Will work on other scripts soon
    1. Formatting (Order, Units, etc.) [Main Priority]
    2. Historical Data (Standard Deviation) [Backlog]
