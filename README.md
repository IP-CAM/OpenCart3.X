Green World Technology OpenCart Module

Last Release

When providing cooperative special stores and individual members using the open source code store system, there is no need to deal with complicated checks on their own. By installing and setting plug-in packages, they can interface with the Green World system in a faster way.
table of Contents

    [Supported Version](#Supported Version)
    Install
    Settings

    金流
    [Electronic Invoice](#Electronic invoice)
    物流

    [Technical Support](#Technical Support)

Supported version
OpenCart 	Modules
3.0.2.0 	3.0.190823
installation

####Environmental requirements Please make sure the PHP curl module is installed. Installation and configuration: https://www.php.net/manual/en/curl.installation.php

####Upload modules Shopping cart background -> Extensions -> Extended installation, upload ecpaypayment.ocmod.zip.
Update OCMOD

Shopping cart background -> Extensions -> Modify settings -> Click the update button in the upper right corner.
set up
Golden Stream

Enable -Shopping cart backend -> Extensions -> Payment module -> Green world integrated cash flow, click the Add button on the right. -Shopping cart backend -> Extensions -> Payment Module -> Green World Integrated Cash Flow, click the Edit button on the right. -Go to Green World Management Backstage, query the following information and fill in it.
Shopping cart background field name 	Green world management background field name
Store Code 	Store Code
Key 	Interface to HashKey
Vector 	Interface HashIV

Precautions -Please note that the contents of Hash Key and Hash IV cannot contain blanks. -The store code 2000132 is a test code, please do not use it in a formal operating environment. -It is recommended to use copy + paste backfill information -Set the status to Enable, set other options according to your needs* (Credit card installment function is only available for special stores)*, press Save to complete the setting.
Electronic invoice

Enable -Shopping cart background -> Extensions -> Payment Module -> Green World Electronic Invoice, click the Add button on the right. -Shopping cart backend -> Extensions -> Payment Module -> Green World Integrated Cash Flow, click the Edit button on the right. -Go to Green World Management Backstage, query the following information and fill in it.
