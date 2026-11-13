# Lesson 03: Styles, Variables and Design Tokens

## គោលបំណង

រៀនបង្កើត values ដែលអាចប្រើឡើងវិញបានសម្រាប់ពណ៌, spacing, typography និង effects។ យល់ពីភាពខុសគ្នារវាង styles និង variables ហើយរៀបចំ tokens ឱ្យសមនឹង design system។

## 1. Styles និង Variables

Styles ជួយរក្សាទុកការកំណត់ដែលអាចប្រើឡើងវិញ ដូចជា text, color, effect និង layout guide style។ Variables រក្សាទុក values ដែលអាចយកទៅប្រើលើ design properties និង prototype actions ដែលគាំទ្រ។

សង្ខេប៖

- Style ជាឈុតការកំណត់រចនាសម្ព័ន្ធ ដូចជា text style ឬ effect style។
- Variable ជាតម្លៃ reusable ដូចជា color, number, string ឬ boolean។
- អាចប្រើរួមគ្នា ដើម្បីរក្សា typography, colors និង modes ឱ្យស្របគ្នា។

សមត្ថភាពដែលអាចភ្ជាប់ទៅ variable អាស្រ័យលើ type និង feature support របស់ Figma បច្ចុប្បន្ន។

## 2. រៀបចំ Color Variables

បង្កើត color variables ដែលបង្ហាញតួនាទី មិនមែនតែពណ៌៖

- color/background/default
- color/text/primary
- color/action/primary
- color/border/subtle

ប្រើ semantic names ដើម្បីឱ្យការប្ដូរ theme មិនត្រូវកែគ្រប់ screen ដោយដៃ។ បង្កើត collection សម្រាប់ core colors ហើយប្រើ modes ដូចជា Light/Dark ប្រសិនបើ product ត្រូវការ។ កុំបង្កើត modes ច្រើនដោយគ្មាន use case។

## 3. Number Variables និង Spacing

Number variables អាចប្រើសម្រាប់ spacing, dimensions និង radius នៅ properties ដែលគាំទ្រ។ ឧទាហរណ៍ naming៖ space/1 = 4, space/2 = 8, space/3 = 12, space/4 = 16។ កំណត់ scale តាម product ហើយកុំយកលេខឧទាហរណ៍នេះជាស្តង់ដារដាច់ខាត។

ប្រសិនបើ design មាន spacing តិចៗខុសៗគ្នាច្រើន សូមសម្រេចថាតើត្រូវកែទៅ scale ដើម្បីធ្វើឱ្យប្រព័ន្ធស្របគ្នាឬទេ។

## 4. Collections និង Modes

Collection ជាក្រុម variables ដែលពាក់ព័ន្ធគ្នា។ Modes ជា value sets ផ្សេងៗក្នុង collection ដូចជា Light/Dark theme ឬ Desktop/Mobile configuration តាម use case។ Alias variables អាចយោងទៅ variables ផ្សេង ដើម្បីឱ្យ semantic token ចង្អុលទៅ primitive value។

ឧទាហរណ៍៖ color/action/primary អាច alias ទៅ palette/blue/600 នៅ Light mode និង palette/blue/300 នៅ Dark mode។ ពិនិត្យ contrast និង readability ទាំងពីរ modes។

## 5. អនុវត្ត

បង្កើត collection មួយសម្រាប់ color tokens និងមួយសម្រាប់ spacing tokens។ បន្ថែម Light/Dark modes លើ colors។ Apply variables ទៅ background, text, primary button និង card។ ប្ដូរ mode ហើយពិនិត្យ screen ទាំងមូល។

បង្កើត text styles សម្រាប់ heading, body និង caption។ កែ style ម្ដង ហើយមើលថា text ដែលប្រើ style នោះធ្វើបច្ចុប្បន្នភាពដែរឬទេ។

## កំហុសទូទៅ

- ដាក់ឈ្មោះ variables តាមតម្លៃពណ៌តែប៉ុណ្ណោះ មិនបង្ហាញតួនាទី។
- បង្កើត Light/Dark mode ដោយមិនពិនិត្យ contrast។
- មាន token ស្ទួន ឬ values ដែលមិនប្រើ។
- ប្រើ variables ក្នុង property ដែល Figma មិនគាំទ្រ។
- បង្កើត spacing scale ដែលមិនសមនឹង content និង touch targets។

## Quick Check

1. Styles និង variables ខុសគ្នាដូចម្តេច?
2. Collection និង mode មានតួនាទីអ្វី?
3. ហេតុអ្វី semantic token names មានប្រយោជន៍?
4. តើអ្វីខ្លះត្រូវពិនិត្យពេលប្ដូរ Light/Dark mode?

## ឯកសារយោង

- [Guide to variables in Figma](https://help.figma.com/hc/en-us/articles/15339657135383-Guide-to-variables-in-Figma)
- [Overview of variables, collections, and modes](https://help.figma.com/hc/en-us/articles/14506821864087-Overview-of-variables-collections-and-modes)
- [The difference between variables and styles](https://help.figma.com/hc/en-us/articles/15871097384471-The-difference-between-variables-and-styles)
