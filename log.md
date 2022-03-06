# 100 Days Of Code - Log

### Day 0: January 4, 2022 

**Today's Progress**: Checked out some API's where I could get course data from UTM without having to implement my own using a web scraper

**Thoughts:** Looks like VIAplanners API is upto date and is the most verbose option I've seen so far. However, it looks like the API key is only available to primary developers. I also came across an outdated but more open API called Nickel. I'm not sure if Nickel still works but it looks like its available to use currently. It was last updated last year.

**Link(s) to work**
1. [VIAplanner Course API](https://docs.viaplanner.ca/course-api/)
2. [Nickel API](https://docs.nikel.ml/docs)


### Day 1: March 5, 2022

**Today's Progress**: Tried to identify the issue on why I can't access the **grassdata\nc_spm_08_grass7\PERMANENT\windows** folder from withing the simple
python code editor in GRASS GIS. Found out how to list all the accessible rasters from a certain mapset in GRASS.

**Thoughts**: After listing all the accessible rasters from within the PERMANENT mapset using the command ```r_dict = gs.parse_command("g.list", type="rast", mapset="PERMANENT")``` I found that the list of accessible rasters in the PERMANENT mapset were in *grassdata\nc_spm_08_grass7\PERMANENT\cats* while the rural_1m is in *grassdata\nc_spm_08_grass7\PERMANENT\windows*. Have posted a reply on the GIS stack post and am waiting on Damians reply from teams aswell.


**Link(s) to work**
1. [GIS Stack Exchange Post](https://gis.stackexchange.com/questions/425385/cant-access-rasters-from-permanent-mapset-from-python)

