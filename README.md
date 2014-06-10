This is a project that demonstrates the usage of WebGL to display proteins in the broswer. This project focuses on OpenCTM using the three.js library to display OpenCTM in the web browser. There are some example proteins provided converted into the various formats. In this directory you will also find 2 html/javascript files dedicated to showing a proof of concept of how to display OpenCTM in the browser. The steps below show how to actually run those files in the browser. These files are written in three.js so they can easily be converted to use a different format (such as maybe GLTF). The advantages of using OpenCTM vs just displaying WebGL in the raw is it is far more efficient and portable. Check out my presentation on the topic titled OpenCTM_Presentation.pdf .

Project Contents
Example Files: Different sized proteins converted from Chimera into OBJ, Collada, OpenCTM, and raw WebGL
Models: Example CTM files for the html/javascript to draw from. The code is commented with purpose that the code can be adapted.

Steps to getting Started

1. Create a webserver [on the mac you can run this command in terminal ( sudo apachectl start  ) your webserver directory is /Library/WebServer/Documents]
2. Install OpenCTM http://openctm.sourceforge.net/?page=download
3. Download three.js http://github.com/mrdoob/three.js/zipball/master
4. Drop the three.js folder into your webserver folder
5. Drop the example files into the three.js /examples/ directory
6. Drop the model files provided into /examples/models/ctm
7. navagate your url to http://localhost/mrdoob-three.js-d3cb4e7/examples/ctm_javascript_example
8. or http://localhost/mrdoob-three.js-d3cb4e7/examples/ctm_javascript_example2
