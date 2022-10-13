<h1> - ADDING INLINE POLICY(Creating a read only permission)</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Inline policies are policies that you create and manage and embed directly into a single user, group, or role.

Sometimes you want to creating users to launch EC2 instances.. for an Auditor for example
So the user would be able to do a cloud assesment then you have to To create  a read-only file whereby they can only see and cannot make changes
IAM 
In this lab I	Used IAM inline policy to create the an Auditor for my Company




<h2>Environments Used </h2>

- <b>AWS CONSOLE </b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch AWS CONSOLE AND LOG IN: <br/>
<img src="https://i.imgur.com/j9g8KMv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
On AWS console home navigate to AWS IAM:  <br/>
<img src="https://i.imgur.com/eDT2vgd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
On IAM dashboard click on user: <br/>
<img src="https://i.imgur.com/f5Xmssl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click on 'Add Users :  <br/>
<img src="https://i.imgur.com/fJXaETa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set User details by inputing the username, access type and custom password for first log in,  click on 'Next: Permissions :  <br/>
<img src="https://i.imgur.com/SOK9xAJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Permissions can be set either by adding the user to an existing group or by clicking on attach existing policies directly, Beacuse my focus is on inline policies I will not make any changes here, Go ahead and click on "Next:Tags" :  <br/>
<img src="https://i.imgur.com/EPKlSFq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 Add Tags for proper description, Optional in my case i didnt add tags then click on 'Next:Review" <br/>
<img src="https://i.imgur.com/tNUveZI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Review all you have inputed AWS will alert you that you the user has no permissions.
Don't worry about that click on "Create user"  <br/>
<img src="https://i.imgur.com/GV4tbIm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 User successfuly created!. Ensure to click on "Download .csv" to get the direct link for log in for the user or  better still send as E-mail directly to the Employee then click on "Close"  <br/>
<img src="https://i.imgur.com/qLNN0Ot.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 Select the ExternalAuditor you just created by double clicking on it <br/>
<img src="https://i.imgur.com/pm3Hp2P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 
 Inline policies are policies that you create and manage and embed directly into a single user, group, or role, So click on add inline polcy <br/>
<img src="https://i.imgur.com/BR8UvQ4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 I decided to use JSON CODE so I Clicked on JSON <br/>
<img src="https://i.imgur.com/HHDJlDR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 Go to Identity and access management Documentation and search for a polciy that allows read-only access to the IAM CONSOLE and copy the JSON code and go back to your console <br/>
<img src="https://i.imgur.com/lIoFowa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 
 Wipe the existing code and past the new code i got from IAM Documentation
Then I Clicked on "Review Policy" <br/>
<img src="https://i.imgur.com/Q2cmqL6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 Input a name for your new polciy and click on "Create Policy" <br/>
<img src="https://i.imgur.com/Vtd7LII.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 Inline Policy successfully created! <br/>
<img src="https://i.imgur.com/PgZuI0F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
