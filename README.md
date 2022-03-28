# COSC140 lab 3

## Answers to the five questions at the end of the lab description

1. p1 = Product.objects.create(name="stuffed shark", description ='soft, but with pointy teeth', price=45.00, minimum_age_appropriate=2, maximum_age_appropriate=43)

2. Product.objects.all()

3. Product.objects.filter(id=6).update(price=22.50)

4. Product.objects.get(id=6).delete()
The ID for deleted objects is None.

5. objects = Product.objects.filter(price__lt=20).order_by("name")
print(objects)

## Lab feedback

 * How long did you spend on this lab?
I was able to finish the lab within the class period and lab period
 * What did you think about it?  What was good?  What could be improved?
I liked this lab. It was a really fun way to learn how objects and classes are related to each other, and how they can be implemented into a database. I thought it was challenging enough but also conceptually easy enough for me to do by myself.
## Feedback

S

Well done!

