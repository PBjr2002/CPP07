# CPP07

## Project Overview

This project focuses on C++ templates, exploring their usage for generic programming. The exercises demonstrate fundamental template concepts including function templates, template instantiation, and template classes.

---

### Exercise 00: Start with a few functions

Implement basic function templates for common operations.

**Key Concepts**:
- Function template syntax
- Template parameter deduction
- Generic programming basics

---

### Exercise 01: Iter

Create a template function that applies a function to each element of an array.

**Key Concepts**:
- Template functions with multiple parameters
- Function pointers as template parameters
- Safe array iteration

---

### Exercise 02: Array

Implement a template class for dynamic arrays with bounds checking.

**Key Concepts**:
- Template classes
- RAII (Resource Acquisition Is Initialization)
- Exception handling
- Deep copy semantics

---

## Key Learning Points

### Template Syntax
- Function templates: `template<typename T>`
- Class templates: `template<typename T> class Array`
- Template specialization and instantiation

### Template Parameters
- Type parameters (`typename T`)
- Non-type parameters (for sizes, values)
- Template template parameters
- Parameter packs (advanced)

### Template Instantiation
- Implicit instantiation through usage
- Explicit instantiation
- Template argument deduction

### Best Practices
- Use `typename` for dependent types
- Implement proper copy semantics for template classes
- Handle edge cases (null pointers, empty arrays)
- Provide meaningful error messages
