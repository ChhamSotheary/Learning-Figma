# Lesson 02: Variants and Component Properties

## គោលបំណង

រៀបចំ components ដែលមានរូបរាងស្រដៀងគ្នាជា variants ហើយប្រើ component properties ដើម្បីបង្ហាញថា instance អាចប្ដូរអ្វីបាន។

## 1. Variants និង Component Set

Variants ជួយដាក់ versions ដែលពាក់ព័ន្ធគ្នាក្នុង component set តែមួយ។ ឧទាហរណ៍ button អាចមាន size និង state ផ្សេងៗ។ Figma រៀបចំ variants ក្នុង component set ដែលមាន properties/values។

ប្រើ variants ពេល variants ទាំងនោះនៅតែមានគោលបំណងដូចគ្នា និងមាន structure ស្រដៀងគ្នា។ កុំបង្កើត variant combination គ្រប់យ៉ាងដោយស្វ័យប្រវត្តិ ប្រសិនបើវាធ្វើឱ្យ set ធំពេក និងពិបាករក។

## 2. រៀបចំ Variant Properties

ឧទាហរណ៍ button properties៖

- Type: Primary, Secondary។
- Size: Small, Medium, Large។
- State: Default, Hover, Disabled។

ដាក់ property/value ឱ្យមានឈ្មោះច្បាស់ និងស្របគ្នា។ មិនចាំបាច់បង្កើត component សម្រាប់គ្រប់បន្សំទេ; បង្កើតតែបន្សំដែល product ត្រូវប្រើ។

## 3. Component Property Types

Component properties អាចជួយបង្ហាញអ្វីដែលអ្នកប្រើ instance អាចកែបាន៖

- Boolean: បង្ហាញ/លាក់ layer ដូចជា icon។
- Text: ប្ដូរ label ឬ text content។
- Instance swap: ប្ដូរ nested component ដូចជា icon។
- Variant: ប្ដូរ attributes ដូចជា size/state។
- Slot: បង្កើតតំបន់ content ដែលអាចបន្ថែម ឬរៀបចំ content ក្នុង instance តាម workflow ដែល Figma គាំទ្រ។

មុខងារ និង UI អាចផ្លាស់ប្ដូរតាម Figma updates និង plan។ សូមមើល component property controls នៅក្នុង Design sidebar របស់អ្នក។

## 4. បង្កើត Button Component Set

1. បង្កើត button design មូលដ្ឋានពីរ ឬច្រើន។
2. ជ្រើស components ដែលមានគោលបំណងដូចគ្នា។
3. បង្កើត component set/variants។
4. កំណត់ variant properties និង values ឱ្យច្បាស់។
5. បន្ថែម text property សម្រាប់ button label។
6. បន្ថែម Boolean property សម្រាប់ icon visibility ប្រសិនបើវាមានប្រយោជន៍។
7. សាកប្ដូរ properties នៅ instance ហើយពិនិត្យ layout។

## 5. Documentation និង Guardrails

Properties ល្អគួរប្រាប់អ្នកប្រើថាត្រូវកែអ្វី។ បន្ថែម description/documentation ប្រសិនបើមានការកំណត់ប្រើប្រាស់ ដូចជា contrast, minimum button size ឬការប្រើ state Disabled។ ជៀសវាងឈ្មោះ property មិនច្បាស់ និង variants ស្ទួនដែលខុសគ្នាតិចតួចដោយគ្មានហេតុផល។

## អនុវត្ត

បង្កើត button component set មាន type Primary/Secondary, size Medium/Large និង state Default/Disabled។ បន្ថែម text property សម្រាប់ label និង optional icon។ សាកប្រើលើទំព័រមួយ ហើយផ្លាស់ប្ដូរតែ properties ដើម្បីបង្កើត versions ផ្សេងៗ។

## កំហុសទូទៅ

- បង្កើត variants ដែលមិនមានរចនាសម្ព័ន្ធ ឬគោលបំណងដូចគ្នា។
- បង្កើតបន្សំច្រើនពេកដែលគ្មានប្រើប្រាស់។
- ប្រើ property names មិនច្បាស់។
- មិនកំណត់ default variant ដែលសមស្រប។
- រំពឹងថា properties នឹងជំនួសការសរសេរឯកសារណែនាំទាំងអស់។

## Quick Check

1. Variant property ខុសពី Text property ដូចម្តេច?
2. តើ Boolean property អាចគ្រប់គ្រងអ្វី?
3. ហេតុអ្វីមិនគួរបង្កើតគ្រប់ combination?
4. តើ component documentation ជួយអ្នកប្រើដូចម្តេច?

## ឯកសារយោង

- [Create and use variants](https://help.figma.com/hc/en-us/articles/360056440594-Create-and-use-variants)
- [Explore component properties](https://help.figma.com/hc/en-us/articles/5579474826519-Explore-component-properties)
