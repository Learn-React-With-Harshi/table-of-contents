# `Learn React With Harshi 👩🏻‍💻 Series`
   Documenting my learning journey of [Namaste React Live Course](https://learn.namastedev.com/) conducted by Akshay Saini
   
## Table of Contents
This is the index page for all the chapters that we will be learning in this course. Following table contains summary of each chapter and link to the respective chapter. 

| Table of Content                                                                             |
| Chapter                                     | Summary                                        | Live Code Demo 
| ------------------------------------------- | :--------------------------------:             | 
| 1. [chapter-01-inception-namaste-react](https://github.com/Learn-React-With-Harshi/chapter-01-inception-namaste-react)   | Chapter-01 (Inception) was the first session of the Namaste React Live course. The whole class was excited about the beginning of a great course. We started learning react from scratch. Environment setup was clearly explained. Started with creating a simple Hello world program . First, using only html, then we tried to implement the same through javascript. Finally, we created a simple hello world program using React. Everything was done without installing any package. Unlike other courses which starts with create-react-app as first session, we tried writing the react code from zero. It was a true inception session for tranforming from ZERO to HERO in React. | [Chapter-01 Live ](https://learn-react-with-harshi-chapter-01.netlify.app/) | 
|  ```<Profile name = { "Harshi"} age={28}   />``` |  ``` const Profile = (props) => { let name = props.name; let age = props.age; } ``` |  
| 2.   Similar to the way mentioned in 1.          | Props object can be destructed using {} to receive only the required props| 
| ```<Profile name = { "Harshi"} age={28}   />```  | ``` const Profile = ({name, age}) => { } ```    | 
| 3. Using spread syntax                           |  And props objects destructed using {}        |
| ```<Profile {...props}   />```   | ``` const Profile = ({name, age}) => { } ```  |
