# Charging and Billing

## Charging

- The charging process is initiated by **Litellm**, which provides usage data in the form of tokens consumed. The **Service Portal (SP)** retrieves this token usage information from Litellm and calculates the corresponding charges based on the price configuration set up in the portal.
- Litellm tracks the tokens consumed during usage.
- Service Portal periodically retrieves the token consumption data.
- The pricing structure (e.g., cost per token by model) is defined and managed in the portal (poin 6).
- Any updates to the price configuration are immediately reflected in the calculation of charges.
- The total charge is computed by multiplying the number of tokens used with the price per token.
- Price Token by IDR (additional poin 1)

## Billing

- The billing process consolidates and manages the charges calculated during the charging phase. It involves the generation, distribution, and tracking of invoices for users or customers. This process ensures transparency, accuracy, and accountability in financial transactions.
- All charges generated from the charging system (e.g., based on token usage) are aggregated over a defined billing period (e.g., daily and monthly).
- Once charges are aggregated, the system automatically generates an invoice for the customer.
- Generated Invoices are distributed to customers via Portal and user accessible to download it.
- The System support multiple payment method (e.g., credit card, Bank Transfer)
