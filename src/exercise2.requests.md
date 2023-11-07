# Запросы

## Запросы, которые отправляются на сервер для получения списка типов товаров в шторке "Каталог"

1. POST  /api/mobile/v1/catalogService/catalog/menu

- URL  
  <https://megamarket.ru/api/mobile/v1/catalogService/catalog/menu>

- Ожидаемый результат  
  Получение типов товаров  

- Заголовки запроса  

POST /api/mobile/v1/catalogService/catalog/menu HTTP/2  
Host: megamarket.ru  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0  
Accept: application/json  
Accept-Language: ru-RU,ru;q=0.8,en-US;q=0.5,en;q=0.3  
Accept-Encoding: gzip, deflate, br  
Referer: https://megamarket.ru/catalog/  
content-type: application/json  
x-requested-with: XMLHttpRequest  
Content-Length: 634  
Origin: https://megamarket.ru  
Connection: keep-alive
Cookie: spid=1693495901940_e202eff0aec75867750e0b2462643699_0c0fjt6c2dj55ii5; adspire_uid=AS.1911801593.1693495907; ssaid=7fe22690-4813-11ee-8c60-bd924d22e9c9; megaCookiesMigrated=true; cfidsw-smm=PleE+IUaUQwRUmE2V3FQ/gfv4jeCqOP3Zt0EX9nlJAyV9fr78xpcAm59xmAq1Uw1JKmifncp345unTS/MkzHDmVBNJ5y3Py7IWc2xD7TQA2aUytOkLEePoaiogLBCzYoY0TondyzNJ94fxrBbg0HJWhl2m3EJlapVpWKBk6o; device_id=8046ed87-4813-11ee-9a27-0242ac110004; sbermegamarket_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; ecom_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; _ga_W49D2LL5S1=GS1.1.1693734624.11.1.1693734631.53.0.0; _ga=GA1.2.50401148.1693495909; isOldUser=true; adtech_uid=0f06fb3c-37d0-4334-8b7f-9ca608d9bf97%3Amegamarket.ru; top100_id=t1.6795753.2083264748.1693495911442; t3_sid_6795753=s1.1842098333.1693730020085.1693734631260.10.39; last_visit=1693719303885%3A%3A1693730103885; tmr_lvid=1d777c5e87bc54ac71f5e84366113e63; tmr_lvidTS=1693495920918; region_info=%7B%22displayName%22%3A%22%D0%9C%D0%BE%D1%81%D0%BA%D0%BE%D0%B2%D1%81%D0%BA%D0%B0%D1%8F%20%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C%22%2C%22kladrId%22%3A%225000000000000%22%2C%22isDeliveryEnabled%22%3Atrue%2C%22geo%22%3A%7B%22lat%22%3A55.755814%2C%22lon%22%3A37.617635%7D%2C%22id%22%3A%2250%22%7D; _gpVisits={"isFirstVisitDomain":true,"idContainer":"10002472"}; adid=169349592227347; _sa=SA1.742d6d39-8ed8-4cb5-b0a7-745058813477.1693495922; _gid=GA1.2.57810654.1693495926; rrpvid=183759657204035; _gcl_au=1.1.1649012851.1693495927; flocktory-uuid=bc805808-1c4b-486b-bac1-9adeb83e4b2e-9; _gp10002472={"hits":51,"vc":1,"ac":1,"a6":1,"a2":1,"a1":1}; __zzatw-smm=MDA0dC0cTHtmcDhhDHEWTT17CT4VHThHKHIzd2UbN1ddHBEkWA4hPwsXXFU+NVQOPHVXLw0uOF4tbx5lUFwmRlVOeiceGH9nFRtQSxgvS18+bX0yUCs5Lmw=jrSjcA==; rcuid=64f0b27b31535728cb1e5f7b; uxs_uid=920a6f80-4813-11ee-8ab4-3da0b4720c09; adrcid=AhaHjBe2yZuGH03fKivSuxQ; cfidsw-smm=PleE+IUaUQwRUmE2V3FQ/gfv4jeCqOP3Zt0EX9nlJAyV9fr78xpcAm59xmAq1Uw1JKmifncp345unTS/MkzHDmVBNJ5y3Py7IWc2xD7TQA2aUytOkLEePoaiogLBCzYoY0TondyzNJ94fxrBbg0HJWhl2m3EJlapVpWKBk6o; tmr_detect=0%7C1693730108483; spsc=1693730021616_293a64d34a6e45d592bdc9558d1daf32_a5476469b72f558bb72e6aae99c6a060; __tld__=null; rrlevt=1693639359031; _ga_QETLGKM757=GS1.1.1693725960.1.1.1693726083.60.0.0; _gat=1  
Sec-Fetch-Dest: empty  
Sec-Fetch-Mode: cors  
Sec-Fetch-Site: same-origin  
TE: trailers  

- Тело запроса

```
{"parentId":"0","depthLevel":3,"auth":{"locationId":"50","appPlatform":"WEB","appVersion":1693462413,"experiments":{"1":"2","8":"2","41":"2","46":"2","53":"2","55":"2","58":"2","68":"1","69":"1","79":"3","85":"2","98":"2","99":"2","107":"1","108":"2","109":"2","119":"2","120":"1","121":"2","122":"1","128":"2","129":"1","132":"2","136":"1","144":"1","148":"1","149":"1","155":"1","170":"3","173":"1","183":"2","187":"3","191":"1","192":"1","201":"3","202":"1","205":"2","5779":"2","20121":"1","67062":"1","67972":"2","69032":"3","70070":"1","72674":"3","81724":"2","85160":"2","86296":"2","86356":"2","90172":"3"},"os":"UNKNOWN_OS"}}
```

- Заголовки ответа

HTTP/2 200 OK  
server: nginx  
date: Sun, 03 Sep 2023 09:50:34 GMT  
content-type: application/json  
access-control-allow-credentials: true  
access-control-allow-headers: Accept, Content-Type, Content-Length, Cookie, Accept-Encoding, X-CSRF-Token, Authorization, Origin, Referer, User-Agent, X-Requested-With  
access-control-allow-methods: POST, GET, OPTIONS, PUT, DELETE  
access-control-allow-origin: https://megamarket.ru  
app-version: mgate:12683  
grpcgateway-content-type: application/grpc  
request-id: 2UsiLifBWcMYKNyAQnqLrFBtNtX  
trace-id: 3702182a2df70b3f  
strict-transport-security: max-age=31536000; includeSubDomains  
x-content-type-options: nosniff  
x-xss-protection: 1; mode=block  
content-encoding: br  
x-sp-crid: 1246422312:8  
X-Firefox-Spdy: h2  

- Тело ответа  

```
{
    "success": true,
    "meta": {
        "time": "2023-09-03T09:50:34Z",
        "traceId": "3702182a2df70b3f",
        "requestId": "2UsiLifBWcMYKNyAQnqLrFBtNtX",
        "appVersion": "mgate:12683"
    },
    "errors": [],
    "nodes": [
        {
            "id": "X12011",
            "title": "Электроника",
            "titleImage": "https://main-cdn.sbermegamarket.ru/mid9/hlr-system/163/510/201/620/1t.png",
            "nodes": [],
            "sequence": 100,
            "subTitle": "475 000 товаров",
            "category": null,
            "collection": {
                "collectionId": "12011",
                "parentId": "0",
                "collectionType": "CATEGORY",
                "title": "Электроника",
                "isDepartment": true,
                "hierarchy": [],
                "url": "/catalog/elektronika/",
                "images": {},
                "description": "",
                "slug": "elektronika",
                "navigationMode": "",
                "allowedServiceSchemes": [],
                "code": "",
                "mainListingCollectionId": "",
                "attributes": null,
                "rating": {},
                "shortTitle": "",
                "mainListingCollectionRelativeUrl": "",
                "name": "",
                "displayName": ""
            },
            "parentId": "0"
        },
        {
            "id": "X502202",
            "title": "Мобильные телефоны и аксессуары",
            "titleImage": "https://main-cdn.sbermegamarket.ru/mid9/hlr-system/189/147/734/111/218/12/2463684633822370t.png",
            "nodes": [],
            "sequence": 1800,
            "subTitle": "",
            "category": null,
            "collection": {
                "collectionId": "502202",
                "parentId": "12011",
                "collectionType": "CATEGORY",
                "title": "Мобильные телефоны и аксессуары",
                "isDepartment": true,
                "hierarchy": [],
                "url": "/catalog/mobilnye-telefony-i-aksessuary/",
                "images": {},
                "description": "",
                "slug": "mobilnye-telefony-i-aksessuary",
                "navigationMode": "",
                "allowedServiceSchemes": [],
                "code": "",
                "mainListingCollectionId": "",
                "attributes": null,
                "rating": {},
                "shortTitle": "",
                "mainListingCollectionRelativeUrl": "",
                "name": "",
                "displayName": ""
            },
            "parentId": "X12011"
        }, 
```

## Запросы, которые отправляются на сервер при использовании поиска товаров в каталоге

1. POST  /api/mobile/v3/catalogService/catalog/searchSuggest

- URL  
  <https://megamarket.ru/api/mobile/v3/catalogService/catalog/searchSuggest>

- Ожидаемый результат  
  
данный запрос отправляется при поиске товара в каталоге  

- Заголовки запроса  

