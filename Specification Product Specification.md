# E-Library Product Specification

## Introduction

This document is configured to showcase the PDF Export Watermark
feature. After selecting Operations \> Export to PDF, each page is
watermarked with an image. Rules for document watermarks can also be
specified via a plugin. This plugin lets users force watermarks based on
a custom field value like "Restricted documents".

### Purpose

A Product Specification is a complete description of the behavior of the
product to be developed. It includes a set of User Stories that describe
all the interactions that users will have with the software. In addition
to User Stories, this document also contains Requirements.

### Scope

The document describes a fictitious online eBook lending library with an
optional online eBook sales component. The focus is on simplicity rather
than depth and completeness, so that you may more easily understand the
Document's features. Not all the User Stories need to be implemented in
the 1.0 release.  The release planning is managed separately. See  .

### References

Specifications:

- [Administration
  Specification](Specification%20Administration%20Specification.md)
- [Catalog Specification](Specification%20Catalog%20Specification.md)

## Overall Description

This system provides an online portal analogous to a public library
where registered patrons can "borrow" books. The main difference being,
that the books in the library catalog are all in electronic formats that
incorporate Digital Rights Management (DRM). This lets the system “lend”
an allowed number of copies to registered users. In addition, when a
book has the proper rights, the E-Library can sell patrons a license for
a personal copy of the electronic book that they can retain permanently.

### Abbreviations and Terms

| TERM | DEFINITION |
|----|----|
| Cart | i.e. “Shopping Cart” – A collection of one or more eBooks that a patron has marked for purchase during the current session. |
| Catalog | The database of eBooks available for loan and possibly for sale. |
| Check Out | The act of “borrowing” an eBook from the library. The term is not used in reference to the process of paying for a purchased eBook. (See Purchase.) |
| Check In | The act of “returning” a previously “borrowed” (checked out) eBook. |
| DRM | Digital Rights Management |
| eBook | An electronic book or other publication lent or sold by the E-Library system. |
| ISBN | International Standard Book Number |
| LC | Library of Congress |
| Loan | See Lend. |
| Lend | The process of flagging an eBook so the appropriate DRM understands that one of the allowable number of “copies” has been allocated to a patron for the allowable lending period. |
| Patron | A user of the E-Library portal. |
| Purchase | The process by which library patrons purchase a DRM license for a personal copy of an eBook.(Also refers to the action of a user navigating through the process of purchasing the eBooks listed in their Cart.) |
| Store | An area of the portal that lists a subset of the library’s eBooks.(eBooks that users can purchase a personal copy license for.) |

## Product Backlog

### Basics

#### Basic Product Behavior

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-198_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-198                               |
| **STATUS:**      | In Progress                          |

This Epic sums up the basic behavior of the product.

**Children:**

- `[EL-107_f534bf6955ea46e7f18be344ac667]`
  EL-107_f534bf6955ea46e7f18be344ac667
- `[EL-191_f534bf6955ea46e7f18be344ac667]`
  EL-191_f534bf6955ea46e7f18be344ac667
- `[EL-105_f534bf6955ea46e7f18be344ac667]`
  EL-105_f534bf6955ea46e7f18be344ac667
- `[EL-138_f534bf6955ea46e7f18be344ac667]`
  EL-138_f534bf6955ea46e7f18be344ac667
- `[EL-139_f534bf6955ea46e7f18be344ac667]`
  EL-139_f534bf6955ea46e7f18be344ac667
- `[EL-136_f534bf6955ea46e7f18be344ac667]`
  EL-136_f534bf6955ea46e7f18be344ac667
- `[EL-137_f534bf6955ea46e7f18be344ac667]`
  EL-137_f534bf6955ea46e7f18be344ac667
- `[EL-140_f534bf6955ea46e7f18be344ac667]`
  EL-140_f534bf6955ea46e7f18be344ac667

#### User Statistics

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-107_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-107                               |
| **STATUS:**      | Verified                             |

Users should easily access information on what books they have borrowed.

**Parents:**

- `[EL-198_f534bf6955ea46e7f18be344ac667]`
  EL-198_f534bf6955ea46e7f18be344ac667

#### Password Regex

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-191_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-191                               |
| **STATUS:**      | Draft                                |

The password must fit the specified Requirements.

**Parents:**

- `[EL-198_f534bf6955ea46e7f18be344ac667]`
  EL-198_f534bf6955ea46e7f18be344ac667

#### Login Page

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-105_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-105                               |
| **STATUS:**      | Verified                             |

When users want to access the Elibrary portal they need to login and
provide valid credentials.

**Parents:**

