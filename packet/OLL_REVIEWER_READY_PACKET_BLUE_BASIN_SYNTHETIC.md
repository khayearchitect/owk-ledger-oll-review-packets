# OLL Reviewer-Ready Packet

Packet ID: OLL-SYN-001
Packet version: v0.2 synthetic public test
Packet period: 01 July 2026 - 31 July 2026
Prepared date: 2026-07-23
Business: Blue Basin Repairs (Synthetic)
Tool: OLL
Slogan/reference: OWK Ledger-Link

## Boundary Notice

Prepared by the business. Not professionally reviewed unless marked by a verified reviewer.

This packet uses synthetic data. It is provided for review-format testing only and is not tax, legal, accounting, payroll, or audit advice.

## Packet Purpose

This reviewer-ready packet tests whether structured business records are easier for a reviewer to inspect before formal review begins.

The packet is intended to show:

- what records are included
- what the business marked as paid, partially paid, or overdue
- what evidence is missing
- what source documents are referenced
- which gaps should be clarified before professional review

## Business Profile Summary

| Field | Value |
| :--- | :--- |
| Business name | Blue Basin Repairs (Synthetic) |
| Business activity | Small local repair and maintenance service provider |
| Trading area | KwaZulu-Natal, South Africa (synthetic) |
| Contact person | Thando M. Mhlongo (synthetic) |
| Contact email | accounts@bluebasin.example |
| Registration number | 2026/000123/07 (synthetic sample) |
| VAT status | VAT enabled for packet test |
| VAT number | 4999999999 (synthetic sample) |
| Packet currency | South African rand (ZAR) |
| VAT example rate | 15% South African VAT example |

## Reviewer Role Note

This packet is intended to help a reviewer inspect business-provided records faster.

The reviewer should still independently verify:

- tax treatment
- VAT correctness
- transaction classification
- payroll compliance
- source-document adequacy
- payment proof reliability
- whether records are complete for the review purpose

## Executive Summary

| Metric | Value |
| :--- | :--- |
| Clients included | 3 |
| Quotes included | 1 |
| Invoices included | 3 |
| Gross invoice total | R 24,150.00 |
| Business-marked paid | R 9,200.00 |
| Business-marked partially paid | R 5,000.00 of R 8,050.00 |
| Business-marked overdue | R 6,900.00 |
| Synthetic employee records | 1 |
| Open missing-information items | 7 |

## Client Register

| Client ID | Client Name | Type | VAT/Tax Identifier | Related Documents | Total Billed |
| :--- | :--- | :--- | :--- | :--- | ---: |
| CL-001 | Harbour Lane Cafe (Synthetic) | Business | VAT-SYN-HLC-001 | QUOOLL001, INVOLL001 | R 9,200.00 |
| CL-002 | North Ridge Flats (Synthetic) | Body corporate | Missing | INVOLL002 | R 8,050.00 |
| CL-003 | Moya Studio (Synthetic) | Business | Not provided | INVOLL003 | R 6,900.00 |

## Document Register

| Document | Type | Date | Recipient | Amount | Status | Source |
| :--- | :--- | :--- | :--- | ---: | :--- | :--- |
| QUOOLL001 | Quote | 2026-07-02 | Harbour Lane Cafe | R 9,200.00 | accepted, converted | source_docs/QUOOLL001.md |
| INVOLL001 | Invoice | 2026-07-05 | Harbour Lane Cafe | R 9,200.00 | business-marked paid | source_docs/INVOLL001.md |
| INVOLL002 | Invoice | 2026-07-12 | North Ridge Flats | R 8,050.00 | business-marked partially paid | source_docs/INVOLL002.md |
| INVOLL003 | Invoice | 2026-07-18 | Moya Studio | R 6,900.00 | overdue | source_docs/INVOLL003.md |
| PAYOLL001 | Payslip summary | 2026-07-31 | Lebo M. | R 7,500.00 gross | synthetic HR record | source_docs/PAYOLL001.md |
| LETOLL001 | Employment letter summary | 2026-07-01 | Lebo M. | n/a | synthetic HR record | source_docs/LETOLL001.md |

## Quote Register

