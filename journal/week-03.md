# Week 3

[← Back to journal index](index.md)

## Lessons — 2/2 complete

| Lesson | Status | Tasks done | Updated |
| --- | --- | --- | --- |
| Learn: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 12 | 15 Jul 2026, 01:17 |
| Practice: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 5 | 17 Jul 2026, 03:19 |

### Learn: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

**What I did**

- **Note:** The data exported contained many messy format or input such as duplicated name, inconsistent text format in both name and email adderess column, inconsistent in date format and both city with postcode were merged together in a single row.
- **Note:** Duplicated name (John Smith) with the same details across the column was deleted during table cleaning.
- **Note:** The inconsistence in both names and email address e.g case and space problem are corrected.
- **Note:** CityPostcode was splitted into different column.

### Practice: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

**What I did**

- **Applied:** Used COUNTIF to counted the value of data I have in DonorID row, identify there are duplicate and duplicated data was removed.
- **Note:** Corrected the inconsistent in capitalization on Name using =TRIME(PROPER(B2)).
- **Note:** Corrected the inconsistent in capitalization on Name using =LOWER(TRIM(C2)).
- **Applied:** Used =SUBSTITUTE(D2," ", "") to correct the inconsistence in phone numbers.
- **Verified:** The output verification shows Count: 7, SUM: 630 and AVERAGE: 90.
- **Note:** i learnt how to use necessary formula on excel to carried out the task

**Practice work**

---
<!-- framework:solve -->
