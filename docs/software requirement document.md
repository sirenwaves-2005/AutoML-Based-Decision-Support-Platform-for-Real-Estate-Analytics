> Software Requirements Specification (SRS)
>
> Personal Expense Tracker
>
> Disha Khakha

**Contents**

[**1 Introduction** [**3**](#introduction)](#introduction)

[1.1 Purpose [3](#purpose)](#purpose)

[1.2 Scope [3](#scope)](#scope)

[1.3 Intended Users [3](#intended-users)](#intended-users)

[**2 Overall Description**
[**3**](#overall-description)](#overall-description)

[2.1 Product Perspective
[3](#product-perspective)](#product-perspective)

[2.2 User Characteristics
[3](#user-characteristics)](#user-characteristics)

[2.3 Operating Environment
[3](#operating-environment)](#operating-environment)

[**3 Functional Requirements**
[**4**](#functional-requirements)](#functional-requirements)

[**4 Non-Functional Requirements**
[**4**](#non-functional-requirements)](#non-functional-requirements)

[**5 Constraints** [**5**](#constraints)](#constraints)

[**6 Assumptions** [**5**](#assumptions)](#assumptions)

[**7 Conclusion** [**5**](#conclusion)](#conclusion)

# Introduction

## Purpose

The purpose of this document is to describe the requirements of the
Personal Expense Tracker application. This system is designed to help
users record, manage and analyze their daily expenses by categorizing
them and providing monthly summaries.

## Scope

The Personal Expense Tracker allows users to log expenses under
different categories, store them in a local database, and view
category-wise expenditure on a monthly basis.

The application is intended for personal use.

## Intended Users

The system is intended for:

> • Individual users managing personal finances

# Overall Description

## Product Perspective

The Personal Expense Tracker is a standalone desktop-based web
application. It consists of a frontend interface, a backend server, and
a local database. The system does not depend on any external services.

## User Characteristics

Users are expected to have basic computer knowledge. No prior technical
knowledge is required to use the application.

## Operating Environment

-   Operating System: Windows / Linux / macOS

-   Browser: Any modern web browser

-   Backend: Python Flask

-   Database: SQLite

# Functional Requirements

-   **FR1:** The system shall allow users to add new expenses.

-   **FR2:** The system shall allow users to assign a category to each
    expense.

-   **FR3:** The system shall store the expense amount, category, date,
    and an optional image of the bill.

-   **FR4:** The system shall allow users to create and manage expense
    categories.

-   **FR5:** The system shall display expenses based on a selected month
    and category.

-   **FR6:** The system shall calculate and display the total
    expenditure for each category on a monthly basis.

-   **FR7:** The system shall allow users to delete and edit an expense.

-   **FR8:** The system shall allow users to set and update their
    current bank balance.

-   **FR9:** The system shall update the bank balance automatically when
    an expense is added or income is credited.

-   **FR10:** The system shall allow users to set a monthly budget.

-   **FR11:** The system shall track the total monthly expenditure
    against the set budget.

-   **FR12:** The system shall notify the user when the monthly
    expenditure is close to exceeding the budget.

-   **FR13:** The system shall suggest expense categories in which
    spending can be reduced based on monthly expenditure patterns.

# Non-Functional Requirements

-   **NFR1:** The system should be easy to use and user-friendly.

-   **NFR2:** The system should respond to user actions within two
    seconds.

-   **NFR3:** The system should store the data securely in a local
    database.

-   **NFR4:** The system should function without internet connectivity.

# Constraints

-   The system must use SQLite as the database.

-   The backend must be implemented using Python Flask.

-   The frontend must use HTML, CSS, and JavaScript.

# Assumptions

-   The application will be used by a single user.

-   User authentication is not required.

-   The system will run on a local machine.

# Conclusion

This document defines the functional and non-functional requirements of
the Personal Expense Tracker application. The purpose of the system is
to provide a simple and efficient way for users to track and analyze
their personal expenses.
