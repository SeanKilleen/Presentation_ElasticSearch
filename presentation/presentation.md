---
marp: true
title: "Stretching .NET: An Introduction to ElasticSearch"
theme: uncover
paginate: false
footer: "An Introduction to ElasticSearch | :earth_americas: [SeanKilleen.com](https://SeanKilleen.com) | :bird: [@sjkilleen](https://twitter.com/sjkilleen)"
class: invert
---
# Stretching .NET

#### An Introduction to ElasticSearch

[elasticsearch.seankilleen.com](https://elasticsearch.seankilleen.com)

---

# Some Love

![](./assets/images/nimblelight-logo.png)

---

<style scoped>
  ul {
    padding: 0;
    list-style: none;
  }
</style>
<!-- _footer: "" -->
![bg left 60%](./assets/images/SeanKilleen_BioPic.png)

# <!--fit--> Hi! :wave: I'm Sean

- :bird: [sjkilleen](https://twitter.com/sjkilleen)
- :earth_americas: [SeanKilleen.com](https://seankilleen.com)
- :briefcase: [Excella](https://excella.com)

---

# Let's Find a Car

---
<!-- _footer: "" -->

![bg contain](./assets/images/site_makeFilter.png)

---
<!-- _footer: "" -->

![bg contain](./assets/images/site_modelFilter.png)

---
<!-- _footer: "" -->

![bg contain](./assets/images/site_featuresFilter.png)

---
<!-- _footer: "" -->

![bg contain](./assets/images/site_mileageFilter.png)

---
<!-- _footer: "" -->

![bg contain](./assets/images/site_multiOption_Before.png)

---
<!-- _footer: "" -->

![bg contain](./assets/images/site_multiOption_After.png)

---
<!-- _footer: "" -->

![bg contain](./assets/images/site_Sort.png)

---

![bg contain](./assets/images/site_pagination.png)

---

![bg contain](./assets/images/site_textSearch.png)

---

# The Traditional Approach

---
<!-- _footer: "" -->

![bg contain](./assets/images/meme-disaster-girl.jpg)

---
<!-- _footer: "" -->

![bg contain](./assets/images/jurassicpark-screen.gif)

---

# Enter ElasticSearch

---

![bg contain](./assets/images/jurassicpark-butts.gif)

---

# &lt; 300 ms

---
<!-- _footer: "" -->
![bg contain](./assets/images/speed_proof.png)

---

#### Our Walkthrough

## Why elasticsearch

---

#### What we'll cover

## Concept Walkthrough

---

#### How is ES Different?

## Document DB

---
<!-- _footer: "" -->
![bg contain](./assets/images/json-data.png)

---

#### How is ES Different?

## Inverted Index

---
<!-- _footer: "" -->

![bg contain](./assets/images/inverted-index.jpg)

<!-- Image credit: https://www.quora.com/What-is-inverted-index-It-is-a-well-known-fact-that-you-need-to-build-indexes-to-implement-efficient-searches-What-is-the-difference-between-index-and-inverted-index-and-how-does-one-build-inverted-index -->

---

#### How is ES Different?

## Scalability

---
<!-- _footer: "" -->
![bg contain](./assets/images/buzzwords-everywhere.jpg)

---

## Think about the data

## ...like, a lot

---

## Creating the Index

---

![bg contain](./assets/images/createIndex_01_Comments.png)

---

![bg contain](./assets/images/createIndex_02_MultiField.png)

---

![bg contain](./assets/images/createIndex_03_Analyzers.png)

---

![bg contain](./assets/images/createIndex_04_Tokenizers.png)

---

#### Concept Review

# Node

---

#### Concept Review

# Index

---

#### Concept Review

# Type

---

#### Concept Review

# Mapping

---

#### Concept Review

# Multi-fields

---

#### Concept Review

# Analyzers

---

#### Analyzer Pipeline

- Input ("`Hello THERE, world!`")
- Character Filters ("`hello there world`")
- Tokenizer (`[hello, there, world]`)
- Token Filters (`[hello, world]`)
- Output

---

#### Concept Review

# Nest :heart: Lambdas

---

# Adding Data

---

![bg contain](./assets/images/vehicle_01_IdField.png)

---

![bg contain](./assets/images/vehicle_02_OtherFields.png)

---

![bg contain](./assets/images/AddOrUpdate_01_BulkIndex.png)

---

#### Concept Review

# Surface Data Correctly

---

#### Concept Review

# Indexing

---

# Retrieving

---

![bg contain](./assets/images/GetAll.png)

---

![bg contain](./assets/images/GetByVin_01_Signature.png)

---

![bg contain](./assets/images/GetByVin_02_FilterSetup.png)

---

![bg contain](./assets/images/GetByVin_03_Search.png)

---

![bg contain](./assets/images/GenerateCountAggregation.png)

---

#### Concept Review

# Query

---

#### Concept Review

# Filters

---

#### Concept Review

# Aggregation

---

# Searching

---

![bg contain](./assets/images/Search_01_HighLevel.png)

---

![bg contain](./assets/images/Search_02_CombinedFilters.png)

---

![bg contain](./assets/images/Search_03_SkipAndTake.png)

---

![bg contain](./assets/images/Search_04_Sort.png)

---
<!-- _footer: "" -->

![bg contain](./assets/images/Search_05_PerformSearch.png)

---

![bg contain](./assets/images/GenerateFilterListWithOr.png)

---

![bg contain](./assets/images/GenerateMakeModelFilters.png)

---

![bg contain](./assets/images/GeneratePriceRangeFilter.png)

---

#### Concept Review

# Paths

---

#### Concept Review

# Boolean Filters

---

#### Concept Review

# Encapsulating NEST

---

# What-if searches

---

![bg contain](./assets/images/DropFilter.png)

---

#### Concept Review

# Cheap Searches == Opportunity

---

### So much more

- Clustering
- Logstash (operations)
- Kibana (visualization)
- X Pack (security, monitoring, ML)
- Beats (shippers)

---

<style scoped>
  ul {
    padding: 0;
    list-style: none;
  }
</style>
<!-- _footer: "" -->
![bg left 60%](./assets/images/SeanKilleen_BioPic.png)

# <!--fit--> Thanks

- :bird: [sjkilleen](https://twitter.com/sjkilleen)
- :earth_americas: [SeanKilleen.com](https://seankilleen.com)
- :briefcase: [Excella](https://excella.com)
