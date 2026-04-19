# CountList
This class exists as a way to count elements without having to do much work; just add the elements, and you get your count.
The list is sorted by order of insertion.

# HOW TO USE
Download the .jar file, then you'll want to import the jar into your project (it's best that you look this part up, because different programs have different ways of doing this), then at the very top of whichever class you're writing, write "import com.stinky.countlist.CountList".

CountList Methods
        .print(): Returns every node of the CountList and their values. EX: list = {"hello", "hello", "hi"}, typing
        System.out.println(list.print()) prints: <hello:2, hi:1>
        -
        .add(String): Adds a new node if it doesn't exist, if it does exist, increments the value of the node by 1.
        -
        .remove(String): Removes an existing node if it's value is 1, otherwise, decrements the value by 1.
        -
        .length(): Returns the length of the CountList. EX: list = {"hello", "hello", "hi"}, typing list.length() returns 2,
        because the number of nodes is 2.
        -
        .destroy(): Completely destroys the list, removing every node and it's value.
        -
        .destroyNodeFromPos(int): Destroys the node at the specified position.
        -
        .destroyNodeFromKey(String): Destroys the node associated with the specified key.
        -
        .toArray(): Converts the list from CountList to a String array. EX: <hello:2, hi:1> turns into ["hello", "hello", "hi"]
        -
        .getValueFromKey(String): Returns the value of the key you entered. EX: Hello = 3, if you type list.getValue("Hello") then
        you'll get 3.
        -
        .getValueFromPos(int): Returns the value at the entered position. EX: EX: list = {"HELLO", "HELLO", "HELLO", "HEY", "HI", "HI"}
        position = 0, returns 3 because the value of HELLO — which is in position 0 — is 3.
        -
        .getKey(int): Returns the node at the specified position. EX: list = {"HELLO", "HELLO", "HELLO", "HEY", "HI", "HI"}
        list.getKey(0) returns "HELLO", because that's the first node.
