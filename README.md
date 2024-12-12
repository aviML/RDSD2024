# RDSD2024
our "Road damage dataset" contains 1700 images of Alligator and Map cracks, Longitudinal cracks, and potholes collected by a GoPro camera mounted on a vehicle's dashboard.
The dataset contains images of the above-mentioned damages with class labels, YOLOv8-style bounding box annotations, and severity labels( Large, medium, and Small). 
The dataset structure is as follows....
                                      RDSD024(Folder)/
                                                     RDSD2024(folder)/
                                                                      images(folder)/
                                                                                     ***image1_name***.jpg
                                                                                     ***image2_name***.jpg
                                                                                     ***image3_name***.jpg
                                                                                     .....................
                                                                                     .....................
                                                                      labels(folder)/
                                                                                     ***labelfile1_name***.txt
                                                                                     ***labelfile2_name***.txt
                                                                                     ***labelfile3_name***.txt
                                                                                     .........................
                                                                                     .........................
                                                                      severity(folder)/
                                                                                      Alligator(folder)/
                                                                                                        ***severitylabel1***.txt
                                                                                                        ***severitylabel2***.txt
                                                                                                        ........................                
                                                                                      Longitudinal crack(folder)/
                                                                                                        ***severitylabel1***.txt
                                                                                                        ***severitylabel2***.txt
                                                                                                        ........................ 
                                                                                                        
                                                                                      potholes(folder)/
                                                                                                        ***severitylabel1***.txt
                                                                                                        ***severitylabel2***.txt
                                                                                                        ........................ 
                                                                      
                                                                                     
                                                              
                                                        
![My Image](Class_instance_count.png)  
