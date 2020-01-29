# frontend-clean-code
Frontend - Clean Code

## Total Productive Maintenance (TPM)

- Organization (Seiri)
- Tidiness (Seiton)
- Cleaning (Seiso)
- Standardization (Seiketsu)
- Dicipline (Shutsuke)

## Code
Code should be the implementation of requirements
Later equals never - LeBlnc's Law

## Tips
- Name variables in a way that is readable for humans
  - let a = 42; 🚫
  - let age = 42; ✅
- Don't mix naming conventation
  - let w_height = 480; 🚫
  - let windowHeight = 480; ✅
- Write comment where it is needed
  - const cdr = 700; 🚫
  - // Callback function debounce rate in milliseconds. 
    const callbackDebounceRate = 700;
