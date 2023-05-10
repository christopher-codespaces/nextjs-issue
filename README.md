When I create a new project using Next.js and run it without making any changes, I receive the following warning message in my terminal:
warn ./node_modules/next/dist/client/add-base-path.js
There are multiple modules with names that only differ in casing.
This can lead to unexpected behavior when compiling on a filesystem with other case-semantic.
Use equal casing. Compare these module identifiers:
* C:\Users\PROLINE\Documents\Builds\swiftlybox\ama\node_modules\next\dist\compiled\@next\react-refresh-utils\dist\loader.js!C:\Users\PROLINE\Documents\Builds\swiftlybox\ama\node_modules\next\dist\build\webpack\loaders\next-swc-loader.js??ruleSet[1].rules[1].oneOf[2].use[1]!C:\Users\PROLINE\Documents\Builds\swiftlybox\ama\node_modules\next\dist\client\add-base-path.js
    Used by 2 module(s), i. e.
![WhatsApp Image 2023-05-10 at 22 25 49](https://github.com/christopher-codespaces/nextjs-issue/assets/125880140/7a896655-a1dc-44c9-b43b-c043054be531)
