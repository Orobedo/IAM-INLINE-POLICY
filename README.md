<h1> - INLINE POLICY(Creating a read only permission)</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
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
Review all that you've inputed and click on "Create User" if satisfied  <br/>
<img src="https://i.imgur.com/fRr9JHJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 User successfuly created and Permission granted!. Ensure to click on "Download .csv" to get the direct link for log in for the user or  better still send as E-mail directly to the Employee  <br/>
<img src="https://i.imgur.com/vr61DfO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