POST /api/mobile/v3/catalogService/catalog/searchSuggest HTTP/2  
Host: megamarket.ru  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0  
Accept: application/json  
Accept-Language: ru-RU,ru;q=0.8,en-US;q=0.5,en;q=0.3  
Accept-Encoding: gzip, deflate, br  
Referer: https://megamarket.ru/  
content-type: application/json  
x-requested-with: XMLHttpRequest  
Content-Length: 664  
Origin: https://megamarket.ru  
Connection: keep-alive  
Cookie: spid=1693495901940_e202eff0aec75867750e0b2462643699_0c0fjt6c2dj55ii5; adspire_uid=AS.1911801593.1693495907; ssaid=7fe22690-4813-11ee-8c60-bd924d22e9c9; megaCookiesMigrated=true; cfidsw-smm=R8Fb+G3dJnYu9XprI7E9D94j2hB5jL85DvvdCZ1q62d/MlMMTPsZwW/GJJnDDAaWXZE4Au2IQ28GAJbglJPoVGlFW4o8wIeQqaB11u03tU3yNgTK3qvGbvM4z2Ge/Dww31djEguYm0NJzh7hzMj/rCT3MPndykywbfsXJDkY; device_id=8046ed87-4813-11ee-9a27-0242ac110004; sbermegamarket_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; ecom_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; _ga_W49D2LL5S1=GS1.1.1693817119.14.1.1693817798.22.0.0; _ga=GA1.1.50401148.1693495909; isOldUser=true; adtech_uid=0f06fb3c-37d0-4334-8b7f-9ca608d9bf97%3Amegamarket.ru; top100_id=t1.6795753.2083264748.1693495911442; t3_sid_6795753=s1.980669749.1693817121655.1693817797552.13.27; last_visit=1693806997562%3A%3A1693817797562; tmr_lvid=1d777c5e87bc54ac71f5e84366113e63; tmr_lvidTS=1693495920918; region_info=%7B%22displayName%22%3A%22%D0%9C%D0%BE%D1%81%D0%BA%D0%BE%D0%B2%D1%81%D0%BA%D0%B0%D1%8F%20%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C%22%2C%22kladrId%22%3A%225000000000000%22%2C%22isDeliveryEnabled%22%3Atrue%2C%22geo%22%3A%7B%22lat%22%3A55.755814%2C%22lon%22%3A37.617635%7D%2C%22id%22%3A%2250%22%7D; _gpVisits={"isFirstVisitDomain":true,"idContainer":"10002472"}; adid=169349592227347; _sa=SA1.742d6d39-8ed8-4cb5-b0a7-745058813477.1693495922; rrpvid=183759657204035; _gcl_au=1.1.1649012851.1693495927; flocktory-uuid=bc805808-1c4b-486b-bac1-9adeb83e4b2e-9; _gp10002472={"utm":"7df3f2b7","hits":5,"vc":1,"ac":1,"a6":1}; __zzatw-smm=MDA0dC0cTHtmcDhhDHEWTT17CT4VHThHKHIzd2UbN1ddHBEkWA4hPwsXXFU+NVQOPHVXLw0uOF4tbx5lUFwnRFxUCi0ZFnpnFRtQSxgvS18+bX0yUCs5Lmw=13RDig==; rcuid=64f0b27b31535728cb1e5f7b; uxs_uid=920a6f80-4813-11ee-8ab4-3da0b4720c09; adrcid=AhaHjBe2yZuGH03fKivSuxQ; cfidsw-smm=R8Fb+G3dJnYu9XprI7E9D94j2hB5jL85DvvdCZ1q62d/MlMMTPsZwW/GJJnDDAaWXZE4Au2IQ28GAJbglJPoVGlFW4o8wIeQqaB11u03tU3yNgTK3qvGbvM4z2Ge/Dww31djEguYm0NJzh7hzMj/rCT3MPndykywbfsXJDkY; tmr_detect=0%7C1693817778587; rrlevt=1693639359031; _ga_QETLGKM757=GS1.1.1693725960.1.1.1693726083.60.0.0; spsc=1693817121623_b7770206f74f81f949c7a92ab758273a_a5476469b72f558bb72e6aae99c6a060; __tld__=null; _gid=GA1.2.1071491218.1693817687; _gat=1  
Sec-Fetch-Dest: empty  
Sec-Fetch-Mode: cors  
Sec-Fetch-Site: same-origin  
TE: trailers  

- Тело запроса  

```
{"searchText":"","searchRequestVersion":10,"ageMore18":false,"auth":{"locationId":"50","appPlatform":"WEB","appVersion":1693462413,"experiments":{"1":"2","8":"2","41":"2","46":"2","53":"2","55":"2","58":"2","68":"1","69":"1","79":"3","85":"2","98":"2","99":"2","107":"1","108":"2","109":"2","119":"2","120":"1","121":"2","122":"1","128":"2","129":"1","132":"2","136":"1","144":"1","148":"1","149":"1","155":"1","170":"3","173":"1","183":"2","187":"3","191":"1","192":"1","201":"3","202":"1","205":"2","5779":"2","20121":"1","67062":"1","67972":"2","69032":"3","70070":"1","72674":"3","81724":"2","85160":"2","86296":"2","86356":"2","90172":"3"},"os":"UNKNOWN_OS"}}  
```

- Заголовки ответа

HTTP/2 200 OK  
server: nginx  
date: Mon, 04 Sep 2023 08:56:42 GMT  
content-type: application/json  
access-control-allow-credentials: true  
access-control-allow-headers: Accept, Content-Type, Content-Length, Cookie, Accept-Encoding, X-CSRF-Token, Authorization, Origin, Referer, User-Agent, X-Requested-With  
access-control-allow-methods: POST, GET, OPTIONS, PUT, DELETE  
access-control-allow-origin: https://megamarket.ru  
app-version: mgate:12763  
grpcgateway-content-type: application/grpc  
request-id: 2UvQvHsSzcuL7qYumy5JlihaDHF  
trace-id: 0c0624b2cd31998d  
strict-transport-security: max-age=31536000; includeSubDomains  
x-content-type-options: nosniff  
x-xss-protection: 1; mode=block  
content-encoding: br  
x-sp-crid: 357147910:61  
X-Firefox-Spdy: h2  

- Тело ответа  

```
{"success":true,"meta":{"time":"2023-09-04T08:56:42Z","traceId":"0c0624b2cd31998d","requestId":"2UvQvHsSzcuL7qYumy5JlihaDHF","appVersion":"mgate:12763"},"errors":[],"suggests":[{"type":"FREQUENT_QUERY","typeDisplayText":"Часто ищут","text":"Московский картофель","searchParams":[{"suggestQueryType":"BRAND_ZONE","queryPayload":"moskovskiy-kartofel","suggestType":"BRAND_ZONE"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}},{"type":"FREQUENT_QUERY","typeDisplayText":"Часто ищут","text":"Сахар","searchParams":[{"suggestQueryType":"CATEGORY","queryPayload":"15748","suggestType":"CATEGORY_0"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}},{"type":"FREQUENT_QUERY","typeDisplayText":"Часто ищут","text":"Сыр","searchParams":[{"suggestQueryType":"PROMPT","queryPayload":"сыр","suggestType":"CONSTRUCTOR"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}},{"type":"FREQUENT_QUERY","typeDisplayText":"Часто ищут","text":"Молоко","searchParams":[{"suggestQueryType":"CATEGORY","queryPayload":"16488","suggestType":"CATEGORY_0"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}},{"type":"FREQUENT_QUERY","typeDisplayText":"Часто ищут","text":"Кофе","searchParams":[{"suggestQueryType":"CATEGORY","queryPayload":"12123","suggestType":"CATEGORY_0"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}}]}
```

2. POST  /api/mobile/v3/catalogService/catalog/searchSuggest

- URL  
  <https://megamarket.ru/api/mobile/v3/catalogService/catalog/searchSuggest>

- Ожидаемый результат  
  
данный запрос отправляется при поиске товара в каталоге (например: "посуда")

- Заголовки запроса  

POST /api/mobile/v3/catalogService/catalog/searchSuggest HTTP/2  
Host: megamarket.ru  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0  
Accept: application/json  
Accept-Language: ru-RU,ru;q=0.8,en-US;q=0.5,en;q=0.3  
Accept-Encoding: gzip, deflate, br  
Referer: https://megamarket.ru/  
content-type: application/json  
x-requested-with: XMLHttpRequest  
Content-Length: 676  
Origin: https://megamarket.ru  
Connection: keep-alive  
Cookie: spid=1693495901940_e202eff0aec75867750e0b2462643699_0c0fjt6c2dj55ii5; adspire_uid=AS.1911801593.1693495907; ssaid=7fe22690-4813-11ee-8c60-bd924d22e9c9; megaCookiesMigrated=true; cfidsw-smm=CotBnfYXXk5+pt7h9dI6sW85onPlOWSg4WDW0c+228b8udJiNwADJrcqAclxm7QjfQoo90Uxdh9lMyy/VxZi2xLXg1lX9slCXW4NFVUUwUXlRHMAfg6WoVW2rj99ZDcWwU8ZW4ZwCutFD7L1WSwRYHf6apPCXOpGhjC1hu+i; device_id=8046ed87-4813-11ee-9a27-0242ac110004; sbermegamarket_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; ecom_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; _ga_W49D2LL5S1=GS1.1.1693817119.14.1.1693819471.50.0.0; _ga=GA1.2.50401148.1693495909; isOldUser=true; adtech_uid=0f06fb3c-37d0-4334-8b7f-9ca608d9bf97%3Amegamarket.ru; top100_id=t1.6795753.2083264748.1693495911442; t3_sid_6795753=s1.980669749.1693817121655.1693819471902.13.77; last_visit=1693808666898%3A%3A1693819466898; tmr_lvid=1d777c5e87bc54ac71f5e84366113e63; tmr_lvidTS=1693495920918; region_info=%7B%22displayName%22%3A%22%D0%A1%D0%90%D0%9D%D0%9A%D0%A2-%D0%9F%D0%95%D0%A2%D0%95%D0%A0%D0%91%D0%A3%D0%A0%D0%93%22%2C%22kladrId%22%3A%227800000000000%22%2C%22isDeliveryEnabled%22%3Atrue%2C%22geo%22%3A%7B%22lat%22%3A59.939095%2C%22lon%22%3A30.315868%7D%2C%22id%22%3A%2278%22%7D; _gpVisits={"isFirstVisitDomain":true,"idContainer":"10002472"}; adid=169349592227347; _sa=SA1.742d6d39-8ed8-4cb5-b0a7-745058813477.1693495922; rrpvid=183759657204035; _gcl_au=1.1.1649012851.1693495927; flocktory-uuid=bc805808-1c4b-486b-bac1-9adeb83e4b2e-9; _gp10002472={"utm":"7df3f2b7","hits":8,"vc":1,"ac":1,"a6":1}; __zzatw-smm=MDA0dC0cTHtmcDhhDHEWTT17CT4VHThHKHIzd2UbN1ddHBEkWA4hPwsXXFU+NVQOPHVXLw0uOF4tbx5lUFwnRF5RfywaGXhnFRtQSxgvS18+bX0yUCs5Lmw=Vl7W/w==; rcuid=64f0b27b31535728cb1e5f7b; uxs_uid=920a6f80-4813-11ee-8ab4-3da0b4720c09; adrcid=AhaHjBe2yZuGH03fKivSuxQ; cfidsw-smm=CotBnfYXXk5+pt7h9dI6sW85onPlOWSg4WDW0c+228b8udJiNwADJrcqAclxm7QjfQoo90Uxdh9lMyy/VxZi2xLXg1lX9slCXW4NFVUUwUXlRHMAfg6WoVW2rj99ZDcWwU8ZW4ZwCutFD7L1WSwRYHf6apPCXOpGhjC1hu+i; tmr_detect=0%7C1693819473821; rrlevt=1693639359031; _ga_QETLGKM757=GS1.1.1693725960.1.1.1693726083.60.0.0; spsc=1693817121623_b7770206f74f81f949c7a92ab758273a_a5476469b72f558bb72e6aae99c6a060; __tld__=null; _gid=GA1.2.1071491218.1693817687; _gat=1  
Sec-Fetch-Dest: empty  
Sec-Fetch-Mode: cors  
Sec-Fetch-Site: same-origin  
TE: trailers  

