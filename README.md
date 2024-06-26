# libreoffice-how-to
How to use LibreOffice Writer, Calc and Impress

## Writer: How to create a horizontal line in Microsoft Word and LibreOffice Writer
- Open Tools → AutoCorrect → AutoCorrect Options.
- In the Options tab, check the Apply Borders box.
- Then enter `---` and press `Enter`

Source:
- https://www.computerhope.com/issues/ch001321.htm

## General: Change Language
- https://help.libreoffice.org/3.3/Common/Selecting_the_Document_Language
- https://tipps.computerbild.de/software/officeprogramme/libreoffice-sprache-aendern-diese-moeglichkeiten-gibt-es-608435.html

## Writer: Page Margins / Seitenränder
- https://www.libreofficehelp.com/change-add-margin-writer-libreoffice/

## Writer: Page Numbers / Seitenzahl
- https://help.libreoffice.org/latest/en-US/text/swriter/guide/footer_pagenumber.html

## Calc: Pivottabelle for Fritzbox Calls
- Go to `fritz.box` → `Telefonie` → `Anrufe` → `Anrufliste` → `Alle Anrufe` → Bottom of the webpage → `Sichern`
- Download the CSV file
- Open the CSV file in LibreOffice Calc
- Delete the first row
- Highlight the full table
- Click on `Data` → `Pivot Table` → `Insert or Edit` → `Current selection` → `Ok`
- Select the following entries for the Pivot table:
  - Filters: empty
  - Column Fields: `Data`
  - Row Fields: `Name`, `Rufnummer`
  - Data Fields: `Count - Rufnummer` (Make sure to change the default value of `Sum - Rufnummer` to `Count - Rufnummer`)
  - `Ok`
- Click on the Dropdown arrow of the column `Name` and only select `(empty)`
- Highlight the newly created Pivot table
- Click on Sort (AZ/ZA or Arrow down/Arrow up)
- Sort by `Count - Rufnummer` and `Descending`
- Done
