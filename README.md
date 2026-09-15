# Personal Budget Tracker 

## Project Description
This project is an upgraded version of the Personal Budget Tracker application. It expands upon the Week 1 layout by replacing static placeholders with interactive HTML tables, upgraded form controls, embedded multimedia elements, and advanced CSS styling.

## File Structure & Functions

* **`index.html`**:
  * **Header Logo:** Embedded an `<img>` tag next to the main title.
  * **Collapsible Section:** Uses `<details>` and `<summary>` for user instructions.
  * **Form Upgrade:** Wrapped in a `<form>` element with unique input `id` attributes and a 5-option `<select>` drop-down list (Food, Transport, Rent, Entertainment, Other).
  * **Expense Table:** Replaced placeholder text with a semantic table using `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>` containing 5 hardcoded expense items.
  * **Multimedia:** Embedded a YouTube video guide via an `<iframe>`.

* **`style.css`**:
  * Formatted tables with `border-collapse: collapse`, cell padding, and primary header background coloring.
  * Added `cursor: pointer` to button styles and row highlight colors on `tr:hover`.
  * Applied advanced CSS selectors: Descendant (`#expenses-list-section td`), Direct Child (`#add-expense-section > form`), Position (`tr:nth-child(even)`), Focus (`:focus`), and Negation (`:not()`).

* **`README.md`**:
  * Documents the project structure and explains the features built.
