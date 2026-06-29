# Home

This is the initial screen you will see in Cashier. It displays the most relevant information and the items that require your attention.

The layout includes the navigation bar on the side and the main content area consisting of four cards showing:

- favourite accounts
- device journal
- scheduled transactions
- synchronization panel

## Favourite Accounts Card

Displays the first 5 accounts selected as Favourites.

Tapping on the card will open the [Favourite Accounts screen](favourites.md).

## Device Journal Card

Displays the list of transactions stored on the device. As other cards, it shows only the latest 5 transactions.
This is a quick indicator you can check to confirm if you have entered the latest transactions.

Tapping on Journal card will lead you to [Journal](journal.md)

## Scheduled Transactions Card

Displays the first 5 scheduled transactions, ordered by the due date.
The color also indicates whether the due date is

- in the future (green),
- today (yellow)
- overdue (red)

Tapping on the card will open [Scheduled Transactions](scheduled-transactions.md).

The dates are displayed using the Short Date preference.
The amount is displayed in one line, with the Payee being truncated based on the width of the row.

## Financial Forecast Card

This card displays the forecast for the selected period.

On the settings screen, accessible through the cog button at the top, you can set the number of days for the forecast, as well as the accounts to be included in the forecast.

The balances for the selected accounts are then projected for the period using the information from the Scheduled Transactions.

## Ledger Validity

Ledger validity is checked automatically and a warning icon is displayed in the toolbar if the ledger is not valid.
Tapping the icon will display the issues identified in the book.

## Data Files Update

A background check is performed on the files in the OPFS store, to see if the files have been modified.
If so, a refresh icon will show up in the toolbar, allowing the user to reload the Beancount files.

This is also possible to do manually from the menu item "Check Files".