- Тело запроса  

```
{"searchText":"посуда","searchRequestVersion":10,"ageMore18":false,"auth":{"locationId":"78","appPlatform":"WEB","appVersion":1693492133,"experiments":{"1":"2","8":"2","41":"2","46":"2","53":"2","55":"2","58":"2","68":"1","69":"1","79":"3","85":"2","98":"2","99":"2","107":"1","108":"2","109":"2","119":"2","120":"1","121":"2","122":"1","128":"2","129":"1","132":"2","136":"1","144":"1","148":"1","149":"1","155":"1","170":"3","173":"1","183":"2","187":"3","191":"1","192":"1","201":"3","202":"1","205":"2","5779":"2","20121":"1","67062":"1","67972":"2","69032":"3","70070":"1","72674":"3","81724":"2","85160":"2","86296":"2","86356":"2","90172":"3"},"os":"UNKNOWN_OS"}} 
```

- Заголовки ответа

HTTP/2 200 OK  
server: nginx  
date: Mon, 04 Sep 2023 09:24:41 GMT  
content-type: application/json  
access-control-allow-credentials: true  
access-control-allow-headers: Accept, Content-Type, Content-Length, Cookie, Accept-Encoding, X-CSRF-Token, Authorization, Origin, Referer, User-Agent, X-Requested-With  
access-control-allow-methods: POST, GET, OPTIONS, PUT, DELETE  
access-control-allow-origin: https://megamarket.ru  
app-version: mgate:12763  
grpcgateway-content-type: application/grpc  
request-id: 2UvUK954tptEVBSF09wZlNRTPjX  
trace-id: 54ae51ba2dd1b5ee  
strict-transport-security: max-age=31536000; includeSubDomains  
x-content-type-options: nosniff  
x-xss-protection: 1; mode=block  
content-encoding: br  
x-sp-crid: 1378929612:30  
X-Firefox-Spdy: h2  

- Тело ответа  

```
{"success":true,"meta":{"time":"2023-09-04T09:24:41Z","traceId":"54ae51ba2dd1b5ee","requestId":"2UvUK954tptEVBSF09wZlNRTPjX","appVersion":"mgate:12763"},"errors":[],"suggests":[{"type":"CATEGORY","typeDisplayText":"Бытовая техника / Крупная техника для кухни","text":"Посудомоечные машины","searchParams":[{"suggestQueryType":"CATEGORY","queryPayload":"12044","suggestType":"CATEGORY_0"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":{"isDepartment":false}}},{"type":"CATEGORY","typeDisplayText":"Бытовая техника / Встраиваемая техника","text":"Встраиваемые посудомоечные машины","searchParams":[{"suggestQueryType":"CATEGORY","queryPayload":"12112","suggestType":"CATEGORY_0"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":{"isDepartment":false}}},{"type":"BRAND","typeDisplayText":"Товары для дома / Посуда","text":"Посуда to go CoolPodarok","searchParams":[{"suggestQueryType":"CATEGORY","queryPayload":"6374339","suggestType":"CATEGORY_0_BRAND"},{"suggestQueryType":"BRAND","queryPayload":"CoolPodarok","suggestType":"CATEGORY_0_BRAND"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}},{"type":"BRAND","typeDisplayText":"Товары для дома / Посуда","text":"Столовая посуда Lefard","searchParams":[{"suggestQueryType":"CATEGORY","queryPayload":"13801","suggestType":"CATEGORY_0_BRAND"},{"suggestQueryType":"BRAND","queryPayload":"Lefard","suggestType":"CATEGORY_0_BRAND"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}},{"type":"CATEGORY_POPULAR_TAG","typeDisplayText":"Бытовая техника / Крупная техника для кухни","text":"Посудомоечные машины напольные","searchParams":[{"suggestQueryType":"TAG","queryPayload":"858267","suggestType":"CATEGORY_0_POPULAR_TAG"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}},{"type":"BRAND_ZONE","typeDisplayText":"Бренд","text":"Камская посуда","searchParams":[{"suggestQueryType":"BRAND_ZONE","queryPayload":"kamskaya-posuda","suggestType":"BRAND_ZONE"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}},{"type":"BRAND_ZONE","typeDisplayText":"Бренд","text":"ВСМПО-Посуда","searchParams":[{"suggestQueryType":"BRAND_ZONE","queryPayload":"vsmpo-posuda","suggestType":"BRAND_ZONE"}],"additionalInfo":{"brandZone":null,"popularItem":null,"category":null}},{"type":"CATEGORY_POPULAR_ITEM","typeDisplayText":"","text":"Встраиваемая посудомоечная машина Leran BDW 45-108","searchParams":[{"suggestQueryType":"ITEM","queryPayload":"100026476723","suggestType":"CATEGORY_0_POPULAR_ITEM"}],"additionalInfo":{"brandZone":null,"popularItem":{"itemPrice":29990,"bonusAmount":11996,"itemImageUrl":"https://main-cdn.sbermegamarket.ru/mid4/hlr-system/59/48/67/31/84/22/100026476723b0.jpg","bonusPercent":40},"category":null}},{"type":"CATEGORY_POPULAR_ITEM","typeDisplayText":"","text":"Посудомоечная машина HYUNDAI DT503 Silver","searchParams":[{"suggestQueryType":"ITEM","queryPayload":"600005533562","suggestType":"CATEGORY_0_POPULAR_ITEM"}],"additionalInfo":{"brandZone":null,"popularItem":{"itemPrice":21370,"bonusAmount":0,"itemImageUrl":"https://main-cdn.sbermegamarket.ru/mid4/hlr-system/-16/272/650/151/202/044/600005533562b0.jpeg","bonusPercent":0},"category":null}},{"type":"CATEGORY_POPULAR_ITEM","typeDisplayText":"","text":"Встраиваемая посудомоечная машина Beko BDIS38120Q","searchParams":[{"suggestQueryType":"ITEM","queryPayload":"100032293587","suggestType":"CATEGORY_0_POPULAR_ITEM"}],"additionalInfo":{"brandZone":null,"popularItem":{"itemPrice":33592,"bonusAmount":13437,"itemImageUrl":"https://main-cdn.sbermegamarket.ru/mid4/hlr-system/153/503/915/671/019/55/100032293587b0.jpg","bonusPercent":40},"category":null}}]}
```

3. POST  /api/mobile/v1/catalogService/catalog/search

- URL  
  <https://megamarket.ru/api/mobile/v1/catalogService/catalog/search>

- Ожидаемый результат  
  
данный запрос отправляется при поиске товара в каталоге (например: "посуда")

- Заголовки запроса  

