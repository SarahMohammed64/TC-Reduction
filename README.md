###🧮 Optimized Item Occurrence Counter in Python
This script efficiently counts the number of times each unique item appears in a list. Unlike naive implementations that use nested loops or repeated calls to list.count(), which result in O(n²) time complexity, this solution uses a single-pass approach to achieve O(n) time complexity.

It leverages either a basic dictionary or Python's built-in collections.Counter for concise and performant execution.

###✅ Features:
Efficient O(n) time complexity using a single loop

Supports any list of hashable items (strings, numbers, etc.)

Clean, readable logic for manual dictionary counting

Optional use of collections.Counter for simplicity

###🧠 How It Works:
Iterate through the list once

For each item, increment its count in a dictionary

Return the dictionary with item frequencies
