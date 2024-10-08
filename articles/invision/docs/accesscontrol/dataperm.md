
# Data Permissions 

Access to resources, such as [Workbooks](../workbooks.md), Data, and APIs are granted to [Access Groups](accessgroups.md). You can grant that access by setting Data Permissions. 

**Note!**

Every time a new workbook is created the access need to be granted.
<br/>

##	Granting Data Permission

<br/>

**Example**

1.	Go to **“Data Permission”** tab,
2.	Highlight the selected Dimension, 
3.	Highlight the selected Hierarchy,
4.	Click on the **“Edit”** button on the right-hand side of Explicit Permission,
5.	Click the **“Add”** button in the Data Access Object Permissions pop-up, 
6.	Select **“Admin”** in the access group selector and click OK,  
7.	Make sure the **“Is Default Identity”** is checked.  

![Workbook Permissions](https://profitbasedocs.blob.core.windows.net/images/DataPerm1.png)  

<br/>

You can now test different identity accesses by moving your identity from Admin to Standard. 

**Note!**
>Remember to add your identity back in the Admin group before you close the designer. If you close the designer before you do this, you will not be able to get back in without deleting the entire identity access configuration I the database.

## View which users have access to a Workbook

You can now easily see which users have access to a Workbook through group membership, both from the Designer and Web client.

<br/>

![img](https://profitbasedocs.blob.core.windows.net/images/permview1.png)
<br/>

![img](https://profitbasedocs.blob.core.windows.net/images/permview2.png)
<br/>

## See Also 

* [Data Permissions Editor](../workbooks/components/accesscontrol/dataperm.md)

<br/>

## Videos

* [Access Control](../../videos/accesscontrol.md)