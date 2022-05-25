## Divergent Shop Data

This repository is based on the classic dbt project [jaffle_shop](https://github.com/dbt-labs/jaffle_shop)

This repo is ONLY AND ONLY created with the ONLY purpose of loading raw data into Snowflake so it is available for training purposes

- This repository is NOT an example on how dbt should be used
- dbt is NOT a loading tool
- dbt is a TRANSFORMATION tool
- In this repository dbt is used to EMULATE the role of a data loading tool such as Fivetran

### What's in this repo?
This repo contains [seeds](https://docs.getdbt.com/docs/building-a-dbt-project/seeds) that includes some (fake) raw data from a fictional app.

The raw data consists of customers, orders, and payments, with the following entity-relationship diagram:

![Jaffle Shop ERD](/etc/jaffle_shop_erd.png)

### What is a jaffle?
A jaffle is a toasted sandwich with crimped, sealed edges. Invented in Bondi in 1949, the humble jaffle is an Australian classic. The sealed edges allow jaffle-eaters to enjoy liquid fillings inside the sandwich, which reach temperatures close to the core of the earth during cooking. Often consumed at home after a night out, the most classic filling is tinned spaghetti, while my personal favourite is leftover beef stew with melted cheese.
