# Simple OPENGL example
In this example there are some lifeless objects like chairs, tables, plates, cabinets

# Running instruction

BUILD:
```
cd src
cc -framework GLUT -framework OpenGL -framework Cocoa offline.cpp  -o glutapp
```

RUN:
```
./glutapp
```

mouse click will change the rotation of the camera  
the curtain will open or close if you press key 'z'  

# Test Environemnt:

Tested in OS X El Capitan (10.11.6)
