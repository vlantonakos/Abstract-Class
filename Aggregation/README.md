# Aggregation
Aggregation is a narrower kind of association. It occurs when there’s a one-way (HAS-A) relationship between the two classes we associate through their objects.

For example, every Passenger has a Car, but a Car doesn’t necessarily have a Passenger. When you declare the Passenger class, you can create a field of the Car type that shows which car the passenger belongs to. Then, when you instantiate a new Passenger object, you can access the data stored in the related Car as well.

Aggregation in Java:
<ul>
    <li>One-directional association</li>
    <li>Represents a HAS-A relationship between two classes</li>
    <li>Only one class is dependent on the other</li>
</ul>
