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

# should be double equals(==), rather than single(=) after card.value. We're checking if they're the same, not telling the computer they are identical.
# Also need a colon(:) after the else statement.
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
# in function below, it should be "def highest_card" not "dif highest_card". "dif" is a spelling error."
# need a comma after card1 in the line declaring the function name.
# the 'if' statement needs to be indented, as well as everything below it.
# on the first return, it should be "return card1", not 'return card'. As it is, card is undefined.
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  

# in function below, "total" is undefined. Need to set it with '0'.
# the whole function also needs to be indented under "class Cardgame".
def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```
