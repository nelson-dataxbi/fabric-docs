---
title: Known issue - Pipelines don't support Role property for Snowflake connector
description: A known issue is posted where pipelines don't support Role property for Snowflake connector.
author: mihart
ms.author: jessicamo
ms.topic: troubleshooting  
ms.date: 08/23/2024
ms.custom: known-issue-817
---

# Known issue - Pipelines don't support Role property for Snowflake connector

Pipelines don't support **Role** property for Snowflake connector.

**Status:** Open

**Product Experience:** Data Factory

## Symptoms

When trying to test the Snowflake connection, you receive an error message similar to: `Test connection operation failed. Failed to open the database connection. [Snowflake] 390201 (08004): The requested warehouse does not exist or not authorized`

## Solutions and workarounds

As a solution, you need to allocate the role to the specific warehouse for the connector to use by default.

## Next steps

- [About known issues](https://support.fabric.microsoft.com/known-issues)