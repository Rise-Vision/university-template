# Univeristy Template

## Introduction

The University Template was created to cycle through 3 photos of students, inspirational quotes, and some information about the students. A preview of the template can be seen here: http://rise-vision.github.io/university-template/src/index.html

##Steps to run the university template:##

1. Fork or download the entire university-template repository.
![alt tag](images/readmestep1.jpg)

3. Host the entire “university-template” folder directory in rise vision storage or your web hosting service.
![alt tag](images/readmestep3.jpg)

4. Copy the link to the university-template.html file where you have it hosted and insert the url into a schedule. (you can also add this link to the url gadget within a presentation)
![alt tag](images/readme-step4.jpg)


##Directions to modify the university template:##

####Changing the names and degrees of the students
The names, and degrees of the students can be adjusted in the index.html file, by editing the ```<p>`` tags within the div containing the class block 2. 

```	<div class="block block2"> <div class="nameSlider"> <p>John Smith<br> <span>Bachelor of Science</span> </p> <p>Jessica Clark<br> <span>Bachelor of Arts</span> </p> <p>Carry West<br> <span>Bachelor of Education</span></p> </div> </div>``

####Changing the quote text
The quotes can be adjusted in the index.html file, by editing the ```<p>`` tags within the div containing the class block 3. 

```	<div class="block block3"><div class="quoteSlider"><p>“Going that extra mile in the job I love is importantto me. I’m not inspired by just meeting the minimum obligations”</p><p>“When one door closes, another opens; but we often look so long and so regretfully upon the closed door that we do not see the one which has opened for us.”</p><p>“Believe in yourself and all that you are. Know that there is something inside you that is greater than any obstacle.”</p></div></div>```

####Removing or adding student images
The university template cycles through 3 images, quotes, and names. 

To add or remove one of the images open the index.html and locate the div at the bottom of the file that contains them. Change the image file paths to your new file paths.

```	<div class="block block1"><ul class="imgSlider"><li><img src="../images/student2_NoBG.png"></li><li><img src="../images/student3_NoBG.png"></li><li><img src="../images/student4_NoBG.png"></li></ul></div>```

To change the duration of each slide locate the following code in the main.js file and modify the numbers "400" and "9000" to reflect the time you would like them to play in millaseconds:

```	$('.imgSlider, .quoteSlider, .nameSlider').rotaterator({fadeSpeed:400, pauseSpeed: 9000});```



####Changing the background image
Open style.css, locate the following code and modify the src url of the img tag to the path of your new background:

```  background-image: url("http://www.centerforstudyabroad.com/wp-content/uploads/2011/01/Galway1-university.jpg");```


## Built With
actual tools used
- HTML
- CSS
- Java Script
- jQuery
- Gulp

The University Template works in conjunction with [Rise Vision](http://www.risevision.com), the [digital signage management application](http://rva.risevision.com/) that runs on [Google Cloud](https://cloud.google.com).

At this time Chrome is the only browser that this project and Rise Vision supports.

## Submitting Issues
If you encounter problems or find defects we really want to hear about them. If you could take the time to add them as issues to this Repository it would be most appreciated. Please Identify the specific template that has the issue and follow the following format where applicable:

**Reproduction Steps**

1. did this
2. then that
3. followed by this (screenshots / video captures always help)

**Expected Results**

What you expected to happen.

**Actual Results**

What actually happened. (screenshots / video captures always help)

## Contributing
All contributions are greatly appreciated and welcome! If you would first like to sound out your contribution ideas please post your thoughts to our [community](http://community.risevision.com), otherwise submit a pull request and we will do our best to incorporate it.


## Resources
If you have any questions or problems please don't hesitate to join our lively and responsive community at http://community.risevision.com.

If you are looking for user documentation on Rise Vision please see http://www.risevision.com/help/users/

If you would like more information on developing applications for Rise Vision please visit http://www.risevision.com/help/developers/.

 If you have any questions or problems please don't hesitate to join our lively and responsive community at http://community.risevision.com.
 
**Additional Content Templates can be found here: https://github.com/Rise-Vision/content-templates**

