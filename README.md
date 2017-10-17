# Mercury boot controller

This simple HTTP service will be stood up parallel to the mercury backend/DHCP services and provide boot services to clients. It will be integrated with the mercury inventory and provide the following functionality:

Standard boot process
Boot local scripts
CRUD for managing custom boot scripts
file IO interface for managing default PXE boot scripts and ipxe binary images

