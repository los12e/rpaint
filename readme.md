1.	Design a process to automate interaction using image-based and OCR text recognition.

step1: use get ocr text activity.
step2: target the screen to browser screen with image.
step3: use tesseract ocr activity inside the get ocr text.
step4: click on get oct text properties in output section-text field create varable called image.
step5: use log message activity in that give message as image.ToString and log level to info.
step6: use write text file activity and select use local file and select file and in text give image.

2.design a process to send automated emails with attachments using uipath
Aim: Perform email automaton.
Email Automation!
 open ReadRangeWorkbook activity give the file address of excel shet(where to and form email address given)

 Now take "output data table as text" activity and give dt then take message box activity give dt

  now give "For EachRow in DataTable" and take item name as currentROw as the variable

  now in body take "getRowItem" activity and give there column to name and set value as the name

  Then take "Assign"activity and give another output variable "emailbody" and ser value to "hi".

  Choose "SendEmail" activity and asve as draft to False and give to email and run all of the cells.
