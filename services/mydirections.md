# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json
?origin=place_id%3AChIJKQDzOA41K4gRajQDdyzD990
&destination=place_id%3AChIJBxZ2UMw0K4gR1LmKMBvveP0
&mode=walking
&units=imperial
&language=fil
&waypoints=optimize%3Atrue%7Cplace_id%3AChIJWyfdtDHL1IkR_bal8ay1Cso%7Cplace_id%3AChIJmzrzi9Y0K4gRgXUc3sTY7RU
&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJKQDzOA41K4gRajQDdyzD990",
         "types" : [ "establishment", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJmzrzi9Y0K4gRgXUc3sTY7RU",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJWyfdtDHL1IkR_bal8ay1Cso",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJBxZ2UMw0K4gR1LmKMBvveP0",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.6530077,
               "lng" : -79.371782
            },
            "southwest" : {
               "lat" : 43.642855,
               "lng" : -79.38718730000001
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "0.5 mi",
                  "value" : 872
               },
               "duration" : {
                  "text" : "11 mins",
                  "value" : 673
               },
               "end_address" : "290 Bremner Blvd, Toronto, ON M5V 3L9, Canada",
               "end_location" : {
                  "lat" : 43.642855,
                  "lng" : -79.38718730000001
               },
               "start_address" : "65 Front St W, Toronto, ON M5J 1E6, Canada",
               "start_location" : {
                  "lat" : 43.6456155,
                  "lng" : -79.38049599999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 375
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 282
                     },
                     "end_location" : {
                        "lat" : 43.644648,
                        "lng" : -79.3850638
                     },
                     "html_instructions" : "Dumiretso pa-\u003cb\u003ekanluran\u003c/b\u003e sa \u003cb\u003eFront St W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cpkiGb_ocNFTRxADT@JDVBTBLBPFXNvAAZLn@Bf@@FTdBBRDTBZF`@@JBVFb@F`@DZBNHn@?BJh@"
                     },
                     "start_location" : {
                        "lat" : 43.6456155,
                        "lng" : -79.38049599999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 191
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 131
                     },
                     "end_location" : {
                        "lat" : 43.6431134,
                        "lng" : -79.3844447
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakaliwa\u003c/b\u003e patungo sa \u003cb\u003eLower Simcoe St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ajkiGr{ocNLCr@WVEp@UFCd@O^MJCTINGRCRG"
                     },
                     "start_location" : {
                        "lat" : 43.644648,
                        "lng" : -79.3850638
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "420 ft",
                        "value" : 128
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 134
                     },
                     "end_location" : {
                        "lat" : 43.6432174,
                        "lng" : -79.3850874
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakanan\u003c/b\u003e papunta sa \u003cb\u003eThe PATH - Skywalk\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eGamitin ang hagdan\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "m`kiGvwocN?FF\\D^Hn@Hp@?@?@A??@A?A??AAC?AEYAG?AACAAAAA?A?]F"
                     },
                     "start_location" : {
                        "lat" : 43.6431134,
                        "lng" : -79.3844447
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "302 ft",
                        "value" : 92
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : 43.6429469,
                        "lng" : -79.3861395
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakaliwa\u003c/b\u003e patungo sa \u003cb\u003eThe PATH - Skywalk\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cakiGx{ocNN`A@FJl@?F?F?R?B?@@B@BRf@"
                     },
                     "start_location" : {
                        "lat" : 43.6432174,
                        "lng" : -79.3850874
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "157 ft",
                        "value" : 48
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 43.6429503,
                        "lng" : -79.38672960000001
                     },
                     "html_instructions" : "Lumiko nang bahagya \u003cb\u003epakanan\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "m_kiGjbpcNA^A\\?T@R@L"
                     },
                     "start_location" : {
                        "lat" : 43.6429469,
                        "lng" : -79.3861395
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "125 ft",
                        "value" : 38
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 43.642855,
                        "lng" : -79.38718730000001
                     },
                     "html_instructions" : "Lumiko nang bahagya \u003cb\u003epakaliwa\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eAng patutunguhan ay nasa kaliwa\u003c/div\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "m_kiG`fpcN@HD`@Hn@"
                     },
                     "start_location" : {
                        "lat" : 43.6429503,
                        "lng" : -79.38672960000001
                     },
                     "travel_mode" : "WALKING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "1.0 mi",
                  "value" : 1565
               },
               "duration" : {
                  "text" : "19 mins",
                  "value" : 1166
               },
               "end_address" : "93 Front St E, Toronto, ON M5E 1C3, Canada",
               "end_location" : {
                  "lat" : 43.64918,
                  "lng" : -79.371782
               },
               "start_address" : "290 Bremner Blvd, Toronto, ON M5V 3L9, Canada",
               "start_location" : {
                  "lat" : 43.642855,
                  "lng" : -79.38718730000001
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "282 ft",
                        "value" : 86
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 62
                     },
                     "end_location" : {
                        "lat" : 43.6429469,
                        "lng" : -79.3861395
                     },
                     "html_instructions" : "Dumiretso pa-\u003cb\u003esilangan\u003c/b\u003e patungo sa \u003cb\u003eThe PATH - Skywalk\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{~jiG|hpcNIo@Ea@AIAMAS?U@]@_@"
                     },
                     "start_location" : {
                        "lat" : 43.642855,
                        "lng" : -79.38718730000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 503
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 356
                     },
                     "end_location" : {
                        "lat" : 43.64499199999999,
                        "lng" : -79.381638
                     },
                     "html_instructions" : "Magpatuloy sa \u003cb\u003eThe PATH - Skywalk\u003c/b\u003e",
                     "polyline" : {
                        "points" : "m_kiGjbpcNSg@ACAC?A?C?S?G?GKm@AGOaAEm@Gi@[]EGUWEGCECAC?A?KBGBYHi@NIBA?A??AAC?CAGE]CQE]CQU_Bm@yECWEUAMEYAG?AAA?AA?A?GBUFA?A??AA?Gk@"
                     },
                     "start_location" : {
                        "lat" : 43.6429469,
                        "lng" : -79.3861395
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 239
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 174
                     },
                     "end_location" : {
                        "lat" : 43.6456412,
                        "lng" : -79.37910160000001
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakaliwa\u003c/b\u003e patungo sa \u003cb\u003eThe PATH - Union-VIA-GO\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "elkiGffocNYHA?A??AAA?ACMKcAQ_BGo@CUEYGo@S_BK{@Ea@"
                     },
                     "start_location" : {
                        "lat" : 43.64499199999999,
                        "lng" : -79.381638
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "118 ft",
                        "value" : 36
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 43.64592589999999,
                        "lng" : -79.37909689999999
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakaliwa\u003c/b\u003e patungo sa \u003cb\u003eBay St.\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gpkiGjvncNe@NIBIS"
                     },
                     "start_location" : {
                        "lat" : 43.6456412,
                        "lng" : -79.37910160000001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 701
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 544
                     },
                     "end_location" : {
                        "lat" : 43.64918,
                        "lng" : -79.371782
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakanan\u003c/b\u003e patungo sa \u003cb\u003eFront St W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eAng patutunguhan ay nasa kanan\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "arkiGjvncN?[WgCG[EYI]IYGSM]MUKWKOMQKMi@g@CUGOAEGKIUCISYO_@KMSe@Me@s@oBMWq@iBKYEIQm@Qc@W]K]Si@?M[gAGYIWEQMc@EOKQMUGSI_@CI"
                     },
                     "start_location" : {
                        "lat" : 43.64592589999999,
                        "lng" : -79.37909689999999
                     },
                     "travel_mode" : "WALKING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "0.9 mi",
                  "value" : 1399
               },
               "duration" : {
                  "text" : "19 mins",
                  "value" : 1122
               },
               "end_address" : "100 Queen St W, Toronto, ON M5H 2N1, Canada",
               "end_location" : {
                  "lat" : 43.6530077,
                  "lng" : -79.3827699
               },
               "start_address" : "93 Front St E, Toronto, ON M5E 1C3, Canada",
               "start_location" : {
                  "lat" : 43.64918,
                  "lng" : -79.371782
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 242
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 191
                     },
                     "end_location" : {
                        "lat" : 43.6481876,
                        "lng" : -79.3744653
                     },
                     "html_instructions" : "Dumiretso pa-\u003cb\u003etimog-kanluran\u003c/b\u003e sa \u003cb\u003eFront St E\u003c/b\u003e patungong \u003cb\u003eMarket St.\u003c/b\u003e",
                     "polyline" : {
                        "points" : "kfliGrhmcNBHH^FRLTJPDNLb@DPHVFXZfA?LRh@J\\V\\g@L\\|@RXJX"
                     },
                     "start_location" : {
                        "lat" : 43.64918,
                        "lng" : -79.371782
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "203 ft",
                        "value" : 62
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 43.6480118,
                        "lng" : -79.3750603
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakanan\u003c/b\u003e papunta sa \u003cb\u003eWellington St E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "e`liGlymcNA?DRBL@D@DVfA"
                     },
                     "start_location" : {
                        "lat" : 43.6481876,
                        "lng" : -79.3744653
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "26 ft",
                        "value" : 8
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 43.6480876,
                        "lng" : -79.375112
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakanan\u003c/b\u003e papunta sa \u003cb\u003eWellington St E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "a_liGb}mcNG@GF"
                     },
                     "start_location" : {
                        "lat" : 43.6480118,
                        "lng" : -79.3750603
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "226 ft",
                        "value" : 69
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 50
                     },
                     "end_location" : {
                        "lat" : 43.6481041,
                        "lng" : -79.3758168
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakaliwa\u003c/b\u003e papunta sa \u003cb\u003eWellington St E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "q_liGl}mcNAHAH@HBJAB?BD|@?BA@CRAB"
                     },
                     "start_location" : {
                        "lat" : 43.6480876,
                        "lng" : -79.375112
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 324
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 259
                     },
                     "end_location" : {
                        "lat" : 43.6474437,
                        "lng" : -79.3796361
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakaliwa\u003c/b\u003e patungo sa \u003cb\u003eWellington St E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "s_liGzancNF^BX^tCD\\Fh@Ff@[LNdABXNbA@Nh@|DHn@BJ"
                     },
                     "start_location" : {
                        "lat" : 43.6481041,
                        "lng" : -79.3758168
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 694
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 571
                     },
                     "end_location" : {
                        "lat" : 43.6530077,
                        "lng" : -79.3827699
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakanan\u003c/b\u003e patungo sa \u003cb\u003eBay St.\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eAng patutunguhan ay nasa kanan\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "o{kiGvyncN[HWJQD[JYHQDuAb@a@Ry@Ta@N}Af@KBUHa@JQDOD}@XYLUHoA^[LeBf@MBWt@GVG\\EJAB?@A@A@A@GFGBq@REByAb@Fj@GBMD"
                     },
                     "start_location" : {
                        "lat" : 43.6474437,
                        "lng" : -79.3796361
                     },
                     "travel_mode" : "WALKING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "cpkiGb_ocNb@pCPlAVpBAZLn@Dn@XxBR~AXxBXlBjCw@xAe@d@Qf@KVtBFt@C?Km@CCC?]FN`ALt@?N@\\@BRf@A^Ar@B`@Fj@Hn@Io@Gk@Ca@@s@@_@Sg@ACAE?g@Mu@UoBGi@[][_@MOYFoA\\AAIm@}AwLKg@c@JIm@]HESwAoMEa@e@NIBIS?[WgCMu@Sw@Uq@Ym@Ya@u@u@Ke@Wq@SYO_@KMSe@aAuC_AaCu@uBW]K]Si@?Mc@aBOi@Ss@Yg@Qs@CIBHPr@Xf@b@|Ab@`B?LRh@J\\V\\g@L\\|@RXJXBR^`BOHCRDTAFD`AETDb@b@nDLfAFf@[LR~APrAr@lFBJ[Hi@Pu@TgBh@{Ah@aDdAaCp@o@VkBl@sBj@_@lAOn@MLyC~@Fj@GBMD"
         },
         "summary" : "Front St W",
         "warnings" : [
            "Ang mga direksyon sa paglalakad ay nasa beta. Mag-ingat – Ang rutang ito ay maaaring mga bangketa of daanan ng mga taong naglalakad, na hindi nakalista."
         ],
         "waypoint_order" : [ 1, 0 ]
      }
   ],
   "status" : "OK"
}

```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