| Quote | Date | Client | Amount | Status | Linked Invoice |
| :--- | :--- | :--- | ---: | :--- | :--- |
| QUOOLL001 | 2026-07-02 | Harbour Lane Cafe | R 9,200.00 | accepted | INVOLL001 |

## Invoice Register

| Invoice | Issue Date | Due Date | Client | Subtotal | VAT | Total | Lifecycle | Payment Status |
| :--- | :--- | :--- | :--- | ---: | ---: | ---: | :--- | :--- |
| INVOLL001 | 2026-07-05 | 2026-07-12 | Harbour Lane Cafe | R 8,000.00 | R 1,200.00 | R 9,200.00 | issued, sent, viewed, PDF downloaded | business-marked paid |
| INVOLL002 | 2026-07-12 | 2026-07-19 | North Ridge Flats | R 7,000.00 | R 1,050.00 | R 8,050.00 | issued, sent, viewed | business-marked partially paid |
| INVOLL003 | 2026-07-18 | 2026-07-22 | Moya Studio | R 6,000.00 | R 900.00 | R 6,900.00 | issued, sent | overdue |

## Expense Summary

Boundary: this is a simple synthetic expense-side summary. It does not claim VAT correctness or expense deductibility.

| Expense | Date | Supplier | Category | Subtotal | VAT | Total | Source | Review Note |
| :--- | :--- | :--- | :--- | ---: | ---: | ---: | :--- | :--- |
| EXP-001 | 2026-07-04 | Parts Depot (Synthetic) | Repair parts | R 1,800.00 | R 270.00 | R 2,070.00 | Missing supplier invoice | Input VAT source document missing |
| EXP-002 | 2026-07-09 | Fuel Stop (Synthetic) | Vehicle fuel | R 950.00 | R 0.00 | R 950.00 | Receipt photo not included | VAT treatment requires reviewer judgement |
| EXP-003 | 2026-07-15 | Tool Hire KZN (Synthetic) | Equipment hire | R 1,200.00 | R 180.00 | R 1,380.00 | Missing supplier VAT number | Supplier VAT identifier missing |

## Bank Statement Stub

| Field | Value |
| :--- | :--- |
| Bank account label | Primary business account |
| Statement period | 2026-07-01 to 2026-07-31 |
| Statement available | No |
| Statement reference | Not included in synthetic packet |
| Review note | Reviewer requested bank statement reference for payment traceability |

## Payment / Reference Summary

| Invoice | Business-Marked Status | Amount Paid | Payment Date | Method | Reference | Evidence Note | Unresolved Gap |
| :--- | :--- | ---: | :--- | :--- | :--- | :--- | :--- |
| INVOLL001 | business-marked paid | R 9,200.00 | 2026-07-10 | EFT | HLC-JUL-REPAIR | Client said POP was sent by email | Payment proof file missing from packet |
| INVOLL002 | business-marked partially paid | R 5,000.00 | 2026-07-18 | EFT | NRF-PART-0718 | Partial payment note captured by business | Remaining R 3,050.00 unpaid or unexplained |
| INVOLL003 | payment pending / overdue | R 0.00 | n/a | n/a | n/a | No payment reference supplied | Reviewer may need ageing/follow-up note |

## Invoice Lifecycle Summary

| Invoice | Issued | Sent | Viewed | PDF Downloaded | Payment Reference Submitted | Business-Marked Paid |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| INVOLL001 | 2026-07-05 | 2026-07-05 | 2026-07-06 | 2026-07-06 | 2026-07-10 | 2026-07-10 |
| INVOLL002 | 2026-07-12 | 2026-07-12 | 2026-07-13 | Not available | 2026-07-18 | business-marked partially paid |
| INVOLL003 | 2026-07-18 | 2026-07-18 | Not available | Not available | Not available | not business-marked paid |

## VAT / Tax Status Summary

| Item | Value |
| :--- | :--- |
| Business VAT mode | VAT enabled for packet test |
| VAT example rate | 15% |
| VAT total shown in packet | R 3,150.00 |
| VAT/tax gap | Client VAT/tax identifier missing for North Ridge Flats |
| Input VAT / expense gap | Supplier invoices and input VAT support are incomplete |

