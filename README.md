# Cplusplus-Program

This project is intended to demonstrate a link between Java methods and C++ front end using JNI. This project was designed in an attempt to help a mock company maintain animal information by utilizing a .txt file as a database. It can take in information about 6 different sub-classes of animals, store it to a .txt file, read said .txt file, allow for manipulation of the loaded data and then save it back to the .txt file. Through development of this program, I learned something new which was creating a vector of unnamed objects to store the data. This way, I could utilize conditional checking on the data being read by the file stream to ensure that the correct object type was created based on the sub-class of animal. From that, this code could benefit from a more complete JNI link as the current one doesn't function as intended. Similarly, this program has a few sections of hard coded error checking which could be improved utilizing other strategies. 

For this program, the most challenging part was maintaining everything which needed to be done. This was developed incrementally with very small steps between moving on. Something as simple as not capturing the correct sub-class of animal in each step could lead to a plethora of errors down the road. This was shown when trying to pull attribute information out of the unnamed objects yielded results such as "-1592392529384" when trying to retrieve the name. This example was caused by declaring a variable, such as nurse, in a base class but then also declaring it in the sub-class. This led the program to only pull the information from the sub-class rather than the base. 

As for what this project will provide to me in the future, it satisfied my curiosity on how we might be able to combine different languages together. It was a very basic example of this however it was fascinating to work through. I look forward to future examples of combing languages to achieve a goal. As for the future, this program is adaptable by simply adding in new sub-classes of animals and ensuring that the functions which pull data check for those types. The entire project is commented in order to allow future users, or myself, to make additions to it. 

This was a really fun project to make and I look forward to doing more in the future!
