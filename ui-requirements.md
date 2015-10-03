# Summary

This document provides all functional and non functional requirements which must be followed when providing the ui sdk for Business Catalyst.

# Functional requirements

1. The ui sdk must provide an easy way to aggregate components in order to create a new application.
1. The ui sdk must provide an easy way to wire components to BC APIs without developer having to code all ajax calls and intercept all responses.
1. The ui sdk must provide a unified way for handling and displaying errors.
1. The ui sdk must provide a very fast way to create forms. It would be awesome for developers to not manually write the submit logic of the form.
1. The ui sdk should be minifiable into one single file which can be referenced by developers in their applications.
1. The ui sdk must provide an easy way to create new components which can be reused by developers.
1. Each component must provide a standard api which developers can use to provide their own custom logic. (e.g: **validation**).
1. Each component must be easily configurable from the application html (databinding / event binding).

# Non functional requirements

# Terminology

| Term      | Definition |
|-----------|------------|
| Component | Code which combines html / css / javascript in order to provide custom dom elements (e.g: bc-button, bc-datagrid). |
| Component aggregation | Code which compines multiple components together in order to create complex User Interfaces. |
| BC APIs integration | Possibility to wire external data sources (bc rest apis) in components without manually writing ajax calls: e.g (list customers in a datagrid.) |