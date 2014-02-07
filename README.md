j-sdView-pgb-helloworld
=======================

An Attempt to show 3D mesh images using Phonegap Build




Feb 07, 2014

IT WORKS!

SEE THE FILE

myGoo3d.html     

Shows how to load a webpage with an object 3D mesh exported from Blender as a wavefront .obj file that also saves a .mtl file. Look great. Can use some basic touch commands to view it in 3D.





Just tested that you can load 2 3D frames in one App page. Looks good, amazing how fast it is. the touch comands are a bit sensitive. Also my Blender Camera is zoomed out too far, but that is a minor error.






Below here are my notes while I was working on it.


Sorry. Presently the Github code works, the problem is that the Webkit used by Phonegap does not refresh the page and you get a double 3D image as soon as you try to move it. 

Another issue is that you get the entire github page, which is less than ideal. I am sure things will change in the near future. I am going to try the same code with CCA (Chrome-cordova-app) to see if it works better. Just search github for cca-helloworld



Note: Do not use the suggested script from github but instead use something like this javascript command


<script>
  this.location = 'https://github.com/hpssjellis/j-sdView-pgb-helloworld/blob/master/RugbyLineoutMaulYellow05.stl?overridemobile=true';
</script>


Google 3D version is at
https://code.google.com/p/jsc3d/


Of course this works perfectly. On window, touch commands work, sort of slow but successful. The only problem is that I do not know how to load my own .stl mesh objects onto the google site. will look into this more


















************************************************************************************************************

###Disclaimer: I spend my time getting complex things working in simple ways. I have no idea if I am doing anything correctly so please beware if you use my work. If you like this App and can hum, play or sing please help the musically illiterate, use a flash capable computer to add your favorite song at http://www.rocksetta.com 
