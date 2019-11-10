---
# Please do not edit this file directly; it is auto generated.
# Instead, please edit 06-grouped_operations_dplyr.md in _episodes_rmd/
title: "Grouped operations using `dplyr`"
teaching: 50
exercises: 30
questions:

objectives: 
- "recognise when to use grouped operations in data analysis"
- "differentiate between grouped summaries and other types of grouped operations"
- "apply grouped summaries using the `group_by()` + `summarise()` functions"
- "apply other grouped operations such as: `group_by()` + `filter()` and `group_by()` + `mutate()`"
- "recognise the importance of the `ungroup()` function"
keypoints:

source: Rmd
---



grouped summaries.

- start with `count()` (simplest of grouped operations)

- then do `group_by() %>% summarise()`

- then do `group_by() %>% mutate()`
  - one idea for this is to calculate grouped mean and calculate residual from it (concept of residual variation conditional on a variable)