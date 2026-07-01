Hardware Connections

    Green LED (for correct password):
        Connect the positive (anode) lead to a digital pin (let's use pin 10).
        Connect the negative (cathode) lead to a resistor (220Ω) and then to ground.

    Red LED (for incorrect password):
        Connect the positive (anode) lead to another digital pin (let's use pin 11).
        Connect the negative (cathode) lead to a resistor (220Ω) and then to ground.
How It Works:

    When the correct password ("1234") is entered and # is pressed:
        The green LED turns on.
        The red LED turns off.

    If an incorrect password is entered:
        The red LED turns on.
        The green LED turns off.

    Pressing * clears the input and turns off both LEDs.
