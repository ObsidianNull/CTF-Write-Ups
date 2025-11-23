# Burp Suite Extensions

**Platform:** [TryHackMe]

**Difficulty:** [Easy]

**Date Completed:** [2025-11-23]

---

## Description

Learn how to use Extensions to broaden the functionality of Burp Suite.

---

## Category

Web Fundamentals

---

## Solution

### Initial Analysis

This room is meant to explore the modular aspects of Burp Suite, focusing on its exposed functionality that allows developers to create additional modules for the framework. We will briefly examine the API documentation and discuss the typical process of adding new modules using the Burp Suite BApp Store.

### Step-by-Step Walkthrough

#### Task 1: Introduction

Simply, read the information presented and click the check button to proceed to the next task.

#### Task 2: The Extensions Interface

This interface provides an overview of extensions loaded into the tool. Some of the components are:

- Extensions List: Displays a list of the extensions currently installed in Burp Suite for the current project. Allows us to activate or deactivate individual extensions.

- Managing Extensions: You can add, remove, or Up/Down (control the sequence in which extensions are invoked when processing traffic.)

- Details, Output, and Errors: Towards the bottom of the window, there are sections for the currently selected extension:
    - Details: Provides information about the selected extension, such as its name, version, and description.

    - Output: Extensions can produce output during their execution, and this section displays any relevant output or results.

    - Errors: If an extension encounters any errors during execution, they will be shown in this section. This is useful for debugging and troubleshooting extension issues.

Review the section and Answer the question.

> Question: Are extensions invoked in ascending (A) or descending (D) order?

> Answer: D

#### Task 3: The BApp Store

The BApp Store allows us to easily discover and integrate official extensions seamlessly into the tool. In this task we will install an extension and see what we can do with it. 

Based on messing around with the tool for a few minutes, it seems like the tool is used compare time difference between valid and invalid inputs which could be used to help determine possible valid inputs. When ready, move onto the next task.

#### Task 4: Jython

This task begins with a note that it can be skipped if using the AttackBox. If you are not using the AttackBox then simply follow the tasks instructions to implement Jython into your version of Burp Suite on your local machine. This tool is used to significantly increase the number of available extensions and enhance your capabilities in performing various security testing and web application assessment tasks.

#### Task 5: The Burp Suite API

In this section, we discuss the functionality of Burp Suite APIs. These give developers significant power and flexibility when writing custom extensions. Coding for Burp Suite can be a complex task and it goes beyond the scope of this module. PortSwigger has extensive documentation that can be used to guide extension development.


## Tools Used

- None

---

## Lessons Learned

- **Key Takeaway 1:** A good glimpse into some other functionality in Burp Suite including how to download and use Extensions

---

## References

- PortSwigger Documentation

---

## Screenshots

All screenshots for this write-up are stored in the `./images/` directory:

- None

---

## Notes

None
