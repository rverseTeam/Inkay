# Inkay-rverse - Aroma patches for Rverse

[![Pretendo network logo](https://github.com/PretendoNetwork/website/raw/master/public/assets/images/opengraph/opengraph-image.png)](https://pretendo.network)

Inkay-rverse is an Aroma/WUPS plugin that patches various Nintendo Network URLs on a Wii U to use rverse instead. It also (for the time being) bypasses SSL verification in most cases.

## Dependencies
Inkay-rverse is only supported on the release version of Aroma configured for autoboot/coldboot. For Tiramisu, see [Nimble](https://github.com/PretendoNetwork/Nimble).

## Safety
Inkay-rverse's patches are all temporary, and only applied in-memory without modifying your console. The SSL patch, while also temporary, could reduce the overall security of your console while active - this is because it no longer checks if a server is verified. However, this does not apply to the Internet Browser, where SSL still works as expected.
