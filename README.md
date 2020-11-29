# Videonystagmography

Videonystagmography (**VNG**) is a technology for testing inner ear and central motor functions, a process known as vestibular assessment. It involves the use of infrared goggles to trace eye movements during visual stimulation and positional changes. 

(**Source** : [Wikipedia](https://en.wikipedia.org/wiki/Videonystagmography#:~:text=Videonystagmography%20(VNG)%20is%20a%20technology,visual%20stimulation%20and%20positional%20changes.))

## What is open-vng ?

**open-vng** is an open source library to motion track the pupil of an eye. It uses computer vision to do so.

To date, it's only working with a video sample **(nystagmus.mp4)** as there's a bunch of parameters to change.

It will automatically detects the pupil, draw some fancy lines and circles, then extract these nystagmus's movement into a .txt file **(log.txt)**

It then plots these datas, and draw a trend line to easily determine what kind of nystagmus is in the video.

## Why open-vng ?

Because **VNS/VNG hardware and software** is freaking **expensive** and **it shouldn't be**.

Anyone can build a VNS/VNG with **only a Raspberry** and a little **bit of Python**. (:

## Quick usage

```python
from open-vng import *

blabla
```

## Contributing
Pull requests are welcome. 


## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
