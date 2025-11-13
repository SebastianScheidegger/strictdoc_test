# Catalog Specification

## Introduction

### Purpose

This document describes couple of requirements related to the
application interface portal.

### References

Specifications:

- [E-Library Product Specification](Specification%20Product%20Specification.md)

## Requirements

### User name and Password validation

#### Password must be validated when the user wants to change it

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-147_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-147                                  |
| **STATUS:**      | Verified                                |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

**Children:**

- `[EL-149_532dae219592ec939c858df6868d53b6]`
  EL-149_532dae219592ec939c858df6868d53b6
- `[EL-148_532dae219592ec939c858df6868d53b6]`
  EL-148_532dae219592ec939c858df6868d53b6
- `[EL-150_532dae219592ec939c858df6868d53b6]`
  EL-150_532dae219592ec939c858df6868d53b6

#### Password must differ from the user name

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-149_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-149                                  |
| **STATUS:**      | Verified                                |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

**Parents:**

- `[EL-147_532dae219592ec939c858df6868d53b6]`
  EL-147_532dae219592ec939c858df6868d53b6

#### Password must contain at least one number

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-148_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-148                                  |
| **STATUS:**      | Verified                                |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

**Parents:**

- `[EL-147_532dae219592ec939c858df6868d53b6]`
  EL-147_532dae219592ec939c858df6868d53b6

#### Password must contain at least 8 characters

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-150_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-150                                  |
| **STATUS:**      | Verified                                |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

**Parents:**

- `[EL-147_532dae219592ec939c858df6868d53b6]`
  EL-147_532dae219592ec939c858df6868d53b6

#### User name must be validated when a new user account is created

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-101_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-101                                  |
| **STATUS:**      | Verified                                |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

**Children:**

- `[EL-146_532dae219592ec939c858df6868d53b6]`
  EL-146_532dae219592ec939c858df6868d53b6
- `[EL-152_532dae219592ec939c858df6868d53b6]`
  EL-152_532dae219592ec939c858df6868d53b6
- `[EL-151_532dae219592ec939c858df6868d53b6]`
  EL-151_532dae219592ec939c858df6868d53b6

#### User name may not contain spaces

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-146_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-146                                  |
| **STATUS:**      | Verified                                |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

**Parents:**

- `[EL-101_532dae219592ec939c858df6868d53b6]`
  EL-101_532dae219592ec939c858df6868d53b6

#### User name must be longer than 3 characters

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-152_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-152                                  |
| **STATUS:**      | Verified                                |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

**Parents:**

- `[EL-101_532dae219592ec939c858df6868d53b6]`
  EL-101_532dae219592ec939c858df6868d53b6

#### User name must contain at least one number

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-151_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-151                                  |
| **STATUS:**      | Verified                                |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

**Parents:**

- `[EL-101_532dae219592ec939c858df6868d53b6]`
  EL-101_532dae219592ec939c858df6868d53b6

### Login Screen

#### User must be informed on the login screen when Caps Lock is turned on

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-156_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-156                                  |
| **STATUS:**      | Approved                                |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

#### User may not be told if the password or user name is wrong

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-157_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-157                                  |
| **STATUS:**      | Rejected                                |

### Performance Requirements

#### System should meet the following acceptance criteria

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-159_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-159                                  |
| **STATUS:**      | Reviewed                                |

| Use Case                | Acceptable Response Time |
|-------------------------|--------------------------|
| Open Application Portal | 2 sec                    |
| Render Search Result    | 1 sec                    |
| Open Book Detail        | 0.5 sec                  |
| Open Author Detail      | 0.5 sec                  |

**COMMENT:**

Item was e-signed

Approval verdict: Approved

### Browser Compatibility

#### System must support all following web browsers

|                  |                                         |
|------------------|-----------------------------------------|
| **UID:**         | EL-160_532dae219592ec939c858df6868d53b6 |
| **POLARION_ID:** | EL-160                                  |
| **STATUS:**      | Reviewed                                |

| Browser     | Support Level                |
|-------------|------------------------------|
| IE 10       | Full Support                 |
| IE 9        | Full Support                 |
| IE 8        | Layout issues are acceptable |
| Firefox 24+ | Full Support                 |
| Chrome 32+  | Full Support                 |