POST /api/mobile/v1/catalogService/catalog/search HTTP/2  
Host: megamarket.ru  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0  
Accept: application/json  
Accept-Language: ru-RU,ru;q=0.8,en-US;q=0.5,en;q=0.3  
Accept-Encoding: gzip, deflate, br  
Referer: https://megamarket.ru/catalog/?q=%D0%BF%D0%BE%D1%81%D1%83%D0%B4%D0%B0  
content-type: application/json  
x-requested-with: XMLHttpRequest  
Content-Length: 923  
Origin: https://megamarket.ru  
Connection: keep-alive  
Cookie: spid=1693495901940_e202eff0aec75867750e0b2462643699_0c0fjt6c2dj55ii5; adspire_uid=AS.1911801593.1693495907; ssaid=7fe22690-4813-11ee-8c60-bd924d22e9c9; megaCookiesMigrated=true; cfidsw-smm=CotBnfYXXk5+pt7h9dI6sW85onPlOWSg4WDW0c+228b8udJiNwADJrcqAclxm7QjfQoo90Uxdh9lMyy/VxZi2xLXg1lX9slCXW4NFVUUwUXlRHMAfg6WoVW2rj99ZDcWwU8ZW4ZwCutFD7L1WSwRYHf6apPCXOpGhjC1hu+i; device_id=8046ed87-4813-11ee-9a27-0242ac110004; sbermegamarket_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; ecom_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; _ga_W49D2LL5S1=GS1.1.1693817119.14.1.1693819471.50.0.0; _ga=GA1.2.50401148.1693495909; isOldUser=true; adtech_uid=0f06fb3c-37d0-4334-8b7f-9ca608d9bf97%3Amegamarket.ru; top100_id=t1.6795753.2083264748.1693495911442; t3_sid_6795753=s1.980669749.1693817121655.1693819482636.13.79; last_visit=1693808666898%3A%3A1693819466898; tmr_lvid=1d777c5e87bc54ac71f5e84366113e63; tmr_lvidTS=1693495920918; region_info=%7B%22displayName%22%3A%22%D0%A1%D0%90%D0%9D%D0%9A%D0%A2-%D0%9F%D0%95%D0%A2%D0%95%D0%A0%D0%91%D0%A3%D0%A0%D0%93%22%2C%22kladrId%22%3A%227800000000000%22%2C%22isDeliveryEnabled%22%3Atrue%2C%22geo%22%3A%7B%22lat%22%3A59.939095%2C%22lon%22%3A30.315868%7D%2C%22id%22%3A%2278%22%7D; _gpVisits={"isFirstVisitDomain":true,"idContainer":"10002472"}; adid=169349592227347; _sa=SA1.742d6d39-8ed8-4cb5-b0a7-745058813477.1693495922; rrpvid=183759657204035; _gcl_au=1.1.1649012851.1693495927; flocktory-uuid=bc805808-1c4b-486b-bac1-9adeb83e4b2e-9; _gp10002472={"utm":"7df3f2b7","hits":8,"vc":1,"ac":1,"a6":1}; __zzatw-smm=MDA0dC0cTHtmcDhhDHEWTT17CT4VHThHKHIzd2UbN1ddHBEkWA4hPwsXXFU+NVQOPHVXLw0uOF4tbx5lUFwnRF5RfywaGXhnFRtQSxgvS18+bX0yUCs5Lmw=Vl7W/w==; rcuid=64f0b27b31535728cb1e5f7b; uxs_uid=920a6f80-4813-11ee-8ab4-3da0b4720c09; adrcid=AhaHjBe2yZuGH03fKivSuxQ; cfidsw-smm=CotBnfYXXk5+pt7h9dI6sW85onPlOWSg4WDW0c+228b8udJiNwADJrcqAclxm7QjfQoo90Uxdh9lMyy/VxZi2xLXg1lX9slCXW4NFVUUwUXlRHMAfg6WoVW2rj99ZDcWwU8ZW4ZwCutFD7L1WSwRYHf6apPCXOpGhjC1hu+i; tmr_detect=0%7C1693819473821; rrlevt=1693639359031; _ga_QETLGKM757=GS1.1.1693725960.1.1.1693726083.60.0.0; spsc=1693817121623_b7770206f74f81f949c7a92ab758273a_a5476469b72f558bb72e6aae99c6a060; __tld__=null; _gid=GA1.2.1071491218.1693817687; _gat=1  
Sec-Fetch-Dest: empty  
Sec-Fetch-Mode: cors  
Sec-Fetch-Site: same-origin  
TE: trailers  

- Тело запроса  

```
{"requestVersion":10,"limit":42,"offset":0,"collectionId":"","selectedAssumedCollectionId":"","isMultiCategorySearch":false,"searchByOriginalQuery":false,"selectedSuggestParams":[],"expandedFiltersIds":["2B0B1FF4756D49CF84B094522D57ED3D"],"sorting":0,"ageMore18":null,"showNotAvailable":true,"searchText":"посуда","auth":{"locationId":"78","appPlatform":"WEB","appVersion":1693492133,"experiments":{"1":"2","8":"2","41":"2","46":"2","53":"2","55":"2","58":"2","68":"1","69":"1","79":"3","85":"2","98":"2","99":"2","107":"1","108":"2","109":"2","119":"2","120":"1","121":"2","122":"1","128":"2","129":"1","132":"2","136":"1","144":"1","148":"1","149":"1","155":"1","170":"3","173":"1","183":"2","187":"3","191":"1","192":"1","201":"3","202":"1","205":"2","5779":"2","20121":"1","67062":"1","67972":"2","69032":"3","70070":"1","72674":"3","81724":"2","85160":"2","86296":"2","86356":"2","90172":"3"},"os":"UNKNOWN_OS"}}
```

- Заголовки ответа

HTTP/2 200 OK  
server: nginx  
date: Mon, 04 Sep 2023 09:24:45 GMT  
content-type: application/json  
access-control-allow-credentials: true  
access-control-allow-headers: Accept, Content-Type, Content-Length, Cookie, Accept-Encoding, X-CSRF-Token, Authorization, Origin, Referer, User-Agent, X-Requested-With  
access-control-allow-methods: POST, GET, OPTIONS, PUT, DELETE  
access-control-allow-origin: https://megamarket.ru  
app-version: mgate:12763  
grpcgateway-content-type: application/grpc  
request-id: 2UvUKTZOQ1xtnfJCd1Vf0VllHs3  
trace-id: 33368b5c88a6d0a3  
strict-transport-security: max-age=31536000; includeSubDomains  
x-content-type-options: nosniff  
x-xss-protection: 1; mode=block  
content-encoding: br  
x-sp-crid: 1378929612:31  
X-Firefox-Spdy: h2  

- Тело ответа  

```
{"success":true,"meta":{"time":"2023-09-04T09:24:45Z","traceId":"33368b5c88a6d0a3","requestId":"2UvUKTZOQ1xtnfJCd1Vf0VllHs3","appVersion":"mgate:12763"},"errors":[],"total":"0","offset":"0","limit":"0","items":[],"tags":[],"categories":[],"merchantIds":[],"priceRange":null,"filters":[],"selectedFilterCount":0,"collectionSelector":{"collections":[]},"processor":{"type":"MENU_NODE","goodsId":"","collectionId":"13626","menuNodeId":"X13626","merchantId":"","merchantSlug":"","url":"/catalog/posuda-801/#?related_search=%D0%BF%D0%BE%D1%81%D1%83%D0%B4%D0%B0","brandSlug":"","merchantLogoUrl":"","menuNodeTitle":"Посуда"},"hasPlus18":false,"navigation":null,"flags":[],"keywords":["посуда"],"view":"DEFAULT_VIEW","allowedServiceSchemes":[],"sorting":[],"listingSize":44,"assumedCollection":null,"alternativeAssumedCollections":[],"queryChangesInfo":null,"searchTextContext":"eyJxdWVyeSI6ItC_0L7RgdGD0LTQsCIsImNvbmNlcHRzIjp7ImNvbmNlcHRGaWx0ZXJzIjpbeyJrZXkiOiJjYXRlZ29yeSIsInZhbHVlIjoiMTM2MjYifV0sImVzRHVyYXRpb25NcyI6MjcsImNhdGVnb3J5RnVsbE1hdGNoIjp0cnVlLCJicmFuZEZ1bGxNYXRjaCI6ZmFsc2UsInR5cGUiOiJDQVRFR09SWSIsImNhdGVnb3J5RGV0ZWN0aW9uTW9kZWwiOiJDT05URU5UIn0sInNlYXJjaEV2ZXJ5d2hlcmVBcHBsaWVkIjpmYWxzZX0=","goodsURL":"https://megamarket.ru/catalog/?q=%D0%BF%D0%BE%D1%81%D1%83%D0%B4%D0%B0#?related_search=%2Fcatalog%2Fposuda-801%2F%23%3Frelated_search%3D%25D0%25BF%25D0%25BE%25D1%2581%25D1%2583%25D0%25B4%25D0%25B0","version":""}
```

4. POST  /api/mobile/v1/catalogService/filters/search

- URL  
  <https://megamarket.ru/api/mobile/v1/catalogService/filters/search>

- Ожидаемый результат  
  
данный запрос отправляется при поиске товара в каталоге (например: "посуда")

- Заголовки запроса  

