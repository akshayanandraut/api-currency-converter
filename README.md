#### **[Contact the creator](https://akshayanandraut.github.io)**

# CURRENCY CONVERTOR


## Documentation 

### Get real-time currency conversions.



#### Parameters:

```

from	-	From currency code. Must be a valid code. 
to		-	To currency code. Must be a valid code.
amount	-	Amount to be converted. Only numeric data is accepted.
format	-	(Optional). Specifies output response type. JSON(default), XML or DIRECT.

```


#### API call format: 

```

https://akshayanand.herokuapp.com/apis/v1/currency/?from=from_currency&to=to_currency&amount=amount&format=format

```

#### Output format:

##### The output response will be in JSON format. Kindly check the structure below.


###### JSON format

``` 	

{
	"data":{
				"from": *from_currency_type* ,
				"to": *to_currency_type* ,
				"amount": *amount* ,
				"response": *result_value* 
			}
}

```


###### XML format

```

<data>
	<item>
		<from> *from_currency_type* </from>
		<to> *to_currency_type* </to>
		<amount> *amount* </amount>
		<response> *result_value* </response>
	</item>
</data>

```			
				
				
###### DIRECT format	

```

*result_value*

```


##### NOTE:

_Please go through the currency codes and error codes page to properly use the api call parameters avoid confusion._



## Currency Codes

