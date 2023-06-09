# Test
### Total number of orders formula (calculated measure)
![Total number of orders formula](https://github.com/DqpM/Test/assets/133138864/16b52e36-77f1-4f6b-a6dd-d3bda04fee48)

### Total number of cookies sold (calculated measure)
![Total number of cookies sold](https://github.com/DqpM/Test/assets/133138864/ff63e4d9-7811-41a4-9f97-cd96a8e57108)

### Total profit formula (calculated measure)
![Total profit formula](https://github.com/DqpM/Test/assets/133138864/76695311-e4d8-4dfc-a723-3963025ff3c8)

### Profit margin % formula (Note! make sure to change format to percentage so that it displays percentages in the visuals)
![profit margin % formula](https://github.com/DqpM/Test/assets/133138864/5888491c-3fe4-4e5f-9a36-9cb8b6a0fe22)

### Calculated column (profit)
![Calculated column (profit)](https://github.com/DqpM/Test/assets/133138864/27819ba0-67b0-4d04-984d-300c0fd7d0a4)

### Distinct customers number
![Distinct customers number](https://github.com/DqpM/Test/assets/133138864/9b822f2b-f646-49df-9dea-6fbbbb2e8d12)

### Day of the week (calculated column)
![Day of the week (calculated column)](https://github.com/DqpM/Test/assets/133138864/7063f79c-9985-47af-9f29-83b3206d668b)

### Find specific word "Chocolate" (calculated column). If found, then put 1 in the row, if not found then put 0
![Find word Chocolate](https://github.com/DqpM/Test/assets/133138864/35620017-2b71-4fe4-bf01-47f91df6e689)

### IF function to find word Chocolate based on another calculated column (in this case "Find Chocolate" is the calculated column name that we use in IF formula)
![IF function to find a Chocolate based on another calculated column](https://github.com/DqpM/Test/assets/133138864/70dfa028-4e31-456d-a05e-8b06d3ba3e6e)

### Using CALCULATE and CONTAINSTRING function to find rows which contain the string Chocolate (calculated measure)
![Using CALCULATE and CONTAINSTRING function to find rows whcih contain the string Chocolate](https://github.com/DqpM/Test/assets/133138864/7e4ece53-fcdd-42c4-9b51-0c73d0d4ea36)

![image](https://github.com/DqpM/Test/assets/133138864/07d1fafe-9e01-4b41-9861-78fc066a9d83)

### Using CALCULATE function to aggregate and filter rows to find number of rows where the product name is exactly "Chocolate Chip" and where the Units sold are more than 500
![Using CALCULATE function and filters to find number of rows where the product name is Chocolate Chip and where the Units sold are more than 500](https://github.com/DqpM/Test/assets/133138864/2ba479d3-caf0-469a-aea0-fb2c40babf8f)

![image](https://github.com/DqpM/Test/assets/133138864/62e4c9aa-3cee-48ba-83ba-ff1e9717a50c)


### Using CALCULATE and CONTAINSSTRING functions to find number of rows where units sold are more than 500 and Product column has any products that contain string  "Chocolate"
![Using CALCULATE and CONTAINSSTRING functions to find number of rows where units sold are more than 500 and Product column has any products that contain name Chocolate](https://github.com/DqpM/Test/assets/133138864/0abf5d50-2438-4dd3-8441-254bddf18b60)

![image](https://github.com/DqpM/Test/assets/133138864/e2fd6255-b7e7-499e-ac5f-1f3a4c6eb32a)

### MAX formula to find the biggest number (Maximum) in the Revenue Column
![Formula to find the biggest number (Maximum) in the Revenue Column](https://github.com/DqpM/Test/assets/133138864/314e2145-295a-489c-9f1c-2c1bee9e9b3b)

![image](https://github.com/DqpM/Test/assets/133138864/c8ba6f39-1313-45c2-9752-b5297a5f24ca)


### IF function to create a calculated column that depending on the Revenue size will show which group does the order fall into (i.e Small, Medium or Big)
![IF function to create a calculated column that depending on the Revenue size will show which group does the order fall into (i e Small, Medium or Big)](https://github.com/DqpM/Test/assets/133138864/37e8b311-affa-4939-b55a-195424c485d4)

#### *other way to achieve the same result:*

![Other way to use IF statement to achieve the same result](https://github.com/DqpM/Test/assets/133138864/340ee819-c780-4f8f-b417-80d0297d2be9)

### Using SWITCH function to group. Note, with SWITCH function it is easier to group when you have many categories/groups (for example 5+)
![Using SWITCH function to group](https://github.com/DqpM/Test/assets/133138864/0963a7e6-5994-426a-ad45-9bf71006d2c0)

### Using SUMX function to iterate over the rows and add revenue from each row one by one
![Using SUMX function to iterate over the rows and add revenue from each row one by one](https://github.com/DqpM/Test/assets/133138864/df025122-2cf7-48d7-9acf-f3b67b559dd9)

![image](https://github.com/DqpM/Test/assets/133138864/55d6b4ad-d70d-4e1e-a07e-ab5c3cc149ab)

### Using CALCULATE function to calculate total sales (Revenue) for all orders that have grouping of "Big"
![Using CALCULATE function to calculate total sales for all orders that have grouping of Big](https://github.com/DqpM/Test/assets/133138864/22eaa53f-c546-447d-92bc-4280422d0211)

![image](https://github.com/DqpM/Test/assets/133138864/bd6af8a1-e89f-44f1-8c75-a558b69da51a)

#### *Note: You can also double check if the above formula was correct by going to your visualizations and either using the filter, to select only the "Big" category in the filter, or you can put the "Grouping of order sizes" in Rows field and "Revenue" in values field and look if the revenue for "Big" category is the same as the revenue from the DAX formula*

![image](https://github.com/DqpM/Test/assets/133138864/f1100320-1774-470a-906b-95b8767c5649)
