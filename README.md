# Common Core Math Standards in many formats

## Data Dictionary

> **NOTE:** Markdown table made with [MarkdownTableMaker for Google Sheets][mtm]

|  **-** | **ID** | **KEY** | **TYPE** | **CATEGORY** | **DOMAIN** | **DETAILS** |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
|  ***datatype*** | `integer` | `string` | `string` | `string` | `string` | `string` |
|  ***model type*** | `integer` | `string` | `Enum` | `Enum` | `Enum` | `string` |
|  ***description*** | unique number for each of the 509 math standards | CCSS.MATH .CONTENT.* | standard or substandard | Grade Level and Topic | Skills or topics based on KEY | The actual standard, describing the item to be learned. |

> **NOTE:** The words `KEY` and `DETAILS` are used for clarity. `KEY` always refers to the standard notation with grade level, domains, and standards. `DETIALS` always refers to the standard in the form of words, phrases, or sentences.

# Formats

## Text files
  + `cccssmath.tsv` - entire file is searchable on GitHub
  + `cccssmath-withid.tsv` - adds `ID` column to `cccssmath.tsv`
    + Useful for cross-referncing between standards
    + Useful for differentiating between very similar standards
    + Useful for keeping track of all 509 math standards (like on flashcards)
    + Easier to use numbers than "K-12 sorting" the keys

## Workbooks
  + `cccssmath.xlsx` - Microsoft Excel spreadsheet
  + `cccssmath.ods` - OpenDocument spreasheet
    + Use with [LibreOffice](https://www.libreoffice.org)
    + Use with [Apache OpenOffice](https://www.openoffice.org)  

## Source Material
  + Commmon Core Math Standards are sourced from the official web site:
    + http://www.corestandards.org/Math/
  + For accuracy, the source material is extracted using the [CCSS Math Standards Extraction Tool (SET)][set].
  + CCSS Math SET also annotates the each standard with Category and Domain data from the source material.
  + For brevity, each standard has been shortened by removing extra examples.
  + For clarity and better machine readability, some symbols have been removed.

# Stats

## Standards vs. Substandards

|  TYPE | COUNT |
| :--- | :---: |
|  standard | 385 |
|  substandard | 124 |
|   |  |
|  **TOTAL** | **509** |

## Standards Grade Level

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
|   |  |
|  **TOTAL** | **509** |

## Standards Domain Counts

|  DOMAIN | COUNT |
| :--- | :---: |
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
|  **TOTAL** | **509** |

# License

Common Core Math Standards are provided under Public License.
  + http://www.corestandards.org/public-license/
  
Any examples or applications beyond the scope of the license are provide under the permissive [MIT Licence](LICENSE):
  + https://tldrlegal.com/license/mit-license
  + https://opensource.org/licenses/MIT


[set]: https://chrome.google.com/webstore/detail/ccss-math-set/mfhkaogejcjjoillacimdhfpjpaoekbf
[mtm]: https://gsuite.google.com/marketplace/app/markdowntablemaker/46507245362
