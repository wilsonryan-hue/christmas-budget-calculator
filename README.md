# Free Christmas budget calculator (UK pounds, one HTML file, nothing stored)

Enter what you can afford for Christmas, how many people you are buying gifts for and what you have already set aside. You get a pound split (gifts, food, cards and wrapping, decorations, activities, buffer), the amount to put aside each week until Christmas Eve, and a 10-row gift tracker that warns you when your planned gifts go over the gifts pot. No sign-up, no server, no cookies, no build step: it is one `index.html` file.

**Use it now, no install:** download `index.html` and open it in any browser, or use the page version with a longer how-to at [tchworks.co.uk/free/christmas-budget-calculator-uk-2026](https://www.tchworks.co.uk/free/christmas-budget-calculator-uk-2026/?utm_source=github&utm_medium=repo&utm_campaign=budget-calc-repo).

## What it does

- Splits your total as a suggestion: 50% gifts, 25% food and drink, 5% cards, postage and wrapping, 5% decorations and tree, 5% days out and activities, 10% buffer.
- Works out the gifts amount per person, the amount still to save, and a weekly saving target counted to Christmas Eve.
- Lets you change the Christmas Day date for the countdown.
- Gift tracker for 10 people: write each person's limit and see the total against the gifts pot, with a clear over or under message.
- Print button for a paper copy. Typed text is shown as text only, never run as code.

## Change the split

Open `index.html` in a text editor and edit the `SPLIT` list near the top of the script. Each row is a label and a percentage; keep them adding up to 100. The first row is treated as the gifts pot.

## Self-host

Put `index.html` on any static host (GitHub Pages, Netlify, a school or church intranet). There is nothing to configure.

## Not financial advice

It does simple arithmetic on the numbers you type in. For free, impartial help with money worries, see [MoneyHelper](https://www.moneyhelper.org.uk/) or [Citizens Advice](https://www.citizensadvice.org.uk/). This project is not affiliated with either.

## Licence

MIT. Made by [TCH Works](https://www.tchworks.co.uk/?utm_source=github&utm_medium=repo&utm_campaign=budget-calc-repo), which also publishes [Christmas cards](https://www.tchworks.co.uk/cards/christmas/?utm_source=github&utm_medium=repo&utm_campaign=budget-calc-repo), a free [Secret Santa generator](https://www.tchworks.co.uk/free/secret-santa-generator/?utm_source=github&utm_medium=repo&utm_campaign=budget-calc-repo) and a printable [Christmas Budget & Gift Planner](https://tchworks.gumroad.com/l/kazjns?utm_source=github&utm_medium=repo&utm_campaign=budget-calc-repo).
