# bank-of-react

https://bank-of-react-b745wfs0u-ajlapid718.vercel.app/debits
https://bank-of-react-b745wfs0u-ajlapid718.vercel.app/credits


Updating the Account Balance

```
Making the Account Balance dynamic:

GIVEN I am on any page displaying the Account Balance
WHEN I view the Account Balance display area
THEN I should see an Account Balance that accurately represents my Debits subtracted from my Credits
AND I should be able to see a negative account balance if I have more Debits than Credits
```

Adding Debits

```
Viewing the Debits page:

GIVEN I am on the Home Page
WHEN I click on 'Debits'
THEN I should be redirected to the Debits page
AND I should see a title of 'Debits' on the page
```
```
Displaying debits:

GIVEN I am on the Debits page
WHEN I view the Debits display area
THEN I should see all of my debits displayed
AND each Debit should display a Debit description
AND each Debit should display a Debit amount
AND each Debit should display a Debit date
```
```
Adding debits:

GIVEN I am on the Debits page
WHEN I enter a new Debit description
AND WHEN I enter a new Debit amount
AND WHEN I click 'Add Debit'
THEN I should see my new debit added to the Debits display area with the current date
AND I should see my Account Balance updated to reflect the new Debit
```
```
Viewing the Account Balance on the Debits page:

GIVEN I am on the Debits page
WHEN I view the Account Balance display area
THEN I should see my Account Balance displayed
```

Adding Credits

```
Viewing the Credits page:

GIVEN I am on the Home Page
WHEN I click on 'Credits'
THEN I should be redirected to the Credits page
AND I should see a title of 'Credits' on the page
```
```
Displaying credits:

GIVEN I am on the Credits page
WHEN I view the Credits display area
THEN I should see all of my Credits displayed
AND each Credit should display a Credit description
AND each Credit should display a Credit amount
AND each Credit should display a Credit date
```
```
Adding Credits:

GIVEN I am on the Credits page
WHEN I enter a new Debit description
AND WHEN I enter a new Debit amount
AND WHEN I click 'Add Debit'
THEN I should see my new debit added to the Credits display area with the current date
AND I should see my Account Balance updated to reflect the new Debit
```
```
Viewing the Account Balance on the Credits page:

GIVEN I am on the Credits page
WHEN I view the Account Balance display area
THEN I should see my Account Balance displayed
```

