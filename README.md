## Copyright and Proprietary Rights

Magic Keyboard V1 is a proprietary software project associated with
Idea Pardazan IPARA Co. (IPARA).

Copyright © 2026 Idea Pardazan IPARA Co. All rights reserved.

No open-source license is granted for this project. Access to this
repository does not constitute permission to use, copy, modify,
distribute, or commercially exploit its proprietary materials.

Website: https://ipara.co

For licensing and commercial inquiries, contact Idea Pardazan IPARA Co.## Copyright and Proprietary Rights

Magic Keyboard V1 is a proprietary software project associated with
Idea Pardazan IPARA Co. (IPARA).

Copyright © 2026 Idea Pardazan IPARA Co. All rights reserved.

No open-source license is granted for this project. Access to this
repository does not constitute permission to use, copy, modify,
distribute, or commercially exploit its proprietary materials.

Website: https://ipara.co

For licensing and commercial inquiries, contact Idea Pardazan IPARA Co.




1. Full Project Description — GitHub README
Magic Keyboard V1
Magic Keyboard V1 is a Windows desktop application concept designed to make Persian typing easier and more natural by converting Finglish (Persian written with Latin characters) into Persian script while preserving English text, technical terminology, and source code.
The project focuses on a practical challenge faced by bilingual users, developers, and content creators: switching between Persian and English while typing in the same application can interrupt workflow and introduce unwanted changes to technical text.
Magic Keyboard aims to provide a lightweight, user-controlled typing assistant that works across Windows applications, with particular attention to mixed-language writing in development environments such as Visual Studio Code.
Key Features
- Finglish-to-Persian Conversion: Convert Persian words and sentences typed with Latin characters into Persian script.
- Mixed-Language Text Handling: Distinguish Persian text from English words, technical terminology, product names, and abbreviations.
- Developer-Friendly Typing: Preserve English identifiers, programming keywords, commands, and source code when writing Persian comments or documentation.
- Context-Aware Text Processing: Use surrounding text and typing context to help determine whether a segment should be converted or preserved.
- Windows System Tray Integration: Provide an accessible tray icon to indicate the application's status.
- Quick Enable/Disable Controls: Allow users to activate or deactivate conversion without closing the application.
- Configurable Behavior: Provide a settings interface for managing conversion preferences and application behavior.
- Automatic Startup: Optionally launch the application when Windows starts.
- Local Processing: Design the core typing and conversion workflow to operate locally, without requiring a paid external API.
Mixed-Language Typing Example
A developer might type:
Man dar morede Magic Keyboard va assistant manager dar VS Code minevisam.

The intended result is:
من در مورد Magic Keyboard و assistant manager در VS Code می‌نویسم.

The objective is to convert the Persian portions while preserving English names, technical terms, and application identifiers.
Similarly, when writing code, the application should distinguish between Persian comments, English prose, and executable code rather than converting every Latin character indiscriminately.
Target Users
Magic Keyboard is intended for:
- Persian-speaking software developers.
- Users who frequently switch between Persian and English.
- Technical writers and documentation authors.
- Students and professionals who write bilingual content.
- Users who prefer typing Persian phonetically with a Latin keyboard layout.
Design Principles
1. Preserve technical accuracy
Programming syntax, commands, identifiers, and English technical terms should remain unchanged unless the user explicitly requests otherwise.
2. Respect the user's control
Users should be able to enable or disable the conversion engine quickly and configure its behavior.
3. Minimize workflow interruption
The application should support natural typing without requiring users to manually convert every sentence or repeatedly switch keyboard layouts.
4. Prioritize privacy
The core design should favor local processing and avoid unnecessary transmission of typed content to external services.
5. Support real-world applications
Compatibility should be tested with common Windows text fields and developer tools, including Visual Studio Code.
Proposed Technical Direction
The project is intended to be developed as a Windows desktop application, with a modular architecture separating the typing interface, text-conversion engine, context detection, configuration, and system integration.
The implementation should be validated against real typing scenarios, especially mixed Persian-English text, code editors, and application-specific input fields.
Specific implementation technologies and dependencies should be confirmed during the initial technical assessment rather than assumed in advance.
Development Status
Magic Keyboard V1 is a planned development project. The features described above represent the intended functionality and design direction; they should not be interpreted as confirmation that every feature has already been implemented or tested.
The development process should prioritize a working prototype, measurable acceptance criteria, compatibility testing, and incremental delivery.
Project Goal
The long-term goal is to make Persian typing with a Latin keyboard more convenient while retaining the accuracy and predictability required for bilingual writing and software development.
Magic Keyboard aims to bridge the gap between natural Persian phonetic typing and the need to preserve English technical content in the same text field.
2. Short Description — GitHub Repository
A Windows typing assistant that converts Finglish into Persian while preserving English text, technical terminology, and source code.


