#!/bin/bash

# Generate sample student data
cat <<EOF > students.csv
1,John Doe,A
2,Jane Smith,B
3,Michael Johnson,C
4,Emily Brown,A
5,David Lee,B
EOF

# Define the path to the CSV file containing student data
CSV_FILE="students.csv"

# Display the generated sample data
echo "Generated sample student data:"
cat "$CSV_FILE"
echo

# Loop through each line in the CSV file
while IFS=',' read -r id name grade
do
    # Simulate registering the student
    echo "Registering student: $name (ID: $id, Grade: $grade)"
    sleep 1  # Simulate some processing time
    
    # Output registration status
    echo "Registered student: $name (ID: $id, Grade: $grade)"
done < "$CSV_FILE"

echo "All students registered successfully."

