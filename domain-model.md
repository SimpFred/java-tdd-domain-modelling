| Classes        | Variables                        | Methods                               | Scenario              | Outcomes             |
|----------------|----------------------------------|---------------------------------------|-----------------------|----------------------|
| `CashRegister` | `Map<Integer, long> weightItem`  | `getPriceForWeightItem(int PLUCode)`  | Product is in map     | Add price to total   |
|                | `Map<barcode, long> barcodeItem` | `getPriceForBarcodeItem(int barcode)` | Product is not in map | Return error message |
|                |                                  |                                       |                       |                      |
|                | `ìnt totalCost`                  | `getTotalCost()`                      | Total cost is > 0     | Return total cost    |
|                |                                  |                                       | Total cost is < 0     | Return error message |
|                |                                  |                                       |                       |                      |

| Classes       | Variables                                                   | Methods                                 | Scenario                 | Outcomes                 |
|---------------|-------------------------------------------------------------|-----------------------------------------|--------------------------|--------------------------|
| `MembersDesk` | `Map<Integer, Map<Integer, List<Receipt>>> shoppingHistory` | `getShoppingHistory(int membersNumber)` | Customer is a member     | Return list of purchases |
|               |                                                             |                                         | Customer is not a member | Return error message     |
|               |                                                             |                                         |                          |                          |
|               |                                                             | `getItemisedReceipt(int receiptNumber)` | Valid receipt number     | Return receipt           |
|               |                                                             |                                         | In valid receipt number  | Return error message     |
|               |                                                             |                                         |                          |                          |


