# To-Do-List-Class-Build
Building a to-do list in class

# Description/Summary
This is the class To-do list assignment, where we were tasked to create a To-do list in three boxes and  Use generic selectors to add some style and add an image/theme of your choice to the page. 

# Table of Content

# Nail day!
article h2 {
color: white;
padding:4px 8px;
}

article li{
    padding: 6px 8px;
    text-transform: uppercase;
}

# To-Do{
     border: 4px solid rgb
}

# To-Do h2{
     color: rgb
}
1. Exercise
2. Breakfast
3. First client of the day
4. Prepare for nail class
5. Teach Students
6. Dinner



# In-progress{
    border: 4px solid rgb
}

# In-progress h2{
  color: rgb
}
1. Exercise
2. Breakfast
3. First client of the day
4. Prepare for nail class
5. Teach Students
6. Dinner

# Done {
     border: 4px solid
}

# Done h2{
   color: rgb
}
1. Exercise
2. Breakfast
3. First client of the day
4. Prepare for nail class
5. Teach Students
6. Dinner

ul li{
     padding: 6px 8px;
    text-transform: uppercase;
}

.do li:nth-child(odd) {
    background-color: rgba(233, 22, 138, 0.838);
}

.progress li:nth-child(odd) {
    background-color: rgb(255, 156, 227);
}

.fin li:nth-child(odd) {
    background-color: rgb(187, 0, 255)
}

input[type="checkbox"]:checked + span::after {
    content: '\2713';  
    margin-left: 50px; 
    display: inline-flex;
    width: 15px;
    height: 15px;
    line-height: 15px;
    justify-content: center;
    align-items: center;
    font-size: 10px;
    background-color: rgb(109, 164, 206);
    border: 3px solid rgb(7, 3, 61);
}