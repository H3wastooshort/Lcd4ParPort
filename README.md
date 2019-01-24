# Lcd4ParPort

Uses the "Standard/Default" Wireing of lcd4linux

Display HD44780-winamp {
    Driver 'HD44780'
    Model 'generic'
    UseBusy 1
    Port '/dev/parports/0'
    Size '20x4'
    Wire {
        RW        'AUTOFD'
        RS        'INIT'
        ENABLE    'STROBE'
        ENABLE2   'GND'
        BACKLIGHT 'GND'
        GPO       'GND'
        POWER     'GND'
    }
}
