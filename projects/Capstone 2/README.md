A Sample quiz project can be developed following the following checklist;

- [ ] Step1
	- [ ] Create a simple mock-up like this https://drive.google.com/file/d/1yTcwpGifgGbEQ7ExgndbbUt0Sb6qhCxG/view
	- [ ] create  project structure (html , css, js files and folders)
	- [ ] link in files, jquery and bootstrap
	- [ ] add static texts
	- [ ] add question and answer section 

- [ ] Step 2
	- [ ] get a list of questions and answers. You can have as many questions as possible but can decide to randomly select 5 per quiz session.
	- [ ] create an array of objects to save these data. It should look like this;
	```
	const qAndA = [
		{
			question: “What is the capital city?”,
			options: [“Lagos”, “Abuja”, “Ibadan”, “Jos”],
			answer: “Abuja”
		},
		{
			question: “How old is the president?”,
			options: [“29”, “49”, “99”, “76”],
			answer: “76”
		} 
		...
		];
	```

- [ ] Step 3
	- [ ] on page load,
	- [ ] select randomly, 5 q and a objects  from the qAndA list
	- [ ] start a loop to run 5 times
	- [ ] render the first question and options in the question section or div
	- [ ] maintain a score point counter , initial value is 0
	
- [ ] Step 4
	- [ ] on clicking an option, 
	- [ ] take the selected option in a variable
	- [ ] check if correct
	- [ ] increase score point if correct
	- [ ] clear contents of question section
	- [ ] render the next question from the 5 selected
	- [ ] continue this loop till all 5 questions are answered 

- [ ] Step 5
	- [ ] on completion,
	- [ ] replace question section with success section
	- [ ] populate success section with result and congratulation messages 


- [ ] Step 6
	- [ ] Styling
