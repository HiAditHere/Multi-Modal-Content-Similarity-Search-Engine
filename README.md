# Assignment 4

image retrieval on basis of text is working
image retrieval on basis of image is working

I am getting the correct ID's. Actually fetching the images from the AWS is still left

to run this application, 

First install requirments.txt

```pip install -r requirements.txt```

Then, open 2 new terminals

in terminal 1 

```streamlit run Hello.py```

in terminal 2

```uvicorn app:app --reload```