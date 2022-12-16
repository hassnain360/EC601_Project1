# EC601 Product Design: Project 1

## Hasnain Abdur Rehman, U26147857

## Photogrammetry: From 3-D Objects to Point Clouds

### Introduction

Photogrammetry refers broadly to the process of obtaining reliable information about the physical world in a computational form. Such information is essential to model the world around us, and this modelling finds applications in a vast amount of scientific fields. In photogrammetry, data is gathered from raw sources using light, electromagnetic radiation, sound waves, and other physical phenomenon, and then processed on a computer to obtain information about physical objects, landscapes, motion fields, etc. In case of light, for example, this data is collected via a camera. Seminal in many of today's tools and technologies that enable our world today, photogrammetry combines the fields of optics, projective geometry, software engineering, electromagnetic field theory, among others. Most technology industries in the modern age either rely directly  on photogrammetry or somehow benefit from it. This paper is a quick survery of the field: we look at the field, some tools involved, applications and latest research that's going on in the field. 


### Problem Statement

Obtaining digital representations of the physical world is an important computational challenge. The aim is to obtain digital representations as close to the reality as possible. This can include the dimensions, surface, texture, area, lighting, and other qualities of the subject. Naturally, constraints exist, over the hardware used to capture information from the world, as well as the software technqiues available to render the data to the required format as per the required use case.

Many variants of photogrammetry exist. Extraction of three-dimensional measurements from two-dimensional data (i.e. images) is one example. Some calcuations can be made to find out dimensions of objects in real world if some standard scale is arleady set. Photogrammetry can also be referred to extracting accurate color ranges and values representing such quantities as albedo, specular reflection, metallicity, or ambient occlusion from photographs of materials for the purposes of physically based rendering. 

Though digital representations have been constructed using various mixtures of specialized hardware, software and domain experts, the need for futher sophistication has not abated. In this project, I survey the field of photogrammetry, provide some examples of exitant and old technologies, and review the research going on in the field.

### History of the Field

At the heart of the field lies projective geometry, which allows calculations that give us information about the real world, by performing measurements on images. Aime Laussedat of the Corps of the French Army, who produced the first measuring camera in 1851, performed such experiments that gave birth to photogrammetry ideas. He continued the ideas of Leonardo da Vinci on projections, and performed the mathematical analysis of photographs as perspective projections, thereby increasing their application to topography.

Around 1858, ariel photography using hot air balloons also started. Almost concurrently (1858), but independently of Laussedat, Meydenbauer, in Germany performed the first experiments making critical measurements of architectural details by the intersection method in the basis of two photographs of the building. Soon, the stereoscopic principle of measurement was established, and the stereo comparator was designed, then the double projector (in 1898). The theories of perspective transformation, radial triangulation were presented by theordor Scheimpflug. This work led to  development of aerial surveying and aerial photogrammetery. World events like World War II, led to both sides making extensive use of  aerial photographs for their military operations. New developments of aerial photography techniques, such as the application of radio control to photoflight navigation, the new wide-angle lenses and devices to achieve true vertical photograph, etc. came into being. All these technologies come together and make up what is known as photogrammetry today. 


### Types of Photogrammetry

As mentioned earlier, photogrammetry can refer to a variety of processes which gather information about the physical world.

The canonical form of photogrammetry is 3-D modelling: making 3-D models of objects, typically using simple 2-D images obtained from cameras. These images can be from any source that is shifted around to take images of the object from different angles. After the retrival of multiple pictures of the object from different angles, these images are then passed to a photogrammetry software which calculates geometric information about the object and constructs a 3-D model of that object. 

Other varients exist, for example using high speed cameras flying on drones, sometimes called Ariel photogrammetry. Mapping from aerial photographs is the best mapping procedures yet developed for large projects, and are invaluable for military intelligence. The major users of aerial mapping methods are the civilian and military mapping agencies of the Government.

Another form is terrestial photogrammetry, where the cameras are fixed. This can be a camera trying to measure the speed of cars on the road. The principle underlying the method of terrestrial photogrammetry is exactly similar to that of plane table surveying, i.e. if the directions of same objects photographed from two  extremities of measured base are known, their position can be located by the intersection of two rays to the same object. 

We can divide terrestial photogrammetry into two branches: (i) Plane-table photogrammetry. (ii) Terrestrial stereo photogrammetry.

The plane table photogrammetry refers to taking a photograph of the area to be mapped from two or three stations. The challenge is the the identification of image points in a pair of photographs. In the case of homogeneous areas of sand or grass, identification might not be  possible.

In terrestrial stereo photogrammetry, stereoscopic measurement provides accuracy for pair of photographs, the camera base and the angles of intersection of the datum rays to the points to be measured can be considerably reduced since the camera axes at the two stations exhibit great similarity to each other. The image points which are parallactically displaced relative to each other in the two photographs are fused to a single spatial image by the stereoscopic measurement. Hence stereo photogrammetry may be preferred over plane table in some cases. 



### Applications & Research

Photogrammetry has vast applications in the fields of medicine, engineering, mapping, architecture, manufacturing, police investigation, cultural heritage, structural geology, real estate, film & entertainment, land surverying, etc. We will look at some of them below.


Use cases of photogrammetry include construction of planimetric and topographic maps, classification of soils, interpretation of geology, acquisition of military intelligence and the preparation of composite pictures of the ground.

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
