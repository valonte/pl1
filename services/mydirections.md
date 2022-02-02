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
               "lat" : 43.6530882,
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
                  "text" : "11 min",
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
                        "text" : "5 min",
                        "value" : 282
                     },
                     "end_location" : {
                        "lat" : 43.644648,
                        "lng" : -79.3850638
                     },
                     "html_instructions" : "Dumiretso pa-\u003cb\u003ekanluran\u003c/b\u003e sa \u003cb\u003eFront St W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cpkiGb_ocNFTRxADT@JDVBTBLBPFXNvAAZNn@@f@@FTbBBN@DBVBXF`@@JBVFb@F`@DZBNHn@?BJh@"
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
                        "text" : "2 min",
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
                        "text" : "2 min",
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
                  "text" : "19 min",
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
                        "text" : "6 min",
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
                        "text" : "3 min",
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
                        "text" : "9 min",
                        "value" : 544
                     },
                     "end_location" : {
                        "lat" : 43.64918,
                        "lng" : -79.371782
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakanan\u003c/b\u003e patungo sa \u003cb\u003eFront St W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eAng patutunguhan ay nasa kanan\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "arkiGjvncN?[WgCG[EYI]IYGSM]MUKWKOMQKMi@s@KYAEGKIUCISYO_@KMSe@Me@s@oBMWq@iBKYEIQm@Qc@W]K]Si@?M[gAGYIWEQMc@EOKQMUGSI_@CI"
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
                  "text" : "0.8 mi",
                  "value" : 1317
               },
               "duration" : {
                  "text" : "18 min",
                  "value" : 1083
               },
               "end_address" : "100 Queen St W, Toronto, ON M5H 2N1, Canada",
               "end_location" : {
                  "lat" : 43.6518419,
                  "lng" : -79.3826469
               },
               "start_address" : "93 Front St E, Toronto, ON M5E 1C3, Canada",
               "start_location" : {
                  "lat" : 43.64918,
                  "lng" : -79.371782
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 181
                     },
                     "duration" : {
                        "text" : "2 min",
                        "value" : 135
                     },
                     "end_location" : {
                        "lat" : 43.6485024,
                        "lng" : -79.3739001
                     },
                     "html_instructions" : "Dumiretso pa-\u003cb\u003etimog-kanluran\u003c/b\u003e sa \u003cb\u003eFront St E\u003c/b\u003e patungong \u003cb\u003eMarket St.\u003c/b\u003e",
                     "polyline" : {
                        "points" : "kfliGrhmcNBHH^FRLTJPDNLb@DPHVFXZfA?LRh@J\\V\\g@L"
                     },
                     "start_location" : {
                        "lat" : 43.64918,
                        "lng" : -79.371782
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 551
                     },
                     "duration" : {
                        "text" : "8 min",
                        "value" : 473
                     },
                     "end_location" : {
                        "lat" : 43.6530882,
                        "lng" : -79.37583819999999
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakanan\u003c/b\u003e patungo sa \u003cb\u003eChurch St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cbliGzumcNE@]NgBj@SFm@RGBs@R_@LE?u@VUPS?]JOFgA\\_@L_Bf@]J{Af@E@[Jk@PI@IBMDOFUH"
                     },
                     "start_location" : {
                        "lat" : 43.6485024,
                        "lng" : -79.3739001
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 574
                     },
                     "duration" : {
                        "text" : "8 min",
                        "value" : 466
                     },
                     "end_location" : {
                        "lat" : 43.6518419,
                        "lng" : -79.3826469
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakaliwa\u003c/b\u003e patungo sa \u003cb\u003eQueen St E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "y~liG~ancNFZFj@Hh@Fb@DV?F@@Jp@d@vDFj@j@dEFf@[VJt@B^BNDXVrBFZHl@Hl@DVLdANp@NfAKZF\\"
                     },
                     "start_location" : {
                        "lat" : 43.6530882,
                        "lng" : -79.37583819999999
                     },
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "36 ft",
                        "value" : 11
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 43.6518419,
                        "lng" : -79.3826469
                     },
                     "html_instructions" : "Lumiko \u003cb\u003epakanan\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eAng patutunguhan ay nasa kaliwa\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_wliGplocN"
                     },
                     "start_location" : {
                        "lat" : 43.6518419,
                        "lng" : -79.3826469
                     },
                     "travel_mode" : "WALKING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "cpkiGb_ocNb@pCPlAVpBAZNn@Bn@XrBPxAThBR~AJh@LCjA]~Bw@`@Mb@KRG?FL|@RdBE?Km@CCa@F\\~B?`@Vn@C|@@h@RhBSiBAi@B}@Wo@?a@]_CMwAa@e@_@e@GAMBuA`@CACOaBgMKu@c@JCAGk@YHA?A?AEoAaLQ}Ao@RIS?[_@cDOw@Qm@s@{AY_@i@s@KYIQM_@SYO_@KMSe@aAuC_AaCu@uBW]K]Si@?Mc@aBOi@Ss@Yg@Qs@CIBHPr@Xf@b@|Ab@`B?LRh@J\\V\\m@NgEvAaBd@u@VUPS?]JwAd@_Ct@{C`AmA\\e@PNfAVlBz@vGr@lF[VJt@Fn@\\lC`@nC\\vBNfAKZF\\"
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
