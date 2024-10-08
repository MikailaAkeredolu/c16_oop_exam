# UML to OOP
- Open book, Open notes, Can Google, No AI Tools, Share Screen, and be on camera !!!

![Screenshot 2024-10-07 at 5 54 46 PM](https://github.com/user-attachments/assets/09a88ba5-e97d-4098-a3a3-816d0ac3bcf6)
### Use the UML above to answer the questions in your main method

> Create an array named **shoppingBag** that contains the 3 clothing items below:
 - clothingItem1 is a small pair of Jeans that cost $20.00
 - clothingItem2 is a medium sized T-shirt that cost $8.00
 - clothingItem3 is a large hat that only cost $2.00

> Leverage the **calculateSubTotal** method to print out the subtotal of the clothing items in the shoppingBag.
- **Sample Expected output** ```Subtotal of clothing items: $30.0```

>  Create 2 different student objects with the info below:

 **Student1's info**
 - Name: Mike.
 - Size: large
 - shoppingBag: list of clothing items.

 **Student2's info**
  - Name: Jane.
 - Size: small
 - shoppingBag: list of clothing items.
   
 > Create an array named **listOfStudents** that stores our two students (student1 and student2)
 - Use the **printInfo** method to quickly print out each student's info for all students stored in the **listOfStudents** 
 - **Sample Expected output**
   ```
      Student ID 1 :  Student Name: Mike
      Student ID 2 :  Student Name: Jane
   ```

> Invoke the **printStudentCounter** to display the number of student objects that have been created thus far
- **Sample Expected output** ```We have created 2 students in our database successfully ```


> Go back and modify your HourlyEmployee class by overloading the constructor to include an hourly employees's hourlyPay and hoursWorked when instantiated
- Use the overloaded constructor to create a new hourlyEmployee
  - Name: Alex
  - Hours Worked: 40 
  - HourlyWage: $20 per hour.
  - Size: small
  - shoppingBag: list of clothing items.
- Now inside the main method, attempt to set the hourly employee's hoursWorked to a negative number
- **Sample Expected Output** ```hoursWorked cannot be a negative number```
  
> Go back and modify your Manager class by overloading the constructor to include a manger's salary when instantiated
- Use the overloaded constructor to create a new manager
  - Name: Terry
  - Salary: $100k 
  - Size: large
  - shoppingBag: list of clothing items.

  
- Now inside the main method, print out the manager's info with the **printIfo** method
- **Sample Expected Output** 
```Terry makes 10000.0 and his shopping bag consist of the following clothing items: Jeans T-shirt Hat```


> Invoke the **printPriceAfterDiscount** method, and print out how much Alex (hourlyEmployee) will pay for clothingItem1 after discounts.
- **Sample Expected Output** ```Jeans will cost Alex : $18.0```


> Leverage the **checkFitting** method twice to check if a clothing item fits a customer
- **Sample Expected Output** ```It is true that the Hat fits Mike```

> Create a new Business object with the following info:
  - Leverage all 3 properties in your constructor
     - Business Name: Acme
     - QtySupplied: 10000
     - productPrice: 20
       
- **IMPORTANT** : In our program, businesses only pay tax on earnings over $100k

> Call the **paysTaxOnEarnings** method to check if the business above is taxable or not.
 - **Sample Expected Output** ```Is this biz taxable?: true ```

> Create an array named **payable** to store all the types of entities that are payable
- Invoke the **printClassNamesOfPayableEntities** method to print out the class names of all payable entities.
 - **Sample Expected Output** 
```
HourlyEmployee
Manager
Business
```

> Use the **checkCustomerDiscount** method to check for how much of a discount a student, hourly employee, and manager qualifies for in our app.
 - **Sample Expected Output**  
```
Student qualifies for a discount of 5.0%
HourlyEmployee qualifies for a discount of 10.0%
Manager qualifies for  a discount of 15.00%
```
***Curve ball -> Note that the manager's discount is formatted in 2 decimals***

> Create a **new Manager object but of type Customer** named customerToEmployee with the following info:
  -  Name: Rick
  -  Size: small
  -  shoppingBag: list of clothing items.
    
> Call the **managerDiscount** method on the customerToEmployee to print out the discount as formatted below:
 - **Sample Expected Output**
 - ```Rick is a manager therefore is entitled to a discount of 15%```

> Finally, invoke the **canGetFired** on the same customerToEmployee object.
  - **Sample Expected Output** ``` true ```

#### Make your repo private and DM it to me by 12:55pm. 


