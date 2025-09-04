# Input related code
## Check boxes
 * Check all checkboxes - JavaScript
   ```javascript
   document.querySelectorAll('input[type="checkbox"]').forEach(cb => cb.checked = true);
   ```
* Uncheck all checkboxes - JavaScript
  ```
  document.querySelectorAll('input[type="checkbox"]').forEach(cb => cb.checked = true);
  ```
* Check all checkboxes - JavaScript (For react)
```javascript
document.querySelectorAll('input[type="checkbox"]').forEach(cb => cb.click());
```
