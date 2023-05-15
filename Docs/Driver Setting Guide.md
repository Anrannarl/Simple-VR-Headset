# Driver Setting Guide
For the general setup guide, please refer to HadesVR. https://github.com/HadesVR/HadesVR  
To use the Vive tracker for headset tracking, please refer to this link. https://github.com/Yersi88/WMR-and-Vive-Tracker  
The tracker position needs to be offset to the center position of your eyes.  
You can find the example tracker json files in the Vive Tracker JSON folder.  
Note that they are for reference only. You need to use json files extracted from your own Vive tracker.  

Setting profiles:  

GearVR Black  
"FOV" : 90,  
"ViewportZoom" : 0.79,  
"Red_K1" : 0.50,  
"Red_K2" : 2.4,  
"Green_K1" : 0.55,  
"Green_K2" : 2.4,  
"Blue_K1" : 0.7,  
"Blue_K2" : 2.4,  

GearVR White  
"FOV" : 90,  
"ViewportZoom" : 0.80,  
"Red_K1" : 0.70,  
"Red_K2" : 1.7,  
"Green_K1" : 0.75,  
"Green_K2" : 1.7,  
"Blue_K1" : 0.9,  
"Blue_K2" : 1.7,  

Google Cardboard V2  
"FOV" : 80,  
"ViewportZoom" : 0.87,  
"Red_K1" : 0.29,  
"Red_K2" : 0.56,  
"Green_K1" : 0.34,  
"Green_K2" : 0.56,  
"Blue_K1" : 0.48,  
"Blue_K2" : 0.56,  

"IPD" : 0.063,  
"DistanceBetweenLenses" : 0.063,  
"DistanceBetweenViews" : 0.063,  
"DisplayWidth" : 0.12096,  

"IPD" should be set to your real IPD  
"DistanceBetweenLenses" should be set to the physical distance between the two lens centers    
"DistanceBetweenViews" should be set to the same value as "DistanceBetweenLenses"  
"DisplayWidth" is the physical width of the display  

