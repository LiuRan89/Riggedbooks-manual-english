# Questions

###❓<font color="#dd0000">Why the most number is 100？</font><br />
I can do more, but I don't think it is necessary, because most of the time artists only care about the thickness of the book.

###❓<font color="#dd0000">Compatible with Eevee and Cycle？</font><br />
Yes。
	
###❓<font color="#dd0000">Is it used the geometry node？</font><br />
no，It's all basic constraints and code.
	
###❓<font color="#dd0000">Can I use other render engines？</font><br />
yes，but you should change materials yourself，but in other render engines,the parameters about roughness will not work.
	
###❓<font color="#dd0000">Will there be more updates？</font><br />
I still have some ideas, but they're difficult to implement, and I'd be happy to update them once the problem is resolved. 
Of course, if there are bugs in the current version, I will try my best to fix them.
	
###❓<font color="#dd0000">How to convert it to a static model？</font><br />
Select the controller，then press the convert to mesh button。

###❓<font color="#dd0000">Why the name of the 100p's control is 99p(100)？</font><br />
Because 100P will upset the order。

###❓<font color="#dd0000">How to add 3D texts to the cover？</font><br />
When the book is closed, find the null object named Cover_Rot_ConD,under it there is a Cover_Up_Null object,you can select the text object,then press shift and drag it to the Cover_up_Null object make the text a children of the Cover_Up_Null object.

###❓<font color="#dd0000">How to get it back when you accidentally delete a keyframe?</font><br />
Select the controller, in the controller's custom properties, there are all parameters, find the required parameter to key frame。
![](image/custompanel.png "")


###❓<font color="#dd0000">How to make a cover flip back animation?</font><br />
Delete the keyframes in the end. Mirror the front keyframes.
![](image/close.png "")




















