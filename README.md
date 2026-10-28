# IoT Workshop Kits

Sketches, wiring notes and handouts for the hands-on IoT workshops that [eARgle Innovation Labs](https://earglelabs.com) runs in schools and colleges.

Everything here is open under the MIT licence. Teachers and workshop leads are welcome to run these sessions themselves.

## What a workshop looks like

A session is built around one board and a small set of sensors, so students wire something up, flash it, and watch it work inside a single sitting. Each workshop folder is self-contained: the sketch, the wiring diagram, the bill of materials, and a printable handout.

## Folder structure

| Path | Contents |
| --- | --- |
| `workshops/<name>/sketch/` | The Arduino or ESP32 sketch, commented for beginners |
| `workshops/<name>/wiring/` | Wiring diagram and a pin-by-pin connection table |
| `workshops/<name>/handout/` | One-page printable handout given to students |
| `workshops/<name>/BOM.md` | Components and quantities for a class of thirty |
| `common/` | Setup guides, driver notes and troubleshooting shared across workshops |

## Boards we use

ESP32 and ESP8266 for anything that needs Wi-Fi, and the Arduino Uno for first sessions where the focus is wiring and logic rather than connectivity.

## Before the session

Flash one board yourself and run the sketch end to end. Check that the school's Wi-Fi allows the devices to reach the internet, or fall back to a phone hotspot. Print the handouts. Bring spare jumper wires, because they are what fails.

## Booking a workshop

To have eARgle run a workshop at your school or college, write to info@eargle.tech or use the contact form at [eargle.tech](https://eargle.tech).

## Contributing

If you run one of these sessions and find a step that trips students up, open an issue or a pull request. Corrections from the classroom are the most useful kind.

## Licence

MIT.
