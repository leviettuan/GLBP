Gradient Local Binary Pattern (GLBP)
=======

<!-- This doesn't show on GitHub...
<object width="512" height="512" type="application/x-shockwave-flash" data="http://content.screencast.com/users/mattdipasquale/folders/Jing/media/7d0d010f-f4fd-44b2-95fb-818a982c2c36/jingswfplayer.swf">
  <param name="movie" value="http://content.screencast.com/users/mattdipasquale/folders/Jing/media/7d0d010f-f4fd-44b2-95fb-818a982c2c36/jingswfplayer.swf" />
  <param name="quality" value="high" />
  <param name="bgcolor" value="#F8F8F8" />
  <param name="flashVars" value="containerwidth=512&containerheight=512&thumb=http://content.screencast.com/users/mattdipasquale/folders/Jing/media/7d0d010f-f4fd-44b2-95fb-818a982c2c36/FirstFrame.jpg&content=http://content.screencast.com/users/mattdipasquale/folders/Jing/media/7d0d010f-f4fd-44b2-95fb-818a982c2c36/00000002.swf&blurover=false" />
  <param name="allowFullScreen" value="true" />
  <param name="scale" value="showall" />
  <param name="allowScriptAccess" value="always" />
  <param name="base" value="http://content.screencast.com/users/mattdipasquale/folders/Jing/media/7d0d010f-f4fd-44b2-95fb-818a982c2c36/" />
</object> -->

We release two tools in this repository. The first tool "training.exe" is used to train your bark image dataset. The second is a testing tool that classifies a bark image based on a pre-trained model.

Firstly, you divide your dataset into two subsets. The traing set is used to train our model that uses Gradient Local Binary Pattern (GLBP) to encode the local texture of image. The images in the test set are not includes in training set.

Then, You can point the training dataset folder for the training tool, and run the testing tool to classify all the images in the test set.
For more information about these tools, see the below video.

Screenshot & Demo Video
-----------------------

To see a demo video, click the screenshot
<a style="float:right" href="https://youtu.be/3mRFK-IM6oU" target="_blank">
  <img alt="PicSciP Demo Video" src="https://github.com/leviettuan/GLBP/blob/master/Images/Video.png" width="100%" height="100%" />
</a>

Screenshot & Demo Video
-----------------------

<a href="http://data.vicos.si/datasets/TRUNK12/TRUNK12.zip">TRUNK12 dataset</a> (http://www.vicos.si/Downloads/TRUNK12)

Contact
-----------------------

For any other question, please contact Tuan Le-Viet at tuan.lv@ou.edu.vn or nguyenleviettuan@gmail.com