- `[EL-198_f534bf6955ea46e7f18be344ac667]`
  EL-198_f534bf6955ea46e7f18be344ac667

#### Access the list of favorite books

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-138_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-138                               |
| **STATUS:**      | Implemented                          |

Users must be able to easily access their list of "Favorite" books.

**Parents:**

- `[EL-198_f534bf6955ea46e7f18be344ac667]`
  EL-198_f534bf6955ea46e7f18be344ac667

#### Maintain the list of favorite books

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-139_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-139                               |
| **STATUS:**      | In Progress                          |

Users should be able to maintain their list of "Favorite" books.

**Parents:**

- `[EL-198_f534bf6955ea46e7f18be344ac667]`
  EL-198_f534bf6955ea46e7f18be344ac667

#### Configure contact information

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-136_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-136                               |
| **STATUS:**      | In Progress                          |

Users must be able to configure their contact information.

**Parents:**

- `[EL-198_f534bf6955ea46e7f18be344ac667]`
  EL-198_f534bf6955ea46e7f18be344ac667

#### Mark a book as favorite

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-137_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-137                               |
| **STATUS:**      | Accepted                             |

Users must be able to mark a book as a "Favorite".

**Parents:**

- `[EL-198_f534bf6955ea46e7f18be344ac667]`
  EL-198_f534bf6955ea46e7f18be344ac667

#### Administration

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-140_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-140                               |
| **STATUS:**      | Verified                             |

Basic users may not be allowed to administer the elibrary system.

**Parents:**

- `[EL-198_f534bf6955ea46e7f18be344ac667]`
  EL-198_f534bf6955ea46e7f18be344ac667

### Book Information

#### Books

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-199_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-199                               |
| **STATUS:**      | In Progress                          |

This Epic describes the Book object.

**Children:**

- `[EL-118_f534bf6955ea46e7f18be344ac667]`
  EL-118_f534bf6955ea46e7f18be344ac667
- `[EL-116_f534bf6955ea46e7f18be344ac667]`
  EL-116_f534bf6955ea46e7f18be344ac667
- `[EL-117_f534bf6955ea46e7f18be344ac667]`
  EL-117_f534bf6955ea46e7f18be344ac667
- `[EL-130_f534bf6955ea46e7f18be344ac667]`
  EL-130_f534bf6955ea46e7f18be344ac667
- `[EL-131_f534bf6955ea46e7f18be344ac667]`
  EL-131_f534bf6955ea46e7f18be344ac667

#### Detailed book information

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-118_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-118                               |
| **STATUS:**      | Verified                             |

Users want to view additional information about a book:

- Number of pages
- Who illustrated the book
- Price

**Parents:**

- `[EL-199_f534bf6955ea46e7f18be344ac667]`
  EL-199_f534bf6955ea46e7f18be344ac667

#### Basic Book Details

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-116_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-116                               |
| **STATUS:**      | Verified                             |

Users want to view basic information about the book:

- Title
- Author
- Published date
- ISBN

**Parents:**

- `[EL-199_f534bf6955ea46e7f18be344ac667]`
  EL-199_f534bf6955ea46e7f18be344ac667

#### Summary of the book

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-117_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-117                               |
| **STATUS:**      | Accepted                             |

When viewing book details, users also want to read a book's summary
(abstract).

**Parents:**

- `[EL-199_f534bf6955ea46e7f18be344ac667]`
  EL-199_f534bf6955ea46e7f18be344ac667

#### Online services

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-130_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-130                               |
| **STATUS:**      | Accepted                             |

Users also want to easily get a list of online resources, with links to
Amazon, ReviewMyBook and other online services. This list of services
needs to be configurable.

**Parents:**

- `[EL-199_f534bf6955ea46e7f18be344ac667]`
  EL-199_f534bf6955ea46e7f18be344ac667

#### EBook - supported readers

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-131_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-131                               |
| **STATUS:**      | Verified                             |

If the book is an eBook, users must be able to get information about the
supported reader applications and platforms.

**Parents:**

- `[EL-199_f534bf6955ea46e7f18be344ac667]`
  EL-199_f534bf6955ea46e7f18be344ac667

### Author Information

#### Author

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-200_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-200                               |
| **STATUS:**      | In Progress                          |

This Epic describes the Author object.

**Children:**

- `[EL-119_f534bf6955ea46e7f18be344ac667]`
  EL-119_f534bf6955ea46e7f18be344ac667
- `[EL-121_f534bf6955ea46e7f18be344ac667]`
  EL-121_f534bf6955ea46e7f18be344ac667