POST /api/mobile/v1/catalogService/filters/search HTTP/2  
Host: megamarket.ru  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0  
Accept: application/json  
Accept-Language: ru-RU,ru;q=0.8,en-US;q=0.5,en;q=0.3  
Accept-Encoding: gzip, deflate, br  
Referer: https://megamarket.ru/catalog/?q=%D0%BF%D0%BE%D1%81%D1%83%D0%B4%D0%B0  
content-type: application/json  
x-requested-with: XMLHttpRequest  
Content-Length: 922  
Origin: https://megamarket.ru  
Connection: keep-alive  
Cookie: spid=1693495901940_e202eff0aec75867750e0b2462643699_0c0fjt6c2dj55ii5; adspire_uid=AS.1911801593.1693495907; ssaid=7fe22690-4813-11ee-8c60-bd924d22e9c9; megaCookiesMigrated=true; cfidsw-smm=CotBnfYXXk5+pt7h9dI6sW85onPlOWSg4WDW0c+228b8udJiNwADJrcqAclxm7QjfQoo90Uxdh9lMyy/VxZi2xLXg1lX9slCXW4NFVUUwUXlRHMAfg6WoVW2rj99ZDcWwU8ZW4ZwCutFD7L1WSwRYHf6apPCXOpGhjC1hu+i; device_id=8046ed87-4813-11ee-9a27-0242ac110004; sbermegamarket_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; ecom_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; _ga_W49D2LL5S1=GS1.1.1693817119.14.1.1693819471.50.0.0; _ga=GA1.2.50401148.1693495909; isOldUser=true; adtech_uid=0f06fb3c-37d0-4334-8b7f-9ca608d9bf97%3Amegamarket.ru; top100_id=t1.6795753.2083264748.1693495911442; t3_sid_6795753=s1.980669749.1693817121655.1693819482636.13.79; last_visit=1693808666898%3A%3A1693819466898; tmr_lvid=1d777c5e87bc54ac71f5e84366113e63; tmr_lvidTS=1693495920918; region_info=%7B%22displayName%22%3A%22%D0%A1%D0%90%D0%9D%D0%9A%D0%A2-%D0%9F%D0%95%D0%A2%D0%95%D0%A0%D0%91%D0%A3%D0%A0%D0%93%22%2C%22kladrId%22%3A%227800000000000%22%2C%22isDeliveryEnabled%22%3Atrue%2C%22geo%22%3A%7B%22lat%22%3A59.939095%2C%22lon%22%3A30.315868%7D%2C%22id%22%3A%2278%22%7D; _gpVisits={"isFirstVisitDomain":true,"idContainer":"10002472"}; adid=169349592227347; _sa=SA1.742d6d39-8ed8-4cb5-b0a7-745058813477.1693495922; rrpvid=183759657204035; _gcl_au=1.1.1649012851.1693495927; flocktory-uuid=bc805808-1c4b-486b-bac1-9adeb83e4b2e-9; _gp10002472={"utm":"7df3f2b7","hits":8,"vc":1,"ac":1,"a6":1}; __zzatw-smm=MDA0dC0cTHtmcDhhDHEWTT17CT4VHThHKHIzd2UbN1ddHBEkWA4hPwsXXFU+NVQOPHVXLw0uOF4tbx5lUFwnRF5RfywaGXhnFRtQSxgvS18+bX0yUCs5Lmw=Vl7W/w==; rcuid=64f0b27b31535728cb1e5f7b; uxs_uid=920a6f80-4813-11ee-8ab4-3da0b4720c09; adrcid=AhaHjBe2yZuGH03fKivSuxQ; cfidsw-smm=CotBnfYXXk5+pt7h9dI6sW85onPlOWSg4WDW0c+228b8udJiNwADJrcqAclxm7QjfQoo90Uxdh9lMyy/VxZi2xLXg1lX9slCXW4NFVUUwUXlRHMAfg6WoVW2rj99ZDcWwU8ZW4ZwCutFD7L1WSwRYHf6apPCXOpGhjC1hu+i; tmr_detect=0%7C1693819473821; rrlevt=1693639359031; _ga_QETLGKM757=GS1.1.1693725960.1.1.1693726083.60.0.0; spsc=1693817121623_b7770206f74f81f949c7a92ab758273a_a5476469b72f558bb72e6aae99c6a060; __tld__=null; _gid=GA1.2.1071491218.1693817687; _gat=1  
Sec-Fetch-Dest: empty  
Sec-Fetch-Mode: cors  
Sec-Fetch-Site: same-origin  
TE: trailers  

- Тело запроса  

```
{"requestVersion":9,"limit":42,"offset":0,"collectionId":"","selectedAssumedCollectionId":"","isMultiCategorySearch":false,"searchByOriginalQuery":false,"selectedSuggestParams":[],"expandedFiltersIds":["2B0B1FF4756D49CF84B094522D57ED3D"],"sorting":0,"ageMore18":null,"showNotAvailable":true,"searchText":"посуда","auth":{"locationId":"78","appPlatform":"WEB","appVersion":1693492133,"experiments":{"1":"2","8":"2","41":"2","46":"2","53":"2","55":"2","58":"2","68":"1","69":"1","79":"3","85":"2","98":"2","99":"2","107":"1","108":"2","109":"2","119":"2","120":"1","121":"2","122":"1","128":"2","129":"1","132":"2","136":"1","144":"1","148":"1","149":"1","155":"1","170":"3","173":"1","183":"2","187":"3","191":"1","192":"1","201":"3","202":"1","205":"2","5779":"2","20121":"1","67062":"1","67972":"2","69032":"3","70070":"1","72674":"3","81724":"2","85160":"2","86296":"2","86356":"2","90172":"3"},"os":"UNKNOWN_OS"}}
```

- Заголовки ответа

HTTP/2 200 OK  
server: nginx  
date: Mon, 04 Sep 2023 09:24:44 GMT  
content-type: application/json  
vary: Accept-Encoding  
access-control-allow-credentials: true  
access-control-allow-headers: Accept, Content-Type, Content-Length, Cookie, Accept-Encoding, X-CSRF-Token, Authorization, Origin, Referer, User-Agent, X-Requested-With  
access-control-allow-methods: POST, GET, OPTIONS, PUT, DELETE  
access-control-allow-origin: https://megamarket.ru  
app-version: mgate:12763  
grpcgateway-content-type: application/grpc  
request-id: 2UvUKeCHoDYWT0CtDRDKZPl12tY  
trace-id: 7e9f4eb17bae5447  
strict-transport-security: max-age=31536000; includeSubDomains  
x-content-type-options: nosniff  
x-xss-protection: 1; mode=block  
x-sp-crid: 1378929612:32  
content-encoding: gzip  
X-Firefox-Spdy: h2  

- Тело ответа  

```
{"success":true,"meta":{"time":"2023-09-04T09:24:44Z","traceId":"7e9f4eb17bae5447","requestId":"2UvUKeCHoDYWT0CtDRDKZPl12tY","appVersion":"mgate:12763"},"errors":[],"filters":[],"selectedFilterCount":0,"totalItemsFound":"0","searchTextContext":""}
```

5. POST  /api/mobile/v1/seoService/seo/search

- URL  
  <https://megamarket.ru/api/mobile/v1/seoService/seo/search>

- Ожидаемый результат  
  
данный запрос отправляется при поиске товара в каталоге (например: "посуда")

- Заголовки запроса  

POST /api/mobile/v1/seoService/seo/search HTTP/2  
Host: megamarket.ru  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0  
Accept: application/json  
Accept-Language: ru-RU,ru;q=0.8,en-US;q=0.5,en;q=0.3  
Accept-Encoding: gzip, deflate, br  
Referer: https://megamarket.ru/catalog/?q=%D0%BF%D0%BE%D1%81%D1%83%D0%B4%D0%B0  
content-type: application/json  
x-requested-with: XMLHttpRequest  
Content-Length: 633  
Origin: https://megamarket.ru  
Connection: keep-alive  
Cookie: spid=1693495901940_e202eff0aec75867750e0b2462643699_0c0fjt6c2dj55ii5; adspire_uid=AS.1911801593.1693495907; ssaid=7fe22690-4813-11ee-8c60-bd924d22e9c9; megaCookiesMigrated=true; cfidsw-smm=CotBnfYXXk5+pt7h9dI6sW85onPlOWSg4WDW0c+228b8udJiNwADJrcqAclxm7QjfQoo90Uxdh9lMyy/VxZi2xLXg1lX9slCXW4NFVUUwUXlRHMAfg6WoVW2rj99ZDcWwU8ZW4ZwCutFD7L1WSwRYHf6apPCXOpGhjC1hu+i; device_id=8046ed87-4813-11ee-9a27-0242ac110004; sbermegamarket_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; ecom_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; _ga_W49D2LL5S1=GS1.1.1693817119.14.1.1693819482.39.0.0; _ga=GA1.2.50401148.1693495909; isOldUser=true; adtech_uid=0f06fb3c-37d0-4334-8b7f-9ca608d9bf97%3Amegamarket.ru; top100_id=t1.6795753.2083264748.1693495911442; t3_sid_6795753=s1.980669749.1693817121655.1693819482636.13.79; last_visit=1693808666898%3A%3A1693819466898; tmr_lvid=1d777c5e87bc54ac71f5e84366113e63; tmr_lvidTS=1693495920918; region_info=%7B%22displayName%22%3A%22%D0%A1%D0%90%D0%9D%D0%9A%D0%A2-%D0%9F%D0%95%D0%A2%D0%95%D0%A0%D0%91%D0%A3%D0%A0%D0%93%22%2C%22kladrId%22%3A%227800000000000%22%2C%22isDeliveryEnabled%22%3Atrue%2C%22geo%22%3A%7B%22lat%22%3A59.939095%2C%22lon%22%3A30.315868%7D%2C%22id%22%3A%2278%22%7D; _gpVisits={"isFirstVisitDomain":true,"idContainer":"10002472"}; adid=169349592227347; _sa=SA1.742d6d39-8ed8-4cb5-b0a7-745058813477.1693495922; rrpvid=183759657204035; _gcl_au=1.1.1649012851.1693495927; flocktory-uuid=bc805808-1c4b-486b-bac1-9adeb83e4b2e-9; _gp10002472={"utm":"7df3f2b7","hits":8,"vc":1,"ac":1,"a6":1}; __zzatw-smm=MDA0dC0cTHtmcDhhDHEWTT17CT4VHThHKHIzd2UbN1ddHBEkWA4hPwsXXFU+NVQOPHVXLw0uOF4tbx5lUFwnRF5RfywaGXhnFRtQSxgvS18+bX0yUCs5Lmw=Vl7W/w==; rcuid=64f0b27b31535728cb1e5f7b; uxs_uid=920a6f80-4813-11ee-8ab4-3da0b4720c09; adrcid=AhaHjBe2yZuGH03fKivSuxQ; cfidsw-smm=CotBnfYXXk5+pt7h9dI6sW85onPlOWSg4WDW0c+228b8udJiNwADJrcqAclxm7QjfQoo90Uxdh9lMyy/VxZi2xLXg1lX9slCXW4NFVUUwUXlRHMAfg6WoVW2rj99ZDcWwU8ZW4ZwCutFD7L1WSwRYHf6apPCXOpGhjC1hu+i; tmr_detect=0%7C1693819473821; rrlevt=1693639359031; _ga_QETLGKM757=GS1.1.1693725960.1.1.1693726083.60.0.0; spsc=1693817121623_b7770206f74f81f949c7a92ab758273a_a5476469b72f558bb72e6aae99c6a060; __tld__=null; _gid=GA1.2.1071491218.1693817687; _gat=1
Sec-Fetch-Dest: empty  
Sec-Fetch-Mode: cors  
Sec-Fetch-Site: same-origin  
TE: trailers   

