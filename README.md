# MasterMatch

## Project Description

MasterMatch is a platform that aims to simplify the process of searching and selecting Master's programs for prospective students globally. This web application provides a user-friendly interface that allows students to filter through a vast array of Master's programs based on their interests and requirements, enabling them to efficiently extract and filter information that matters most to them.
The application's primary objective is to provide a comprehensive and straightforward platform for prospective students to search, compare and contrast a broad base of Master's programs, thereby empowering them to make informed decisions when selecting the program that best suits their needs and aspirations.

#### Technologies Used:
Trying to make use of the concepts we used in our Algorithms and Data Structures class, as well as other classes, we used python to implement our algorithm. In regards to the structure of the program, we first of all created a class of our Master Programs that would allow us to store the data we wanted to store later with the desired attributes. We then created a hash table that would use the program name and the according university rank as a key and store the attributes of each program, such as the country name, language, etc, as values. We optimised this process by using list comprehension. As the core of our program, we then defined all the different filters and further used the textwrap package to make our user output more astheatically pleasing

#### Challenges Faced:
One of the major challenges we faced during the development of the MasterMatch application was the creation of a front end. Not having any experience with front ends, we decided to focus on the structure of our algorithm and the optimisation of its workings, and leave the frontend step for a later development stage. Missing a front end, what also came as a challenge to us was the implementation of a ‘save’ function for favourite programs, as, not implementing it through a button in a front end, this could end up in a very tedious and time consuming series of yes or no questions for each option displayed, which we wanted to avoid in order to keep the user experience lean. Lastly, the same holds true for the function of displaying more of the desired data of the fitting programs to the user. We saw the possibility of implementing this through an extra question, in which the user could specify which attributes of the program they would want to be displayed, however, we preferred a lean user experience over a multitude of questions. Putting ourselves in the shoes of a user, we assumed that it would be suffi	cient to be able to filter for the attributes that we care about most, and thereby already make sure that those are fulfilled. This idea was also confirmed when revisiting our interviews and talking to our test users. 

Besides that, making sure that our program does not crash, no matter what the user inputs (so mainly input vallidation) was also a big challenge. This was mainly due to many different data types being present in the dataset, which took us a while to understand and fix accordingly, like for example the fact that currency type was not a string and so on. This also challenged us to not only understand our data very well, but also to thoroughly understand the interaction between the filter functions and the main functions, in order to know where to implement which error statements, and where to include the loops to repetitively ask for user input. 

#### Features to Implement in the Future:
The MasterMatch application is still in development, and we plan to add the following features in the future:
- User profiles: A user can create a profile and save their favourite programs, making it easy to access them later.
- Click and obtain more information: The user should be able to click on any program and get all information stored in our database, plus a ink to an official website
- Reviews and ratings: A review and rating system that enables students to rate and review programs based on their experience, thereby providing insights for other prospective students.
- FAQ section: Answering frequent questions about how the program works, possibly also serving as a resource to guide students in the process of making their decision

#### Motivation:
The motivation behind the MasterMatch application was to simplify the process of searching and selecting Master's programs for prospective students. We realised that the process of searching for a Master's program can be tedious, time-consuming, and overwhelming, with little to no guidance. We built the application to provide students with a comprehensive platform to compare and contrast different programs based on their interests and requirements, making the process more efficient and students better informed.

#### Problem Solved:
The MasterMatch application solves the problem of the tedious, time-consuming, and overwhelming process of searching for a Master's program. The platform provides a user-friendly interface that allows students to filter through a vast array of Master's programs based on their interests and requirements, empowering them to make informed decisions when selecting the program that best suits their needs and aspirations. The application streamlines the process of searching for a Master's program, and allows its users to optimise their research and decision making process. 




## How to Install and Run the Project

Having realised our project in one single .ipynb file, in  order to use it, you must simply download this file. Before running it, it is additionally necessary to download the dataset provided, and load it in the appropriate manner to your python interpreter (or google colab). In the .ipynb file we provided, the first few lines of code are dedicated to mounting the google drive and reading the csv from there. It is essential to adapt this section, as the location of the downloaded csv dataset will be a different one on your device, most likely not on google drive, except for if you upload it to your drive beforehand. Hence, please adapt the input for the read_csv command accordingly to where your dataset is stored. 

Regarding necessary packages, those are the packages used that must be installed to run the program:
pandas
numpy 
Textwrap


Lastly, to run the program, you should make sure that the condition __name__ == "__main__" holds true in order for the algorithm to execute when running the file. Alternatively, you may run main() separately. The algorithm should now execute. 