- `[EL-120_f534bf6955ea46e7f18be344ac667]`
  EL-120_f534bf6955ea46e7f18be344ac667

#### Basic Author Details

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-119_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-119                               |
| **STATUS:**      | Verified                             |

When viewing a book's details, users also want to get information about
the author or authors. The details should include:

- Full name
- Date of birth
- Date of death (If deceased) 
- A list of other books written by them. (If more than 5, the 6th
  entry can be a link to a complete bibliography page.)

**Parents:**

- `[EL-200_f534bf6955ea46e7f18be344ac667]`
  EL-200_f534bf6955ea46e7f18be344ac667

#### When viewing an author's list of books, users want to see which books are stored...

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-121_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-121                               |
| **STATUS:**      | Accepted                             |

When viewing an author's list of books, users want to see which books
are stored in the library and whether or not they are currently
available for check out.

**Parents:**

- `[EL-200_f534bf6955ea46e7f18be344ac667]`
  EL-200_f534bf6955ea46e7f18be344ac667

#### Photo of an author

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-120_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-120                               |
| **STATUS:**      | Reviewed                             |

Show photo(s) of an author.

**Parents:**

- `[EL-200_f534bf6955ea46e7f18be344ac667]`
  EL-200_f534bf6955ea46e7f18be344ac667

### Searches

#### Searches

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-201_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-201                               |
| **STATUS:**      | In Progress                          |

This Epic describes all relevant information for the Search feature.

**Children:**

- `[EL-108_f534bf6955ea46e7f18be344ac667]`
  EL-108_f534bf6955ea46e7f18be344ac667
- `[EL-115_f534bf6955ea46e7f18be344ac667]`
  EL-115_f534bf6955ea46e7f18be344ac667
- `[EL-134_f534bf6955ea46e7f18be344ac667]`
  EL-134_f534bf6955ea46e7f18be344ac667
- `[EL-135_f534bf6955ea46e7f18be344ac667]`
  EL-135_f534bf6955ea46e7f18be344ac667
- `[EL-132_f534bf6955ea46e7f18be344ac667]`
  EL-132_f534bf6955ea46e7f18be344ac667
- `[EL-133_f534bf6955ea46e7f18be344ac667]`
  EL-133_f534bf6955ea46e7f18be344ac667
- `[EL-122_f534bf6955ea46e7f18be344ac667]`
  EL-122_f534bf6955ea46e7f18be344ac667
- `[EL-109_f534bf6955ea46e7f18be344ac667]`
  EL-109_f534bf6955ea46e7f18be344ac667

#### Search for a book by book name

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-108_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-108                               |
| **STATUS:**      | Verified                             |

Users typicaly search for the book by name. This feature should be
accesssible all the times.

**Parents:**

- `[EL-201_f534bf6955ea46e7f18be344ac667]`
  EL-201_f534bf6955ea46e7f18be344ac667

#### Search for an author by author name

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-115_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-115                               |
| **STATUS:**      | Verified                             |

Users want to be able to search for authors by name.

**Parents:**

- `[EL-201_f534bf6955ea46e7f18be344ac667]`
  EL-201_f534bf6955ea46e7f18be344ac667

#### Listing of the 20 most frequently borrowed eBooks.

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-134_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-134                               |
| **STATUS:**      | Verified                             |

The system should provide a way to return a list of the 20 most
frequently borrowed eBooks.

- The actual number should be configurable by an administrator.
- The UI should provide a selectable list of values: 10, 20, 25, 50, 100

**Parents:**

- `[EL-201_f534bf6955ea46e7f18be344ac667]`
  EL-201_f534bf6955ea46e7f18be344ac667

#### The listing of 10-50 recently checked books.

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-135_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-135                               |
| **STATUS:**      | Verified                             |

The system should provide an easy way to get the listing of the 10-50
(configurable) most recently checked-in eBooks.

**Parents:**

- `[EL-201_f534bf6955ea46e7f18be344ac667]`
  EL-201_f534bf6955ea46e7f18be344ac667

#### Advanced Search should provide an easy way to construct complex search queries

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-132_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-132                               |
| **STATUS:**      | Change Implementation                |

Advanced Search  should provide an easy way to construct complex search
queries based on multiple fields with different logic (e.g. AND, OR,
NOT).

**Parents:**

- `[EL-201_f534bf6955ea46e7f18be344ac667]`
  EL-201_f534bf6955ea46e7f18be344ac667

#### List of newly added books.

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-133_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-133                               |
| **STATUS:**      | Verified                             |

The system must provide an easy way to list newly added books. It can
return a listing of the 10 - 50 (configurable) most recently added
eBooks.