- Тело запроса  

```
{"searchQuery":"посуда","auth":{"locationId":"78","appPlatform":"WEB","appVersion":1693492133,"experiments":{"1":"2","8":"2","41":"2","46":"2","53":"2","55":"2","58":"2","68":"1","69":"1","79":"3","85":"2","98":"2","99":"2","107":"1","108":"2","109":"2","119":"2","120":"1","121":"2","122":"1","128":"2","129":"1","132":"2","136":"1","144":"1","148":"1","149":"1","155":"1","170":"3","173":"1","183":"2","187":"3","191":"1","192":"1","201":"3","202":"1","205":"2","5779":"2","20121":"1","67062":"1","67972":"2","69032":"3","70070":"1","72674":"3","81724":"2","85160":"2","86296":"2","86356":"2","90172":"3"},"os":"UNKNOWN_OS"}}
```

- Заголовки ответа

HTTP/2 200 OK  
server: nginx  
date: Mon, 04 Sep 2023 09:24:46 GMT  
content-type: application/json  
access-control-allow-credentials: true  
access-control-allow-headers: Accept, Content-Type, Content-Length, Cookie, Accept-Encoding, X-CSRF-Token, Authorization, Origin, Referer, User-Agent, X-Requested-With  
access-control-allow-methods: POST, GET, OPTIONS, PUT, DELETE  
access-control-allow-origin: https://megamarket.ru  
app-version: mgate:12763  
grpcgateway-content-type: application/grpc  
request-id: 2UvUKfXhF5kM2jVufEhcTSMyK8X  
trace-id: 37cecd2c2768a688  
strict-transport-security: max-age=31536000; includeSubDomains  
x-content-type-options: nosniff  
x-xss-protection: 1; mode=block  
content-encoding: br  
x-sp-crid: 1378929612:33  
X-Firefox-Spdy: h2  

- Тело ответа  

```
{"success":true,"meta":{"time":"2023-09-04T09:24:46Z","traceId":"37cecd2c2768a688","requestId":"2UvUKfXhF5kM2jVufEhcTSMyK8X","appVersion":"mgate:12763"},"errors":[],"seoMeta":{"title":"Результаты по запросу «посуда»","keywords":"","description":"Маркетплейс megamarket.ru – это место выгодных покупок в интернет-магазинах. Мегамаркет – хорошо, когда есть выбор!","h1":"Результаты по запросу «посуда»","text":"","robots":"","canonical":"","prev":"","next":"","ogp":{"title":"Маркетплейс megamarket.ru - место выгодных покупок","description":"Маркетплейс megamarket.ru – это место выгодных покупок в интернет-магазинах. Мегамаркет – хорошо, когда есть выбор!","url":"","image":"https://megamarket.ru/logo_og.png","type":"website","imageType":"","siteName":"megamarket.ru"},"twitter":{"card":"summary","creator":"@sbermm","title":"Поиск товаров. megamarket.ru - место выгодных покупок","description":"Маркетплейс megamarket.ru – это место выгодных покупок в интернет-магазинах. Мегамаркет – хорошо, когда есть выбор!","image":"https://megamarket.ru/logo_twitter.png"},"url":""}}
```

## Запросы, отправляемые на сервер при поиске региона или города в модалке выбора вашего региона

1. POST  /api/mobile/v1/addressSuggestService/address/suggest

- URL  
  <https://megamarket.ru/api/mobile/v1/addressSuggestService/address/suggest>

- Ожидаемый результат  
  
данный запрос отправляется при поиске региона  

- Заголовки запроса  
  
POST /api/mobile/v1/addressSuggestService/address/suggest HTTP/2  
Host: megamarket.ru  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0  
Accept: application/json  
Accept-Language: ru-RU,ru;q=0.8,en-US;q=0.5,en;q=0.3  
Accept-Encoding: gzip, deflate, br  
Referer: https://megamarket.ru/info/cc-terms/  
content-type: application/json  
x-requested-with: XMLHttpRequest  
Content-Length: 780  
Origin: https://megamarket.ru  
Connection: keep-alive  
Cookie: spid=1693495901940_e202eff0aec75867750e0b2462643699_0c0fjt6c2dj55ii5; adspire_uid=AS.1911801593.1693495907; ssaid=7fe22690-4813-11ee-8c60-bd924d22e9c9; megaCookiesMigrated=true; cfidsw-smm=nqm9UC2r+suECrcp0QNz/zT7lrvn9Y7hryE0XsUAjgQSCr4V+N+0Ny1hej5FmSwRoEdJfv0/3cpBLqKdzMymNvqWhr4zdeYTi/PDMoUiw3WondrONMEjbn4ToJghLQzB7hHEaksfz6che1oUorF+fbT2/k9K8gCHNlIh6IW6; device_id=220873b0-4ce7-11ee-8e06-0242ac110002; sbermegamarket_token=ba3ea922-dd17-4896-bdc7-0c23c20f2686; ecom_token=ba3ea922-dd17-4896-bdc7-0c23c20f2686; _ga_W49D2LL5S1=GS1.1.1693940013.18.1.1693940700.36.0.0; _ga=GA1.2.50401148.1693495909; isOldUser=true; adtech_uid=0f06fb3c-37d0-4334-8b7f-9ca608d9bf97%3Amegamarket.ru; top100_id=t1.6795753.2083264748.1693495911442; t3_sid_6795753=s1.1127185861.1693939922162.1693940700366.18.38; last_visit=1693834435846%3A%3A1693845235846; tmr_lvid=1d777c5e87bc54ac71f5e84366113e63; tmr_lvidTS=1693495920918; _gpVisits={"isFirstVisitDomain":true,"idContainer":"10002472"}; adid=169349592227347; _sa=SA1.742d6d39-8ed8-4cb5-b0a7-745058813477.1693495922; rrpvid=183759657204035; _gcl_au=1.1.1649012851.1693495927; flocktory-uuid=bc805808-1c4b-486b-bac1-9adeb83e4b2e-9; __zzatw-smm=MDA0dC0cTHtmcDhhDHEWTT17CT4VHThHKHIzd2Vgb2UdZExaJ0leU2shC1E0NWYQSk9NRzM4P2h9HlQcOVURDxYSNhcjEn10J08NEWQ/SnF5LDdXYTAPFhFNRxhFZ15EQ11wJA==7pBVXw==; rcuid=64f0b27b31535728cb1e5f7b; uxs_uid=920a6f80-4813-11ee-8ab4-3da0b4720c09; adrcid=AhaHjBe2yZuGH03fKivSuxQ; cfidsw-smm=nqm9UC2r+suECrcp0QNz/zT7lrvn9Y7hryE0XsUAjgQSCr4V+N+0Ny1hej5FmSwRoEdJfv0/3cpBLqKdzMymNvqWhr4zdeYTi/PDMoUiw3WondrONMEjbn4ToJghLQzB7hHEaksfz6che1oUorF+fbT2/k9K8gCHNlIh6IW6; rrlevt=1694066497407; _ga_QETLGKM757=GS1.1.1693725960.1.1.1693726083.60.0.0; spsc=1694066482247_468f5055b5351ee3b673013c42c4f39b_a5476469b72f558bb72e6aae99c6a060; __tld__=null; region_info=%7B%22displayName%22%3A%22%D0%A1%D0%90%D0%9D%D0%9A%D0%A2-%D0%9F%D0%95%D0%A2%D0%95%D0%A0%D0%91%D0%A3%D0%A0%D0%93%22%2C%22kladrId%22%3A%227800000000000%22%2C%22isDeliveryEnabled%22%3Atrue%2C%22geo%22%3A%7B%22lat%22%3A59.939095%2C%22lon%22%3A30.315868%7D%2C%22id%22%3A%2278%22%7D; _gp10002472={"ac":1,"a2":1,"hits":6,"vc":1,"a6":1}; tmr_detect=0%7C1694066937169  
Sec-Fetch-Dest: empty  
Sec-Fetch-Mode: cors  
Sec-Fetch-Site: same-origin  
TE: trailers   

- Тело запроса  

```
{"query":"v","count":10,"isSkipRegionFilter":true,"onlyRegionsCities":true,"auth":{"locationId":"78","appPlatform":"WEB","appVersion":1693492133,"experiments":{"1":"2","8":"1","15":"3","41":"2","46":"2","53":"2","55":"2","58":"2","68":"1","69":"1","79":"3","85":"2","96":"2","98":"2","99":"2","107":"2","108":"2","109":"1","119":"1","120":"1","121":"2","122":"1","128":"1","129":"2","130":"2","132":"2","136":"2","144":"3","145":"1","147":"3","148":"3","149":"1","155":"2","163":"2","169":"1","170":"1","173":"1","178":"2","183":"1","187":"3","191":"1","192":"2","201":"3","202":"1","205":"2","5779":"2","20121":"2","43568":"2","67062":"1","67972":"2","69032":"3","70070":"1","72674":"3","80283":"1","81724":"2","85160":"2","86296":"2","86356":"2","90172":"3"},"os":"UNKNOWN_OS"}}
```

- Заголовки ответа

