---
tags:
    - Sample
---

# Create a new text file
echo "Hello, world!" > example.txt

# Display the contents of the file
cat example.txt

# Count the number of lines in the file
wc -l example.txt

# Search for a specific word in the file
grep "world" example.txt

# Replace a word in the file
sed -i 's/world/universe/g' example.txt

# Display the modified contents of the file
cat example.txt
