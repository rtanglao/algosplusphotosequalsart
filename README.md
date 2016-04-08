# Roland's UBC Visualizing Vancouver Visuals Talk April 4, 2016
1. [PDF](https://www.dropbox.com/s/ocv6y3mmbplab7o/photosplusalogorithms%3Dart.pdf?dl=0), [Keynote](https://www.dropbox.com/s/4r3jg1vcezk4t8c/photosplusalogorithms%3Dart.key?dl=0), [vvv on flickr](https://flickr.com/roland/tags/rolandtanglaoinfoviz)
2. datasets:
    3. [instagram vancover 2015 CSV file with top colour, lat, long, date](https://github.com/rtanglao/rtgram/blob/master/13March2016-abbreviated-instagram-vancouver-top-colour-lat-long-date-2015.csv.gz)
1. The missing video: [Vancouver Instagram 2015 top colour 365 ggmaps 1 week per second i.e. 7 fps](https://www.flickr.com/photos/roland/25318716224)
2. questions, comments? Please [file a github issue](https://github.com/rtanglao/algosplusphotosequalsart/issues/new) or email roland AT rolandtanglao.com

<hr />
# After UBCDSD now what :-) ?
## 05 April 2016
1. convert from ruby + R to all R? add in gganimate?
2. convert to Shiny?
3. visualize Anthony's Firefox Android mobile dataset using R?
4. Use [@ecohydrologist](https://twitter.com/ecohydrologist) aka Mark Johnson's music algorithms?

## 07 April 2016

1. going to start with gganimate
## 08 April 2016
1. I think I am not going to be able to do anything while I am away from Vancouver!

<hr />
**THE FOLLOWING MATERIAL IS OBSOLETE PLEASE IGNORE** :-)

## 04 April 2016 Algorithms + Photos = art
rough plan (maybe use shapecollage for letters):

1. Show the art
2. Show the photos
3. Show the algorithms
4. Show the narration
5. Show the Mentors

* Along the way mention narrating your work, using a glue language and have fun!
* mistakes happen
* everything breaks (APIs, databases, languages, you name it; OS eg. OS X can't handle 1 million files gracefully)
* do you need a database? at scale you do!?! YAGNI for small datasets; avoid impedance mismatches if the data is JSON leave it in JSON
* glue code you need it
* narrate your work daily
* r is the ultimate prototyping environment for "small" data
* have a mentor in your town / in your skype 
* perhaps use barcodes as background images? or as vertical dividers?

## PROGRESS 30 March 2016
1. used ```ln -s``` in an xargs loop to get 3000 files since dragging and dropping from a directory with a million files doesn't work very well at all

 ```sh
 find .. -name '*_n.jpg' -exec ln -s {} .  \;
 gm convert photos\ +\ algos\ \=\ art\ auto\ 34233\ x\  3540.png photos\ +\ algos\ \=\ art\ auto\ 34233\ x\  3540.jpg
```

1. [3000 shapecollage photos processed by gm convert from png to jpg](https://github.com/rtanglao/algosplusphotosequalsart/blob/master/photos%20%2B%20algos%20%3D%20art%20auto%2034233%20x%203540.jpg) ([better version on flickr](https://www.flickr.com/photos/roland/26120401556/))