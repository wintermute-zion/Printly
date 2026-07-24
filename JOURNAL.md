# Journal

## July 23, 9:43 PM: ESP32 and printer serial time!

Just spending some tim figuring out the wiring to get an ESP32 hooked up to a receipt printer. For this, I'll be using a TTL serial receipt printer since it is SO much easier to wire up (no voltage steppers, no long pinouts, etc.). After some work, I got this:
| ESP32 | TTL Serial |
| ---------------- | ---------- |
| GND | GND |
| GPIO17 UART2 TXD | TXD |
| GPIO16 UART2 RXD | RXD |

A lot of work for not much, you might be thinking. But at least this tells me where to start making the PCB from here forward.
![A picture of many tables and graphs, all of which are pinouts for various serial formats](assets/journal/journal_jul23.png)

_Time spent: 2 hours_
