# Lab 04 - Garage Band with OOP

## Project Name - Pythonic Garage Band

### Author - Gordon P Reilley Jr

### Feature Tasks and Requirements:

- Use Python classes to model a `Band` made up of different kinds of musicians.

- Start with `Guitarist`,`Bassist`, and `Drummer`.

- Make use of a `Musician` base class to handle common functionality which particular kinds of musicians will inherit.

### User Acceptance Tests

Unit tests will be supplied for this lab. Your job is to make them pass. Do NOT modify the supplied tests (except to enable for stretch goals.)

**Band Tests**
- A `Band` instance should have a `name` attribute which is a string.
- A `Band` instance should have a `members` attribute which is a list of instances that inherit from `Musician` base (or super) class.
- A `Band` instance should have a `play_solos` method that asks each member musician to play a solo, in the order they were added to band.
- A `Band` instance should have appropriate `__str__` and `__repr__` methods.

**Musician Subclass Tests**
- Each kind of `Musician` instance should have appropriate `__str__` and `__repr__` methods.
- Each kind of `Musician` instance should have a `get_instrument` method that returns string.
- Each kind of `Musician` instance should have a `play_solo` method that returns string.