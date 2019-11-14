---
title: /HK MO
layout: page
permalink: /hkmo/
---

[TOC]

# Hong Kong Middle Office Tasks
## Daily Tasks
### HK daily trades confirmation / settlement / fails
### DMA daily locate

#### Why

Whenever traders need to sell short a stock, they need to locate the borrow first, which trader shall do it by themselves in APAC. However for DMA trade, trader doesn't know when the trade will be executed, so we send out the daily locate email to make execution broker prepared.

#### How

In the morning, please open TradeSmart to see what is the most updated APAC locate list - and update the daily email to reflect. The email includes some locate list for London trader as well, just keep those.

### David Cook 4.5bps commission update
#### Why
David has some trades under special strategies that our commission table doesn't work for those so that we need to manually adjust.
#### How

In container - trade search - save search -> find "David Cook New 4.5bps Comm Check" -> run the search with updated date, the result should be the trades that need to update the commissions.

### Restricted CCY checking
### NAB fail check
### daily DVD & CPN posting check
### BONY file drop

#### Why

BONY CTC files are not automated yet, so need to manually saved down from emails to the folders.

#### How

There are two emails containing two files coming around 2pm to 3:15pm HKT, named "Portfolio Holdings_DD Mmm YYYY.csv" and "Transaction History Report_DD Mmm YYYY.csv". Please save them down first and move to "R:\Middle Office\Operations - Reference\Control\ManualFileDrops"

### NAB file drop

#### Why

NAB daily files are not automated yet, so we need to manually download from the NAB portal and move to folders.

#### How

Please download the daily transactions and position statements from NAB website and drop them in ""R:\Middle Office\Operations - Reference\Control\ManualFileDrops""

### Stock loan check - borrow / return
### CTC file status
Checking the file status in the CTC - Missing Feeds for each reconciliation items and chase relevant parties.
### CTC breaks checking and resolution
I am currently looking after the category "AssetServicing" and "Tax" in txn reconciliation.
All APAC names in stock loan reconciliation

## Weekly Tasks
### Upcoming coupon WHT checking
### Stamp Duty CB hedge
### SFC short selling - compliance
### DVD COUPON files sent to CITCO

## Monthly Tasks
### Excess Borrow Check
### Offshore onshore funds ratio update
### TRS reset settlement - different names

## Adhoc Tasks and Some Special Things
### Security Setup

### Counterparty Setup

### Adhoc security conversion
### TRS unwind settlement
### Positions moving

### JP DVD LOCKS

### China Domestic CB - TRS

