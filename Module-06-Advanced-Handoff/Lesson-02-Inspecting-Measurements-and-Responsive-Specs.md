# Lesson 02: Inspecting Measurements and Responsive Specs

## គោលបំណង

រៀបចំ design specifications ឱ្យ developer យល់ពី dimensions, spacing, typography, component behavior និង responsive rules ដោយប្រើ inspection tools និង annotations។

## 1. Inspect Properties

ជ្រើស frame/layer ក្នុង Dev Mode ឬ Properties panel ហើយពិនិត្យ៖

- Width/height និង position។
- Padding, gap និង alignment នៅ Auto Layout។
- Text font, size, weight, line height និង color។
- Fill, stroke, corner radius និង effects។
- Constraints និង resizing behavior។
- Source component និង instance properties។

កុំកត់លេខគ្រប់ layer ដោយដៃ ប្រសិនបើ properties panel អាចបង្ហាញបាន។ ផ្ដោតលើ decisions ដែលមានឥទ្ធិពលលើការអនុវត្ត។

## 2. Measurements និង Annotation

ប្រើ measurement views ដើម្បីបង្ហាញ distance រវាង elements។ បន្ថែម annotation នៅចំណុចដែលមានច្បាប់ពិសេស ដូចជា minimum/maximum width, breakpoint behavior, crop rules ឬ validation states។

ឧទាហរណ៍ annotation ល្អ៖ “នៅ width ក្រោម breakpoint នេះ card list ប្រែទៅ single column; image រក្សា aspect ratio”។ វាច្បាស់ជាង “make responsive”។

## 3. Responsive Specs

សម្រាប់ breakpoint នីមួយៗ បញ្ជាក់៖

- Frame size ដែលបានប្រើសម្រាប់ reference។
- Content max width និង margins។
- Columns/gutters ឬ single-column behavior។
- Elements ដែល hide/show/reorder។
- Text wrapping និង truncation rules។
- Fixed/sticky elements និង scrolling behavior។

Frame dimensions ជា reference scenarios មិនមែនជា list ទាំងអស់នៃ device sizes ដែល product ត្រូវ support ទេ។ សរសេរអំពី behavior រវាង breakpoints ប្រសិនបើសំខាន់។

## 4. Component States និង Edge Cases

សម្រាប់ components សំខាន់ៗ បង្ហាញ states៖ default, hover/focus (បើ relevant), active, disabled, error, loading និង empty។ សម្រាប់ form field ពន្យល់ error placement និងការរក្សា input។ សម្រាប់ modal បង្ហាញ close/cancel behavior។

កុំបង្ហាញ state ដែលមិនមានក្នុង product requirements ដើម្បីតុបតែង file ប៉ុណ្ណោះ។

## អនុវត្ត

យក frame មួយពី Module 03 ឬ 04 ហើយបន្ថែម annotation សម្រាប់ responsive breakpoint, button states និង content overflow។ សុំ peer ម្នាក់ឱ្យពិនិត្យ ហើយឱ្យគាត់ពន្យល់ behavior ដោយមិនសួរអ្នក។ កែ note ដែលមិនច្បាស់។

## Quick Check

1. តើគួរបញ្ជាក់ responsive behavior អ្វីខ្លះ?
2. ហេតុអ្វី “make responsive” មិនមែនជា handoff note គ្រប់គ្រាន់?
3. តើ states ណាខ្លះសមស្របសម្រាប់ form field?
4. តើអ្នកបែងចែក reference frame size និង supported viewport behavior ដូចម្តេច?

## ឯកសារយោង

- [Guide to Dev Mode in Figma](https://help.figma.com/hc/en-us/articles/15023124644247-Guide-to-Dev-Mode-in-Figma)
- [Apply constraints to define how layers resize](https://help.figma.com/hc/en-us/articles/360039957734-Apply-constraints-to-define-how-layers-resize)
