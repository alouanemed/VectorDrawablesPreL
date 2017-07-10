# VectorDrawablesPreL
A set of custom views to support using vector drawables for pre-L devices

When working with vector drawables everything works fine in > L devices.But when you try Pre-L devices (kitkat..) it gives you  more or less of these errors : 

#Caused by: android.content.res.Resources$NotFoundException: File res/drawable/abc_vector.xml from drawable resource ID ####

Check list : 
- You have vector support enabled in your gradle
// Gradle Plugin 2.0+  
` android {  
   defaultConfig {  
     vectorDrawables.useSupportLibrary = true  
    }  
 }  `
 
 - You have the latest appcompat and design dependencies in your gradle
 
 ...
 

Custom views : 

- TextView



