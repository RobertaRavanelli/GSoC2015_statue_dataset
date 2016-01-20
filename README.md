# GSoC2015_statue_dataset
Dataset realized for the video of GSoc 2015 structured light project 
https://www.youtube.com/watch?v=O5P65CYqo_Q

Inside your opencv build directory, remember to change all the paths (also that inside the images list yaml files) and then run the sample example_structured_light_pointcloud.

For my paths:

// Statue front side
./bin/example_structured_light_pointcloud /home/roberta/Sviluppo/GSoC2015_statue_dataset/images_statue_front_side.yaml /home/roberta/Sviluppo/GSoC2015_statue_dataset/calibrationParameters.yml 1280 800

// Statue back side
./bin/example_structured_light_pointcloud /home/roberta/Sviluppo/GSoC2015_statue_dataset/images_statue_back_side.yaml /home/roberta/Sviluppo/GSoC2015_statue_dataset/calibrationParameters.yml 1280 800

// Statue with GSoC shirt
./bin/example_structured_light_pointcloud /home/roberta/Sviluppo/GSoC2015_statue_dataset/images_statue_gsoc_shirt.yaml /home/roberta/Sviluppo/GSoC2015_statue_dataset/calibrationParameters.yml 1280 800 1 1




