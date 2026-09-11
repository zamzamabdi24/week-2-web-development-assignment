# My Budget Tracker

A simple and responsive budget tracker website created with HTML and CSS. The project helps users view sample expenses, understand their spending categories, and prepare for future JavaScript functionality.

## Project Description

My Budget Tracker is a beginner-friendly web project that displays a budget summary and an expense list. Users can enter an expense name, amount, category, and date using the form.

The Week 2 version includes a structured expense table, category dropdown, multimedia content, advanced CSS selectors, and an instructions section.

## Features

- Displays the total budget.
- Displays total expenses.
- Displays the remaining balance.
- Provides an Add Expense form.
- Includes a category dropdown.
- Displays five sample expenses in a table.
- Uses alternating table-row colors.
- Includes table-row hover effects.
- Includes a budgeting tip video.
- Includes a budget tracker icon.
- Includes a collapsible instructions section.
- Uses responsive CSS for smaller screens.

## Technologies Used

- HTML5
- CSS3
- Semantic HTML elements
- CSS Flexbox
- CSS media queries
- CSS pseudo-classes

## Project Files

```text
budget-tracker/
│
├── index.html
├── style.css
└── README.md
```

## How to Run the Project

1. Download or clone this repository.
2. Open the project folder.
3. Make sure `index.html` and `style.css` are in the same folder.
4. Open `index.html` in a web browser.

You can also use Visual Studio Code with the Live Server extension to preview the project.

## How to Use the Tracker

1. Open the website in a browser.
2. Review the budget summary.
3. Enter an expense name.
4. Enter the expense amount.
5. Select a category from the dropdown menu.
6. Choose the expense date.
7. Click the **Add Expense** button.

The button is currently for display only. JavaScript functionality will be added in a future week.

## Expense Categories

The available categories are:

- Food
- Transport
- Rent
- Entertainment
- Other

## Sample Expenses

The project includes the following sample expenses:

| Name | Amount | Category | Date |
|---|---:|---|---|
| Groceries | KSh 2,500 | Food | 2026-09-01 |
| Bus fare | KSh 300 | Transport | 2026-09-02 |
| House rent | KSh 25,000 | Rent | 2026-09-03 |
| Movie ticket | KSh 1,200 | Entertainment | 2026-09-05 |
| Mobile airtime | KSh 500 | Other | 2026-09-07 |

## CSS Selectors Used

The project demonstrates several advanced CSS selectors:

```css
.add-expense-section > form
```

This is a direct-child selector.

```css
.expenses-section td
```

This is a descendant selector.

```css
tbody tr:nth-child(even)
```

This styles alternating table rows.

```css
input:not([type="submit"])
```

This selects inputs that are not submit buttons.

```css
input:focus
```

This changes the appearance of an input while it is selected.

```css
tbody tr:hover
```

This changes the table-row background when the mouse moves over it.

## Future Improvements

- Add JavaScript functionality to the form.
- Add new expenses to the table automatically.
- Calculate the total expenses dynamically.
- Calculate the remaining balance automatically.
- Add the ability to delete expenses.
- Store expenses using browser local storage.
- Add charts showing spending by category.

## Author

Created by **Zamzam Ismail Abdi**.

## License

This project is created for educational purposes.
