# aluminum-calculator

A WordPress plugin that calculates the weight of different aluminum profiles based on their dimensions.

Aluminum Profile Calculator is a versatile WordPress plugin that allows users to calculate the theoretical weight of various aluminum profiles. Users can select from 10 different profile types, enter dimensions, and get accurate weight calculations.
Features

10 different aluminum profile types (Sheet, U Profile, Solid Rod, etc.)
Dynamic form fields that change based on the selected profile
Specific weight selection option
Unit and total weight calculations
Mobile-responsive design
Multi-language support with translation ready files
Easy integration with shortcode [aluminum_calculator]

Installation

Upload the aluminum-calculator folder to the /wp-content/plugins/ directory
Activate the plugin through the 'Plugins' menu in WordPress
Place the shortcode [aluminum_calculator] in any page or post

Usage

Select a profile type from the left panel
Fill in the dimensions in the middle panel
Select the specific weight of the material (if different from default)
Click "CALCULATE" to get the weight result

Calculation Formulas
The plugin uses the following formulas for weight calculations:

Sheet: width * length * thickness * specific weight / 1000000
U Profile: ((width * length) - (inner width * (length - thickness))) * thickness * specific weight / 1000000
Solid Rod: π * (diameter/2)² * length * specific weight / 1000000
Flat Bar: width * thickness * length * specific weight / 1000000
Square Profile: width * width * length * specific weight / 1000000
Angle: ((width1 * thickness) + (width2 * thickness) - (thickness * thickness)) * length * specific weight / 1000000
Rectangular Profile: ((width * length) - ((width - 2thickness) * (length - 2thickness))) * specific weight / 1000
Tube Profile: π * ((outer diameter/2)² - (inner diameter/2)²) * length * specific weight / 1000000
Square Box Profile: ((width * width) - ((width - 2thickness) * (width - 2thickness))) * length * specific weight / 1000000
T Profile: ((width * thickness) + ((length - thickness) * thickness)) * specific weight * length / 1000000

Translation
This plugin is translation-ready. To translate it to your language:

Install the "Loco Translate" plugin
Navigate to Loco Translate > Plugins > Aluminum Profile Calculator
Create a new language translation
Translate all strings and save

A Turkish translation is included in the /languages folder.

Customization

You can customize the appearance by editing the style.css file. To add new profile types or modify calculation formulas, edit the main plugin file (aluminum-calculator.php) and the JavaScript file (script.js).

License

This plugin is licensed under the GPL v2 or later.

Author
Created by Halim KILIÇ

Support

For support, please create an issue in this GitHub repository or contact me at hello@wptr.com
