Spell scrolls are special magic items which store a specific spell for a time of need. Special knowledge is needed to create them, in addition to a great skill in enchanting and the ability of spellcasting. There are two types of spell scrolls: learning spell scrolls and invoking spell scrolls.
 
## Learning Spell Scrolls
 
Learning spell scrolls are commonly used to teach mages, both new and old, how to cast a certain spell. Anyone can learn a spell, regardless of their ability to cast it in practice. Once a creature attempts to learn a spell from the scroll via [[Proficiency and Downtime#Downtime Points|downtime training]], they must attune to the scroll to complete the process, consuming the scroll in the process. The costs for non-rare spells are as follows:
 
| **Spell Level** | **Cost per Magic Type of the Spell (sc)** | **Downtime Points Required** |
| --------------- | ----------------------------------------- | ---------------------------- |
| 1th             | 20                                        | 1                            |
| 2nd             | 35                                        | 1                            |
| 3rd             | 55                                        | 1                            |
| 4th             | 80                                        | 2                            |
| 5th             | 110                                       | 2                            |
 
For ease of calculation and notably spell scrolls of spells over 5th level, the price is given by:
```python
zeroth_cost = 10
first_inc = 10
add_inc = 5

def total_cost(level, types_num):
	cur = zeroth_cost
	for i in range(level):
		cur += first_inc + add_inc * i
	return cur * types_num

level = int(input("Enter scroll level: "))
types_num = int(input("Enter number of magic types: "))
print(f"Scroll cost - {total_cost(level, types_num)} sc.")
```
 
## Invoking Spell Scrolls
 
Invoking spell scrolls are used to invoke a certain spell within them. Every creature that can fulfill the normal components of the spell (usually verbal and somatic) can cast the spell inside the scroll by touching it and spending the spell's casting time. The scroll is consumed in the process.  

>[!note]
>The rules for spellcasting apply to the spell cast, e.g. casting an arcana spell without being at least a 1st level arcanist means that you won't add your proficiency modifier to the spellcasting modifier.