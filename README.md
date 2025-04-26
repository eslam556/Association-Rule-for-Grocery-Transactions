# Market Basket Analysis Using Association Rules

## Objective
The goal of this project is to apply **Market Basket Analysis** techniques to discover patterns and associations between items in grocery transactions from an Egyptian supermarket. This can help businesses optimize product offerings, manage inventory, and design marketing strategies.

## Association Rules
**Association rules** are used to find relationships between items that are frequently bought together. A rule is typically represented as:

**A → B**

This means if a customer buys item A, they are likely to also buy item B.

### Key Metrics:
1. **Support**: The percentage of transactions that contain both items A and B.
   - Formula:  
   `Support(A → B) = Transactions containing A and B / Total transactions`
   
2. **Confidence**: The probability that item B will be purchased when item A is purchased.
   - Formula:  
   `Confidence(A → B) = Transactions containing both A and B / Transactions containing A`
   
3. **Lift**: Measures how much more likely A and B are to be bought together than independently.
   - Formula:  
   `Lift(A → B) = Confidence(A → B) / Support(B)`

### Strong vs Weak Rules:
- **Strong Rules**: High confidence and lift values, showing a strong relationship between items.
- **Weak Rules**: Low confidence or lift, indicating a weaker relationship.
