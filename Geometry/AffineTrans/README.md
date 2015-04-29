# Testing for this module just support gray-scale images !  

# Using these to do functional simulation:  

At first, changing your work path:  
    
    set proj_path your-project-path  

etc.  
    
    set proj_path B:/Complex_Mind/FPGA-Imaging-Library/Geometry/AffineTrans  

Run this commond at first time:

    vlib work  

Then, compile all your source file:  

    modelsim gui -> Compile -> Compile all  

Then, run this:

    do $proj_path/FunSimForHDL/Run.do