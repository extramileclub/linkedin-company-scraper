### LinkedIn Company Scraper

This actor can scrape detailed information about companies listed on LinkedIn without any hassle. It takes company URLs and provides you with structured data. You can scrape a single URL or a list of URLs.

[linkedin-company-scraper](https://apify.com/logical_scrapers/linkedin-company-scraper)

### How It Works
The LinkedIn Company Scraper allows you to gather detailed information from LinkedIn company pages. Simply provide the URLs of the companies you want to scrape, and the actor will fetch the data for you. This scraper is perfect for data analysis, research, and gaining insights from LinkedIn content.

### What Data You Can Get from This Scraper

| Field                        | Description                                               |
|------------------------------|-----------------------------------------------------------|
| 🏢 name                      | The name of the company                                    |
| 🌐 url                       | The LinkedIn URL of the company                            |
| 🏙️ mainAddress.streetAddress | The street address of the company                          |
| 🏙️ mainAddress.addressLocality | The city where the company is located                   |
| 🏙️ mainAddress.addressRegion | The state/region where the company is located              |
| 🌍 mainAddress.addressCountry | The country where the company is located                  |
| 📝 description               | The description of the company                             |
| 👥 numberOfEmployees         | The number of employees at the company                     |
| 🖼️ logo.contentUrl          | The URL of the company's logo                              |
| 🌐 website                   | The website of the company                                 |
| 🏢 industry                  | The industry in which the company operates                 |
| 📏 companySize               | The size of the company                                    |
| 📍 headquarters              | The headquarters of the company                            |
| 🏢 type                      | The type of the company (e.g., Public, Private)            |
| 📅 founded                   | The year the company was founded                           |
| 🏆 specialties               | The specialties of the company                             |
| 📄 similarPages              | Similar companies, including their name, industry, address, and LinkedIn URL |


### Input

Provide an array of TikTok post URLs.

Example:
```
[
    "https://www.linkedin.com/company/microsoft"
]
```


### sample output 
Here is the sample output of this actor:

```
[
  {
    "name": "Microsoft",
    "url": "https://www.linkedin.com/company/microsoft",
    "mainAddress": {
      "type": "PostalAddress",
      "streetAddress": "1 Microsoft Way",
      "addressLocality": "Redmond",
      "addressRegion": "Washington",
      "postalCode": "98052",
      "addressCountry": "US"
    },
    "description": "Every company has a mission. What's ours? To empower every person and every organization to achieve more. We believe technology can and should be a force for good and that meaningful innovation contributes to a brighter world in the future and today. Our culture doesn’t just encourage curiosity; it embraces it. Each day we make progress together by showing up as our authentic selves. We show up with a learn-it-all mentality. We show up cheering on others, knowing their success doesn't diminish our own. We show up every day open to learning our own biases, changing our behavior, and inviting in differences. Because impact matters. \n\nMicrosoft operates in 190 countries and is made up of more than 220,000 passionate employees worldwide.",
    "numberOfEmployees": 229131,
    "logo": {
      "contentUrl": "https://media.licdn.com/dms/image/C560BAQE88xCsONDULQ/company-logo_200_200/0/1630652622688/microsoft_logo?e=2147483647&v=beta&t=lrgXR6JnGSOHh9TMrOApgjnVMkQeZytbf87qVfOaiuU",
      "description": "Microsoft",
      "@type": "ImageObject"
    },
    "Website": "",
    "Industry": "Software Development",
    "Company size": "10,001+ employees",
    "Headquarters": "Redmond, Washington",
    "Type": "Public Company",
    "Specialties": "Business Software, Developer Tools, Home & Educational Software, Tablets, Search, Advertising, Servers, Windows Operating System, Windows Applications & Platforms, Smartphones, Cloud Computing, Quantum Computing, Future of Work, Productivity, AI, Artificial Intelligence, Machine Learning, Laptops, Mixed Reality, Virtual Reality, Gaming, Developers, and IT Professional",
    "addresses": [
      "1 Denison Street, North Sydney, NSW 2060, AU",
      "1950 Meadowvale Blvd, Mississauga, Ontario L5N 8L9, CA",
      "39, Quai du Président Roosevelt, Issy-les-Moulineaux, Île-de-France 92130, FR",
      "Walter-Gropius-Straße 5, München, 80807, DE",
      "2-16-3 Konan, Minato-ku, Tokyo 108-0075, JP",
      "Thames Valley Park Drive, Reading, Berkshire RG6 1WG, GB",
      "Kanalvej 7, 2800 Kongens Lyngby, DK",
      "Luchthavenlaan 1k, Zaventem, Flemish Region 1930, BE",
      "Keilalahdentie 2-4, Espoo, 02150, FI",
      "Viale Pasubio, 21, Milan, Lombardy 20154, IT",
      "50, Jongro 1-gil, Jongno-gu, Seoul, KR",
      "Evert van de Beekstraat 354, Schiphol, North Holland 1118 CZ, NL",
      "Dronning Eufemia gate 71, Oslo, 0194, NO",
      "Paseo del Club Deportivo, 1, Centro Empresarial La Finca - Edificio 1, Pozuelo de Alarcón, 28223, ES",
      "Regeringsgatan 25, Stockholm, 111 53, SE",
      "8058 Zürich-Flughafen, The Circle 02, Zürich, CH",
      "Av. President Juscelino Kubitscheck, 1909, Sao Paulo, 04551-065, BR",
      "海淀区，丹棱街5号, 中国, 100080, CN",
      "DLF Building No.5 (Epitome), Cyber City, DLF Phase III, Gurgaon, 122002, IN",
      "Av. Vasco de Quiroga 3200, Col. Centro de Ciudad Santa Fe, Del Álvaro Obregón, 01210, MX",
      "Ул. Крылатская, 17, Москва, 121614, RU",
      "3012 William Nicol Drive, Johannesburg, Gauteng 2191, ZA",
      "Aydın Sokak No:7, Bellevue Residences, Levent Mahallesi, İstanbul, 34340, TR",
      "Am Europlatz 3, Vienna, 1120, AT",
      "100 Cyberport Road, 15/F, Cyberport 2, Hong Kong, HK",
      "One Microsoft Place, South County Business Park, Leopardstown, Dublin 18 D18, IE",
      "רחוב הפנינה 2, רעננה, 43107, IL",
      "22 Viaduct Harbour Avenue, Auckland, NZ",
      "Al. Jerozolimskie 195a, Warszawa, 02-222, PL",
      "Rua do Fogo de Santelmo, Lote 2.07.02, Lisboa, 1990 – 110, PT",
      "The Business Gate, Building A2 Airport Road, Cordobah, Riyadh, 11552, SA",
      "182 Cecil Street, #13-01 Frasers Tower, Singapore, 069547, SG",
      "Pradiareň 1900, Svätoplukova 2A, Bratislava, 821 08, SK",
      "Zhongxiao East Road Section 5 No. 68, Xinyi District, Taipei City, TW",
      "Sheikh Zayed Road, Dubai Internet City, Building No 8, Dubai, 52244, AE",
      "1106 Federal Capital, Bouchard 710, Buenos Aires, AR",
      "Av. Vitacura 6844, Santiago, CL",
      "Calle 92 # 11 – 51, Bogota, CO",
      "Kilo 28, Cairo/Alex Desert Road, Abou Rawash, Cairo, EG",
      "Jl. Jend. Sudirman Kav. 52-53, Jakarta Stock Exchange Building Tower II, Jakarta, 12190, ID",
      "No. 211, Jalan Tun Sambanthan, Menara Shell, Kuala Lumpur, 50470, MY",
      "Ayala Avenue cor Edsa, Brgy. San Lorenzo,, 11F, One Ayala East Tower, Makati City, 1223, PH",
      "Bulevardul Iuliu Maniu nr. 6P, Clădirea Campus 6.2, București, 061103, RO",
      "87/2 ถนนวิทยุ แขวงลุมพินี, ตึก CRC Tower ออลซีซันส์เพลส, เขตปทุมวัน กรุงเทพฯ, 10330, TH"
    ],
    "affiliatedPages": [
      {
        "name": "GitHub",
        "industry": "Software Development",
        "address": "San Francisco, CA",
        "linkeinUrl": "https://www.linkedin.com/company/github"
      },
      {
        "name": "Microsoft Learn",
        "industry": "IT Services and IT Consulting",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoftlearn/"
      },
      {
        "name": "Microsoft Cloud",
        "industry": "Software Development",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-cloud-platform/"
      },
      {
        "name": "Microsoft 365",
        "industry": "IT Services and IT Consulting",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-365/"
      },
      {
        "name": "Microsoft Security",
        "industry": "IT Services and IT Consulting",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-security/"
      },
      {
        "name": "Microsoft Developer",
        "industry": "Software Development",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-developers/"
      },
      {
        "name": "Microsoft Research",
        "industry": "Think Tanks",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoftresearch/"
      },
      {
        "name": "Windows Developer",
        "industry": null,
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/windows-developers/"
      },
      {
        "name": "Microsoft Azure",
        "industry": "Technology, Information and Internet",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-azure/"
      },
      {
        "name": "Microsoft Dynamics 365",
        "industry": "Software Development",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-dynamics/"
      },
      {
        "name": "Microsoft Visual Studio",
        "industry": "Software Development",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-visual-studio/"
      },
      {
        "name": "Microsoft AI Cloud Partner Program",
        "industry": "Information Technology & Services",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-cloud-partner-program/"
      },
      {
        "name": "Microsoft Power Platform",
        "industry": "Software Development",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-power-platform/"
      },
      {
        "name": "Microsoft SQL Server",
        "industry": "Software Development",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/showcase/msft-sql-server/"
      },
      {
        "name": "Microsoft On the Issues",
        "industry": "Technology, Information and Internet",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-on-the-issues/"
      },
      {
        "name": "Microsoft Surface",
        "industry": "Computer Hardware",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-surface/"
      },
      {
        "name": "Microsoft Fabric",
        "industry": "Data Infrastructure and Analytics",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoftfabric/"
      },
      {
        "name": "Microsoft Advertising",
        "industry": "Advertising Services",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-advertising/"
      },
      {
        "name": "Microsoft in Government",
        "industry": "Software Development",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-in-government/"
      },
      {
        "name": "Microsoft for Healthcare",
        "industry": "Software Development",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-health/"
      },
      {
        "name": "M12, Microsoft's Venture Fund",
        "industry": "Venture Capital and Private Equity Principals",
        "address": "San Francisco, California",
        "linkeinUrl": "https://www.linkedin.com/company/m12vc"
      },
      {
        "name": "Microsoft Viva",
        "industry": "Software Development",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-viva/"
      },
      {
        "name": "Microsoft 365 Insider Program",
        "industry": "Software Development",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-365-insider/"
      },
      {
        "name": "Microsoft Threat Intelligence",
        "industry": "Computer and Network Security",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-threat-intelligence/"
      },
      {
        "name": "Flip",
        "industry": "E-Learning Providers",
        "address": "Minneapolis, MN",
        "linkeinUrl": "https://www.linkedin.com/company/microsoftflip"
      },
      {
        "name": "Microsoft Reactor",
        "industry": "Technology, Information and Internet",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-reactor/"
      },
      {
        "name": "Microsoft Windows",
        "industry": "Software Development",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-windows/"
      },
      {
        "name": "M",
        "industry": "Software Development",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/covid19-business-resource-center/"
      },
      {
        "name": "Metaswitch Networks",
        "industry": "Telecommunications",
        "address": null,
        "linkeinUrl": "https://uk.linkedin.com/company/metaswitch-networks"
      },
      {
        "name": "Microsoft Military Affairs",
        "industry": "Information Technology & Services",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-military-affairs/"
      },
      {
        "name": "Microsoft AI",
        "industry": "Software Development",
        "address": null,
        "linkeinUrl": "https://mx.linkedin.com/showcase/microsoft-ai/"
      },
      {
        "name": "Microsoft for Nonprofits",
        "industry": "Software Development",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-for-nonprofits/"
      },
      {
        "name": "Microsoft Copilot",
        "industry": "Software Development",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoftcopilot/"
      },
      {
        "name": "Microsoft Security Response Center",
        "industry": "Computer and Network Security",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-security-response-center/"
      },
      {
        "name": "Studios Quality - Xbox Game Studios",
        "industry": "Computer Games",
        "address": "Redmond, WA",
        "linkeinUrl": "https://www.linkedin.com/company/studios-quality"
      },
      {
        "name": "Microsoft 365 Developer",
        "industry": "Technology, Information and Internet",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft365dev/"
      },
      {
        "name": "Xbox",
        "industry": "Entertainment Providers",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/xbox/"
      },
      {
        "name": "Microsoft News and Stories",
        "industry": "Technology, Information and Internet",
        "address": "Redmond, Washington",
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-news-and-stories/"
      },
      {
        "name": "Microsoft's Entrepreneurship for Positive Impact",
        "industry": "Software Development",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/entrepreneurshipforpositiveimpact/"
      },
      {
        "name": "Go China Connection",
        "industry": "IT Services and IT Consulting",
        "address": "Beijing, Beijing",
        "linkeinUrl": "https://cn.linkedin.com/showcase/go-china-connection/"
      },
      {
        "name": "Microsoft Developers 365",
        "industry": null,
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/showcase/microsoft-developers-365/"
      }
    ],
    "similarPages": [
      {
        "name": "Google",
        "industry": "Software Development",
        "address": "Mountain View, CA",
        "linkeinUrl": "https://www.linkedin.com/company/google"
      },
      {
        "name": "Amazon",
        "industry": "Software Development",
        "address": "Seattle, WA",
        "linkeinUrl": "https://www.linkedin.com/company/amazon"
      },
      {
        "name": "Apple",
        "industry": "Computers and Electronics Manufacturing",
        "address": "Cupertino, California",
        "linkeinUrl": "https://www.linkedin.com/company/apple"
      },
      {
        "name": "IBM",
        "industry": "IT Services and IT Consulting",
        "address": "Armonk, New York, NY",
        "linkeinUrl": "https://www.linkedin.com/company/ibm"
      },
      {
        "name": "Meta",
        "industry": "Software Development",
        "address": "Menlo Park, CA",
        "linkeinUrl": "https://www.linkedin.com/company/meta"
      },
      {
        "name": "Deloitte",
        "industry": "Business Consulting and Services",
        "address": null,
        "linkeinUrl": "https://www.linkedin.com/company/deloitte"
      },
      {
        "name": "Netflix",
        "industry": "Entertainment Providers",
        "address": "Los Gatos, CA",
        "linkeinUrl": "https://www.linkedin.com/company/netflix"
      },
      {
        "name": "LinkedIn",
        "industry": "Software Development",
        "address": "Sunnyvale, CA",
        "linkeinUrl": "https://www.linkedin.com/company/linkedin"
      },
      {
        "name": "Oracle",
        "industry": "IT Services and IT Consulting",
        "address": "Austin, Texas",
        "linkeinUrl": "https://www.linkedin.com/company/oracle"
      },
      {
        "name": "Accenture",
        "industry": "Business Consulting and Services",
        "address": null,
        "linkeinUrl": "https://ie.linkedin.com/company/accenture"
      }
    ]
  }
]
```

If you have any feature requests or encounter any bugs, please feel free to create an issue. Your feedback is highly appreciated and helps us improve the actor.

