# MongoDB Training

## Badges

![Mongodb_badge](mongodb_badges.png)

## Difference

Two key differences b/w a relational databases (e.g., MySQL) and non-relational/document databases (e.g., MongoDB).

 > Relational databases (e.g., MySQL) use rigid tables with fixed schemas. Non-relational/document databases (e.g., MongoDB) store JSON-like documents (BSON) with **flexible schemas** (when added) that are better for evolving or unstructured data. MongoDB allows documents within the same **collection** to have different shapes when schema validation is not added (adding schema is optional, has its own set of issues though). 

> Relational databases (e.g., MySQL) usually scale vertically. Non-relational/document databases (e.g., MongoDB) supports **horizontal scaling** via **sharding** across many servers.

## Healthcare Usecase of MongoDB

> MongoDB suits managing electronic health records. EHR's have varied data types like notes, images, and results, and structured, semi-structured and unstructured data. MongoDB is flexible enough to easily handle changes and diverse data without costly migrations. Plus, MongoDB’s **replication** ensures availability, which is critical for patient care systems.