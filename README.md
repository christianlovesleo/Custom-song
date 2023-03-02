# Custom-song
x=1
k=2
live_loop :hi do
  3.times do
    sample :guit_e_fifths
    sleep k
  end
  stop
end
sleep 5
live_loop :lo do
  3.times do
    sample :guit_e_fifths
    sleep x
  end
  stop
end
8
live_loop :ho do
  6.times do
    sample :bd_pure, amp:3
    sleep x
  end
  stop
end
sleep 6
define :sharp do
  play :as4
  sleep x
end
passion_fruit ="C:/Users/Christian Huitron/Documents/Audacity/tomp3.cc - Drake  Passionfruit.wav"
sample passion_fruit
sleep 23
use_bpm 120
use_synth :piano
live_loop :foo do
  4.times do
    play :e2, sustain: 0.25
    sleep 1.5
    play :b2, sustain: 0.25
    sleep 1.5
    play :cs3, sustain: 0.25
    sleep x
  end
  stop
end
live_loop :try do
  4.times do
    play :cs, sustain: 0.25
    sleep 1.5
    play :b2, sustain: 0.25
    sleep 1.5
    play :cs3, sustain: 0.25
    sleep x
  end
  stop
end
play :fs5
sleep x
play :cs5
sleep 2
sleep x
sleep 2
play :b4
sleep 2
play :fs5
sleep x
play :as4
sleep 2
sleep x
sleep x
sleep x
sharp
sharp
sharp
sharp
sharp
sharp
sharp
sharp
sharp
sharp
