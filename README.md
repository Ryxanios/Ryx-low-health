Applies realistic injury effects when player health drops below 50%. Character movement changes to an injured/stumbling walk animation, making it harder to move quickly when badly hurt. Effects automatically clear when health is restored above the threshold.Customizable Options:

Health threshold: Change the percentage at which effects trigger (default: 50%)
Animation style: Swap move_m@injured for different injury animations like move_m@drunk@verydrunk or move_m@hurry_butch@a
Update frequency: Adjust Citizen.Wait(100) to check health more or less frequently (lower = more responsive, higher = better performance)
