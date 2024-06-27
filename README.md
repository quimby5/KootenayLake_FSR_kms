
A Geographic dataset of forestry road mile markers in the Kootenay Lake region.

# BACKGROUND:
British Columbia has many miles of Forest Service Roads (FSRs), now more recently known as Resource Roads (RRs). These are typically unpaved, often rough, sometimes unmaintained. They provide access to crown land resources such as forestry blocks, or backcountry recreation areas.  More information about these roads can be found here: https://www2.gov.bc.ca/gov/content/industry/natural-resource-use/resource-roads

One important aspect of travelling these roads safely is the mile markers which are posted for the purpose of identifying where you are, and broadcasting your progress up or down the road on the local radio channel.   These are typically signs with a yellow background, and black text. They may be as detailed as "BOBTAIL 13km UP" ... or simply be a single number.  Either way, these indicate kilometers of travel from the 0 km mark. More background on signage standards can be found here: https://www2.gov.bc.ca/gov/content/industry/natural-resource-use/resource-roads/engineering-standards-guidelines/forest-service-road-signs

Note: All distances are in kilometers. "Mile marker" is sometimes used interchangeably as a generic term because we Canadians are sloppy with our adherence to the Metric system.   Also, in OpenStreetMap these features are mapped with the "highway=milestone" key, even though the distance key is in kilometers. Go figure.


# ABOUT THIS DATASET:

A point dataset which can be imported into any GPS software or hardware to show kilometer markers on the map. 

Each point is a sign found in the field, and recorded where the ACTUAL SIGN IS FOUND, with typical GPS accuracy. We cannot just interpolate intervals along the road centreline because a) not every km has a sign posted  and b) the actual location of the sign doesn't always match the centerline interval for many various reasons.

The GPX and KML files in this repo are extracts from the main repository which is the OpenStreetMap database.  This means
 - If you would like to contribute to this dataset, simply sign up as a user and contribute to the OpenStreetMap project. (But get in touch with me so we can coordinate! See below)
 - The data contained in the files of this repo are published under the same license and attribution requirements as the OpenStreetMap project. See https://www.openstreetmap.org/copyright

I am using an overpass query to extract the features with tag highway=milestone, within a bbox that encloses most of the Kootenay Lake FSRs. This is a rectangle and by no means precise, at this point.


# PROGRESS AND COMPLETENESS
This is a work in progress.  I am typically trying to travel one named FSR and collect all km markers at once, for that road.  This would include all spurs for that named FSR. 

Completed roads:
- Woodbury Mainline (Spring 2024)
- Fletcher (Spring 2024)
- Cody-Cedar (Spring 2024)
- Lendrum Creek (Spring 2024)
- Krao Creek (Spring 2024)

I am focused mainly on FSRs in the Kootenay Lake area because that is where I work, travel, and recreate. Contact me if there is interest to expand this or include other geographic areas.
