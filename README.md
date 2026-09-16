# IIS
ATLS
Lab 1: Capacitive sensing

Capacitive Simon Says is a memory game that replaces physical buttons with bare wire touch pads powered by capacitive touch. There are five pads and five matching LEDs. When it powers on, the board spends a couple seconds calibrating, measuring how each pad reads when nothing is touching it so it can tell later when something is. Once that's done, it waits for you to send any character in the Serial Monitor before the game actually starts. From there, it plays a short sequence of LED flashes, and you repeat it back by touching the pads in the same order. Get it right, and the sequence grows by one and plays again. Get it wrong, or take too long on a step, and the game ends and tells you how far you got. Send the letter 'r' anytime to start over. 

AI use: I used AI to help debug my code, understand the calibration process, and learn how to use C++ functions like RandomSeed.
