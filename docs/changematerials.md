# Manual replace textures

**Change the cover tex：You need to prepare three JPG images **：  
Similar to the following, respectively corresponding to the book cover front, back and side：

![](image/threeimage.png "")	

**Cover textures：**select cover model，it has five materials，control different parts of the cover.
![](image/selectcover.png "")	
![](image/matpanel.png "")

**Cover_Front_Mat：**cover front
![](image/Cover_Front_Mat.jpg "")

**Cover_Spine_Mat：**cover side  
![](image/Cover_Spine_Mat.jpg "")


 **Cover_Back_Mat：**cover back
![](image/Cover_Back_Mat.jpg "")


 **Cover_Inner_Mat：**cover inner
 ![](image/Cover_Inner_Mat.jpg "")

 **Cover_Rim_Mat：**cover  rim
 ![](image/Cover_Rim_Mat.jpg "")

**Page materials**：every page has a single texture，select the page，you can find the material in the material panel。

**Change Pages' bump map texture**：Every page's material has a bump node group linked to the bump channel.selet it ,press Tab key on the keyboard,enter the node group ,you will find a texture called tile_page in it ,replace it with your own paper texture.As the texture is in the node group ,so once you changed it in one node group,every page's bump node has been changed.And,in the bump node group,I have created some node links to shift the uv randomly,so once you changed the texture,every page's uv for bump texture will not be the same.
 ![](image/bumpnode.jpg "")
 
 ![](image/bumpnodegroup.jpg "")
 
!!! Note
	Because every paper has two sides,so each material has two textures, one for the front and one for the back of the page. Just change these maps with yours.
	 ![](image/shadernodes.jpg "")



