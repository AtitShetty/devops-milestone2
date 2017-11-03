## Static Analysis of Checkbox.io

Ankur Garg (agarg12)
<br /><br />


### Requirements
node pacakges required are mentioned in package.json

### Execution
Run `npm install` in this folder <br />
followed by `node main.js ./checkbox.io/server-side/site`

### Report:
Report is generated in xml format by the code.
For one specific run, report is provided in xml and txt format in this folder (analysis_report.xml  and analysis.txt)

### Files;
main.js - the main analysis script
checkbox.io/ - directory contains server side code of the checkbox.io


## Failing Cases:
\----------------Failing Cases---------------<br />
Function -  EscapeCode  in file -  ./checkbox.io/server-side/site/marqdown.js  - Message Chain Length =  8<br />
Function -  ProcessTokens  in file -  ./checkbox.io/server-side/site/marqdown.js  - Number of lines =  233<br />
Function -  ProcessTokens  in file -  ./checkbox.io/server-side/site/marqdown.js  - Message Chain Length =  4<br />
Function -  anon function @58  in file -  ./checkbox.io/server-side/site/routes/admin.js  - Message Chain Length =  4<br />
Function -  anon function @63  in file -  ./checkbox.io/server-side/site/routes/admin.js  - Message Chain Length =  4<br />
Function -  anon function @64  in file -  ./checkbox.io/server-side/site/routes/admin.js  - Message Chain Length =  4<br />
Function -  anon function @86  in file -  ./checkbox.io/server-side/site/routes/admin.js  - Message Chain Length =  4<br />
Function -  anon function @87  in file -  ./checkbox.io/server-side/site/routes/admin.js  - Message Chain Length =  4<br />
Function -  anon function @89  in file -  ./checkbox.io/server-side/site/routes/admin.js  - Message Chain Length =  4<br />
Function -  anon function @153  in file -  ./checkbox.io/server-side/site/routes/study.js  - Message Chain Length =  4<br />
\--------------------------------------------<br />
