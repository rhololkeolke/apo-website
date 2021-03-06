Service Events Functional Test
==============================

+---------------+----------------+---------------+
|ID             |Results         |Status         |
+---------------+----------------+---------------+
|7              |No link is      |PASS           |
|               |displayed for   |               |
|               |the create      |               |
|               |event and       |               |
|               |navigating to   |               |
|               |the create page |               |
|               |manually        |               |
|               |redirects the   |               |
|               |user to the     |               |
|               |login page      |               |
+---------------+----------------+---------------+
|8              |All the         |PASS           |
|               |information is  |               |
|               |accepted and    |               |
|               |the new event   |               |
|               |is displayed in |               |
|               |the list of     |               |
|               |service events  |               |
+---------------+----------------+---------------+
|9              |No edit link is |PASS           |
|               |displayed and   |               |
|               |manually        |               |
|               |navigating to   |               |
|               |an edit page    |               |
|               |address         |               |
|               |redirects the   |               |
|               |user to the     |               |
|               |login page      |               |
+---------------+----------------+---------------+
|10             |The edit link   |PASS           |
|               |is              |               |
|               |displayed. When |               |
|               |clicked the     |               |
|               |edit form       |               |
|               |appears. All    |               |
|               |changed         |               |
|               |information is  |               |
|               |updated         |               |
+---------------+----------------+---------------+
|11             |The user is     |PASS           |
|               |directed to the |               |
|               |login page with |               |
|               |a message       |               |
|               |saying they do  |               |
|               |not have        |               |
|               |permission to   |               |
|               |view the page   |               |
+---------------+----------------+---------------+
|12             |The user is     |PASS           |
|               |able to see a   |               |
|               |list of all     |               |
|               |existing        |               |
|               |service events  |               |
|               |grouped by      |               |
|               |future events   |               |
|               |and past events |               |
+---------------+----------------+---------------+
|13             |No field is     |FAIL           |
|               |displayed on a  |               |
|               |service events  |               |
|               |page            |               |
+---------------+----------------+---------------+
|14             |The user is     |PASS           |
|               |added to the    |               |
|               |list of users   |               |
|               |going.          |               |
+---------------+----------------+---------------+
|15             |Upon clicking   |PASS           |
|               |on the submit   |               |
|               |service report  |               |
|               |link forms for  |               |
|               |each signed up  |               |
|               |member are      |               |
|               |present. Upon   |               |
|               |filling out the |               |
|               |forms and       |               |
|               |saving them the |               |
|               |information     |               |
|               |becomes         |               |
|               |available for   |               |
|               |viewing along   |               |
|               |with a status.  |               |
|               |                |               |
|               |Note that the   |               |
|               |submit link     |               |
|               |only appears    |               |
|               |when the event  |               |
|               |past the start  |               |
|               |date-time       |               |
+---------------+----------------+---------------+
|16             |The status for  |PASS           |
|               |the submitted   |               |
|               |hours appears,  |               |
|               |but there is no |               |
|               |way to change   |               |
|               |the             |               |
|               |information.    |               |
+---------------+----------------+---------------+
|17             |The status for  |PASS           |
|               |the submitted   |               |
|               |hours appears   |               |
+---------------+----------------+---------------+
|18             |Each submitted  |PASS           |
|               |hour has an     |               |
|               |option to set   |               |
|               |the             |               |
|               |status. Clicking|               |
|               |the save button |               |
|               |updates the     |               |
|               |statuses so that|               |
|               |upon refreshing |               |
|               |the page        |               |
|               |everything is   |               |
|               |saved.          |               |
+---------------+----------------+---------------+
|19             |The service     |PASS           |
|               |event status is |               |
|               |updated upon    |               |
|               |saving and      |               |
|               |refreshing the  |               |
|               |page            |               |
+---------------+----------------+---------------+