Boundary: VAT/tax correctness is not claimed. This is business-provided VAT context for reviewer inspection.

## HR / Employee Summary

| Field | Value |
| :--- | :--- |
| Employee | Lebo M. (Synthetic Employee) |
| Role | Junior repair assistant |
| Employment start date | 2026-07-01 |
| ID number status | Present in private business record, redacted in public synthetic packet |
| Tax number status | Missing |
| Payslip summaries included | 1 |
| Employment letter summaries included | 1 |
| Payroll boundary | This packet does not claim payroll compliance. |

## Source Document List

| Source | Description | Status |
| :--- | :--- | :--- |
| source_docs/QUOOLL001.md | Synthetic quote summary | Included |
| source_docs/INVOLL001.md | Synthetic invoice summary | Included |
| source_docs/INVOLL002.md | Synthetic invoice summary | Included |
| source_docs/INVOLL003.md | Synthetic invoice summary | Included |
| source_docs/PAYOLL001.md | Synthetic payslip summary | Included |
| source_docs/LETOLL001.md | Synthetic employment letter summary | Included |
| csv/clients.csv | Client register export | Included |
| csv/invoices.csv | Invoice register export | Included |
| csv/payment_evidence.csv | Payment evidence export | Included |
| csv/missing_information.csv | Missing-information export | Included |
| POP-HLC-JUL-REPAIR.pdf | Client proof of payment for INVOLL001 | Missing |

## Missing-Information Checklist

| Gap ID | Status | Category | Affected Record | Reviewer Question | Priority |
| :--- | :--- | :--- | :--- | :--- | :--- |
| GAP-001 | Pending | Payment proof | INVOLL001 | Can the business provide the actual proof of payment for reference HLC-JUL-REPAIR? | High |
| GAP-002 | Pending | Partial payment | INVOLL002 | Is the remaining R 3,050.00 still due, written off, or expected later? | High |
| GAP-003 | Pending | VAT/tax identifier | CL-002 / INVOLL002 | Does North Ridge Flats require VAT/tax identifier capture for this review? | Medium |
| GAP-004 | Pending | HR tax detail | PAYOLL001 | Is the employee tax number unavailable, pending, or intentionally absent? | Medium |
| GAP-005 | Not Applicable | Client invoice view | INVOLL003 | Was the client invoice view opened, or was the invoice only sent? | Low |
| GAP-006 | Pending | Bank statement | Payment evidence | Which bank statement line confirms INVOLL001 and INVOLL002 payment references? | High |
| GAP-007 | Pending | Input VAT / expenses | Expense summary | Are supplier invoices available to support input VAT examples? | High |

## Business-Provided Notes

- INVOLL001 was created from accepted quote QUOOLL001.
- INVOLL002 was partially paid after the client requested time to settle the remaining balance. The business has not yet marked whether the balance is still due, disputed, written off, or expected later.
- INVOLL003 was sent but no client response has been recorded.
- Employee tax number is not available in the synthetic record and should be treated as a missing HR field.

## Output / Export Inventory

This packet includes:

- packet/OLL_REVIEWER_READY_PACKET_BLUE_BASIN_SYNTHETIC.md
- csv/clients.csv
- csv/documents.csv
- csv/quotes.csv
- csv/invoices.csv
- csv/payment_evidence.csv
- csv/invoice_lifecycle.csv
- csv/hr_summary.csv
- csv/missing_information.csv
- csv/gap_status.csv
- csv/expenses.csv
- csv/bank_statement_stub.csv
- source_docs/QUOOLL001.md
- source_docs/INVOLL001.md
- source_docs/INVOLL002.md
- source_docs/INVOLL003.md
- source_docs/PAYOLL001.md
- source_docs/LETOLL001.md

## Review Questions

Please review the packet format, not the business decisions.

1. What is missing before a reviewer could start useful review?
2. Which fields are unclear?
3. Which sections are unnecessary?
4. Which sections increase confidence?
5. Would this reduce back-and-forth with a business owner?
6. Would you prefer this as a static packet, CSV files, a link, or all three?
