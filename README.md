LEDSaid uses the asign library (https://github.com/Krussell/asign) to send packets to Alpha LED Signs.

## Simple Hello World Example
	ledsaid -t "{SOT}{STX}{WriteText}{A}{Flash}{Red}Hello {Green}World{ETX}{EOT}"

## Demo Packet
This packet displays most features of the alpha sign protocol:
https://github.com/Krussell/ledsaid/blob/master/demo/demo.txt