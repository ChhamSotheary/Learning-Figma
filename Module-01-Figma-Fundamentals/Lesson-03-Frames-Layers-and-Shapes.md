# Lesson 03: Frames, Layers and Shapes

## 1. What is a Frame?
**Frame** គឺជា Container សម្រាប់ដាក់ និងរៀបចំ Design Elements។ វាអាចតំណាងឱ្យ Mobile Screen, Website Section ឬ Component។

ឧទាហរណ៍៖ Mobile screen មួយអាចមាន Header, Search Bar, Product List និង Bottom Navigation នៅក្នុង Frame តែមួយ។

## 2. Create a Frame
1. ជ្រើស Frame tool ឬចុច `F`។
2. ជ្រើសទំហំ Preset ឬកំណត់ Width និង Height ដោយខ្លួនឯង។
3. Rename Frame ជា `Mobile Home`។
4. មើល Width និង Height នៅក្នុង Properties Panel។

សម្រាប់លំហាត់នេះ អាចប្រើទំហំ 390 × 844 px ជាទំហំសាកល្បង មិនមែនជាទំហំស្តង់ដារសម្រាប់ទូរស័ព្ទទាំងអស់ទេ។

## 3. Frame vs Group

| Frame | Group |
|---|---|
| មាន Container និង Frame properties | ជាការដាក់ Objects ជាក្រុម |
| អាចប្រើសម្រាប់ Screen/Section | ប្រើដើម្បីរៀបចំ Objects ដែលទាក់ទងគ្នា |
| គាំទ្រ Layout features ដូចជា Auto Layout | មិនមាន Layout behavior ដូច Frame ដោយស្វ័យប្រវត្តិទេ |

ប្រើ Frame សម្រាប់ Screen ឬ Section។ ប្រើ Group នៅពេលចង់ជ្រើស និងរៀបចំ Objects ជាក្រុមសាមញ្ញ។

## 4. Create Shapes
Shapes ជួយបង្កើត UI Elements ដូចជា Buttons, Cards និង Backgrounds។
- Rectangle: `R`
- Ellipse: `O`
- Line: ជ្រើស Line tool
- Polygon/Star: ជ្រើសពី Shape tools

### Rectangle Practice
1. ជ្រើស Rectangle tool។
2. Drag លើ Canvas ដើម្បីគូរ។
3. កែ Width និង Height។
4. កែ Fill color។
5. កែ Corner radius ប្រសិនបើចង់បានជ្រុងមូល។

## 5. Fill and Stroke
- **Fill**: ពណ៌ ឬរូបភាពនៅខាងក្នុង Shape។
- **Stroke**: បន្ទាត់ជុំវិញ Shape។

ឧទាហរណ៍៖ Button អាចមាន Fill ពណ៌ខៀវ និង Stroke មិនចាំបាច់មាន។ Search field អាចមាន Fill ពណ៌ស និង Stroke ពណ៌ប្រផេះស្រាល។

## 6. Corner Radius
Corner radius កំណត់កម្រិតមូលនៃជ្រុង Shape។ ប្រើ Radius ឱ្យស្របគ្នានៅក្នុង Design ដើម្បីឱ្យ UI មានភាពស៊ីសង្វាក់។

## 7. Text Tool
ចុច `T` ដើម្បីប្រើ Text tool។
1. ចុចលើ Canvas។
2. វាយអក្សរ។
3. ជ្រើស Text layer។
4. កែ Font, Size, Weight, Line height និង Color នៅក្នុង Properties Panel។

## 8. Organize Layers
ឧទាហរណ៍៖
```
Mobile Home
├── Header
│   ├── Logo
│   └── Profile Icon
├── Search Field
├── Featured Product
│   ├── Product Image
│   ├── Product Name
│   └── Price
└── Shop Button
```

## Practice Task
បង្កើត Mobile Frame មួយ ហើយបន្ថែម Header text, Search field, Product card, Product name, price និង Button។ ប្រើ Fill, Stroke, Corner radius និង Text properties ហើយ Rename Layers ឱ្យត្រឹមត្រូវ។

## Quick Check
1. Frame ខុសពី Group ដូចម្តេច?
2. Fill និង Stroke ខុសគ្នាយ៉ាងដូចម្តេច?
3. តើ Text tool ប្រើ Shortcut អ្វី?
4. ហេតុអ្វីត្រូវរៀបចំ Layers?