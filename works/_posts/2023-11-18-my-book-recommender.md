---
layout: post
title: My Book Recommender
truncated_preview: true
excerpt_separator: <!--more-->
order: 2
---

A new way to explore books aligned with your interest. Discover your next read by using my book recommending tool. 

## Overview
I developed a book recommending tool that leverages Python and effectively utilizes [OpenLibrary's Search API](https://openlibrary.org/dev/docs/api/search) to access and search a large database of books. This API allows for personalized recommendations using user input. The process involves making an API request based on a genre and keywords provided by the user, storing results in a Pandas DataFrame, and randomly choosing one of the results. This tool features a user-friendly GUI application made using [Tkinter](https://docs.python.org/3/library/tkinter.html) where the user can provide input and see their recommended book's information displayed. 

<!--more-->

## Development
This project began as a class assignment in the very first programming class I took at my university. However, the original version was much more limited since there were only six possible books that could be recommended, it was a terminal-based application, and functioned like a BuzzFeed quiz. 

My goal with this project was to expand on this by allowing the user to provide input on what they want to read, have more book options, and create a GUI for this application. 

I chose to use Python since that is what I used in the original project. Furthermore, I decided to use OpenLibrary's Search API after learning about it from a [public list of free APIs](https://github.com/public-apis/public-apis). The ability to access a large database of books and search within this database made the API suitable for my project. Developing the GUI was fairly straightforward because I have worked with GUI applications and the MVC design pattern in coursework. One of the main challenges was adjusting to Tkinter. My previous experience with GUI applications was with Java and JavaFX, but I was able to apply my background knowledge and reference Tkinter's documentation.  

## Further Thoughts
I learned how to use APIs and gained a better understanding of their uses. I feel that after working on this, I could confidently work on projects that make use of APIs. I found it extremely rewarding to demonstrate what I have learned in coursework since my first programming class and learn new technologies, such as APIs. 

Some future plans for this project include making it into a web or mobile application. Another idea involves enhancing the recommendation system of this tool. 