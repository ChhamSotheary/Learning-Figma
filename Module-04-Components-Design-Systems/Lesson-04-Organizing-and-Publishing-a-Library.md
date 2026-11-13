# Lesson 04: Organizing and Publishing a Design Library

## គោលបំណង

រៀបចំ components, styles និង variables ជា library ដែលអ្នករចនាអាចប្រើឡើងវិញ និងយល់ពីដំណើរការ publish/update library ដោយមិនបំផ្លាញ design ដែលកំពុងប្រើប្រាស់។

## 1. រៀបចំ Source File

បង្កើត design file សម្រាប់ library ដាច់ដោយឡែកពី product screens។ រៀបចំ pages ដូចជា Foundations, Components និង Patterns។ ដាក់ឈ្មោះ assets ឱ្យស្របគ្នា និងលុប draft/duplicate components ដែលមិនត្រូវចែករំលែក។

ដាក់ documentation នៅក្នុង component description ឬ page documentation៖

- គោលបំណង និងពេលណាគួរប្រើ។
- Properties/variants ដែលអាចកែបាន។
- Accessibility និង contrast notes។
- ករណីដែលមិនគួរប្រើ។
- អ្នកទទួលខុសត្រូវ និង version/changelog ប្រសិនបើមាន។

## 2. Publish Library

Library publishing អនុញ្ញាតឱ្យ files ផ្សេងប្រើ components, styles និង variables ពី source file។ ដើម្បី publish ត្រូវមាន edit access ហើយ plan/workspace អាចកំណត់ថាតើអាច share library ឆ្លង file បានឬទេ។ Starter plan អាចបង្កើត assets ក្នុង file ប៉ុន្តែការបោះពុម្ព library ទៅប្រើក្នុង files ផ្សេងមាន plan limitations។

លំហូរទូទៅ៖

1. បើក file ដែលមាន components/styles/variables។
2. ទៅ Assets និងបើក Libraries។
3. ជ្រើស source file ហើយ publish។
4. បន្ថែម description នៃគោលបំណង និងការផ្លាស់ប្ដូរ។
5. បើក library ក្នុង consumer file ហើយបញ្ចូល assets ដែលចាំបាច់។

ពិនិត្យ UI និង plan ក្នុង account របស់អ្នក ព្រោះ menus និងសិទ្ធិអាចខុសគ្នាតាម workspace។

## 3. Review Library Updates

ពេល source library ផ្លាស់ប្ដូរ consumer files អាចមាន updates ឱ្យ review។ មុន accept សូមពិនិត្យ៖

- តើ component changed, added ឬ removed?
- តើ overrides នៅ instances រក្សាបានទេ?
- តើ layout, contrast និង responsive behavior នៅត្រឹមត្រូវទេ?
- តើ update គួរអនុវត្តភ្លាម ឬត្រូវរង់ចាំការសម្រេចរបស់ team?
- តើ documentation និង changelog បានធ្វើបច្ចុប្បន្នភាពទេ?

កុំ accept updates ដោយស្វ័យប្រវត្តិលើ screens សំខាន់ៗ ដោយមិនពិនិត្យផលប៉ះពាល់។

## 4. Governance និង Contribution

កំណត់ច្បាប់ថាអ្នកណាអាចបន្ថែម/កែ assets និងរបៀប review។ ប្រើ naming conventions និង issue/request process ដើម្បីជៀសវាង duplicate components។ កំណត់កម្រិត compatibility៖ breaking component changes ត្រូវមាន migration notes និងពេលវេលាឱ្យ consumer files កែតាម។

## អនុវត្ត

បង្កើត mini library មាន button components, input, card, text styles និង color/spacing variables។ Publish ប្រសិនបើ plan អនុញ្ញាត ឬរៀបចំ assets ក្នុង file ជា practice library។ បង្កើត consumer page មួយ ប្រើ assets ហើយធ្វើ update មួយ ដូចជា button padding។ Review update នៅ consumer file និងកត់ត្រាផលប៉ះពាល់។

## កំហុសទូទៅ

- Publish source file ដែលមាន draft assets និងឈ្មោះមិនច្បាស់។
- មិនពន្យល់ការផ្លាស់ប្ដូរ library។
- ធ្វើ breaking change ដោយគ្មាន migration notes។
- សន្មតថា plan ទាំងអស់គាំទ្រ library sharing ដូចគ្នា។
- បង្កើត components ច្រើនដោយគ្មានអ្នកថែទាំ។

## Quick Check

1. តើ source library file ខុសពី consumer design file ដូចម្តេច?
2. តើត្រូវ review អ្វីមុនទទួល library update?
3. ហេតុអ្វីត្រូវមាន naming convention និង governance?
4. តើ plan អាចប៉ះពាល់ការបោះពុម្ព library ដូចម្តេច?

## ឯកសារយោង

- [Publish a library](https://help.figma.com/hc/en-us/articles/360025508373-Publish-a-library)
- [Explore component properties](https://help.figma.com/hc/en-us/articles/5579474826519-Explore-component-properties)
