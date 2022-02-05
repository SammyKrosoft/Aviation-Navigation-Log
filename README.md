# Aviation Navigation Log - Instructions

This is an Excel  workbook to help planning a cross country flight. [Here's the download link for the Excel Workbook](https://github.com/SammyKrosoft/Aviation-Navigation-Log/raw/main/NAV%20Log%20Calculator%20-%20Flight%20Planner%20-%20E6B-like.xlsx)

Fill the following with your VFR map, upper winds tables, POH and compass swing table:

- True Course (**TC**) - with your protractor on your **VFR map**
- Wind Direction (**Wd**) and Wind speed (**Ws**) - check the **Upper Winds map at your planned altitude** from [Transport Canada website](https://flightplanning.navcanada.ca/cgi-bin/CreePage.pl?Langue=anglais&NoSession=NS_Inconnu&Page=Fore-obs%2Ffd-text&TypeDoc=html)
- True Air Speed (**TAS**) - from your **Pilot Operating Handbook** (**POH**)
- Magnetic Variation (**VAR**) - from your **VFR map**
- Compass Magnetic Deviation (**DEV**) - **compass swing table** from your plane (see the photo on the **Mag Dev Compass Sample** tab for an example) - it's updated every 12 months
- Distance (**DIST**) - with your plotter on your **VFR map**

and the spreadsheet will calculate for you the Wind Correction Angle (**WCA**), True Heading (**TH**), Compass Heading (**CH**), Ground Speed (**GS**), Fuel consumption, Fuel remaining, Estimated Time Enroute (**ETE**) and Estimated Time of Arrival (**ETA**).

> NOTE: the calculated cells are in orange (light and lighter so that it's easy on ink when printing), and by default the sheets are protected to avoid accidental deletion of the formulas for WCA/TH/CH/GS/Fuel/ETE/ETA - headers (TC/Wd/Ws/...) are also protected, and you can unprotect the sheets anytime to customize the logs, it's not password protected.

# This Workbook has several tabs

- **Formulas**: shows the trigonometric math formulas used in the Nav Logs tables to calculate the WCA
- **Nav Log (not foldable)**: you fill (TC, Wd, Ws, TAS, VAR, DEV, Dist) and it calculates the above values (WCA, TH, CH, GS,ETE, ETA,...). If you fold it, you won't be able to see the checkpoint names and the CH/GS/ETE/ETA/Fuel info
- **Nav Log (Foldable)**: same as above, but I moved the checkpoints names column so that you can fold and use the relevant part of your Nav Log  in flight (the part that shows the CH, Dist, GS, ETE, ETA, Fuel consumed, Fuel remainig. Indeed the TC, Wd, Ws, TAS, VAR and DEV are of no use while flying through your navigation checkpoints; only the CH, GS, ETE, ETA and Fuel information are the metrics you check (and correct with the actual values) in flight.
- **Cross Wind Calculator**: illustrates and calculate the cross-winds (and the wind correction angle for illustration purposes); Along with the calculation of the cross-wind/head-wind components, I put there 2 compass-style schemas: one with the plane and wind headings, and one with the runway orientation and wind heading
- **Mag Dev Compass Sample**: that's just a photo of how the compass swing table looks like in a plane.

![image](https://user-images.githubusercontent.com/33433229/152469497-25c7a614-06dc-48c0-a4a4-f1ffc709a249.png)

# Screenshots

Showing only the **Nav Log (Foldable)** here as the **Nav Log (non foldable)** is exactly the same in a different disposition (checkpoint names is on the first column instead of in the middle-right)

## Nav Log (Foldable) tab

![image](https://user-images.githubusercontent.com/33433229/152470388-bad3fa2c-ba66-42e0-bac4-dd4f7daad7e5.png)

## Cross Winds tab

![image](https://user-images.githubusercontent.com/33433229/152625600-6da9d814-05f6-43f7-9094-035be891522c.png)
