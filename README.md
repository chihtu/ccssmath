# Common Core Math Standards in many formats

## Data Dictionary

> **NOTE:** Markdown table made with [MarkdownTableMaker for Google Sheets][mtm]

|  **-** | **ID** | **KEY** | **CATEGORY** | **DOMAIN** | **DETAILS** |
| ---: | :---: | :---: | :---: | :---: | :---: |
|  ***type*** | `integer` | `string` | `string` | `string` | `string` |
|  ***description*** | unique number for each of the 509 math standards | CCSS.MATH .CONTENT.* | Grade Level and Topic | Skills or topics based on KEY | The actual standard, describing the item to be learned. |

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
  + For accuracy, the source material is extracted using the CCSS Math Standards Extraction Tool (SET).
  + CCSS Math SET also annotates the each standard with Category and Domain data from the source material.
  + For brevity, each standard has been shortened by removing extra examples.
  + For clarity and better machine readability, some symbols have been removed.

# Stats

## Standards vs. Substandards

|  TYPE | COUNT |
| --- | :---: |
|  standard | 385 |
|  substandard | 124 |
|   |  |
|  **TOTAL** | **509** |

# License

Common Core Math Standards are provided under Public License.
  + http://www.corestandards.org/public-license/
  
Any examples or applications beyond the scope of the license are provide under the permissive [MIT Licence](LICENSE):
  + https://tldrlegal.com/license/mit-license
  + https://opensource.org/licenses/MIT


[mtm]: https://gsuite.google.com/marketplace/app/markdowntablemaker/46507245362
