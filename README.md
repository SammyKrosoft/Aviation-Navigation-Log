# Introduction

This repository has nothing to do with Microsoft Exchange, Microsoft O365 or Powershell. It's just about one of my passions: **aviation**. I got back into the sky after 20 years grounded, and I recently reviewed cross-country navigation, so I decided to make an Excel tool to help out in the navigation preparation.

As I'm a visual person, I also included compasses showing the wind direction and runway orientation (as well as a plane heading) that moves as you change the plane/wind/runway headings and calculate your WCA and the crosswind (and headwind) components - which are calculated using math trigonometry which I won't cover the details here.


# Aviation Navigation Log - Instructions

This is an Excel  workbook to help planning a cross country flight. 

![image](https://user-images.githubusercontent.com/33433229/152830504-c5bbf66d-0618-4933-88dc-6686c52b8400.png)

[Here's the download link for this Excel Workbook](https://github.com/SammyKrosoft/Aviation-Navigation-Log/raw/main/NAV%20Log%20Calculator%20-%20Flight%20Planner%20-%20E6B-like.xlsx) *(right-click "Save link as" or click on the link to open on a browser supporting view only Excel files)*

Fill the following with your VFR map, upper winds tables, POH and compass swing table:

1. True Course (**TC**) - with your protractor on your **VFR map**

2. Altitude (**ALT**) - it's not used for calculations, just to remember your planned altitude. 
> Note: Remember the cruising altitude rule above 3000 FT ASL
> - Right or East half - **0° - 179°** => VFR : **odd + 500ft** (3500, 5500, 7500,...)
> - Left or West half - **180° - 359°** => VFR : **even + 500ft** (4500, 6500, 8500, ...)
> 
> These are the magnetic course (TC + VAR) - therefore I will need to put the VAR column closer to TC, and remove the TH (True Heading) column and replace it with an MC (Magnetic course) column before the WCA (Wind Correctopn Angle) => then the MH (Magnetic Heading) will be MC + WCA... but that will be for the V2 of the workbook !

3. Wind Direction (**Wd**) and Wind speed (**Ws**) - check the **Upper Winds map at your planned altitude**, for example from [Transport Canada website](https://flightplanning.navcanada.ca/cgi-bin/CreePage.pl?Langue=anglais&NoSession=NS_Inconnu&Page=Fore-obs%2Ffd-text&TypeDoc=html) for Canada

4. Temperature (**TEMP**) - it's also not used for calculations, just as a reference.

5. True Air Speed (**TAS**) - from your **Pilot Operating Handbook** (**POH**)

6. Magnetic Variation (**VAR**) - from your **VFR map**

7. Compass Magnetic Deviation (**DEV**) - **compass swing table** from your plane (see the photo on the **Mag Dev Compass Sample** tab for an example) - it's updated every 12 months

8. Distance (**DIST**) - with your plotter on your **VFR map**

and the spreadsheet will calculate for you the Wind Correction Angle (**WCA**), True Heading (**TH**), Compass Heading (**CH**), Ground Speed (**GS**), Fuel consumption, Fuel remaining, Estimated Time Enroute (**ETE**) and Estimated Time of Arrival (**ETA**).

> NOTE: the calculated cells are in orange (light and lighter so that it's easy on ink when printing), and by default the sheets are protected to avoid accidental deletion of the formulas for WCA/TH/CH/GS/Fuel/ETE/ETA - headers (TC/Wd/Ws/...) are also protected, and you can unprotect the sheets anytime to customize the logs, it's not password protected.

# This Workbook has several tabs

- **Formulas**: shows the trigonometric math formulas used in the Nav Logs tables to calculate the WCA
- **Nav Log (not foldable)**: you fill (TC, Wd, Ws, TAS, VAR, DEV, Dist) and it calculates the above values (WCA, TH, CH, GS,ETE, ETA,...). If you fold it, you won't be able to see the checkpoint names along with the CH/GS/ETE/ETA/Fuel info without unfolding your sheet
- **Nav Log (Foldable)**: same as above, but I moved the checkpoints names column so that you can fold and use the relevant part of your Nav Log  in flight (the part that shows the CH, Dist, GS, ETE, ETA, Fuel consumed, Fuel remainig. Indeed the TC, Wd, Ws, TAS, VAR and DEV are of no use while flying through your navigation checkpoints; only the CH, GS, ETE, ETA and Fuel information are the metrics you check (and correct with the actual values) in flight.
- **Cross Wind Calculator**: illustrates and calculate the cross-winds (and the wind correction angle for illustration purposes); Along with the calculation of the cross-wind/head-wind components, I put there 2 compass-style schemas: one with the plane and wind headings, and one with the runway orientation and wind heading
- **Mag Dev Compass Sample**: that's just a photo of what the compass swing table looks like in a plane.

![image](https://user-images.githubusercontent.com/33433229/152469497-25c7a614-06dc-48c0-a4a4-f1ffc709a249.png)

# Screenshots

Showing only the **Nav Log (Foldable)** here as the **Nav Log (non foldable)** is exactly the same in a different disposition (checkpoint names is on the first column instead of in the middle-right)

## Nav Log (Foldable) tab

![image](https://user-images.githubusercontent.com/33433229/152470388-bad3fa2c-ba66-42e0-bac4-dd4f7daad7e5.png)

## Cross Winds tab

![image](https://user-images.githubusercontent.com/33433229/152667589-9dd85eee-d11a-4fba-8ded-6186a3859be3.png)