HTTP/2 200 OK  
server: nginx  
date: Thu, 07 Sep 2023 06:10:42 GMT  
content-type: application/json  
access-control-allow-credentials: true  
access-control-allow-headers: Accept, Content-Type, Content-Length, Cookie, Accept-Encoding, X-CSRF-Token, Authorization, Origin, Referer, User-Agent, X-Requested-With  
access-control-allow-methods: POST, GET, OPTIONS, PUT, DELETE  
access-control-allow-origin: https://megamarket.ru  
app-version: mgate:12857  
grpcgateway-content-type: application/grpc  
request-id: 2V3a6VGeH0jZLUhFeIcsBd66kYM  
trace-id: 5881af98de10a57b  
strict-transport-security: max-age=31536000; includeSubDomains  
x-content-type-options: nosniff  
x-xss-protection: 1; mode=block  
content-encoding: br 
x-sp-crid: 327848632:9  
X-Firefox-Spdy: h2  

- Тело ответа  

```
{"items":[{"addressId":"2gis_4644959885983809","full":"Волгоградская область, Волгоград","building":"","buildingType":"","city":"Волгоград","cityType":"Город","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"Волгоградская область","regionType":"","street":"","streetType":"","geoLat":48.70708,"geoLon":44.516975,"regionFiasId":"da051ec8-da2e-4a66-b542-473b8d221ab4","fiasId":"","regionKladrId":"3400000000000","area":"","settlement":"Волгоград","settlementType":"Город","regionId":"34","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false},{"addressId":"2gis_3519059979141128","full":"Приморский край, Владивосток","building":"","buildingType":"","city":"Владивосток","cityType":"Город","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"Приморский край","regionType":"","street":"","streetType":"","geoLat":43.11546,"geoLon":131.88481,"regionFiasId":"43909681-d6e1-432d-b61f-ddac393cb5da","fiasId":"","regionKladrId":"2500000000000","area":"","settlement":"Владивосток","settlementType":"Город","regionId":"25","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false},{"addressId":"2gis_4363484909273106","full":"Воронежская область, Воронеж","building":"","buildingType":"","city":"Воронеж","cityType":"Город","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"Воронежская область","regionType":"","street":"","streetType":"","geoLat":51.66055,"geoLon":39.199776,"regionFiasId":"b756fe6b-bbd3-44d5-9302-5bfcc740f46e","fiasId":"","regionKladrId":"3600000000000","area":"","settlement":"Воронеж","settlementType":"Город","regionId":"36","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false},{"addressId":"2gis_8304134583222334","full":"Владимирская область, Владимир","building":"","buildingType":"","city":"Владимир","cityType":"Город","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"Владимирская область","regionType":"","street":"","streetType":"","geoLat":56.129143,"geoLon":40.406635,"regionFiasId":"b8837188-39ee-4ff9-bc91-fcc9ed451bb3","fiasId":"","regionKladrId":"3300000000000","area":"","settlement":"Владимир","settlementType":"Город","regionId":"33","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false},{"addressId":"2gis_70030076138301140","full":"Ленинградская область, Выборг","building":"","buildingType":"","city":"Выборг","cityType":"Город","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"Ленинградская область","regionType":"","street":"","streetType":"","geoLat":60.707626,"geoLon":28.753693,"regionFiasId":"6d1ebb35-70c6-4129-bd55-da3969658f5d","fiasId":"","regionKladrId":"4700000000000","area":"","settlement":"Выборг","settlementType":"Город","regionId":"47","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false},{"addressId":"2gis_1267655302447148","full":"Волгоградская область","building":"","buildingType":"","city":"","cityType":"","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"Волгоградская область","regionType":"","street":"","streetType":"","geoLat":49.64021,"geoLon":44.151432,"regionFiasId":"da051ec8-da2e-4a66-b542-473b8d221ab4","fiasId":"","regionKladrId":"3400000000000","area":"","settlement":"","settlementType":"","regionId":"34","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false},{"addressId":"2gis_10978146861973508","full":"Вологодская область, Вологда","building":"","buildingType":"","city":"Вологда","cityType":"Город","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"Вологодская область","regionType":"","street":"","streetType":"","geoLat":59.22062,"geoLon":39.89174,"regionFiasId":"ed36085a-b2f5-454f-b9a9-1c9a678ee618","fiasId":"","regionKladrId":"3500000000000","area":"","settlement":"Вологда","settlementType":"Город","regionId":"35","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false},{"addressId":"2gis_1267655302447150","full":"Воронежская область","building":"","buildingType":"","city":"","cityType":"","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"Воронежская область","regionType":"","street":"","streetType":"","geoLat":51.13433,"geoLon":40.022274,"regionFiasId":"b756fe6b-bbd3-44d5-9302-5bfcc740f46e","fiasId":"","regionKladrId":"3600000000000","area":"","settlement":"","settlementType":"","regionId":"36","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false},{"addressId":"2gis_10837409373618180","full":"Новгородская область, Великий Новгород","building":"","buildingType":"","city":"Великий Новгород","cityType":"Город","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"Новгородская область","regionType":"","street":"","streetType":"","geoLat":58.522766,"geoLon":31.270185,"regionFiasId":"e5a84b81-8ea1-49e3-b3c4-0528651be129","fiasId":"","regionKladrId":"5300000000000","area":"","settlement":"Великий Новгород","settlementType":"Город","regionId":"53","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false},{"addressId":"2gis_16044696473293721","full":"Владикавказ","building":"","buildingType":"","city":"Владикавказ","cityType":"Город","entrance":"","flat":"","flatType":"","floor":"","house":"","houseType":"","intercom":"","postalCode":"","region":"","regionType":"","street":"","streetType":"","geoLat":43.024837,"geoLon":44.681377,"regionFiasId":"","fiasId":"","regionKladrId":"","area":"","settlement":"Владикавказ","settlementType":"Город","regionId":"","rawData":null,"courierDeliveryError":null,"isCorrect":true,"addressCoordinatesAccuracy":"ADDRESS_COORDINATES_ACCURACY_UNKNOWN","isGeoReplaced":false}]}
```

2. POST  /api/mobile/v1/regionService/region/search

- URL  
  <https://megamarket.ru/api/mobile/v1/regionService/region/search>

- Ожидаемый результат  
  
данный запрос отправляется при поиске региона  

- Заголовки запроса  
- 
POST /api/mobile/v1/regionService/region/search HTTP/2  
Host: megamarket.ru  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0  
Accept: application/json  
Accept-Language: ru-RU,ru;q=0.8,en-US;q=0.5,en;q=0.3  
Accept-Encoding: gzip, deflate, br  
Referer: https://megamarket.ru/  
content-type: application/json  
x-requested-with: XMLHttpRequest  
Content-Length: 125  
Origin: https://megamarket.ru  
Connection: keep-alive  
Cookie: spid=1693495901940_e202eff0aec75867750e0b2462643699_0c0fjt6c2dj55ii5; adspire_uid=AS.1911801593.1693495907; ssaid=7fe22690-4813-11ee-8c60-bd924d22e9c9; megaCookiesMigrated=true; cfidsw-smm=QkRMotRxiP/hwd6gqe+odX+NbXgJzw59g+EjYlosedqML2DfX9d8N1+GtEGjbXFi2oXFE1d/5HHwzLRqRtUOCEIRwqSXsgsWE1dQhKJwnFt8hNBWnklIr4yCXv90wF26NrGAxRZQlPfTKh07Riee6ppbD+hwnwBys5BciTTk; device_id=8046ed87-4813-11ee-9a27-0242ac110004; sbermegamarket_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; ecom_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; _ga_W49D2LL5S1=GS1.1.1693817119.14.1.1693818147.60.0.0; _ga=GA1.1.50401148.1693495909; isOldUser=true; adtech_uid=0f06fb3c-37d0-4334-8b7f-9ca608d9bf97%3Amegamarket.ru; top100_id=t1.6795753.2083264748.1693495911442; t3_sid_6795753=s1.980669749.1693817121655.1693818143095.13.39; last_visit=1693806997562%3A%3A1693817797562; tmr_lvid=1d777c5e87bc54ac71f5e84366113e63; tmr_lvidTS=1693495920918; region_info=%7B%22displayName%22%3A%22%D0%9C%D0%BE%D1%81%D0%BA%D0%BE%D0%B2%D1%81%D0%BA%D0%B0%D1%8F%20%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C%22%2C%22kladrId%22%3A%225000000000000%22%2C%22isDeliveryEnabled%22%3Atrue%2C%22geo%22%3A%7B%22lat%22%3A55.755814%2C%22lon%22%3A37.617635%7D%2C%22id%22%3A%2250%22%7D; _gpVisits={"isFirstVisitDomain":true,"idContainer":"10002472"}; adid=169349592227347; _sa=SA1.742d6d39-8ed8-4cb5-b0a7-745058813477.1693495922; rrpvid=183759657204035; _gcl_au=1.1.1649012851.1693495927; flocktory-uuid=bc805808-1c4b-486b-bac1-9adeb83e4b2e-9; _gp10002472={"utm":"7df3f2b7","hits":6,"vc":1,"ac":1,"a6":1}; __zzatw-smm=MDA0dC0cTHtmcDhhDHEWTT17CT4VHThHKHIzd2UbN1ddHBEkWA4hPwsXXFU+NVQOPHVXLw0uOF4tbx5lUFwnRFxUCi0ZFnpnFRtQSxgvS18+bX0yUCs5Lmw=13RDig==; rcuid=64f0b27b31535728cb1e5f7b; uxs_uid=920a6f80-4813-11ee-8ab4-3da0b4720c09; adrcid=AhaHjBe2yZuGH03fKivSuxQ; cfidsw-smm=LibiyBHYBZo3sfwV8zehWklMrGNJCUsDHdIYViaXNDJ0oa+DhhO0Z9I+NaqElSFvsDjActiHxMgSFyo9hJxq4sPFusTl6HvdC2tW8VxeBFHgp/CaMfLfqcQplcUFSMnHoX0OrTvGyGbKJeLB0CZTGi8+uUUNzK7u+I/m+GGM; tmr_detect=0%7C1693817806766; rrlevt=1693639359031; _ga_QETLGKM757=GS1.1.1693725960.1.1.1693726083.60.0.0; spsc=1693817121623_b7770206f74f81f949c7a92ab758273a_a5476469b72f558bb72e6aae99c6a060; __tld__=null; _gid=GA1.2.1071491218.1693817687  
Sec-Fetch-Dest: empty  
Sec-Fetch-Mode: cors  
Sec-Fetch-Site: same-origin  
TE: trailers   

