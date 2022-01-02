# Final Project: Volume Rendering (VTK)
###### simple volume rendring website with Node.js and React
   
   
Name | Sec | BN |   
--- | --- | --- | 
salma Hussien  | 1 | 38
Sandra essa | 1 | 35 
Habiba mohamed | 1 | 25


# Main Idea 
we display CT for Chest and Head applying widget on both of them but ray casting only on Chest and Marching cubes on Head.

# Implmentation Details
 ## Table of contents
* [rendring window setup ](#rendring window setup)
* [Switching between head and chest](#Switching between head and chest)
* [marching cubes on head ](#marching cubes iin head )
* [ray casting on chest  ](#ray casting on chest  )
* [ray casting on chest  ](#widget on Head and Chest)

## rendring window setup 
first we creat instance of vtkFullScreenRenderWindow class setting background to whatever color you want 

```

    const fullScreenRenderer = vtkFullScreenRenderWindow.newInstance({
        background: [0, 0, 0],
    });
```









