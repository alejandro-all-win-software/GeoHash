# GeoHash

Geohash is a system for encoding a ```(latitude, longitude)``` pair into a single Base32 string. In the Geohash system the world is divided into a rectangular grid. Each character of a Geohash string specifies one of 32 subdivisions of the prefix hash. For example the Geohash ```abcd``` is one of 32 four-character hashes fully contained within the larger Geohash ```abc```.

The longer the shared prefix between two hashes, the closer they are to each other. For example ```abcdef``` is closer to ```abcdeg``` than ```abcdff```. However the converse is not true! Two areas may be very close to each other while having very different Geohashes:

<img width="302" alt="Screen Shot 2021-06-20 at 1 58 09 PM" src="https://user-images.githubusercontent.com/83901702/122663789-8e411f00-d1cf-11eb-9a84-c05246d97a0d.png">
