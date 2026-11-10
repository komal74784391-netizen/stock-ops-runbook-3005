# Restock policy

- A SKU needs restocking when on-hand stock is below its configured threshold.
- Order quantity = threshold - current stock.
- Mark zero-stock items Critical; all other reorders are Reorder.
- Every pass updates the shared Restock Register and the runbook watchlist.
