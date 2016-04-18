#gradStop.js

####JavaScript micro library to generate gradient color stops


###Usage:

    var gradient1 = gradStop({
       stops: 5,
       inputFormat: 'hex',
       colorArray: ['#343838', '#00DFFC']
    });
    
    console.log(gradient1);
    // rgb(52,56,56), rgb(39,97,105), rgb(26,139,154), rgb(13,181,203), rgb(0,223,252)


![alt text][1]


  [1]: https://cdn.rawgit.com/Siddharth11/gradStop.js/master/gradient%20strip.png



####Default Parameters:
 * inputFormat: 'hex' *`supports hex, rgb and hsl`*
 * stops: 5
 * colorArray: ['#fff', '#000'] *`supports upto 4 values`*

Both shorthand(#fff) and standard(#ffffff) format hex values are supported.

###[Demo](http://codepen.io/Siddharth11/full/RPvJmO)
