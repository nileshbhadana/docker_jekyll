# docker_jekyll
This is for launching a Jekyll server on docker container using jekyll server image.
This uses bretfisher/jekyll-serve as image and is basically a practise for bind mounts.
  > first be in this directory
  
  Launch the container as follows:
  
  > docker container run --name jekyll-server -p 80:4000 -v $(pwd):/site bretfisher/jekyll-serve


  
  
# about Jekyll
Jekyll is a simple, extendable, static site generator. You give it text written in your favorite markup language and it churns through layouts to create a static website. Throughout that process you can tweak how you want the site URLs to look, what data gets displayed in the layout, and more.
