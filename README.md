# Localization

These are the official localization files for LocationSimulator. Feel free to fork the project and contribute to an existing language or create a new one. The easiest why to edit these files is by using [LocalizationEditor](https://github.com/igorkulman/iOSLocalizationEditor). Just click on the release link on the right sidebar and download the latest release. To contribute a new language follow these steps: 

1. Download or clone this repository. 
2. Create a new folder with your language code and the file ending `lproj`. 
3. Place a new empty file called `Localizable.strings` inside the newly created folder.
4. Start `LocalizationEditor` and click on the folder icon.
5. Choose the downloaded `Localization` folder.
6. You'll get a list with all strings to localize. Missing strings are highlighted with a red border.
7. Open a pull request or open a new issue and upload your strings.

If you want to edit an existing language just skip step 2 and 3. If you need help with creating a new language, let me know! If you are a developer or know how to install python3 and use a terminal you can easily create a new language which already has some pre-translated entries. 

Run the following command and replace `LANGUAGE_CODE` with your language code. E.g. this would be `de` for german.

```
python3 MainMenuTranslate.py Base.lproj/Localizable.strings -l LANGUAGE_CODE
```

## Current status

##### Fully supported languages:
- Englisch
- German
- Swedisch

##### Partial supported languages:
- Spanish
- Chinese
- Italian

##### Almost no translation: 
- French

## License

The MainMenuTranslations.plist is extracted from [here](https://github.com/core-code/MiscApps/tree/c396d60ceb6720b4e9c7052c57557c52b525a1be/Translator). It is therefore licened under the MIT license.

## Language codes

<details>
  <summary>Click to show the table</summary>
</br>

| Code| Language                    |  
|-----|-----------------------------|
| aa  | Afar                        |
| ab  | Abkhazian                   |
| ace | Achinese                    |
| ach | Acoli                       |
| ada | Adangme                     |
| ady | Adyghe                      |
| ae  | Avestan                     |
| aeb | Tunisian Arabic             |
| af  | Afrikaans                   |
| afh | Afrihili                    |
| agq | Aghem                       |
| ain | Ainu                        |
| ak  | Akan                        |
| akk | Akkadian                    |
| akz | Alabama                     |
| ale | Aleut                       |
| aln | Gheg Albanian               |
| alt | Southern Altai              |
| am  | Amharic                     |
| an  | Aragonese                   |
| ang | Old English                 |
| anp | Angika                      |
| ar  | Arabic                      |
| arc | Aramaic                     |
| arn | Mapuche                     |
| aro | Araona                      |
| arp | Arapaho                     |
| arq | Algerian Arabic             |
| ars | Arabic, Najdi               |
| arw | Arawak                      |
| ary | Moroccan Arabic             |
| arz | Egyptian Arabic             |
| as  | Assamese                    |
| asa | Asu                         |
| ase | American Sign Language      |
| ast | Asturian                    |
| av  | Avaric                      |
| avk | Kotava                      |
| awa | Awadhi                      |
| ay  | Aymara                      |
| az  | Azerbaijani                 |
| ba  | Bashkir                     |
| bal | Baluchi                     |
| ban | Balinese                    |
| bar | Bavarian                    |
| bas | Basaa                       |
| bax | Bamun                       |
| bbc | Batak Toba                  |
| bbj | Ghomala                     |
| be  | Belarusian                  |
| bej | Beja                        |
| bem | Bemba                       |
| bew | Betawi                      |
| bez | Bena                        |
| bfd | Bafut                       |
| bfq | Badaga                      |
| bg  | Bulgarian                   |
| bgn | Western Balochi             |
| bho | Bhojpuri                    |
| bi  | Bislama                     |
| bik | Bikol                       |
| bin | Bini                        |
| bjn | Banjar                      |
| bkm | Kom                         |
| bla | Siksiká                     |
| bm  | Bambara                     |
| bn  | Bangla                      |
| bo  | Tibetan                     |
| bpy | Bishnupriya                 |
| bqi | Bakhtiari                   |
| br  | Breton                      |
| bra | Braj                        |
| brh | Brahui                      |
| brx | Bodo                        |
| bs  | Bosnian                     |
| bss | Akoose                      |
| bua | Buriat                      |
| bug | Buginese                    |
| bum | Bulu                        |
| byn | Blin                        |
| byv | Medumba                     |
| ca  | Catalan                     |
| cad | Caddo                       |
| car | Carib                       |
| cay | Cayuga                      |
| cch | Atsam                       |
| ccp | Chakma                      |
| ce  | Chechen                     |
| ceb | Cebuano                     |
| cgg | Chiga                       |
| ch  | Chamorro                    |
| chb | Chibcha                     |
| chg | Chagatai                    |
| chk | Chuukese                    |
| chm | Mari                        |
| chn | Chinook Jargon              |
| cho | Choctaw                     |
| chp | Chipewyan                   |
| chr | Cherokee                    |
| chy | Cheyenne                    |
| ckb | Kurdish, Sorani             |
| co  | Corsican                    |
| cop | Coptic                      |
| cps | Capiznon                    |
| cr  | Cree                        |
| crh | Crimean Turkish             |
| cs  | Czech                       |
| csb | Kashubian                   |
| cu  | Church Slavic               |
| cv  | Chuvash                     |
| cy  | Welsh                       |
| da  | Danish                      |
| dak | Dakota                      |
| dar | Dargwa                      |
| dav | Taita                       |
| de  | German                      |
| del | Delaware                    |
| den | Slave                       |
| dgr | Dogrib                      |
| din | Dinka                       |
| dje | Zarma                       |
| doi | Dogri                       |
| dsb | Lower Sorbian               |
| dtp | Central Dusun               |
| dua | Duala                       |
| dum | Middle Dutch                |
| dv  | Dhivehi                     |
| dyo | Jola-Fonyi                  |
| dyu | Dyula                       |
| dz  | Dzongkha                    |
| dzg | Dazaga                      |
| ebu | Embu                        |
| ee  | Ewe                         |
| efi | Efik                        |
| egl | Emilian                     |
| egy | Ancient Egyptian            |
| eka | Ekajuk                      |
| el  | Greek                       |
| elx | Elamite                     |
| en  | English                     |
| enm | Middle English              |
| eo  | Esperanto                   |
| es  | Spanish                     |
| esu | Central Yupik               |
| et  | Estonian                    |
| eu  | Basque                      |
| ewo | Ewondo                      |
| ext | Extremaduran                |
| fa  | Persian                     |
| fan | Fang                        |
| fat | Fanti                       |
| ff  | Fula                        |
| fi  | Finnish                     |
| fil | Filipino                    |
| fit | Tornedalen Finnish          |
| fj  | Fijian                      |
| fo  | Faroese                     |
| fon | Fon                         |
| fr  | French                      |
| frc | Cajun French                |
| frm | Middle French               |
| fro | Old French                  |
| frp | Arpitan                     |
| frr | Northern Frisian            |
| frs | Eastern Frisian             |
| fur | Friulian                    |
| fy  | Western Frisian             |
| ga  | Irish                       |
| gaa | Ga                          |
| gag | Gagauz                      |
| gan | Gan Chinese                 |
| gay | Gayo                        |
| gba | Gbaya                       |
| gbz | Zoroastrian Dari            |
| gd  | Scottish Gaelic             |
| gez | Geez                        |
| gil | Gilbertese                  |
| gl  | Galician                    |
| glk | Gilaki                      |
| gmh | Middle High German          |
| gn  | Guarani                     |
| goh | Old High German             |
| gom | Goan Konkani                |
| gon | Gondi                       |
| gor | Gorontalo                   |
| got | Gothic                      |
| grb | Grebo                       |
| grc | Ancient Greek               |
| gsw | Swiss German                |
| gu  | Gujarati                    |
| guc | Wayuu                       |
| gur | Frafra                      |
| guz | Gusii                       |
| gv  | Manx                        |
| gwi | Gwichʼin                    |
| ha  | Hausa                       |
| hai | Haida                       |
| hak | Hakka Chinese               |
| haw | Hawaiian                    |
| he  | Hebrew                      |
| hi  | Hindi                       |
| hif | Fiji Hindi                  |
| hil | Hiligaynon                  |
| hit | Hittite                     |
| hmn | Hmong                       |
| ho  | Hiri Motu                   |
| hr  | Croatian                    |
| hsb | Upper Sorbian               |
| hsn | Xiang Chinese               |
| ht  | Haitian Creole              |
| hu  | Hungarian                   |
| hup | Hupa                        |
| hy  | Armenian                    |
| hz  | Herero                      |
| ia  | Interlingua                 |
| iba | Iban                        |
| ibb | Ibibio                      |
| id  | Indonesian                  |
| ie  | Interlingue                 |
| ig  | Igbo                        |
| ii  | Sichuan Yi                  |
| ik  | Inupiaq                     |
| ilo | Iloko                       |
| inh | Ingush                      |
| io  | Ido                         |
| is  | Icelandic                   |
| it  | Italian                     |
| iu  | Inuktitut                   |
| izh | Ingrian                     |
| ja  | Japanese                    |
| jam | Jamaican Creole English     |
| jbo | Lojban                      |
| jgo | Ngomba                      |
| jmc | Machame                     |
| jpr | Judeo-Persian               |
| jrb | Judeo-Arabic                |
| jut | Jutish                      |
| jv  | Javanese                    |
| ka  | Georgian                    |
| kaa | Kara-Kalpak                 |
| kab | Kabyle                      |
| kac | Kachin                      |
| kaj | Jju                         |
| kam | Kamba                       |
| kaw | Kawi                        |
| kbd | Kabardian                   |
| kbl | Kanembu                     |
| kcg | Tyap                        |
| kde | Makonde                     |
| kea | Kabuverdianu                |
| ken | Kenyang                     |
| kfo | Koro                        |
| kg  | Kongo                       |
| kgp | Kaingang                    |
| kha | Khasi                       |
| kho | Khotanese                   |
| khq | Koyra Chiini                |
| khw | Khowar                      |
| ki  | Kikuyu                      |
| kiu | Kirmanjki                   |
| kj  | Kuanyama                    |
| kk  | Kazakh                      |
| kkj | Kako                        |
| kl  | Kalaallisut                 |
| kln | Kalenjin                    |
| km  | Khmer                       |
| kmb | Kimbundu                    |
| kn  | Kannada                     |
| ko  | Korean                      |
| koi | Komi-Permyak                |
| kok | Konkani                     |
| kos | Kosraean                    |
| kpe | Kpelle                      |
| kr  | Kanuri                      |
| krc | Karachay-Balkar             |
| kri | Krio                        |
| krj | Kinaray-a                   |
| krl | Karelian                    |
| kru | Kurukh                      |
| ks  | Kashmiri                    |
| ksb | Shambala                    |
| ksf | Bafia                       |
| ksh | Colognian                   |
| ku  | Kurdish                     |
| kum | Kumyk                       |
| kut | Kutenai                     |
| kv  | Komi                        |
| kw  | Cornish                     |
| ky  | Kyrgyz                      |
| la  | Latin                       |
| lad | Ladino                      |
| lag | Langi                       |
| lah | Lahnda                      |
| lam | Lamba                       |
| lb  | Luxembourgish               |
| lez | Lezghian                    |
| lfn | Lingua Franca Nova          |
| lg  | Ganda                       |
| li  | Limburgish                  |
| lij | Ligurian                    |
| liv | Livonian                    |
| lkt | Lakota                      |
| lmo | Lombard                     |
| ln  | Lingala                     |
| lo  | Lao                         |
| lol | Mongo                       |
| loz | Lozi                        |
| lrc | Northern Luri               |
| lt  | Lithuanian                  |
| ltg | Latgalian                   |
| lu  | Luba-Katanga                |
| lua | Luba-Lulua                  |
| lui | Luiseno                     |
| lun | Lunda                       |
| luo | Luo                         |
| lus | Mizo                        |
| luy | Luyia                       |
| lv  | Latvian                     |
| lzh | Literary Chinese            |
| lzz | Laz                         |
| mad | Madurese                    |
| maf | Mafa                        |
| mag | Magahi                      |
| mai | Maithili                    |
| mak | Makasar                     |
| man | Mandingo                    |
| mas | Masai                       |
| mde | Maba                        |
| mdf | Moksha                      |
| mdh |                             |
| mdr | Mandar                      |
| men | Mende                       |
| mer | Meru                        |
| mfe | Morisyen                    |
| mg  | Malagasy                    |
| mga | Middle Irish                |
| mgh | Makhuwa-Meetto              |
| mgo | Metaʼ                       |
| mh  | Marshallese                 |
| mi  | Māori                       |
| mic | Mi'kmaq                     |
| min | Minangkabau                 |
| mis |                             |
| mk  | Macedonian                  |
| ml  | Malayalam                   |
| mn  | Mongolian                   |
| mnc | Manchu                      |
| mni | Manipuri                    |
| moh | Mohawk                      |
| mos | Mossi                       |
| mr  | Marathi                     |
| mrj | Western Mari                |
| ms  | Malay                       |
| mt  | Maltese                     |
| mua | Mundang                     |
| mul | Multiple languages          |
| mus | Creek                       |
| mwl | Mirandese                   |
| mwr | Marwari                     |
| mwv | Mentawai                    |
| my  | Burmese                     |
| mye | Myene                       |
| myv | Erzya                       |
| mzn | Mazanderani                 |
| na  | Nauru                       |
| nan | Min Nan Chinese             |
| nap | Neapolitan                  |
| naq | Nama                        |
| nb  | Norwegian Bokmål            |
| nd  | North Ndebele               |
| nds | Low German                  |
| ne  | Nepali                      |
| new | Newari                      |
| ng  | Ndonga                      |
| nia | Nias                        |
| niu | Niuean                      |
| njo | Ao Naga                     |
| nl  | Dutch                       |
| nmg | Kwasio                      |
| nn  | Norwegian Nynorsk           |
| nnh | Ngiemboon                   |
| no  | Norwegian                   |
| nog | Nogai                       |
| non | Old Norse                   |
| nov | Novial                      |
| nqo | N’Ko                        |
| nr  | South Ndebele               |
| nso | Northern Sotho              |
| nus | Nuer                        |
| nv  | Navajo                      |
| nwc | Classical Newari            |
| ny  | Nyanja                      |
| nym | Nyamwezi                    |
| nyn | Nyankole                    |
| nyo | Nyoro                       |
| nzi | Nzima                       |
| oc  | Occitan                     |
| oj  | Ojibwa                      |
| om  | Oromo                       |
| or  | Odia                        |
| os  | Ossetic                     |
| osa | Osage                       |
| ota | Ottoman Turkish             |
| otk |                             |
| oui |                             |
| pa  | Punjabi                     |
| pag | Pangasinan                  |
| pal | Pahlavi                     |
| pam | Pampanga                    |
| pap | Papiamento                  |
| pau | Palauan                     |
| pcd | Picard                      |
| pcm | Nigerian Pidgin             |
| pdc | Pennsylvania German         |
| pdt | Plautdietsch                |
| peo | Old Persian                 |
| pfl | Palatine German             |
| phn | Phoenician                  |
| pi  | Pali                        |
| pl  | Polish                      |
| pms | Piedmontese                 |
| pnt | Pontic                      |
| pon | Pohnpeian                   |
| prg | Prussian                    |
| pro | Old Provençal               |
| ps  | Pashto                      |
| pt  | Portuguese                  |
| qu  | Quechua                     |
| quc | Kʼicheʼ                     |
| qug | Chimborazo Highland Quichua |
| raj | Rajasthani                  |
| rap | Rapanui                     |
| rar | Rarotongan                  |
| rgn | Romagnol                    |
| rhg | Rohingya                    |
| rif | Riffian                     |
| rm  | Romansh                     |
| rn  | Rundi                       |
| ro  | Romanian                    |
| rof | Rombo                       |
| rom | Romany                      |
| rtm | Rotuman                     |
| ru  | Russian                     |
| rue | Rusyn                       |
| rug | Roviana                     |
| rup | Aromanian                   |
| rw  | Kinyarwanda                 |
| rwk | Rwa                         |
| sa  | Sanskrit                    |
| sad | Sandawe                     |
| sah | Yakut                       |
| sam | Samaritan Aramaic           |
| saq | Samburu                     |
| sas | Sasak                       |
| sat | Santali                     |
| saz | Saurashtra                  |
| sba | Ngambay                     |
| sbp | Sangu                       |
| sc  | Sardinian                   |
| scn | Sicilian                    |
| sco | Scots                       |
| sd  | Sindhi                      |
| sdc | Sassarese Sardinian         |
| sdh | Southern Kurdish            |
| se  | Northern Sami               |
| see | Seneca                      |
| seh | Sena                        |
| sei | Seri                        |
| sel | Selkup                      |
| ses | Koyraboro Senni             |
| sg  | Sango                       |
| sga | Old Irish                   |
| sgs | Samogitian                  |
| shi | Tachelhit                   |
| shn | Shan                        |
| shu | Chadian Arabic              |
| si  | Sinhala                     |
| sid | Sidamo                      |
| sk  | Slovak                      |
| sl  | Slovenian                   |
| sli | Lower Silesian              |
| sly | Selayar                     |
| sm  | Samoan                      |
| sma | Southern Sami               |
| smj | Lule Sami                   |
| smn | Inari Sami                  |
| sms | Skolt Sami                  |
| sn  | Shona                       |
| snk | Soninke                     |
| so  | Somali                      |
| sog | Sogdien                     |
| sq  | Albanian                    |
| sr  | Serbian                     |
| srn | Sranan Tongo                |
| srr | Serer                       |
| ss  | Swati                       |
| ssy | Saho                        |
| st  | Southern Sotho              |
| stq | Saterland Frisian           |
| su  | Sundanese                   |
| suk | Sukuma                      |
| sus | Susu                        |
| sux | Sumerian                    |
| sv  | Swedish                     |
| sw  | Swahili                     |
| swb | Comorian                    |
| syc | Classical Syriac            |
| syr | Assyrian                    |
| szl | Silesian                    |
| ta  | Tamil                       |
| tcy | Tulu                        |
| te  | Telugu                      |
| tem | Timne                       |
| teo | Teso                        |
| ter | Tereno                      |
| tet | Tetum                       |
| tg  | Tajik                       |
| th  | Thai                        |
| ti  | Tigrinya                    |
| tig | Tigre                       |
| tiv | Tiv                         |
| tk  | Turkmen                     |
| tkl | Tokelau                     |
| tkr | Tsakhur                     |
| tlh | Klingon                     |
| tli | Tlingit                     |
| tly | Talysh                      |
| tmh | Tamashek                    |
| tn  | Tswana                      |
| to  | Tongan                      |
| tog | Nyasa Tonga                 |
| tpi | Tok Pisin                   |
| tr  | Turkish                     |
| tru | Turoyo                      |
| trv | Taroko                      |
| ts  | Tsonga                      |
| tsd | Tsakonian                   |
| tsi | Tsimshian                   |
| tt  | Tatar                       |
| ttt | Muslim Tat                  |
| tum | Tumbuka                     |
| tvl | Tuvalu                      |
| tw  | Twi                         |
| twq | Tasawaq                     |
| ty  | Tahitian                    |
| tyv | Tuvinian                    |
| tzm | Central Atlas Tamazight     |
| udm | Udmurt                      |
| ug  | Uyghur                      |
| uga | Ugaritic                    |
| uk  | Ukrainian                   |
| umb | Umbundu                     |
| und | Unknown language            |
| ur  | Urdu                        |
| uz  | Uzbek                       |
| vai | Vai                         |
| ve  | Venda                       |
| vec | Venetian                    |
| vep | Veps                        |
| vi  | Vietnamese                  |
| vls | West Flemish                |
| vmf | Main-Franconian             |
| vo  | Volapük                     |
| vot | Votic                       |
| vro | Võro                        |
| vun | Vunjo                       |
| wa  | Walloon                     |
| wae | Walser                      |
| wal | Wolaytta                    |
| war | Waray                       |
| was | Washo                       |
| wbp | Warlpiri                    |
| wo  | Wolof                       |
| wuu | Shanghainese                |
| xal | Kalmyk                      |
| xh  | Xhosa                       |
| xmf | Mingrelian                  |
| xog | Soga                        |
| yao | Yao                         |
| yap | Yapese                      |
| yav | Yangben                     |
| ybb | Yemba                       |
| yi  | Yiddish                     |
| yo  | Yoruba                      |
| yrl | Nheengatu                   |
| yue | Cantonese                   |
| za  | Zhuang                      |
| zap | Zapotec                     |
| zbl | Blissymbols                 |
| zea | Zeelandic                   |
| zen | Zenaga                      |
| zgh | Standard Moroccan Tamazight |
| zh  | Chinese                     |
| zu  | Zulu                        |
| zun | Zuni                        |
| zxx | No linguistic content       |
| zza | Zaza                        |

</details>
