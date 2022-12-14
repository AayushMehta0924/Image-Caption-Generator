# Content Based Image Captioning
This project is used to generate caption for the images requested as an argument. This project uses the technique known as <b> Reverse image search engine</b> where it search for the similar images as input and on bases of that image retrive the caption from the knowledge base.

## How To Use It?
1. `pip install -r requirements.txt`
2. Once the installion of the file is done you are all set to locally run <b>imageCaptioning.py</b> in order to get caption to your image
3. TO execute it run `python imageCaptioning.py --image "path to the image"`

## Run with Docker
```shell
# 1. First, clone the repo
$ git clone https://github.com/AayushMehta0924/Image-Caption-Generator.git
$ cd Content-Based-Image-Captioning

# 2. Build Docker image
$ docker build -t Content-Based-Image-Captioning .

# 3. Run!
$ docker run -it --rm -p 5000:5000 Content-Based-Image-Captioning
```

### Sample :-
<p align='center'>
 <img src="samples/images.jpg" alt='A surfer riding a large wave in the ocean.'>
</p>
<br/>
<h2 align='center'>A surfer riding a large wave in the ocean.</h2>

### Demo :-
A demo site has been deployed to give better visual understanding of the project itself it is written in flutter for android, it is currently in beta stage and will keep on getting updated.
<a href='https://imagecaptioning-ec0f5.web.app/#/'>Here is the link to the site</a>
