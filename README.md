# UE4-Mobile-Skin-Shading
Different method for Mobile Skin Shading with support on Opengl es 3.1
![alt text](https://github.com/tigershan1130/UE4-Mobile-Skin-Shading/blob/main/HighresScreenshot00000.png)
![alt text](https://github.com/tigershan1130/UE4-Mobile-Skin-Shading/blob/main/HighresScreenshot00001.png)
left most uses LUT lookup for shading

middle uses Gauss Spherical Approximation

Right is the good old diffuse shading.


This project need to enable mobile support for Opengl ES3.1 and uses custom modification on UE4 4.26.2, which you can find here:
https://github.com/tigershan1130/UnrealEngine-1/commit/11cdd35a9c3d73900d3ea71f018175a0e223e2dd
