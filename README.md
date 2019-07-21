FlightGear ICAO.groundnet.xml Files

FlightGear ICAO.groundnet.xml files initially based on X-Plane Scenery Gateway airport .dat file taxi routes and parking positions. If no airport taxi route and/or all airport parking positions did not exist in the X-Plane Scenery Gateway airport .dat file, the file was edited in World Editor (WED) to include a taxi route and all parking positions. After this, M-Herweg's conversion scripts aptdat2sqlite.py and sqlite2xml.py were used to obtain draft groundnets. These groundnets were modified using TaxiDraw until acceptable behavior in FlightGear was achieved. In addition, parking positions (ramp starts in X-Plane) were added as necessary and/or positions were modified to include airline gate assignments using actual data available at the time of modification on websites such as Flightview.com and FlightAware.com. 

FlightGear ICAO.rwyuse.xml and ICAO.jetways.xml Files

FlightGear ICAO.rwyuse.xml files were created for airports where appropriate and necessary.
FlightGear ICAO.jetways.xml files were created for airport terminal buildings. These may be used as replacements for ICAO.jetways.xml files that don't match well with terminal buildings or with planes at parking positions in the created groundnet files.

FlightGear ICAO.twr.xml and ICAO.threshold.xml files were created to replace the default FG files, if the default files were found to be in error or, in the case of the threshold files, missing a threshold at the airport. 

FlightGear Airport.dat Files

Airport.dat files are also included. These files are mostly modifications of X-Plane Scenery Gateway airport.dat files, made using the WED editor. Modifications include the addition of a taxi route if one was not present in the original X-Plane file, parking positions (ramp starts), deletion of certain X-Plane objects, facades, etc. not used by FlightGear, and changes to the position of certain entities if they did not align when viewed in WED with Wed-O-Maker's (Bing) background for that airport. X-Plane Draped Polygons were converted to taxiways or lines if appropriate. Other surfaces were added as taxiways including parking lots, gravel or dirt covered areas, airport area roads, among others.

File Structure

The file structure is intended to be copied at its root and placed on a local hard drive "as is". Add a reference to the folder within the  Flightgear AddOns, Additional Scenery Folders.
