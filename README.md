Paper: A Pragmatic Machine Learning Approach to Quantify Tumor-Infiltrating Lymphocytes in Whole Slide Images ([Link](https://api.nva.unit.no/publication/0198cc44342f-0b194d89-cbc9-4ffb-b2a5-78988c93ab77))

1. Install or verify that the following on your system:
 - Docker 
 - Nvidia-drivers
 - Nvidia docker
 - CUDA & cuDNN

2. Build image from sources
Run `docker build -t hover:1.0 .`in Dockerfiles folder.

3. Make a file structure for mounting to container
e.g. </data/input/some_dataset/Images/>, </data/output/infer/>
![Tree structure example](./tree_structure_template.png)

4. Modify <launch.sh> script and run it.
