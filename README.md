# hardware-state-synchronisation
The essentials of shopping-app, shopping-pi-door and shopping-counting for our smart shelf project.
In a nutshell, we leverage MeteorJS to synchronise the central databank state between different clients such as the user and the Raspberry Pi that is controlling the electric door lock through a relay. If the database state changes then the Pi modifies its GPIO pins accordingly. At the same time the PI streams a video feed to the PC which also modifies the database which in turn updates the app of the user.
