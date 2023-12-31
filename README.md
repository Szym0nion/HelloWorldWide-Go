# HelloWorldWide GO Pack

## Getting started with third party packages
**To initialize a module and pass in a fully-qualified name for your own package. If you wanted to host your module on GitHub under your username “pikachu”, you could initialize your module like this:**
## `go mod init github.com/pikachu/yourepositoryname`
**This creates a file called go.mod. Let’s look at that file:**
## `cat go.mod`
**Output**:

_module github.com/piakchu/yourepositoryname_

_go 1.21.2_

**Now use the go get command to download the third-party UUID module:**
## `go get github.com/Szym0nion/HelloWorldWide-Go`
**Now look again at your own go.mod file:**
## `cat go.mod`
**Output**:
_module github.com/pikachu/yourepositoryname_

_go 1.21.2_

_require github.com/Szym0nion/HelloWorldWide-Go_ 

**Write a short code and check if the function works correctly (e.g. in the photo below). To run the program:**
## `go run main.go`
![image](https://github.com/Szym0nion/HelloWorldWide-Go/assets/110334194/c559f7b0-5a6c-4c1b-97bd-6ad492238ed5)

As the name suggests, the package has a function that will tell you how to say hello in any language. Here's the list of features:

Afrikaans - **AF**,
Aymara - **AJ**,
Akan - **AK**,
Albanian - **SQ**,
Amharic - **AM**,
Arabic - **AR**,
Assamese - **AS**,
Azerbaijani - **AZ**,
Bambara - **BM**,
Basque - **EU**,
Bengali - **BN**,
Bhojpuri - **BH**,
Byelorussian - **BE**,
Burmese - **MY**,
Bosnian - **BS**,
Bulgarian - **BG**,
Cebuano - **CE**,
Chinese - **ZH**,
Croatian - **HR**,
Czech - **CZ**,
Dogri - **DO**,
Danish - **DA**,
English - **ENG**,
Esperanto - **EO**,
Estonian - **ET**,
Eve - **EE**,
Filipino - **PH**,
Finnish - **FI**,
French - **FR**,
Galician - **GL**,
Ganda - **LG**,
Greek - **EL**,
Georgian - **KA**,
Guarani - **PYG**,
Gujarati - **GU**,
Hausa - **HA**,
Hawaiian - **USHI**,
Hebrew - **HE**,
Hindi - **HI**,
Spanish - **ES**,
Hmong - **HM**,
Igbo - **IG**,
Ilokano - **IL**,
Indonesian - **ID**,
Irish - **GA**,
Icelandic - **IS**,
Japanese - **JA**,
Javanese - **JV**,
Yiddish - **YI**,
Yoruba - **YO**,
Kannada - **KN**,
Catalan - **CA**,
Kazakh - **KK**,
Quechua - **QU**,
Khmer - **KM**,
Xhosa - **XH**,
Kinya-rwanda - **RW**,
Kyrgyz - **KY**,
Konkani GOA - **KOK**,
Korean - **KO**,
Corsican - **CO**,
Haitian Creole - **HT**,
Krio - **KRI**,
Kurdish - **KU**,
Lao - **LO**,
Lingala - **LN**,
Lithuanian - **LT**,
Luxembourgish - **LB**,
Latin - **LA**,
Latvian - **LV**,
Macedonian - **MK**,
Maithilli - **MAI**,
Malayalam - **ML**,
Malay - **MS**,
Maldivian - **DV**,
Malagasy - **MG**,
Maltese - **MT**,
manipuri - **MNI**,
Maori - **MI**,
Marathi - **MR**,
Mizo - **LUS**,
Mongolian - **MN**,
Nepali - **NE**,
Dutch - **NL**,
German - **DE**,
Nyanja - **NY**,
Norwegian - **NO**,
Oriya - **OR**,
Armenian - **HY**,
Oromo - **OM**,
Pashto - **PS**,
Punjabi - **PA**,
Persian - **FA**,
Polish - **PL**,
Portuguese - **PT**,
Russian - **RU**,
Romanian - **RO**,
Samoan - **SM**,
Sanskrit - **SA**,
Serbian - **SR**,
Shona - **SN**,
Sindhi - **SD**,
Slovak - **SK**,
Slovenian - **SL**,
Somali - **SO**,
Sorani - **CKB**,
Southern Sotho - **ST**,
Northern Sotho - **NSO**,
Swahili - **SW**,
Sundanese - **SU**,
Sinhalese - **SI**,
Scottish Gaelic - **GD**,
Swedish - **SV**,
Tajik - **TG**,
Thai - **TH**,
Tamil - **TA**,
Tatar - **TT**,
Telugu - **TE**,
Tigrinya - **TI**,
Tsonga - **TS**,
Turkish - **TR**,
Turkmen - **TK**,
Uyghur - **UG**,
Ukrainian - **UK**,
Urdu - **UR**,
Uzbek - **UZ**,
Welsh - **CY**,
Hungarian - **HU**,
Vietnamese - **VI**,
Italian - **IT**,
West Frisian - **FY**,
Zulu - **ZU**

**function names correspond to ISO 639-1, ISO 639-2, ISO 639-3
