# Task description

Implement a method, that determines on base on the allergy test score for the given person whether or not they're allergic to a given item, and their full list of allergies. Allergy test is represented by a single numeric score which contains the information about all the allergies the person has (that they were tested for). The list of allergens for test are:
- eggs (1)
- peanuts (2)
- shellfish (4)
- strawberries (8)
- tomatoes (16)
- chocolate (32)
- pollen (64)
- cats (128)     
**Note**: a given score may include allergens not listed above (i.e. allergens that score 256, 512, 1024, etc.). Your method should ignore those components of the score. For example, if the allergy score is `257`, your program should only report the `eggs` (1) allergy.