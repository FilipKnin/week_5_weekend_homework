### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby
### Testing task 2 code:

# Carry out dynamic testing on the code below.
# Correct the errors below that you spotted in task 1.

require_relative('card.rb')
class CardGame

 #incorrect name of method
  def checkforAce(card)
    # "=" assignment operator used instead of comparison "=="
    if card.value = 1
      return true
    else
      return false
    end
  end

  # incorrect syntax defining method "dif" used instead of "def"
  dif highest_card(card1 card2)
  #incorrect incrementations
  if card1.value > card2.value
    # .name not defined; card - not existing variable
    return card.name
  else
    #missing return
    card2
  end
end

#class CardGame ended in wrong line
end
 #incorrect incrementations
def self.cards_total(cards)
  #variable total should have assigned value to 0
  total
  for card in cards
    total += card.value
    #incorrect syntax
    return "You have a total of" + total
  end
end

#class CardGame should be ended here

```
