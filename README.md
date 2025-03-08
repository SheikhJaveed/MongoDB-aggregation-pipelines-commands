# MongoDB Aggregation Pipelines Examples

This repository contains examples of MongoDB aggregation pipelines, demonstrating various data transformation and analysis techniques using the MongoDB Aggregation Framework.

## 📌 What is MongoDB Aggregation?
MongoDB aggregation is a powerful framework for processing and analyzing data in a collection. It allows you to filter, group, transform, and compute aggregated results using a series of pipeline stages.


## 🚀 Aggregation Pipeline Stages
Here are some commonly used stages in MongoDB aggregation:

- `$match` → Filters documents based on conditions.
- `$group` → Groups documents by a specified key.
- `$sort` → Sorts documents by a field.
- `$project` → Reshapes documents by specifying which fields to include/exclude.
- `$limit` → Limits the number of documents in output.
- `$lookup` → Performs a left outer join to another collection.
- `$unwind` → Deconstructs an array field into separate documents.

## 🛠 How to Run Aggregations
1. Open MongoDB Shell (`mongosh`) or MongoDB Compass.
2. Select your database and collection.
3. Run an aggregation query using:
   ```js
   db.collection.aggregate(pipeline)
   ```