1. Updated Full Project Description — GitHub README
این بخش را به معرفی پروژه اضافه کن تا پشتیبانی از زبان‌های آینده نیز مشخص باشد.
Planned Multilingual Support
Magic Keyboard is designed with a modular architecture that can be extended to support multiple languages over time. The initial development focus is Finglish-to-Persian conversion, with the long-term goal of enabling intelligent multilingual typing within a single application.
Future language support may include:
- Persian (Farsi): Finglish-to-Persian conversion and context-aware Persian typing.
- English: Preservation of English text, technical terminology, and natural English typing.
- Arabic: Arabic-script input support, with appropriate language-specific conversion and text handling.
- German: German phonetic typing support and mixed Persian-German text handling.
- French: French text recognition and mixed-language typing support.
- Spanish: Spanish text recognition and mixed-language typing support.
- Italian: Italian text recognition and mixed-language typing support.
- Turkish: Turkish text recognition and mixed-language typing support.
- Russian: Russian transliteration and text conversion support.
- Additional languages: The architecture should allow new languages to be added incrementally without requiring a complete redesign of the application.
Multilingual Design Goals
The planned multilingual engine should aim to:
1. Identify the intended language from typing patterns, context, and user preferences.
2. Convert text only when the selected language and conversion rules require it.
3. Preserve original English words, technical terms, names, URLs, commands, and source code.
4. Support mixed-language sentences containing two or more languages.
5. Allow users to enable, disable, and configure individual language modules.
6. Provide language-specific transliteration rules rather than relying on a single universal conversion algorithm.
7. Support future expansion through modular language packs and configurable conversion rules.
Important: These languages represent planned expansion targets, not confirmed existing features. Each language should be implemented and tested separately before being advertised as supported.
2. Updated One-Line GitHub Description
A multilingual Windows typing assistant designed to convert Finglish into Persian, with planned support for additional languages while preserving English text, technical terminology, and source code.1. Full Project Description — GitHub README
Magic Keyboard V1
Magic Keyboard V1 is a Windows desktop application concept designed to make Persian typing easier and more natural by converting Finglish (Persian written with Latin characters) into Persian script while preserving English text, technical terminology, and source code.
The project focuses on a practical challenge faced by bilingual users, developers, and content creators: switching between Persian and English while typing in the same application can interrupt workflow and introduce unwanted changes to technical text.
Magic Keyboard aims to provide a lightweight, user-controlled typing assistant that works across Windows applications, with particular attention to mixed-language writing in development environments such as Visual Studio Code.
Key Features
- Finglish-to-Persian Conversion: Convert Persian words and sentences typed with Latin characters into Persian script.
- Mixed-Language Text Handling: Distinguish Persian text from English words, technical terminology, product names, and abbreviations.
- Developer-Friendly Typing: Preserve English identifiers, programming keywords, commands, and source code when writing Persian comments or documentation.
- Context-Aware Text Processing: Use surrounding text and typing context to help determine whether a segment should be converted or preserved.
- Windows System Tray Integration: Provide an accessible tray icon to indicate the application's status.
- Quick Enable/Disable Controls: Allow users to activate or deactivate conversion without closing the application.
- Configurable Behavior: Provide a settings interface for managing conversion preferences and application behavior.
- Automatic Startup: Optionally launch the application when Windows starts.
- Local Processing: Design the core typing and conversion workflow to operate locally, without requiring a paid external API.
Mixed-Language Typing Example
A developer might type:
Man dar morede Magic Keyboard va assistant manager dar VS Code minevisam.

