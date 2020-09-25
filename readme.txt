VORABVERSION für den #MSHACK2020 - Münsterhack 2020

The data you are looking at contains information on how many available parking spaces for bikes available in the vicinity of the Münster (Westf.) Hauptbahnhof / main station and on the actual counts counted on local surveys.
In its current state, it only contains actual counts, however we want to enrich it using publicly sourced data.
Over the course of various weeks we regulary made photographs of the relevant parking spaces and prepared them so they can be used to gain more info on the usage of bikes near the main station.
You can contribute to this data set (and download the results) on https://bikes.informationsfabrik.de .
The final goal is to produce a resilient dataset which can be used to answer various questions, e.g.
- How many bikes are parked around the main station?
- How does this change among different week days or time of days?
- How many bikes are never being moved?

The original dataset has been produced as part of the Zukunftsbahnhöfe summer test 2020, see https://gobeta.de/ms .

Please see the accompanying license file or https://creativecommons.org/licenses/by/4.0/ to learn about what you are allowed to do with this data.

Notes on the data:
- bike_parkings_spaces_hbf.csv
	- contains the parking areas which were examined in this test.
	- for the bike capacity estimations for open areas we assumed a space requirement of 1.5m^2 per bike. This includes the area that the parked bike needs plus space for ways and maneuvering. This is assumed to be the absolute minimum.
	- sources: http://www.politykaparkingowa.pl/assets/Uploads/Raport-II-Zaacznik-nr-2-Typy-i-planowanie-parkingow.pdf, https://www.adfc-bayern.de/fileadmin/user_upload/images/01_Menue_links/Service_Dienstleistungen/Abstellanlagen/ADFC_BY_Hinweise_Planung_Abstellanlagen_2018_12_web.pdf
- bike_counts_hbf.csv
	- contains counts of parked bikes on certain date and positions
	- source: survey means that the actual bikes were counted manually
	- The counts for double stacked bike racks usually only contain the number of bikes which were actually parked in the racks. When includesAdditionals is 1, then the count includes additional bikes which were parked right next to the racks.
