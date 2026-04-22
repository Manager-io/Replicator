# Replicator

A [Manager.io](https://www.manager.io) extension that copies data from one business to another.

## What it does

Select entities to copy, pick a source business and a destination business, and Replicator reads from the source and writes to the destination in batches.

Currently supported entities:

- Customers
- Suppliers
- Employees
- Inventory items
- Non-inventory items

Records keep their original keys, so re-running the replication updates existing records on the destination rather than creating duplicates.