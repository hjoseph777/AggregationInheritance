# AggregationInheritance
This repository contains an assignment focused on calculating a Customer's phone bill. It includes the implementation of several classes and their relationships, along with their attributes and methods.

<p align="center">
  <img src="PhoneBill.png" alt="Phone Bill">
</p>



### Classes and Relationships

|Class               | Attributes                                                                 | Methods                                     | Relationships                                  |
|--------------------|----------------------------------------------------------------------------|---------------------------------------------|-----------------------------------------------|
| **Customer**       | - `name: String` <br> - `address: String` <br> - `currentBalance: Double`  | - `getName(): String` <br> - `getAddress(): String` <br> - `getCurrentBalance(): Double` | |
| **PhoneBill**      | - `customer: Customer` <br> - `callDuration: Integer` <br> - `callCost: Double` | - `calculateCallCost(): Double` <br> - `printBill(): void` | - **Association:** `PhoneBill` is associated with `Customer` |
| **MobilePhoneBill**| - `smsCount: Integer`                                                      | - `calculateTotalDue(): Double` <br> - `printBill(): void` | - **Inheritance:** `MobilePhoneBill` inherits from `PhoneBill` |






Author Harry Joseph  Date: December 9, 2024
[Github](https://github.com/hjoseph777)













