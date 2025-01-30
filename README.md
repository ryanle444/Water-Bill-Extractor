# Water-Bill-Extractor
A tool that is used to find when and how much I was charged for my water bills in bank statements.

Using pypdf, this program:
1. Reads bank statements (pdf files).
2. Finds the transactions that correlates to a water bill charge from the local county.
3. Extracts the date the transaction took place and how much I was charged for.
4. Spits it out in an Excel file.
