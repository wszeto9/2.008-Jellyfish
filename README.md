# 2.008 Jellyfish
 PCA for Jellyfish themed yo-yos for my 2.008 project

# Ordering Instructions
- [Download the manufacturing data](https://github.com/wszeto9/2.008-Jellyfish/raw/main/jellyfish_lights/production.zip)
- Head to https://cart.jlcpcb.com/quote
- Click "Add Gerber File", upload the "Gerber.zip" file from the downloaded files
- Change PCB quantity to 25
- Change PCB Color to White
- Scroll down, select PCB Assembly
- By default they should be selected: Assemble top side, Economic, tooling holes added by JLCPCB, No confirm on parts placement
- Calculated price should show $30.10. Stop if this is different.
- Choose Confirm
- May ask to create an account, please do so.
- Upload BOM, CPL file. BOM file is named bom.csv, CPL file is named positions.csv
- Product description: Research\Education\DIY\Entertainment : Toy 950300
- Click next
- On top: 153 Parts detected, 153 parts confirmed. Confirm this. If numbers are off, stop and ask.
- Press next. Confirm: Price: $103.93. If this is correct, add to cart.
- Enter shipping info
- Choose DHL Express Worldwide for shipping
- Total should be $144.02 including shipping.
- For payment, you might get a $9 coupon. Feel free to use it.
- Please forward any emails within the next 24 hours if errors pop up. The parts go through human checks, and they will email you if there's issues.


# Version info:
A01: Initial design, has incorrect values for LEDs, R4, C3
A02: Updated values for LEDs, R4,C3. PCB is the same as A01, and only BOM components changed
B01: Final PCA shape (unreleased)