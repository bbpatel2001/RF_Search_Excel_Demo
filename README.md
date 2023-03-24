# RF_Search_Excel_Demo
Robot Framework Search demo Project.  Take text from the Excel sheet, search it on the website, get expected value from first section. If Search text in First section get the Price.

Python 3.11.2
pandas 1.5.3
selenium 4.8.2
robotframework 6.0.2
robotframework-seleniumlibrary 6.0.0

run command robot Testcases\Search\tc_search.robot


Test details.



1. go to www.sis.se
2. Click search bar.
3. Enter DATA: SS-EN ISO 9001 (Verify that quick search result "SS-EN ISO 9001:2015" Appears) (Assertion that)(From excel sheet)
4. Enter DATA: SS-EN ISO 9001:2015(From excel sheet)
5. Press enter
6. Confirm that first search result is SS-EN ISO 9001:2015 (Assertion)(From excel sheet)
7. Check that price is 1759 SEK (From excel sheet)



If any of the criterium is not meet the test shall shown as failed.
If all criteria are meet then the test shall be shown as passed.


