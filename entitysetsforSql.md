Description:
We build the fitness website. User can check the food nutrition, gym location, fitness class offering, and self-exercise detail. We also offer the fitness plan depends on the user’s information. User can use our website to manage their fitness plan.

Example of entities and relationships sets:
User:  userid, lastName, firstName, age, weight, height, target
Food: name, weight, cardio, carbon, protein, sodium
self-exercise: type, name, duration, cardio, difficultLevel, bodyFocus
fitness-class: id, name, training focus, cardio, startTime, duration
gym: id, address, name, openTime, closeTime, phone, email, className
plan: id, target, weight, period, cardioPerDay
have: userid, plan.id
include: plan.id, self-exercise.name, fitness-class.id