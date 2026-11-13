# Lesson 02: Overlays, Scrolling and Navigation

## គោលបំណង

បង្កើត overlays សម្រាប់ dialog/menu, scrollable frames និង navigation រវាង pages ដើម្បីឱ្យ prototype ស្រដៀងនឹង user flow ពិត។

## 1. Overlays

Overlay បង្ហាញ frame មួយលើ screen បច្ចុប្បន្ន។ ប្រើសម្រាប់ confirmation dialog, menu, tooltip ឬ modal form។

1. បង្កើត overlay frame ដាច់ដោយឡែក។
2. ជ្រើស hotspot នៅ screen ដើម។
3. បន្ថែម interaction ហើយជ្រើស Open overlay។
4. ជ្រើសទីតាំង និងការបិទ overlay ដូចជា click outside ប្រសិនបើ UI គាំទ្រ។
5. បន្ថែម close/cancel action តាម design។

ពិនិត្យ overlay placement និង contrast ដើម្បីឱ្យ content ខាងក្រោយមិនបង្កការភាន់ច្រឡំ។

## 2. Scroll និង Overflow

ដើម្បី prototype scrolling សូមធ្វើឱ្យ content លើស bounds របស់ frame ហើយកំណត់ overflow behavior ក្នុង Prototype settings។ អាចធ្វើ vertical scrolling សម្រាប់ long page ឬ horizontal scrolling សម្រាប់ carousel។

សម្រាប់ sticky/fixed navigation ឬ toolbar សូមកំណត់ scroll position behavior របស់ layer។ Preview ក្នុង prototype ដើម្បីពិនិត្យថា scroll area ត្រឹមត្រូវ និង fixed elements មិនបិទ content។

## 3. Scroll To

Scroll to action អាចផ្លាស់ទីទៅ object មួយក្នុង frame ដដែល។ វាសាកសមសម្រាប់ table of contents, anchor navigation ឬ Back to top button។ ប្រើ animation សមរម្យ ហើយពិនិត្យថា destination មិនត្រូវបានបាំងដោយ fixed header។

## 4. Navigation និង Back

ភ្ជាប់ navigation items ទៅ destination frames ដោយមាន flow logic ច្បាស់។ ប្រើ Back trigger ប្រសិនបើត្រូវត្រឡប់ទៅ screen មុន។ តេស្តដោយចាប់ផ្តើមពី flow starting point មិនមែនចុច frames តាមលំដាប់ចៃដន្យទេ។

## អនុវត្ត

បង្កើត long article page មាន fixed header, scrollable content, table-of-contents links និង feedback modal។ Preview ហើយសាក scroll, Scroll to, open overlay និង close overlay។

## កំហុសទូទៅ

- Content មិនលើស frame ទើបមិនមាន scroll។
- Fixed element បិទ content នៅខាងក្រោម។
- Overlay បង្ហាញក្រៅ viewport។
- Scroll to ទៅ target ដែលលាក់ក្រោយ header។
- Back action ត្រឡប់ទៅផ្លូវមិនត្រឹមត្រូវ។

## Quick Check

1. តើ overlay សមស្របសម្រាប់ UI patterns អ្វី?
2. តើត្រូវធ្វើអ្វីដើម្បីឱ្យ frame អាច scroll?
3. Scroll to ខុសពី Navigate to ដូចម្តេច?
4. តើអ្វីអាចធ្វើឱ្យ Back flow ច្រឡំ?

## ឯកសារយោង

- [Create overlays in your prototypes](https://help.figma.com/hc/en-us/articles/360039818254-Create-overlays-in-your-prototypes)
- [Prototype scroll and overflow behavior](https://help.figma.com/hc/en-us/articles/360039818734-Prototype-scroll-and-overflow-behavior)
- [Preserve scroll position in prototypes](https://help.figma.com/hc/en-us/articles/360051747774-Preserve-scroll-position-in-prototypes)
