# Personal-portfolio

The HTML code creates a simple portfolio page with a table layout. The table is centered and contains information about a person named Shammi Akter, including her ID, section, batch, skills, and hobbies, along with a profile image.

1. Document Structure:

<!DOCTYPE html>: Declares the document type and version of HTML (HTML5 in this case).
<html>: Root element that contains all other elements on the page.
<head>: Contains meta-information about the document, such as the title.
<title>: Sets the title of the web page (displayed in the browser tab).
2. Body Content
<body>: Contains the visible content of the web page.
<h1><center>Assignment on portfolio</center></h1>: Displays a main heading, centered. Note that <center> is deprecated; modern practice uses CSS for centering.
  
3. Table Layout:
  
<table border="2" width="50%" height="600px" align="center" bgcolor="2a2c2b">: Creates a table with:
border="2": A border width of 2 pixels.
width="50%": Table width is 50% of the page width.
height="600px": Table height is 600 pixels.
align="center": Centers the table horizontally.
bgcolor="2a2c2b": Background color. Note that bgcolor is outdated; use CSS for styling.
  
4. Table Rows and Cells:
  
<tr>: Defines a table row.

<td colspan="2">: A cell that spans two columns.
<font size="6" face="Helvetica" color="white">: Sets the font size, family, and color. The <font> tag is deprecated; use CSS for styling.
<center>MY PORTFOLIO</center>: Displays the text "MY PORTFOLIO" centered. As with the <center> tag, use CSS for centering text.
<tr></tr>: An empty row. This appears to be a mistake and should be removed as it doesn’t contribute to the layout.

<td>: Defines a table cell.

Contains:
<font size="5" color="white">: Displays text in a specified font size and color.
Details about the person, such as name, ID, section, and batch.
<p>: Paragraph tags used to separate content.
<b><u>Skills:</u></b>: Bold and underlined text indicating the "Skills" section.
<ul> and <li>: Used to list skills and hobbies.
<td>: Another table cell.

<img src="Shammi.jpeg" height="300px">: Displays an image with a height of 300 pixels. The src attribute points to the image file "Shammi.jpeg".
