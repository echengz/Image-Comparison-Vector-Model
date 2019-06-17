Emily Cheng echeng6@jhu,edu
cs466 Information Retrieval and Web Agents, Spring 2016
Final Project

In this class we have learned different types of information retrieval and
language processing from four previous projects:

    Assignment 1: End-of-Sentence Detection and Text Segment Classification
    Assignment 2: Vector Models of Information Retrieval (Search Engine)
    Assignment 3: Lexical Ambiguity Resolution
    Assignment 4: Web Robots

My final project aims to take everything we've learned from these projects, but
apply it to color processing in images. Color can simply be considered another 
language; where we are used to looking at words and their context in the
sentence or phrase as an indicator for their significance, I looked at each
pixel's RBG values, which are specific to each color, and used that to begin
implementing the vector model.

This program essentially takes a user-supplied image, and runs various similarity
tests to either another user-supplied image, or through images found on the
web. Utilizing the second option places a web robot on a specified or default
website, and the robot will subsequently crawl and grab any images it finds
from thereon. The program will then report whether two images match or not. For
data collection, it can also run and output the results of the similarity tests
themselves.

While this project itself is small-scaled, the big-picture aim for this project
was to present a potential solution to the enormous art-theft problem that runs
rampant on the Internet. More information of this project as a whole, and the
process, can be read in the writeup.pdf provided. 