def calculate_age(current_years, birth_years):
  age= current_years - birth_years
  return age
  
  my_age = calculate_age(2020,1991)
  dads_age = calculate_age(2020,1963)
  print("I am" +str(my_age) +"years old and my dad is:" +str(dads_age)" years old")
