# Lesson 02: Auto Layout Fundamentals

## គោលបំណង

រៀនប្រើ Auto Layout ដើម្បីឱ្យ frame រៀបចំ child elements តាមទិសដៅ និងចន្លោះដែលកំណត់។ វាសាកសមសម្រាប់ button, list row, card, menu និង form ដែល content អាចប្រែប្រួល។

## 1. Auto Layout ជាអ្វី?

Auto Layout ជា layout behavior សម្រាប់ frame មួយ។ វារៀបចំ child layers តាមលំដាប់ផ្ដេក ឬបញ្ឈរ ហើយអាចគ្រប់គ្រង padding, spacing, alignment និង resizing។ ចាប់ផ្ដើមដោយជ្រើស frame ឬ layers ដែលចង់ដាក់ក្នុង layout រួចប្រើ Add auto layout ក្នុង Design sidebar។ Shortcut អាចខុសគ្នាតាម operating system និងការកំណត់ ដូច្នេះសូមមើល tooltip ក្នុង Figma។

## 2. Direction និង Alignment

- Horizontal សម្រាប់ button មាន icon និង label, navigation row ឬ card row។
- Vertical សម្រាប់ form, menu ឬ content card។
- កំណត់ alignment ដើម្បីដាក់ child layers ក្នុង container។
- កំណត់ gap រវាង child elements។
- ពិនិត្យលំដាប់ child layers ក្នុង Layers panel ព្រោះ Auto Layout រៀបចំតាមលំដាប់នោះ។

## 3. Padding និង Gap

Padding ជាចន្លោះពី child elements ទៅគែមខាងក្នុង container។ Gap ជាចន្លោះរវាង child elements។

ឧទាហរណ៍ button៖ horizontal padding 16px, vertical padding 10px និង gap 8px រវាង icon និង label។ តម្លៃទាំងនេះជាឧទាហរណ៍ប៉ុណ្ណោះ។ ជ្រើសរើសតាម typography, touch target និង design system។ បើ container មាន padding ស្មើគ្នា ប្រើ unified padding; បើត្រូវការខុសគ្នា កំណត់តាម edge។

## 4. Resizing: Hug, Fill និង Fixed

- Hug contents: ទំហំសមតាម content និង padding។
- Fill container: ពង្រីកដើម្បីប្រើចន្លោះដែលនៅសល់ក្នុង parent។
- Fixed width/height: រក្សាទំហំដែលបានកំណត់។

Button អាចប្រើ Hug contents ដើម្បីធំតាម label។ Input field ក្នុង form អាចប្រើ Fill container ដើម្បីពេញទទឹង parent។ Avatar អាចប្រើ Fixed size។ សាកកែ text ឱ្យវែង និងប្ដូរទទឹង parent ដើម្បីមើល behavior។

## 5. Nested Auto Layout

អាចដាក់ Auto Layout frames មួយនៅក្នុងមួយទៀត។ Product card ឧទាហរណ៍អាចមាន vertical card container, image frame, horizontal row សម្រាប់ title/favorite icon, និង price/button នៅខាងក្រោម។

ចាប់ផ្ដើមពី structure តូចៗ រួចដាក់ចូល parent។ បើ nested layout ស្មុគស្មាញ សូមសម្រេចថា child គួរចូល flow ឬត្រូវដាក់ដោយ absolute position ដោយមានហេតុផល។

## 6. អនុវត្ត Button និង Card

**Button**
1. បង្កើត text label ហើយជ្រើសវា។
2. បង្កើត Auto Layout frame។
3. កំណត់ padding, fill និង corner radius។
4. សាកប្ដូរ label ទៅអក្សរវែងជាងមុន។
5. ពិនិត្យថា button ពង្រីកដោយមិនកាត់ text។

**Product card**
1. បង្កើត parent ជា vertical Auto Layout។
2. ដាក់ image, title, price និង action។
3. កំណត់ gap និង padding។
4. ប្ដូរ title ទៅច្រើនបន្ទាត់ ហើយពិនិត្យ card។
5. កែ width parent ហើយពិនិត្យ fill/hug behavior។

## កំហុសទូទៅ

- កំណត់ Fill លើ child ដោយគ្មានចន្លោះនៅសល់ក្នុង parent។
- ប្រើ Fixed height លើ text ច្រើនបន្ទាត់ រហូតអក្សរត្រូវកាត់។
- ច្រឡំ padding ជាមួយ gap។
- ដាក់ layer ទាំងអស់ក្នុង Auto Layout ទោះវាមិនគួរចូល flow ក៏ដោយ។
- មិនសាក content វែង និងទទឹងខុសៗគ្នា។

## Quick Check

1. តើ Auto Layout ជួយអ្វីនៅពេល content ប្រែប្រួល?
2. Padding ខុសពី gap ដូចម្តេច?
3. តើ Hug, Fill និង Fixed មានន័យដូចម្តេច?
4. តើគួរប្រើ nested Auto Layout នៅពេលណា?

## ឯកសារយោង

- [Guide to auto layout in Figma](https://help.figma.com/hc/en-us/articles/360040451373-Guide-to-auto-layout-in-Figma)
