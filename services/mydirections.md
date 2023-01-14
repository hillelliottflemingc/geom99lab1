# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://YourDirectionsApiURLGoesHere

Parameters added:
avoid= tolls|ferries
mode= bicycle
departure_time=now
waypoints= Ottawa and Oshawa
Ottawa place id: ChIJrxNRX7IFzkwR7RXdMeFRaoo
Oshawa place id: ChIJM3XTzCEd1YkRv_xE-PLvjN0


Final URL:
https://maps.googleapis.com/maps/api/directions/json?origin=Montreal&destination=Toronto&avoid=tolls|ferries&mode=bicycling&departure_time=now&waypoint_place_ids=true&waypoints=place_id:ChIJrxNRX7IFzkwR7RXdMeFRaoo%7Cplace_id:ChIJM3XTzCEd1YkRv_xE-PLvjN0&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE

```

## Next paste the full JSON response to this query here:

{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJDbdkHFQayUwR7-8fITgxTmU",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJrxNRX7IFzkwR7RXdMeFRaoo",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJM3XTzCEd1YkRv_xE-PLvjN0",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJpTvG15DL1IkRd8S0KlBVNTI",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 45.5442086,
               "lng" : -73.560059
            },
            "southwest" : {
               "lat" : 43.6532565,
               "lng" : -79.38303979999999
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "191 km",
                  "value" : 190863
               },
               "duration" : {
                  "text" : "9 hours 57 mins",
                  "value" : 35830
               },
               "end_address" : "Ottawa, ON, Canada",
               "end_location" : {
                  "lat" : 45.4213651,
                  "lng" : -75.6970503
               },
               "start_address" : "Montreal, QC, Canada",
               "start_location" : {
                  "lat" : 45.5018696,
                  "lng" : -73.5674191
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 763
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 261
                     },
                     "end_location" : {
                        "lat" : 45.497355,
                        "lng" : -73.5601502
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e on \u003cb\u003eBlvd Robert-Bourassa\u003c/b\u003e toward \u003cb\u003eBoulevard René-Lévesque O\u003c/b\u003e",
                     "polyline" : {
                        "points" : "uavtGjs_`MJOV]Vk@fA_CLYRi@f@sAXu@Na@Xq@JUJUPYNUp@iAhAiB`@q@nAuB|@yApAkAVSJMRYr@iBnAmD"
                     },
                     "start_location" : {
                        "lat" : 45.5018696,
                        "lng" : -73.5674191
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 108
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 45.4965753,
                        "lng" : -73.5609855
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRue Saint-Paul O\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oeutG|e~_MRRHJRRHHn@r@n@t@"
                     },
                     "start_location" : {
                        "lat" : 45.497355,
                        "lng" : -73.5601502
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "86 m",
                        "value" : 86
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 45.4961573,
                        "lng" : -73.560059
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRue de l'Inspecteur\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "s`utGdk~_MrAyD"
                     },
                     "start_location" : {
                        "lat" : 45.4965753,
                        "lng" : -73.5609855
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1176
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 266
                     },
                     "end_location" : {
                        "lat" : 45.4869506,
                        "lng" : -73.56737459999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRue William\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_~ttGje~_Mt@t@X^X\\NPJLRRLHJF`BbAz@h@j@`@hAn@PLDDJHpBpATNtC`B~Av@xFhDrD`C~@l@NFJLnDlDzAvAx@x@vBpB"
                     },
                     "start_location" : {
                        "lat" : 45.4961573,
                        "lng" : -73.560059
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 209
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 50
                     },
                     "end_location" : {
                        "lat" : 45.4854286,
                        "lng" : -73.56629749999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRue des Seigneurs\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mdstG`s_`Mt@qBFMJOHIXWBC\\WVOFAB?D?F@LDDD@?JFD@D@F?JA@AB?PCJCFC"
                     },
                     "start_location" : {
                        "lat" : 45.4869506,
                        "lng" : -73.56737459999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7 m",
                        "value" : 7
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 45.485386,
                        "lng" : -73.5663563
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at \u003cb\u003ePont des Seigneurs\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}zrtGjl_`MFJ"
                     },
                     "start_location" : {
                        "lat" : 45.4854286,
                        "lng" : -73.56629749999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 101
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 45.4846744,
                        "lng" : -73.5664233
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uzrtGvl_`MBGDGf@m@BE@??A@?@?@@F@HBF@@@@@@@BDDHDJJRBB@BDBHD"
                     },
                     "start_location" : {
                        "lat" : 45.485386,
                        "lng" : -73.5663563
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 625
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 109
                     },
                     "end_location" : {
                        "lat" : 45.4805066,
                        "lng" : -73.57175149999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "evrtGbm_`MFDDDHHDDBDJNFLHLNVJRh@z@LXBHDJz@tANPb@j@b@j@JNHHX^LNVZRRJJJHJHNRRXVj@JNHNBDDH~@jAJLRXf@v@PRZ`@HHn@t@h@h@BFDJ"
                     },
                     "start_location" : {
                        "lat" : 45.4846744,
                        "lng" : -73.5664233
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "90 m",
                        "value" : 90
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 45.4801693,
                        "lng" : -73.57268449999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "e|qtGln``M?\\Cl@BP@D@DBBDHLPJNZ^"
                     },
                     "start_location" : {
                        "lat" : 45.4805066,
                        "lng" : -73.57175149999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 176
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 45.47887,
                        "lng" : -73.5736993
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "azqtGft``MHHFFFFB@D@D?F?PEXGF?D?B@B@BBDBVb@l@~@NPPTTXFH"
                     },
                     "start_location" : {
                        "lat" : 45.4801693,
                        "lng" : -73.57268449999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 km",
                        "value" : 2401
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 423
                     },
                     "end_location" : {
                        "lat" : 45.4647703,
                        "lng" : -73.5954184
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "}qqtGrz``MLNZ^Z^Z\\?@DFLNBDNPb@n@RTV\\@?DF`@TNFNFFBDBDDFF~@fBL`@FLHNPVFHJNT\\@BBHH^DJ?@@@d@h@RPj@d@@@B@H@@@B?J?@?@?@@B?BBb@b@d@`@b@b@zAtAB@XZj@j@rAlAnBfBbB|Aj@h@^XJHFBD@D@RBNBPHRNDBHJJJDFHHRRNNNLXVLJ`A~@f@f@`@^RTf@l@FHNLJLJFDB@BBDBHP`@l@nANZb@v@`@v@@@LTFLNXLXHRBDHPN`@v@zBlAtDDJ@D@F?D@F?F@D?JAHE`@?@?B?@?B?B@DBF@F@D@B@@BFLTNXJRBBZp@R^Td@HPLZHVL`@FXFVBN@@F\\@LBLDRJr@@LFj@@B\\rCJ~@NlAD\\VpB?BLn@Fb@Lb@HRPf@?@Th@Rj@FNXz@Pp@H\\FR?@Rh@@@@@R`@Vd@X^@@NTFN"
                     },
                     "start_location" : {
                        "lat" : 45.47887,
                        "lng" : -73.5736993
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "71 m",
                        "value" : 71
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 45.4652415,
                        "lng" : -73.59603799999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yyntGjbe`MCDo@~@i@t@"
                     },
                     "start_location" : {
                        "lat" : 45.4647703,
                        "lng" : -73.5954184
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 382
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 77
                     },
                     "end_location" : {
                        "lat" : 45.4630447,
                        "lng" : -73.5997955
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w|ntGffe`MBFBFNZBHDJ@@BDv@rAXd@NTHLVd@`@r@|@`BVf@JRHRTf@LXl@vABHLZTt@BD"
                     },
                     "start_location" : {
                        "lat" : 45.4652415,
                        "lng" : -73.59603799999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4.4 km",
                        "value" : 4411
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 789
                     },
                     "end_location" : {
                        "lat" : 45.4412573,
                        "lng" : -73.64606259999999
                     },
                     "html_instructions" : "Continue straight",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "_ontGv}e`Mf@~AX~@ZdALd@JZDPH\\FLFRN`@\\`Ap@tBn@lB@Bd@|ALb@Nl@Lj@DZBL@^BPBLHVr@vBDN`@fBb@lBTdAPr@Fl@Fb@BPDRFZ\\zANn@Jh@Rv@\\zANv@\\hBj@zCF`@Nj@Xr@DJHTNb@J\\ZlAFXDZDTDPVz@j@~ATr@H\\ZxAVdAFRFRHV^fAJVNVR`@Xt@BFJ^Hf@DTPr@BHFLJJDDFLFPBFDPBD\\`@DFJPRZ?@HPN`@FRNl@BDV|@HR^hATp@@DZx@d@fAr@bBPb@l@lA\\r@^l@d@v@Zf@j@bAR\\@@j@|@p@hADHBF`@l@x@bA\\f@^p@PX@@f@z@n@lAd@z@Xh@b@n@vAfB`AhAh@`@HHnA~@b@^FHTVf@j@TZDDPPd@\\t@r@LNn@z@\\j@|@zAf@|@j@pAr@lBp@nB`@hAp@tB^vA\\fAh@tBj@jBp@nBLl@Ll@Vz@Nn@J\\`@xAd@nBVz@Nt@L^@Dn@|BRl@p@xBjB`Gh@dBTt@BJTv@`@rAPn@Rl@Z~@VdAp@bDF@BDBDrAlE"
                     },
                     "start_location" : {
                        "lat" : 45.4630447,
                        "lng" : -73.5997955
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "53 m",
                        "value" : 53
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 45.4408304,
                        "lng" : -73.64575429999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{fjtGz~n`M~@m@TO"
                     },
                     "start_location" : {
                        "lat" : 45.4412573,
                        "lng" : -73.64606259999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 1991
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 440
                     },
                     "end_location" : {
                        "lat" : 45.4310026,
                        "lng" : -73.66605250000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "edjtG||n`ME[AG@C?E@ABAB?@@@B?B?BAJ?B?@@BBL@B@B@@DRHT@DDNDLL\\Rh@Rj@N^BHTf@j@pATf@Th@Rf@Tf@P`@BFTf@l@nATf@j@nATf@HNLXDJhAbCbAxBTf@dCnFvA`Df@tAn@hBJ\\BTRjA?@Lr@@DHb@@BJ`@BD@BLXP^HR@B@FHZ@H@PBR@FBJLb@Nf@h@xARf@?@f@tARj@Pf@@@Ph@@?Rj@FRFLDDFHDHBJ?F@J@PDJDHJFLDLHHHFJDLBPBLDJLJTVf@d@LNFHJd@\\dAPn@RpAHZr@tADJFTXjAh@hBHRPh@b@pA`@fA^hADL?D@L?N?L@@@FFNLPRTDP"
                     },
                     "start_location" : {
                        "lat" : 45.4408304,
                        "lng" : -73.64575429999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 477
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 75
                     },
                     "end_location" : {
                        "lat" : 45.4309746,
                        "lng" : -73.67070129999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eChem. du Musée\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wfhtGx{r`Mc@?S?K@K@G?G@GBUHGBEBKDGDGFSVADADE`@?D?F@HThABNBJFj@BNBXF`@Hn@@HD\\@FD\\D^Hz@@ZJvA@?TPFFFJFL@?@LBL@VBT@J@D@B@B@DBFHRDLBH?B?@?B?@?@CF"
                     },
                     "start_location" : {
                        "lat" : 45.4310026,
                        "lng" : -73.66605250000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "91 m",
                        "value" : 91
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 45.4311354,
                        "lng" : -73.67172550000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qfhtGzxs`ME@KJEDCBAFCJCJCJCJ?DAF@H@LBZB`@@X"
                     },
                     "start_location" : {
                        "lat" : 45.4309746,
                        "lng" : -73.67070129999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 233
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 45.4310368,
                        "lng" : -73.6746859
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "polyline" : {
                        "points" : "sghtGh_t`M?BAD?B?H?J@F?H?H@H?HALAN?HAHAN?PAV?T?\\?T?@@d@Bd@FbA?DBZ@X@LBL?F@J?R?N?b@"
                     },
                     "start_location" : {
                        "lat" : 45.4311354,
                        "lng" : -73.67172550000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "77 m",
                        "value" : 77
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 45.4311648,
                        "lng" : -73.6756285
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "_ghtGxqt`MBH@J@JANCJGRK~@C\\AJ"
                     },
                     "start_location" : {
                        "lat" : 45.4310368,
                        "lng" : -73.6746859
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 115
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 45.431384,
                        "lng" : -73.67706819999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "wghtGtwt`MALAHALEb@ABGj@?@APALCNA?G|@?@?DAXAR"
                     },
                     "start_location" : {
                        "lat" : 45.4311648,
                        "lng" : -73.6756285
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 281
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 45.4322255,
                        "lng" : -73.68041240000001
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "cihtGt`u`M?LAHADEXADER?HAPAXCJ?@CLK\\ADADAPE^CNERW`ACNCX?RENEPKf@Ib@Ih@ObAAJAD?@ABCBC?"
                     },
                     "start_location" : {
                        "lat" : 45.431384,
                        "lng" : -73.67706819999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "69 m",
                        "value" : 69
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 45.4323899,
                        "lng" : -73.6812623
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "mnhtGpuu`MKfAS`B"
                     },
                     "start_location" : {
                        "lat" : 45.4322255,
                        "lng" : -73.68041240000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "13 m",
                        "value" : 13
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 45.4324739,
                        "lng" : -73.68136800000001
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "mohtGzzu`MIHCBAB?B"
                     },
                     "start_location" : {
                        "lat" : 45.4323899,
                        "lng" : -73.6812623
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "26 m",
                        "value" : 26
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 45.4324595,
                        "lng" : -73.6816888
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}ohtGp{u`MAB@D@F@FBFALCN"
                     },
                     "start_location" : {
                        "lat" : 45.4324739,
                        "lng" : -73.68136800000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 118
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 45.4324349,
                        "lng" : -73.68318600000001
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "{ohtGp}u`MC^?R?l@?NAT?TA`@?J?H?F@F@HF`@?H@F?F"
                     },
                     "start_location" : {
                        "lat" : 45.4324595,
                        "lng" : -73.6816888
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "15 m",
                        "value" : 15
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 45.4325507,
                        "lng" : -73.68329490000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uohtG|fv`MEDC@MJ"
                     },
                     "start_location" : {
                        "lat" : 45.4324349,
                        "lng" : -73.68318600000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "21 m",
                        "value" : 21
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 45.4325065,
                        "lng" : -73.68355649999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eProm Père Marquette\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mphtGpgv`M@NBP@R"
                     },
                     "start_location" : {
                        "lat" : 45.4325507,
                        "lng" : -73.68329490000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "38 m",
                        "value" : 38
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 45.4327508,
                        "lng" : -73.6839042
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eBd Saint-Joseph\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ephtGfiv`MA@A@A@OXA@ILMR"
                     },
                     "start_location" : {
                        "lat" : 45.4325065,
                        "lng" : -73.68355649999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "40 m",
                        "value" : 40
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 45.433062,
                        "lng" : -73.6836555
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eBd Saint-Joseph\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uqhtGjkv`MQM?AGEGEEEEECAECAAC?"
                     },
                     "start_location" : {
                        "lat" : 45.4327508,
                        "lng" : -73.6839042
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "69 m",
                        "value" : 69
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 45.433597,
                        "lng" : -73.68397379999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eBd Saint-Joseph\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sshtGziv`MGHININGFA@C@G?a@CC?A@E@KF"
                     },
                     "start_location" : {
                        "lat" : 45.433062,
                        "lng" : -73.6836555
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 440
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 111
                     },
                     "end_location" : {
                        "lat" : 45.4336515,
                        "lng" : -73.68927459999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBd Saint-Joseph\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_whtGxkv`MIn@CTCLADMb@y@~BGRCLAJG^CZEXA`@A\\?T@^BXDh@N|AHx@LhA^nBJl@NdAD`@"
                     },
                     "start_location" : {
                        "lat" : 45.433597,
                        "lng" : -73.68397379999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1099
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 208
                     },
                     "end_location" : {
                        "lat" : 45.43499180000001,
                        "lng" : -73.70140789999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "iwhtG|lw`MR@DADEHWFOBEDCD?JDNJLPFD@@DH@FDV@P?j@I~DAz@@RBJHZBP@P@j@?@OhC?vA?l@@NCp@U`BAFGh@Kt@CZCROb@Ul@Wr@Qh@ET?PALCNEHMLOZWdAq@jCe@hBKZ?T?P?FANENGLWz@[|A_@pBCb@@l@D|@Hv@Hp@ANCd@Il@"
                     },
                     "start_location" : {
                        "lat" : 45.4336515,
                        "lng" : -73.68927459999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 571
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 100
                     },
                     "end_location" : {
                        "lat" : 45.4363757,
                        "lng" : -73.70822629999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "u_itGxxy`MAHIXIh@Ep@A\\Al@CRGRE\\Er@ApAAf@A^C~CCh@BZBVD^?ZI^[hAy@lC]|@YvA]tAGRADCLGLENILA@"
                     },
                     "start_location" : {
                        "lat" : 45.43499180000001,
                        "lng" : -73.70140789999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1059
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 184
                     },
                     "end_location" : {
                        "lat" : 45.43894179999999,
                        "lng" : -73.72003789999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "khitGlc{`MGf@AL?T@RJr@@LJbAHh@Db@Bx@AtAEtAIhA?^Eb@CRCLCJCF?F@H?H?F?FALCFADCHAHCZEd@Ej@AJETCNITQZSZWZ]ZUJ[T]LQNSZSZMVMLEDCDEFAHCHAJALALEh@ETCT?FCNIbAA\\?t@CfBChAANALCNENGLININILKNONCBEFCFAHCH?LAL?P?TBpCBn@?T@l@?H?HAJEFa@?"
                     },
                     "start_location" : {
                        "lat" : 45.4363757,
                        "lng" : -73.70822629999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "6.1 km",
                        "value" : 6116
                     },
                     "duration" : {
                        "text" : "18 mins",
                        "value" : 1095
                     },
                     "end_location" : {
                        "lat" : 45.448317,
                        "lng" : -73.791034
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLakeshore Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kxitGfm}`MCPALEPGRKRQZYd@KXi@hAu@~@STg@j@A@OTOVOVADOl@Oj@ENCNCNCL?BAJAVCX?HALAT?XAp@?NErCAbBAjE?X?@?fBCfCA`G?rB?H@r@@P@`@D|@Bl@Dr@JbBLbBB\\JbBJvBHlAHbA?JFn@Ft@Fh@D`@F`@Fb@@DDRHVTl@BJPj@HTHTTh@Xl@HPLVLPDHDFBHBFBFBHDPDNBPBRBL@NBX@d@@\\@j@?`@ArA?jB?x@AP?d@?P?N@L?L@F?DH`A?D@JBl@Fx@FvA@X@`A?JD`A@R?HALAnAAhA?PAv@C~@ALAJANYjBKd@YhAYrAKj@Kj@e@xDI`@Id@E\\Gj@E^Cb@?VAH?T?V@B@ZBp@RtCBZBZD`@PnAX`BJj@Nz@@F@JBR@JFj@Dp@Bj@Bd@?R?F?D?T?PAT?`@AX?n@EzD@R?d@B|@@NBXRzCBf@@H?J@V?XAZATAZAJCPCPEPEP?@ENGPENO^e@lA_@jAq@dCM\\ITSn@GLe@rAAFGNEPEPERCRETCRSvBEd@Ch@Ct@?\\?L?D@P@^@JBJ@JBLDLBLDNFRH`@BH@H@F@H@H@F@N?J@B@b@LpJB|A?L?JALALCLCLELENwBtGIj@ARAT?R?TBR?BHjAJdBDf@VtCFf@@T?TCRCRET?@s@fCm@xBEJ]fAMTKTMNMLOHOHOFQDgBXq@NGBEBGBEBEDEDEDEDEDMNuArBaD~E[r@KPc@x@eBrDINq@lAS^Uh@yBxFWt@Mf@Md@Ov@GZCXIp@IvAEd@CTEXi@nCa@bBENGPYr@GRI\\Kh@Q|@OdAYlBGZC\\AZ?V?D@NBRBHPp@DN@F@H?F@F?F?F?F?F?JATCP?DIv@StAWvBEj@CZCp@Ah@ARI~@?N?TBlA"
                     },
                     "start_location" : {
                        "lat" : 45.43894179999999,
                        "lng" : -73.72003789999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 373
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 80
                     },
                     "end_location" : {
                        "lat" : 45.4499626,
                        "lng" : -73.7916053
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAv. de la Baie de Valois\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_sktG|hkaMsAb@_@LBZBTFlAALAFWFKBKDMBCAAC?EEm@Eq@Cq@Es@C[EGG?A?aAVQFCBADBb@@J@TAD?@ABCBMFIB"
                     },
                     "start_location" : {
                        "lat" : 45.448317,
                        "lng" : -73.791034
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3219
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 594
                     },
                     "end_location" : {
                        "lat" : 45.4398331,
                        "lng" : -73.8301026
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAve Donegani\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "g}ktGplkaM?RPjCBd@Df@FhAJvAd@vFH~@HdALjAJ~@Jn@PhAn@fEh@dEl@`Er@bEt@tE|@nFDPBLhAhFJ`@b@nBBH@HxCtN?BDPZ|AxDxQ@FH^tAxG^dBXrA^pB@Fv@pEFTFZ?@f@fCFZXdBl@hDN`AZ|AF^\\pBn@lEt@pEP`AfBpJt@|DlA~Gd@pCXdBN|@NB@Bj@bDf@zCl@|C"
                     },
                     "start_location" : {
                        "lat" : 45.4499626,
                        "lng" : -73.7916053
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "48 m",
                        "value" : 48
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 45.4399205,
                        "lng" : -73.8305946
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}}itGb}raMUf@GNABAF?B@FLP"
                     },
                     "start_location" : {
                        "lat" : 45.4398331,
                        "lng" : -73.8301026
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 163
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 45.438545,
                        "lng" : -73.8298755
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "o~itGd`saM`@OBA@?HEXK^Q`@Q`@QTKJE`@OLEFEFE"
                     },
                     "start_location" : {
                        "lat" : 45.4399205,
                        "lng" : -73.8305946
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "41 m",
                        "value" : 41
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 45.4388432,
                        "lng" : -73.8297826
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}uitGv{raMCOEICEEAGAKBG@IH"
                     },
                     "start_location" : {
                        "lat" : 45.438545,
                        "lng" : -73.8298755
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 408
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 69
                     },
                     "end_location" : {
                        "lat" : 45.4375424,
                        "lng" : -73.83453759999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wwitGb{raM@FJp@DRPtAJn@PdAFZJn@Jn@^jCd@fCBLHh@N|@RnANv@@JBF@@@@B?DEBA"
                     },
                     "start_location" : {
                        "lat" : 45.4388432,
                        "lng" : -73.8297826
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 175
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 45.4360341,
                        "lng" : -73.8339081
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAv. de la Pointe-Claire\u003c/b\u003e",
                     "polyline" : {
                        "points" : "soitGzxsaMzBu@jBk@`@Mb@M"
                     },
                     "start_location" : {
                        "lat" : 45.4375424,
                        "lng" : -73.83453759999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "94 m",
                        "value" : 94
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 45.4356751,
                        "lng" : -73.83496579999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eAv. Willowbrook\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "efitG|tsaM@FBHBNBL@RBNBR@JBJBHT`@FJDJ?H?D"
                     },
                     "start_location" : {
                        "lat" : 45.4360341,
                        "lng" : -73.8339081
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 529
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 85
                     },
                     "end_location" : {
                        "lat" : 45.43247299999999,
                        "lng" : -73.8395163
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAv. Willowbrook\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_ditGp{saMJRDFBDjCzB^^dCbCHPLJrC|BPTPPRRBBBD@DBF?@@DBF@H@HF^BXJn@Dj@^`D"
                     },
                     "start_location" : {
                        "lat" : 45.4356751,
                        "lng" : -73.83496579999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 114
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 45.4314915,
                        "lng" : -73.8391049
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAll. Sweetbriar\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}ohtG~wtaMr@Wp@U|Ae@"
                     },
                     "start_location" : {
                        "lat" : 45.43247299999999,
                        "lng" : -73.8395163
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 168
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 45.43108669999999,
                        "lng" : -73.8411826
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eClaude St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yihtGjutaMFh@D\\Ht@Jx@Fl@Dp@H`@RdB"
                     },
                     "start_location" : {
                        "lat" : 45.4314915,
                        "lng" : -73.8391049
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4.9 km",
                        "value" : 4898
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 892
                     },
                     "end_location" : {
                        "lat" : 45.4140628,
                        "lng" : -73.8974259
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBd Beaconsfield\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ightGjbuaMCXCXAT?L?N?H?F?H@LFb@XxBX~BBRBR@R?P?L?LAH?JAFALALK`@[jAKd@EVCRAZ?N?PBh@Bf@BP@BFXJ`@XhABLTr@?@J\\DLZjATr@VdAf@pB^vAJ\\h@tBbAvDfApELp@TnARhADVDPDVFTf@zA|@rCpEfNP`@L`@J`@Nt@Jn@F^F`@XpBV~AXjBZ|B`@pC`@xC\\zBZxBTlALb@Lb@LZJVr@nA`@n@f@~@LTJPJTLRL\\\\bAPf@T|@Jf@RjA^|CFd@Fb@R`BD^PtAHn@ZvBXjC@HFd@DZFd@Jv@Jf@Hh@J`@Tp@Th@^z@Vf@n@xAf@fA`@`ALZRf@Ph@Vx@Pj@\\lAR~@Jd@VnAHd@Jh@Fb@Dh@Fl@Fx@FhADj@NdBl@lJXfEZxEF|@H`AHx@L~@PdAt@vEhBdLfA|Gp@pERlAP~@Lr@Lf@V~@nArETz@p@vBt@vAlAnB^b@~@fAd@h@|@fARVPVXd@P\\Xf@b@bAVl@"
                     },
                     "start_location" : {
                        "lat" : 45.43108669999999,
                        "lng" : -73.8411826
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4.0 km",
                        "value" : 4043
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 689
                     },
                     "end_location" : {
                        "lat" : 45.4027227,
                        "lng" : -73.94451520000001
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eChem. Lakeshore\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRue Lakeshore\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{|dtG|a`bMRt@DRHZP~@VtAXvAd@lCp@~DTxAb@nCLdAj@xEThCT`CNhBHz@Fb@Jl@^|AVnAh@tC@FV`BRhAXfAXhAPn@^zAL`@ZtAV`APl@`@rARh@\\x@Vx@HVDLDPR|@p@~CDPFNNf@Vv@Rh@L^j@`BNd@Rp@Lb@HRFP@BFTDP@DDPBLDNBTDTDd@?P?X?R?@A\\Ad@?R?T?P?V@T@N?L@J@PBH?BFXFXH^L`@P^LVNVZ`@\\Zv@d@d@R\\Pl@XVN@@RJ`@\\LJLN\\^V^T^J\\J\\J^FVF\\BPDZD\\@XB^@T@L?V@??P?L?J?VATA^ARCTEd@Gv@AZCXAf@?@AZAR?h@?V@N@fABl@DjAHdD?V?n@?b@Aj@AX?FCb@Gt@SpBCZAXCd@?X?R@VB`@Dh@@DDf@Fd@Lr@FZF^BRBV@DDr@BdABhA?vB@jB?nAAlA?n@?D@d@@~@BbB@l@@^@ZBRBVJ\\Z|@DLHVNb@Tx@@DLj@XfAv@jDRx@Nz@H`@Jd@BLPx@Lj@Lp@TlAHb@Fd@Bj@@R@d@Bt@B^BZDZHd@P`ALl@?DR`AFb@DX@HDVDX"
                     },
                     "start_location" : {
                        "lat" : 45.4140628,
                        "lng" : -73.8974259
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 924
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 190
                     },
                     "end_location" : {
                        "lat" : 45.4047281,
                        "lng" : -73.95571319999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRue Sainte-Anne\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_vbtGfhibM@\\Bd@Bl@?b@A`@?`@En@ClC?f@?n@?v@A|@AT?BCXCTEd@Gp@W`CK~@ADOdAAFMz@E`@EZa@vEU|AEZKZGN?BIPKVABYn@kAlCCHAFCJAJAPEVAPAXAR?BA^?XAN?RAT?HAZIl@ADAB?BABa@dA"
                     },
                     "start_location" : {
                        "lat" : 45.4027227,
                        "lng" : -73.94451520000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 880
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 204
                     },
                     "end_location" : {
                        "lat" : 45.3991838,
                        "lng" : -73.9588803
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qbctGdnkbMb@f@@CN_@Vu@@SDYBWDU?EDYBSBQDMDM?MAKCGAACAAAEAE?CBCBCDADAF?D?D@FBDBB@@@@DFRPBBJHLLB@XVBBPNFF^XBB\\ZXT^ZRPf@`@|@t@BBXTDBXT\\XHFTRBBf@b@VRLHHFZTBBBBXVBBXV@@@@XVBBl@j@HHBBXV\\ZFFXTHFNNBB^X?@\\VDBTPBBDDLJDB?@@?@?@?@?@??A@A?E?A?C?E?C?E?C"
                     },
                     "start_location" : {
                        "lat" : 45.4047281,
                        "lng" : -73.95571319999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "91 m",
                        "value" : 91
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 45.3985136,
                        "lng" : -73.9585445
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003e1ère Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{_btG~albM@HBFDDB@DBD?DADCBCDCd@g@l@k@"
                     },
                     "start_location" : {
                        "lat" : 45.3991838,
                        "lng" : -73.9588803
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "84 m",
                        "value" : 84
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 45.3979302,
                        "lng" : -73.959228
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e1ère Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "u{atGz_lbMV\\zAjB"
                     },
                     "start_location" : {
                        "lat" : 45.3985136,
                        "lng" : -73.9585445
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1749
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 459
                     },
                     "end_location" : {
                        "lat" : 45.3869827,
                        "lng" : -73.9705287
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGrand Boulevard\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "axatGddlbM`Au@|@q@j@_@~@m@lA}@`@YNMJGLILCJE@?H?|@B\\@r@HB?RB`ANVXXZt@~@pB|Bv@|@hGpH`AjAlAxA\\`@X^l@r@p@z@X\\PRZ`@x@bAb@h@HJf@j@Z^\\`@\\^FHV\\d@l@\\b@JNP`@Lf@@DP`AF\\Jr@DXVfBBNF^`@bCBVZ~BHj@Jv@\\zBLv@\\zB"
                     },
                     "start_location" : {
                        "lat" : 45.3979302,
                        "lng" : -73.959228
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2237
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 454
                     },
                     "end_location" : {
                        "lat" : 45.3806267,
                        "lng" : -73.99769429999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e5e Avenue\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ss_tGxjnbM`ArGJl@BX`@nCBJ@NJn@`AlG~Ej\\DRzCfSpApIx@lFv@jFbBtLJp@v@pFb@|CDXL|@DVN`AJv@Lx@@JN|@@LNdALx@RrAHf@XnBf@dDBNb@vC@N\\jDAR"
                     },
                     "start_location" : {
                        "lat" : 45.3869827,
                        "lng" : -73.9705287
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 665
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 137
                     },
                     "end_location" : {
                        "lat" : 45.3860561,
                        "lng" : -73.99802249999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eChem. Duhamel\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}k~sGptsbM?JAPEXIZK\\M\\QZSNMF[HI@O@G?I@K?gAGUE{C]YKWGa@MeAc@u@[MEeAa@GAkAQ]Cy@C[CSBKDg@Xa@PQJMBEBE?A?EAEC"
                     },
                     "start_location" : {
                        "lat" : 45.3806267,
                        "lng" : -73.99769429999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 632
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 124
                     },
                     "end_location" : {
                        "lat" : 45.3856595,
                        "lng" : -74.0060343
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{m_tGrvsbMMb@?DAJ@N@x@JpH@r@@FJtFBdBDbB@t@@r@FjE@r@?P@^@r@?DFbAJz@DXHb@"
                     },
                     "start_location" : {
                        "lat" : 45.3860561,
                        "lng" : -73.99802249999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "15 m",
                        "value" : 15
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 45.3857887,
                        "lng" : -74.006097
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAv. Sabourin\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kk_tGthubMYL"
                     },
                     "start_location" : {
                        "lat" : 45.3856595,
                        "lng" : -74.0060343
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 270
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 119
                     },
                     "end_location" : {
                        "lat" : 45.3844784,
                        "lng" : -74.00899459999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAutoroute du Souvenir\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eA 20\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "el_tGbiubMP|@`@|AfApCbAhCdAhC"
                     },
                     "start_location" : {
                        "lat" : 45.3857887,
                        "lng" : -74.006097
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 392
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 118
                     },
                     "end_location" : {
                        "lat" : 45.3873387,
                        "lng" : -74.0118133
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAv. Saint-Henri\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eQC-340 O\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_d_tGd{ubMQPgAlAIF{ApA]XiA|@EBIFCBURGDWP_@VKL]\\aAz@UTGFMPEDCDCNCX"
                     },
                     "start_location" : {
                        "lat" : 45.3844784,
                        "lng" : -74.00899459999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "83 m",
                        "value" : 83
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 45.3869155,
                        "lng" : -74.0126825
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRue Adèle\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "{u_tGxlvbM@H@DDJRf@t@hB"
                     },
                     "start_location" : {
                        "lat" : 45.3873387,
                        "lng" : -74.0118133
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1654
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 311
                     },
                     "end_location" : {
                        "lat" : 45.3982755,
                        "lng" : -74.0256954
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAv. Saint-Charles\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eQC-340 O\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gs_tGfrvbM{@|@uAxAkBpBa@^[Xy@v@QNONo@x@e@n@y@jAOTi@z@[f@[h@]j@Yd@kAlBMTg@x@Wb@s@dBg@zAa@hAm@zA_BdDeDzF_@n@CDEFk@~@wArBILIDC@STc@h@w@|@_@VOL_@VQJSJMFMBe@LaAVy@VUJMHgA`@eAb@}@d@]ViAv@"
                     },
                     "start_location" : {
                        "lat" : 45.3869155,
                        "lng" : -74.0126825
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 128
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 45.399079,
                        "lng" : -74.0245271
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRue Léger\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gzatGrcybM]m@aC{D"
                     },
                     "start_location" : {
                        "lat" : 45.3982755,
                        "lng" : -74.0256954
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 439
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 79
                     },
                     "end_location" : {
                        "lat" : 45.4020675,
                        "lng" : -74.02816369999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRue Louise-Josephte\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "g_btGh|xbMwArByAxByAvBsApBkA|Ae@j@OPGD_@XMJSNIFWVGD"
                     },
                     "start_location" : {
                        "lat" : 45.399079,
                        "lng" : -74.0245271
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 590
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 99
                     },
                     "end_location" : {
                        "lat" : 45.4063176,
                        "lng" : -74.0314307
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "}qbtG~rybMAFKRUNq@hAcBlAEDCF?LAPCHKJWTcA`A_@@IDG@G@GESI}@ACCA?CECEGSKQECCAG?E@KFMJE@MBMBk@r@sA`BkB~Bi@x@"
                     },
                     "start_location" : {
                        "lat" : 45.4020675,
                        "lng" : -74.02816369999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "46 m",
                        "value" : 46
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 45.4066554,
                        "lng" : -74.0317481
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e at \u003cb\u003eRue du Chevalier\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "olctGlgzbMCDIJMJKB[\\"
                     },
                     "start_location" : {
                        "lat" : 45.4063176,
                        "lng" : -74.0314307
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 127
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 45.4060308,
                        "lng" : -74.033103
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRue Dutrisac\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "snctGlizbMLVLZl@|A\\jAHRJZ"
                     },
                     "start_location" : {
                        "lat" : 45.4066554,
                        "lng" : -74.0317481
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 824
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 203
                     },
                     "end_location" : {
                        "lat" : 45.412111,
                        "lng" : -74.0391219
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAv. Saint-Charles\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ujctGzqzbM{@t@WVk@h@]Zg@d@EDw@t@}@z@aB|AWPeB`BGH{@x@{AxAoArAYZa@`@{@x@cBjBgBlBq@t@_@b@WP"
                     },
                     "start_location" : {
                        "lat" : 45.4060308,
                        "lng" : -74.033103
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "13 m",
                        "value" : 13
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 45.41205,
                        "lng" : -74.0392682
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eAv. Saint-Charles\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "updtGnw{bMJ\\"
                     },
                     "start_location" : {
                        "lat" : 45.412111,
                        "lng" : -74.0391219
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1010
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 190
                     },
                     "end_location" : {
                        "lat" : 45.4174914,
                        "lng" : -74.04827
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAv. Saint-Charles\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ipdtGlx{bM_Ax@_@^o@j@MJoA`A_BfBKJyArBoAvBUTKJWNEDw@n@mBtA{@r@QNu@v@o@h@UVs@lA]v@Yz@Op@Ib@G^Ih@Gd@Gr@Ep@Cp@?t@@L?`@Bf@Bb@Dd@D^BTDRDT"
                     },
                     "start_location" : {
                        "lat" : 45.41205,
                        "lng" : -74.0392682
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.7 km",
                        "value" : 3744
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 661
                     },
                     "end_location" : {
                        "lat" : 45.4408295,
                        "lng" : -74.07573940000002
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eChem. de l'Anse\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "iretGtp}bMe@ROHyAf@c@Pg@VIFIHGJELCNCPCXE`@Mt@Q`AeApESx@ADqB`GOl@Kp@UbAO`@_@bAsB~EMXw@xAqBzDq@nAo@bAuBlDGHs@dAY`@_@d@m@v@_@f@s@bA?@Yb@MPKPe@l@ORCBOLSJSJWH[HUJMFIFKHKJMLCDmA|Aa@`@u@v@A@]d@[b@c@p@_@d@[^w@r@}AvAy@r@g@d@k@l@i@j@WX}@`AUV_EnDSPEDo@h@kChBa@Vk@\\UXSP_@\\CBc@Xo@^w@`@w@^}@ZyAx@gBjAgBtAu@b@{@^u@\\[LODYBG?S?a@E{B[G?gACQ?iFBc@@gA@S@mB@u@Do@RUNSRQTMZK\\I\\CZA^Cj@D`BH|BPfGJdCDt@h@jD"
                     },
                     "start_location" : {
                        "lat" : 45.4174914,
                        "lng" : -74.04827
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "13.0 km",
                        "value" : 12958
                     },
                     "duration" : {
                        "text" : "39 mins",
                        "value" : 2327
                     },
                     "end_location" : {
                        "lat" : 45.4824997,
                        "lng" : -74.21605459999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRue Main\u003c/b\u003e",
                     "polyline" : {
                        "points" : "edjtGj|bcMHn@d@jCZfCpAzKFn@Br@C~BCz@KvCC`BMdDAvA@v@@PNjD@LHlBHfAJx@Hj@Nj@Rd@|@rBfBxDDPHR?BBR@R?TEZIb@GRa@xAMb@AHq@fCYjAc@lBKb@[hBAJQpAGv@Ep@Mp@S~@Mn@Kn@Kn@QfA[rB?DKpAKvBKbCCl@GjBO|FCzBCpDAxA?N@RT~C@l@?NATC\\EZEZq@nAy@pAU^MRINGJa@p@mArBGLc@bAQ`@_@^KJ_@^u@p@CBQLMDGB}@TIBk@Pk@Pc@Ne@La@PcA\\g@PQFq@\\]VSLm@p@UXe@n@q@d@q@f@eEzBMFo@h@g@b@}@r@o@f@wAn@u@RYLwAp@q@XQLGFGHGJA@m@tAc@pAQd@w@rBENSz@OrAGp@Ip@ATMlAC^M~AI|@Kz@ABU|AQf@Qh@Sj@e@tAEH_@lAeBpFWz@K\\u@bC[bAMh@E^Cj@?@?xA@dD?z@BpC?r@@p@@r@DdBRvBTfBDh@RzAFj@B`@B`@Bl@BbA@p@BdBBrA@vA@bAAb@AZ?P?NB^R|@l@nBJh@XvAJz@Dl@m@jCQt@[`Aa@tAk@lAABaAnByAnC[~@i@nAINQR]\\s@t@y@r@_@ZiBvBkCxD{BtDq@hAu@rAo@jAYj@Qb@ABKXK`@Kt@Gr@[hDGb@GXMn@_AbCe@|@q@bAk@`ASR{A~B}@|@uBtBwCzC[Z{@lAc@n@UZw@`Bg@tAOb@e@~AqAtDQj@a@vACFw@bC_AvCa@jAUv@GVo@jCa@zBSbAsAzGKf@_@~Bm@nDCPi@tCu@tDCJc@`CY~AI^S|@CLW|ASbBIp@Ef@AHEp@?FEz@GtA?@IbB?@Ct@Cl@?D?b@?F?\\@|@B|@?DBj@Bf@@JDn@@`@?R@T?ZAj@IfAEj@MdACTE\\CPAFIZEPKRO\\CF]n@MREFe@t@}@hA_@\\c@b@SXQTg@x@c@fAGZa@dC]~BSrBCb@KxA?JEdBExCCf@C|@ElAAVEp@ATG|@CNGp@CPc@|DEf@ObBGp@Mf@]~@MXGPYt@e@pAqApDQh@IRK^Kd@EV]rBg@rC[lB_@|AmBnH_@zAi@pBSfAOx@WrACRUzB?DQlE]xFAX_@rDi@~DUbBU|Aa@nC_@zBCT]|B]rBOz@c@lBENUr@Yt@IVSh@g@vAQh@CDGNAFCHGNGNO^Uf@KNUX[f@UXABUZa@d@EDuAhAc@\\ST]d@Y\\SZIHGJ[`@_@j@QVm@x@UZKNY\\o@n@u@t@QR_AjAgA|AW`@MT_@x@A@Qf@M\\Kb@EXCJy@hF]bCGd@ATAVAzD@~A?FBp@Db@Fd@VrBHj@TdBHp@Fp@PbB?dB?xC@dF"
                     },
                     "start_location" : {
                        "lat" : 45.4408295,
                        "lng" : -74.07573940000002
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3168
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 559
                     },
                     "end_location" : {
                        "lat" : 45.4806096,
                        "lng" : -74.2548477
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eChem. de l'Anse\u003c/b\u003e",
                     "polyline" : {
                        "points" : "shrtGhi~cMRlDFbAVjDDl@TrAbAhFLn@RbA\\fBJb@Nn@Nn@\\zALl@p@tCf@tCDPZ|Ah@jCb@rBTdADPjAfFj@jCj@jCZ|Ax@~DJ`BNbBTtB@^FzAJx@Fh@^|E?d@CdBA`BUzCa@zFK|AADU`BCLItAEp@Gp@Er@Er@s@tFo@`EM^yBlNADs@vDsAfHa@tDEv@Ez@A~KH|CDrCLjF?\\BjBJtD"
                     },
                     "start_location" : {
                        "lat" : 45.4824997,
                        "lng" : -74.21605459999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4.1 km",
                        "value" : 4082
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 750
                     },
                     "end_location" : {
                        "lat" : 45.4809778,
                        "lng" : -74.3062228
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eQC-342 O\u003c/b\u003e",
                     "polyline" : {
                        "points" : "y|qtGx{edM?f@@pC@`BBlEF~FDxG@|@@f@?RFdDBrB?XBnB@\\DnCDpE@XBnCBrCJ|I?VDdENjO@tCB`DFjHB|A@bB@r@@|@?Z@NNdPBvEB~DDX?|@@d@JvD@fB@|@BhC@h@@v@@j@BxA?bA@dA@bA@h@@|@@jA?P@z@H`GDxGF|G?l@?XHnHD~ID~ABbBDnEDfEJzIBrB@rB?P@V?N?`@Av@SdB]lCERU`BEVAFI`@GTGRQd@KXYn@KXS`@SZ[^]ZWRYRYP"
                     },
                     "start_location" : {
                        "lat" : 45.4806096,
                        "lng" : -74.2548477
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "11.0 km",
                        "value" : 10954
                     },
                     "duration" : {
                        "text" : "34 mins",
                        "value" : 2032
                     },
                     "end_location" : {
                        "lat" : 45.4981999,
                        "lng" : -74.4441552
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Ontario\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "c_rtGz|odM?h@FbDF|DVhQ@V@Z?TRlM@X?@NjM?VFvEBhD@VB`EArDIxEAT?`@a@jHk@xHUtC[~Dm@dHgAvOM|AKlAm@vHY|Dq@fJe@zFg@hGEp@Gn@YrDKfASdCm@|HGp@UzC{@hLIbAw@tKCZe@pGg@~EAXUtCk@pHeBzTCLqAjQAHwAtQcBdUeAjNiBrVIz@wBvWEd@y@xLYlDyAzPgCz\\{@nLk@lH[fE]`FeCd[Q~By@pKk@lHEp@UlCwBbZi@hH_AdMMbBi@bHIz@WxC_@fEGn@eAjNaAhMeA|NEh@}A|SyApQk@lHQzBe@tG_ArKEn@o@~I?@c@xFe@zFq@~IaAbM]hE"
                     },
                     "start_location" : {
                        "lat" : 45.4809778,
                        "lng" : -74.3062228
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "24.9 km",
                        "value" : 24934
                     },
                     "duration" : {
                        "text" : "1 hour 15 mins",
                        "value" : 4484
                     },
                     "end_location" : {
                        "lat" : 45.5417089,
                        "lng" : -74.7524552
                     },
                     "html_instructions" : "Continue onto \u003cb\u003ePrescott-Russell Recreational Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wjutG~zjeMw@jKYnDS|BYtC{AbPKjA_@lDk@vFy@bImDf]gAlK_AzIkAvLKr@?BiAlK}@zIiAlKu@hHa@vDUbB_AbHg@nCaApFqE`UsAzGiG`[uDdRy@|DaBhIyJzf@Mn@aC~LUfAsBxJsFjXmBlJgAjFw@|DaBhIgAjF[|Ai@lCEPG\\g@dCOt@[|AaBjImLzl@wChO}BhLCLgAtFsAzG{CfOmFbXeAjFeAjFi@lCw@zDqBxJw@|DkCvMeAjFyCfOeAlFgAjFMl@[~AAHI\\Kv@G^g@`Da@pCKn@m@`E]`DQbBIp@kAjKIp@SfBYnCaAxIGp@m@vFK|@gA~JkEba@m@vFQ|A}BvSaCtT_DjY_AxIeGlj@o@vFm@vF}AnNAPy@xIE`@]hEIhAGlAIvAQxEKpCEnBEbCCjDAbB@vH@fFBdFBtD@nD@lE@~DH`QFlNFnC@t@@p@FlBl@~JJzAx@pKp@~INxBD\\^fFp@zHTxCXpD^~EDp@n@jIj@hHBXZfEJnALtAPvBJrAV~Ct@~I@Pf@lGd@fGHbA^hEJbBTlDXpFJnCDp@H~ANnFBzB@`AL|DDrAHhDFfBBxBLjFJjE@r@@^N`HFhCH`DP~HFbCFnCDnBHxCJlF?PPxGD~B@p@BlAFdFB~A?dH?RG~GGlDCdBIjEKpDGlAOxCMnCYnE?BEf@W|C?B[bE?DEZWfD?D[bE?DAF]lFAFCd@?BAH[~D?HEf@AHSlCKpAg@bIAHKvAAJWjDC\\YfDUrCEt@Ip@CTK|AIpAGz@Ef@A\\El@Ix@MjBALGz@SdCADEx@KxAGt@?Dc@tFEr@UvDKbAIbAG|@OlBG`AOtBIrA[~DSnCAJOzBGfAMhAMhBCXEt@KrAOpB?DQdC]lEItAQbC[~DO|BGbAQzB_@nFCd@OlBa@vFc@~F]|Ey@bLGr@StCYjDAVCb@KhAOfBKpAc@hHGhAa@zEO`COvBM|AWdDi@bI?Di@fHCV]|EQnCs@rJKxAM|AQfCKvAQdCM~AO|BKhAQnC]tEADSbCIzAKrAEr@KnAGr@EZE`@Gd@"
                     },
                     "start_location" : {
                        "lat" : 45.4981999,
                        "lng" : -74.4441552
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 244
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 69
                     },
                     "end_location" : {
                        "lat" : 45.5417058,
                        "lng" : -74.7555881
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eCounty Rd 20\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRegional Rd 20\u003c/b\u003e",
                     "polyline" : {
                        "points" : "uz}tGzaggM?z@?`G?rH"
                     },
                     "start_location" : {
                        "lat" : 45.5417089,
                        "lng" : -74.7524552
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "44 m",
                        "value" : 44
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 45.54208089999999,
                        "lng" : -74.7554071
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003ePrescott-Russell Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uz}tGluggMiAc@"
                     },
                     "start_location" : {
                        "lat" : 45.5417058,
                        "lng" : -74.7555881
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7.5 km",
                        "value" : 7549
                     },
                     "duration" : {
                        "text" : "23 mins",
                        "value" : 1356
                     },
                     "end_location" : {
                        "lat" : 45.5407492,
                        "lng" : -74.8516612
                     },
                     "html_instructions" : "Continue onto \u003cb\u003ePrescott-Russell Recreational Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_}}tGhtggMShC[fEYlDO~B[hEEp@Q`CIfAW`DKxAGp@c@dGUdDIjAUjDWzCIjAEp@]fF]|EGp@C^k@`IEj@a@`GKxAc@dHW~EGzAKbDErAIjDAj@C~CCnACbF?R?^@lFH`IH|EDxABp@N~F?HBh@HdDN|FNrFRpH?@H`DPfGJnH@d@PpHBr@T`IFvAFbBBr@Bp@@j@Dx@@b@FxC?BBl@FdB@XF~BHxCHtD@TBr@RvH\\`NNbFHlCHbDRfJBp@Bp@@r@@l@JjB@r@DbB?@Br@@p@Br@PlHFfB@t@LxEDrA?DZlLFzBR~G?Jf@bRH|DNbGRjHJbDRbHJvCZrMDzAXtKDjA\\nL?`@ZbLPrHD`BVjKPzFJdC@`@?VEb@"
                     },
                     "start_location" : {
                        "lat" : 45.54208089999999,
                        "lng" : -74.7554071
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "22 m",
                        "value" : 22
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 45.54067209999999,
                        "lng" : -74.8519175
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eConcession Rd 8\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "ut}tGzmzgMNr@"
                     },
                     "start_location" : {
                        "lat" : 45.5407492,
                        "lng" : -74.8516612
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "33.8 km",
                        "value" : 33751
                     },
                     "duration" : {
                        "text" : "1 hour 42 mins",
                        "value" : 6105
                     },
                     "end_location" : {
                        "lat" : 45.4356268,
                        "lng" : -75.2367058
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePrescott-Russell Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "et}tGnozgMCN?H@l@JdEFzAVtJF~BJrELlEBp@LpEJrCJpCTfE`@xG^tEh@`GZ|CHr@p@rF`@rCXlB|@zFnAdHBPpAjGDLvAhGvAnFRx@rArE?@xBxGpBpGTx@tAnEz@pCd@xAbBlFpBlGFRbBtFfBlFBFbBtEjAxDHX~AdFdD`Lh@pBfAhDt@`C^fAX`Ap@xBbAfDjApDBFnA~DX~@j@lBbBtF|@tCxChJDLzA|Et@~B|CpJdDvK|@vCn@rBpA~DrAdEjChIjBfGV|@bA|ChAjD|A~En@rBVz@fAlDRn@\\fAlAzEd@vBp@bDRfAj@fDNdATbBVpCXdCXdEN|BFnANnDFtD@TBvDIpH?l@I~CG`B[xFYdEUlEO~CIxA]dGa@~F]zGCRWzDY~EG~AOfDa@tFS~DC^GdAUzD?N]nGC^UjEEz@U~DCp@]hFIdBQ~CQnCEp@?@MhBUbE?@Ep@KjBa@lIMrB[|F?@YjEUzFCj@?BElCC`AC`A@lB?X?rCJhF@Z?BRfE?@@HBh@VbEd@pEZjC?BHl@?@@Fh@~DHn@Hn@Ff@VbBHn@Jp@Jp@RvAHn@R`BT`B\\rC@Dz@bHHh@F^Jb@J^VdAJh@XhBh@lDN~@DXPnBFj@Hn@F`@Lj@VlAfAbFlAlFbA|DRt@pAfEj@`B~@nCfC|GjChGpDpHh@`AzBdEPZv@pAzA~B`@j@hCxDzCnE^j@tAnBjBlCjDdF~@tAfA`Bh@|@PVr@bAv@fA~@vAh@|@~AxBvBzCxAxBr@fAfBhCv@hAjAbBlAfBbClDPVvApBpAjBj@z@fAfBlC~DfBdCd@p@tB~C|AzB~@rArC~Dd@p@r@dAnBtCxBdD~@tA|A|BlBrCrEvGfEfG|@pARZj@v@bB`CLRJNVb@hBjCbA`BjBbC`AnA`A~At@lAfBfCtApBbBdC`AtAnC~DRZx@lAdAzAT`@RXX`@fD~E\\h@tAnBh@~@^h@fCpDjIxLbCjD?@hBjCzCpEx@lA|BfDvLdQt@hAb@l@by@jlAT^hD~EbA~A`@l@`AbB@@l@jAp@pARd@JRl@tA^z@Zr@n@bBj@~A^jA^hAl@rBZhA\\lAp@zCt@zDLp@h@lDN~@BLHx@`@dCPvAD`@f@dDb@~CD\\Z~BHf@\\bCTxAHp@b@nCN`AD^NbAvCvSbBtLzChTbAbHxBxOzIdn@T`B`@pCHh@Hp@^pCPhABVlCnRLx@x@rF`A|G?DbAbH`@pCv@rFTbBvAbKxCjTPhAZvB~B`P\\fCzBxOT~A`AbH|@hGxBvOvG`e@tEz[Hp@Jr@t@nFRzARxAHn@Fb@VnBNlABRNbBf@nFHz@LbBRdCf@xIV`HBf@PxG?VN`GPvHB~AHzCDtCB~@LpF@n@BzABdBFbCFzBNnGFhCRjI@f@FxC?DFvC@RBpABbA@~@Bl@@j@A^AXCPAFARCT?T@z@@N@NHZDLDNBJ@J@R?NHbDFzCBnAFrDHfEBt@LjE?FD|AJ|DBlB@j@DdB@f@J`EJpEJjGPxHD`BFvCPpHFzCJxFDjBBp@JpEB`B@p@?LPnGHlDHdDD|BFjDDrA@r@DtAFfDBr@NnH@@NhHJtEDzBPnIBp@HzDHxCDdB@t@D`BBr@RhJFrCDzBL|FLjFNfGJnEBdBHlEDjBD~ALjFR~I@VRrGJ`CJpBVxDF|A`@bGHjBVbET`E\\dGVfEDh@^dGZbGb@vH"
                     },
                     "start_location" : {
                        "lat" : 45.54067209999999,
                        "lng" : -74.8519175
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "26.0 km",
                        "value" : 26046
                     },
                     "duration" : {
                        "text" : "1 hour 21 mins",
                        "value" : 4850
                     },
                     "end_location" : {
                        "lat" : 45.4170462,
                        "lng" : -75.56606499999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003ePrescott-Russell Trail Link\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ucitGltejMZfFRjDDp@VjEJzAPzCVzDN|BPnD?@f@vJb@jIFx@X`ERzCTdEDp@PdDVzDJdB?BPrCDp@Dp@PvCJdBHbBBf@r@|K?@LlBBh@Dn@Dr@NtC?@PtCBh@?H@?NtCDr@Dp@Dr@PtC?@Dr@PrC?@L`B?@Bd@F|@Dr@VfE?@J`B?BJ`B?@J`B@B@TRnD?BVdE?BJ`B?@FbAHrADn@h@fIDv@Dj@RjEZzFB`@TfDDb@VvEVhEl@hK@JV`DDtAJrBTxDFbAVhEb@zG@PHdBTtDDp@LdBDp@Dp@@DBj@PjEJdB\\zFVhENjC@Jb@nHVhEBp@b@fHPtCJdBDp@XhE@Lf@`JNhCV~D`@dHd@bIPtCRdDZlFJhB\\pFTnEHrAd@`Ib@jHXzEVdEHxANbCRvD@HVvDHjBDh@VrEDp@NfCPdDLdBLhBRxCLhCVhEJjBHfBRrCDn@\\bE?FHbBJdBBp@PvCBr@JnBV~DD|@ThEDp@FnALxBJdBFp@Dp@@Xh@fI@Xh@~HR|CNlCJnB^|G^lGHtAF`Ad@fIHjABp@VjERzD@LP`DPlC\\bFFhARbELjBj@pJJrA^~FNrCPvCP|CTbETnDFjA^|FFz@Bf@NdC@l@@V\\hFNpCLhBDr@VbEDv@n@fKPbDVnEb@hH?Fb@jHf@zIDp@NzBRhDFlAd@bHPlDNfCBd@HzAHjAF`ATxDBh@^dGHdATjDPtCB^XrFHxAZbFL|BXlE\\vFLvB\\`GHjABV\\rG@B\\vEDjA@HBf@D~@ZpFTtCB`@NtBDp@LtBHrAX|F\\pGHnAJbBJdBJbBFbAB`@Fp@PvCDp@JbBR`DDf@JjBJvBNdEBdAD~@Bj@FhB@x@DbBBtB?`@BjB@nC?rC?bB@tCEjEK~EAb@MpFIrBCp@E|@YlGUzESpEEn@OzCEn@OtDWrF[vGQ`EG|AEfAADEx@AVATC^CRGbAMdCYhGGdBI|AE|@Cd@Ed@GzAGpAA`@AFCh@Cf@AREz@KfCe@tJ[zGIfBI`B?HKnBS~DCh@I~AGpAKvBItBEp@A`@GbAMpCEr@IpBMpCIxAGbBIrAGrAEx@GnAI~AIjBEr@Cp@GnAC\\Cx@G|@IfBEz@?VALAHEL?^?N?RCTC^ARCb@EjAG`AIrBIpBUrEMhCEt@Cr@GjAU`FG~@UpFKlBKlBW~FOjDGvAY`GUbFEl@UdFGpAMdCMlCEx@EfAGtAYlFKxBCh@Ct@]nHI~AOhDE`AKlBQlDWrFGzAGtAEp@EtAShEg@rKShEg@~JUxFYjGOvCe@~JUlE_@pHWtFK|BWnG[dG_@lI_AfS[fJGrBGjBKbKAlK@dEHnFFfDNpFL`CLhD?@@HP|CVzDTvCb@jF@HDn@`@dFZdDFt@NfBLzA`@hEBP\\nDPnCFv@NbBNbBBb@LjBHpAJzA`@dEBd@F|@LxAn@tHXdDb@`Fd@bGJtAVfC^dFVxCn@tHJtAFz@^rD\\lEd@vF\\rD@Xd@bGd@~FTfCXfDb@lFd@rFN|AZlEHfAJvAVlD"
                     },
                     "start_location" : {
                        "lat" : 45.4356268,
                        "lng" : -75.2367058
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 316
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 83
                     },
                     "end_location" : {
                        "lat" : 45.4197014,
                        "lng" : -75.567452
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAnderson Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 27 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qoetGz~elMGDsBdAWLyEfCMHQFQFE@]DE?I@QBk@J"
                     },
                     "start_location" : {
                        "lat" : 45.4170462,
                        "lng" : -75.56606499999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1619
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 313
                     },
                     "end_location" : {
                        "lat" : 45.4230302,
                        "lng" : -75.5864874
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003eAnderson Rd\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "c`ftGpgflMA??AA?AA?AC?AAA?CAA?A?C?A?A@A?C@A@A@A@A@A@ABA@A@?@AB?@?@AB?B?@?B?B?B?B?B@B?@@B?B@@@B@@@@@@@@?@@?@@@??@@HDP@RA\\C\\A\\CZE`@EZIh@Gd@Gb@C^EXAZ[tCIn@?@OnAa@|DEZMxAOfBKjACTAVAX?ZA\\?^?R?B@jBBvHBrEBzE?hAD~I?z@?B?l@AVARE^ANAJEVEXIXKZYx@GPq@dB}AzDe@jASb@]x@Yp@Ub@QZELMRMRQNUT"
                     },
                     "start_location" : {
                        "lat" : 45.4197014,
                        "lng" : -75.567452
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1400
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 295
                     },
                     "end_location" : {
                        "lat" : 45.4167681,
                        "lng" : -75.6020156
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eInnes Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 27 N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 30\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Innes Rd/\u003cwbr/\u003eOttawa Regional Rd 30\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}tftGp~ilMfApDPj@@Fx@hCJ^b@xAPr@Lb@FRf@tBh@bC@FNn@Lj@TfAFVRv@Pr@XbA@D\\lAL^\\fARl@JXJXFLFPj@vAXl@z@zBJZJXHXFNHPH\\ZfABHTv@`@rANh@Vx@p@~BL\\Nh@~@`D`AzCHZHXZbAL^LVTp@Rl@Tr@"
                     },
                     "start_location" : {
                        "lat" : 45.4230302,
                        "lng" : -75.5864874
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.8 km",
                        "value" : 2801
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 498
                     },
                     "end_location" : {
                        "lat" : 45.424763,
                        "lng" : -75.635547
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCyrville Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 128\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ymetGr_mlMFn@@RANAJKXEHGJEFCDGLITGRCVCTAT?R@JBVHd@Nt@Ft@@\\?NALE^O`Ag@nDIf@ETQhAKn@c@nCg@`DUpAg@bDMx@Kn@EXAHCPC^C`@Cb@?@Ad@A\\?`@A|@Aj@A\\AP?J?BA\\Gj@CVG`@CL?BAJAHEVEVEP?DA@?BMf@A@Ux@KVq@fBMXQd@KVIPIREPENGRKb@Kh@G\\Op@EZADQ`AQhACJUzAe@hCa@`COj@GZO~@_@hCId@CN{@rEEPYzAG`@I`@CJAFYxAKn@]dBUpA?@CJADAFIb@CPEXADMp@_@|BU|AAHId@CRI`@QlAOz@[pBG^Id@o@|DG^G^E^EXCTER[`CABIn@e@zDKz@EPCNIv@Il@?HEPWhBOz@S`AIh@IXMf@Y~@K`@"
                     },
                     "start_location" : {
                        "lat" : 45.4167681,
                        "lng" : -75.6020156
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1183
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 324
                     },
                     "end_location" : {
                        "lat" : 45.4215814,
                        "lng" : -75.6474269
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOgilvie Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 50\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Ottawa Regional Rd 50\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w_gtGdqslMPr@HX@BRfA?BLn@F^?DD^F~@Dj@BXDx@Bd@Bx@@n@DpB?r@AdDBlB?d@?pADnC@J@HBFDNDFBDDDDBDBD@B?D@H?DAF?\\E`AKFAlAIJ@F@F?jAKJCDADAHAD@D@B@BBDDBDBHDH@D@H?LDlABfA@D@FDRBr@Bx@LvEDpABRBzAAd@?N?D?NDjB@V@l@"
                     },
                     "start_location" : {
                        "lat" : 45.424763,
                        "lng" : -75.635547
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 325
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 106
                     },
                     "end_location" : {
                        "lat" : 45.4186723,
                        "lng" : -75.64701409999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBelfast Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{kftGl{ulMRCf@Gt@IRCp@E`@AZCrBOfAIFAlAIj@CPC"
                     },
                     "start_location" : {
                        "lat" : 45.4215814,
                        "lng" : -75.6474269
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 395
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 59
                     },
                     "end_location" : {
                        "lat" : 45.4184029,
                        "lng" : -75.65202789999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTremblay Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uyetGxxulMDh@BP@N?TBx@Bl@?ZDfAB^B~AENCp@Ab@?DDpC?Z?F@h@@F?L?H@FD`AF`A@p@BR"
                     },
                     "start_location" : {
                        "lat" : 45.4186723,
                        "lng" : -75.64701409999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "87 m",
                        "value" : 87
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 45.4177756,
                        "lng" : -75.65238119999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_xetGdxvlMV?b@CNAH?DBDBFDBPBLFX@B"
                     },
                     "start_location" : {
                        "lat" : 45.4184029,
                        "lng" : -75.65202789999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "11 m",
                        "value" : 11
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 45.41786,
                        "lng" : -75.65244539999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ctetGjzvlMOL"
                     },
                     "start_location" : {
                        "lat" : 45.4177756,
                        "lng" : -75.65238119999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 290
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 45.4162395,
                        "lng" : -75.65532039999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "stetGxzvlMDJTl@FNFPHXFNNd@N^Pd@JZFPDLDFHLFLFLFNN^V`@f@p@z@nABD@B"
                     },
                     "start_location" : {
                        "lat" : 45.41786,
                        "lng" : -75.65244539999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 605
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 116
                     },
                     "end_location" : {
                        "lat" : 45.416205,
                        "lng" : -75.6614318
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ojetGvlwlMNGDA@??@B@LT@@HPBDFLHLLXJXJXDRBRBVBVB~@?@@T@N?D?B@`@?Z?^?@?`@?N?@?^?f@@d@@d@?RAJAHCH?@@F?F@d@@N@R?JJj@Fb@HXDJHPBHZp@@F?D@F?F?DAHCPGRELSXMH[NYNg@X]PEAC@G@G@GBGD"
                     },
                     "start_location" : {
                        "lat" : 45.4162395,
                        "lng" : -75.65532039999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 224
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 38
                     },
                     "end_location" : {
                        "lat" : 45.4165039,
                        "lng" : -75.6642701
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRideau River Pedestrian/\u003cwbr/\u003eCycling Bridge\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gjetG|rxlMCZEz@Cp@ARC\\Cr@En@?@Ep@Er@ARC\\E^?HAFCh@?`@"
                     },
                     "start_location" : {
                        "lat" : 45.416205,
                        "lng" : -75.6614318
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 457
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 91
                     },
                     "end_location" : {
                        "lat" : 45.41490719999999,
                        "lng" : -75.66880019999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cletGtdylM`@?F?DCDC@?BAHCHAJ?F@LFDFf@v@FJDJDJBHDRBJ@JBN@P?R?B?~@@j@Bb@DZ?B@HDb@?PALJ`@FVJj@Lx@Fj@@F@FBNJv@?HB`@@L?@?B?DADADAHAF?B@HD\\@B@B@@?@B?B?@?@A"
                     },
                     "start_location" : {
                        "lat" : 45.4165039,
                        "lng" : -75.6642701
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "9 m",
                        "value" : 9
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 45.41488,
                        "lng" : -75.66891029999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ebetG~`zlM@FBH?B"
                     },
                     "start_location" : {
                        "lat" : 45.41490719999999,
                        "lng" : -75.66880019999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1277
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 287
                     },
                     "end_location" : {
                        "lat" : 45.420817,
                        "lng" : -75.6823165
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_betGtazlMKD{Ap@C@q@ZOHMHIFQPMNEFEFKVQ`@AFKVEHCDEH_@hAc@xAIZw@xCSv@Kb@Qj@Ql@Oj@Od@Sr@Oh@M`@EJCFK^?DGVKn@CVIn@CPAFc@pBG\\e@xBm@jDIf@ANCNERCRCLMlAKz@EVOfAOx@Md@GVW`AUp@a@bAs@bBKTGPADo@v@aApA[p@"
                     },
                     "start_location" : {
                        "lat" : 45.41488,
                        "lng" : -75.66891029999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "57 m",
                        "value" : 57
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 45.4212749,
                        "lng" : -75.6824029
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cgftGnu|lMIMA?CAA?WEC@A?C@e@`@"
                     },
                     "start_location" : {
                        "lat" : 45.420817,
                        "lng" : -75.6823165
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 173
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 45.42049249999999,
                        "lng" : -75.6830648
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}iftG~u|lM?@Ph@DDDDB@B@@?@A@?@A@A@A@C?C@CAC?CAGACACCEAAAA?A?CAA?C?C@C@C?A@A?A@?@A@AB?@?@@B@@@@@@B?B?B?B?BAD?BAB?@?B?B?@@@?B@@@@BB@@@@BBDDHJNP@@VXPR"
                     },
                     "start_location" : {
                        "lat" : 45.4212749,
                        "lng" : -75.6824029
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 462
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 88
                     },
                     "end_location" : {
                        "lat" : 45.4228732,
                        "lng" : -75.6878067
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "aeftGbz|lMwCdHKVe@dA]z@Ul@EJEDCBGBGBEDCDCJELGVG\\Mj@S~@EPCFCBA@IHMHKHEHCFGPERCP?BCHK^Wj@"
                     },
                     "start_location" : {
                        "lat" : 45.42049249999999,
                        "lng" : -75.6830648
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "44 m",
                        "value" : 44
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 45.4232288,
                        "lng" : -75.68764949999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eLaurier Ave W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 48\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}sftGxw}lMEGGICCECIEA?AAC?C?Y@"
                     },
                     "start_location" : {
                        "lat" : 45.4228732,
                        "lng" : -75.6878067
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 342
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 134
                     },
                     "end_location" : {
                        "lat" : 45.4217151,
                        "lng" : -75.6914603
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLaurier Ave W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 48\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "evftGxv}lMHXTt@JZ^pAPh@@BPj@Pl@HTFR@DHXFNDNDN\\lAZjANb@V~@Tz@"
                     },
                     "start_location" : {
                        "lat" : 45.4232288,
                        "lng" : -75.68764949999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "36 m",
                        "value" : 36
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 45.4219769,
                        "lng" : -75.6917376
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eElgin St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 91\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wlftGrn~lMUXEB?@GFON"
                     },
                     "start_location" : {
                        "lat" : 45.4217151,
                        "lng" : -75.6914603
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "48 m",
                        "value" : 48
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 45.4220528,
                        "lng" : -75.6923388
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eElgin St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 91\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "knftGjp~lMA\\?NEh@E^"
                     },
                     "start_location" : {
                        "lat" : 45.4219769,
                        "lng" : -75.6917376
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "12 m",
                        "value" : 12
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 45.4221513,
                        "lng" : -75.6923932
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eElgin St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 91\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ynftGbt~lMA?A?A?A?A?A??@A??@A?A@?@A??@"
                     },
                     "start_location" : {
                        "lat" : 45.4220528,
                        "lng" : -75.6923388
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "21 m",
                        "value" : 21
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 45.42208189999999,
                        "lng" : -75.69260079999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eElgin St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 91\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "moftGlt~lM?@A@?@?@?@?@?@?@?@?@?@?@?@@@?@?@@??@@??@@@@@@??@@?@?"
                     },
                     "start_location" : {
                        "lat" : 45.4221513,
                        "lng" : -75.6923932
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "68 m",
                        "value" : 68
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 45.4219335,
                        "lng" : -75.69340249999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eElgin St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 91\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_oftGvu~lMD\\?@DTFd@BH@FDN@D@D?B?@?BABCF"
                     },
                     "start_location" : {
                        "lat" : 45.42208189999999,
                        "lng" : -75.69260079999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "10 m",
                        "value" : 10
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 45.4219101,
                        "lng" : -75.6935306
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eElgin St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 91\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "anftGvz~lMBX"
                     },
                     "start_location" : {
                        "lat" : 45.4219335,
                        "lng" : -75.69340249999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "83 m",
                        "value" : 83
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 65
                     },
                     "end_location" : {
                        "lat" : 45.4225502,
                        "lng" : -75.69408439999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eElgin St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 91\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}mftGp{~lM[Vs@j@o@h@"
                     },
                     "start_location" : {
                        "lat" : 45.4219101,
                        "lng" : -75.6935306
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 268
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 45.4213651,
                        "lng" : -75.6970503
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAlbert St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa 42\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}qftG~~~lM?V@PBLb@pATp@b@tAh@bBFNFRDNL\\x@hC"
                     },
                     "start_location" : {
                        "lat" : 45.4225502,
                        "lng" : -75.69408439999999
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "370 km",
                  "value" : 369976
               },
               "duration" : {
                  "text" : "19 hours 20 mins",
                  "value" : 69597
               },
               "end_address" : "Oshawa, ON, Canada",
               "end_location" : {
                  "lat" : 43.8970998,
                  "lng" : -78.8657942
               },
               "start_address" : "Ottawa, ON, Canada",
               "start_location" : {
                  "lat" : 45.4213651,
                  "lng" : -75.6970503
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 295
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 64
                     },
                     "end_location" : {
                        "lat" : 45.41994649999999,
                        "lng" : -75.7002372
                     },
                     "html_instructions" : "Head \u003cb\u003esouthwest\u003c/b\u003e on \u003cb\u003eAlbert St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa 42\u003c/b\u003e toward \u003cb\u003eR. O'Connor St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 87\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qjftGpq_mMXx@vAdEHPBFDJPh@|@nCBB@B@BFPt@~B"
                     },
                     "start_location" : {
                        "lat" : 45.4213651,
                        "lng" : -75.6970503
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 243
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 56
                     },
                     "end_location" : {
                        "lat" : 45.4217996,
                        "lng" : -75.70189289999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBank St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 31\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uaftGne`mMkAbAML]XWXEFGDGFGDWTg@`@KJWRy@n@e@^"
                     },
                     "start_location" : {
                        "lat" : 45.41994649999999,
                        "lng" : -75.7002372
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 763
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 180
                     },
                     "end_location" : {
                        "lat" : 45.4189568,
                        "lng" : -75.7104875
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWellington St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa 34\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gmftGxo`mM~@tCfAhDl@dBn@rB?@A@?@@@?B?@BHTp@rAfEBHPj@`A~CPj@Tr@L`@jAnD@FDPBJLb@D^BV@V@J?D?TAZAPAHAPAJCVGh@Gh@"
                     },
                     "start_location" : {
                        "lat" : 45.4217996,
                        "lng" : -75.70189289999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 488
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 117
                     },
                     "end_location" : {
                        "lat" : 45.4163335,
                        "lng" : -75.71479269999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWellington St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa 34\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "o{etGpebmMKlBAP?JAH?J@T@RDPH^FVJ\\Pj@L\\N\\PZLT^^\\ZPLFFFBPHv@`@bA`@PHPJBBB@LLPPVXR\\NXFNZv@BHFH"
                     },
                     "start_location" : {
                        "lat" : 45.4189568,
                        "lng" : -75.7104875
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 168
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 45.41545139999999,
                        "lng" : -75.7165327
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSir John A. Macdonald Parkway W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "aketGl`cmMVl@t@hBb@fAt@jBFN"
                     },
                     "start_location" : {
                        "lat" : 45.4163335,
                        "lng" : -75.71479269999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "57 m",
                        "value" : 57
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 45.4159452,
                        "lng" : -75.7167211
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qeetGhkcmMA?g@Ty@N"
                     },
                     "start_location" : {
                        "lat" : 45.41545139999999,
                        "lng" : -75.7165327
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 319
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 59
                     },
                     "end_location" : {
                        "lat" : 45.414091,
                        "lng" : -75.7197346
                     },
                     "html_instructions" : "Sharp \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-sharp-left",
                     "polyline" : {
                        "points" : "uhetGnlcmM@?TLNTR\\R^NZJRPl@F\\F\\?@HTFPFLB@FBDBJNb@x@P^JRRTX`AHNPRPPNN"
                     },
                     "start_location" : {
                        "lat" : 45.4159452,
                        "lng" : -75.7167211
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 471
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 76
                     },
                     "end_location" : {
                        "lat" : 45.4117732,
                        "lng" : -75.72422349999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eOttawa Riv Pathway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "a}dtGh_dmM^F|@NLBHDHBDD@?HJFHFJLNFJFFHHHFJHFFFHDFv@zANXDLFNBLHTHb@H`@BTJz@BPD`@@JJdAFj@Hj@Hn@RtA@JFX"
                     },
                     "start_location" : {
                        "lat" : 45.414091,
                        "lng" : -75.7197346
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1585
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 275
                     },
                     "end_location" : {
                        "lat" : 45.4105988,
                        "lng" : -75.74104369999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eOttawa Riv Pathway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "qndtGj{dmMRbBFp@@l@@z@@p@Bn@HfBDx@Db@Hf@F\\J`@HVBPBR?\\?^?\\@b@?B@VDRFVJTHPLJh@`@JTHp@H`B?H@r@?h@Cz@Ap@?@Iz@Gd@SxAQ`B_@z@O\\Sf@_@x@EB]HQFKBG@EBE@CBIHWRIHMNCBCBUR_@VMJQLWPQNSRGHGHKRENCJCL?J@J@PDTDPFLDHFHHJ@@JHLHRNf@XHDBBLJJLJNFJNZL^Ld@\\nA`@|ARx@Ld@N`@Xx@@BPj@BDDRFVDZ@L@LDVDPFLJVDJDL@RFj@Bf@?X@^BTDLDP"
                     },
                     "start_location" : {
                        "lat" : 45.4117732,
                        "lng" : -75.72422349999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 km",
                        "value" : 2596
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 469
                     },
                     "end_location" : {
                        "lat" : 45.3957793,
                        "lng" : -75.7605811
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eOttawa Riv Pathway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "ggdtGndhmMDDb@n@DHPTLNHJDP@R?PEZCb@AR?XBVPt@p@dC@H\\rAFLDDDDRFPDJFNNN\\^jAFTJDb@TFB`@RLFRJb@TTPVRJJJLV^PTFJX\\HNFLDJDNFZH^F\\BXD`@Bd@BX?@@NDRHTFVBRBRDVHl@Fh@Fl@D`@F`@DVH^HVHRHNLTJJHJFJFLDJFN?BDHBFFDNNNNBBJLPRHF?@DBFDVPLFLHHBHDJFLLNJPRJNJP@@FRHV@BH\\@J@DBR@L?ZA`@AhAAdBAr@?r@Ap@?r@?b@@N?@B^@P?@BRBLBHLXHTDPDNHVNf@X~@HRHVJXLPNTNTTTNLFDLJNJLHXNr@^JH`@\\^ZLJLHLFHFLHPRPNHFHDHBLFTDb@HPDLFLDFDJHPPFHFHRNNJHFHJDHHPTl@Rl@JTJVVh@LRLR`@l@h@n@XXVXZX\\Vf@V\\JZHr@F\\@f@?^ElAUp@I`@ELGRILKr@a@LETKLGTMRQTSXc@"
                     },
                     "start_location" : {
                        "lat" : 45.4105988,
                        "lng" : -75.74104369999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 972
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 183
                     },
                     "end_location" : {
                        "lat" : 45.38800759999999,
                        "lng" : -75.7653923
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSir John A. Macdonald Parkway W\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "sjatGr~kmMLCTCXAd@?`@B\\B^FN@F@LBx@Pf@JNBND~AZh@Lf@JB?b@J\\HRD^JJBRF\\NXL^RLHNJ\\TJJFDRPTRVXLPJNZ`@^p@Zf@T`@NTBFT^LRLRX`@JLHJVV`@^RNTPTLLHTJp@^~@f@^Tj@^NJDF"
                     },
                     "start_location" : {
                        "lat" : 45.3957793,
                        "lng" : -75.7605811
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "37 m",
                        "value" : 37
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 45.3881281,
                        "lng" : -75.7658292
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eOttawa Riv Pathway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "az_tGt|lmMWvA"
                     },
                     "start_location" : {
                        "lat" : 45.38800759999999,
                        "lng" : -75.7653923
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.7 km",
                        "value" : 3673
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 663
                     },
                     "end_location" : {
                        "lat" : 45.365609,
                        "lng" : -75.79643899999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOttawa Riv Pathway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yz_tGl_mmMB@LB^Vp@b@NLb@^`@`@TX\\b@d@l@TZ`@h@Zb@NRPVNR`@j@LLj@v@z@x@dA`AVTVVl@v@T^Xd@HPDHFLXn@Vn@Tj@Rj@Pj@H^D\\Dt@B`A?PGp@Ih@G`@Ed@?R@L@T?JBTFj@Jb@FZBHDNBP?DBT?J@H?HBNFj@Hh@Ll@FXNd@N\\JRR`@PZPV\\`@VTJJXT\\TRHXJr@Rx@Nb@H`@Ff@L`@HXJRHNH@?BBB@BBB@BBB@@Bd@z@JNJJLJJHHF^TTJHJFHJT@@HPHPXZv@p@b@`@`@RJDh@JVD^LXR~@l@vA|@NNBB@@HRTb@`@j@BF?@@?TRPNLH\\b@T^Pb@Rr@ZnAd@hBXnA^rAPl@Vj@LZd@z@^x@N^Tb@JPT\\PPTRZLLDN?h@B|@DVHRHTJb@\\^b@XJN@b@ILAP@ZJ`AvAJVJVTn@JRrE`KXn@hEfJ\\x@v@bBjAhCxBvEzAhDfBxDVh@T^LHTHf@HB@VJB?LB"
                     },
                     "start_location" : {
                        "lat" : 45.3881281,
                        "lng" : -75.7658292
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 2014
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 350
                     },
                     "end_location" : {
                        "lat" : 45.3519596,
                        "lng" : -75.812493
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eOttawa Riv Pathway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "an{sGv~rmM@X?DFd@BNBFFRHR@D@F@F@F?F@H?F?N?^BV@FBHhBxDt@~AhBpDFPXd@xAbCDHb@j@LRf@r@b@n@V\\TZZ^TXTT`DjDlBdBrFrFNDJHVTzAlAj@j@jAfAl@h@n@l@xBpBLJJJJHlBfBXV~AvApAlA`A~@RRtAjAr@n@hD`D`Av@t@p@TR^d@Zb@PXV`@DHPr@@@?@@@@@?@@@@?@AJK"
                     },
                     "start_location" : {
                        "lat" : 45.365609,
                        "lng" : -75.79643899999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 665
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 179
                     },
                     "end_location" : {
                        "lat" : 45.3469754,
                        "lng" : -75.8167782
                     },
                     "html_instructions" : "Take the crosswalk",
                     "polyline" : {
                        "points" : "wxxsG`cvmMROFGDC@C@??A@?@?@??@B@@B@B@DBFBD@BDHDFFFFFFDRRNLJJb@`@HHFFt@p@b@`@p@l@hAdA`B~AlAbArAhANLNHtAhAf@`@fBpAVVBDDBB@LFDT"
                     },
                     "start_location" : {
                        "lat" : 45.3519596,
                        "lng" : -75.812493
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "61 m",
                        "value" : 61
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : 45.3466586,
                        "lng" : -75.8173833
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAero Dr\u003c/b\u003e",
                     "polyline" : {
                        "points" : "sywsGz}vmMH\\DTBD@FBHDHDFFF?@DDDDDB"
                     },
                     "start_location" : {
                        "lat" : 45.3469754,
                        "lng" : -75.8167782
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 km",
                        "value" : 2418
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 445
                     },
                     "end_location" : {
                        "lat" : 45.3430098,
                        "lng" : -75.8423753
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTrans Canada Trail\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWatts Creek Pathway\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "swwsGrawmMNY@ABA@A@AB?@?D@F@DBPLRPRNv@n@\\Xf@`@TN`@Xv@p@LLh@d@PZJXJ\\Fn@Bt@Hf@Ld@Hn@Dl@HbBBz@?H?HBv@FjAJ~@\\|BRnARtALjAN|ADl@@\\?^Ab@Id@CHCTADIb@CX?R@R@H@FBFBFBDBBDBB@D@D@RBXBD@F@D@FDDFDFDNBJ@N?JEZUv@EPCREf@?P@J?P@??NH\\FNFNJNLJVTNNJL@BJN?BFLFPDNFT@R@NANEPIJOJOFQDGDKHELCD?BCH?D?H?JFZF\\@L?JEXMd@Kb@EJCTAH@PBRDPHLJLp@f@NPLXH\\V~@@BP^T^HNDH@J@J?n@?b@@n@Bd@Jp@J`@Tn@Tf@h@v@FLFPBRBRBRBh@Dr@D`A?DADCDCDCFYXUVGJCFCHCJ?FAF?L@f@?H?D?DERCLCJCFCFQXADCFALATANAHETI\\AFADEFEH_@d@]d@CDCFADAFEj@CJADCFCDCDQXEDGFMJKHGHKPCFEJGTCJ?H?B?LBVBX?X?^Cd@ATAF?HCHAFEJCHAJAD?F@H?F@HBRB`@"
                     },
                     "start_location" : {
                        "lat" : 45.3466586,
                        "lng" : -75.8173833
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 km",
                        "value" : 2062
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 565
                     },
                     "end_location" : {
                        "lat" : 45.3252849,
                        "lng" : -75.8352494
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMoodie Dr\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 59\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "y`wsGz}{mMTEtC[h@In@GPMPERChDa@`AMl@IfDc@bBS@AfBUPClAMrC_@jBUxBY|@Md@GNENC\\Kt@UVKTKnAi@tAq@@APIBCJMjEwBhFcC`@QrBaArAq@TMj@Y^S@A|Aw@VGzBeANGj@W~@c@j@WbCcAZMFCzCoAFCvBy@"
                     },
                     "start_location" : {
                        "lat" : 45.3430098,
                        "lng" : -75.8423753
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 380
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 71
                     },
                     "end_location" : {
                        "lat" : 45.32283839999999,
                        "lng" : -75.83831959999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eFitzgerald Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_rssGhqzmMN`ADXZvADTBN@@@FBHFLNPRPd@b@PP`@`@ZXHHbA`AVVVVXVd@d@BBLJDBB@B@D?F@F?F?D?"
                     },
                     "start_location" : {
                        "lat" : 45.3252849,
                        "lng" : -75.8352494
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 845
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 153
                     },
                     "end_location" : {
                        "lat" : 45.3175886,
                        "lng" : -75.84499869999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wbssGnd{mMDPBVHz@@J?D?B?BADKTMZABKVCHAHAL?PBBHLLLj@h@fBdB\\\\f@h@p@p@`@`@`@^j@h@f@f@`@`@d@d@tArAp@r@vBtB\\\\tDpDZXZXPRNR"
                     },
                     "start_location" : {
                        "lat" : 45.32283839999999,
                        "lng" : -75.83831959999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "6.3 km",
                        "value" : 6277
                     },
                     "duration" : {
                        "text" : "20 mins",
                        "value" : 1192
                     },
                     "end_location" : {
                        "lat" : 45.2741254,
                        "lng" : -75.8953837
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "}arsGfn|mMVTVVTT^^FFZ\\LJVV\\ZFFd@b@FFLLBBBBdFbFvDtDx@v@PPx@x@n@l@fAfAt@t@b@b@\\Zn@l@p@p@h@h@h@h@hCfC`I|Hv@t@nHfHdH`HDF\\ZjDdDb@d@@@NNt@t@rArAr@j@hGdGd@b@fGbGzHrHt@x@xIrIrOhOrMjM`@XzJvJpDnDhCbCLLvCzClChDhCtDxBtDVb@~GhMdArBJPnF|JTd@X^vAlCvAlCzBbExApCpXzg@jFpJVd@zAtCHNBBDDB@DBB@FB@DBD@B?D?F?F"
                     },
                     "start_location" : {
                        "lat" : 45.3175886,
                        "lng" : -75.84499869999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "12 m",
                        "value" : 12
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 45.2742294,
                        "lng" : -75.8954382
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRobert Grant Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "irisGbifnMSJ"
                     },
                     "start_location" : {
                        "lat" : 45.2741254,
                        "lng" : -75.8953837
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 129
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 45.27404139999999,
                        "lng" : -75.8954983
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit and stay on \u003cb\u003eRobert Grant Ave\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "}risGnifnMAACAAAC?A?C?C?A?C@C??@A?C@ABA@CBABABABAB?BAD?B?B?D?B?B?D@B@B?B@BBD@@@B@@B@@@B@B@@?B@B?@?BA@?@A@?BA@A@CBABE@C@C?C@C?A@A?C?E?C?CPa@"
                     },
                     "start_location" : {
                        "lat" : 45.2742294,
                        "lng" : -75.8954382
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.5 km",
                        "value" : 3494
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 659
                     },
                     "end_location" : {
                        "lat" : 45.2534481,
                        "lng" : -75.9287319
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wqisGzifnMJB@@BB@D@F@@@HDNDJhC`FvBrD`BxCdEzH|AtCnFxJ`B|CjBjDx@`B`@t@LRhAvB\\n@Vd@`AfB|DtHBJ?R?d@BNb@t@JPHRNFNDTHNRl@dA`BvChCvEBDjAxBtElI|ApCjAtB`FjJHNbCtEnCdFfAtB`@v@BB@@@@DBF@D@D@FDBDFLDF?D?B?BAH?B?D@B@@@BB@FHJPLPf@|@`@t@b@x@hApBjHnN~DhH@@rChFBJ@B@H?N?LBj@BRJVRb@R\\"
                     },
                     "start_location" : {
                        "lat" : 45.27404139999999,
                        "lng" : -75.8954983
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "20.8 km",
                        "value" : 20787
                     },
                     "duration" : {
                        "text" : "1 hour 5 mins",
                        "value" : 3913
                     },
                     "end_location" : {
                        "lat" : 45.1362399,
                        "lng" : -76.1342183
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "aqesGpylnMDHDBDDFBF@VBF?DBDBDFFHPXvCnFlDtGR\\`HdM^p@jC|EjC|Eh@~@tB|D@@rBxDhDlG@@nC`F?@zCtFjE`I?@~DnHVb@NXfE|H?@tD`H~EbJ@@dFjJFN@?n@jAfApBTd@Xd@t@vA~@dBhApB~AvCjCdF@@bDjG|C`G~BfE@@vBzDvB|Dt@rAlGbLnBnDVd@~BfEpBrDfDhGn@hAvB|D`ErHdAnBfApBnCdFTd@n@jAfApBn@jAdDjGJPJRvB|DVd@nCdFPXlA|BVd@~AvCzAhCDJvB|DvB~DhDpGbDbGvFlKnBjDxErINZ`HdMdBbDnCbFnA`CfCrEnCbFjArBjC`FVd@fApBVd@Vf@Vd@Zj@j@dAVd@Vd@n@jAvB|D`@v@LR|AxCVd@vB|D^t@~@`Bn@jAxB|DVb@xBzDVd@T`@`BzCn@jAl@lAn@jAvB|Dl@jA@@fApBjBjDHPn@jAp@jAn@jAVd@fApBnC`Fn@jA`BvCnC`FrBtDr@rAn@lAbBbDPZVd@Vd@fApBVd@v@vAfApBfApBn@jAjBfDLRdArB`CjELVn@jAfApB~AvCpCbFVd@~AvCPZ\\n@vB|DnCbFvB|DlA|BhCvE~AvC~AvC~AvCjC|EBD~AvCn@jAVd@vB|DvB|Dn@jAn@jAlApBVd@Td@Vd@Zn@Xh@Vf@Vh@T`@Vd@Vd@Vd@Vd@~AvC~AxCvAhC^r@xBzDfAnBfApBXd@Vd@~AtCrAfCFLf@|@n@lADF`A~At@jALRhBhDFHNZ~AvChBhDVd@h@bAjAzB~AvCnFfK~CtH|@zBh@rA~@zBh@pAh@pA`A~Br@~BPj@v@bCPj@t@bCb@vAHRvA`EtB`GRn@Pd@zCvIdA|CXv@rBbGdCjHjAlDZz@JXd@tAx@`Cd@tA~AtE?@rB`Gz@hCd@tAjAjDv@|BlAnDx@`CTr@v@vBbAzClCzHlAnDPh@dCjHlAnDRh@?@Ph@v@bCz@hCN`@Vr@`@lABFN`@xCvIBH`CbHBFnBxFBHRh@jAjD`@lA|@hCN`@nAtDhAbDBFhAbD@Fb@lABFd@tA`@lABFnBxFBFd@tAb@lABHfA`DBHt@vBVr@N`@Tr@|AlEBFfAbDVr@nBvFBH~AtEN`@pAtDN`@BFd@tAzCvIL`@DJ|AhEBFhA`DBF\\`AJZHZFVDVHb@?@V|@BHDPl@dBjA~Cn@fBdA|CFRpA~Cf@lAp@`BJRdAzC`BvEN`@@Fv@bClAjDDPDPh@`BRf@Tf@DJDPPh@L`@Tb@X\\"
                     },
                     "start_location" : {
                        "lat" : 45.2534481,
                        "lng" : -75.9287319
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7 m",
                        "value" : 7
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 45.1361792,
                        "lng" : -76.134181
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eQueen St S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "otnrGz}toMJG"
                     },
                     "start_location" : {
                        "lat" : 45.1362399,
                        "lng" : -76.1342183
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "94 m",
                        "value" : 94
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 45.13566300000001,
                        "lng" : -76.13512519999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eColeman St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ctnrGr}toMTn@f@hAh@bA"
                     },
                     "start_location" : {
                        "lat" : 45.1361792,
                        "lng" : -76.134181
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 326
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 82
                     },
                     "end_location" : {
                        "lat" : 45.1333093,
                        "lng" : -76.1374012
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eColeman St\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "{pnrGpcuoMp@dA|@d@fA^`@N~@ZLHJJFFHHFLv@vAVd@Vd@Vd@FL"
                     },
                     "start_location" : {
                        "lat" : 45.13566300000001,
                        "lng" : -76.13512519999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "12.9 km",
                        "value" : 12942
                     },
                     "duration" : {
                        "text" : "38 mins",
                        "value" : 2270
                     },
                     "end_location" : {
                        "lat" : 45.025833,
                        "lng" : -76.0776133
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOttawa Valley Rail Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ebnrGvquoM`A_At@q@JKfAoA~@{@rAwABEt@s@d@c@TWjAsA~A_B?AhBgBdAgAdCiCfAgAr@u@DC~B{BRQ^[\\[TSFE\\[x@o@\\[@A@AXSDETQfAy@FETQ~@q@TQHEPOvBuAJGHEtBoAhBgAz@c@HEZQdAg@VMHElB_ApAi@HCVMx@]FCHCXK|@[f@SFEXKh@UdCu@xBm@JEHAdBg@ZGHChCg@@?z@QHAbCe@HAjEi@l@I|@KFAXEHA|@KjAOhBO\\Cb@Ab@Cb@Ax@Cp@E|BMvCQFAb@CtAMx@IdAMfAK`@Ed@InDm@r@MzBe@b@KdAUlD{@d@MlBm@|Ag@h@QrBu@nAg@FClBy@rB_A@ArAo@pAs@HETM`@QZQd@U`@SVOhAk@dAi@JETM~@g@z@e@hAi@^Sn@[tBiAv@a@jBaAd@UhDcB|C_BDCXO`@U^SXODC`@U^S^U@?^Uz@i@zAaAFE~@o@`Aq@zAeAPMjBwATQhBwAx@o@\\W^YHGpCwBLKlByAHGjBwAbA{@`@[dBoArAaA\\YHErAiA`CkBVQ|BgB\\Wl@e@n@g@x@q@`As@xAiAbBqAlByA`Au@~AmADC\\Y^[rAaAFG^YzAiAzBiB^Y~AmAnByAh@_@^WTOHG^Wj@_@r@e@NM|AcA`@UNKNI^UpBmANI^U`Ak@^SlAo@xAw@~@e@XOnAq@z@]FCfBw@xAo@ZMf@S`@Qr@YtBw@d@QdC}@^OxAi@rBs@HEzAm@bA_@b@OtAi@LExAg@pAe@`@OBA\\M`@Q`@Op@WPG`@M`@Ob@MXM`@QbAa@VKlAe@`@O`@Ol@UzAi@bBk@nEaBHCrDuAn@U|CiAn@U|By@tDsAbA_@bA_@PINGfC_Ab@QdC{@zBw@pAe@x@[HEdBs@JEv@YfC_AfBo@bA]?AjE}Af@Q`Bm@bA_@DAbDmAxBw@NGbA_@jAc@z@[`@ObA_@NGr@WbBo@hBo@n@WvDwAf@QbAa@fC_Af@QbC}@bA_@t@Wn@WbA]b@OdBo@`@ObA_@jAa@z@]bA_@`@OTKpAc@hDmAlAc@~B{@rBw@t@WbDmApDqA`@O`@ObDmAlBq@lAc@VKbAa@b@OfDoArAg@vAg@\\MBAbAa@"
                     },
                     "start_location" : {
                        "lat" : 45.1333093,
                        "lng" : -76.1374012
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "20.0 km",
                        "value" : 20021
                     },
                     "duration" : {
                        "text" : "57 mins",
                        "value" : 3446
                     },
                     "end_location" : {
                        "lat" : 44.9032794,
                        "lng" : -76.24921429999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePerth Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 10\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Route 10\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mbyqG`|ioM|@~AJNNV`@n@Xb@HLBBn@z@\\`@XVTJVHl@PD@`@N\\FD@ZFB?\\Dd@Bb@?b@AV?JAb@EpAKfD]b@EhBK\\?dB@D?b@@b@@b@@p@@|ADb@@nCFjAB^@b@@b@?b@@b@@fAB~GJb@@b@@D?lD?f@?\\?fA@r@DRBb@F`@F@?`@JbAVb@NpFdB`@NNDj@Tj@TZP\\Xl@d@d@f@Zd@Zb@BFPZj@jAp@|ATf@Vf@xDtIp@|Ax@lB@@Td@\\t@d@z@x@tAh@|@@@p@`ApAfBX`@FHfA`Bb@r@\\j@R`@Tn@DJHTj@hB~@jDNj@Nl@p@dCV`AR`Ad@bClBhKJn@VtABFd@~B^vATr@Vr@j@jAb@z@JLNTHJNR\\b@j@j@XTFDb@Zz@f@|Ar@nBbArAp@`@Rt@`@hD|B^V|IbG|AjA|@r@^VXVB@hH~ElAv@^Z\\VZXVXVVJLl@v@T^fApBn@hA~AvCXd@j@bAXl@fAtBl@lAVd@LTl@lAVd@dArB@?Td@Vd@Tf@fArBrB~D~IbQjCdF|AxCVf@l@jA|AzCVd@rB~DVf@Vd@@DbAlBVd@lCdF`B~CfAfCTdALl@TfABTDp@L|B?jA?lBG|AGnBGxACp@EnACl@AXAR?\\AT?nA@`@?NBX@V@NH~@Fl@@BHl@Lt@Lj@\\jA`@rAHRpAdEVp@Tr@P`@Vh@Tb@R\\LRT`@b@p@Z`@\\^@@l@p@JFZXf@`@tCtB^X\\V^Vf@^VPf@^v@b@ZPBB`@RVLFB`@PB@v@VHB`@J?@TFJBb@J`@JfAT\\Hf@J`@JF@ZF`@Hb@Jb@H`@HdATb@Hp@N^HVHTFVLTJ`@R|@p@v@p@VZNPBFbBrCzEpIVd@rFtJVb@fAnBVd@Xd@hDdGVd@Vb@`@p@f@|@jDbG|HbNBD`DdGVf@nKjSnHlNfApBVf@l@jAzGjMR`@BBbAtBrB`EvDxHVd@fKvSzAzCfA|BP^FPXn@lAdDbD|I|CrI~AhEVr@vDvJz@zBlBhETf@j@pAVf@N\\xBhElCfFl@jAVd@dArBl@lAn@jArB`EnHtNVd@|@fBlA~BbHbNnHvNjCfFrB~DTf@n@jAdAtB~A~C~@fB^p@`AjBTd@p@rAHN^t@LV`E`INZx@`BN\\PZdArBdGxLtCfGHN|ErJxAvC|A|Cn@lA`DnGVd@zAzCdArBdArBrB`ETd@Vf@`HzMfHjNvE`JTd@`GhLbDlG|BjETd@fArB|BlEbAlBBDd@z@rBxDzApCbEtHbCnEdFnJFJbDdGZh@LX~CxFvAlCJPDFVd@hAnBzBbE~AtCpFvJhAnBJTrA~B~AtCd@`A"
                     },
                     "start_location" : {
                        "lat" : 45.025833,
                        "lng" : -76.0776133
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 342
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 71
                     },
                     "end_location" : {
                        "lat" : 44.9056509,
                        "lng" : -76.2519829
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVictoria St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "odaqGplkpMw@`A[^m@t@w@~@[^wBjCm@t@}AnB"
                     },
                     "start_location" : {
                        "lat" : 44.9032794,
                        "lng" : -76.24921429999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 418
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : 44.9032078,
                        "lng" : -76.2560082
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eIsabella St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "isaqGz}kpMVd@lBlDbCzEl@jAj@bAbCdF"
                     },
                     "start_location" : {
                        "lat" : 44.9056509,
                        "lng" : -76.2519829
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 335
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 75
                     },
                     "end_location" : {
                        "lat" : 44.9054894,
                        "lng" : -76.25879399999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWilson St W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLanark County Rd 43\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "adaqG`wlpM{@fACByAlBq@|@qAdBWXw@dAQRgAxA"
                     },
                     "start_location" : {
                        "lat" : 44.9032078,
                        "lng" : -76.2560082
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "5.0 km",
                        "value" : 4959
                     },
                     "duration" : {
                        "text" : "14 mins",
                        "value" : 869
                     },
                     "end_location" : {
                        "lat" : 44.8825478,
                        "lng" : -76.3089737
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSunset Blvd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Rd 6\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow County Rd 6\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "iraqGlhmpMJNFHFLt@jADDZh@JRR\\JRLVRj@NZNd@VpA@FDZDVBT@X@d@?j@@`@A^Ep@Ej@MhAUpBeArJa@jEAFQxAK`AGl@Ir@Gd@CPK~@Ij@OlBChA@lB?^DjAHp@H~@Nv@Lb@Rx@L^Th@Vn@T`@P\\`@v@n@jAtCrFvB`ELTVd@HP`@z@hA~Bx@pBRh@FJr@~Al@~A\\z@fB|Dh@hA|AbDdCbFPXVd@NTfBnCNTX`@n@`AhBtC|@|Aj@fApEbIl@fAnCdF\\p@jBjDzArCFJfArB@@l@dA@@fAnBn@fA?@dAdBDF`AfB~@|Az@bBVf@DHzAxC|CdG?@DFbArBP\\DHlBvDBDTd@@BR`@Vf@@Bb@x@dAnB^r@@BhEnIlEvI`EdIfAvBpEzIdBrD"
                     },
                     "start_location" : {
                        "lat" : 44.9054894,
                        "lng" : -76.25879399999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 418
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 91
                     },
                     "end_location" : {
                        "lat" : 44.8853593,
                        "lng" : -76.312493
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eGlen Tay Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}b}pG`bwpMk@v@qAbB[`@iBdC[`@gCfDMPg@p@s@|@A@]l@"
                     },
                     "start_location" : {
                        "lat" : 44.8825478,
                        "lng" : -76.3089737
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 476
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 141
                     },
                     "end_location" : {
                        "lat" : 44.8834167,
                        "lng" : -76.31787039999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHwy 7\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans-Canada Hwy\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ot}pG`xwpM`@zA\\nARx@r@zCj@vBbAzDp@dC|@fDV`ABL"
                     },
                     "start_location" : {
                        "lat" : 44.8853593,
                        "lng" : -76.312493
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "33.5 km",
                        "value" : 33535
                     },
                     "duration" : {
                        "text" : "1 hour 51 mins",
                        "value" : 6682
                     },
                     "end_location" : {
                        "lat" : 44.7756972,
                        "lng" : -76.68436699999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kh}pGtyxpM@A\\]p@bCn@bC`ApDNj@p@bCPl@Rr@r@rC^zANl@n@hC`@zAT~@XfAX~ALl@`@rCBNTbCFp@Dp@Dr@Bd@?JBnADhABp@@f@BvC@|A?FFbBBjABXBp@FlABTFp@Fn@Fp@PbBHn@P`BR`BHj@?BHn@Hp@Hn@Hp@R~AR`B\\pCHp@Hn@\\pCHn@Hp@R`BHn@R`BHn@Hn@T`BHp@Hn@\\pCHn@R`BHp@Hn@\\pC\\pC\\pCf@bEp@rFp@rFHn@\\pCp@rFp@rFh@`E\\pC`CxRp@rFHn@p@rFHp@z@bHHn@p@rFHn@Jp@f@`ER`B\\pCHp@Hn@\\pCHn@Hp@f@`Ep@rFp@rFR`B\\pCHn@\\pCJp@f@`E\\pCb@hDp@rF|@bHr@pFz@bHr@rF|@bH\\pCnEd_@bBfNv@lGHn@Hn@R`B\\pCHn@Hp@Hn@\\pCT`Bt@hGDXp@rF\\pCf@`Er@rFf@bEz@bHR~AThBn@jFX`CL~@^pCHp@@@p@nE@Bv@zDH^pAfFf@~A`@tAd@xAlCrIDLjAjDhAlDjAjDPj@j@~AJ`@Pj@bArDhCbJ\\nARt@`@xANl@`ArD^xAPl@Nj@n@fCd@vAb@tATt@|@nBTf@j@nAXb@jAhBVV\\\\x@x@\\\\Z\\\\ZBBXV\\ZxBjBz@t@|@v@z@t@z@t@\\Z^Xr@n@d@b@\\Z?@`BtB`@p@NTdAnB\\z@Rh@Th@JXf@hBdBjGNl@ZhADN\\zA~@tD^xAz@lDBFrA~ENl@Pj@BJl@xBPl@Nj@FRJTPb@@DXx@LXTf@P^BHPj@J\\`AdEBLF`@Hn@FZBRP`BBJBd@Fp@DbC@p@@p@@r@@p@@TO~BUfECRUxGGpALhDBp@Dr@DfANjA^nCZbCRz@x@vDd@vBX|@b@vARj@t@`Cb@vAPj@p@rBXv@d@tAnAhDPj@`BrERh@d@tAz@~Bf@rARh@Rh@Rh@z@|BTh@Rh@Rh@f@rARh@Tl@l@nAj@nALVHLdBlCXb@Xb@Xb@RZx@hApAdBX^pAdBX`@jBdCX`@Z`@X^Z`@nAdB|AtB`@x@Vf@bAtBj@jAr@fCPj@Nl@Nd@@DJn@Ll@Jn@X|ALn@Hj@Hp@T~AHn@Hn@Jp@L`AR`CNbBL`B@FJnCPfEDp@Br@?BBrC@p@BvC@jA@N@lB@dB?p@@vC?RA\\Cr@Cp@Cp@EdBAHGd@[rCMl@Ml@Mn@Ml@?@kAhDITKPWf@eApBUd@Wf@eApBo@lAQ\\CFcBhEAFIVuA|Dg@tA_@fAELq@~B}@bCCJK^Ol@U~@EZm@rDAJGp@Gn@CZATCr@Aj@?DAp@AdB?LBb@Bp@Br@HbBB\\B^BNHp@V~AFb@BHNl@Nl@XlAn@fBd@jATh@LXHJX`@r@bAXb@Z`@DF~CxDpA`BrBdCnAvAtAzAx@z@tAzAvAbBnB|BZ^~@fA|C~Dt@|@rA`BZ^PRb@l@nAdBr@dA|@nAh@z@Xb@jAhBZh@R`@hAfC`@bAhAvCXx@d@tAhAlDPj@x@dChAfDPj@|AnEBDVb@Vd@n@jADFRXzAzBLLv@|@lBzB@@NVd@l@Z^pA~Av@lAVb@JPJRJTp@fBRh@z@|B@DXvAl@~CLlAP`B?FTvE?ZFnHBfD?tA?bB@|F?jE@p@?^APEp@K`CATUrCGp@ALYbCIp@]pCIn@Gp@]pCIn@In@W`B[lCIn@[pCIp@In@cAtIIn@Ip@S`BIn@In@S`BGp@In@Ip@q@rFy@bHS`BKz@Gd@In@e@`E]rCQrAUlBQ`B]pCe@bEIp@In@K~@MrA_@rDG`AI~A?BEdBG`E?FKvCEbBCp@EjEAdBCtBBlAFv@H~ARbCVtB@Fh@pCJ^p@fC`@vArA`FTx@j@xBpA`F~@rDV`AjAjEvCrKpA`F`BlGXdAz@vCb@xA|@xCZ`AlBbGd@tAnBbGPj@Rh@Pj@v@`CPj@Rh@v@bCPh@FRHVbArDNj@FVFTNl@FTd@rBZzAvAtGhAfF\\zA|@dEH`@Z|ALl@Z|Ah@jCLl@x@xDh@jCdAhFNr@Jf@\\|ALl@\\zAx@xDDRr@dD|@dEVnA\\zAv@xDNl@^zA|@nDJt@PdAd@rBd@lBHZvBvHPj@Nj@\\|ALl@Ll@j@hCNn@FVl@`Dr@dC`@xA|@hDVr@b@vA\\dAn@bBj@zA\\pAp@jC|@tBh@lA`@hAlAnE^v@BJf@hBJZPj@v@`C@D~@lD`@xAbBlG@D`AbFv@zDLl@f@jCLn@FTDVj@jCLl@\\zAl@rCP^Tf@l@lARb@\\d@t@bAh@t@z@vAx@pAd@bA`AvBNl@\\xAZrAHx@Fp@Fp@LnA@PDdBBlA?hA?p@?p@AhACZM`BEp@CZSbAKn@Y|AId@GVQdACXGp@M`BGp@ANA`@?r@AbB?r@?HBf@Dp@Bh@@FFn@Fp@NbBBPVhANl@Nl@Nj@^zAH`@DH`AxBTf@Rf@@BjAdBh@z@d@f@h@l@NNz@t@\\ZTRj@V^R`@PXLh@PhCv@b@Lt@TLDb@JzBj@n@XbBx@`Ad@bAb@^RbAd@^PdCjA`@R`@P^Rz@`@f@V`Aj@^R`Ah@^T^Tj@Zr@h@|@t@RPhBlBRN|@r@|AjAv@l@DBdBn@`@NbA^`@NB@fCjAZN~@f@@@X^r@~@\\b@v@`AFHLZp@xAxAjErB`GPj@d@tAXv@~@`DPj@t@bCPj@@FfAdDb@vAL`@~@pD@LJn@TxAVxCFp@JhA@XBfADlADnABTDn@LbBJtABJ^zANl@b@hBLZh@nA\\z@~@|AVd@p@hAn@hAXb@Vd@Vb@HNLVTf@j@vA"
                     },
                     "start_location" : {
                        "lat" : 44.8834167,
                        "lng" : -76.31787039999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 970
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 208
                     },
                     "end_location" : {
                        "lat" : 44.7681691,
                        "lng" : -76.6901323
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRd. 38\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "cghpGhl`sMJ@TDn@Jv@LLBRD\\HZHl@P\\JXL@@XLt@`@RLTPFDJHd@d@HF@@r@x@\\`@RVxAjBt@`ATZ|@hApA`BbApA^d@PNHJJHDDTNTNbAj@`@TbAd@^R`@R^RNFPH@@PFZHZH"
                     },
                     "start_location" : {
                        "lat" : 44.7756972,
                        "lng" : -76.68436699999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "40 m",
                        "value" : 40
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 44.7681915,
                        "lng" : -76.6906431
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMedical Center Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "axfpGhpasMCdB"
                     },
                     "start_location" : {
                        "lat" : 44.7681691,
                        "lng" : -76.6901323
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 353
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 44.76513629999999,
                        "lng" : -76.68942819999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eK&amp;P Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "exfpGnsasMjAi@bAWFAdBg@^MnA]\\IrBq@B?ZIHAVGXGDA"
                     },
                     "start_location" : {
                        "lat" : 44.7681915,
                        "lng" : -76.6906431
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "19.9 km",
                        "value" : 19935
                     },
                     "duration" : {
                        "text" : "1 hour 6 mins",
                        "value" : 3963
                     },
                     "end_location" : {
                        "lat" : 44.7148526,
                        "lng" : -76.91201199999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTrans-Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "cefpG|kasMdBMlBGvAHzBXrBp@nBz@`At@lA~@x@|@|@rAn@`Ap@lAj@pAzA|CRb@xAzC?@jBjERf@j@pA\\x@p@lBv@~BzAzEfBxFBJ`ArDPj@?BVzARrA@JNbBJnABdAB|@@r@?J?jCAbBAdDBb@JlC@HR~ATlBTrAJj@jAnDb@tAf@|A`@nAd@vATr@d@xAHV@FL`@@JLn@BRRhAJp@LrCHbBFdBLtCHbBHbBPhEHbBJlC@F\\nF@Hd@fDPfA@?H^ZpAp@dC`@xAz@`DDPNl@d@xBVrBx@xG?HRrCFp@Dp@Dp@XxD@LHbBNlCAjB?t@IpG@lA@rA@NNbBFz@RtAJn@Hn@BTv@bDjAbFNp@pArGLn@Ln@R|AhBdNRzA?Bn@~DV~AJp@XzAd@lCJh@~AtG|@tD@Bd@pA^fAx@pAr@fAJPLNnAdBt@`AHHh@|@Vb@Xb@f@rAh@rAHTV`Az@~CLdAFb@Px@Ln@t@xDHb@lApFLl@DPn@pBPj@b@vAx@jCN`@|AvEL^l@|A`BrEJVfAdE`@xANl@Tz@VjAf@xBNtB\\dEDn@XtCFn@D`@p@nEHn@BJ`A|Ev@xDFZT~@z@vDNn@Dn@VrCPlBLvAFp@Fn@XbDr@fBTf@Zv@XjALl@Nl@R|@VjAf@fCJt@\\nCJp@Dn@TfEDp@Dp@Dp@@r@?p@DvCD|C?j@?vC?p@?r@?p@?hE?r@?bB?dB?bB?jEA`GJbHFv@VrCDd@Fz@JbBHjAE|BCp@IhEEvCGvCCt@OvFCp@GbBC`A?b@@dB?p@?dB?p@?PR`CFp@Fp@Dp@BZXtB^nCHp@Hn@h@`EHn@Hn@Hp@\\nCJp@Hn@BNJdCDp@Bp@Bp@Dj@?DAdBAp@?LItAEp@KbBGp@KbBAVYxBg@`ES`BCVCXKbBCp@Ep@Ep@IrA?`A?p@?r@?p@?l@?BAr@Ap@CrA?N?f@CbBAp@?HMxAGp@Gn@_@dEGp@?B]lCIn@In@Ip@i@`EIn@?BEl@Gp@Ep@O`BEp@CVQtGK`EBXBdCHlHBvC@`A?b@BzF?dB@fAIrDOzFEdBAp@G~BE`FAp@GbJAn@DdBBr@@p@NrGRzDPbEz@~IDf@d@xCh@hDRbAfAfFLl@^fB\\nApA~ENl@^tAt@fC`@vAPj@Pj@xBtHnAtENl@Pj@Nl@`@vA^xA`@xANl@Pj@`ArDbApD^xA\\lAtAlFp@dCpA`F`ArD`ArDf@hB`@zBZjBDb@XrCJdARpDBp@Dp@?HHlCNfEDpABPJn@V~AHn@Jn@Lv@`@nAl@nBBBbAtBXl@xBdD@B\\\\x@z@jDnD@BfCbDnA|AlAnBr@fAjAhBt@jAJN`AxA`CzDf@fAvA~Cj@nAVf@`AvB?@Lj@BHJ\\~@xBj@pA~@xBh@nATh@~@xBFNf@z@fAnBVd@n@hAn@jArA~B`AxAt@dAlAfBX`@r@dADDdB~Br@bAZ`@t@bAxDjFPTv@xATd@n@lAz@pBVp@JVVjAVrAFZb@jDDh@JfBBfAHh@GhF?DQbDa@nDARe@nBeAtDyAvCc@x@e@r@y@hA}AxAsBxAIFw@^WNoCbAoBt@"
                     },
                     "start_location" : {
                        "lat" : 44.76513629999999,
                        "lng" : -76.68942819999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 976
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 183
                     },
                     "end_location" : {
                        "lat" : 44.7180758,
                        "lng" : -76.92268179999999
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eCamp Ln\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "yj|oG`{ltM}AhAIFcAz@cApAIJu@fAKTo@hAS\\e@fA[|@Qf@a@zA]xA?@Kn@Ox@MrA?BEp@Cp@Ep@EbAA^Cp@EdBGbBIvCCp@Ap@Ap@CdBAp@?r@Ap@Ap@Af@"
                     },
                     "start_location" : {
                        "lat" : 44.7148526,
                        "lng" : -76.91201199999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1615
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 352
                     },
                     "end_location" : {
                        "lat" : 44.7186332,
                        "lng" : -76.94306720000002
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eArden Gardens Trail\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans-Canada Trail\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Trans-Canada Trail\u003c/div\u003e",
                     "polyline" : {
                        "points" : "__}oGv}ntM?j@CdBAp@Ap@Ar@CtCEpC?\\ATEtCAr@Ap@EvCAp@Ap@E|B?XAp@?HCh@KfEOpF?HEdBAh@GpEAdBAjAGnDK|FAp@CbBK|FAp@GhEAr@A`@@`A@LD|B?JHzA@FF~AFt@Dp@"
                     },
                     "start_location" : {
                        "lat" : 44.7180758,
                        "lng" : -76.92268179999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "42.3 km",
                        "value" : 42334
                     },
                     "duration" : {
                        "text" : "2 hours 14 mins",
                        "value" : 8049
                     },
                     "end_location" : {
                        "lat" : 44.4767836,
                        "lng" : -77.3077601
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eTrans-Canada Trail\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "mb}oGd}rtMDb@Fp@P`BFp@Fn@BPF\\ZzANn@`@lBj@rBBJz@jCHTh@pAf@rATh@|@zBf@pAh@rAh@pAdBnEh@pAFNjArCJVFPTh@f@pATh@Rh@Rf@Th@p@dBJTTd@Vf@Tf@bArBVf@Td@`@x@`AxAr@dA~BnDr@dAB@~AxCP`@~AlD^dAz@~B\\`AFRNl@Nj@VdADTLl@Jn@Jn@@DJf@V~ALn@Dp@N`BDp@Fp@TrCFp@?BDl@L`BZfEDp@ZdEFp@Dp@L`BBZ?T@r@BbBDrDATKvCCp@MhEEz@Af@MtCCp@Ep@Cr@MtCA|@Cr@Ap@EpADbABp@Br@LxCHj@V|ALn@Fb@b@dB^zAd@nBJRhAnBn@hAfAlBZd@X`@Xb@Vb@lAhBr@dAr@dAjAhBXb@r@dArArBPXhAnBVb@Xd@|@zAFRRh@f@rAvB|F?@`@tAb@vAZfAb@vB\\fCLbBL`B@J?xA@tBA`@IbBIbBCp@IhBK|AKbBKvAMz@i@~Dg@pDQ|@e@lCKn@In@SrAAf@GdBCp@Cp@ChA@lA@p@Br@DbAD\\Fp@B^BPJn@Jt@b@rBFNd@fBJZZz@t@dB@BVd@d@z@JLX^t@bAZ`@LNfAhAZ\\rCpCn@p@zAjBp@z@x@hAXb@lAfBj@v@z@rAvCtEdBnC^h@l@|@lAfB|CnERZLZrAdC`BtCVd@@BpCvEd@x@HN~AvCdAnBTj@lCbHRh@vBxFv@rBj@~AlAhDlAjDRf@j@nAlBfE`AxBN^?LdAlB`BtCNXFH`E~E`BpBtBxC^h@rAvCVl@r@|BNj@HTPfA^zBL`AHp@Jn@\\pCHj@Np@ZzAn@tCv@rBt@rBjAzBf@`AFHlBbCt@~@LNbCdCpCrCpCrCx@z@vAvAx@x@@@X^lB`Ct@~@LNJRxBpDBBfAnBn@hAdBxCj@fAtBzDvB|DVd@hAlBb@v@JPn@jA|AxCfApBz@|ArAbCfAnBvBzD~@`BFNZ~@d@t@`BlC@BvBzDVd@fApB~AtC~AvC@B~@pBlBbE@@d@tARh@~AtEnAjDPf@|@zBr@lBx@~BRh@nAfDL^Tv@p@~B@Dj@`DDZFn@Jv@P|B?NHvB?pABhE@lAATChEAdBAbBCvCAr@Ap@?p@Ap@?b@?NAp@Cz@?f@AJDd@Bp@B`@@NHpAFbA@VPhAV|AF\\z@|CNb@j@bB`@dAnAfDBH~B`HL`@BH^zALl@Nl@Pt@Lx@RjAb@jC?@Fp@XrCVrC`@pEBLHfAN`BFn@Fp@N`BFp@Fp@N`Bd@rF@@P`BLfAFVX|ALn@Ll@DT|A`GLb@Rh@f@~AvApDJRTf@Tf@vA|Cl@nAj@nAvA~CTd@Tf@Vf@`AvB`AvBTd@bAvBr@~ANTx@vA~@|CPj@`@xAPj@Pj@`@vA`BlFNl@Nj@Pl@\\pA@FPj@r@bC`AdDVt@Pj@b@tAd@tAd@xARh@f@rAL\\^l@Vd@Vb@`BpCjAnBp@hAhAjBp@hAzBtDjAlBd@x@`@t@tB|DTf@Vd@Vd@l@jAVd@Vd@Vf@|AvCl@jA`AhB\\l@n@fAZb@pAbBt@`Af@p@l@f@|@r@xBfB^Xn@f@n@ZdBv@^N`@PdBp@hEdBdBp@`@P`A^b@T`Af@^RLFnAbAz@t@~@t@r@`AbAtAJNbBpCp@fARZ`AhCTb@|@fBZr@Tf@JTx@zA@@X^X`@pAbBX^RVbBxA^Z|@n@|@p@BBjBjApAr@^R`Ah@|@f@`@\\^X\\X\\XHFjApA\\^Z\\tA|Av@z@x@|@`AhAx@|@Z^Z^rAzA`EtEvAvA\\ZZ\\fBhBtBhAt@Z`@N@?tA^r@LfANlCXB@bBZD@bA`@fC~@`@N@@^NjG~Bf@NjD`AjCt@xBl@NFlDbAhCt@`@LpF~AdAXhCv@zAb@JBb@JfBd@dAVjCp@v@RrAXlDv@lCl@`B^h@JlDz@vG~A@?nEhAhCn@jCn@dAX|Bj@xCn@jCj@|FpA|@Rb@HjCl@jCl@dATbE~@n@PjCr@`@JhBf@n@Pv@TbAXb@LbAXjCt@HBx@\\dBp@`@N`@N`A`@`@P`@N`@N`@PfC`A`@PfC`AbA`@dBp@`@NhBr@\\P^PbAb@^R`@PbBv@bAb@`@RdChA`Ab@`@P^R`@PbAb@^Rd@R\\N`Ad@bBv@dChAbAb@tDdB`Af@`@T^RbCpA`B|@`B|@bB|@^R^R`Ah@`@R`Ah@~@f@`@R`Ah@^R`@RXPDB`B~@`DjBbFtCbE~B`DjB`CtA`Ah@`CtA^T`@T^Rd@X`@X~@n@^T^V^V|AfA~B|A|@n@~@n@^V^V|AdA~@n@~AfA|B|A|EdD~DnC|@l@fBlAr@n@\\Z\\Zd@b@TTvAzAXZlCzCx@|@Z\\^b@bDvDBBtApAPNdBbAh@Tx@\\HBhBd@~A`@FB~Aj@tAx@n@d@n@f@bBlBXZZ^r@x@BBZ`@nAbBZ^t@bAt@`AX`@pAbBpA`BjBdCX`@pA`BX`@pAbBjBbCh@t@JLt@`AlBbCt@~@lBbCX`@v@`AjBbCt@`Av@`AnA`Bz@dAVXpBzBv@|@dAhA`ClCNP|C~CNNhAdA`@Lp@TfB~@j@`@jAx@NPtAxA?@~A~Br@xANXrAxD\\`AFR|AtEb@tAd@tAjAlD?@Pf@v@~BjAjDJXhBbFf@pAxBzF\\z@rBbF|BtFvAfDfBlEJVlB`FtDtJrFrN~@dC|CdI~CnIjCbHdBpE^bAjB~EjCbHdBpEXx@~A~DdBnEpAdDbDjIpAdDdBlE^bAZx@z@|BbBpElAfDnAfDj@|Av@rBxBxFdBnEpAdD`DjIt@jB`ChGvApD|@zB|@zBf@rApAdDpAdDh@pAf@rAh@pAdBnEFNdAvCRh@f@tAL\\`@fB^xA\\zAn@jCHj@T~AN~@X`CXdE\\vFb@hHJ~AZ|Ff@zIXxFZvFb@dIh@xEFn@NlAh@vDHXl@fC@D`@pAPf@n@pAt@vAj@v@dGjI~@`AbBhBpDnBfAZdAXRFxBN`@Bd@?n@?|AQPAPElBWbASlASZErBS`B??@jBPJ@~Bd@RDp@TbA^hC|@^LfCfA`@P\\N^\\x@x@Z`@dCfD~AtB^x@P\\Tv@ZdAR~@\\xAT~@j@lCZ`AJXb@dA`AhBjAbBtAnBzCzDZ`@t@`AnBfCjCxDLPhApBdBjEpAdDDHzC`IxBxF`AfCL^Rd@d@tARh@x@|BRj@Rh@x@|Bf@rAn@fBdAzCFPDN"
                     },
                     "start_location" : {
                        "lat" : 44.7186332,
                        "lng" : -76.94306720000002
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 152
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 44.47565729999999,
                        "lng" : -77.3066846
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLouisa St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{zmnGndzvMv@{@xAuALMNMRULKLG"
                     },
                     "start_location" : {
                        "lat" : 44.4767836,
                        "lng" : -77.3077601
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 980
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 260
                     },
                     "end_location" : {
                        "lat" : 44.4726017,
                        "lng" : -77.3182623
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRiver St E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{smnGv}yvMn@rDNv@|@|E~@jFPjA\\dB@JRnAh@lDHb@TtAJl@f@jCTnAb@hCLn@b@lCx@~EV~AJn@V|A"
                     },
                     "start_location" : {
                        "lat" : 44.47565729999999,
                        "lng" : -77.3066846
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "13.3 km",
                        "value" : 13332
                     },
                     "duration" : {
                        "text" : "41 mins",
                        "value" : 2471
                     },
                     "end_location" : {
                        "lat" : 44.4304546,
                        "lng" : -77.4629863
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eCrookston Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "w`mnGbf|vMV|Af@tCd@jCp@|DJl@Ln@|@jFJn@d@lCX|AJl@d@lCJn@~@jF~@jFX|Al@fDBRLn@Jl@Jn@Jn@p@zDLn@nBfLJn@p@|DJl@jAzGJn@V|AbBxJP|@x@|EJn@V|AJn@X|AJn@tAhIX~AJl@PbAh@hDxBxMJn@Jh@n@`EJn@V~AJl@FZDRJn@Jn@b@lCJl@Ln@Jn@Jl@Jn@l@pDp@hEJn@Ln@n@zDJn@FV`AbG@DdAnG@DdChOd@lCf@|CfAzG`BzJLv@n@dEF^rAjIJn@d@lCJn@BPF\\~@hF?@l@~DHfAFlA?p@?vAA\\G|@I~@StAe@pBs@pBe@z@{@nAQPuArAeAx@qAnAo@v@c@v@Uh@Yp@]fAWfAYnBIv@EpACz@@b@BhD?FN~IVhPBbBJzFBnA@`ADt@?JBv@b@fDXxA\\rAXx@HTbA|B|AjDZx@^fAHT^jB@FTrAd@xCJn@V|ABRRjAZtBdB~K|@zF^~BV|Az@nD@F\\zA\\zA\\zAXrA~@|DLl@DRHXh@xBDJd@bBN\\^|@b@t@h@z@NRb@f@t@v@v@n@zBtA~@h@vD`Cf@ZtCdB|CnBxGdEjAz@d@`@RP~@fAt@hATd@p@vAv@rCP~@b@zB|DjW`@nCRtAx@lDVt@Vl@Th@p@dAvCtEr@fAp@fAT\\fBtCp@fAnEnHdCrDJNnD|FjAjB|BrDhAjB`AzAxBpGN`@f@~AhAlDhAjDf@|Ad@tAfD`K`FbOPj@d@rA|AvEn@nBpA|DDJZr@j@~@RTx@x@nErCLJ`Az@RZXb@JNb@lAr@zBhAlDb@vAPh@b@vAHVLf@FXBLD`@Hn@@HH|D@n@?@Dp@?@N|AP`BHp@?BDj@Dp@@^?v@ALAh@Gv@QpA_@jBKl@[|AMl@iBtJMl@[|AY|AWnAMt@ADGn@Ir@"
                     },
                     "start_location" : {
                        "lat" : 44.4726017,
                        "lng" : -77.3182623
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 726
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 132
                     },
                     "end_location" : {
                        "lat" : 44.4369259,
                        "lng" : -77.4619828
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eON-62 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "iydnGtnxwM[Kc@M_AUeASaAMeAQyAUoASk@G[EKAQCe@Ek@EQA{@Cs@C}MQ"
                     },
                     "start_location" : {
                        "lat" : 44.4304546,
                        "lng" : -77.4629863
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "25.0 km",
                        "value" : 24990
                     },
                     "duration" : {
                        "text" : "1 hour 14 mins",
                        "value" : 4467
                     },
                     "end_location" : {
                        "lat" : 44.35377310000001,
                        "lng" : -77.7345878
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSpring Brook Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yafnGjhxwM`@lCl@~Db@pCRzAvA`Kt@nFt@nF`BnL^nCtA~Jh@vDNtALbAHh@`@xC|BlOZzBBN`@zCZzBl@fEvA~J`CpPd@zC\\zBVvABXR~APnAVzABRR~AR`B\\nCFb@lDbThAzGV|AhA|GV|AV|A`BzJhAzGnApHfBrKtAhI|@lFt@nE`AzFv@jEFZNl@Pz@X~@Tt@HVN^\\|@BFn@jAl@lAVf@l@hAbBfDLXj@nAj@jA@@b@xAh@hBFXZ|AVvA?BT`B|@~Gh@~DrA`KzBlObA~GlCrQv@dFHn@x@lFdA~GnAlIx@lFdCjQdE~YpF~_@xC|SbC~PlCnR`A|GzDnXHn@vA~JfEp[R`BhAnIh@`EHn@h@~DhApIPvAT~A|@~GJp@r@nF^nC\\nCh@`EJn@\\nCJn@|@`Hh@~DL|@~@pGt@lFT~AJn@d@bDd@jDj@~D^pCr@nF^nCJn@tC~SHn@tA`K^nC^nC@Hj@rD`@nCn@jEFb@R~AHn@Hn@|@`HR~AR`BJn@x@lFb@zCZpB`@nCJn@`@lCV~AJn@T|AnAlIJn@Jn@T~AHn@Hn@Hn@Jn@Hn@^pCHn@t@nFHn@T~A|ApLJn@R~AhAnIj@~DHn@Hn@Hn@^pCJn@^nCR~AHn@^nCj@~DHn@Hp@Hn@Jn@D^BNBPF\\^nCHn@t@nFhAnILv@Ff@x@lFHn@dBlLJn@l@~DHn@dBlLJn@Jl@T~AJn@`@nCHn@V|AT~AdBlLx@nFHn@dA`H`AvF`@nCJn@Jn@?DZnB\\`CZzBZjB\\`C@HRzA\\zBZpBZrB\\|BNbAT|AV|AZtBRvATzARrARpA@FPfAJr@N`ADTVjBDZ\\zBZpBBRLx@TvAL~@TvAFb@F`@\\zBF^RrAXlBXnB`@tCZrBZxBZvBJn@RvA^vB\\~BJj@d@vCP`A`@fCFb@ZjB`@lCh@fDd@rCb@pCDVd@vC^~B`@fCl@|DrAjIl@~DDXJj@PfAF^Jl@b@nCV~AJl@PhATxAFXT~ADTDVF^H^FXHXPd@JXJXNVNZBDRZ@@^d@TTXXRNPNRLLFPJXL\\L^HTDJ@L@`@BR?^A\\CRCXEXGZIp@Yb@OtEkBTKl@Ux@[n@Wx@[fAg@|@[bAa@v@[DA|@a@x@[~@_@r@YBA|@_@l@WFEd@Qv@[~@a@bAa@z@[x@[ZORI`@Oh@Qb@Sv@[p@W`@Sh@SPE|@_@^Mh@QNENCTCLARAZ?Z@P@VBPBJBLDJD\\LRJPJPLNJRPRRPT@@X`@Zd@N^LZJXJ\\Lh@Jf@Hd@VpAZvBBJXbBTtAZjB\\pBBPZdBh@|C^rB@FRbABPNz@P|@BRTnAN|@zAdId@lCb@~BPx@N|@p@jDJh@P~@Nt@hAdGxA`IhDvQPz@Hd@TjAr@vDJf@Lp@F^DTFXF\\Jh@Hf@Lp@Jj@RbAP`ATnALn@Jn@Hd@P|@Jl@PbALn@Lv@\\fBV|AJh@Jj@Jh@Jj@Hh@Lp@Hd@Jh@P|@Lr@Jh@Lv@N|@Jh@Lp@P~@Jf@TvATlATjALr@DTF^P|@PbADVLn@d@jCFVx@rELl@@DJj@Jj@Ll@Hd@Nt@?@^jBTlAJn@FXLr@DLF`@BLDNRjADNTlADRH`@Lr@H`@?@Np@VvAJj@Np@"
                     },
                     "start_location" : {
                        "lat" : 44.4369259,
                        "lng" : -77.4619828
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "6.7 km",
                        "value" : 6660
                     },
                     "duration" : {
                        "text" : "19 mins",
                        "value" : 1146
                     },
                     "end_location" : {
                        "lat" : 44.3162358,
                        "lng" : -77.7862349
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eCounty Rd 38\u003c/b\u003e",
                     "polyline" : {
                        "points" : "azumGdpmyMr@zD@JH`@X|AV|A@BJj@Lv@RtA@@Hl@V|AV~Az@lF@LF^Jn@b@nC@HHb@Jn@Jn@?BJj@?BHh@Jn@Hb@@JJn@Jl@Jn@V~A`@lCF\\BPJn@Jl@Jn@V~AHl@Jn@Hb@@Jb@lC`@nCNz@lAtHXfBfA~Gd@~CxAfJVzA^~Bh@~CTrAXdBlB`Lf@tC|@nFb@hC\\tBRnATtAJn@X|AFd@Nx@Jn@BTDV@Fr@jEh@fDHf@f@`DLt@FXFVFVFRHVDLLZDLLXP^T`@FHHNLRV\\BDLNJL\\^\\X\\Zz@t@LJn@h@FFTPDDd@\\RJLHb@RXJXJRFTFl@J`@DP@`AFf@@b@BR?T@V?N@L?V?\\?d@?RAb@CB?bAG\\C`EYxE_@|Cq@`@I\\Id@Gn@@bAJz@Jh@FZD`ADJ?b@?\\?z@GPCjBUnDg@jBUfAIdAIPAtB?F@v@Nr@\\XTRRh@n@N`@Rh@DHL^nBjG`@lAHTZh@jArARN|@r@^VzC~BHFPRtAxAXd@Vd@^l@l@v@xC`C\\XFDpBbB^ZxAnA^X\\XtD~CxBjB|@r@ZX\\PD@`@HdATTFRJt@h@FF`@^Xb@~@lBLTl@fA@BLTzBvDx@rAVb@`BpC`A`B"
                     },
                     "start_location" : {
                        "lat" : 44.35377310000001,
                        "lng" : -77.7345878
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1362
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 224
                     },
                     "end_location" : {
                        "lat" : 44.30823729999999,
                        "lng" : -77.79788499999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eFront St N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "oonmG|rwyMl@|@l@pADHb@lAzAzEJZz@pCLXFLDFHLXb@Xb@HTNT\\d@JRDFLRN`@Lb@XfAtAtGFXDRf@bCTjAj@nBnC|GJZLXJNLJ`@Xf@NbCx@^Jh@PpH~BdAVHB"
                     },
                     "start_location" : {
                        "lat" : 44.3162358,
                        "lng" : -77.7862349
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 191
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 44.3084827,
                        "lng" : -77.8002626
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBridge St W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Rd 8\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "o}lmGv{yyMElAI`BEp@Cp@IbBEp@Ep@"
                     },
                     "start_location" : {
                        "lat" : 44.30823729999999,
                        "lng" : -77.79788499999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "11.1 km",
                        "value" : 11090
                     },
                     "duration" : {
                        "text" : "32 mins",
                        "value" : 1927
                     },
                     "end_location" : {
                        "lat" : 44.2131159,
                        "lng" : -77.82616209999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGrand Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Rd 30\u003c/b\u003e (signs for \u003cb\u003eON-30 S\u003c/b\u003e)\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow County Rd 30\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "__mmGrjzyM`APd@\\HJz@n@VTp@h@p@f@\\VHF\\^?@h@~@h@x@b@n@n@d@t@PnBb@p@JzAVhBXzBr@xAb@nEnAxC|@hWhHzI`CjEhAbBf@dAXNF`AVl@P|C|@~@Z`@Lb@LjFrBhAf@jBr@d@PJDnAZJ@j@H|B^bCP\\?b@?b@?`A@~BQZAFA|Fe@tAMPCdASbDeAjAa@r@SjA]r@MtAI\\@pALbCj@|Cz@~Bj@dCr@b@Jz@TpB`@x@LxGfA~@P|@Pb@JB@`@LRHVJZNZNPJn@`@x@h@d@ZBBxBzAVPjAv@p@b@XRRJZPD@b@R^N`@Rf@Pr@XdAb@z@\\dA\\h@NXH`@Jh@JxBd@v@NbARjB`@|@PtDt@r@Jd@Fn@DR@R?j@?n@Ch@C`@C|AIxAIl@CRAv@GvBKp@EnBITAvBClBAf@?rCCh@?vAAbAAl@?N?R?N?h@@V@`@DPBTDTDPDPFVHVLNHNJPLJHPL\\X`@\\f@b@f@d@\\\\xArAb@b@LLHHZTb@^ZXPNDDTPNJRJ`@Pb@Nb@LNDLBPBX@V@V?TAZCz@KHC`@I@?RCr@S^KFAZIfCm@xBk@z@S|A]t@Kv@Kp@GfAEfA@fAD\\B\\Dv@JD@x@PDBv@RdA^j@V^Nr@\\PFHDh@V~@d@fAh@HDx@\\j@VHDj@Tb@N\\Hf@L^H^Hz@PlATRDb@HVD~@PbAPvAZ`APhAT`APFBb@Hx@Nl@Lx@N|@PTDj@J|@Rt@Nf@Hn@L\\Hd@HXFpAV`B`@`AVlA^LDv@Z^N@@d@Np@Tr@Xn@Tl@Tn@TTHh@Pr@VdA^j@Tf@PXJVHHB|@ZjA`@`@Nr@VrAb@hA`@nHnClI|CbBr@tFtBhFlB`NfFbA^`@Nd@PtA`@t@Hj@?xAAv@Kz@Sr@Wj@YtBeArFqCzC}A"
                     },
                     "start_location" : {
                        "lat" : 44.3084827,
                        "lng" : -77.8002626
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1360
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 251
                     },
                     "end_location" : {
                        "lat" : 44.2091046,
                        "lng" : -77.8422051
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eNorthumberland County Rd 29\u003c/b\u003e (signs for \u003cb\u003eNorham\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_kzlGnl_zMPfAbA|GXlBF^t@zDLl@zAdIf@jCt@xDzAfIdClMLl@ZzA?D`@pBXzALn@BNn@zDLrADn@Dn@?LFrA?r@@dB"
                     },
                     "start_location" : {
                        "lat" : 44.2131159,
                        "lng" : -77.82616209999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3232
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 595
                     },
                     "end_location" : {
                        "lat" : 44.1899455,
                        "lng" : -77.8719547
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eNorham Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{qylGxpbzMv@HHDDDFHFJDLHXDLRr@P^BHf@bAx@|@HHnAfA\\ZZXvBpB\\ZxAtA\\ZvAtA\\ZpDhD\\Zz@v@DFh@l@FFRVhA~B\\t@dBvDj@nAlD|HdBxDvA~ClD|Hj@nAlBfETf@dBzDFHdApBFLnDdJ`@dADLPh@`ClHHVzEbNRh@nDbK|@pBVd@v@rApE|Ft@`AfCbDvEdG"
                     },
                     "start_location" : {
                        "lat" : 44.2091046,
                        "lng" : -77.8422051
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 244
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 44.1885453,
                        "lng" : -77.8695931
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003ePlatt Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003ePuffer St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ezulGtjhzMv@{ATe@Vg@l@kA`BoDHMVc@"
                     },
                     "start_location" : {
                        "lat" : 44.1899455,
                        "lng" : -77.8719547
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2240
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 418
                     },
                     "end_location" : {
                        "lat" : 44.1697852,
                        "lng" : -77.8780038
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eGravel Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mqulG|{gzMZ`@X`@HLl@n@r@v@^T`CtANHpDnBlA@N?NC`@Ib@Gb@I@?@A`AQf@I\\IB?^GBAdAS\\?b@AN?\\LVFXFFB`@P`@NfC`A`@N`@NfC`A`@N`@P`@NdBp@fC~@`@PhDrAfDtAfCbAbA`@hEfBbA`@bA`@fDtA`C~@f@RjDrA`A^j@R|B|@FB|Al@FBf@RVTNl@"
                     },
                     "start_location" : {
                        "lat" : 44.1885453,
                        "lng" : -77.8695931
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "11.5 km",
                        "value" : 11518
                     },
                     "duration" : {
                        "text" : "37 mins",
                        "value" : 2248
                     },
                     "end_location" : {
                        "lat" : 44.0922951,
                        "lng" : -77.93882219999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCounty Rd 25\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "e|qlGnpizMfEJxABt@BjBFp@@xA?jAEf@C\\Ex@KLAv@MXGVG`AWBA`@KdAYzBm@zDeAd@MTGHCfBe@rA]pBi@~Ac@nA]n@QLEZILEb@M`@Kf@OrAa@tAa@`A]f@O~@[@?bBm@r@WbC{@v@WBAz@YlCaAzBw@JEhDmAhC}@nAc@dBo@|Bw@dBm@dBm@jDmAhFiBhAa@bA_@t@Wn@UzBy@`Bm@LAL?NCZM`A_@\\MfA_@PGnA_@bB_@\\Eh@EfAEP?fBDr@Dj@Jj@Lp@RzDtAjA`@j@RtNdFhC~@xKxD~EbBtBt@`A\\pBt@f@RPFTJJF^Rv@d@VTh@`@h@h@v@~@nA|A|AtB`@h@dB|BnAbBx@hAxBhDf@t@tAxBXb@p@fAXb@|A~BpBtCfBhCLLj@z@BDlGbJvCbE`AtAjA`BxB|CxB|C`AtA|AzBHL~@nANThBhC`@l@dBdChAzAbBxBx@`ADFrAxAj@n@LN|@`A`A`AhAjAvAxAHHdCjC~BbCx@|@f@j@@Bl@t@p@`AHNNTZf@Zh@@B\\p@P^N\\t@hB\\`ARl@l@xBJ\\DVJTNh@Pr@Pn@Tv@BHj@zBPj@lAvEf@tBFXRfAT~ABTHn@Db@Fd@VtDXfFDt@?@Bn@Bb@N`CFpA@NB`@@RJbBDz@?NDt@DdANhCLdCBd@DjAx@rQBp@@X@VDp@@PD|@JfBJpAFj@Ff@Hh@Jn@BTFVLr@XvAH`@BJR|@`@`BFRPj@Tt@L^L\\DJRh@FL\\|@^x@^v@^t@R^Vd@pBpCbBzBX^@@V`@r@dAFHPVbAtAJLZ`@HJPPZ\\\\\\NPj@b@`@\\x@l@LJ`BhAjClBBBrBfB?@Z^dAnApAjBb@l@p@dAl@~@v@lARX`@l@hAhB|@vAxCtE`BbCbCjDvArBdCfDr@bAx@fAp@`A@@t@fAV`@DFl@nA"
                     },
                     "start_location" : {
                        "lat" : 44.1697852,
                        "lng" : -77.8780038
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 967
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 209
                     },
                     "end_location" : {
                        "lat" : 44.0849195,
                        "lng" : -77.9325116
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003ePercy St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Rd 25\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRegional Rd 25\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow County Rd 25\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{wblGrluzM`@U~@k@~AcA~@k@\\YZU^a@rA_Bt@}@Z_@v@_A`DwDb@a@^a@v@q@rAiA`FyCPMj@]lAs@xA}@t@e@XU"
                     },
                     "start_location" : {
                        "lat" : 44.0922951,
                        "lng" : -77.93882219999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1769
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 410
                     },
                     "end_location" : {
                        "lat" : 44.0709919,
                        "lng" : -77.933691
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eOld Shelter Valley Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wialGdetzMX`@X`@PVFJVd@n@hAVb@Xd@Vb@hArBTV@BTf@Vl@JFl@h@\\X\\Z\\XzAnA\\ZzAnA\\Xz@t@\\X^ZzApA`@FXBVK^Q`@Q^Q@A`@M`@O`@O`@M`@O@?^Q`@QdBs@`@QVKFC`@Q`@O`@O`@OdBo@`@Q`@O`@ObA_@dBq@`@Ob@O`@OJEt@[`@O`@Q`@O`@O`@Q`@O`@O`@QdBq@`@OzB}@HI"
                     },
                     "start_location" : {
                        "lat" : 44.0849195,
                        "lng" : -77.9325116
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "12.9 km",
                        "value" : 12900
                     },
                     "duration" : {
                        "text" : "34 mins",
                        "value" : 2069
                     },
                     "end_location" : {
                        "lat" : 43.99574459999999,
                        "lng" : -78.00561499999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eShelter Valley Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ur~kGpltzM|@hFLn@Jl@X|AJn@d@jC|@hFLn@V|APdALn@b@jCJn@V|AJn@z@jFLr@VvALl@Jn@Jl@X|A\\hB^~BJn@p@zDJn@Lv@Hd@r@xDX|ALl@tAfILn@n@zDvAdIT|AJn@b@lC@L\\`CHl@Jn@T~A^nCJl@bAlHj@lDn@|DV|AV|AJn@Hh@@BJn@V|AJn@V|A@JFb@Jl@V~A@HFd@Hl@Jn@T~AHn@T~AT|A@BHj@Hn@Jn@T|AHn@Jn@Hn@`@lCHn@Jr@v@lFHn@Jn@Hn@Jn@Hl@Jn@Hn@`@lCHn@Hb@TjBHn@P`BHn@Hn@Fh@@DJl@Jn@Fb@Xt@JRDDHJTPPJJDVHHDNFt@SnEqA`@M`@Mb@KbA[hCu@jEoAfBg@jCu@`@M`@KdA[`@Mb@K`@MfBg@`@M`@MdAY`@MLETCNCXE`@D`@Lh@d@JNJLLT?@Ph@b@tAPj@BH^jAb@tAPj@\\dAj@dBPh@Pj@Rh@Pj@hAjDhAhDPj@@@jAdDRh@rAtDdBzDL`@VdA|AzG`@zAt@fClA`G\\jA|@|BtBtFJVpDtGNZb@f@X^jAjBr@dAxCpEt@hAdDvDh@p@r@x@bBjAlAz@ZJ~AN`@EjBa@hD{@LCTGh@IbBQjBFN@R@b@DhAL^Bb@D`@Bd@FnC@P?PAfAI`@CF?VGB?b@GzBYh@GpASb@GpNoBt@MNE`@KBAnAq@h@m@bAkAR]pAsCj@mATg@Tg@Tg@v@eB`@w@Te@nAeCl@_AbAo@v@MvF}@`AUd@O^M@A^UpBgAPI|BgAf@UJETG\\KjAKJA~AEhB^f@LZL`@P|@^~@|@p@l@bBzAf@d@TLNHp@Pn@FXCb@E^ErAUx@[ZKf@_@nBwBZ]`@e@p@y@t@_Ad@m@NSXa@vAkBl@{@@C\\e@z@kAHMjA_A\\Y@?PMVM^C`@A\\@D?b@H|@\\DB|@ZnAh@r@d@HD`Av@f@f@DFjAfBVb@zJpOt@dA|@lA`AfBr@lBRv@bAlDzA~D~@~ATX~ApBxEpFp@r@Z^xN|ODFZ^vBjCfAvAHLd@z@@@Rj@j@bC@HHb@jA|HTdBTjBNlAXz@b@Zx@V"
                     },
                     "start_location" : {
                        "lat" : 44.0709919,
                        "lng" : -77.933691
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "14.4 km",
                        "value" : 14374
                     },
                     "duration" : {
                        "text" : "42 mins",
                        "value" : 2520
                     },
                     "end_location" : {
                        "lat" : 43.9591607,
                        "lng" : -78.1759886
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCounty Rd 2 W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "k|okG`nb{MA~A@|B?Z@p@DlAFhBJvBLnBLpAFl@D^TnBBPRvAZdCJ|@~@lHZnC\\tCP~AHn@Fd@@HHn@Fn@PrA@LHn@@HDd@Hj@@J@@D^D^@NL|@j@tE?@\\pCBNb@bDd@hDR~A@FZfCHr@Z|BTdB@DFh@Fd@Hn@h@bEz@lGl@nENlAnBfOl@vEDXRdBLbAFj@@\\B^?Z?\\AP?HAVA\\C^E^G^Ih@Ox@m@rCI^c@xBGZ]fBKx@A?ALANC`@C\\C|@?t@Bt@Dn@?DDZDl@BPNnANvA^jDD^J~@Fn@r@pGt@bHj@lF?BFn@Fd@TdB?BJj@Ln@Ln@Nn@Nl@Nf@DPTr@Vz@Pj@HVX|@Rl@f@bB^dAHX|@rC@Fb@tAZ`AHX^fA|@vC\\dAb@tARn@Nd@Rh@d@jA`@x@d@`AN\\h@bA`AjBv@|Ah@fAj@lAVj@@BRh@N`@Pn@DPFXDVBPJl@PnAj@`Eb@|C`C~PtA|J^hCnArIxBzOVhBRxAn@lEx@bGBNh@rDF`@|@pGj@~Db@|Ch@pD\\|BNjALbA^fD@DP~AP`B`@pDBLXpCHp@Hl@Jz@LdALx@PnATbBlAnIl@xDHn@Jn@d@bDPhAJl@`A|GJl@Jn@DX`B`L|BpOtFt_@V|AHn@v@lF\\|BbEjY^pCV`BJt@Jv@RtAT|A`A~Gb@zCPlA`@vCx@vFBLF`@l@`Eb@vC\\~Br@|Eb@|CPjANbA\\~BJn@DZZpBHn@PhANbAp@jE@Nl@|D`@rCj@|D`@nCDVZxB`@lCHl@r@zE^dCJp@^fCBNRnAFb@PhABRf@fDLr@PlARtAb@rCVdB^hCj@zDd@|Cv@rF\\vBb@|Cr@|EV~A`@tCZlBXjBXhBT~AFb@TvARtABLRtA\\vBZvBdBfL^lCHf@^fCXjBJp@PnA\\fCp@pEl@jEl@rDRrAZxBRrALbAJp@XpBN|@dAjHPrAPtA?BBR@XB`@Dz@LzCFzADt@BRDx@\\jIBt@FvAL~DBp@BbD@|E@vC?rC@`@@z@"
                     },
                     "start_location" : {
                        "lat" : 43.99574459999999,
                        "lng" : -78.00561499999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 840
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 196
                     },
                     "end_location" : {
                        "lat" : 43.9584024,
                        "lng" : -78.18641649999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eKing St W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wwhkG|vc|MB`AD~ABp@?B@jDJxBZhHVbELpBB`@BXB\\FzAFhADzBFtCDvBH|H"
                     },
                     "start_location" : {
                        "lat" : 43.9591607,
                        "lng" : -78.1759886
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 750
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 136
                     },
                     "end_location" : {
                        "lat" : 43.9648032,
                        "lng" : -78.18936529999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBurnham St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_shkGbxe|MWHa@LeBl@a@Lc@Ns@TODi@TcA`@uDrAgBj@m@R}Aj@a@NaBj@yAb@{D`Bc@R"
                     },
                     "start_location" : {
                        "lat" : 43.9584024,
                        "lng" : -78.18641649999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 367
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 59
                     },
                     "end_location" : {
                        "lat" : 43.963605,
                        "lng" : -78.1936338
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_{ikGpjf|Mv@hEHf@HVNf@Jd@Np@FXFb@L`AHd@Jj@BN~@fF"
                     },
                     "start_location" : {
                        "lat" : 43.9648032,
                        "lng" : -78.18936529999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 461
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 84
                     },
                     "end_location" : {
                        "lat" : 43.9621058,
                        "lng" : -78.19899649999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eKerr St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "osikGdeg|M`BrIF^`AfFJn@H`@FXDf@h@rCn@lD"
                     },
                     "start_location" : {
                        "lat" : 43.963605,
                        "lng" : -78.1936338
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 653
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 157
                     },
                     "end_location" : {
                        "lat" : 43.967693,
                        "lng" : -78.20146280000002
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ejikGvfh|M[PIDKBYJC?WHUBMBG@KFg@XQFcCv@oEvAUHSFQBc@JSFiDjAkDlAsAd@OJ"
                     },
                     "start_location" : {
                        "lat" : 43.9621058,
                        "lng" : -78.19899649999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 337
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 63
                     },
                     "end_location" : {
                        "lat" : 43.970578,
                        "lng" : -78.2027614
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRogers Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "amjkGbvh|M{CdAgA^WHoAb@uAf@_DfA"
                     },
                     "start_location" : {
                        "lat" : 43.967693,
                        "lng" : -78.20146280000002
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7.6 km",
                        "value" : 7556
                     },
                     "duration" : {
                        "text" : "22 mins",
                        "value" : 1324
                     },
                     "end_location" : {
                        "lat" : 43.9479034,
                        "lng" : -78.2914316
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eElgin St W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Rd 2 W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow County Rd 2 W\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "c_kkGf~h|Md@`DXtBj@zDjAhIfAjHZvBd@|CLz@NbA`AlGl@`E\\nCL~@l@|DJv@\\|Bx@rFNdA`BbLbAhHDTj@|D`@pC|@nGn@jEhA|Ht@fFbBlLx@pF~@nGb@`Dl@dERrAfA|HJr@Jn@z@bGlAhI\\xBBPxAfJ|A~J`@hCV`BT`BHl@`AtG@DHn@j@|Dj@fEJn@T~AjAjIZxBNdAd@dDj@~D~AdLD\\fBdMBTlA~Hh@jDbA`HRrAVdBRtAj@jDZlBBPr@rE\\~BL|@DZZpBJn@`@tC~AnKN`AF\\Z~AVlAFP?@Rv@J^Ld@`@lAXv@Rh@@BXn@Zr@d@|@jAxB^t@`@r@h@fAXr@Tj@Rf@@BZ|@Rt@BHX~@Px@Rx@?@Nx@TvAd@rCz@jFh@dDd@rC`@hC\\rBH^^~Bh@|CZjB`BpJV|AX|AJl@Lr@XnBDXN~@Jp@"
                     },
                     "start_location" : {
                        "lat" : 43.970578,
                        "lng" : -78.2027614
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 106
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 43.9479129,
                        "lng" : -78.2927555
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRobertson St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "kqfkGlhz|M?n@@x@?`@?jAAP?FAV"
                     },
                     "start_location" : {
                        "lat" : 43.9479034,
                        "lng" : -78.2914316
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 154
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 43.9492941,
                        "lng" : -78.29285109999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eQueen St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mqfkGvpz|MoADkBFwAB"
                     },
                     "start_location" : {
                        "lat" : 43.9479129,
                        "lng" : -78.2927555
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 592
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 278
                     },
                     "end_location" : {
                        "lat" : 43.9493724,
                        "lng" : -78.29972359999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAugusta St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "azfkGhqz|MYzFBXFfA@VCr@Gf@Cf@Ep@En@CZStBHn@v@jFl@zDHn@BJBVKPeAp@"
                     },
                     "start_location" : {
                        "lat" : 43.9492941,
                        "lng" : -78.29285109999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 574
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 191
                     },
                     "end_location" : {
                        "lat" : 43.9473751,
                        "lng" : -78.3063221
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSherbourne St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qzfkGf|{|M^zBV~AXzAh@~AVrALl@Jl@v@xDX|AZzANl@v@tDh@fC"
                     },
                     "start_location" : {
                        "lat" : 43.9493724,
                        "lng" : -78.29972359999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 114
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 43.9483454,
                        "lng" : -78.3067836
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVictoria St S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cnfkGne}|MaEzA"
                     },
                     "start_location" : {
                        "lat" : 43.9473751,
                        "lng" : -78.3063221
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1164
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 161
                     },
                     "end_location" : {
                        "lat" : 43.9464645,
                        "lng" : -78.3197321
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eStrachan St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "etfkGjh}|MFf@BRHVNf@p@nBFJJ^Xh@DHNZ\\r@H\\Vz@v@lF@BHh@Hd@^zBN~@@H\\bCrBdMnApHL|@H|@D`@HnACr@E^G`@Mr@Of@Ur@CDWh@s@z@MHa@Xe@^"
                     },
                     "start_location" : {
                        "lat" : 43.9483454,
                        "lng" : -78.3067836
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "21.0 km",
                        "value" : 21023
                     },
                     "duration" : {
                        "text" : "1 hour 8 mins",
                        "value" : 4096
                     },
                     "end_location" : {
                        "lat" : 43.9007621,
                        "lng" : -78.5514147
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLakeshore Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "khfkGhy_}Mv@nCJ\\b@dAf@j@p@j@n@d@xBfB|@p@|AlA~@t@JNb@r@LR|@tAdAPfAN`@FF@FBJHBHBH@HBT@^E|BClBKjD?H?h@?VBTP`Bn@rFFl@t@bHv@~Gh@|Dx@jG^nBJl@b@bCf@jA^jAh@jBNh@Ln@f@`C@Ft@xERrBPbBJ~ADn@n@hK^tFFl@FjAPnCR~CDn@^rFBr@LtC@n@@p@@`A?p@YrDw@zKA\\Ap@@fE@xF@fEXdEb@nEXpCFp@h@pFN`B`@`EP~AN`BN`BVpC^`EJlATrAHXPl@JXPpA?xAEd@Gj@OzAIn@Cp@Ep@MrCEp@GbBE|AAt@AbBHpBd@pDn@rEFVNl@h@vB\\r@|AfDl@x@Zb@bCfD~ChEt@`AX`@bCfDxDjFZ`@FHbA~AVb@DHx@nBRf@@@`@tAPh@ZdABRt@vDBPRdE?^?bB?p@?dH?DLnDb@hGRrCFp@RpCDp@L`BRpCFp@b@lGBv@F~D?^BbABx@Bh@?D@p@@T@lA@j@?D@h@?F?p@@h@?FBtC@h@?FBbB?@@f@?FB`B?@Fn@Fh@BZNhAFh@@Dd@xD@DHn@Ff@?@P~A?FLhADTJl@DVX|A@FDL`@vAHTh@jBHTFTHTX~@Nj@HTFTHTFTPj@Pj@FTDNVhAH\\VhC?V?X?V?X?hA?X?V?\\DvB@V@X?V@X@VBjABbB@V@V?N@H@VFp@FfABXDn@BV?BLj@P|@vAxEJZPh@Rh@Ph@Rh@d@tARh@d@rAPh@Rj@Ph@Rh@\\dAlA`DtBzF`AjC`A|Cl@pBP|@Nl@ZrA`AhE|@rDj@fCNl@T~@FXJn@`@lBDZJn@T|ANdA`@lCbAzGv@lFBRPx@j@fCx@vD?B^fBHZPj@Nl@`@vAVz@Nj@Pj@p@dCNj@LGNCf@K@?PCXCXAL@N?HBPBVHJDHFRLJHHHHHNPRTXZ@BX^VZJPPVNTHNPXFPDJHTHZBN?@DNBLDZD\\Df@Ft@@H@RDr@Dl@BZ?HFt@J~@@R@LFl@Fn@Fn@Dd@Hv@j@rFDf@P~Ad@`EFf@LjABPD`@@LF`@@LBRDZ?@Fb@BTBLDTDT?@DPFXDL@DHVDLDL@@HRN\\HPHNHNJNJNNRLPLLTV^`@FFHHHJLLHJHJHLHLFLDJ@?r@|AlAlCHN@@DJHRLX@BJVHN@@DJDJXl@Xp@Th@DJDH^z@Vl@LX?@DHFNFLLVFNHL@DR^Td@JRJRNXFJDHFJDHFHBDFHJJFHFFTVNTHHFJFH@?FHJHFBD@JBH?L?b@AL?L@J@JBJBLDPFPHND@@NDTFXHZHTHNDj@P@?JFPJHDNLJHJLHH@@NRFJBDJPJPJVDL?@FPHTDXDRJf@D\\DZDPBR@D@H@D@HDX?DBN?F@F@N?P@^?RAR?X?FAh@?d@?X?R?R?R@\\?T@^@f@@FB`A@NBz@?@HtBDjAFlAFx@BXBXF^HZRr@v@jC`@vALf@Rn@`BzF\\jAh@nB^pALb@`AzDPp@Jf@Nj@DLh@~BZtAjBhIf@vBTz@pA|E@DNf@FTzAnF@FLb@`AnDbAlDBJLf@p@jCH\\FVRbAZ~APt@J`@BJLf@?BJb@BHDTBJBJFV@JPx@Bh@?h@ANKbBMxBCZGfAOpBIzAAPI~@ItAK`A?BEVSbAiAnC}@`Bg@`AyAvCo@jAWd@EHg@~@CFS\\Yh@k@hAeAnBS^CDm@jAo@hAEJIL_@p@U^ABMPORWXGFWP[VC?_@TKDu@`@_Ah@GB{Av@a@T_Af@]Rc@TaCpAWLIDULmBdAE@GBgAl@]ZCFEJCF?H?J?JDTFZBNBLFXd@tB\\bBNl@F\\jAtFt@fDLj@?@h@fCLl@Ll@Nl@Jj@@@v@vDLj@?@Lj@Ll@@?Ll@Ll@v@tD?@\\xA?@F\\BLFXBP?BDVDj@N~BNnCJvBFlAt@dO@J@XRbE@H@ZBTJ|B@TP`DBl@?P@XA^?LCx@Et@AVKlBCj@Y|FB\\J`ADX?@BRDXXtB\\lC?@DXNbADXBTXxBBT@?Hn@DXBTb@bDJjADX\\fDBTB^RpBFr@D`@@HL`B@B@VBT?BFj@HjABT?BBTJjAHfAFr@LpAT`DFn@L`BTrCDn@TrCBXHdAN`B\\bE\\bEDn@Fn@Fx@VnD?J@p@@p@@bB@p@BbBBp@FvBFfB@v@@p@@P?R?@?H?N?`@@L?b@?fE?p@?p@@p@?bB?p@?p@?p@?bB@rC?bB?p@?p@@bB?LEb@Cd@AHGZER[xAMl@c@pBWbA]xA"
                     },
                     "start_location" : {
                        "lat" : 43.9464645,
                        "lng" : -78.3197321
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2193
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 346
                     },
                     "end_location" : {
                        "lat" : 43.8983372,
                        "lng" : -78.57210429999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eLakeshore Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wj}jGham~M`A[JE`@OTIJEDANEf@ODA`@MDA`@ORILEHCVIPIVIXKhAa@`@EH?D?N@@@N@f@TPNLT@DJ`@D\\BT?RD~ABlBBjB@h@LzIBjBD~D@`@?\\@p@@t@D~C@FBlC@`ABbBF`E@d@?NFxA?P@\\?DBtA?@BlB@v@BvABtA@t@@j@@t@@|@B~A@R@hANxG?T@Z@d@?H?BAdAEn@CNAHGh@Q|A[xCGd@m@zFGd@AHAFCVELEFIFOD[JEB}@XGBMDOJA@GHEDEF"
                     },
                     "start_location" : {
                        "lat" : 43.9007621,
                        "lng" : -78.5514147
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 409
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 62
                     },
                     "end_location" : {
                        "lat" : 43.8973644,
                        "lng" : -78.57696799999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBoulton St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "s{|jGrbq~M@Z@H@H?@Fb@p@vEZrB|@rG@Hd@nC?@Hl@@^?RCLEJ"
                     },
                     "start_location" : {
                        "lat" : 43.8983372,
                        "lng" : -78.57210429999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1205
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 217
                     },
                     "end_location" : {
                        "lat" : 43.9063069,
                        "lng" : -78.58372989999999
                     },
                     "html_instructions" : "\u003cb\u003eBoulton St\u003c/b\u003e turns slightly \u003cb\u003eright\u003c/b\u003e and becomes \u003cb\u003eMill St S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ou|jG`ar~MqAd@_@N_@Ny@Zm@RA?_@Nc@NQHODa@Na@Ne@P]La@Na@LcA^A?]Lu@Tu@VgA\\KDODaBf@[JG@}Bz@k@RKDyAh@i@RYLWJIBiBt@[N[PCBOHOPCBSXA@QTMVELIRGNGXERCRANAN?b@Ad@ALE`@AJAXKp@I`@ERABAFA?KRKNU^KPGP"
                     },
                     "start_location" : {
                        "lat" : 43.8973644,
                        "lng" : -78.57696799999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 611
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 110
                     },
                     "end_location" : {
                        "lat" : 43.9015297,
                        "lng" : -78.5870209
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003ePort of Newcastle Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mm~jGhks~Mb@?R@XFNDFBHDTNNLd@`@`A|@|A|Az@v@hD~C\\XtCjCTPNHPFNBPBP@X?\\ELCNE"
                     },
                     "start_location" : {
                        "lat" : 43.9063069,
                        "lng" : -78.58372989999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 605
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 104
                     },
                     "end_location" : {
                        "lat" : 43.8998019,
                        "lng" : -78.59418509999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMilligan St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qo}jGz_t~Mz@hGh@pDr@~Dj@vDh@pDXfBT|A`@lCJn@Jn@"
                     },
                     "start_location" : {
                        "lat" : 43.9015297,
                        "lng" : -78.5870209
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 292
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 73
                     },
                     "end_location" : {
                        "lat" : 43.90222420000001,
                        "lng" : -78.5955675
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eToronto St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wd}jGtlu~MQPCBMJQJOJMFc@Ra@Pa@P_@Pa@PoAj@a@Na@PqAf@"
                     },
                     "start_location" : {
                        "lat" : 43.8998019,
                        "lng" : -78.59418509999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 294
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 51
                     },
                     "end_location" : {
                        "lat" : 43.9016984,
                        "lng" : -78.59909499999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{s}jGhuu~MDX?F@F?F?DAFCPEN?DAH?H?R@F?DBNBH@F@@?BBTBLBRBPHn@NfAJv@Bb@FX@R@J?J?r@@J@LBLBPBNBJDJ"
                     },
                     "start_location" : {
                        "lat" : 43.90222420000001,
                        "lng" : -78.5955675
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "53 m",
                        "value" : 53
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 43.9018601,
                        "lng" : -78.5996378
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "sp}jGhkv~MQRGFA@CF?FALAJ?H?HBP"
                     },
                     "start_location" : {
                        "lat" : 43.9016984,
                        "lng" : -78.59909499999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 586
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 123
                     },
                     "end_location" : {
                        "lat" : 43.902697,
                        "lng" : -78.6065662
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "sq}jGvnv~M?@AB?DFh@@D?B?@?B?DEPENCHAHAHAJ?BCh@AFCTCDCDEDGDUVGFCDCHAF?FAJ?J?JBJ?@@FJ^@B@D@F@H@T?@@TAR?F?@AFCJEVCJAF?HAL@B?J@d@?\\?RCp@Cp@AJEhAEz@CTEPAFCLG^ADEZALCNC`@?BAZAPAV?LAH?@CPEX?@AL?J?LAH?FEh@"
                     },
                     "start_location" : {
                        "lat" : 43.9018601,
                        "lng" : -78.5996378
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 203
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 44
                     },
                     "end_location" : {
                        "lat" : 43.904447,
                        "lng" : -78.60725819999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCobbledick Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{v}jG`zw~MS?I@k@LE@]Ja@NgC|@eA\\"
                     },
                     "start_location" : {
                        "lat" : 43.902697,
                        "lng" : -78.6065662
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1307
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 215
                     },
                     "end_location" : {
                        "lat" : 43.90141759999999,
                        "lng" : -78.62214449999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eService Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ya~jGj~w~MRxCJbBVnEXdEXvDfA`Pn@rIf@dHb@nF^dERpBb@tDPzAFb@HZLZNTPNTNNDH@J@H?z@]"
                     },
                     "start_location" : {
                        "lat" : 43.904447,
                        "lng" : -78.60725819999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1729
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 309
                     },
                     "end_location" : {
                        "lat" : 43.8953098,
                        "lng" : -78.6411255
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{n}jGj{z~MDTHn@Hb@Pn@@DFRJN@@RN`@^DFX^\\b@PZN`@DP@L?J?TAn@Cl@AR@V?H@TBZHz@Bd@D\\Hp@BNX|ANz@F^Ln@Ll@F^DLLj@J`@@JFZN`ADXBT@L?Z?ZAl@C`@Et@Ch@Cb@@J?B@B@FDDD@L@J@DDFDT`@FHV^@@LXJZH^^~ALd@DLF`@Hl@XbC@L?R?h@BX@H@FDJFHFDHJNRHPFRD^X~@Nj@DPLVRf@Tf@DHr@|AJVRz@FRTz@JZPj@`@rARl@@FVr@f@tAHVHZDNXzAHb@XfB?@Jn@V|A"
                     },
                     "start_location" : {
                        "lat" : 43.90141759999999,
                        "lng" : -78.62214449999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 176
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 43.89379599999999,
                        "lng" : -78.6404649
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBennett Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uh|jG`r~~MjDkA`Cy@"
                     },
                     "start_location" : {
                        "lat" : 43.8953098,
                        "lng" : -78.6411255
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 876
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 149
                     },
                     "end_location" : {
                        "lat" : 43.8936705,
                        "lng" : -78.6511895
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePort Darlington Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "g_|jGzm~~MRx@H`AFt@BbB?nA?F@bB?DE~D?L?tA?bB?PB`ADt@JdBNfBPvBTlD?@FpBCzACf@En@a@lC]`BMh@E`A"
                     },
                     "start_location" : {
                        "lat" : 43.89379599999999,
                        "lng" : -78.6404649
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "20 m",
                        "value" : 20
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 43.8935006,
                        "lng" : -78.65111089999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLambs Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eS Service Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "m~{jG|p`_N`@O"
                     },
                     "start_location" : {
                        "lat" : 43.8936705,
                        "lng" : -78.6511895
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 844
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 178
                     },
                     "end_location" : {
                        "lat" : 43.89071089999999,
                        "lng" : -78.66072269999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eE Beach Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "k}{jGlp`_NDVHVNh@Tt@J^JXHZHb@Rx@`@pBBJp@|CHVZjAd@~ALPBBJD@@LNFN@BJVVzBXdCHn@Jz@D^V|A?BPx@Ll@Jl@H\\?DBHDNBRBHBVAV?FCT?RAH?LBXDXD\\F\\Lv@"
                     },
                     "start_location" : {
                        "lat" : 43.8935006,
                        "lng" : -78.65111089999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 807
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 126
                     },
                     "end_location" : {
                        "lat" : 43.8939635,
                        "lng" : -78.66699009999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003ePort Darlington Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}k{jGnlb_Nh@zDHn@jApI@N?HAHAFELGDIFKFYJQFa@NODQFOFYJEBCFCHAFA@AJ?F?@@L@HJt@?H?JAHCHCJEFGFODQHuAd@c@N[JOFQLOJOLm@p@KJ?@]^MJKFWLqBx@w@H"
                     },
                     "start_location" : {
                        "lat" : 43.89071089999999,
                        "lng" : -78.66072269999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 511
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 84
                     },
                     "end_location" : {
                        "lat" : 43.8952873,
                        "lng" : -78.671583
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "g`|jGtsc_N?P@J@JAD?@CJ?@GRGTCLCLALAJAN?LAP?R?JAB?FAB?DEJELIRGPEN?@ELALCL?H?F@NFXBNDLHNDFDF@DBD@F?J?H@L?LBFBJDJDRBJ?DAF?BABCFCDCFA?CFCBGBGDC@EBKDMFA@IDOHOHIHEFCDADCJ?F?H@F@@JVDL@@@D?FAFAJGJ?@CBCBKFA@E?C?SGMCIC[@Q?"
                     },
                     "start_location" : {
                        "lat" : 43.8939635,
                        "lng" : -78.66699009999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 208
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 34
                     },
                     "end_location" : {
                        "lat" : 43.8951159,
                        "lng" : -78.6741646
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eW Beach Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qh|jGjpd_NDpA@h@BpA@XP~F@Z"
                     },
                     "start_location" : {
                        "lat" : 43.8952873,
                        "lng" : -78.671583
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "54 m",
                        "value" : 54
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 43.8950715,
                        "lng" : -78.6748351
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eW Beach Rd\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "og|jGn`e_N@h@@b@Dp@?F"
                     },
                     "start_location" : {
                        "lat" : 43.8951159,
                        "lng" : -78.6741646
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 133
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 43.8939752,
                        "lng" : -78.6754244
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "eg|jGvde_NLLLLZRB@?@PFNFB@VD\\FPDP@D@D@BBDDFH"
                     },
                     "start_location" : {
                        "lat" : 43.8950715,
                        "lng" : -78.6748351
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1264
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 266
                     },
                     "end_location" : {
                        "lat" : 43.8915855,
                        "lng" : -78.68809279999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "k`|jGjhe_NMx@EXELCHCFIL?@GHKNED?@O^O^EJCDCBC@CBCDADCJA@CFGJMNA@MNGHELIRCLCHITAJCJ?@GZADABEJGPCFAD?@EHEFEFABED?@EDEHEHEJALAL?H?B?T@ZDl@?HB^Bj@Dl@LrB@F@TFx@@LDt@Dd@Dr@@ND`@FbABh@Fh@DZDL?@FPDZDb@@J@B?@BPJ`@FZJ^Lb@HV?@@FHX?BBF@@DPFVFRFP@D?B@?FTBN@BBDDNBLBD@@DJLX@@LLDDJDRFPDZF@?t@XJBL@RBHDB@DHLXHRBDHJHJJHFD~@r@ZVTT?@VVJTHNBF@DJh@Lp@Hh@"
                     },
                     "start_location" : {
                        "lat" : 43.8939752,
                        "lng" : -78.6754244
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 202
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 62
                     },
                     "end_location" : {
                        "lat" : 43.8933028,
                        "lng" : -78.68888889999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBowmanville Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mq{jGpwg_NcCl@cBr@}Ar@OH"
                     },
                     "start_location" : {
                        "lat" : 43.8915855,
                        "lng" : -78.68809279999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.0 km",
                        "value" : 2992
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 636
                     },
                     "end_location" : {
                        "lat" : 43.8814396,
                        "lng" : -78.72087209999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eEnergy Dr\u003c/b\u003e (signs for \u003cb\u003eKingston\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "c|{jGp|g_NLd@Nb@h@|ALf@Jb@d@lC@\\@T?`@A\\Av@AnAHnAH^JVxAbEjD~IRh@HPf@pARh@j@xAlBzERh@h@rAd@nA|@|BRf@@@vBtFTh@x@xBdAjCXr@bCnHfAbDRp@@DlC|Ln@`ENz@Db@b@hDTdCPbCRpCzBv]X`E\\dAXx@b@bAl@z@f@f@f@`@d@Vf@Nj@PRFd@Lx@Tb@ZFNHJFNDHBH@L@RBX"
                     },
                     "start_location" : {
                        "lat" : 43.8933028,
                        "lng" : -78.68888889999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 103
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 43.8809853,
                        "lng" : -78.7210525
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit\u003cdiv style=\"font-size:0.9em\"\u003eRestricted usage road\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "_ryjGldn_NA@A@A@A@?@ABA@A@AF?DAB?D?B?D@B?D@B?B@B@BBB@B?@@@@??@@@@??@@?B@@?B@@?B?@?B?@AB?@ABABC@?@A@A@A@A@A@C@A\\e@"
                     },
                     "start_location" : {
                        "lat" : 43.8814396,
                        "lng" : -78.72087209999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1811
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 353
                     },
                     "end_location" : {
                        "lat" : 43.8797421,
                        "lng" : -78.74239039999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "eoyjGpen_NHPFLBF@B@N@N@L?LBV@ZBXB`@@T?@B^@R?NC\\E^Eb@EXCLEVIj@Gh@Id@EZAFEVELGZEPELI^Sj@ALYlC?@Ch@AFEx@C\\@J?D@J@DDFDFVHHDHDFJBP@JB^?BA\\CRA`@?NAH@j@Df@?BFp@Fn@Fj@@BFl@?@Db@@L?BANIRSb@CFQZCJKVEN?@CNAV?H?PBjA?LCLAHCFABEFONGDCBCDAF?H?L?@Dr@D^Fn@Fn@Fp@Fn@N`BFn@Fn@Fp@N~AXpCFn@Fp@N~AFp@N~AVpCHn@@PD^Fn@Fn@Fp@Fn@Hn@Fn@Fp@Fn@Fn@Hn@@HDf@Hl@Jn@\\tBLl@"
                     },
                     "start_location" : {
                        "lat" : 43.8809853,
                        "lng" : -78.7210525
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 708
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 93
                     },
                     "end_location" : {
                        "lat" : 43.87366369999999,
                        "lng" : -78.73977839999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCrago Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kgyjG|jr_NhEyAB?~@]bA]~@[`Bi@`@MdBm@`@MhC{@~JgDFAB?D?D@"
                     },
                     "start_location" : {
                        "lat" : 43.8797421,
                        "lng" : -78.74239039999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1331
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 237
                     },
                     "end_location" : {
                        "lat" : 43.8762084,
                        "lng" : -78.7516126
                     },
                     "html_instructions" : "\u003cb\u003eCrago Rd\u003c/b\u003e turns slightly \u003cb\u003eright\u003c/b\u003e and becomes \u003cb\u003eOsborne Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "kaxjGrzq_N@?LJFP^vBHl@DVDV^xB\\nBHd@Lv@Ln@VzAzBrMLn@TvA@DDn@?@@d@ALA~AAlAIvBEbBEtAEn@CLCJIRMPIHKFcAZeAZ_Cp@oBn@mA`@aDdA}C`AA@G@GB"
                     },
                     "start_location" : {
                        "lat" : 43.87366369999999,
                        "lng" : -78.73977839999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 786
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 112
                     },
                     "end_location" : {
                        "lat" : 43.8761728,
                        "lng" : -78.7609554
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eEnergy Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "iqxjGpdt_NBPn@pEt@lF`@lCFb@VlBHl@@HFj@DVBZBl@@`@@h@Ab@Ah@Cb@Ch@E\\G^Gb@I`@Ov@UnAEP{@tEc@xBQ|@?@"
                     },
                     "start_location" : {
                        "lat" : 43.8762084,
                        "lng" : -78.7516126
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 117
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 51
                     },
                     "end_location" : {
                        "lat" : 43.87516770000001,
                        "lng" : -78.76136629999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCourtice Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "aqxjG~~u_NVHnDfA"
                     },
                     "start_location" : {
                        "lat" : 43.8761728,
                        "lng" : -78.7609554
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 2032
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 384
                     },
                     "end_location" : {
                        "lat" : 43.87424439999999,
                        "lng" : -78.7841834
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDarlington Park Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yjxjGpav_NGl@Kn@Gd@QhACRCHWpASfAY|@Ul@Wl@O\\Wd@EHMVeBpCu@dACB[p@GZOl@WdAERE^Cx@CdA?F@\\Dt@Fj@@HD`@@BL`ABLL|@RzAPjAj@bEXzAT|@@Dl@~BFRp@bCV`AN|@Fj@Bf@NvFDfCFdDPvC?X?D?N@NF|@F|@RbAJl@Rh@LXJXZVVv@@FFz@@t@@X@p@?b@?LCp@Al@IdBABAl@Ap@AFDpBNhA@LL\\BHXLDB\\B`@O"
                     },
                     "start_location" : {
                        "lat" : 43.87516770000001,
                        "lng" : -78.76136629999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 536
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 108
                     },
                     "end_location" : {
                        "lat" : 43.87373119999999,
                        "lng" : -78.79055489999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_exjGbpz_N@`@?F?VCn@AT?BCTAR?F?J@T?JCt@?H?ND\\@V@P?DAV?P?@G`@AL?BBPBNBRANAR?@Eh@AV?RBJ?FH^FR@L?R?@A^?L?@?FBJFLBHFPDL@L?NAJCRAJ@L@N@D@F?N?N?LBZ?J?D?DBNDVDT@P?H?F@T@JBBBDHFNF@?"
                     },
                     "start_location" : {
                        "lat" : 43.87424439999999,
                        "lng" : -78.7841834
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 826
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 121
                     },
                     "end_location" : {
                        "lat" : 43.8759555,
                        "lng" : -78.80021189999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yaxjG|w{_NSt@Gd@Gl@?@Gp@En@Gp@?FOvAQ`B?HInBARAv@GtCAZ?BEvASjBCNMl@Kb@CHGXAHi@hCCHI`@?@Sh@Qh@CFGNGPUr@Qh@O`@CFGLGRMZGVENATAXERMNGTETAZAX"
                     },
                     "start_location" : {
                        "lat" : 43.87373119999999,
                        "lng" : -78.79055489999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 284
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 43.8775457,
                        "lng" : -78.80293929999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eColonel Sam Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "woxjGht}_NA@oA~AGFk@x@A@W`@A?iA~C{@~BUx@"
                     },
                     "start_location" : {
                        "lat" : 43.8759555,
                        "lng" : -78.80021189999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 2032
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 346
                     },
                     "end_location" : {
                        "lat" : 43.8805287,
                        "lng" : -78.8224498
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit and stay on \u003cb\u003eColonel Sam Dr\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "uyxjGje~_NA?A??@A?A??@A??@A@?@A@?@?@?@?@A??@?@@??@?@?@?@@@?@@@@@?@@?@??@@?@?@?@?B@RNb@`@\\\\j@dATf@Jf@DPB\\Bb@@~@Ch@Gh@Kf@IZIVU`@S\\GFYXWXqCjC}D~CsBjAa@NeBl@a@LaBj@aA\\UH_@XYXe@h@S^MZQf@@PIRCF_@dAcA|CGf@Ef@Ep@Cp@Bf@?JBb@DVJ|@nBhMJn@Jn@VbBLr@f@pDlAlI@DHf@t@rF^lCb@hD"
                     },
                     "start_location" : {
                        "lat" : 43.8775457,
                        "lng" : -78.80293929999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 845
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 141
                     },
                     "end_location" : {
                        "lat" : 43.8741144,
                        "lng" : -78.8190134
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ilyjGh_b`NXENEFEBEDGDQDGDEFC\\EVEHCFGB?FGFEPKTEPEJAPB\\@ZBFBHBFFb@p@LTXXLJHBF?HAt@Ud@Ob@KFALCLEXIf@QdAYHCVIf@Q|@[@?`@QBAHGJKBCHM^m@x@sAJSdAkBd@}@Ta@Ve@NULOJSDI"
                     },
                     "start_location" : {
                        "lat" : 43.8805287,
                        "lng" : -78.8224498
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 598
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 127
                     },
                     "end_location" : {
                        "lat" : 43.872134,
                        "lng" : -78.8251528
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "edxjGxia`NJULUHGHELA@@H@FFFHBHDNPhAF`@@LXfBHd@T~AT|AJj@T`B@DHf@XjB`@nCN`ABLJt@D`@DRNt@BR@D?DF`@@F@FDT"
                     },
                     "start_location" : {
                        "lat" : 43.8741144,
                        "lng" : -78.8190134
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "8 m",
                        "value" : 8
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 43.8720659,
                        "lng" : -78.8251219
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eFarewell St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 56\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ywwjGdpb`NJE"
                     },
                     "start_location" : {
                        "lat" : 43.872134,
                        "lng" : -78.8251528
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 873
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 159
                     },
                     "end_location" : {
                        "lat" : 43.8686889,
                        "lng" : -78.83472189999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHarbour Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mwwjG~ob`NNbALhA@FJx@ZtChBxPRxADL\\xATt@@Dl@vAlArCTf@Rf@~@xBTf@Tf@Rf@BFP^@DNVDFFJT^n@x@"
                     },
                     "start_location" : {
                        "lat" : 43.8720659,
                        "lng" : -78.8251219
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 248
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 62
                     },
                     "end_location" : {
                        "lat" : 43.8673548,
                        "lng" : -78.83224539999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSimcoe St S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ibwjG~kd`NfDyHbBsD"
                     },
                     "start_location" : {
                        "lat" : 43.8686889,
                        "lng" : -78.83472189999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 668
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 117
                     },
                     "end_location" : {
                        "lat" : 43.8662412,
                        "lng" : -78.8399747
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}yvjGp|c`NJN@Bh@xAFN@DCDK\\ALAJ?PI`@OdAM|@AV@TDfA@d@Hd@Jl@Lr@VjADXTbANt@TvAF^D^@V?NAPAPELAJ?H?P@^C~@?FAH@L@TDR@J?H?Z@NDXHVDPHPHNX\\"
                     },
                     "start_location" : {
                        "lat" : 43.8673548,
                        "lng" : -78.83224539999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1078
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 227
                     },
                     "end_location" : {
                        "lat" : 43.8719776,
                        "lng" : -78.84842429999999
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eJoseph Kolodzie Oshawa Creek Bike Path\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "_svjGxle`NJJHLBF@F@H?PEVS`@KPEVA\\E\\C^ETCPAP?T@FBLDh@BR?PALARCf@Ad@Cd@CLINCDCBCDOVMZQ`@IRKROZMXKXGJEHA@CBGFKFOHODG@A@E@MBM?O@G@EBCDCDIFEHEJCDCHAJAN?LALCLCDAFIPABELCRC\\CVANADAFAFGJEH?@ABGHEBEBMAK?I?GBCBEHEHGFIBMB]HWHQBU?[?A?E?O?MBMBQDA?ODU@K@G?KBMHQHA?SJSZ[l@c@l@A@_@Vg@Ve@PGDi@`@A?GFGHCLCLAJGJGD"
                     },
                     "start_location" : {
                        "lat" : 43.8662412,
                        "lng" : -78.8399747
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.4 km",
                        "value" : 3406
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 671
                     },
                     "end_location" : {
                        "lat" : 43.894981,
                        "lng" : -78.86714549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eJoseph Kolodzie Oshawa Creek Bike Path\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{vwjGrag`NO?U@KDGFIJIJMREHEL?@GPGNCRCPAXAP?LBF@FNNHR@L?FQjAERI\\GJKDGFMV[n@[t@Wf@Ol@IXSn@M`@KZMVINSVULMJEJQf@C@E@SCY?SC[SYGMCOESOY[MMIEOEc@A_@?[?A?UL_@RSLO`@Wh@WjAC`A?Z?|AEVI\\Wr@CPGf@?RBJBBBFPNNR@J@L?LGj@CPKRQVUNm@`@E@YRc@\\A@a@\\WTm@b@OLURSPQNM?UFKLMTKJQNIF_@NS?MFk@VYJg@Ri@RGAMIUOEIC@GCc@OS?ODSHKDSJWHIDSHEJQd@AHG\\ENABGDSRCBYJA@MDM?M?SBk@L[FWHc@Ro@\\s@`@c@\\_@XCDKNIVEJI\\CFEFMHYHEDGRAP@NFL?T?NETa@xAI\\Gb@Ip@KZIHOF]Hq@^UTGJSVWLa@JCAGAGAYGSA[LQLEFa@b@mAdAYNYH{@TE@y@d@w@V_@JI@MAI@SFYHm@Fq@P[HEAE?GAG@_@LIBWH[HGBGDQRENCHCBK@OBA@c@JC@SBW?UA_@C]AQBKDKFG@A?wAN_C`@qC^SDA?KFA?WNA?o@TqA`@WHsAn@{@^aAb@"
                     },
                     "start_location" : {
                        "lat" : 43.8719776,
                        "lng" : -78.84842429999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "36 m",
                        "value" : 36
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 43.8950647,
                        "lng" : -78.8667174
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eJoseph Kolodzie Oshawa Creek Bike Path\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "sf|jGtvj`NG_@CICQ?O?I"
                     },
                     "start_location" : {
                        "lat" : 43.894981,
                        "lng" : -78.86714549999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 204
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 42
                     },
                     "end_location" : {
                        "lat" : 43.8965942,
                        "lng" : -78.8680193
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eJoseph Kolodzie Oshawa Creek Bike Path\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cg|jG~sj`NE?KAE@SFKHU^o@h@c@XQLMLKXEHOLw@h@UT"
                     },
                     "start_location" : {
                        "lat" : 43.8950647,
                        "lng" : -78.8667174
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 187
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 77
                     },
                     "end_location" : {
                        "lat" : 43.8970998,
                        "lng" : -78.8657942
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKing St W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "up|jGb|j`N[yB]aCCOKw@[yB"
                     },
                     "start_location" : {
                        "lat" : 43.8965942,
                        "lng" : -78.8680193
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "64.9 km",
                  "value" : 64909
               },
               "duration" : {
                  "text" : "3 hours 31 mins",
                  "value" : 12640
               },
               "end_address" : "Toronto, ON, Canada",
               "end_location" : {
                  "lat" : 43.6532565,
                  "lng" : -79.38303979999999
               },
               "start_address" : "Oshawa, ON, Canada",
               "start_location" : {
                  "lat" : 43.8970998,
                  "lng" : -78.8657942
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "4 m",
                        "value" : 4
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 43.8971109,
                        "lng" : -78.8657456
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eKing St W\u003c/b\u003e toward \u003cb\u003eCentre St N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 2A\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{s|jGdnj`NAG"
                     },
                     "start_location" : {
                        "lat" : 43.8970998,
                        "lng" : -78.8657942
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 220
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 43
                     },
                     "end_location" : {
                        "lat" : 43.8952749,
                        "lng" : -78.8647555
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCentre St S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 2A\u003c/b\u003e (signs for \u003cb\u003eON-401\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}s|jG|mj`Nh@c@b@Yz@_@~@]dDiA"
                     },
                     "start_location" : {
                        "lat" : 43.8971109,
                        "lng" : -78.8657456
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "80 m",
                        "value" : 80
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 43.8950464,
                        "lng" : -78.8657003
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBagot St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mh|jGvgj`NT|AT|A"
                     },
                     "start_location" : {
                        "lat" : 43.8952749,
                        "lng" : -78.8647555
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "40 m",
                        "value" : 40
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 43.89535679999999,
                        "lng" : -78.8659425
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eQueen St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ag|jGrmj`Nm@d@OH"
                     },
                     "start_location" : {
                        "lat" : 43.8950464,
                        "lng" : -78.8657003
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 107
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 43.894981,
                        "lng" : -78.86714549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eJoseph Kolodzie Oshawa Creek Bike Path\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_i|jGboj`NJT?@Ld@HRHN@D@JHf@?H?NBPBHF^"
                     },
                     "start_location" : {
                        "lat" : 43.89535679999999,
                        "lng" : -78.8659425
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 600
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 99
                     },
                     "end_location" : {
                        "lat" : 43.8897661,
                        "lng" : -78.86547089999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eJoseph Kolodzie Oshawa Creek Bike Path\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sf|jGtvj`N`Ac@z@_@rAo@VIpAa@n@U@?VO@?JG@?REpC_@~Ba@vAO@?FAJGJEPC\\@^BT@V?RCBAb@K@ANCJABC"
                     },
                     "start_location" : {
                        "lat" : 43.894981,
                        "lng" : -78.86714549999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 510
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 109
                     },
                     "end_location" : {
                        "lat" : 43.8855491,
                        "lng" : -78.86345009999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eJoseph Kolodzie Oshawa Creek Bike Path\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "af{jGdlj`NBIDOPSFEFCZIVIHC^MFAF@D?D@ZIp@Ql@GXIRGHAL@HA^Kv@Wx@e@DAz@UXIXOlAeA`@c@DGPMZMR@XF"
                     },
                     "start_location" : {
                        "lat" : 43.8897661,
                        "lng" : -78.86547089999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 127
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 49
                     },
                     "end_location" : {
                        "lat" : 43.885281,
                        "lng" : -78.864891
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eSinclair Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ukzjGp_j`N@`@APAX?H@PDZNfADf@@L@LBF@@FBF?"
                     },
                     "start_location" : {
                        "lat" : 43.8855491,
                        "lng" : -78.86345009999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "84 m",
                        "value" : 84
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 43.88506,
                        "lng" : -78.86589099999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSinclair Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_jzjGphj`Nj@fE"
                     },
                     "start_location" : {
                        "lat" : 43.885281,
                        "lng" : -78.864891
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 734
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 137
                     },
                     "end_location" : {
                        "lat" : 43.87878500000001,
                        "lng" : -78.863057
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCubert St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "shzjGxnj`NlC}@nCeAlDoApCcAfBo@`DiAb@M`@M~@YZKDA\\KBCRGx@YdBm@"
                     },
                     "start_location" : {
                        "lat" : 43.88506,
                        "lng" : -78.86589099999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7.7 km",
                        "value" : 7662
                     },
                     "duration" : {
                        "text" : "23 mins",
                        "value" : 1399
                     },
                     "end_location" : {
                        "lat" : 43.8590214,
                        "lng" : -78.9500108
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBloor St W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 22\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Durham Regional Rd 22\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mayjGb}i`N^dCBPPjAR`A`@dDLz@DTVdBRzAPpAPvAHh@Dd@LdAP|AXxBThB\\fDJ~@Hn@h@|DXrBVlBh@~Cr@xDJf@BJN|@BJFT@Bb@vA^xATz@DLDTd@jCN`AHh@^hC^zCLdA@JHn@t@nEjApH\\tB~@rGjAdINhAh@pDdArHn@vDh@xCDPHZHVPl@\\`AZ~@h@jARb@hAbBZ^X\\lAzAn@x@r@~@@Bh@x@h@bAj@nADJHd@l@nBPh@f@|AHVNb@DJ~AhFjAlDzAxEJ^d@zANf@nAbEBFLd@FZBH?@FXNt@D\\NbAT`BTzAN~@BJHNf@bDPbA@JHp@D\\N`B?D?j@Gf@GXELS`@UZMFMJ_@NiAZOFsA\\o@NeA^CBYR[^Ud@Mj@Gn@An@@D@\\pAfJHn@XrBT|AJn@XtBnAjIHn@V~AbA~ETpAHz@Ft@F~@NxGHjBBPP`B|@nGV`BJl@?DVdB?j@\\dCf@dDJp@Jn@Jx@b@zCBRb@hDHh@j@|DXrBRhANbAL|@N|@HXDLDNV|ALl@TpA@JVbB@FBPTnBF^l@hFP~Ab@~CTbBLbAVdBPnAZvBn@|EFf@RzAZ|BDRT|A^jCNbAC\\?@Jv@@LN`ABTHt@Jt@^dDd@hDr@lFb@|Ch@|DNrA"
                     },
                     "start_location" : {
                        "lat" : 43.87878500000001,
                        "lng" : -78.863057
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "12 m",
                        "value" : 12
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 43.85891489999999,
                        "lng" : -78.949969
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBayside Gate\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{eujGp|z`NTG"
                     },
                     "start_location" : {
                        "lat" : 43.8590214,
                        "lng" : -78.9500108
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1420
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 272
                     },
                     "end_location" : {
                        "lat" : 43.8553591,
                        "lng" : -78.9669555
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVictoria St W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 22\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "eeujGh|z`Nh@vEj@hEJn@Hn@R~A@DFh@d@jDBV^nCp@jFJvA@D?DAFAHJv@H|@Db@RvBP|ANvAVnB\\fC^lCLdAZ`C@Hd@dDb@zC@BXpBXnBZdC\\`Cf@lD"
                     },
                     "start_location" : {
                        "lat" : 43.85891489999999,
                        "lng" : -78.949969
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 147
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 64
                     },
                     "end_location" : {
                        "lat" : 43.8541462,
                        "lng" : -78.9662343
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eEastbourne Beach Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWaterfront Trail\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePartial restricted usage road\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_otjGnf~`Nv@k@NKBANGFCFCDCXK@?`@Q`@Q^S"
                     },
                     "start_location" : {
                        "lat" : 43.8553591,
                        "lng" : -78.9669555
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 241
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 51
                     },
                     "end_location" : {
                        "lat" : 43.8526032,
                        "lng" : -78.9654706
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWaterfront Trl\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mgtjG|a~`NBo@?A?C@M@EBIDIHMBEBM@KJc@@CFO?ADGFE@?DAFAH?L?J?b@Bf@JNDFBBBJFB@H?H?HATAB?FZ"
                     },
                     "start_location" : {
                        "lat" : 43.8541462,
                        "lng" : -78.9662343
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "85 m",
                        "value" : 85
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 43.852157,
                        "lng" : -78.9661193
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eWaterfront Trl\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "w}sjGd}}`ND\\PAFh@@TBH@BBD@@B@VFB@HB"
                     },
                     "start_location" : {
                        "lat" : 43.8526032,
                        "lng" : -78.9654706
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "92 m",
                        "value" : 92
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 43.8514016,
                        "lng" : -78.9660519
                     },
                     "html_instructions" : "\u003cb\u003eWaterfront Trl\u003c/b\u003e turns slightly \u003cb\u003eleft\u003c/b\u003e and becomes \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_{sjGfa~`NBAZKj@WLEJEJ@HBB@HHHFBH"
                     },
                     "start_location" : {
                        "lat" : 43.852157,
                        "lng" : -78.9661193
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 771
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 127
                     },
                     "end_location" : {
                        "lat" : 43.8478715,
                        "lng" : -78.97140030000001
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "gvsjGx`~`NDPBVDTBFJXJh@BRBND`@?@BlA?d@?`@ALC`@?HEd@?@En@?DAj@?@?XBT@HBPFZBR@R@BDj@Bh@@FBJFTBHFTHRRh@Rh@HPJTDLLRHNHJDDB@HFFDLFRJLBFBNDJ?D@TAF?HAb@KXKPIJGBCZSLIPMPMLEPIHED?HA\\AN@HBBB@@DF@FDRBAJCF\\"
                     },
                     "start_location" : {
                        "lat" : 43.8514016,
                        "lng" : -78.9660519
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1001
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 179
                     },
                     "end_location" : {
                        "lat" : 43.839262,
                        "lng" : -78.96773639999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHalls Rd S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "e`sjGfb_aN|KoDb@O`@MdPiF`@MbA]vIqCb@MlEwA"
                     },
                     "start_location" : {
                        "lat" : 43.8478715,
                        "lng" : -78.97140030000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 147
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 43.83829950000001,
                        "lng" : -78.96884679999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kjqjGjk~`N@JBJ@BB@DADA@@BDDV@HFHRXFF\\b@VVl@h@FDH@"
                     },
                     "start_location" : {
                        "lat" : 43.839262,
                        "lng" : -78.96773639999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 348
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 53
                     },
                     "end_location" : {
                        "lat" : 43.8358058,
                        "lng" : -78.9691735
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kdqjGhr~`NJG`@YFGRIBEDGDKDWBKJKHKNILG@ANAHAJ@PFJDHFRPRPF@F@f@Aj@?J@RJPH`@TLJJLBBFJDH@D@F?JCNAJ?J"
                     },
                     "start_location" : {
                        "lat" : 43.83829950000001,
                        "lng" : -78.96884679999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 263
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 38
                     },
                     "end_location" : {
                        "lat" : 43.8339281,
                        "lng" : -78.97087639999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ytpjGht~`NDFFFNNl@f@NL^X@@NLTNJBLBL?T?@?F@HBLH@@HFLPPVNXJPBHBBDTBH@D?@?B@?B@FE@?@@DT"
                     },
                     "start_location" : {
                        "lat" : 43.8358058,
                        "lng" : -78.9691735
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 455
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 87
                     },
                     "end_location" : {
                        "lat" : 43.831159,
                        "lng" : -78.974981
                     },
                     "html_instructions" : "\u003cb\u003eWaterfront Trail\u003c/b\u003e turns slightly \u003cb\u003eleft\u003c/b\u003e and becomes \u003cb\u003eOntoro Blvd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "aipjG~~~`NFAF?HBNPDF`@t@BFbAfBZj@pBrDDFhCvEVd@Vb@BF|@~A"
                     },
                     "start_location" : {
                        "lat" : 43.8339281,
                        "lng" : -78.97087639999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 479
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 85
                     },
                     "end_location" : {
                        "lat" : 43.8288497,
                        "lng" : -78.97975129999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wwojGrx_aNLDBB@B@DBJ@BBFBDLH@@FBFHFN?BDLBLBN?@BFJLLPJNBH@D?F@LBHDLJNDP@D@FDHFJFF@@HHNRDFPXFHFLDPRv@HTBFBDR^Vd@@FBR@HDDBBJHFJ@D@NBRDHBBJPDN@N@VBF@BHNDR?B?PDf@BT@H?B"
                     },
                     "start_location" : {
                        "lat" : 43.831159,
                        "lng" : -78.974981
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "62 m",
                        "value" : 62
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 43.8292454,
                        "lng" : -78.9802871
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "iiojGlv`aNSTGNWh@[Z"
                     },
                     "start_location" : {
                        "lat" : 43.8288497,
                        "lng" : -78.97975129999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "60 m",
                        "value" : 60
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 43.8289844,
                        "lng" : -78.98086929999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ykojGxy`aNJZHJJLLL@@BD@LAR?D"
                     },
                     "start_location" : {
                        "lat" : 43.8292454,
                        "lng" : -78.9802871
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 374
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 63
                     },
                     "end_location" : {
                        "lat" : 43.8307938,
                        "lng" : -78.98439950000001
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "cjojGl}`aNEZ?H?J?JF^@DDZ@TAPO\\EFOVGDA@QNIJQRELABCDGb@C@EHILSVORGDELCPERIRSRUPCDEHKV?@IX]\\IJ[^Y^"
                     },
                     "start_location" : {
                        "lat" : 43.8289844,
                        "lng" : -78.98086929999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 289
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 49
                     },
                     "end_location" : {
                        "lat" : 43.8315596,
                        "lng" : -78.98771979999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "muojGnsaaNBJDNBJ?B?F?DAJGN?BA@M\\CHCNARCd@CTE^?FI^AHAHAh@?BANEZA@Sb@ABGZCPERCHKj@A@CJI\\Mf@CBAB"
                     },
                     "start_location" : {
                        "lat" : 43.8307938,
                        "lng" : -78.98439950000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "84 m",
                        "value" : 84
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 43.8321608,
                        "lng" : -78.9882253
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "gzojGfhbaNCFCDKRGJEHORSPEDGBC@GBIAME"
                     },
                     "start_location" : {
                        "lat" : 43.8315596,
                        "lng" : -78.98771979999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1277
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 208
                     },
                     "end_location" : {
                        "lat" : 43.827653,
                        "lng" : -78.99440419999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_~ojGlkbaNGHK\\A@Ih@?@Mb@CDKRMLGDMFEHA@EP?H@VAN?HCLGRCDOd@EV?H?BBLFT@L@NCPADERAN@N@L@FJZBFHJHJNJB@PFD?L?HAJAJAB@D@DDBB@@DBBCF?DD@?D@HAHEFCb@OVITEPC\\K\\MHEBE@EBCHOBCDEFCd@SHEBA\\KLEJCDAFEFE@CNMHOFIDIDG\\m@P]HMHCRPRFPATMNCTD`@HN?V?V?LAHALCLCP@PEFALBD@L?F@BH?@BLBV@F?ZCf@FNHn@@XA^APAH?f@?\\@R@@DX@V?FEPCNCJCJC^E^?R?JBVBFFPDP?@@FBN?L?HCJGJADGJGPEPEJ@^@^BNBLBNDJDHB@"
                     },
                     "start_location" : {
                        "lat" : 43.8321608,
                        "lng" : -78.9882253
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 155
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 26
                     },
                     "end_location" : {
                        "lat" : 43.8274295,
                        "lng" : -78.99606179999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "yaojG~qcaNFHHHBBBFLX@H@NAPCLEJABMXGJADADAL@H@JDX@BH^Jb@BHBD"
                     },
                     "start_location" : {
                        "lat" : 43.827653,
                        "lng" : -78.99440419999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "79 m",
                        "value" : 79
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 43.8271296,
                        "lng" : -78.99677129999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "m`ojGj|caNB@D@D@PBB@BDDFBJJ`@?H@H?JCLAL?H"
                     },
                     "start_location" : {
                        "lat" : 43.8274295,
                        "lng" : -78.99606179999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.7 km",
                        "value" : 3747
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 683
                     },
                     "end_location" : {
                        "lat" : 43.8170848,
                        "lng" : -79.03683099999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "q~njGx`daNBHBDLT^n@HLHP@H@H@L?J@^@R@PDRDNDJLTJJJLDHBJL`@NTHLFLBJ?@@HBP@RBTH\\Nf@FJDPZ~@Vp@BJNZRh@Ph@Rh@Zv@JXRf@@?Tf@FNJVNZ\\~@JTJNZf@HN@H@D@R@V?FB|@@dA?F?X@N?F@FDRFNHPLTLRNVPDJ@F@HAD?FCLAJ?H@BBDFDHFJDLP^NXNT?@LXNd@FRf@tBBDBJH\\DJ?@?@@BJXZn@@DZf@PZTd@@?Tb@?@DFN\\HJ@DDLFP@@@DR^BBR`@`@v@HTTf@Tf@Tf@BFP^Rf@Td@@@FL@FBHBF?H@F@H?T@DBHBLBJ@FHLHNDDFJDJBFDLBL@H@F?B?HAFAFCJEJO`@ITAF?DAF?D?D@N@R@DAD?BABGTId@AHABAF?H?D?F?L?J@H?HBJDPBJ@F@J?@BVDj@BX?B@HBJDPBNBNBN@D?BDPFTHZ@H@F@@?F@F@XTjALn@DTBN?J?HAF@D?HBN@TFn@Jl@FZBHH\\@BNd@@DXt@LZLVFNHLHJHFPFLBB@JBHFBF@?BFHVFVF^Hp@BJBb@BVBj@?\\?L@J@JBLBRDPPx@HTDJFHJFl@`@LLHNFNHPVp@Vp@HRPh@PV@BHLZb@T^Td@L\\@FLb@@HFTDJ?@JNDN@F@H?`@?DAb@?JANMfAAHE\\KVGRCNAHEd@AJC\\?DCf@AHCl@?@Eb@IjACTAXCr@Ix@?JCl@At@Ap@Ap@?n@AvAA|@AbBAr@?PARCr@Gn@AFAJAV?J?BBd@@X@NCPEP?@ANCVF\\?D?DAH?BCLAN@VAt@?J?H@J?D?N@h@ATCH?BC@?@S\\A@ABCFIb@ETI^?H?D@DBJBBHLLP`@j@PZRZ?@?DAr@?HAFABKTMVGLm@lACDMTCH"
                     },
                     "start_location" : {
                        "lat" : 43.8271296,
                        "lng" : -78.99677129999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1452
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 271
                     },
                     "end_location" : {
                        "lat" : 43.8121998,
                        "lng" : -79.0518086
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w_mjGd{kaNAJ@LBLFH@@DBPBJ@JBLJDD@@?@JLDHBLDLDXHZDPBJBV@REf@AHGb@Ab@?N?NF\\@b@@z@?X?T@b@BFBF?T@DBFBJ@J?F@X?VAP?NAL@F?J@NANIj@EX?L?P?FAHGNABYt@GVCN?FDX@F@DP`@DJJ\\DLDPB^F\\BFF\\DXBTAPAN?J@FBNDL@T?@JdADV?@?P@T@D@HBPDH\\f@RLJFHDRLXPZTHJHNPZFFLRBFTXFHBFJf@DZ@@?DAFEb@AX@H?H@@@HHTDHFPJNJJPFl@LDBDFDR@?Ll@DPL^^jARl@?BRl@FJVn@FLPd@DPDVBF@BJJ`@^FLTd@FJr@|ADJRh@FL@D@FAP"
                     },
                     "start_location" : {
                        "lat" : 43.8170848,
                        "lng" : -79.03683099999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1012
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 233
                     },
                     "end_location" : {
                        "lat" : 43.8154455,
                        "lng" : -79.05995229999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "galjGxxnaNATAHCFE@a@La@Lc@LcAXUHID?BA@CJ?J@T@FBf@@DDj@Bf@@FB^@P?TAJCHA@EDIDQBa@H[Dy@PGBGDm@h@OHA@a@LIBaDdAa@LmA^WLA@]PA@GDEFGRAR?X@DBd@BJHl@Hn@Jn@^lCHn@Jn@R|AJn@Hn@Hn@DZDRHl@PjA"
                     },
                     "start_location" : {
                        "lat" : 43.8121998,
                        "lng" : -79.0518086
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "28 m",
                        "value" : 28
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 43.8156821,
                        "lng" : -79.06005689999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBrock Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "quljGtkpaNWJUH"
                     },
                     "start_location" : {
                        "lat" : 43.8154455,
                        "lng" : -79.05995229999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 855
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 195
                     },
                     "end_location" : {
                        "lat" : 43.8134986,
                        "lng" : -79.070171
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_wljGjlpaNDl@?@BFDL@F@N@H@LDVDTBVDVF`@Dd@@D?P?D?X@P?DFl@@TBT?@DVHNRVDNBFBLBP@BPfALv@@L@JJ|@@F@NDVLz@@HF^@N?F?P@R@d@Ff@BP@DBVH`@J^b@lCDVJn@NdADVJn@DXDRD\\?@N~@F^Hl@BNFb@BPBV@R?DAX?XDTDP@N?P"
                     },
                     "start_location" : {
                        "lat" : 43.8156821,
                        "lng" : -79.06005689999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "85 m",
                        "value" : 85
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 43.8140645,
                        "lng" : -79.07078009999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kiljGpkraNC@MFODUHOLOPCDKTGL?J?H"
                     },
                     "start_location" : {
                        "lat" : 43.8134986,
                        "lng" : -79.070171
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 968
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 160
                     },
                     "end_location" : {
                        "lat" : 43.812725,
                        "lng" : -79.0802987
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{lljGjoraN?@@HBFFFXRJLDDJTBHDNHZ@FLXDD?@NRXZJNFLJTH\\BR@PBf@?ZCZK`@[jAE`@?PBRBJFPJP@@?@VTB@VJHBVDH?b@@B?R?J@ZBFBB?^JLDPJHDJV@D?BBL@J?J?DAHE\\AFGn@CNQnAIn@?BIj@G`@CJSxAADIn@Il@In@G`@CLSzA?B?BC^@L@`@ALCZERMl@Ml@Kl@A?In@"
                     },
                     "start_location" : {
                        "lat" : 43.8140645,
                        "lng" : -79.07078009999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1875
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 359
                     },
                     "end_location" : {
                        "lat" : 43.8287974,
                        "lng" : -79.08733939999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLiverpool Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "odljGzjtaNSBOF_@LA?]J_A\\C@[LcAZKDUHg@PsC|@iDjAgDjAkC|@cCz@gFdBgC|@{Bv@UFcA\\a@LgA^[J_Bh@mBl@{JhDeFdBqC|@kDjAcA^iAb@W?EB_@Lm@RSD"
                     },
                     "start_location" : {
                        "lat" : 43.812725,
                        "lng" : -79.0802987
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1109
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 175
                     },
                     "end_location" : {
                        "lat" : 43.824167,
                        "lng" : -79.09933629999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBayly St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 22\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_iojGzvuaNBZJvBBb@?@FnBBpA@h@Hv@BXDTDZDPV|@L^P`@hAbDx@|Bf@tAr@rBhBfFPT`AdCN\\zBtFx@tBnAjDt@tBBFt@~B"
                     },
                     "start_location" : {
                        "lat" : 43.8287974,
                        "lng" : -79.08733939999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 331
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 102
                     },
                     "end_location" : {
                        "lat" : 43.8214625,
                        "lng" : -79.09924649999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "alnjGzaxaNPID?J@J@JHZNN?V@H?FAFC`@QB@D@JD^j@DLB@BBFDPJD@LBN?B?RANCVGJ?HIFEBCX]?ADCFKDEDABAZIDAb@I"
                     },
                     "start_location" : {
                        "lat" : 43.824167,
                        "lng" : -79.09933629999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 269
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 51
                     },
                     "end_location" : {
                        "lat" : 43.8194173,
                        "lng" : -79.0988249
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eVistula Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "c{mjGhaxaNGi@BY@CFOLIBATGn@Q`@Mb@MZCF?NB~DbA"
                     },
                     "start_location" : {
                        "lat" : 43.8214625,
                        "lng" : -79.09924649999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "65 m",
                        "value" : 65
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 43.8192055,
                        "lng" : -79.09806519999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eElvira Ct\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "knmjGr~waNJm@Jq@Pu@"
                     },
                     "start_location" : {
                        "lat" : 43.8194173,
                        "lng" : -79.0988249
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 124
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 43.8182531,
                        "lng" : -79.0979377
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ammjG|ywaNF?`@B@?Z@F@@@HDNJB@D@D?JEBC@EDMJ]@E@AB?VH"
                     },
                     "start_location" : {
                        "lat" : 43.8192055,
                        "lng" : -79.09806519999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 390
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : 43.8150451,
                        "lng" : -79.09778849999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "agmjGbywaNJBL@JAFEPKNEDCL?J?BD@?HHLR@@\\ZZJH?JCdA_@t@KVEJIDCNODGTYNGXGHCX?D@RFFB@@L?HAH?PCH@DD@?FHLX"
                     },
                     "start_location" : {
                        "lat" : 43.8182531,
                        "lng" : -79.0979377
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 237
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : 43.8130324,
                        "lng" : -79.09692780000002
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBreezy Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "asljGdxwaNBAZIvAWlAQ|@]`C{AD@F@"
                     },
                     "start_location" : {
                        "lat" : 43.8150451,
                        "lng" : -79.09778849999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 283
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 49
                     },
                     "end_location" : {
                        "lat" : 43.8107855,
                        "lng" : -79.0968645
                     },
                     "html_instructions" : "\u003cb\u003eBreezy Dr\u003c/b\u003e turns slightly \u003cb\u003eleft\u003c/b\u003e and becomes \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mfljGxrwaNPWHE@A^MDAhA]F?JLBD@@Zd@Hd@BBBBF@LCBAj@MTCBAz@LX?NCDAXQBG"
                     },
                     "start_location" : {
                        "lat" : 43.8130324,
                        "lng" : -79.09692780000002
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "42 m",
                        "value" : 42
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 43.81044139999999,
                        "lng" : -79.09700719999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mxkjGjrwaNDDDBPJNHD@D?D?DC"
                     },
                     "start_location" : {
                        "lat" : 43.8107855,
                        "lng" : -79.0968645
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 337
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 75
                     },
                     "end_location" : {
                        "lat" : 43.80898149999999,
                        "lng" : -79.1004555
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gvkjGhswaNP^BDBDBF@F?F@D@H@FBJ@FBJ@F@H@FDHIH?@?B?DDDXj@@F?H?T?@A\\?DBF@B?@FDVRDDDFHN@@DHN\\Rb@Nh@@DTb@R^P\\FPDJHd@BP"
                     },
                     "start_location" : {
                        "lat" : 43.81044139999999,
                        "lng" : -79.09700719999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "5 m",
                        "value" : 5
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 43.8090235,
                        "lng" : -79.1004738
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eW Shore Blvd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cmkjGzhxaNG@"
                     },
                     "start_location" : {
                        "lat" : 43.80898149999999,
                        "lng" : -79.1004555
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 116
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 43.8087167,
                        "lng" : -79.1018591
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSurf Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kmkjG|hxaN\\nC\\dC"
                     },
                     "start_location" : {
                        "lat" : 43.8090235,
                        "lng" : -79.1004738
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 223
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 43.8067928,
                        "lng" : -79.1010663
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMarksbury Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "okkjGrqxaNhCy@vFcB"
                     },
                     "start_location" : {
                        "lat" : 43.8087167,
                        "lng" : -79.1018591
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1423
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 293
                     },
                     "end_location" : {
                        "lat" : 43.7976862,
                        "lng" : -79.11175060000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "m_kjGtlxaN?H@LFX@DDLHPBHBDDLBJ@L?FBFJRBBLNFHRNNJ@@BDBJFNBLBLBXBJHXTf@P\\DHP\\BFNXDJDDJLHJFJJLFBZRB@`@PJFD?P@\\BBB^V^V\\VTNHH`@\\VZX`@t@`AZ^NFd@r@|@fAVNVLb@RDDNNHP@BHXFX?b@?@@b@L`@LLNLLJDBDFX^LTHJTJ@?R@LAL?RC@?V@^HLFRLDLDR?JAh@BJBJFBP@H@NBPD^HB@|@XDB^NTNJH@BPTHXH\\Hl@@J@RBL?D@F@BBFBF@BBF@BBB@BBDFFDF@@BBDFFDFFDBB@BBHDRJDBD@DBBBDDB@BBFJDF?@DHL\\@DLh@"
                     },
                     "start_location" : {
                        "lat" : 43.8067928,
                        "lng" : -79.1010663
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 385
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 86
                     },
                     "end_location" : {
                        "lat" : 43.7968508,
                        "lng" : -79.1163359
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRodd Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qfijGlozaNJf@H`@h@xBJ`@BHFV@FBRDb@Df@@B@JB`@@NDZ?FDTDV@JT~ABXBT@p@@f@BhA?N?RATCV"
                     },
                     "start_location" : {
                        "lat" : 43.7976862,
                        "lng" : -79.11175060000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "64 m",
                        "value" : 64
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 43.7963032,
                        "lng" : -79.1165616
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBella Vista Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "iaijGbl{aN`@PXLDB@?B@RDP?"
                     },
                     "start_location" : {
                        "lat" : 43.7968508,
                        "lng" : -79.1163359
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 266
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 43.7948805,
                        "lng" : -79.11826719999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "{}hjGnm{aNDH@@@BB@DBD@D@F@@?L@D@F@J@LDD@B@B@@@HDDDFDBB@@BBFFBFHLRZDD@BBBDBB@BBJBLFJDHDFDJHJF@@VJB@FB?@@??@?@?@GZALCFAFGLMNEFCB?@AB"
                     },
                     "start_location" : {
                        "lat" : 43.7963032,
                        "lng" : -79.1165616
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4.7 km",
                        "value" : 4716
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 922
                     },
                     "end_location" : {
                        "lat" : 43.7636145,
                        "lng" : -79.1514928
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_uhjGdx{aNAF?D?F?B@@@BFB@@NJFDFDRNJFBBHFJFJHTN@?@?@?@A?AAAA?IGMIAAAAAA?ACGAE?AAACA?K?I?GBQNg@L_@@A?A@A@?@?@?B?DBLJt@f@RLRL`@Z`@XDDJJLFJFRFF@JBLFFBHBLHPJPNFDJJNNZVVTPNVPr@h@d@ZNJVNNHFBB@VLDBJDPHB?D@JBB?D@B?@?DANAHAB?BAD?F?B?@?D@B@@@@@BBHHFL@BHJLP@B@@@@BBDDFDDD@@D@HDJDFBVHF@RDPDJBD@DBNHNJDFTZVb@HLHJJHDBBBDBB@JDLBZJNDNDRFB?JFFDFH@?DHFJDL?@FLLZDJFHHJHHRL@?^TJFFBn@TF@JDHDFBDDHFFF?BJPLVLVLRFFHHB@FDLFJB@?NDPDZFD@NBD@B@B@B@BB@BDFBD@BBDBFFHFHHJFFDDDDVTLJFDJFDDD@?@FBTJB?XJ@@@@@?FLHLDJLVFN?@HRHTNd@BHBHBFBDFFRPHFVRPJFD@@DB@@@@DDBBDDB@JH@@NLJH@?DDBB@B@B@@@BBD?B@BDL@B@B@??@@@BB@@@?TH@@HBLFF@@@B@DDNN@@DDHHJLHJLN@@B@@@JDJDD@B@DB@@DB?@@?@B@@?BDLBNFT?@@@@@?@@@@@@?@@VPJHJJZ^FFPR@BDF@@FHFLFH?B@@@B?B@FBJFNHPLPDDBDDDFDBBLJHHDDf@d@RRFDRR@@HHRP@@VTBBVRr@n@z@v@vBlB?@FDPNb@PFBFFDDFFJLNP@BFHFDHFFBNHJDLFDBDFHHBDFJPR@@ZZLJ\\Xn@f@JHHJFJFJFLDHFJDFDDJJd@XPLPJNFFBPDXKHEDAHAJAHAF@F@FBFBFFHFFFDH@DBFDNDJHZJ`@FTDLDJFHDFHHVRNJHDFHFFJPJNFFLLZXHFd@VLFRJNJJHFHHJJTJPP\\LTPTNPRN`@ZJHHD`@VVLJHDBBDBB@BBDFPL`@Rh@JTFNJPPRPRFDFDJDHDVFNFHBDBDDBFDHFLJXDRJXJ\\Vj@JRJRNTNTVZ`@h@JLHHJHPLJHBB@@BFDLBH@F@H?H?J?`@?P@J@B?DBB@DDFLRFFp@bAl@|@p@fAd@r@^n@DFP\\?@R`@R^JTJTXn@Zn@HP@BbArBBNDBDBFDHDDBDDDDHHBDJLNNFFDHBFDH@DJRFL?@JRDLBB?BBF@D@FBHBFDFFJHJLPHHDDVTDDDBHHDFDFFHLNHLFHHLB@DDNNTPVNHFDBDB@BBDPVHLLPHLJPFJBBJPFNFLDLBJDP@L?@BL@J?N@LAL?R?T@L@PBN@LBLDVHb@F`@Jj@F`@Jj@Fd@FZFX"
                     },
                     "start_location" : {
                        "lat" : 43.7948805,
                        "lng" : -79.11826719999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "23 m",
                        "value" : 23
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 43.7638063,
                        "lng" : -79.15158699999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBeechgrove Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qqbjGxgbbNODWL"
                     },
                     "start_location" : {
                        "lat" : 43.7636145,
                        "lng" : -79.1514928
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.3 km",
                        "value" : 2297
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 439
                     },
                     "end_location" : {
                        "lat" : 43.7573345,
                        "lng" : -79.17595279999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCopperfield Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yrbjGlhbbNt@xEHd@@NDZ@Z@H?LAL?JAJEVETUhAAF?BABAJ?F?T?J@P@D@FBJHb@XvANv@Hd@Lp@Jl@Jn@Ll@?BXhB\\rB@FXdB\\vBHd@@HBH?@FPDFDJRXZf@NTT`@JNFLHRBH@BBFHXBJ?@BPDV@J@LBZ@\\?P?R?PAZ?LEfB?\\@ZBXB\\TnBHr@r@nG?BNvAL~@?HNhABZBR\\pDBRj@`GJ|@Fr@`@vDh@fEFb@BX?J?FDb@?N@H@RFp@@PD\\DTDV@LJx@Hx@Hr@Fl@LjA@RBRD\\@L@LR~A?FBT@LDRD\\Fh@BP?F@L@D?B@??@@?B?B?DCDENYBEBEDGBELMNGNEJIHCFAF?H?F?FAJCFAJCHEFEBEtBhA"
                     },
                     "start_location" : {
                        "lat" : 43.7638063,
                        "lng" : -79.15158699999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 879
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 145
                     },
                     "end_location" : {
                        "lat" : 43.75323969999999,
                        "lng" : -79.17980899999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGreyabbey Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ijajGt`gbNH]H]Rw@DUDQ@I@IDo@Dm@@]@K@I?C@CBGBI`@_AFKBG@CBCBCBCDC~@]DCB?@A@?@?@AB@@?@?BB@D@B@B@LBLz@tDFZlAnFJf@BLBDBF@B@@@B@@B@@@B@@@@@@?J@F@F@B@D@FBPFNHHDFFFDFFHJDFDFHJFJBJFLBH@BHVVv@Ld@BDb@xA^lAf@bBZbABF@D?D@D?F?J?N"
                     },
                     "start_location" : {
                        "lat" : 43.7573345,
                        "lng" : -79.17595279999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1389
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 282
                     },
                     "end_location" : {
                        "lat" : 43.7483663,
                        "lng" : -79.19539329999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGuildwood Pkwy\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wp`jGxxgbNB?B@@?@@DDJPTb@Vd@jCzEx@xAHPR\\JRNVVf@Th@HRFNNb@Rp@DLDTLb@@HJf@Hf@@LDTF`@R|AF\\?@Hb@F`@NfAJv@BVn@xEj@|D\\lCPhA?DJv@VlBHn@DX@PjAdJFR\\pCPrARxAXxBXvB"
                     },
                     "start_location" : {
                        "lat" : 43.75323969999999,
                        "lng" : -79.17980899999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 678
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 132
                     },
                     "end_location" : {
                        "lat" : 43.7437745,
                        "lng" : -79.1961405
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ir_jGdzjbNTA@@F@DBB?F?n@UVIx@Wh@WNG@A@?@C@A?C@C@EF[FO@IJOVULQBABCNCBA@?B@@?FD\\XNRNR@D@@BD@?@@@?N@B?^B\\DJD~@N@?D?@?@?@@@??@@@@BP`C?B@L@J@NBLBH?J?N?N?P@VDRDPBHBH@?PEd@OREVK`@MRGFCTIPEPGVIBA"
                     },
                     "start_location" : {
                        "lat" : 43.7483663,
                        "lng" : -79.19539329999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1603
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 288
                     },
                     "end_location" : {
                        "lat" : 43.7340184,
                        "lng" : -79.2101943
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSylvan Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qu~iGz~jbN@HBHHv@Jn@BPDZDXF`@@N@LDVBXDTBRBHBHBFBDHJHLjAlANNXZ~@bAfAhA`@b@PPv@z@p@r@Z^~@`ARPNVhAfB~@tAdCvDNVr@dA\\h@FJFJBF@DBFFRPt@XlAXfALl@Ld@FZBDBHDJFLDHBDRTNPNN\\^fGlGzFfGLJPRLNJLJLHNFPFPTz@HRHPDLLN"
                     },
                     "start_location" : {
                        "lat" : 43.7437745,
                        "lng" : -79.1961405
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 484
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 94
                     },
                     "end_location" : {
                        "lat" : 43.7307595,
                        "lng" : -79.2137901
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eSylvan Ave\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "sx|iGtvmbNBDJLBBNNrAvAtAzA`AdA`@Zp@d@VRZVB@PNHJJLNPRZJR@BLZHVJ\\Lh@Hd@BX@F@B?@@@B?F?N?T?B?B?D?@?D?F@"
                     },
                     "start_location" : {
                        "lat" : 43.7340184,
                        "lng" : -79.2101943
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 189
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : 43.72955690000001,
                        "lng" : -79.2152306
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gd|iGdmnbNAR?N@J@JFRDJBFFFJHFFHFHFHFFFDD\\^FFDBDBDBDB@?JDB?HFFDHFHFHDDFDBFL"
                     },
                     "start_location" : {
                        "lat" : 43.7307595,
                        "lng" : -79.2137901
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 319
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 225
                     },
                     "end_location" : {
                        "lat" : 43.7297615,
                        "lng" : -79.2182193
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "w|{iGdvnbNQf@?BKTENA@AN@N@L@JDNFPFPHLJLJNHLJNHNDLFLFLDLFNJf@@H?F@F?NALAHAJCHCHCFABCBEDCDEFEBABCBEBMFGB_@NIDC@CBEBIF"
                     },
                     "start_location" : {
                        "lat" : 43.72955690000001,
                        "lng" : -79.2152306
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 122
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 43.7302373,
                        "lng" : -79.2193075
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBellehaven Crescent\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_~{iGzhobNBF@HBH@N?H?N?NAN?DAJENELILGHGDCBQHMFMFOF"
                     },
                     "start_location" : {
                        "lat" : 43.7297615,
                        "lng" : -79.2182193
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 391
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 43.73085409999999,
                        "lng" : -79.2240585
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eBellehaven Crescent\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_a|iGtoobNAFAFAFCFITEPCRCT?BEz@Ct@CXAZInBEt@E|@?JAPAZGhA?LStEALATAHAFADAFEF"
                     },
                     "start_location" : {
                        "lat" : 43.7302373,
                        "lng" : -79.2193075
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 131
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 43.7319648,
                        "lng" : -79.2245669
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRavine Dr\u003c/b\u003e",
                     "polyline" : {
                        "points" : "yd|iGjmpbNCBCBGBKDs@Ty@Xu@R]N"
                     },
                     "start_location" : {
                        "lat" : 43.73085409999999,
                        "lng" : -79.2240585
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 240
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 101
                     },
                     "end_location" : {
                        "lat" : 43.7340297,
                        "lng" : -79.22543759999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBellamy Rd S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wk|iGpppbNa@He@PkA`@IBSFy@VQF_DbA"
                     },
                     "start_location" : {
                        "lat" : 43.7319648,
                        "lng" : -79.2245669
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1775
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 326
                     },
                     "end_location" : {
                        "lat" : 43.7260983,
                        "lng" : -79.2436283
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOakridge Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ux|iG~upbNdA~Hf@tDf@tD@F~@|GfAjIt@pFd@pDTzA^pCPpALv@Fd@^nCHd@DVDRDLDJDFb@l@xCzDfB~Bl@v@HJZ`@dEfFbBrBnB|B`DxDbAnAT\\"
                     },
                     "start_location" : {
                        "lat" : 43.7340297,
                        "lng" : -79.22543759999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 901
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 220
                     },
                     "end_location" : {
                        "lat" : 43.7183382,
                        "lng" : -79.2403999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBrimley Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cg{iGtgtbNHCdBk@vEwAdDeA~@Y@?hCy@DAzDmALEdA]PEh@QPG`@MHCzAe@p@Ur@SDCbA[`Bg@~@YVK"
                     },
                     "start_location" : {
                        "lat" : 43.7260983,
                        "lng" : -79.2436283
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "8.3 km",
                        "value" : 8266
                     },
                     "duration" : {
                        "text" : "23 mins",
                        "value" : 1355
                     },
                     "end_location" : {
                        "lat" : 43.6699496,
                        "lng" : -79.3111773
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKingston Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "svyiGnssbNfBtB`@f@rA~ATV|@dAnC`DlAxADDbCxCvA`BpAzARVJJ\\`@X^FFb@d@FHn@r@rB`CLLn@t@JLPPVZB@^b@NLJJdBtA^T^VTLh@\\TNfAn@xAx@x@b@PJ~Az@PNhB~@zDvBt@^NHBBbAf@FDVJ^RrAp@PJNFt@`@~@f@lAp@^PNJ^RFDn@\\bAh@h@XBBFDPJ?@NJBBHFLNRRVZRV@BV`@JNBDD@@@JNLNJNDDHJHFFFJHJJB@FDNLHDFDLHHBBBRJRHNFD@D@JDH@JBRDJBVDH@FBPBF@D@JBTDRB@@\\FPDTD`@JB@^H?@b@LJBFBXJXJ^NRHPHJFLD@@HDRJTLj@\\x@j@d@\\`@Xb@^d@`@XXf@f@RTp@x@PVx@hAl@z@xBzCvApBPVZ`@Zd@PTLPBB@@@@F?^h@BD`@h@d@p@FFNT`@j@\\n@FJNNHLRXNV^h@Xb@FJf@z@FNVd@BFDBBFFLJRLVd@`AXh@LXHVBDDHN\\Xl@zAhDp@zADHr@xAN^Zn@LXP\\NZh@dAb@x@T^v@rA`@p@dElHNRxA~Br@nAxAfCNVXf@dAbBlB~Ct@nA`@p@f@v@l@bAbAzAVb@LTz@pA\\l@dAbBj@~@DHNRVd@N\\Vj@LXJ\\Nd@Lh@ZfAv@lCHZh@hBTr@FTFVVnANt@Jd@H^Ll@F\\Lt@B\\BTBn@?FFhAHbBHnA@ZFzAFtA@XP~D@HPxEBj@HxBBj@HhCDjB@h@Bz@@b@?RD^Bl@@b@@`@HvBDr@Dh@Hb@VhB`@nCl@lELbARtApArIL~@L|@Hn@d@fENjADXBP@DF\\HXZfA^lA^hAfAlDlA`EJTPn@LXHVRb@P`@HLFRHNJNHPNR^h@zAhBhBtBHJ\\^hArAFFDFRRHL^b@r@z@n@v@~AjB`@f@JHNPJLLNf@h@X\\d@l@NNLNNLB@B@NLNJNHXLRJrAh@nAf@fAd@ZJn@X"
                     },
                     "start_location" : {
                        "lat" : 43.7183382,
                        "lng" : -79.2403999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.9 km",
                        "value" : 3936
                     },
                     "duration" : {
                        "text" : "14 mins",
                        "value" : 816
                     },
                     "end_location" : {
                        "lat" : 43.6611965,
                        "lng" : -79.3581409
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDundas St E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ehpiGzmacNAJ?P@vABn@?HDj@D\\BLBPDPDH?@FNFLP^?@FNJTHRBF@DBJDNBL?@BN@DAL@L@F?\\B`@BVB~@BZBnA@R@J@N@PDTBNJr@@H@HPhAPrABJBHHLLbA@H?J@nA@v@@z@@F@\\d@jDZxBRzAPtAHd@TjBDXRpADXBX@L@L@V?NB~A?JHbE?HH~D?H@hA@\\?B@rBAtB@`@@h@FbB@N@P@JBTFf@RdAN~@BTT|AZzBF^RvAZvBRrA`@rCHl@`@vC@HJ|@@JJpBZdGFv@Dz@@V@JB^D^Df@VpB\\fCBND\\L`APjAD^XjBTvANhABRDTDPJ^DLBJh@pAl@~AHR@DJXJ\\BFFZJ`@BPBNDZDN@RDh@Dh@?HL~ABb@BXB\\F~@Fz@LvA?@D\\?B@Z@H?B@DFd@N|@ZnBD\\Jl@RzAPhABN@FR|AFb@XlBFf@F\\DV?@NjAFZFh@Jn@NdA@NDV`@lCBNFh@@PBNHjALzBHvA@TLhBNnBDh@@HBPNnA@BZrBLx@NbA"
                     },
                     "start_location" : {
                        "lat" : 43.6699496,
                        "lng" : -79.3111773
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 196
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 43
                     },
                     "end_location" : {
                        "lat" : 43.659509,
                        "lng" : -79.3574326
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRiver St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "oqniGjsjcNp@Ub@M^KHEl@QTGxAg@r@U"
                     },
                     "start_location" : {
                        "lat" : 43.6611965,
                        "lng" : -79.3581409
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1832
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 431
                     },
                     "end_location" : {
                        "lat" : 43.654326,
                        "lng" : -79.37875799999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eShuter St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}fniG|njcN\\r@HPd@`AZp@P^d@~@JR~@lBDFVl@LZJ\\?BDPBRBPHp@ZtB`@`D`@lCBV?D@JBVNbABTLv@F`@Jv@Jl@VjBT~AF`@ZdCZ|BZvB@L?J@H@L?J@L?P@jB?zB?P@B?J?H@H@J@RTbBNdA^vCHj@Hl@b@fDDb@BLNnADXBNPfBH`@BXFXBVF\\D^Fh@d@rDDXRbBTzANhAJx@VtBVpB"
                     },
                     "start_location" : {
                        "lat" : 43.659509,
                        "lng" : -79.3574326
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 192
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 49
                     },
                     "end_location" : {
                        "lat" : 43.6526722,
                        "lng" : -79.378063
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eVictoria St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qfmiGftncNrGsBv@W"
                     },
                     "start_location" : {
                        "lat" : 43.654326,
                        "lng" : -79.37875799999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 308
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 117
                     },
                     "end_location" : {
                        "lat" : 43.6518897,
                        "lng" : -79.38173239999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eQueen St E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "e|liGzoncNr@nFD^NfAHh@XpCLz@Lv@PtA"
                     },
                     "start_location" : {
                        "lat" : 43.6526722,
                        "lng" : -79.378063
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 152
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 43.652962,
                        "lng" : -79.382633
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBay St.\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "iwliGxfocNIb@CLCLAHCHADABADCBABEDCDIDu@Tk@H{@T"
                     },
                     "start_location" : {
                        "lat" : 43.6518897,
                        "lng" : -79.38173239999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "45 m",
                        "value" : 45
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 43.652871,
                        "lng" : -79.38317289999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at \u003cb\u003eAlbert St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_~liGllocNHz@Fn@"
                     },
                     "start_location" : {
                        "lat" : 43.652962,
                        "lng" : -79.382633
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "47 m",
                        "value" : 47
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 43.6524799,
                        "lng" : -79.38296489999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eNorthwalk Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "m}liGxoocN|@_@NI"
                     },
                     "start_location" : {
                        "lat" : 43.652871,
                        "lng" : -79.38317289999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "32 m",
                        "value" : 32
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 57
                     },
                     "end_location" : {
                        "lat" : 43.6526831,
                        "lng" : -79.3828082
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eNorthwalk Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eTake the stairs\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_{liGnnocNGOISCCQD?B"
                     },
                     "start_location" : {
                        "lat" : 43.6524799,
                        "lng" : -79.38296489999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "66 m",
                        "value" : 66
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 43.6532565,
                        "lng" : -79.38303979999999
                     },
                     "html_instructions" : "Take the pedestrian overpass",
                     "polyline" : {
                        "points" : "g|liGpmocNYHIBWHIBm@P"
                     },
                     "start_location" : {
                        "lat" : 43.6526831,
                        "lng" : -79.3828082
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "uavtGjs_`Mtb@_m@d{@zg@dT`K|dA|jAfvBjnGrfC`}GgKhuCkc@jvGcw@xrHlt@hhGnr@l}Az`DpbNvL`eD~Sfy@pq@fOh}@veEuv@tsCoeC|jC_`C~qDet@fQnH~`BqUrxBu_AfqAc_@bhCyoAzsFen@xiC{FneCpDltNefCty]_hDr{Qcl@~tNyCnmMop@rqOxSb_IfsAlrHtbAhhDmF~}CvA|cExaCf|E|zEbgHjcCz{Slm@xsPjoBdz_@ej@btLtHjaL`Jz_EqW~cDoKdjBfZj^v[xsAei@|zChXnkDj`AvlEze@~lAdbBh~@tpE|nGdv@|yA|BzlA~wBiEbpHbcJ~pJ~jQvgGbaLbfEtjLhd@ndAvm@k[dsAmj@foFklCdiGiaCneBqF~|AreB|bD`fGv`BzgBlyDb`Ip~CdlHuAnrBbeB`eDzq@l~DztBb~OltBfiHty@zcCq]l{B~{AzmC~@btDtf@|bF|bAtgE|f@ltCxcAtiAdgAl`Cn~@bj@nz@tt@hSvqAhc@daE~qAvwJ|WpnJ~rAfzDdj@djA_l@xgAeHp}Cb|@|gCpr@neH|eFliJxcBvbI|jBl~Bt~B|wAtjIjeD~zB`|B~xCj|GvjBjsFpw@r_@py@tgBf~@blEdp@vcFbRddEznCxmFbXhw@e\\pf@zNjcDpi@`bDnuBz`Nnz@pfGf}A`aKfnAwWfp@faCxx@tuEnq@|zCr~AvRzsAjcBvrChmBvcFtn@lwEleAle@hAxRvdAv_@pq@pcAv_C`x@~T|eCva@hlCao@heDl`Dpe@xhCx{@f{AvcA`Jfd@tWlf@aMfa@vj@vi@fjDzNpl@~t@}Lnl@jfBf~@f[|mBce@tg@kXxiAbdB|a@pfDhNteC~dCpcObq@l{EpEtqBu[jv@o`@ng@~U``DnfAneHrq@~cHl_BxdKli@pgF~pBfuF`c@n{BeVd}AqFroA~Lj{Bt\\dmEcDzaBcq@~_@bWjoB~HjxCti@lbDaCfjBjMvuBzaAjsErC|nB|i@xCxBj_Aa\\diBfUbkCoU~rAx@vTa\\vz@dRvb@te@jDbb@roAaJzbAi}BzrBgp@vGfp@wGhcAxC|v@ryDfv@bjH~w@`oCbO|[~fAyQpo@x}@{Nj}@fYtKfo@plCbU|`DxVjjAyJpzAfLftAqy@f_@a`@hw@dg@j_@l`AoCzx@z`Abv@deA`cDtiDz{@~eDxpBpgExu@pjAoIxe@kDhkAbbAf`@p~Ap_Af`@tUptBf`DriAjfEdb@l~DtaAltF"
         },
         "summary" : "Prescott-Russell Recreational Trail",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
         "waypoint_order" : [ 0, 1 ]
      }
   ],
   "status" : "OK"
}
