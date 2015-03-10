##Second Sample Appcelerator Alloy Mobile Project for Howard U SCS Cross-Platform Mobile App Dev Class

* Project is based off of the default 2 Tab template available in Titanium Studio.
* Project is a sample demonstrating the use of Titatium ListView, Appcelerator Cloud Service `ti.cloud` module `moment.js` and `q` for promises
* This code should run successfully on IOS and Android using the Appcelerator 3.5.0 SDK
* Concepts here are meant to be a introductory guide to concepts covered in my book on Appcelerator Alloy and Appcelerator Cloud Services

![text](screens/small_book_cover.png)

____
###Getting Started
Please setup your constants by modifying the file [`tiapp.xml`](tiapp.xml) in the `root` directory of your project

Modify the code below to use your values from the Appcelerator Cloud Services console. The information can be found at http://my.appcelerator.com. If you are starting with a new project you created in Appcelerator Studio, you can cloud enable the application at creation and skip this step

````Javascript
<property name="acs-api-key-development" type="string">YOR VALUE HERE</property>
````
----------------------------------
Stuff our legal folk make us say:

Appcelerator, Appcelerator Titanium and associated marks and logos are 
trademarks of Appcelerator, Inc. 

Titanium is Copyright (c) 2008-2013 by Appcelerator, Inc. All Rights Reserved.

Titanium is licensed under the Apache Public License (Version 2). Please
see the LICENSE file for the full license.
