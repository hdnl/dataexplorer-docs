---
title: Delete extent tags retention policy management - Azure Data Explorer
description: This article describes the delete extent tags retention policy command in Azure Data Explorer.
ms.reviewer: yonil
ms.topic: reference
ms.date: 02/21/2023
---
# .delete extent tags retention policy

Deletes a table-level or database-level extent tags retention policy. For more information, see [extent tags retention policy](extent-tags-retention-policy.md).

## Permissions

You must have at least [Database Admin](access-control/role-based-access-control.md) permissions to run this command.

## Syntax

```kusto
.delete table table_name policy extent_tags_retention

.delete database database_name policy extent_tags_retention
```

## Example

Delete the extent tags retention policy for the table named `MyTable`:

```kusto
.delete table MyTable policy extent_tags_retention
```
