# BabyCarryWorkout

Static web page generated with Hugo (https://gohugo.io)

### install the hugo command line tool from the Hugo website, or use choco

choco install hugo -confirm

### after that, run and test locally:

hugo serve --themesDir themes

### generate the page that will be served on the web:

hugo

Goal is to automate the delivery of the final generated site to the hosting party. First try will be with Travis-ci.


### convert image to webp format

Google developers

https://storage.googleapis.com/downloads.webmproject.org/releases/webp/index.html

CMD windowr:

set path=%path;C:\Applicaties\libwebp-1.2.0-windows-x64\bin

example:
cwebp -q 80 image.png -o image.webp

