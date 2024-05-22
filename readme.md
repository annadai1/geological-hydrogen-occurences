## Varea Energy Hydrogen Map Squarespace SOP

squarespace.html file contains code ready for embedding into Squarespace page. Note that this is not valid stand-alone HTML

### 1 Check configuration

Configuration parameters used for integrations with other services:

Mapbox API key:

`pk.eyJ1IjoiYW5uYWRhaTEiLCJhIjoiY2x3Y2VraXM3MHkzbTJxbXlxOHRmY3VzeCJ9.tu-4Msj5BYX0vHjh6P95oQ`

Google Sheet API endpoint for .CSV data:

`https://docs.google.com/spreadsheets/d/e/2PACX-1vRpDCyLzqH4c3x98GsYq8ydxE78aPhmUEffxbkpyXvVWa7k6sBEyX8q98oxFrKxFRzXigv3ULP7UWXS/pub?gid=943834720&single=true&output=csv`

In a case it will be required to replace one of them - find it in the squarespace.html and replace it. Since this code is for direct embedding in Squarespace it's no way to move them in some kind of config or environment

### 2 Embed code into Squrespace website

- Open page where you intend to place map for editing

- Add block of type `CODE` on a page

- Copy & Paste contents of squarespace.html into this CODE block

- Save block

If necessary it's possible add other blocks below and above of map block
