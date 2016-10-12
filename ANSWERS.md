## Questions

1. What is the difference between new and create for a model?
New creates an instance of the model with undefined attributes while create creates an instance of the model with specified attributes and is saved to the database. 
2. What command combined with new will emulate the same behavior as create?
`<instance>.save!`.
3. What is the default integer column that exists on every table but we did NOT define?
The ID.
4. What single line of ruby code can insert a cat with the name "Kira" in the database?
Cat.create(:name=>"Kira")
5. How did you like this homework in comparison with the previous homeworks? I wished it would include more aspects of model & migration manipulation with perhaps more description of the fundamentals like HW2. Other than that, it was good.
