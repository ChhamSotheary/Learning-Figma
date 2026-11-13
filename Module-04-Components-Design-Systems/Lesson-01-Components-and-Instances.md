# Lesson 01: Components and Instances

## គោលបំណង

យល់ពីភាពខុសគ្នារវាង Main component និង Instance ហើយបង្កើត reusable UI elements ដើម្បីកាត់បន្ថយការងារដដែលៗ និងរក្សា design ឱ្យស្របគ្នា។

## 1. Component ជាអ្វី?

Component គឺជា element ឬ group ដែលអាចប្រើឡើងវិញ។ ឧទាហរណ៍៖ button, input field, icon button, navigation item និង product card។ កែ Main component នឹងអាចធ្វើឱ្យ instances ដែលប្រើវាទទួលការធ្វើបច្ចុប្បន្នភាពផងដែរ លើកលែងតែ properties ដែល instance បាន override។

- Main component: ប្រភពនៃ component។
- Instance: ច្បាប់ចម្លងភ្ជាប់ទៅ Main component ដែលអាចដាក់ក្នុង design។
- Component set: ក្រុម component variants ដែលមាន properties រួម។

## 2. បង្កើត Component

1. បង្កើត button ដែលមាន text, fill, padding និង corner radius។
2. ជ្រើស layers របស់ button។
3. ប្រើ Create component ក្នុង toolbar ឬ shortcut ដែល Figma បង្ហាញ។
4. សង្កេតសញ្ញាពណ៌ស្វាយ និងឈ្មោះ component នៅ Layers/Assets។
5. ដាក់ឈ្មោះដែលបង្ហាញតួនាទី ដូចជា Button / Primary។

Figma UI និង shortcut អាចប្ដូរតាម platform។ ប្រសិនបើ shortcut មិនដូចគ្នា សូមប្រើ toolbar/menu ដែលមាន label បច្ចុប្បន្ន។

## 3. ប្រើ និងកែ Instance

បង្កើត instance ពី Assets panel ឬ duplicate instance ដែលមានស្រាប់។ ប្ដូរ text ឬ properties ដែលអនុញ្ញាត ហើយកុំកែ nested layers ដោយគ្មានមូលហេតុ ព្រោះវាអាចបង្កើត override ដែលពិបាកថែទាំ។

បើ Main component ប្រែប្រួល សូមពិនិត្យ instances ដើម្បីប្រាកដថា updates មិនធ្វើឱ្យ layout ខូច។ បើ instance ត្រូវការការផ្លាស់ប្តូរតែមួយកន្លែង សូមប្រើ property ឬ override ដែលបានគ្រោងទុក។

## 4. របៀបរៀបចំ Component

ប្រើឈ្មោះឱ្យងាយស្វែងរក៖ Button / Primary, Button / Secondary, Input / Default, Card / Product។ Slash naming ជួយបង្កើត hierarchy នៅ Assets panel។

គិតពី៖

- តើ component ត្រូវប្រើឡើងវិញពិតប្រាកដឬទេ?
- តើ content និង size អាចប្រែប្រួលទេ?
- តើអាចប្រើ Auto Layout ដើម្បីកុំឱ្យ text កាត់ទេ?
- តើ component មាន accessibility/contrast requirements អ្វី?
- តើអ្នកប្រើ component ផ្សេងនឹងដឹងថាត្រូវកែអ្វីខ្លះ?

## 5. កុំ Detach ដោយប្រញាប់

Detach instance បំបែកទំនាក់ទំនងជាមួយ Main component។ ប្រើតែពេលចាំបាច់ ព្រោះវាធ្វើឱ្យ instance នោះមិនទទួល updates ពី source ដូចមុន។ មុន detach សូមពិនិត្យថា៖

- តើអាចបង្កើត property ឬ variant ថ្មីបានទេ?
- តើ override ធម្មតាគ្រប់គ្រាន់ឬទេ?
- តើ design នេះជាករណីពិសេសដែលមិនគួរជា component ទេ?

## អនុវត្ត

បង្កើត Main component សម្រាប់ Primary button និង Secondary button។ ប្រើ instances ទាំងពីរនៅក្នុង registration form និង modal។ ប្ដូរ label មួយទៅពាក្យវែង ហើយពិនិត្យថា Auto Layout និង text behavior នៅត្រឹមត្រូវ។ កែ Main component ម្ដង ហើយពិនិត្យ instances ទាំងអស់។

## កំហុសទូទៅ

- បង្កើត component សម្រាប់ elements មិនដែលប្រើឡើងវិញ។
- ដាក់ឈ្មោះ generic ដូចជា Component 12។
- Override ច្រើនពេករហូតមិនដឹងថា source មានអ្វី។
- Detach ដើម្បីកែអ្វីតូចៗដែល property អាចដោះស្រាយបាន។
- កែ Main component ដោយមិនពិនិត្យ instances។

## Quick Check

1. Main component ខុសពី Instance ដូចម្តេច?
2. តើ instance ទទួល updates ពី source ដែរឬទេ?
3. តើ slash naming ជួយអ្វី?
4. តើពេលណាគួរ detach instance?

## ឯកសារយោង

- [Create components](https://help.figma.com/hc/en-us/articles/360038663994-Create-components)
- [Explore component properties](https://help.figma.com/hc/en-us/articles/5579474826519-Explore-component-properties)
