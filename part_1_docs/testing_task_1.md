### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1: #NEEDS TO BE == IN ORDER TO COMPARE VALUES
      return True
    else #MISSING : AFTER THE ELSE
      return False
   

  dif highest_card(self, card1 card2): #TYPOS: 'def' INSTEAD OF 'dif', MISSING COMMA AFTER 'card1'
  if card1.value > card2.value: #BLOCK NEEDS TO BE INDENTED
    return card #TYPO: SHOULD BE 'card1'
  else:
    return card2
  


def cards_total(self, cards):
  total #NEEDS TO BE ASSIGNED INITIAL VALUE OF 0
  for card in cards:
    total += card.value
    return "You have a total of" + total # CANNOT CONCATENATE STRING WITH AN INTEGER. USE FORMATTED STRING INSTEAD. THE RETURN ALSO NEEDS TO BE OUTSIDE THE FOR LOOP, ie INDENTED LEFT ONE.
  
```
