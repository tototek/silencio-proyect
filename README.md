# silencio-proyect
Proyect for the TensorFlow Microcontroller Challenge

Onomatopoeias are words that represent noises or sounds, and Interjections are words or expressions that, when pronounced in an exclamatory tone, express a mood or capture a person's attention.Onomatopoeias can be used as interjections.

In our case we will use Shhh! ;Shhh! which is always used to ask for silence, at least in the Spanish language (Warning: it can change for other languages).

So why not ask for silence Shhhh ! Shhhhhh! to our Nano 33 BLE trained with TinyML ?.

The nano 33 will understand the order and send a command to silence the alarm of our mobile.

The model in the nano 33 was trained, with ambient noise, the noise of the alarm itself and the Shhh! and differentiates it with great accuracy.

The project was successfully implemented in Edge Impulse.


Warning :The part of sending commands using the nano 33 as HID is still to be implemented.
