<%* numRows = await tp.system.prompt("Enter the number of rows for the table:");
console.log(numRows)
parsednumrows =parseInt(numRows)
console.log(parsednumrows)
title = tp.file.title
titleWithDashes = title.split(' ').join('-')
let table = `| 1d${parsednumrows}  | Effect |
| -------- | -------- |`;

  

for (let i = 0; i < parseInt(numRows); i++) {

    table += `\n|  ${i + 1} | |`;
}
console.log(table);
-%>

<% table  %>
<% `^${titleWithDashes}-table\n` %>
Hit the dice icon below to roll on the table 
`<% `dice:[[${title}#^${titleWithDashes}-table]]`%>`