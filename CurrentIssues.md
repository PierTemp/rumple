# rumple
Arduino Nano to Sparkfun LTE Shield for Temp Sensing

The temp sense file needs to be made so that it pushes a proper temperature and date reading to hologram. Right now it sends jibberish. 

When I send "read_digital" through hologram to the LTE boar I need the board to respond with the temperature, date, and time every 30 minutes on infinate loop to hologram to be parsed into thingspeak, google sheets, etc. 
