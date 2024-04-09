# User feedback: Switch two operators

- [ ] Users reported that they need the exponential function more often than the % operator and would like to switch their place

## Copilot Prompts
- open layout/activity_main.xml and switch to the code view
- "Where is the UI element for the exponential function?"
- "How should I change it to become the % function? Keep in mind there's is already % functionality somewhere in the file and this other eventhandler should be used. also rename the id but prevent collision"
- "(never output comments mixed in the XML output, since they are invalid syntax)"
- Copy the new button over, now let's update the old % button to become the exponential function
- "Where is the percent button that I now need to switch to exp?"
- Select the button XML element
- "make this now the exponential function button. Tie into the existing eventhandler for exp stuff, rename the ID"

# New Features: Add fizzbuzz functionality
- open Expression
- "Where is it doing any calculation in here?"
- open Calculator
- "Where should I put in a new method to calculate the amount of fizz from fizzbuzz?"
- "how can I integrate it with parseFactor?"
- "Where do I write the test for that?"