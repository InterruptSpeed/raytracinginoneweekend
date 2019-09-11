# raytracinginoneweekend
repo contains my follow-along of Peter Shirley's book

# build and usage on windows

```
// Chapter N where N is a number between 1 and 7
cl chapterN.cpp /EHsc
chapterN.exe > N.ppm
```

```
g++ chapterN.cpp -o chapterN
./chapterN -o N.ppm
feh N.ppm
```
