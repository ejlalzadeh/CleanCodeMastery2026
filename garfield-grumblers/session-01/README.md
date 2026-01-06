# Garfield Grumblers – Session 01

## TASK 1 – Code Smell Hunting

**Goal:** Identify code smells and readability issues in popular libraries. Document your strategy to clean them in `code_smells.md`.

### Target files

- [`RequestHandlerWrapper.cs` – MediatR](https://github.com/LuckyPennySoftware/MediatR/blob/be61f5a415965bf81893a05b25e0c4936079f35c/src/MediatR/Wrappers/RequestHandlerWrapper.cs#L15)
- [`Mediator.cs` – MediatR](https://github.com/jbogard/MediatR/blob/main/src/MediatR/Mediator.cs#L50)

### Instructions

1. Clone or open the code locally.  
2. Identify all smells:  
   - Long methods  
   - Confusing names  
   - Duplication  
   - Deep nesting  
   - Unclear responsibilities  
3. Document each smell in `code_smells.md` with:  
   - Line number  
   - Smell description  
   - Why it’s a problem  
   - Proposed refactor  

### Output

- `code_smells.md` file with your findings and solutions.  
- Concrete examples of refactored snippets (inline code samples).

---

## TASK 2 – Clean Code Checklist

**Goal:** Define a concrete, language-agnostic checklist for writing clean code.

### Instructions

1. Brainstorm concrete principles (not just “write clean code”) from multiple perspectives:  
   - Function / method design  
   - Naming conventions  
   - Class / module structure  
   - Error handling  
   - Testability  
2. Discuss how different programming paradigms (OOP, functional) affect these rules.  
3. Write your checklist in `clean_code_checklist.md` (5–10 concrete points).

### Output

- `clean_code_checklist.md` file with explicit, actionable rules.  
- 1–2 discussion points per rule with rationale.
