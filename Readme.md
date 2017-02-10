# LMOD and LAMPS

LMOD is a database provided by the USDA which has been embedded in the web service LAMPS.

Use the follwing request to access the API:
``` bash
curl -X POST -H "Accept:application/json" "http://csip.engr.colostate.edu:8087/csip-lamps/m/lamps/1.0"
-F param=@c:/Users/nstoddar/Dev/LMOD/req.json
-F file1=@c:/Users/nstoddar/Dev/LMOD/IowaCounties.kmz>LAMPS_output.txt
```
Note: You will want to be in a Linux shell for this. :smile:
