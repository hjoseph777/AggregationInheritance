# AggregationInheritance
This assignment is based on calculating a PhoneBill for a Customer

<p align="right">
  <img src="PhoneBill.png" alt="Phone Bill">
</p>


### Classes and Relationships

| Class              | Attributes                                                                 | Methods                                     | Relationships                                  |
|--------------------|----------------------------------------------------------------------------|---------------------------------------------|-----------------------------------------------|
| **Customer**       | - `name: String` <br> - `address: String` <br> - `currentBalance: Double`  | - `getName(): String` <br> - `getAddress(): String` <br> - `getCurrentBalance(): Double` | |
| **PhoneBill**      | - `customer: Customer` <br> - `callDuration: Integer` <br> - `callCost: Double` | - `calculateCallCost(): Double` <br> - `printBill(): void` | - **Association:** `PhoneBill` is associated with `Customer` |
| **MobilePhoneBill**| - `smsCount: Integer`                                                      | - `calculateTotalDue(): Double` <br> - `printBill(): void` | - **Inheritance:** `MobilePhoneBill` inherits from `PhoneBill` |


















# Synopsis of Phone Bill UML Class Diagram

## Classes and Attributes

### Customer class 1
**Attributes:**
- `name: String`
- `address: String` 
- `currentBalance: Double`

**Methods:**
- `getName(): String`
- `getAddress(): String`
- `getCurrentBalance(): Double`

### PhoneBill   class 2
**Attributes:**
- `customer: Customer`
- `callDuration: Integer`
- `callCost: Double`

**Methods:**
- `calculateCallCost(): Double`
- `printBill(): void`

### MobilePhoneBill class 3
**Attributes:**
- `smsCount: Integer`

**Methods:**
- `calculateTotalDue(): Double`
- `printBill(): void`

## Relationships
- **Inheritance:** `MobilePhoneBill` inherits from `PhoneBill`
- **Association:** `PhoneBill` is associated with `Customer`

---

