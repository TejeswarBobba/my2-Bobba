# my2-Bobba
# Tejeswar Bobba
#### My favourite vacation spot is GOA
 It is the best place to enjoy with **friends** and is known for its **stunning beaches** and has many more **landscapes** which can be explored.

 
---

#### Activities Performed in favourite vacation spot 

1. Explored the besutiful beaches.
2. went to the ancient forts.
3. Tasted different types of sea foods in a restaurants.
- **Chicken Butter Masala:** Must try dish in Goa which has a unique taste.
- **Stuffed Crab Mixture:** Must try dish which is made up of smashed crab meat.
- **Fish Thali:** Must try dish where the different types of fish fry's and curry's are available.

For the personal information about me,click here [MyStats](MyStats.md).

---

#### Sports recommended to play

The below table describes about the different types of sports which are recommended to play.Also mentioned the reason and hours needs to spend on the respective sport.

| Sport | Reason | Hours to be spent per week|
|:---:|:---:|:---:|
| Cricket |Can help to develop physical fitness and will improve essential fine motor skills. | 4-6 |
| Badminton | Can help to strengthen the heart muscle and limit the risk of blood vessels clogging. | 3-4 |
| Football | will help in building strength, stamina and speed.Also used to improvr concentration and coordination.| 5-6 |
| Volleyball | will help to teach important lessons in perseverance, teamwork and selflessness. | 4-5 |

---

#### Pithy Quotes 

> "The important thing is not to stop questioning." - *Albert Einstein*

>"The more I learn, the more I realize how much I don't know." - *Isaac Newton*

---

#### Code Fencing 

> Relevant question on stack overflow : [Link for stack overflow question](https://stackoverflow.com/questions/25590269/styling-radio-button)

```
/*
  Hide the original radios and checkboxes
  (but still accessible)

  :not(#foo) > is a rule filter to block browsers
  that don't support that selector from
  applying rules they shouldn't

*/
li:not(#foo) > fieldset > div > span > input[type='radio'],
li:not(#foo) > fieldset > div > span > input[type='checkbox'] {
  /* Hide the input, but have it still be clickable */
  opacity: 0;

  float: left;
  width: 18px;
}


li:not(#foo) > fieldset > div > span > input[type='radio'] + label,
li:not(#foo) > fieldset > div > span > input[type='checkbox'] + label {
  margin: 0;
  clear: none;

  /* Left padding makes room for image */
  padding: 5px 0 4px 24px;

  /* Make look clickable because they are */
  cursor: pointer;

  background: url(off.png) left center no-repeat;
}

/* Change from unchecked to checked graphic */
li:not(#foo) > fieldset > div > span > input[type='radio']:checked + label {
  background-image: url(radio.png);
}
li:not(#foo) > fieldset > div > span > input[type='checkbox']:checked + label {
  background-image: url(check.png);
}
```
Source of the snippet has been taken from here :[Snippet source link](https://css-tricks.com/snippets/css/custom-checkboxes-and-radio-buttons/)