```

 **CODES**		**CURRENCY NAME**				
  AED     United Arab Emirates Dirham (AED) 
  AFN     Afghan Afghani (AFN) 
  ALL     Albanian Lek (ALL) 
  AMD     Armenian Dram (AMD) 
  ANG     Netherlands Antillean Guilder (ANG) 
  AOA     Angolan Kwanza (AOA) 
  ARS     Argentine Peso (ARS) 
  AUD     Australian Dollar (A$) 
  AWG     Aruban Florin (AWG) 
  AZN     Azerbaijani Manat (AZN) 
  BAM     Bosnia-Herzegovina Convertible Mark (BAM) 
  BBD     Barbadian Dollar (BBD) 
  BDT     Bangladeshi Taka (BDT) 
  BGN     Bulgarian Lev (BGN) 
  BHD     Bahraini Dinar (BHD) 
  BIF     Burundian Franc (BIF) 
  BMD     Bermudan Dollar (BMD) 
  BND     Brunei Dollar (BND) 
  BOB     Bolivian Boliviano (BOB) 
  BRL     Brazilian Real (R$) 
  BSD     Bahamian Dollar (BSD) 
  BTC     Bitcoin (฿) 
  BTN     Bhutanese Ngultrum (BTN) 
  BWP     Botswanan Pula (BWP) 
  BYN     Belarusian Ruble (BYN) 
  BYR     Belarusian Ruble (2000-2016) (BYR) 
  BZD     Belize Dollar (BZD) 
  CAD     Canadian Dollar (CA$) 
  CDF     Congolese Franc (CDF) 
  CHF     Swiss Franc (CHF) 
  CLF     Chilean Unit of Account (UF) (CLF) 
  CLP     Chilean Peso (CLP) 
  CNH     CNH (CNH) 
  CNY     Chinese Yuan (CN¥) 
  COP     Colombian Peso (COP) 
  CRC     Costa Rican Colón (CRC) 
  CUP     Cuban Peso (CUP) 
  CVE     Cape Verdean Escudo (CVE) 
  CZK     Czech Republic Koruna (CZK) 
  DEM     German Mark (DEM) 
  DJF     Djiboutian Franc (DJF) 
  DKK     Danish Krone (DKK) 
  DOP     Dominican Peso (DOP) 
  DZD     Algerian Dinar (DZD) 
  EGP     Egyptian Pound (EGP) 
  ERN     Eritrean Nakfa (ERN) 
  ETB     Ethiopian Birr (ETB) 
  EUR     Euro (€) 
  FIM     Finnish Markka (FIM) 
  FJD     Fijian Dollar (FJD) 
  FKP     Falkland Islands Pound (FKP) 
  FRF     French Franc (FRF) 
  GBP     British Pound (£) 
  GEL     Georgian Lari (GEL) 
  GHS     Ghanaian Cedi (GHS) 
  GIP     Gibraltar Pound (GIP) 
  GMD     Gambian Dalasi (GMD) 
  GNF     Guinean Franc (GNF) 
  GTQ     Guatemalan Quetzal (GTQ) 
  GYD     Guyanaese Dollar (GYD) 
  HKD     Hong Kong Dollar (HK$) 
  HNL     Honduran Lempira (HNL) 
  HRK     Croatian Kuna (HRK) 
  HTG     Haitian Gourde (HTG) 
  HUF     Hungarian Forint (HUF) 
  IDR     Indonesian Rupiah (IDR) 
  IEP     Irish Pound (IEP) 
  ILS     Israeli New Sheqel (₪) 
  INR     Indian Rupee (₹) 
  IQD     Iraqi Dinar (IQD) 
  IRR     Iranian Rial (IRR) 
  ISK     Icelandic Króna (ISK) 
  ITL     Italian Lira (ITL) 
  JMD     Jamaican Dollar (JMD) 
  JOD     Jordanian Dinar (JOD) 
  JPY     Japanese Yen (¥) 
  KES     Kenyan Shilling (KES) 
  KGS     Kyrgystani Som (KGS) 
  KHR     Cambodian Riel (KHR) 
  KMF     Comorian Franc (KMF) 
  KPW     North Korean Won (KPW) 
  KRW     South Korean Won (₩) 
  KWD     Kuwaiti Dinar (KWD) 
  KYD     Cayman Islands Dollar (KYD) 
  KZT     Kazakhstani Tenge (KZT) 
  LAK     Laotian Kip (LAK) 
  LBP     Lebanese Pound (LBP) 
  LKR     Sri Lankan Rupee (LKR) 
  LRD     Liberian Dollar (LRD) 
  LSL     Lesotho Loti (LSL) 
  LTL     Lithuanian Litas (LTL) 
  LVL     Latvian Lats (LVL) 
  LYD     Libyan Dinar (LYD) 
  MAD     Moroccan Dirham (MAD) 
  MDL     Moldovan Leu (MDL) 
  MGA     Malagasy Ariary (MGA) 
  MKD     Macedonian Denar (MKD) 
  MMK     Myanmar Kyat (MMK) 
  MNT     Mongolian Tugrik (MNT) 
  MOP     Macanese Pataca (MOP) 
  MRO     Mauritanian Ouguiya (MRO) 
  MUR     Mauritian Rupee (MUR) 
  MVR     Maldivian Rufiyaa (MVR) 
  MWK     Malawian Kwacha (MWK) 
  MXN     Mexican Peso (MX$) 
  MYR     Malaysian Ringgit (MYR) 
  MZN     Mozambican Metical (MZN) 
  NAD     Namibian Dollar (NAD) 
  NGN     Nigerian Naira (NGN) 
  NIO     Nicaraguan Córdoba (NIO) 
  NOK     Norwegian Krone (NOK) 
  NPR     Nepalese Rupee (NPR) 
  NZD     New Zealand Dollar (NZ$) 
  OMR     Omani Rial (OMR) 
  PAB     Panamanian Balboa (PAB) 
  PEN     Peruvian Nuevo Sol (PEN) 
  PGK     Papua New Guinean Kina (PGK) 
  PHP     Philippine Peso (PHP) 
  PKG     PKG (PKG) 
  PKR     Pakistani Rupee (PKR) 
  PLN     Polish Zloty (PLN) 
  PYG     Paraguayan Guarani (PYG) 
  QAR     Qatari Rial (QAR) 
  RON     Romanian Leu (RON) 
  RSD     Serbian Dinar (RSD) 
  RUB     Russian Ruble (RUB) 
  RWF     Rwandan Franc (RWF) 
  SAR     Saudi Riyal (SAR) 
  SBD     Solomon Islands Dollar (SBD) 
  SCR     Seychellois Rupee (SCR) 
  SDG     Sudanese Pound (SDG) 
  SEK     Swedish Krona (SEK) 
  SGD     Singapore Dollar (SGD) 
  SHP     St. Helena Pound (SHP) 
  SKK     Slovak Koruna (SKK) 
  SLL     Sierra Leonean Leone (SLL) 
  SOS     Somali Shilling (SOS) 
  SRD     Surinamese Dollar (SRD) 
  STD     São Tomé &amp; Príncipe Dobra (STD) 
  SVC     Salvadoran Colón (SVC) 
  SYP     Syrian Pound (SYP) 
  SZL     Swazi Lilangeni (SZL) 
  THB     Thai Baht (THB) 
  TJS     Tajikistani Somoni (TJS) 
  TMT     Turkmenistani Manat (TMT) 
  TND     Tunisian Dinar (TND) 
  TOP     Tongan Paʻanga (TOP) 
  TRY     Turkish Lira (TRY) 
  TTD     Trinidad &amp; Tobago Dollar (TTD) 
  TWD     New Taiwan Dollar (NT$) 
  TZS     Tanzanian Shilling (TZS) 
  UAH     Ukrainian Hryvnia (UAH) 
  UGX     Ugandan Shilling (UGX) 
  USD     US Dollar ($) 
  UYU     Uruguayan Peso (UYU) 
  UZS     Uzbekistani Som (UZS) 
  VEF     Venezuelan Bolívar (VEF) 
  VND     Vietnamese Dong (₫) 
  VUV     Vanuatu Vatu (VUV)   
  WST     Samoan Tala (WST) 
  XAF     Central African CFA Franc (FCFA) 
  XCD     East Caribbean Dollar (EC$) 
  XDR     Special Drawing Rights (XDR) 
  XOF     West African CFA Franc (CFA) 
  XPF     CFP Franc (CFPF) 
  YER     Yemeni Rial (YER) 
  ZAR     South African Rand (ZAR) 
  ZMK     Zambian Kwacha (1968–2012) (ZMK) 
  ZMW     Zambian Kwacha (ZMW) 
  ZWL     Zimbabwean Dollar (2009) (ZWL) 
  
```

## Error Codes

```

**ERROR NO.** 		 **DESCRIPTION**

001	-		This error occurs because one of the required parameters(from, to and amount) is not provided with the call. Please check the documentation for proper api call.

002	-		This error occurs because the from and to currency parameters are the same. 
						
003	-		This error occurs because the from parameter is invalid. Please check the currency codes in the documentation for valid currency codes.
 						
004	-		This error occurs because the from and to currency parameters are the same. 			

005	-		This error occurs because the amount specified is not a valid numeric. 			
			
```

[Contact the creator](https://akshayanandraut.github.io)