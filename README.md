# -Smart-Queuing-System
A computer vision system deployed on the edge, using Intel's OpenVINO, to count the number of people in a queue.

## Project Overview
Three different scenarios that depict real-world problems for Computer Vision on the egde are provided in "Project Scenarios.pdf."

The create_python_script notebook writes out the smart_queue detection app, while the create_job_submission script is a pipeline to submit various inferencing jobs from the given case studies. 

The manufacturing, retail and transportation notebooks submit the jobs to Intel's DevCloud to run the inferencing jobs on various Intel's Hardware and produce a simulated result on the performance metric (frames per second, model load time, and inference speed) of the system on various Intel hardware.

The hardware proposal and a comparison of the performance of the various hardware is given in Choosing the Right Hardware.pdf.
