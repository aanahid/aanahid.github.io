---
layout: post
title: My Book Recommender
truncated_preview: true
excerpt_separator: <!--more-->
order: 2
---

A new way to explore books aligned with your interest. Discover your next read by using my book recommending web app. 

![Book Recommender Website](/images/book.png)

## Overview
I developed a dynamic book recommending web app that integrates [React](https://react.dev/) for the frontend and [Flask](https://flask.palletsprojects.com/en/3.0.x/) (Python) for the backend. This tool effectively utilizes [OpenLibrary's Search API](https://openlibrary.org/dev/docs/api/search) to access and search a large database of books for the users recommendation. The process involves making an API request based on a genre and keywords provided by the user, storing results in a [pandas DataFrame](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html), and randomly choosing one of the results. 

You can view this project on [Github](https://github.com/aanahid/book-recommender).

<!--more-->

## Development

This project has undergone several iterations to improve user experience. This project began as a class assignment in the very first programming class I took at my university. However, the original version was much more limited since there were only six possible books that could be recommended, it was a command-line interface (CLI) application, and functioned like a BuzzFeed quiz. To make this project more user-friendly, the project evolved into a graphical user interface (GUI) application using [Tkinter](https://docs.python.org/3/library/tkinter.html). 

Most recently, the latest version of the project has been developed into a web application using React and Flask. When designing the user interface, I utilized [Figma](https://www.figma.com/file/XdiOOfMX4iLKwlVdMOxM45/My-Book-Recommender?type=design&node-id=0%3A1&mode=design&t=E7AE3xtfwp1r1EFP-1). The web app version offers a dynamic and responsive interface, making it even more convenient for users to explore book recommendations based on their preferences. 

![Book Recommendation](/images/book_withrec.png)

I chose to use Python for the backend since that is what I used in the original project. I also wanted to gain experience using [Flask](https://flask.palletsprojects.com/en/3.0.x/), a web framework for Python. Furthermore, I decided to use OpenLibrary's Search API after learning about it from a [public list of free APIs](https://github.com/public-apis/public-apis). The ability to access a large database of books and search within this database made the API suitable for my project. 

## Further Thoughts
I learned how to use APIs, developed a better understanding of their uses, and gained experience in developing both the frontend and backend of a web application. I feel that after working on this, I could confidently work on projects that make use of APIs. I hope to further advance my web development skills after this project. I found it extremely rewarding to not only demonstrate what I have learned in coursework since my first programming class, but also learn to use new technologies, such as APIs. 

Some future plans for this project involve enhancing the recommendation system of this tool. 