The intended result is:
من در مورد Magic Keyboard و assistant manager در VS Code می‌نویسم.

The objective is to convert the Persian portions while preserving English names, technical terms, and application identifiers.
Similarly, when writing code, the application should distinguish between Persian comments, English prose, and executable code rather than converting every Latin character indiscriminately.
Target Users
Magic Keyboard is intended for:
- Persian-speaking software developers.
- Users who frequently switch between Persian and English.
- Technical writers and documentation authors.
- Students and professionals who write bilingual content.
- Users who prefer typing Persian phonetically with a Latin keyboard layout.
Design Principles
1. Preserve technical accuracy
Programming syntax, commands, identifiers, and English technical terms should remain unchanged unless the user explicitly requests otherwise.
2. Respect the user's control
Users should be able to enable or disable the conversion engine quickly and configure its behavior.
3. Minimize workflow interruption
The application should support natural typing without requiring users to manually convert every sentence or repeatedly switch keyboard layouts.
4. Prioritize privacy
The core design should favor local processing and avoid unnecessary transmission of typed content to external services.
5. Support real-world applications
Compatibility should be tested with common Windows text fields and developer tools, including Visual Studio Code.
Proposed Technical Direction
The project is intended to be developed as a Windows desktop application, with a modular architecture separating the typing interface, text-conversion engine, context detection, configuration, and system integration.
The implementation should be validated against real typing scenarios, especially mixed Persian-English text, code editors, and application-specific input fields.
Specific implementation technologies and dependencies should be confirmed during the initial technical assessment rather than assumed in advance.
Development Status
Magic Keyboard V1 is a planned development project. The features described above represent the intended functionality and design direction; they should not be interpreted as confirmation that every feature has already been implemented or tested.
The development process should prioritize a working prototype, measurable acceptance criteria, compatibility testing, and incremental delivery.
Project Goal
The long-term goal is to make Persian typing with a Latin keyboard more convenient while retaining the accuracy and predictability required for bilingual writing and software development.
Magic Keyboard aims to bridge the gap between natural Persian phonetic typing and the need to preserve English technical content in the same text field.
2. Short Description — GitHub Repository
A Windows typing assistant that converts Finglish into Persian while preserving English text, technical terminology, and source code.


1. Updated Full Project Description — GitHub README.
Planned Multilingual Support
Magic Keyboard is designed with a modular architecture that can be extended to support multiple languages over time. The initial development focus is Finglish-to-Persian conversion, with the long-term goal of enabling intelligent multilingual typing within a single application.
Future language support may include:
- Persian (Farsi): Finglish-to-Persian conversion and context-aware Persian typing.
- English: Preservation of English text, technical terminology, and natural English typing.
- Arabic: Arabic-script input support, with appropriate language-specific conversion and text handling.
- German: German phonetic typing support and mixed Persian-German text handling.
- French: French text recognition and mixed-language typing support.
- Spanish: Spanish text recognition and mixed-language typing support.
- Italian: Italian text recognition and mixed-language typing support.
- Turkish: Turkish text recognition and mixed-language typing support.
- Russian: Russian transliteration and text conversion support.
- Additional languages: The architecture should allow new languages to be added incrementally without requiring a complete redesign of the application.
Multilingual Design Goals
The planned multilingual engine should aim to:
1. Identify the intended language from typing patterns, context, and user preferences.
2. Convert text only when the selected language and conversion rules require it.
3. Preserve original English words, technical terms, names, URLs, commands, and source code.
4. Support mixed-language sentences containing two or more languages.
5. Allow users to enable, disable, and configure individual language modules.
6. Provide language-specific transliteration rules rather than relying on a single universal conversion algorithm.
7. Support future expansion through modular language packs and configurable conversion rules.
Important: These languages represent planned expansion targets, not confirmed existing features. Each language should be implemented and tested separately before being advertised as supported.
2. Updated One-Line GitHub Description
A multilingual Windows typing assistant designed to convert Finglish into Persian, with planned support for additional languages while preserving English text, technical terminology, and source code.
