# selenium-test
This is a rudiment test script for Lynn to complete montonous and repetitive work(add role to amounts of employee)

Only works for selenium IDE
and THE ORDER OF RUNING SCRIPTS IS A-C-B

Since IDE cannot locate element in a opening new website, so the test case must be executed one by one.


1.firefox version54 can work for selenium IDE
55 no longer support

must degrade firefox
https://support.mozilla.org/en-US/kb/install-older-version-of-firefox#w_downgrade-alternatives

get previous version on
https://ftp.mozilla.org/pub/firefox/releases/54.0/win64/zh-CN/

2.download selenium: 
http://www.seleniumhq.org/download/

documents for selenium: 
http://www.seleniumhq.org/docs/02_selenium_ide.jsp#chapter02-ref

3.In Selenium IDE
文件-open demo_a, demo_c, demo_b
actions-play current testcase 先执行demo_a
actions-play current testcase 执行完demo_a后执行demo_c 再d