**Parents:**

- `[EL-201_f534bf6955ea46e7f18be344ac667]`
  EL-201_f534bf6955ea46e7f18be344ac667

#### Users like to also search for content - (Full-text search)

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-122_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-122                               |
| **STATUS:**      | In Progress                          |

Users aslo like to search for content. This requires a full-text search
option.

**Parents:**

- `[EL-201_f534bf6955ea46e7f18be344ac667]`
  EL-201_f534bf6955ea46e7f18be344ac667

#### Search for a book by advanced properties

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-109_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-109                               |
| **STATUS:**      | In Progress                          |

Users want to search for books using additional properties, for example
ISBN or date, but this advanced search should not be too complicated.

**Parents:**

- `[EL-201_f534bf6955ea46e7f18be344ac667]`
  EL-201_f534bf6955ea46e7f18be344ac667

## Administration

### User Roles

The system must provide for the following types of user accounts:

| ACCOUNT TYPE | PERMISSIONS |
|----|----|
| Administrator | Can access any component or area of the system including the accounts of other users. |
| Librarian | Can access the catalog management features of the system. |
| Patron | Can access the general library features, including browsing, searching, check out, check in, reserve, and purchase. |
| Student | Same as a Patron, except students can not access Purchase features. |

#### User Roles

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-202_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-202                               |
| **STATUS:**      | Verified                             |

This Epic sums up all the information on the User Roles feature.

**Children:**

- `[EL-143_f534bf6955ea46e7f18be344ac667]`
  EL-143_f534bf6955ea46e7f18be344ac667
- `[EL-142_f534bf6955ea46e7f18be344ac667]`
  EL-142_f534bf6955ea46e7f18be344ac667

#### System Administrator must be able to set the user roles.

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-143_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-143                               |
| **STATUS:**      | Verified                             |

**Parents:**

- `[EL-202_f534bf6955ea46e7f18be344ac667]`
  EL-202_f534bf6955ea46e7f18be344ac667

#### There are two user roles: Basic User and Administrator.

|                  |                                      |
|------------------|--------------------------------------|
| **UID:**         | EL-142_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-142                               |
| **STATUS:**      | Verified                             |

There are two user roles: Basic User and Administrator. Basic users have
no access to the administration portal.

**Parents:**

- `[EL-202_f534bf6955ea46e7f18be344ac667]`
  EL-202_f534bf6955ea46e7f18be344ac667

## Requirements

### Performance Requirements

If there are performance requirements for the product under various
circumstances, state them here and explain their rationale.This helps
developers understand the intended performance targets and make design
choices accordingly. Specify the timing relationships for real time
systems. Make these requirements as specific as possible. You may need
to state performance requirements for individual functional requirements
or features.

#### This is a sample of non functional requirement.

|                  |                                     |
|------------------|-------------------------------------|
| **UID:**         | EL-69_f534bf6955ea46e7f18be344ac667 |
| **POLARION_ID:** | EL-69                               |
| **STATUS:**      | Rejected                            |

### Safety Requirements

Specify any requirements concerned with possible loss, damage, or harm
that could result from the use of the product. Define any safeguards or
actions that must be taken, as well as actions that must be prevented.
Refer to any external policies or regulations that describe safety
issues that could affect the product’s design or use. Define any safety
certifications that must be satisfied.

### Security Requirements

Specify any requirements regarding security or privacy issues
surrounding the use of the product or the protection of data used and
created by the product. Define any user identity authentication
requirements. Refer to any external policies or regulations containing
security issues that affect the product. Define any security or privacy
certifications that must be satisfied.

### Software Quality Attributes

Specify any additional quality characteristics for the product that will
be important to either customers or developers. Some to consider are:
adaptability, availability, correctness, flexibility, interoperability,
maintainability, portability, reliability, reusability, robustness,
testability, and usability. Write these to be specific, quantitative,
and verifiable when possible. At the very least, clarify the relative
preferences for various attributes, such as ease of use over ease of
learning.

### Other Requirements

Define any other requirements not covered elsewhere in the
specification. This might include database requirements,
internationalization requirements, legal requirements, reuse objectives
for the project, and so on. Add any new sections that are pertinent to
the project.

## Appendix A: Terminology/Glossary/Definitions list

Define all the terms necessary to properly interpret this document,
including acronyms and abbreviations. You may wish to build a separate
glossary that spans multiple projects or the entire organization, and
just include terms specific to a single project in each document.

## Appendix B: Analysis Models

Optionally, include any pertinent analysis models, such as data flow
diagrams, class diagrams, state-transition diagrams, or
entity-relationship diagrams.
