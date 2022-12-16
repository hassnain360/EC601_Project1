# EC601 Product Design: Project 1

## Hasnain Abdur Rehman, U26147857

## Photogrammetry: From 3-D Objects to Point Clouds

### Introduction

Photogrammetry refers broadly to the process of obtaining reliable information about the physical world in a computational form. Such information is essential to model the world around us, and this modelling finds applications in a vast amount of scientific fields. In photogrammetry, data is gathered from raw sources using light, electromagnetic radiation, sound waves, and other physical phenomenon, and then processed on a computer to obtain information about physical objects, landscapes, motion fields, etc. Seminal in many of today's tools and technologies that enable our world today, photogrammetry combines the fields of optics, projective geometry, software engineering, electromagnetic field theory, among others. Most technology industries either rely on photogrammetry or som

### History of the Field

### Types of Photogrammetry

Photogrammetry can refer to a variety of processes which gather information about the physical world.

The canonical form of photogrammetry is 3-D modelling: making 3-D models of objects, typically using simple 2-D images obtained from cameras. These images can be from any source that is shifted around to take images of the object from different angles. After the retrival of multiple pictures of the object from different angles, these images are then passed to a photogrammetry software which calculates geometric information about the object and constructs a 3-D model of that object. 

 calculates Other varients exist, for example using high speed cameras flying on drones, sometimes called Ariel photogrammetry. Another form is terrestial photogrammetry, where the cameras are fixed. This can be a camera trying to measure the speed of cars on the road. 



### Problem Statement

Obtaining digital representations of the physical world is an important computational challenge. The aim is to obtain digital representations as close to the reality as possible. This can include the dimensions, surface, texture, area, and other qualities of the subject. Naturally, constraints exist, over the hardware used to capture information from the world, as well as the software technqiues available to render the data to the required format as per the required use case.

Many variants of photogrammetry exist. Extraction of three-dimensional measurements from two-dimensional data (i.e. images) is one example. Some calcuations can be made to find out dimensions of objects in real world if some standard scale is arleady set. Photogrammetry can also be reffered to extracting accurate color ranges and values representing such quantities as albedo, specular reflection, metallicity, or ambient occlusion from photographs of materials for the purposes of physically based rendering. 

Though digital representations have been constructed using various mixtures of specialized hardware, software and domain experts, the need for futher sophistication has not abated. In this project, I survey the field of photogrammetry, provide some examples of exitant and old technologies, and review the research going on in the field.

### Applications & Research

Photogrammetry has vast applications in the fields of medicine, engineering, mapping, architecture, manufacturing, police investigation, cultural heritage, structural geology, real estate, film & entertainment, land surverying, etc. We will look at some of them below.

Photogrammetry performed to obtain 3-D models of physical world objects are indispensible in today's world: such models can easily be used in AR/VR settings, games, and other artificial settings like driving simulation programs. 3-D models of ancient artifacts are also obtained using photogrammetry for their preservation and remote view access throughout the world. 



Ariel photogrammetry is the de-facto method to obtain maps -- proven to be  accurate and cost-effective. Photogrammetry has a cardinal advantage over a similar technology, LIDAR, that it is very cost effective, since it only requires images. 


A very common use is creation of maps using aerial photogrammetry . Google maps has an enormous use-base, and is an important use-case of photogrammetry.  To create such maps, the camera is mounted in an aircraft and is pointed vertically towards the ground. en As the aircraft flies, multiple images of the ground are taken. The aircraft traditionally have been fixed wing manned craft but many projects now are done with drones and UAVs. Traditionally these photos were processed in a stereo-plotter (an instrument that lets an operator see two photos at once in a stereo view) but now are often processed by automated desktop systems. This is an example of evolution and necessity of photogrammetry in making real world accessible to us in our digital devices. 

### Research Directions, Industry Innovations & More ...

Due to its ubiquity, there is a blooming open source community on photogrammetry. Softwares like AliceVision, All3dp, Meshroom, Colmap, Micmap are used for various photogrammetry purposes. 

 Photogrammetry is being used in startups using the these maps to use AI to obtain information about the world, for example population densities, deforestation, etc.


Other products with commerical support for General Applications include `Context Capture & Acute 3D`, `PhotoModeler` ,  `PhotoScan`,  `Pix4dMapper` , `Reality Capture`, `Recapn addition`. `DataMapper` &  `DroneDeploy` are  more specifically aimed at just UAV / drone photograhy and are cloud based.     

Other power aerial photogrammetry mapping platforms include `BAE Systems SOCETSET` , `DAT/EM International Summit Evolution `, `Intergraph Z/I Imaging`, `KLT Associates ATLAS`,  `PCI Geomatics`.


### Conclusion

The field of photogrammetry is vast. We can looked at some common modalities, softwares, and use cases where photogrammetry is used. With the advent of AI, so much more is being done using photogrammetry; one exellent example is using photogrammetry to build virtual worlds, aka. 'the Meta-verse'. We will see more sophiscated softwares, standards and use-cases as the field progress alongside other booming technologies. 


### Resources

[1] https://en.wikipedia.org/wiki/Photogrammetry#Mapping
[2] https://www.dronegenuity.com/aerial-photogrammetry/
[3] https://www.esri.com/en-us/arcgis/products/imagery-remote-sensing/capabilities/mapping
[4] https://www.photogrammetry.com/photogrammetry-software.htm
[5] https://books.google.com/books?hl=en&lr=&id=D4h8EAAAQBAJ&oi=fnd&pg=PA1&dq=photogrammetry&ots=6ILV1UzExr&sig=hcOkvJSTU7UdYB6ey4Y8y3eZQH8#v=onepage&q=photogrammetry&f=false
[6] https://www.allthescience.org/what-is-aerial-photogrammetry.htm
[7] https://formlabs.com/blog/photogrammetry-guide-and-software-comparison/
[8] https://www.pix4d.com/blog/lidar-photogrammetry
[9] https://modtechlabs.com/beginners-guide-photogrammetry/
