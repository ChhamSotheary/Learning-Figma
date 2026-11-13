# Lesson 01: Dev Mode and Design Handoff

## គោលបំណង

យល់ពីការរៀបចំ design សម្រាប់ handoff និងរបៀបប្រើ Dev Mode ដើម្បីឱ្យ developer ពិនិត្យ design properties, assets និងការផ្លាស់ប្ដូរបានមានប្រសិទ្ធភាព។

## 1. Handoff ជាការសហការណ៍

Handoff មិនមែនជាការផ្ញើ link ហើយបញ្ចប់ទេ។ Designer និង developer ត្រូវយល់ដូចគ្នាអំពី៖

- តើ frame/flow ណាដែលត្រូវអនុវត្ត។
- Breakpoints និង responsive behavior។
- Component states និង interaction behavior។
- Assets ត្រូវ export format/scale អ្វី។
- Content, error states, loading states និង empty states។
- អ្វីដែលមិនទាន់សម្រេច ឬត្រូវសួរបន្ថែម។

កុំគិតថា screenshot តែមួយអាចបញ្ជាក់ layout behavior ទាំងអស់បាន។

## 2. Dev Mode

Dev Mode ជា developer-focused workspace សម្រាប់ inspect design properties, វាស់ចម្ងាយ, មើល snippets/asset exports និងគ្រប់គ្រង handoff។ Feature availability អាចអាស្រ័យលើ plan និង permission របស់ file។ បើមិនឃើញ Dev Mode សូមពិនិត្យ plan/access របស់ workspace។

ជ្រើស layer ឬ frame ហើយពិនិត្យ៖

- Position និង dimensions។
- Fill, stroke, radius និង effects។
- Typography និង line height។
- Layout/Auto Layout properties។
- Component instance និង properties។
- Export settings និង asset variants។

Generated code snippets គ្រាន់តែជាចំណុចយោង មិនមែន production-ready code ដែលអាចយកទៅប្រើដោយគ្មាន review ទេ។

## 3. Ready for Development និង Annotations

មុន handoff៖

1. រៀបចំ pages/frames ឱ្យងាយស្វែងរក។
2. កំណត់ frame ឬ section ដែលចង់ handoff ជា ready-for-dev ប្រសិនបើ workflow/plan គាំទ្រ។
3. បន្ថែម annotations សម្រាប់ចំណុចដែល screenshot មិនអាចពន្យល់បាន។
4. បន្ថែម measurements និង behavior notes តែត្រង់កន្លែងចាំបាច់។
5. បញ្ជាក់ version/date ឬ changelog សម្រាប់ update សំខាន់។

Annotation គួរប្រាប់កិច្ចការដែល developer ត្រូវធ្វើ មិនមែនគ្រាន់តែបកស្រាយអ្វីដែលមើលឃើញរួចទេ។

## 4. Review Handoff

រៀបចំ short walkthrough៖ ពន្យល់ user flow, responsive decisions, states និង open questions។ សុំ developer បញ្ជាក់ថា assets និង states គ្រប់គ្រាន់។ បន្ទាប់ពី feedback សូមកែ file ឬកត់បញ្ហាដែលនឹងដោះស្រាយក្រោយ។

## Quick Check

1. Dev Mode ជួយ developer ក្នុងការងារអ្វី?
2. ហេតុអ្វី generated snippets មិនគួរត្រូវបានចាត់ទុកជាកូដចុងក្រោយ?
3. តើ annotation គួរបន្ថែមពេលណា?
4. តើមានព័ត៌មានអ្វីខ្លះដែល screenshot មិនអាចបង្ហាញ?

## ឯកសារយោង

- [Guide to Dev Mode in Figma](https://help.figma.com/hc/en-us/articles/15023124644247-Guide-to-Dev-Mode-in-Figma)
