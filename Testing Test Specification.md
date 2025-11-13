# E-Library Test Specification

## Introduction

### Purpose

Test Case Specification collects the test cases. Each test case
specifies inputs, predicted results, and a set of execution conditions
for a test item.

### Scope

Provide a short description of the software features being tested.

### References

Specifications:

- [Administration
  Specification](Specification%20Administration%20Specification.md)
- [Catalog Specification](Specification%20Catalog%20Specification.md)
- [E-Library Product
  Specification](Specification%20Product%20Specification.md)

## Test Cases

### Catalog Test Cases

#### Rich text book summary

|                  |                                        |
|------------------|----------------------------------------|
| **UID:**         | EL-41_a92a7e7f4a7c4b39c58d79f921d486e8 |
| **POLARION_ID:** | EL-41                                  |
| **STATUS:**      | Active                                 |

| Search for a book.  | E.g. using keywords | The results page is shown.  |
|----|----|----|
| Open a book's properties dialog. |  | The book's properties dialog is shown. |
| Check for the "Summary" field. |  | A "Summary" field is displayed in the dialog and it should contain some rich text. |

#### Open Book Properties

|                  |                                        |
|------------------|----------------------------------------|
| **UID:**         | EL-40_a92a7e7f4a7c4b39c58d79f921d486e8 |
| **POLARION_ID:** | EL-40                                  |
| **STATUS:**      | Active                                 |

| Search for a book. | E.g. using keywords | The results page is shown. |
|----|----|----|
| Double click on a book. |  | The book's properties dialog is shown. |
| Hit the "Enter" key. |  | Results are shown and the keyword is highlighted. The dialog renders nicely: name, ISBN, author, data, .. |

#### Search for book using keywords

|                  |                                        |
|------------------|----------------------------------------|
| **UID:**         | EL-39_a92a7e7f4a7c4b39c58d79f921d486e8 |
| **POLARION_ID:** | EL-39                                  |
| **STATUS:**      | Active                                 |

| Open "Search perspective". | Login to the E-Library Portal, and click search in the top left corner. | The Search page is displayed. The focus should, by default, be in the "Search" text field. |
|----|----|----|
| Type: dog. |  | dog is typed in the "Search" text field. |
| Hit the "Enter" key. |  | Results are shown and keyword is highlighted. |

#### Search for book using ISBN

|                  |                                        |
|------------------|----------------------------------------|
| **UID:**         | EL-38_a92a7e7f4a7c4b39c58d79f921d486e8 |
| **POLARION_ID:** | EL-38                                  |
| **STATUS:**      | Active                                 |

| Open "Search perspective". | Login to the E-Library Portal, and click "Search" in the top left corner. | The Search page is displayed. |
|----|----|----|
| Select "Search by ISBN". |  | There is a search via drop-down list next to the search field. |
| Type: 12-34-567. |  | The ISBN field should be validated, so you cannot click search before you enter the full number. |
| Click "Search". |  | Results are shown, 1 book should be returned. |

#### Open E-Library portal

|                  |                                        |
|------------------|----------------------------------------|
| **UID:**         | EL-37_a92a7e7f4a7c4b39c58d79f921d486e8 |
| **POLARION_ID:** | EL-37                                  |
| **STATUS:**      | Active                                 |

| Login to the E-Library portal. |  | On login the E-library portal is opened. |
|----|----|----|
| Scroll down the home page. |  | Search, add and administration portlets are rendered correctly. |

#### Login to the portal

|                  |                                        |
|------------------|----------------------------------------|
| **UID:**         | EL-36_a92a7e7f4a7c4b39c58d79f921d486e8 |
| **POLARION_ID:** | EL-36                                  |
| **STATUS:**      | Active                                 |

| Open Login Screen. | Go to the E-Library Portal welcome page and click login on the right hand corner.  | Login screen with user name and password text fields is displayed. |
|----|----|----|
| Enter incorrect User Details. | Incorrect details: admin/wrong | The login button is disabled until both user name and password is entered. |
| Click "Login". |  | Login failed message is shown. |

#### Favorite Books

|                  |                                        |
|------------------|----------------------------------------|
| **UID:**         | EL-43_a92a7e7f4a7c4b39c58d79f921d486e8 |
| **POLARION_ID:** | EL-43                                  |
| **STATUS:**      | Active                                 |

| Open the portal view. | Login to the E-Library Portal.  | Portal view is opened and different portlets are rendered there. |
|----|----|----|
| Check "Top 10 favorite books" | The portal view page shoud display the "Top 10 favorite books" portlet by default. | The portlet is displayed and it 10 books are listed. |

#### Open Author details

|                  |                                        |
|------------------|----------------------------------------|
| **UID:**         | EL-42_a92a7e7f4a7c4b39c58d79f921d486e8 |
| **POLARION_ID:** | EL-42                                  |
| **STATUS:**      | Active                                 |

| Search for a book.  | E.g. using keywords | The results page is shown.  |
|----|----|----|
| Open a book's properties dialog.  |  | The book's properties dialog is shown.  |
| Check the author's name. | The book's "Properties" dialog should show the book's author. | The author's name is displayed in the dialog and is clickable. |
| Click on the author's name. | Left click to open the "Author's Details" dialog. | The dialog is opened and renders: First name, last name, nationality, and date of birth . |

## Appendix A: Terminology/Glossary/Definitions list

Define all the terms necessary to properly interpret this document,
including acronyms and abbreviations. You may wish to build a separate
glossary that spans multiple projects or the entire organization, and
just include terms specific to a single project in each document.
