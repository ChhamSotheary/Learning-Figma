# Lesson 03: Animations and Smart Animate

## គោលបំណង

ជ្រើស transition និង animation ឱ្យសមនឹង interaction ដោយប្រើ Instant, dissolve, move, slide ឬ Smart Animate ដែលមានក្នុង Prototype settings។

## 1. តួនាទីរបស់ Animation

Animation អាចជួយបង្ហាញថា content មកពីណា, layer មួយផ្លាស់ទៅណា និងតើ interaction ទទួលបាន response។ ប្រើវាដើម្បីគាំទ្រការយល់ មិនមែនដើម្បីបន្ថែមចលនាគ្រប់កន្លែងទេ។

## 2. Transition Types

Figma មាន transition options ជាច្រើន ហើយឈ្មោះ/controls អាចផ្លាស់ប្ដូរតាម UI version។ ជ្រើស transition ដោយគិតពី៖

- Interaction គួរមានអារម្មណ៍លឿន ឬទន់រលូន?
- Content ប្ដូរទីតាំង ឬប្ដូរទំព័រ?
- Animation បង្ហាញទំនាក់ទំនងអ្វី?
- តើវាធ្វើឱ្យ flow យឺត ឬរំខានដែរឬទេ?

Instant សមសម្រាប់ navigation ដែលមិនចាំបាច់បង្ហាញ motion។ Dissolve សមសម្រាប់ប្ដូររូបរាងទន់ៗ។ Move/slide សមសម្រាប់ panels និង drawers ប្រសិនបើទិសចលនាឆ្លុះបញ្ចាំង hierarchy។

## 3. Smart Animate

Smart Animate ប្រៀបធៀប layers រវាង frames ហើយ animate properties ដែលស្របគ្នា។ ដើម្បីជួយឱ្យវាដំណើរការ៖

- រក្សាឈ្មោះ និង hierarchy របស់ layers ដែលជាគូ។
- រៀបចំ starting និង destination frames ឱ្យមាន layers ដែលត្រូវគ្នា។
- ផ្លាស់ប្ដូរ properties ដូចជា position, size, opacity ឬ fill តាមបំណង។
- Preview ហើយកែបើ layer មិន match តាមការរំពឹង។

ប្រសិនបើឈ្មោះ/hierarchy មិនត្រូវគ្នា Figma អាច fade layers ជំនួសឱ្យការផ្លាស់ទី។ សាកល្បងលើ file របស់អ្នក ព្រោះ behavior អាស្រ័យលើ layer matching។

## 4. Easing និង Duration

Easing គ្រប់គ្រងការបង្កើន/បន្ថយល្បឿន។ Duration កំណត់រយៈពេល។ ចាប់ផ្តើមពីចលនាខ្លី និង subtle រួច preview។ កុំប្រើ duration យូរពេកសម្រាប់ action ដែលអ្នកប្រើរំពឹងថាភ្លាមៗ។

ពិនិត្យ animation នៅ prototype viewer ដើម្បីឃើញ timing ពិត និងកែ curve/curve direction តាមចលនា។

## អនុវត្ត

បង្កើត product card detail interaction៖ នៅ state ដំបូង card តូច; ពេល click វាពង្រីកជាផ្នែក details។ រក្សា layer names ឱ្យស្រប និងសាក Smart Animate។ បង្កើត version ទីពីរជា Instant ហើយប្រៀបធៀបថា version ណាធ្វើឱ្យ interaction យល់ងាយជាង។

## កំហុសទូទៅ

- ប្រើ Smart Animate លើ layers ដែលឈ្មោះ និង hierarchy មិន match។
- ដាក់ motion លើ action គ្រប់យ៉ាង។
- ប្រើ easing មិនសមនឹងទិសចលនា។
- មិន preview animation ហើយសន្មតថាវានឹងដំណើរការ។
- ប្រើចលនាដើម្បីលាក់ navigation ដែលមិនច្បាស់។

## Quick Check

1. Smart Animate ផ្គូផ្គង layers ដោយផ្អែកលើអ្វី?
2. តើពេលណា Instant សមជាង animation?
3. Easing និង duration មានតួនាទីអ្វី?
4. តើអ្នកនឹងដោះស្រាយ layer ដែលមិន match ដូចម្តេច?

## ឯកសារយោង

- [Prototype animations](https://help.figma.com/hc/en-us/articles/360040522373-Prototype-animations)
- [Connect your prototype](https://help.figma.com/hc/en-us/articles/360040315773-Connect-your-prototype)
