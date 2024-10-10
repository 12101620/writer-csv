# Writing with DictWriter
import csv
data = [
    ['Name', 'Age', 'Job'],
    ['Alice', '30', 'Purchaser'],
    ['Bernard', '25', 'Data Analyst'],
    ['Cecile', '42', 'HR'],
    ['Stanley', '40', 'Manager']
]
with open('output.csv', 'w', newline='') as file:
    writer = csv.writer(file)
    
 

