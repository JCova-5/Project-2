# Project Overview

## Project Links

- [add your github repo link]()
- [add your deployment link]()

## Project Description

My project will be an NBA info page. You will be able to Tap on a team and find their information.
You will also be able to do the same for a player which will display a bit of information about the player.

## API

https://www.balldontlie.io/api/v1/players/



```
{data: {{
"id": 237,
"first_name": "LeBron",
"height_feet": 6,
"height_inches": 8,
"last_name": "James",
"position": "F",
"team": {
"id": 14,
"abbreviation": "LAL",
"city": "Los Angeles",
"conference": "West",
"division": "Pacific",
"full_name": "Los Angeles Lakers",
"name": "Lakers"
},
"weight_pounds": 250
}} }
```


## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Also, define the the React components and the architectural design of your app.

- [add link to your wireframes](https://www.figma.com/file/z9tyc9XTJXGGIBbI787nte/Untitled?node-id=40%3A12)
- [add link to your react architecture](https://www.figma.com/file/q3dfFMsRx5wq8gVjxL2kD1/Untitled?node-id=4%3A2)


### MVP/PostMVP - 5min

After completion, user will be able to find player and team information. There will be a page for Team listing and the user will be able to tap on the team and see information displayed on page. This will be the same for the player page.  

#### MVP EXAMPLE
- Find and use external api 
- Render data on page 
- Allow user to interact with the page
- Display information by specific choice of player or team.

#### PostMVP EXAMPLE

- Add localStorage or firebase for storage

## Components
##### Writing out your components and its descriptions isn't a required part of the proposal but can be helpful.

Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components. 

| Component | Description | 
| --- | :---: |  
| App | This will make the initial data pull and include React Router| 
| Header | This will render the header include the nav | 
| Footer | This will render the header include the nav | 
| App.js | Will be the complete Parent component. | 
| TeamPage | Child component that will render the team information when clicked | 
| PlayerPage | This will render the player information when clicked. | 


Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe. Also, put a gif at the top of your Readme before you pitch, and you'll get a panda prize.

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Setting up component Skeleton | H | 1hrs| :---: | :---: |
| Working with API | H | 5hrs| :---: | :---: |
| Building components | H | 8hrs| :---: | :---: |
| Make Responsive | H | 5hrs| :---: | :---: |
| Editing Links | H | 4hrs| :---: | :---: |
| ? | H | ? | :---: | :---: |
| Styling | M | 5hrs| :---: | :---: |
| Total | H | 28hrs| :---: | :---: |

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project such as Axios, ReactStrap, D3, etc. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description.  Code snippet should not be greater than 10 lines of code. 

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```
