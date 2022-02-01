# fabio-tests-nisargatman
<b>Vector AI assessment </b>

First, I went about becoming familiar with REACT and installed everything I thought I needed. I took an example template from:
```python
npx create-react-app my-app
```
and modified the app.js file to make use of the npm-reorder-images package. You must install this package 
```python
npm install react-reorder-images
```
We now have a list of images with captions as described in the JSON file. I didn't have loads of time for this project so I left it like that. The 2x3 grid and the overlay click feature can be made with some time working with the css of the file. The image spinner is a tad more complicated, I'm really not sure how I would approach this? I assume a gif stored locally and using a react- something like this npmjs.com/package/react-spinners (using react and halogen).
To start, navigate to my-app and run
```python
npm start
```
and it will pop up on a localhost.

<b>Backend bit. </b>
<br /> I created the ```information.json``` file in the src folder. I wrote a piece of code called ```information.py ``` to take the JSON file and insert it into a ```data.db``` file. This is obviously a more flexible format and integrates with a REST API. 

So, that's it. This was a really interesting project, everything is very different to what I've done before and I'd definitely like to work on something like this in the future. 
<br /> From here, I'd be looking for guidance on:
  - Best apporach for the spinner load thing
  - How does a REST API work?
  - Does this 'react' scale up well?
  - How do I integrate the backend python with the backend java. 






