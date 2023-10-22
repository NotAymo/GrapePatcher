# Inkay - Aroma patches for Grape

Inkay is an Aroma/WUPS plugin that patches various Nintendo Network URLs on a Wii U to use Pretendo Network instead. It also (for the time being) bypasses SSL verification in most cases.

Inkay does not currently include the game-specific patches present in [Nimble](https://github.com/PretendoNetwork/Nimble). These will be implemented soon™.

# Note from Aymo

This is best not using it, since its beta software and could brick your Wii U
its made for https://grape.helioho.st/ but the original Inkay is at https://github.com/PretendoNetwork/Inkay

## Dependencies
Inkay is only supported on the release version of Aroma configured for autoboot/coldboot. For Tiramisu, see [Nimble](https://github.com/PretendoNetwork/Nimble).

## Safety
Inkay's patches are all temporary, and only applied in-memory without modifying your console. The SSL patch, while also temporary, could reduce the overall security of your console while active - this is because it no longer checks if a server is verified. However, this does not apply to the Internet Browser, where SSL still works as expected.

## TODO
See [Issues](https://github.com/PretendoNetwork/Inkay/issues).
