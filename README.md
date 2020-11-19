# Web-Server-Log-analysis-Big-data-
 Web server log analysis with Hadoop,Mapreduce,Pig & Sqoop

## The compressed file contains the client requests captured by a Web server looks like:
 21.125.155.111 - - [01/Jan/2012:12:07:48 +0530] "GET /digital-cameras/digital-camera/sony-qx-dsc-qx100-point-shoot-digital-camera-black.html HTTP/1.1" 200 1470    "Mozilla/5.0 (Windows; U; Windows NT 6.1; en-US; rv:1.9.2.17) Gecko/20110420 Firefox/3.6.17" "-"


 The Weblog file contains 1L of such lines.

 
### KPIs:
1. Parse logs and convert request string into structured format (/a/b/c/d  =>  a	b	c	d)
50.57.190.149	-	-	22/Apr/2012:07:12:41 +0530	GET /computers/laptops.html?brand=819 HTTP/1.0	computers	-	-	laptops.html	brand=819	200	12530	-	-

2. count of page views by individual user
3. How much time a user has spent on a perticular page (visit duration per user per page)

4. Top / Bottom 5 :  catagery-1/ catagery-2 / page / user-agent / referal / users / entry pages / exit pages / 
(Exclude status code other than 200, also exclude record related to css/js/image)

5. Total pageviews / Category wise pageviews / Unique pageviews

6. count of status code = 200 / 404 / 400 / 500






