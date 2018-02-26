# GPIO Piezo Buzzer

Play buzzer sounds using a GPIO piezo on the Raspberry Pi.

## References

<https://pypi.python.org/pypi/RPi.GPIO>

## Requirements
        python-rpi.gpio

## Usage
        $ gpio-piezo-buzzer [-h] -g GPIO [-s '[[PITCH, DURATION, DELAY], ...]']

## Example
To play three notes of increasing pitch (500,1000,1500) and duration (1,2,3) with a 0.5 second pause between each note, using GPIO pin 18.

        $ gpio-piezo-buzzer -g 18 -s '[[500, 1, 0.5], [1000, 2, 0.5], [1500, 3, 0]]'