# ATC FAQs


- 

<a name="atc"></a>
- <b>Which clients can I use to connect once <i>Audio for VATSIM</i> is launched?</b>
    - All currently supported clients are available but must be used with the <i>Audio for VATSIM</i> Standalone Client. <i>Soon™</i> ATC clients will be updated to use AFV without the extra client.
- <b>Do I need to update my sector files for <i>Audio for VATSIM</i> to work?</b>
    - No
- <b>The RDF-Plugin for <i>Euroscope</i> is no longer working, what should I do?</b>
    - The RDF-Plugin Uses data from a source that no longer exists.
- <b>Do I need to bandbox multiple DEL/GND/TWR/APP frequencies?</b>
    - Your Facility Engineer (FE) will know more, but there should be no need to transmit any differently than you did pre-AFV.
- <b>Are there any changes to the Ground to Ground (G2G) Communications?</b>
    - Unfortunately, Ground to Ground communications via the radar clients will not work at all upon launch. However a more reliable and easier to use Ground to Ground communication protocol will work when the controller clients are fully integrated with <i>Audio for VATSIM</i>. You will need to use <i>Teamspeak</i> or another voice communication method in the interim.
- <b>I’ve logged in as GND/TWR/APP but aircraft sound really crackly/I can’t hear aircraft on the ground/on the ILS even though they should be well within range</b>
    - The default visibility centre in your sector file may be somewhere other than your airport. Try forcing the radar visibility centre to your airport in order to update your transceiver location.
- <b>My transceiver doesn’t cover the entire airspace I’m controlling, what should I do?</b>
    - Contact your local Facility Engineer (if you are a Facility Engineer who needs help, please reach out to the team leader).
- <b>How do I set my transceiver locations?</b>
    - This will depend on whether your local ARTCC/vACC has a Facility Engineer who has configured your airspace.
        - If the position you are logging on to has been pre-configured, your transceivers will be automatically downloaded from the AFV facility database and you will not be able to edit these. This is to ensure consistent results for pilots and minimise the likelihood of frequency clashes with adjacent facilities.
        - If the position you are logging in to has not been pre-configured, your transceivers will automatically follow your controller client visibility points. You can add up to four additional ‘main’ transceivers by adding additional radar visibility points, and you can add smaller ‘top down’ transceivers for airports outside of the coverage of your main transceivers using the <i>Audio for VATSIM</i> ATC client.
- <b>What is the range of my radio transceivers?</b>
    - This will depend on the height of your transceiver, the height of the receiving aircraft and to a lesser extent whether your sector has been pre-configured by your local Facility Engineer or you are using controller client visibility centres. If you are using controller client visibility centres, your own transceiver height is set based on the type of facility you are connecting as.
        - All ‘top down’ transceivers added through the ATC client have the same specifications as DEL, GND and TWR transceivers.
        - The circles displayed on the AFV ATC client represent the range of each transceiver at sea level.

    | Position      | Max range at sea level (nm) | Max range at FL350 (nm) |
    | :             |   :                         |  :                      |
    | DEL, GND, TWR | 7                           | 236                     |
    | APP           | 12                          | 242                     |
    | CTR           | 42                          | 272                     |
    | FSS           | 48                          | 278                     |