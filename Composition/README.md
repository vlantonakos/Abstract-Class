# Composition

Composition is a stricter form of aggregation. It occurs when the two classes you associate are mutually dependent and can’t exist without each other.

For example, take a Car and an Engine class. A Car cannot run without an Engine, while an Engine also can’t function without being built into a Car. This kind of relationship between objects is also called a PART-OF relationship.

Composition in Java:
<ul>
    <li>A restricted form of aggregation</li>
    <li>Represents a PART-OF relationship between two classes</li>
    <li>Both classes are dependent on each other</li>
    <li>If one class ceases to exist, the other can’t survive alone</li>
</ul>
