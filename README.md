# CSE168-Lightfield-Viewer

My CSE 168 project proposal is to implement a light field viewer that can take in datasets acquired from the new Stanford Light Field Archive, and render an interactive display of the light field. Once that is completed, I would hopefully try to implement some sort of compression method to make rendering the images more lightweight. Seeing how large the datasets from the Light Field Archive are, I can the necessity of compression methods to really speed up rendering in real time and make the interactivity more responsive and smooth.

![chess_image](chess_demo.png?raw=true)

My initial naive implementation was written in Python, as it allowed me to quickly modify the raw data contained in the light field to produce a final image. Currently, I have it set that by changing initial parameters, I can change the depth of field to produce images like the one above. However, It also takes much longer than expected to process and render the data and is nowhere close to being able to run in real time, so I will most likely have to rebuild what I have so far with a dedicated rendering engine like OpenGL, as recommended in the final project writeup.

There are still many things I need to understand about how the light field viewer works to properly implement it, but its applications look facinating. Looking at demos of the cutting edge light field viewers was incredibly impressive, especially at how the resulting image accurately shifted reflections and lighting, mimicking how the light reflections would work physically.

My current implementation is definitely incomplete, but overall it seems like an interesting and novel field of study to research and try to recreate myself.

