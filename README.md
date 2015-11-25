# JavaScript_for_RePhone

## Get started
Follow [the JavaScript for RePhone wiki](http://www.seeedstudio.com/wiki/JavaScript_for_RePhone) to get started.


## API
+ audio
    - audio.play('music.mp3')
    - audio.pause()
    - audio.resume()
    - audio.stop()
    - audio.set_volome(n), n from 1 to 6
    - audio.get_volome()
    
+ gsm
    - gsm.call(phone_number)
    - gsm.hang()
    - gsm.accept()
    - gsm.on_incoming_call(function (phone_number) { print('incoming call from', phone_number); })
    - gsm.text(phone_number, message)
    - gsm.on_new_message(function (phone_number, message) { print('got a message'); })
    
+ gpio
    - gpio.mode(pin, mode)
    - gpio.read(pin)
    - gpio.write(pin, value)
    
