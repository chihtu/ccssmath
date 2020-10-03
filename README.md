# Common Core Math Standards in many formats
  + There are 517 Math standards.
  + Standards include math practices and content area standards.
  + Math symbols use Unicode superscripts and subscripts (without HTML).
  + Formats include text files and workbooks (e.g., spreadsheets).
  + Formats now include JSON files.
  + Formats now include SQL files.
  + Use keyword `ccssmath` to search for Math standards with the [**CCSS MATHREF Chrome extension**][ref].
  + **FOR DEVELOPERS:** Source material extracted with the [**CCSS Math Standards Extraction Tool (SET)**][set].

> **NOTE:** Looking for [Common Core English Language Arts standards](https://github.com/pvtuhs/ccssela)?

# Table of Contents
  + [Data Dictionary](#data-dictionary)
  + [Formats](#formats)
  + [CCMS Stats](#common-core-math-standards-statistics)
  + [Source Material](#source-material)
  + [References](#references)
  + [License](#license)


# Data Dictionary

> **NOTE:** Markdown table made with [MarkdownTableMaker for Google Sheets][mtm]

|   | ID | KEY | TYPE | CATEGORY | SECTION | DOMAIN | GRADELEVEL | DETAILS |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|  ***datatype*** | `Integer` | `String` | `String` | `String` | `String` | `String` | `String` | `String` |
|  ***model type*** | `Integer` | `String` | `Enum` | `String` | `Enum` | `Enum` | `Enum` | `String` |
|  ***description*** | unique number for each of the 509 math standards | CCSS.MATH.*  | standard or substandard | grade level and/or topics | section of the standards with similar characteristics | skills or topics based on KEY | grade level or grade level grouping | actual standard, describing the item to be learned |


> **NOTE:** The words `KEY` and `DETAILS` are used for clarity. `KEY` always refers to the standard notation with grade level, domains, and standards information. `DETAILS` always refers to the standard in the form of words, phrases, or sentences.

# Formats

## Text files
  + `ccssmath.tsv`
    + Tab-separated values (TSV) text file
    + This file is [searchable on GitHub](https://github.com/pvtuhs/ccssmath/blob/master/text/ccssmath.tsv)
    + Imports into spreadsheets or databases
    + `ccssmath.txt` - backwards-compatible equivalent of `ccssmath.tsv`
  + `ccssmath-withid.tsv`
    + Adds ID column to each record in `ccssmath.tsv` as a primary key
    + This file is [searchable on GitHub](https://github.com/pvtuhs/ccssmath/blob/master/text/ccssmath-withid.tsv)
    + Useful for cross-referncing between standards
    + Useful for differentiating between very similar standards
    + Useful for keeping track of all 517 math standards (like on flashcards)
    + Sorting the numbers is easier than "K-12 sorting" the keys
    + `ccssmath-withid.txt` - backwards-compatible equivalent of `ccssmath-withid.tsv`

## Workbooks
  + `ccssmath.xlsx` - Microsoft Excel spreadsheet
      + Use with [Google Sheets](https://www.google.com/sheets/about/).
      + Use with [Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel).
      + Use with [Zoho Sheet](https://www.zoho.com/sheet/).
  + `ccssmath.ods` - OpenDocument spreasheet
    + Use with [LibreOffice](https://www.libreoffice.org).
    + Use with [Apache OpenOffice](https://www.openoffice.org).

## JSON files
  + `ccssmath.json`
    + JavaScript Object Notation
    + Delivers math standards as a structured data object.
    + Useful for developers.

## SQL files
  + `sqlite-ccssmath.sql`
    + Use with [SQLite.](https://www.sqlite.org/index.html)
    + Useful for database developers.
    + Useful for complex data analysis.
    + From shell: `$ sqlite3 filename.sqlite`
    + In `sqlite3`:
      + Run the script: `sqlite> .read sqlite-ccssmath.sql`
      + View the tables: `sqlite> .tables`


# Source Material
  + Commmon Core Math Standards are sourced from the official web site:
    + http://www.corestandards.org/Math/
  + For accuracy, the source material is extracted using the [**CCSS Math Standards Extraction Tool (SET)**][set].
  + CCSS Math SET also annotates the each standard with Category and Domain data from the source material.
  + For brevity, each standard has been shortened by removing extra examples.
  + For clarity and better machine readability, some symbols have been removed.

# Common Core Math Standards Statistics

## Standards vs. Substandards

> **NOTE:** Markdown table made with [MarkdownTableMaker for Google Sheets][mtm]

|  TYPE | COUNT |
| :--- | :---: |
|  standard | 393 |
|  substandard | 124 |
|   |  |
|  **TOTAL** | **517** |

## Standards Grade Level

> **NOTE:** Markdown table made with [MarkdownTableMaker for Google Sheets][mtm]

|  GRADE LEVEL | COUNT |
| :--- | :---: |
|  Kindergarten | 25 |
|  Grade 1 | 24 |
|  Grade 2 | 28 |
|  Grade 3 | 37 |
|  Grade 4 | 37 |
|  Grade 5 | 40 |
|  Grade 6 | 47 |
|  Grade 7 | 43 |
|  Grade 8 | 36 |
|  High School | 192 |
|  K-12 | 8 |
|   |  |
|  **TOTAL** | **517** |

## Standards Domain Counts

> **NOTE:** Markdown table made with [MarkdownTableMaker for Google Sheets][mtm]

|  DOMAIN | COUNT |
| :--- | :---: |
|  Mathematical Practices | 8 |
|  Counting and Cardinality | 10 |
|  Geometry | 43 |
|  Measurement and Data | 50 |
|  Number and Operations in Base Ten | 39 |
|  Operations and Algebraic Thinking | 34 |
|  Number and Operations with Fractions | 37 |
|  Expressions and Equations | 31 |
|  The Number System | 28 |
|  Ratios and Proportional Relationships | 14 |
|  Statistics and Probability | 26 |
|  Functions | 5 |
|  The Complex Number System | 9 |
|  Quantities | 3 |
|  The Real Number System | 3 |
|  Vector and Matrix Quantities | 17 |
|  Arithmetic with Polynomials and Rational Expressions | 7 |
|  Creating Equations | 4 |
|  Reasoning with Equations and Inequalities | 14 |
|  Seeing Structure in Expressions | 9 |
|  Building Functions | 12 |
|  Interpreting Functions | 16 |
|  Linear, Quadratic, and Exponential Models | 8 |
|  Trigonometric Functions | 9 |
|  Circles | 5 |
|  Congruence | 13 |
|  Geometric Measurement and Dimension | 4 |
|  Expressing Geometric Properties with Equations | 7 |
|  Modeling with Geometry | 3 |
|  Similarity, Right Triangles, and Trigonometry | 13 |
|  Conditional Probability and the Rules of Probability | 9 |
|  Making Inferences and Justifying Conclusions | 6 |
|  Interpreting Categorical and Quantitative Data | 12 |
|  Using Probability to Make Decisions | 9 |
|   |  |
|  **TOTAL** | **517** |


# References

+ http://www.corestandards.org/Math/
+ http://www.corestandards.org/wp-content/uploads/Math_Standards.pdf


# License

Common Core Math Standards are provided under Public License.
  + http://www.corestandards.org/public-license/

Any examples or applications beyond the scope of the license are provided under the permissive [MIT Licence](LICENSE):
  + https://tldrlegal.com/license/mit-license
  + https://opensource.org/licenses/MIT


[ref]: https://chrome.google.com/webstore/detail/ccss-mathref/jckdedknnpncidbbaobpchejiodjmpfj
[set]: https://chrome.google.com/webstore/detail/ccss-math-set/mfhkaogejcjjoillacimdhfpjpaoekbf
[mtm]: https://gsuite.google.com/marketplace/app/markdowntablemaker/46507245362
