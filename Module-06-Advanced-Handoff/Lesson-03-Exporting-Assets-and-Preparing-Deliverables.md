# Lesson 03: Exporting Assets and Preparing Deliverables

## គោលបំណង

ជ្រើស content សម្រាប់ export, កំណត់ format និង scale ឱ្យសមនឹងការប្រើប្រាស់ ហើយរៀបចំ assets ដើម្បីឱ្យ developer អាចកំណត់ទីតាំងបានងាយ។

## 1. ជ្រើស Format តាមការប្រើប្រាស់

- PNG: raster image ដែលមាន transparency។
- JPG: រូបថត ឬរូបភាពដែលមិនត្រូវការ transparency។
- SVG: vector icon/illustration ដែលគួររក្សា scalability; សូមពិនិត្យ output និង simplify settings។
- PDF: ឯកសារឬ artwork សម្រាប់ចែករំលែក/បោះពុម្ពតាមតម្រូវការ។

ជ្រើស format តាម integration និង quality requirement របស់ project។ កុំ export text/logo ជា raster ប្រសិនបើ vector format សមស្របជាង។

## 2. Export Configuration

1. ជ្រើស layer/frame ដែលត្រូវ export។
2. បន្ថែម Export configuration នៅ right sidebar។
3. ជ្រើស format និង scale/size ដែល developer ត្រូវការ។
4. Preview output ប្រសិនបើមាន។
5. Export ហើយពិនិត្យ file name, transparency, crop និង resolution។

Scale ដូចជា 1x/2x គួរត្រូវបានជ្រើសតាម target platform និង asset requirements។ កុំសន្មតថា 2x តែងតែត្រឹមត្រូវសម្រាប់គ្រប់ asset។

## 3. Naming និង Export Organization

ដាក់ឈ្មោះ assets តាម semantic role ដូចជា icon/search, logo/brand, illustration/empty-state។ Slash-separated names អាចត្រូវបាន export ជា folder hierarchy អាស្រ័យលើ Figma behavior។ សម្រប naming ជាមួយ project conventions របស់ developer។

សម្រាប់ icon set សូមរក្សាទំហំ artboard និង alignment ឱ្យស្របគ្នា។ សម្រាប់ images សូមពិនិត្យ crop និង focal point ម្ដងទៀត។

## 4. Asset Handoff Checklist

- Export format, dimensions និង color profile ត្រូវបានកំណត់។
- SVG icons មិនមាន unwanted backgrounds ឬ excessive layers។
- PNG transparency ត្រឹមត្រូវ។
- Filenames មានន័យ និងមិនស្ទួន។
- Asset មាន alt-text/context ប្រសិនបើត្រូវការសម្រាប់ accessibility documentation។
- Developer ដឹងថាអ្វីអាចបង្កើតឡើងវិញដោយ CSS និងអ្វីត្រូវប្រើ asset។

## អនុវត្ត

ជ្រើស logo, icon, product image និង one illustration។ កំណត់ export formats តាម use case រួច export។ បើក files ដើម្បីពិនិត្យ transparency, crop, dimensions និង naming មុនប្រគល់ឱ្យ developer។

## Quick Check

1. តើពេលណា PNG សមជាង JPG?
2. តើអ្វីខ្លះត្រូវពិនិត្យក្រោយ export?
3. ហេតុអ្វី naming assets សំខាន់សម្រាប់ handoff?
4. តើ Dev Mode មាន export controls នៅកន្លែងណា?

## ឯកសារយោង

- [Export static designs from Figma](https://help.figma.com/hc/en-us/articles/360040028114-Export-static-designs-from-Figma)
- [Export formats and settings for static designs](https://help.figma.com/hc/en-us/articles/13402894554519-Export-formats-and-settings-for-static-designs)
