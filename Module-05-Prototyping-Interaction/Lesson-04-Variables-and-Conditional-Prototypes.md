# Lesson 04: Variables and Conditional Prototypes

## គោលបំណង

ប្រើ variables និង conditional actions ដើម្បីបង្ហាញ prototype states ដូចជា cart count, selected tab ឬ success/error outcome។ មុខងារ និង availability អាចអាស្រ័យលើ Figma plan និង feature rollout។

## 1. Variables ក្នុង Prototype

Variables អាចរក្សាតម្លៃដែល prototype interaction កែ ឬប្រើក្នុង condition។ ឧទាហរណ៍ number variable សម្រាប់ cart count, boolean សម្រាប់ menu open/closed ឬ string សម្រាប់ selected filter ប្រសិនបើ type នោះត្រូវបាន support។

ដាក់ឈ្មោះតាមអត្ថន័យ ដូចជា cart/item-count ឬ menu/is-open។ កំណត់ initial value មុនសាក flow ដើម្បីឱ្យ prototype ចាប់ផ្ដើមពី state ដែលអ្នករំពឹង។

## 2. Set Variable និង Conditions

ក្នុង interaction អាចប្រើ Set variable action ដើម្បីប្ដូរតម្លៃ។ Conditional action ប្រើ if/else logic ដែលពិនិត្យ expression ហើយបញ្ជូនទៅ action ផ្សេងតាមលទ្ធផល។

ឧទាហរណ៍ checkout prototype៖ ប្រសិនបើ cart item count ធំជាងសូន្យ ទៅ checkout; បើសូន្យ បង្ហាញ empty-cart overlay។ Syntax និង supported operators សូមពិនិត្យតាម interaction editor និង Figma documentation បច្ចុប្បន្ន។

## 3. រៀបចំ State Flow

1. បង្កើត variables ដែលចាំបាច់ និងកំណត់ initial values។
2. ជ្រើស interaction trigger។
3. បន្ថែម Set variable action មុន navigation ប្រសិនបើចាំបាច់។
4. បន្ថែម Conditional action និងកំណត់ if/else branches។
5. ភ្ជាប់ destination សម្រាប់ branch នីមួយៗ។
6. Preview flow ហើយសាក values ផ្សេងៗ។

បើ interaction មាន actions ច្រើន សូមរៀបលំដាប់ឱ្យច្បាស់ និងកត់ត្រា state transitions។

## 4. អនុវត្ត

បង្កើត cart prototype មាន Product screen, Cart screen, Empty state និង Checkout screen។ ប្រើ number variable សម្រាប់ item count និង condition ដើម្បីបង្ហាញ empty state ឬ checkout។ បន្ថែម reset/start flow ដើម្បីអាចសាកល្បង state ទាំងពីរឡើងវិញ។

## កំហុសទូទៅ

- មិនកំណត់ initial variable value។
- Condition syntax មិនត្រូវតាម operator ដែល Figma support។
- ច្រឡំ visual state ជាមួយ interaction state។
- បន្ថែម actions ច្រើនដោយមិនពិនិត្យលំដាប់។
- មិនសាកល្បង branch ទាំង If និង Else។

## Quick Check

1. តើ variable អាចតំណាងឱ្យ state អ្វីខ្លះ?
2. តើ Conditional action ប្រើសម្រាប់អ្វី?
3. ហេតុអ្វីត្រូវកំណត់ initial value?
4. តើអ្នកនឹងសាក branch ទាំងពីរដោយរបៀបណា?

## ឯកសារយោង

- [Multiple actions and conditionals](https://help.figma.com/hc/en-us/articles/15253220891799-Multiple-actions-and-conditionals)
- [Guide to variables in Figma](https://help.figma.com/hc/en-us/articles/15339657135383-Guide-to-variables-in-Figma)
