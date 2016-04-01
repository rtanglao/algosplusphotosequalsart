# 04 April 2016 Algorithms + Photos = art
rough plan (maybe use shapecollage for letters):

1. Show the art
2. Show the photos
3. Show the algorithms
4. Show the narration

Along the way mention narrating your work, using a glue language and have fun!

## PROGRESS 30 March 2016
1. used ```ln -s``` in an xargs loop to get 3000 files since dragging and dropping from a directory with a million files doesn't work very well at all

```sh
find .. -name '*_n.jpg' -exec ln -s {} .  \;
gm convert photos\ +\ algos\ \=\ art\ auto\ 34233\ x\ 3540.png photos\ +\ algos\ \=\ art\ auto\ 34233\ x\ 3540.jpg
```

1. [3000 shapecollage photos processed by gm convert from png to jpg](https://github.com/rtanglao/algosplusphotosequalsart/blob/master/photos%20%2B%20algos%20%3D%20art%20auto%2034233%20x%203540.jpg) ([better version on flickr](https://www.flickr.com/photos/roland/26120401556/))