# FoldandCurl
An Adobe After Effect script to make curling and folding.  
轻松制作卷曲、折叠效果.[`观看演示`](http://www.bilibili.com/video/av8042868/index_2.html)
</br>
## Demo:
![](https://github.com/bigxixi/ReadMe-Resources/blob/master/FoldandCurl/fold_demo.gif)
![](https://github.com/bigxixi/ReadMe-Resources/blob/master/FoldandCurl/curl_demo.gif)  

# How to Use
Download the [`ZIP file`](https://github.com/bigxixi/FoldandCurl/archive/master.zip) and unzip.</br>
Run AE, click `File`->`Script`->`Run Script File...` and choose the `SaveFrameAsPNG-Plus.jsx` file.  
</br>
Or you can copy the `SaveFrameAsPNG-Plus.jsx` to your AE script folder:
>**Windows:**  
>`C:\Program Files\Adobe\Adobe After Effects <version>\Support Files\Script\`  
>**Mac:**  
>`/Applications/Adobe After Effects <version>/Scripts/`

</br>
### Then:  
1. Select layer(s) as an element to fold or curl.  
The script generates the curl chain by a layer's width or height, which means layers like textlayer or shapelayer should be pre-composed and set the width and height to work properly.  
2. Take a direction.  
3. Input the count of elements to be generated.  
4. Select the behavior, fold or curl.    
5. If you want to generate a sub chain of a preview one, check the "Link to Preview".   

**note:**  
 1. Add ONLY ONE direction to the ROOT element.  
 2. Don't generate more then once in one direction.  

**How to control:**  
 1. Select the root element - effect - angle control to control the fold or curl progress.  
 2. You can toggle the orientation of each "sub chain" by just selecting them.  

