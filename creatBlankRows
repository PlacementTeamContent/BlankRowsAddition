function createFiveBlankRows() {
  const sheet = SpreadsheetApp.getActiveSpreadsheet().getActiveSheet();
  var question_content_column = sheet.getRange("A:A"); // Column A
  let i = 2;
  while (i<question_content_column.getNumRows()) {
      console.log("i",i);
      let startRow = i; // Specify the row after which you want to insert the blank rows
      let numRows = 24; // Number of blank rows to insert
      sheet.insertRowsAfter(startRow, numRows);
    i += 25;
  }
}
