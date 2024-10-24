A chain of large supermarkets needs an information system to support its activities. In particular, in addition to
wanting to track each product sold per individual receipt (in each store), it also wants to associate the receipt with the
customer through a loyalty campaign, tracking information for each customer such as the number of family members,
the customer's residence, the age of the subscriber, etc. The information system must also support the chain's
administrators in managing inventory. The warehouse must never run out of a product, so when the number of
available boxes, including those on the shelves, falls below a certain threshold, it is necessary to initiate a process for
acquiring new boxes. Note that the warehouse is unique for the entire chain, which includes multiple stores, even in
different cities and regions.
• Design a domain model in UML that captures: the products for sale, the stock levels in the warehouse, and the
products actually sold.
• Design the purchasing process in BPMN initiated by the warehouse manager.
• Design a data warehouse (DW) that serves as the foundation for the analytical CRM desired by the administrators.
• Define the star schema (SS) of the designed DW from the previous step.
• Define SQL queries on the DW that allow for generating the required charts and tables for reporting.
