# Data Structures

- if we use more than one "json key" in json object, automatically old values overiding with latest values.

- to overcome above overriding, we are using data structures.

  1. Map
  2. WeakMap
  3. Set
  4. WeakSet

# Map() Data Structures

- map won't allow duplicate keys(if keys are primitive)

- map allows duplicate keys( if keys are object)

- map used to store the data in the form of a key & value pairs
  clear()
  Map()
  delete()
  entries(),forEach(),for....of()
  get()
  has()
  keys()
  set()
  values()
  size

# Why data Structures ?

JSON contain limitation to overcome NetScape introduced DS.

# WeakMap()

- weak map allows JSON objects as keys only.

# Set()

    - Set won't allow the duplicate values.

      add(): used to add the data to the set.

      clear(): delete the complete data from the set.

      constructor() : used to create the object to the set.

      delete(): inorder to delete particular element.

      entries(),for(), forEach(), for...of(): used to iterate the Set

      has(): used to check whether the value present or not.

      Values(): to get all the values from the set.

      size property: used to know the size of the set.

How to know the API? using dir()

Adv of converting object to array? User manipulations.

# for...of loop

- only for data structures they introduced for...of

# for...in loop

- used for JSON objects

# WeakSet()

- weakset can't accept primitives.

- allows only object
