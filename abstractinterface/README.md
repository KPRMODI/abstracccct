1. You can't initiate the Enemy Class because it is abstracted meaning it is supposed to be hidden and it's inheritors and sub classes are supposed to be initiated because the methods are also abstracted.

2. If a subclass did not implement update() or attack() then it would not compile. This is because subclasses of abstract class parents must include the abstract methods and overload them.

3. Enemy[] demonstrates polymorphism because it is a list that stores the different classes of slime, skeleton, and dragon in the Enemy type and call the methods of update() and attack() for each of them which is polymorphism, many shapes and forms.

4. It is helpful for the Enemy class to have a concrete method like takeDamage() so that all the subclasses of Enemy have the same way of taking damage only with the amount of damage being changed for each of them. It mades the code more consistent and managable making the concrete method in the abstract class.

5. Yes it could be implemented with interfaces alone. You would just have to repeat more code and copy it to the classes like the methods which would be redundant which is why abstraction is better for this type of project for a 2d action RPG.
