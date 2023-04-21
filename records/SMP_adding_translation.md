# Process of adding a new string using the Translation component in sm_platform
When changes are made with a string that uses the Translate component or translate() function in a PR, they should also file a ticket or a follow up PR to ensure that the correspoding Chinese and Russian language files are updated.
The steps to update are as follows:
* Run `npm run extract` to make `en.json` file updated
* Manually updates `ru.json` file, ask Sasha for language help. Ensure that the ID in `ru.json` corresponds to the ID in `en.json`.
* Manually updates `zh.json` file, ask Mingya for language help. Ensure that the ID in `zh.json` corresponds to the ID in `en.json`.