- Тело запроса  

```
{"regionId":"50","auth":{"locationId":"50","appPlatform":"WEB","appVersion":1693492133,"experiments":null,"os":"UNKNOWN_OS"}}  
```

- Заголовки ответа

HTTP/2 200 OK  
server: nginx  
date: Mon, 04 Sep 2023 09:02:28 GMT  
content-type: application/json  
vary: Accept-Encoding  
access-control-allow-credentials: true  
access-control-allow-headers: Accept, Content-Type, Content-Length, Cookie, Accept-Encoding, X-CSRF-Token, Authorization, Origin, Referer, User-Agent, X-Requested-With  
access-control-allow-methods: POST, GET, OPTIONS, PUT, DELETE  
access-control-allow-origin: https://megamarket.ru  
app-version: mgate:12683  
grpcgateway-content-type: application/grpc  
request-id: 2UvRcfIbiJpyvzuLhjYDSjLPfup  
trace-id: 2206767dcf1a6c39  
strict-transport-security: max-age=31536000; includeSubDomains  
x-content-type-options: nosniff  
x-xss-protection: 1; mode=block  
x-sp-crid: 647695295:2  
content-encoding: gzip  
X-Firefox-Spdy: h2  

- Тело ответа  

```
{"regions":[{"id":"50","kladrId":"5000000000000","dislplayName":"Московская область","isPickupPointDeliveryEnabled":true,"isCourierDeliveryEnabled":true,"isDeliveryEnabled":true,"geoLat":"55.755814","geoLon":"37.617635","isTopList":false,"deliveryByLogisticClass":["SBLM135","SBLM30","ANYPVZ","BROKEN","MGT","KGT","OVER","NONE"],"courierDeliveryDetails":{"description":"","url":"","isEnabled":true,"logisticClasses":["SBLM135","SBLM30"]},"pickupDeliveryDetails":{"description":"","url":"","isEnabled":true,"logisticClasses":["ANYPVZ"]},"cncDeliveryDetails":{"description":"","url":"","isEnabled":true,"logisticClasses":["BROKEN","MGT","KGT","OVER","NONE"]},"cndDeliveryDetails":{"description":"","url":"","isEnabled":true,"logisticClasses":["BROKEN","MGT","KGT","OVER","NONE"]},"cndbmDeliveryDetails":{"description":"","url":"","isEnabled":false,"logisticClasses":[]},"subdomain":"","subfolder":"","postalCode":"","timezoneUtcOffset":"UTC+3","isDetectedByIp":false}]}
```

3. POST  /api/mobile/v1/userLocationService/region/save

- URL  
  <https://megamarket.ru/api/mobile/v1/userLocationService/region/save>

- Ожидаемый результат  
  
данный запрос отправляется при подтверждении введенного города (Санкт-Петербург)  

- Заголовки запроса  

POST /api/mobile/v1/userLocationService/region/save HTTP/2  
Host: megamarket.ru  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0  
Accept: application/json  
Accept-Language: ru-RU,ru;q=0.8,en-US;q=0.5,en;q=0.3  
Accept-Encoding: gzip, deflate, br  
Referer: https://megamarket.ru/  
content-type: application/json  
x-requested-with: XMLHttpRequest  
Content-Length: 645  
Origin: https://megamarket.ru  
Connection: keep-alive  
Cookie: spid=1693495901940_e202eff0aec75867750e0b2462643699_0c0fjt6c2dj55ii5; adspire_uid=AS.1911801593.1693495907; ssaid=7fe22690-4813-11ee-8c60-bd924d22e9c9; megaCookiesMigrated=true; cfidsw-smm=5OcBFXlcdwShD+OXv+Egkpqx2LEmAYtUCcksHlZOAxDCHATMQr6cw4lDnZUNCa/WHT8zgkJWdRSVvcK2hS9sfQsfLBV25zDBwERrosdJAcYUBCdeddX9b6MlwxIBBr+OG2MbRubpAeO2YEXGpc5V2umjmxANvESqPEiaN7uy; device_id=8046ed87-4813-11ee-9a27-0242ac110004; sbermegamarket_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; ecom_token=01e16e68-6c75-42e6-a2c2-d1da5b90dc05; _ga_W49D2LL5S1=GS1.1.1693817119.14.1.1693818611.60.0.0; _ga=GA1.2.50401148.1693495909; isOldUser=true; adtech_uid=0f06fb3c-37d0-4334-8b7f-9ca608d9bf97%3Amegamarket.ru; top100_id=t1.6795753.2083264748.1693495911442; t3_sid_6795753=s1.980669749.1693817121655.1693818547122.13.51; last_visit=1693807348553%3A%3A1693818148553; tmr_lvid=1d777c5e87bc54ac71f5e84366113e63; tmr_lvidTS=1693495920918; region_info=%7B%22displayName%22%3A%22%D0%A1%D0%90%D0%9D%D0%9A%D0%A2-%D0%9F%D0%95%D0%A2%D0%95%D0%A0%D0%91%D0%A3%D0%A0%D0%93%22%2C%22kladrId%22%3A%227800000000000%22%2C%22isDeliveryEnabled%22%3Atrue%2C%22geo%22%3A%7B%22lat%22%3A59.939095%2C%22lon%22%3A30.315868%7D%2C%22id%22%3A%2278%22%7D; _gpVisits={"isFirstVisitDomain":true,"idContainer":"10002472"}; adid=169349592227347; _sa=SA1.742d6d39-8ed8-4cb5-b0a7-745058813477.1693495922; rrpvid=183759657204035; _gcl_au=1.1.1649012851.1693495927; flocktory-uuid=bc805808-1c4b-486b-bac1-9adeb83e4b2e-9; _gp10002472={"utm":"7df3f2b7","hits":7,"vc":1,"ac":1,"a6":1}; __zzatw-smm=MDA0dC0cTHtmcDhhDHEWTT17CT4VHThHKHIzd2UbN1ddHBEkWA4hPwsXXFU+NVQOPHVXLw0uOF4tbx5lUFwnRF1OfS4ZEn9nFRtQSxgvS18+bX0yUCs5Lmw=P1mc4Q==; rcuid=64f0b27b31535728cb1e5f7b; uxs_uid=920a6f80-4813-11ee-8ab4-3da0b4720c09; adrcid=AhaHjBe2yZuGH03fKivSuxQ; cfidsw-smm=5OcBFXlcdwShD+OXv+Egkpqx2LEmAYtUCcksHlZOAxDCHATMQr6cw4lDnZUNCa/WHT8zgkJWdRSVvcK2hS9sfQsfLBV25zDBwERrosdJAcYUBCdeddX9b6MlwxIBBr+OG2MbRubpAeO2YEXGpc5V2umjmxANvESqPEiaN7uy; tmr_detect=0%7C1693818155122; rrlevt=1693639359031; _ga_QETLGKM757=GS1.1.1693725960.1.1.1693726083.60.0.0; spsc=1693817121623_b7770206f74f81f949c7a92ab758273a_a5476469b72f558bb72e6aae99c6a060; __tld__=null; _gid=GA1.2.1071491218.1693817687; _gat=1  
Sec-Fetch-Dest: empty  
Sec-Fetch-Mode: cors  
Sec-Fetch-Site: same-origin  
TE: trailers  

- Тело запроса  

```
{"region":"78","kladr_id":"7800000000000","auth":{"locationId":"50","appPlatform":"WEB","appVersion":1693492133,"experiments":{"1":"2","8":"2","41":"2","46":"2","53":"2","55":"2","58":"2","68":"1","69":"1","79":"3","85":"2","98":"2","99":"2","107":"1","108":"2","109":"2","119":"2","120":"1","121":"2","122":"1","128":"2","129":"1","132":"2","136":"1","144":"1","148":"1","149":"1","155":"1","170":"3","173":"1","183":"2","187":"3","191":"1","192":"1","201":"3","202":"1","205":"2","5779":"2","20121":"1","67062":"1","67972":"2","69032":"3","70070":"1","72674":"3","81724":"2","85160":"2","86296":"2","86356":"2","90172":"3"},"os":"UNKNOWN_OS"}}
```

- Заголовки ответа

HTTP/2 200 OK  
server: nginx  
date: Mon, 04 Sep 2023 09:10:25 GMT  
content-type: application/json  
vary: Accept-Encoding  
access-control-allow-credentials: true  
access-control-allow-headers: Accept, Content-Type, Content-Length, Cookie, Accept-Encoding, X-CSRF-Token, Authorization, Origin, Referer, User-Agent, X-Requested-With  
access-control-allow-methods: POST, GET, OPTIONS, PUT, DELETE  
access-control-allow-origin: https://megamarket.ru  
app-version: mgate:12763  
grpcgateway-content-type: application/grpc  
request-id: 2UvSad1wbMga8BKmK68uXvr7es3  
trace-id: 19e1365f9b2f227a  
strict-transport-security: max-age=31536000; includeSubDomains  
x-content-type-options: nosniff  
x-xss-protection: 1; mode=block  
x-sp-crid: 1398848906:7  
content-encoding: gzip  
X-Firefox-Spdy: h2  

- Тело ответа  

```
{"success":true,"meta":{"time":"2023-09-04T09:10:25Z","traceId":"19e1365f9b2f227a","requestId":"2UvSad1wbMga8BKmK68uXvr7es3","appVersion":"mgate:12763"},"errors":[]}
```