setup()
======

What it does: The setup function is called when sketch is started. It will run at least once after each **powerup** or **reset** of a Arduino board.

``` arduino
void setup()
{
    Serial.begin(9600);
    pinMode(ButtonPin, INPUT);
}

void loop()
{
    // Insert code here...
}
```
