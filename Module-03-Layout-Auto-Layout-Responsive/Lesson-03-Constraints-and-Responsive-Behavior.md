# Lesson 03: Constraints and Responsive Behavior

## គោលបំណង

យល់ពីរបៀបដែល child layer ឆ្លើយតបនៅពេល parent frame ផ្លាស់ប្ដូរទំហំ។ អ្នកនឹងអនុវត្ត constraints, resizing និង responsive checks ដើម្បីធ្វើឱ្យ design សម្របតាមអេក្រង់ផ្សេងៗ។

## 1. Responsive Design មិនមែនគ្រាន់តែបង្រួមទេ

Responsive design គិតពីរបៀបដែល content, layout និង controls ឆ្លើយតបតាមទំហំ viewport។ ពេលធ្វើ design សួរថា៖ content ត្រូវប្ដូរលំដាប់ឬទេ? Columns ច្រើនគួរប្រែជាជួរឈរតែមួយឬទេ? Navigation ត្រូវប្ដូរទៅ menu ឬទេ? Text និង button អាច wrap បានទេ? Touch targets នៅតែប្រើបានទេ?

មិនមាន breakpoint តែមួយសម្រាប់គ្រប់ product ទេ។ ជ្រើស breakpoints តាមកន្លែងដែល content ចាប់ផ្ដើមមិនដំណើរការ។

## 2. Constraints នៅក្នុង Frame ធម្មតា

Constraints កំណត់ទីតាំង ឬទំហំរបស់ child layer ប្រៀបធៀបទៅនឹង parent frame ពេល resize៖

- Left/Top: រក្សាទីតាំងទាក់ទងនឹងគែមឆ្វេង/លើ។
- Right/Bottom: រក្សាចម្ងាយទាក់ទងនឹងគែមស្តាំ/ក្រោម។
- Center: រក្សាកណ្ដាល។
- Left and right ឬ Top and bottom: លាតបណ្ដោយរវាងគែមទាំងពីរ។
- Scale: ប្ដូរទំហំ និងទីតាំងតាមសមាមាត្រ។

Constraints អនុវត្តលើ child layers ក្នុង frame ដែលមិនប្រើ Auto Layout។ ក្នុង Auto Layout frame ប្រើ sizing behavior និង flow settings របស់ Auto Layout ជាចម្បង។

## 3. អនុវត្ត Constraints

1. បង្កើត frame ហើយដាក់ child elements នៅខាងក្នុង។
2. ជ្រើស child ដូចជា button ឬ side panel។
3. នៅ Position section ក្នុង right sidebar ជ្រើស constraint តាមអាកប្បកិរិយាដែលចង់បាន។
4. ប្ដូរទទឹង ឬកម្ពស់ parent frame។
5. សង្កេតទីតាំង និងទំហំរបស់ child។
6. សាក left/right លើ element ដែលគួរលាត និង right/bottom លើ floating action button។

Constraint មិនអាចជំនួស layout ថ្មីសម្រាប់ mobile បានទេ។ បើ content ត្រូវប្ដូររចនាសម្ព័ន្ធ សូមបង្កើត frame សម្រាប់ breakpoint នោះ និងកែ layout ដោយចេតនា។

## 4. Layout Guides និង Columns

ប្រើ Layout guides ដើម្បីតម្រឹម content និងកំណត់ columns។ Guides អាចមាន fixed dimensions ឬ stretch តាម frame។ អ្នកអាចផ្សំ guides ជាមួយ constraints ដើម្បីឱ្យ elements តម្រឹមពេល frame ផ្លាស់ប្ដូរ។

កុំច្រឡំ Layout guides ជាជំនួយមើលឃើញ ជាមួយ grid ក្នុង Auto Layout ដែលគ្រប់គ្រងការរៀបចំ child elements។

## 5. Responsive Testing ក្នុង Figma

បង្កើត frames យ៉ាងហោចណាស់បី៖ Mobile, Tablet និង Desktop។ ពិនិត្យ text wrapping/overflow, button/input width, image crop, navigation/content order, alignment/spacing និង touch targets។ ប្រើ prototype preview ដើម្បីមើល responsive scaling តាម constraints និង Auto Layout; វាមិនជំនួសការរៀបចំ layout សម្រាប់ breakpoint ផ្សេងដោយខ្លួនឯងទេ។

## 6. លំហាត់ខ្លី

យក product landing page ពីមេរៀនមុន ហើយបង្កើត Mobile, Tablet និង Desktop frames។ Desktop ប្រើ columns; Tablet កាត់ចំនួន columns; Mobile ដាក់ content ជាជួរឈរតែមួយ។ ប្រើ Auto Layout សម្រាប់ lists និង buttons ហើយ constraints សម្រាប់ elements ដែលត្រូវនៅជិតគែម។ កត់សម្គាល់ថាហេតុអ្វី layout ផ្លាស់ប្ដូរនៅ breakpoint នីមួយៗ។

## កំហុសទូទៅ

- គិតថា Scale constraint ធ្វើឱ្យ layout responsive ទាំងស្រុង។
- ប្រើ constraints លើ layer ក្នុង Auto Layout frame។
- មិនសាកទំហំអេក្រង់ផ្សេង។
- អនុញ្ញាតឱ្យ text ឬ button overflow ដោយមិនកំណត់។
- ជ្រើស breakpoint ដោយគ្មានមូលហេតុពី content។

## Quick Check

1. Constraints ចង child layer ទៅនឹងអ្វី?
2. តើ constraints ប្រើលើ child ក្នុង Auto Layout frame បានទេ?
3. ពេលណាត្រូវបង្កើត layout ផ្សេង ជំនួសឱ្យការបង្រួម frame?
4. តើអ្នកគួរពិនិត្យអ្វីខ្លះនៅ mobile/tablet/desktop?

## ឯកសារយោង

- [Apply constraints to define how layers resize](https://help.figma.com/hc/en-us/articles/360039957734-Apply-constraints-to-define-how-layers-resize)
- [Combine layout guides and constraints](https://help.figma.com/hc/en-us/articles/360039957934-Combine-layout-guides-and-constraints)
- [Play your prototypes](https://help.figma.com/hc/en-us/articles/360040318013-Play-your-prototypes)
