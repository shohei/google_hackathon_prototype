#Arduino-MIDI projects for Google Hackathon

- Prototyping codes of Arduino-MIDI application

## realtime_midi_parser
- Get the MIDI signal from MIDI keyboard and extract the "note"(not completed)
- using 0x55(fixed velocity) or 0x90(note ON) as the marker

## writeread_midi_progmem_to_eeprom
- Store the MIDI data in the PROGMEM in the form of HEX array(sounddata.h)
- Write that data into EEPROM
- Read that data from EEPROM 
- Required to improve because EEPROM can store only 1k byte

## MIDI_recorder
- Real time MIDI recorder by combining the above two codes(not completed)

## play_withorwithoutyou_midi
- Extra project
- Play baseline of ["With or without you"](http://www.youtube.com/watch?v=XmSdTa9kaiQ) by U2
