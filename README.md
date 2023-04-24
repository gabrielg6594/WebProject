# WebProject

## Explanation 

In this code I have a frame for the original calendar in the middle. Using this it is possible to go around and see through the different days, months, and years. Aside from this I use JSON in `<script>` this part of a structure of code that is in a ``html`` file converts what ever is written inside into javascript code, in this case we need it to be JSON format in order to make events. 

This is the structure of the JSON code that is needed in order for an event to show up on the calendar
```
id: 'event1', // ID 
name: "New Year", // name 
date: "January/1/2023", // date 
type: "holiday", // type
```

This is the form and least amount of information required in order for the event to show up. 

This is the MVP the bare bones that will make it work 

AMVP

For the AMVP I am making a form that will take information and then will avitvely make a new event that will last until the page is refreshed. So far I have a form partically finished but am stuck on the part of how to take the input and display it as a temporary part (until refreshed).
