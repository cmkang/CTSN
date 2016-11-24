# CTSN

#Detection and Recognition of Text Embedded in Online Images via Neural Context Models

![alt tag](https://raw.githubusercontent.com/cmkang/CTSN/master/intro.png)

This project hosts the code and dataset for our AAAI 2017 paper

We address the problem of detecting and recognizing the text embedded in online images that are circulated over the Web. 
Our idea is to leverage context information for both text detection and recognition. For detection, we use local image context around the text region, based on that the text often sequentially appear in online images. For recognition, we exploit the metadata associated with the input online image, including tags, comments, and title, which are used as a topic prior for the word candidates in the image. 
To infuse such two sets of context information, we propose a \textit{contextual text spotting network} (CTSN). We perform comparative evaluation with five state-of-the-art text spotting methods on newly collected Instagram and Flickr datasets. We show that our approach that benefits from context information is more successful for text spotting in online images.


##Reference

```
@inproceedings{ctsn:2017:AAAI,
    author    = {Chulmoo Kang, Gunhee Kim and Suk I. Yoo},
    title     = "{Detection and Recognition of Text Embedded in Online Images via Neural Context Models}"
    booktitle = {AAAI},
    year      = 2017
}
```

##Code and Dataset
Comming Soon(in Feb. 2017)





