# Another Counter 
 Redux is an open-source JavaScript library for managing application state.<br>
 It is most commonly used with libraries such as React or Angular for building user interfaces.<br>
 You've already created counters in vanilla javascript and using React.<br>
 We know that unlike React, in Redux we can access state from any where(within any comonent) and all the keys and values will be wrapped in one state.
 Now You will be creating a <strong>counter</strong> with some more functions than previous one using Redux. If user logged in show counter otherwise don't.<br>
 ## Acceptance Criteria
 - [ ] Overall state should be an object with keys as counter and islogged.
 - [ ] islogged tell whether is user is logged in or out depending on the value true and false respectively.
 - [ ] counter will tell current value which will be displayed on the screen.
 - [ ] value of counter will be only integers (+ve / -ve / 0).
 - [ ] if user logged in dispaly counter otherwise don't
 - [ ] intially user will be logged out(islogged: false) and (counter: 0)
 - [ ] should have ablility to change initial state.
 - [ ] render a button which have ```name='Login'```
 - [ ] By clicking on 'Login' button show the counter and change button which have ```name='Logout'```
 - [ ] By clicking on 'Logout' button remove the counter from dom and change button which have ```name='Login'```
 - [ ] render a input field which will take input a number.
 - [ ] counter will be updated by click three buttons ```+``` / ```-```/ ```Add amount```.
 - [ ] 'Add amount' will increase the value of counter by input field value.
 - [ ] '+' will increase counter by 1
 - [ ] '-' will decrease counter by 1
 - [ ] '+', '-' and 'Add amount' buttons should be visible.
 - [ ] display current counter value inside a tag which have attribute ```data-testid='counter```'
 

 
