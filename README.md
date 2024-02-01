# UE4-Mobile-Skin-Shading(YOU MUST SWITCH TO OPENGLES RENDERING MODE IN UE)

Different method for Mobile Skin Shading with support on Opengl es 3.1
![image](https://github.com/tigershan1130/UE4-Mobile-Skin-Shading/assets/39791762/c3c75744-e823-4c07-b305-8723033683e9)

![image](https://github.com/tigershan1130/UE4-Mobile-Skin-Shading/assets/39791762/a7be1ece-6b59-4b61-b4e7-3dac2eab954b)

left most uses LUT lookup for shading

middle uses Gauss Spherical Approximation

Right is the good old diffuse shading.


This project need to enable mobile support for Opengl ES3.1 and uses custom modification on UE4 4.26.2, which you can find here:
https://github.com/tigershan1130/UnrealEngine-1/commit/11cdd35a9c3d73900d3ea71f018175a0e223e2dd
