# Relu_Consultancy-Hiring-challenge--Web-scraper
Hiring Challenge from Relu Consultancy

You need to build a script that retrieves the delivery information for each product. To access the delivery information, you will need to hover over the Down arrow option shown in screenshot below. Your script should go through each link, retrieve the delivery information, and print the delivery information for each product line by line.

Output:
print("Standard Express,Standard Express - Collection Point,Standard Express - Pick Locker")


Product URL ="https://shopee.sg/-Sale!-DW5600-High-Quality-WaterProof-Digital-Watch-560A-i.228561211.15888274757?sp_atk=6c5f17f1-2160-4384-b42d-06cf3cee7b70&xptdk=6c5f17f1-2160-4384-b42d-06cf3cee7b70"
![Screenshot 2023-04-07 092944](https://user-images.githubusercontent.com/117152309/230538574-6d19d1eb-ba1c-45cf-8113-4cc3495797a2.png)



once you hover the mouse cursor on the shipping fees, you will see the delivery options such as "Standard Express,Standard Express - Collection Point,Standard Express - Pick Locker" we have to print this.
![Screenshot 2023-04-07 093039](https://user-images.githubusercontent.com/117152309/230538509-4460d174-2bef-4769-b759-4f9a5548ab79.png)


Input Format

No Input needed for this problem
Constraints

No Constraints
Output Format

For Multiple Delivery Option Output Format -"Delivery Option 1,Delivery Option2"
For Single Delivery Option Output Format -"Delivery Option"
Sample Output 0

Standard Express
Standard Express,Standard Express - Collection Point,Standard Express - Pick Locker
Standard Express
Explanation 0

the your code should be following to get the Output accounding to URL -

print("Standard Express")
or
print("Standard Express,Standard Express - Collection Point,Standard Express - Pick Locker")
or
print("Standard Express")
