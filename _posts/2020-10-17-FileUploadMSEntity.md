---
layout: post
title:  "FileUploader MS Entities"
date:   2020-10-17
description: Describing the table contents.
comments: true
---

Following tables are part of [SpringApp-FileUploader](https://github.com/Someshbose/SpringApp) Microservice.

## CORE_FILE_STORE

| COLUMN | TYPE | FEATURE |
| ------ | ------ | ------ | 
| FILE_STORE_ID  | NUMBER | PK |
| FILE_REFERENCE_ID | VARCHAR | 
| FILE_TYPE_CODE | VARCHAR | 
| FILE_NAME | VARCHAR | 
| CHAR_SET | VARCHAR | 
| FILE_EXTENSION | VARCHAR |
| STATUS | VARCHAR | 
| SUBMITTER_EMAIL | VARCHAR |
| FILE_CONTENT | BLOB |
| CORRELATION_ID| VARCHAR|
| CREATED_BY| VARCHAR |
| CREATION_DATE | DATE|
| UPDATED_BY | VARCHAR|
| UPDATION_DATE | DATE|

## CORE_FILE_TYPE

## CORE_FILE_ACCESS