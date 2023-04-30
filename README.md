Chatbot for Health Emergencies

This is a chatbot that uses OpenAI's GPT-3.5 language model to provide first aid solutions for health emergencies. The bot is integrated with Telegram, so you can interact with it through a Telegram bot.

Requirements

Go v1.16 or later
A Telegram bot token
An OpenAI API key
Installation
Clone the repository to your local machine.
Install the required dependencies by running go mod download.
Copy the config.example.json file to config.json and update it with your Telegram bot token and OpenAI API key.
Run the program with go run main.go.

Usage

You can interact with the bot through the Telegram app by adding the bot to a group or sending it direct messages. You can also access the bot's web interface by visiting http://localhost:8080/.

To ask the bot for first aid solutions for a health emergency, send a message that includes the symptoms you are experiencing. The bot will use the OpenAI API to generate a response that includes a list of first aid actions in order.

Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

License






Getting BPM using Pulse Sensor Library
This is a simple Arduino sketch that reads a Pulse Sensor signal and calculates the user's BPM (beats per minute) using the Pulse Sensor Playground library. The BPM value is displayed in the Arduino Serial Monitor and the built-in LED is also blinked according to the heartbeat.

Installation

To use this sketch, you need to install the Pulse Sensor Playground library in your Arduino IDE. You can follow the instructions provided in the Pulse Sensor Getting Started Guide.

Usage
Connect the Pulse Sensor to your Arduino board according to the instructions provided by the manufacturer. The PulseSensor PURPLE WIRE is connected to ANALOG PIN 0 in this code.

Upload the code to your Arduino board and open the Serial Monitor. You should see the BPM readings being printed in the Serial Monitor.

The Threshold value is set to 550 by default. You can fine-tune this value using the "Getting Started Project" or leave it as is.

Functionality
This code uses the PulseSensorPlayground library to create an instance of the Pulse Sensor object called pulseSensor. The pulseSensor object is then configured in the setup() function to assign the PulseSensor PURPLE WIRE to ANALOG PIN 0 and set the threshold value.

In the loop() function, the code constantly tests whether a beat has happened using the pulseSensor.sawStartOfBeat() function. If a beat is detected, the BPM value is calculated using the pulseSensor.getBeatsPerMinute() function and printed in the Serial Monitor.

Additionally, the built-in LED is blinked with each heartbeat using the pulseSensor.blinkOnPulse(LED) function.

License
This code is provided under the MIT License.
MIT




Saviour - Critical Care
This is the source code for the Saviour - Critical Care website. It uses HTML and CSS, and the Flowbite CSS framework.

Getting Started
To run the website locally, you can simply open the index.html file in your web browser. Alternatively, you can serve the website using a web server of your choice.

Usage
This website is designed for a fictional medical company called Saviour - Critical Care. It includes a navigation bar, a logo, and some sample content. You can customize the website by editing the HTML and CSS files.

Credits
This website was created by [Your Name], based on the Flowbite CSS framework.

License
This project is licensed under the MIT License - see the LICENSE file for details.
