# OpenClassrooms  

Ce dépôt contient une mini-application pour le P3 du parcours **Grande École du Numérique**.

Entrevoisins  
![15543713165688_icon-above-font copie](https://user-images.githubusercontent.com/60298344/74930597-4c874500-53de-11ea-957b-a1ee759e9130.png)

Project 3 Openclassroom

Project Title
Step 1 : functionality development as following on the picture

Step 2 : Make 4 tests of Instrumented  Tests

Step 3 : Make local Unit Test for each function

Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
You need Android Studio, about version built see on section "Built With" on Readme file below

## On Manifest xml :
<uses-permission android:name="android.permission.INTERNET" />

## About dependencies :
    implementation fileTree(dir: 'libs', include: ['*.jar'])
    implementation 'com.android.support:appcompat-v7:28.0.0'
    implementation 'com.android.support:design:28.0.0'
    implementation 'com.android.support.constraint:constraint-layout:1.1.3'
    implementation 'com.android.support:support-v4:28.0.0'
    implementation 'com.android.support:recyclerview-v7:28.0.0'
    implementation 'com.jakewharton:butterknife:9.0.0'
    annotationProcessor 'com.jakewharton:butterknife-compiler:9.0.0'
    implementation 'com.github.bumptech.glide:glide:4.9.0'
    annotationProcessor 'com.github.bumptech.glide:compiler:4.9.0'
    // EVENT BUS
    implementation 'org.greenrobot:eventbus:3.1.1'
    // UNIT TEST
    testImplementation 'junit:junit:4.12'
    testImplementation 'org.hamcrest:java-hamcrest:2.0.0.0'
    // INSTRUMENTATION TEST
    androidTestImplementation 'com.android.support.test:rules:1.0.2'
    androidTestImplementation 'com.android.support.test:runner:1.0.2'
    androidTestImplementation 'com.android.support.test.espresso:espresso-core:3.0.2'
    androidTestImplementation 'com.android.support.test.espresso:espresso-contrib:3.0.2'


## Installing:

You had to use Android Studio to run this application. Because there are not the Apk installation  

Copy this link: https://github.com/laminemessaci/Projet_N-_3_Entrevoisin   

![image_2](https://user-images.githubusercontent.com/60298344/74931105-43e33e80-53df-11ea-88e5-5ea2c14d75bc.png)


Open Android Studio file -> new --> Project from Version Control(Git) Paste the link you had copy on the appear windows, on first line test if it is ok (click on test button at right to ensure that is successful) you only have to do next button on each windows, and at the end done to have it   

![image2](https://user-images.githubusercontent.com/60298344/74930954-eea72d00-53de-11ea-929e-4f58b28aa4f6.png)  

![image_4](https://user-images.githubusercontent.com/60298344/74931243-7d1bae80-53df-11ea-803e-f23a6b768b67.png)



After, make sure you are on "app", choose your AVD manager device or choose your external device link with your computer and click on "Run".   

![image_5](https://user-images.githubusercontent.com/60298344/74931336-ae947a00-53df-11ea-95c1-addbf2e58a2b.png)  

On the application, you can see the different persons names on neighbours page, you can scroll it. when you click on one of this item, a new windows will open, you have more informations about him or her, and you will choose if you want to have this neighbour name on your favorite, you had to just click on the star below the image of the person, the star pass to yellow color. After that, when you ar going to favorite page, you can see that you have you neighbour that you had choose. On each page, if you want to delete the neighbours or the favorite, you had to click on the delete button at the end of each item you want   
Running the tests      
Have a look on folder for Html test result: Entrevoisins\TestResult-NeighbourServiceTest,TestResult-NeighboursListTest contains the Test Results on Html Version    
About the note on pdf file name "note de cadrage.pdf" : "Développez une nouvelle fonctionnalité pour l’application Entrevoisins Note de cadrage.pdf"          
- Phase 1 : Functionality Development as the picture
                        Have a look on : 
                                        ___DetaiFragmentl.java__ , with the layout : __fragment_detail.xml__
                        
 - Phase 2 : Make 4 tests of Instrumented Tests
                        Have a look on : 
                                       - Package com.openclassrooms.entrevoisins(androidTest), and on folder _neighbour_list :                                                         __NeighbourListTest.java__
                                           
                                          
                        
- Phase 3 : Make 4 local Unit Test for each function
                      Have a look on : 
                                       - Package com.openclassrooms.entrevoisins.service(test) : ___NeighbourServiceTest.java__

                                         
## For Android Test :

For the file ___NeighboursListTest.java__ :

go to folder : Java/com/openclassrooms/entrevoisins/neighbours_list and open ___NeighboursListTest.java__, on the left side of "public class __NeighboursListTest()__ click on the both green button to run all the tests.


## For Local Unit Test :

For the file NeighboursServiceTest.java :

go to folder : Java/com/openclassrooms/entrevoisins/service and open __NeighboursServiceTest__, on the left side of "public class __NeighbourServiceTest__ click on the both green button to run all the tests.


## Deployment:

Run on Microsoft Windows, it will be done on other system too.

## Built With
Android Studio Version: 3.5.3 - To download the software --> https://developer.android.com/studio


## Versioning
I only use Github, git.
Openclassroom - Project 3 base of project download - Openclassroom

## Authors

* **laminemessaci** - *Training work* - [laminemessaci](https://github.com/laminemessaci/Projet_N-_3_Entrevoisin)

* **Openclassroom** - *Project 3 base of project download* - [Openclassroom](https://github.com/Deyine/OpenClassroom/tree/master/Android/Entrevoisins)


## Acknowledgments
Inspiration : https://www.youtube.com Tutorial, https://stackoverflow.com Forum, https://antonioleiva.com/collapsing-toolbar-layout/,
the mentors on openClassroom.
