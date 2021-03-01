# Day One Reflection

**2/22/21**

## What does inheritance accomplish for us in C#?

It allows us to make classes that are similar but separate without having to re-write all the props they have in common. We can instead write a "base class" that includes all of them and pass those into the children classes with inheritance.

## How does member inheritance work in C#? Does a class inherit all members of the base class?

This depends on the accessability syntax that was used but generally a class takes in all the members of a parent class except the constructor and finalizers. You can control what is visible among those child classes with accessability modifiers however.

## How does accessability affect inheritance?

For almost all accessability modifiers, inheritance will work as normal, but anything marked as private won't be visible to the child classes. This may have some use cases, but you can access those private props if the child class is nestled inside the parent.

## Daily Project https://github.com/ethanvachon/inheritance-test
