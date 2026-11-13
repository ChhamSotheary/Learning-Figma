# Lesson 04: Building a Responsive Layout

## គោលបំណង

យក layout principles, Auto Layout និង constraints មកប្រើក្នុង mini project តែមួយ។ អ្នកនឹងបង្កើត responsive event landing page ពី desktop ទៅ mobile ហើយរៀបចំ layers ឱ្យងាយកែ និង handoff។

## Project Brief

បង្កើត landing page សម្រាប់ event មួយដែលមាន header/navigation/CTA, hero title/summary/date, speaker cards, agenda និង footer មាន contact details។ គោលដៅគឺឱ្យអ្នកប្រើរកព័ត៌មាន event និងចុះឈ្មោះបានរហ័ស។

## ជំហានទី ១៖ រៀបចំ Frames

បង្កើត Desktop, Tablet និង Mobile frames។ ដាក់ឈ្មោះដូចជា Event / Desktop, Event / Tablet និង Event / Mobile។ ប្រើ Layout guides នៅ desktop ដើម្បីកំណត់ content width និង columns។ ជ្រើសទំហំតាម project brief និងឧបករណ៍ដែលចង់គាំទ្រ; ទំហំ frame គ្រាន់តែជាចំណុចចាប់ផ្ដើម មិនមែនស្តង់ដារតែមួយសម្រាប់គ្រប់ឧបករណ៍ទេ។

## ជំហានទី ២៖ បង្កើត Desktop Layout

- រៀបចំ header ជា horizontal Auto Layout។
- ដាក់ hero content និង artwork ជាពីរ columns។
- រៀបចំ speaker cards ជា row/grid។
- ប្រើ vertical Auto Layout សម្រាប់ agenda items។
- កំណត់ spacing និង alignment ឱ្យស្របគ្នា។

បង្កើត components ប្រសិនបើ card ឬ button ត្រូវប្រើច្រើនដង។ ក្នុងមេរៀននេះ ផ្តោតលើ layout behavior មុនពង្រីក design system។

## ជំហានទី ៣៖ ប្ដូរទៅ Tablet និង Mobile

កុំគ្រាន់តែបង្រួម desktop frame។ សម្រេចតាម content៖ Navigation អាចប្ដូរទៅ menu; hero columns អាចដាក់ជាជួរឈរតែមួយ; speaker cards អាចបង្ហាញពីរ columns លើ tablet និងមួយលើ mobile; agenda ត្រូវរក្សាអត្ថបទអានបាន; CTA ត្រូវមើលឃើញ និងចុចងាយ។

ប្រើ Auto Layout សម្រាប់ content flow និង constraints សម្រាប់ child layers ក្នុង frame ធម្មតាដែលត្រូវរក្សាទីតាំងជាប់គែម។

## ជំហានទី ៤៖ សាកល្បង Content Variations

សាក title វែង, speaker name ពីរបន្ទាត់ និង agenda description វែង។ ពិនិត្យថា card កើនកម្ពស់តាម content, button រក្សា padding, columns មិនបង្ហាប់អត្ថបទ, image មិនបាត់ focal point និងគ្មាន overflow ដែលមិនចង់បាន។

## ជំហានទី ៥៖ Prototype និង Review

បង្កើត flow ពី landing page ទៅ registration confirmation screen។ សាក preview នៅទំហំផ្សេងៗ ហើយពិនិត្យ៖

- Hierarchy និង spacing ស្របគ្នា។
- Layers និង frames មានឈ្មោះច្បាស់។
- Layout behavior មិនខូចពេល resize។
- Text, image និង buttons មិន overflow។
- Primary CTA ត្រូវបានរកឃើញងាយ។
- Mobile layout មិនមែនគ្រាន់តែ desktop version តូចជាង។

## Deliverables

- Figma file មាន Desktop, Tablet និង Mobile frames។
- Auto Layout សម្រាប់ button, speaker card និង agenda row។
- Prototype flow មួយទៅ confirmation screen។
- Link ឬ screenshot សម្រាប់ review។
- កំណត់ចំណាំអំពី breakpoint decisions និង trade-offs។

## Quick Check

1. ហេតុអ្វី responsive layout មិនមែនគ្រាន់តែបង្រួម desktop?
2. តើ elements ណាខ្លះគួរប្រើ Auto Layout?
3. តើនៅកន្លែងណាគួរប្រើ constraints?
4. តើ content variations ជួយរកបញ្ហាអ្វី?
5. តើអ្នកនឹងពន្យល់ breakpoint decisions ទៅ developer ដូចម្តេច?

## ឯកសារយោង

- [Guide to auto layout in Figma](https://help.figma.com/hc/en-us/articles/360040451373-Guide-to-auto-layout-in-Figma)
- [Apply constraints to define how layers resize](https://help.figma.com/hc/en-us/articles/360039957734-Apply-constraints-to-define-how-layers-resize)
- [Play your prototypes](https://help.figma.com/hc/en-us/articles/360040318013-Play-your-prototypes)
