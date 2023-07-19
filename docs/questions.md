# Questions

###❓<font color="#dd0000">About adjusting the curvature of the book spine？</font><br />
Problem description: the cover spine and pages will interlaing when you increase the spine offset
![](image/coverspineinter.gif "")
Find a null object in the middle of the spine cover ,it  is used to control the deep offset of bind and pages,it can be moved left and right ,then you will solve the prolem
![](image/coverspineintersolveA.png"")
![](image/coverspineintersolveB.png"")

###❓<font color="#dd0000">How to transform the book？</font><br />
**[Transform](transform.md)**

###❓<font color="#dd0000">How to reduce the number of pages？</font><br />
Video tut:[https://youtu.be/VriFDudqick](https://youtu.be/VriFDudqick)

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

###❓<font color="#dd0000">Blender crashed when playing open animation？</font><br />
In my tests so far, I only found that blender crashes when the wiggle bone addon is turned on at the same time.
So,if Blender crashed when playing open animation ,be sure to check if the wiggle bone addon is turned on.

###❓<font color="#dd0000">"Replace textures" not work？</font><br />
1. check the texture's format: jpg
2. check the textures' name: PageTex001.jpg，   PageTex002.jpg，  ...... PageTex199.jpg， Cover_Front_Tex，Cover_Spine_Tex,Cover_Back_tex
3. Check that the controller is selected before executing the command
4. still not work,click the reset button ,and try it again
5. still not work,contact me (547198894@qq.com):send some screenshots of your blender file and rename folder to me .

###❓<font color="#dd0000">How to export Book animation to other 3d softwares？(unity,c4d,max,maya,......)</font><br />
Video Tut：[https://youtu.be/Q0eA1I7yfqg](https://youtu.be/Q0eA1I7yfqg)
















