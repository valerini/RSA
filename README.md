# RSA

This repo contains all the files necessary to render azbuka.stanford.edu.
The main file where everything starts is index.html.

If you want to edit:

1. First always do
> git pull

2. After edits check that everything renders well in the browser by opening index.html local file.

3. Commit changes to the shared repository:
> git add "your files"
> git commit -m "message"
> git push -u origin master

4. To publish (i.e. make azbuka.stanford.edu display your local copy) run
> sh upload.sh
You may need to edit upload.sh to make it upload the files that you've changed (there is a file mask).
