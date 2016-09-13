# BlinkingNerves

Demo project with Raspberry Pi, blinking LED lights using Elixir and Nerves.

If you need to change the target device simple do so in the mix.exs and change "rpi" to one 
of the known target systems. run `mix deps.get`

## Available Target Devices
- Raspberry Pi A+, B, B+ and Zero nerves_system_rpi rpi
- Raspberry Pi 2  nerves_system_rpi2  rpi2
- Raspberry Pi 3  nerves_system_rpi3  rpi3
- BeagleBone Black  nerves_system_bbb bbb
- Alix  nerves_system_alix  alix
- AG150 nerves_system_ag150 ag150
- Intel Galileo 2 nerves_system_galileo galileo
- Lego EV3  nerves_system_ev3 ev3
- QEmu Arm  nerves_system_qemu_arm  qemu_arm


## To start your Nerves app:

  * Install dependencies with `mix deps.get`
  * Create firmware with `mix firmware`
  * Burn to an SD card with `mix firmware.burn`

## Learn more

  * Official docs: https://hexdocs.pm/nerves/getting-started.html
  * Official website: http://www.nerves-project.org/
  * Discussion Slack elixir-lang #nerves ([Invite](https://elixir-slackin.herokuapp.com/))
  * Source: https://github.com/nerves-project/nerves
