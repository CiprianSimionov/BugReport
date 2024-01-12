# Bug samples
----------------------------------------------------------------

I've created and listed below a few bug samples documented with Jira

![jiraSample](https://github.com/CiprianSimionov/BugReport_Samples/assets/26772192/4e057f0c-1fc4-49bd-9cc3-57943de60269)

--------------------------------------------------------------
## Set item quantity to 0
------------------------------------------------------------
*Priority & Severity*

P3 Normal

*Description* 

Item is not removed from cart when quantity is set to zero.

*Steps to reproduce*

1. Access https://www.gotica.ro/cos-produse.html?v2.2
2. Add at least one item to shopping cart
3. Set item quantity to 0

*Expected results*

The item should be removed from cart
The cart total price should be updated
 
*Actual results*

When item quantity is set to 0, the item is not removed, and is set by default to 1

![set item quantity to 0](https://github.com/CiprianSimionov/BugReport_Samples/assets/26772192/878ed529-e5d1-466d-83f1-1dfda19f0f50)

--------------------------------------------------------------
## Broken link
------------------------------------------------------------
*Priority & Severity*

P3 Normal

*Description* 

When trying to access following report link, it throws an error with content not found.

*Steps to reproduce*

1. Access https://www.primariabistrita.ro/rapoarte/ 
2. Select “Raport primar”

*Expected results*

Accessing “Raport primar” link should redirect and download specific resource.
 
*Actual results*

Accessing link triggers 404 error page.

![broken link](https://github.com/CiprianSimionov/BugReport_Samples/assets/26772192/9b488fde-f825-458f-ac67-87ad22df116a)

--------------------------------------------------------------
## Button contrast issue
------------------------------------------------------------
*Priority & Severity*

P4 Normal

*Description* 

When clicking on welcome button and move pointer from selected element, contrast does not change.

*Steps to reproduce*

1. Click on “welcome user” button
2. Hover mouse over it
3. Leave pointer from selected element

*Expected results*

While clicking and leaving selected element, it should reverse to its original contrast state.
 
*Actual results*

Onmouseleave, selected element stays defocused and loose contrast

![contrast](https://github.com/CiprianSimionov/BugReport_Samples/assets/26772192/3ec56b1c-7b99-423e-aaba-7ca5576ef38a)

--------------------------------------------------------------
## Overlapping Dropdown menu
------------------------------------------------------------
*Priority & Severity*

P1 High

*Description* 

Dropdown menu is overlapping navbar section

*Steps to reproduce*

1. Access https://www.gotica.ro/
2. hover mouse over "Incaltaminte" list
3. click on it to focus
4. hover mouse over "Copii" list

*Expected results*

On mouse leave "Incaltaminte" list should not be focused
"Copii" list should be highlighted and a dropdown menu should open
 
*Actual results*

Highlighted list overlaps "Copii" list

![onmousefocus](https://github.com/CiprianSimionov/BugReport_Samples/assets/26772192/ada739ea-f418-4ec6-a368-4d4ece21703b)

--------------------------------------------------------------
## Language selection is not working
------------------------------------------------------------
*Priority & Severity*

P2 Major

*Description* 

When changing the language of the website, a message displays that selected language has been changed, with no real effects.

*Steps to reproduce*

1.Go to https://juice-shop.herokuapp.com/#/
2.Click on “Choose language”
3.Select “Portugues”

*Expected results*

Each section should be translated into selected language.
 
*Actual results*

Some languages are not translated.

![language translation](https://github.com/CiprianSimionov/BugReport_Samples/assets/26772192/c65e85fa-6b09-47ee-b006-4bae228b0cb9)

--------------------------------------------------------------
## The body in "About us" section has placeholder text displayed
------------------------------------------------------------
*Priority & Severity*

P2 Major

*Description* 

The “About us” section is set by default with placeholder text.

*Steps to reproduce*

1.Go to https://juice-shop.herokuapp.com/#/
2.Click on “Open side menu”
3.Click on “About us”

*Expected results*

The “About us” section should share information regarding the website.
 
*Actual results*

There is a placeholder text displayed.

![About Us - placeholder](https://github.com/CiprianSimionov/BugReport_Samples/assets/26772192/f18f59dd-b29e-405d-b984-29412d541596)

--------------------------------------------------------------
## Document is missing
------------------------------------------------------------
*Priority & Severity*

P2 Major

*Description* 

When trying to access pdf document “petitie_persoana_fizica.php“ it triggers an 404 error not found.

*Steps to reproduce*

1.Access https://www.primariatechirghiol.ro/
2.Open dev tools
3.Inspect error in console and network section

*Expected results*

The document should be publicly available.
 
*Actual results*

The document is missing with an 404 error thrown.

![missing document](https://github.com/CiprianSimionov/BugReport_Samples/assets/26772192/f5a9f9f6-6a7a-4987-9cea-a970f70a47e3)

--------------------------------------------------------------
## Missing URL attribute
------------------------------------------------------------
*Priority & Severity*

P4 Minor

*Description* 

When trying to click on header social icons, there is no redirect to specific pages.

*Steps to reproduce*

1.Access https://www.gotica.ro/
2.On top navbar menu and click on social icons

*Expected results*

Customer should be redirected to required page links.
 
*Actual results*

Customer is not redirected to required pages.

![navbar-icons href](https://github.com/CiprianSimionov/BugReport_Samples/assets/26772192/1bfaea4f-e689-4aef-8eb3-45fa5e9aff3c)









