# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/dragAndDropWithinFrame.spec.ts >> drag and drop with iframe
- Location: tests/dragAndDropWithinFrame.spec.ts:4:5

# Error details

```
Test timeout of 10000ms exceeded.
```

```
TimeoutError: page.goto: Timeout 5000ms exceeded.
Call log:
  - navigating to "https://www.globalsqa.com/demo-site/draganddrop/", waiting until "load"

```

# Page snapshot

```yaml
- generic [ref=e2]:
  - banner [ref=e3]:
    - generic [ref=e7]:
      - generic:
        - generic:
          - generic:
            - button [ref=e8] [cursor=pointer]
            - textbox "Search..." [ref=e9]
        - link "pinterest" [ref=e10] [cursor=pointer]:
          - /url: https://in.pinterest.com/globalsqa/
        - link "twitter" [ref=e11] [cursor=pointer]:
          - /url: https://twitter.com/Global_SQA
        - link "linkedin" [ref=e12] [cursor=pointer]:
          - /url: https://www.linkedin.com/company/globalsqa
        - link "google" [ref=e13] [cursor=pointer]:
          - /url: https://plus.google.com/103761557396023531439/posts
        - link "facebook" [ref=e14] [cursor=pointer]:
          - /url: https://facebook.com/globalsqa
        - generic [ref=e15]: contact@globalsqa.com
    - generic [ref=e19]:
      - link [ref=e22] [cursor=pointer]:
        - /url: https://www.globalsqa.com/
        - img "GlobalSQA" [ref=e23]
      - generic [ref=e24]:
        - list:
          - listitem [ref=e25]:
            - link "About" [ref=e26] [cursor=pointer]:
              - /url: https://www.globalsqa.com/about/
          - listitem [ref=e27]:
            - link "CheatSheets" [ref=e28] [cursor=pointer]:
              - /url: https://www.globalsqa.com/cheatsheets/
          - listitem [ref=e29]:
            - link "Free Ebooks" [ref=e30] [cursor=pointer]:
              - /url: https://www.globalsqa.com/free-ebooks/
          - listitem [ref=e32]:
            - link "Tester’s Hub" [ref=e33] [cursor=pointer]:
              - /url: https://www.globalsqa.com/testers-hub/
            - text:  
          - listitem [ref=e35]:
            - link "Contact Us" [ref=e36] [cursor=pointer]:
              - /url: https://www.globalsqa.com/contact-us/
    - text:    
  - generic [ref=e37]:
    - generic [ref=e41]:
      - generic [ref=e42]:
        - link "Home" [ref=e43] [cursor=pointer]:
          - /url: https://www.globalsqa.com/
        - link "Demo Testing Site" [ref=e45] [cursor=pointer]:
          - /url: https://www.globalsqa.com/demo-site/
        - link "Drag And Drop" [ref=e47] [cursor=pointer]:
          - /url: https://www.globalsqa.com/demo-site/draganddrop/
      - heading "Drag And Drop" [level=1] [ref=e50]
    - generic [ref=e53]:
      - generic [ref=e54]:
        - generic [ref=e55]:
          - heading "Interaction" [level=4] [ref=e56]
          - list [ref=e58]:
            - listitem [ref=e59]:
              - link "Sortable" [ref=e60] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/sorting/
            - listitem [ref=e62]:
              - link "Drag And Drop" [ref=e63] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/draganddrop/
            - listitem [ref=e65]:
              - link "Select Elements" [ref=e66] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/select-elements/
            - listitem [ref=e68]:
              - link "Draggable Boxes" [ref=e69] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/draggableboxes/
            - listitem [ref=e71]:
              - link "DropDown Menu" [ref=e72] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/select-dropdown-menu/
        - generic [ref=e74]:
          - heading "Widgets" [level=4] [ref=e75]
          - list [ref=e77]:
            - listitem [ref=e78]:
              - link "Tooltip" [ref=e79] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/tooltip/
            - listitem [ref=e81]:
              - link "Sliders" [ref=e82] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/sliders/
            - listitem [ref=e84]:
              - link "Spinner" [ref=e85] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/spinner/
            - listitem [ref=e87]:
              - link "DatePicker" [ref=e88] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/datepicker/
            - listitem [ref=e90]:
              - link "Progress Bar" [ref=e91] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/progress-bar/
            - listitem [ref=e93]:
              - link "Dialog Boxes" [ref=e94] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/dialog-boxes/
            - listitem [ref=e96]:
              - link "Auto Complete" [ref=e97] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/auto-complete/
            - listitem [ref=e99]:
              - link "Accordion And Tabs" [ref=e100] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/accordion-and-tabs/
        - iframe [ref=e103]:
          - generic [ref=f6e1]:
            - generic [ref=f6e6]:
              - generic [ref=f6e7]:
                - link "Jednoiposoban stan na Nov €55,000 Prikaži više" [ref=f6e11] [cursor=pointer]:
                  - /url: https://adclick.g.doubleclick.net/aclk?sa=l&ai=CUg_7BAF_avXRJ7zo-d8PvZ2_-A3X5JavhwHSoNufyRHZ5LGbzAgQASCn5pMjYLEFoAHI2I7fA8gBCakC6b_Hi7QlRT6oAwHIA8sEqgT1AU_QXNM2ojya-H9NXxxkaRpSDMMmdIG7C8MUnZFq2aroq7z9Ysr94l3vFABGouE64BEuq1uxynySDOZNTGbxo9TM_wprxIuXSpXT2uBNvzZ9NB_1RsLUxJe-aXaGhZpkRiKTR1TH6iYWko_V2Mh2Ugz8mxgNcgpjQ0-NMNrOoLCE5gJK3sVInQMBeRcz56fDDEf26_4zDrdbkvdKqKULdtsEZM5G79moRGQQrCusgjNBYeMEma9gk-EqkcCR-3OYaLcfeRVrBOsz5e04t4ZfmgG9faEAWmPjXnAZCNSWoNSg_b8mPusC5JRRC5m1Yg9yISuSQM8RwATiob-flgSIBbehwL1K-gUGCCUQARgAoAYugAegp_EgqAenzLECqAfi2LECqAemvhuoB8zOsQKoB_PRG6gHltgbqAeqm7ECqAf-6LECqAeOzhuoB5PYG6gH8OAbqAfulrECqAf-nrECqAevvrECqAef4bECqAem67ECqAfZtrECqAeaBqgH_56xAqgH35-xAqgH-MKxAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAtgHAMAIAdIIMwiAYRABGJ8DMgiKgoCAgICACDoPgECAwICAgICogAKog4AQSL39wTpYhZWk6oaglgNgAYAKAZALA5gLAcgLAYAMAaIMIEgBYgIKAGoQCg5jb20uaGFsb29nbGFzaXgBiAEBkAEBqg0CUlPIDQHqDRMIt-mk6oaglgMVPHT-BR29zg_f8A0CiA4J2BMKiBQD0BUBmBYByhYCCgD4FgGAFwGyFxAYASoKNTcxODk4MTMwOFAGuhcCOAGqGBcJAAAAAADqukASCjU3MTg5ODEzMDgYAbIYCRICk04YLiIBANAYAegYAcIZAggB&ae=1&gclid=EAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASABEgJe_vD_BwE&num=1&cid=CAQShgIAEQoqgaY0yabUKKsLhlwlpkzSPHk2kchltrk8-I8I2YxZcvhoRMVERUwlmaD0vDrdb8n-Q6mc5_-eJZAHpmbX64MSTpsEB6sCDsr6XLjKeOTU9YEwHRLYzGVf44WsfSAgGyXfrOUkcp-G05M9CDlD3q9IHs8Gav9YcOFcGItEKr0kXbdQ9KOxcyIiF9cNyrD_iS0xCikt1Y9lRDsJY0GL9oJiExf-cvK3-zPZU1OJa0jW6ToNznYYA3qkWX_BTQ3S2QsGWjzFvNX1QmdkkAf-eR4Jzwu1FV14P-ZK15jcgVEy8JA58Bh9MDKpBxQMhsXzI2cJ2xwkUGEi3HzN5IpDKkYng6uCGAE&sig=AOD64_1g-wW01JhgXDEdFtU90_Bv9OepCg&client=ca-pub-2878895907861435&nb=9&adurl=https://www.halooglasi.com/nekretnine/prodaja-stanova/jednoiposoban-stan-na-novoj-detelinari/5425647231245%3Fkid%3D1%26gad_source%3D5%26gad_campaignid%3D19993202871%26gclid%3DEAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASABEgJe_vD_BwE
                  - generic [ref=f6e14]:
                    - generic [ref=f6e16]:
                      - generic [ref=f6e17]: Jednoiposobanstan na Nov
                      - generic [ref=f6e19]: €55,000
                    - generic [ref=f6e20]: Prikaži više
                - link "Kuća 70m2, plac 7,73 ari, €23,000 Prikaži više" [ref=f6e27] [cursor=pointer]:
                  - /url: https://adclick.g.doubleclick.net/aclk?sa=l&ai=CpqeJBAF_avXRJ7zo-d8PvZ2_-A3X5JavhwHSoNufyRHZ5LGbzAgQASCn5pMjYLEFoAHI2I7fA8gBCakC6b_Hi7QlRT6oAwHIA8sEqgT1AU_QXNM2ojya-H9NXxxkaRpSDMMmdIG7C8MUnZFq2aroq7z9Ysr94l3vFABGouE64BEuq1uxynySDOZNTGbxo9TM_wprxIuXSpXT2uBNvzZ9NB_1RsLUxJe-aXaGhZpkRiKTR1TH6iYWko_V2Mh2Ugz8mxgNcgpjQ0-NMNrOoLCE5gJK3sVInQMBeRcz56fDDEf26_4zDrdbkvdKqKULdtsEZM5G79moRGQQrCusgjNBYeMEma9gk-EqkcCR-3OYaLcfeRVrBOsz5e04t4ZfmgG9faEAWmPjXnAZCNSWoNSg_b8mPusC5JRRC5m1Yg9yISuSQM8RwATiob-flgSIBbehwL1K-gUGCCUQARgBoAYugAegp_EgqAenzLECqAfi2LECqAemvhuoB8zOsQKoB_PRG6gHltgbqAeqm7ECqAf-6LECqAeOzhuoB5PYG6gH8OAbqAfulrECqAf-nrECqAevvrECqAef4bECqAem67ECqAfZtrECqAeaBqgH_56xAqgH35-xAqgH-MKxAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAtgHAMAIAtIIMwiAYRABGJ8DMgiKgoCAgICACDoPgECAwICAgICogAKog4AQSL39wTpYhZWk6oaglgNgAYAKAZALA5gLAcgLAYAMAaIMIEgBYgIKAGoQCg5jb20uaGFsb29nbGFzaXgBiAEBkAEBqg0CUlPIDQHqDRMIt-mk6oaglgMVPHT-BR29zg_f8A0CiA4J2BMKiBQD0BUBmBYByhYCCgD4FgGAFwGyFxAYASoKNTcxODk4MTMwOFAGuhcCOAGqGBcJAAAAAADqukASCjU3MTg5ODEzMDgYAbIYCRICk04YLiIBANAYAegYAcIZAggB&ae=1&gclid=EAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASACEgLJxvD_BwE&num=1&cid=CAQShgIAEQoqgaY0yabUKKsLhlwlpkzSPHk2kchltrk8-I8I2YxZcvhoRMVERUwlmaD0vDrdb8n-Q6mc5_-eJZAHpmbX64MSTpsEB6sCDsr6XLjKeOTU9YEwHRLYzGVf44WsfSAgGyXfrOUkcp-G05M9CDlD3q9IHs8Gav9YcOFcGItEKr0kXbdQ9KOxcyIiF9cNyrD_iS0xCikt1Y9lRDsJY0GL9oJiExf-cvK3-zPZU1OJa0jW6ToNznYYA3qkWX_BTQ3S2QsGWjzFvNX1QmdkkAf-eR4Jzwu1FV14P-ZK15jcgVEy8JA58Bh9MDKpBxQMhsXzI2cJ2xwkUGEi3HzN5IpDKkYng6uCGAE&sig=AOD64_3BeZtLJTpK88IoAjutFOVrDuQGtw&client=ca-pub-2878895907861435&nb=9&adurl=https://www.halooglasi.com/nekretnine/prodaja-kuca/kuca-70m2-plac-7-73-ari-sa-imanjem-u-starom-m/5425646475871%3Fkid%3D1%26gad_source%3D5%26gad_campaignid%3D19993202871%26gclid%3DEAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASACEgLJxvD_BwE
                  - generic [ref=f6e30]:
                    - generic [ref=f6e32]:
                      - generic [ref=f6e33]: Kuća 70m2, plac7,73 ari,
                      - generic [ref=f6e35]: €23,000
                    - generic [ref=f6e36]: Prikaži više
                - link "Prodaje se kuća u prirodi €22,000 Prikaži više" [ref=f6e43] [cursor=pointer]:
                  - /url: https://adclick.g.doubleclick.net/aclk?sa=l&ai=CQ_PdBAF_avXRJ7zo-d8PvZ2_-A3X5JavhwHSoNufyRHZ5LGbzAgQASCn5pMjYLEFoAHI2I7fA8gBCakC6b_Hi7QlRT6oAwHIA8sEqgT1AU_QXNM2ojya-H9NXxxkaRpSDMMmdIG7C8MUnZFq2aroq7z9Ysr94l3vFABGouE64BEuq1uxynySDOZNTGbxo9TM_wprxIuXSpXT2uBNvzZ9NB_1RsLUxJe-aXaGhZpkRiKTR1TH6iYWko_V2Mh2Ugz8mxgNcgpjQ0-NMNrOoLCE5gJK3sVInQMBeRcz56fDDEf26_4zDrdbkvdKqKULdtsEZM5G79moRGQQrCusgjNBYeMEma9gk-EqkcCR-3OYaLcfeRVrBOsz5e04t4ZfmgG9faEAWmPjXnAZCNSWoNSg_b8mPusC5JRRC5m1Yg9yISuSQM8RwATiob-flgSIBbehwL1K-gUGCCUQARgCoAYugAegp_EgqAenzLECqAfi2LECqAemvhuoB8zOsQKoB_PRG6gHltgbqAeqm7ECqAf-6LECqAeOzhuoB5PYG6gH8OAbqAfulrECqAf-nrECqAevvrECqAef4bECqAem67ECqAfZtrECqAeaBqgH_56xAqgH35-xAqgH-MKxAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAtgHAMAIA9IIMwiAYRABGJ8DMgiKgoCAgICACDoPgECAwICAgICogAKog4AQSL39wTpYhZWk6oaglgNgAYAKAZALA5gLAcgLAYAMAaIMIEgBYgIKAGoQCg5jb20uaGFsb29nbGFzaXgBiAEBkAEBqg0CUlPIDQHqDRMIt-mk6oaglgMVPHT-BR29zg_f8A0CiA4J2BMKiBQD0BUBmBYByhYCCgD4FgGAFwGyFxAYASoKNTcxODk4MTMwOFAGuhcCOAGqGBcJAAAAAADqukASCjU3MTg5ODEzMDgYAbIYCRICk04YLiIBANAYAegYAcIZAggB&ae=1&gclid=EAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASADEgKW3PD_BwE&num=1&cid=CAQShgIAEQoqgaY0yabUKKsLhlwlpkzSPHk2kchltrk8-I8I2YxZcvhoRMVERUwlmaD0vDrdb8n-Q6mc5_-eJZAHpmbX64MSTpsEB6sCDsr6XLjKeOTU9YEwHRLYzGVf44WsfSAgGyXfrOUkcp-G05M9CDlD3q9IHs8Gav9YcOFcGItEKr0kXbdQ9KOxcyIiF9cNyrD_iS0xCikt1Y9lRDsJY0GL9oJiExf-cvK3-zPZU1OJa0jW6ToNznYYA3qkWX_BTQ3S2QsGWjzFvNX1QmdkkAf-eR4Jzwu1FV14P-ZK15jcgVEy8JA58Bh9MDKpBxQMhsXzI2cJ2xwkUGEi3HzN5IpDKkYng6uCGAE&sig=AOD64_2tRlpuuknJZGRm_XvkdlTqzwmjfw&client=ca-pub-2878895907861435&nb=9&adurl=https://www.halooglasi.com/nekretnine/prodaja-kuca/prodaje-se-kuca-u-prirodi-u-velikom-drenovcu/5425644399885%3Fkid%3D1%26gad_source%3D5%26gad_campaignid%3D19993202871%26gclid%3DEAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASADEgKW3PD_BwE
                  - generic [ref=f6e46]:
                    - generic [ref=f6e48]:
                      - generic [ref=f6e49]: Prodaje se kućau prirodi
                      - generic [ref=f6e51]: €22,000
                    - generic [ref=f6e52]: Prikaži više
                - link "Prodaja, Uciteljsko naselj €122,000 Prikaži više" [ref=f6e59] [cursor=pointer]:
                  - /url: https://adclick.g.doubleclick.net/aclk?sa=l&ai=CX2fQBAF_avXRJ7zo-d8PvZ2_-A3X5JavhwHSoNufyRHZ5LGbzAgQASCn5pMjYLEFoAHI2I7fA8gBCakC6b_Hi7QlRT6oAwHIA8sEqgT1AU_QXNM2ojya-H9NXxxkaRpSDMMmdIG7C8MUnZFq2aroq7z9Ysr94l3vFABGouE64BEuq1uxynySDOZNTGbxo9TM_wprxIuXSpXT2uBNvzZ9NB_1RsLUxJe-aXaGhZpkRiKTR1TH6iYWko_V2Mh2Ugz8mxgNcgpjQ0-NMNrOoLCE5gJK3sVInQMBeRcz56fDDEf26_4zDrdbkvdKqKULdtsEZM5G79moRGQQrCusgjNBYeMEma9gk-EqkcCR-3OYaLcfeRVrBOsz5e04t4ZfmgG9faEAWmPjXnAZCNSWoNSg_b8mPusC5JRRC5m1Yg9yISuSQM8RwATiob-flgSIBbehwL1K-gUGCCUQARgDoAYugAegp_EgqAenzLECqAfi2LECqAemvhuoB8zOsQKoB_PRG6gHltgbqAeqm7ECqAf-6LECqAeOzhuoB5PYG6gH8OAbqAfulrECqAf-nrECqAevvrECqAef4bECqAem67ECqAfZtrECqAeaBqgH_56xAqgH35-xAqgH-MKxAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAtgHAMAIBNIIMwiAYRABGJ8DMgiKgoCAgICACDoPgECAwICAgICogAKog4AQSL39wTpYhZWk6oaglgNgAYAKAZALA5gLAcgLAYAMAaIMIEgBYgIKAGoQCg5jb20uaGFsb29nbGFzaXgBiAEBkAEBqg0CUlPIDQHqDRMIt-mk6oaglgMVPHT-BR29zg_f8A0CiA4J2BMKiBQD0BUBmBYByhYCCgD4FgGAFwGyFxAYASoKNTcxODk4MTMwOFAGuhcCOAGqGBcJAAAAAADqukASCjU3MTg5ODEzMDgYAbIYCRICk04YLiIBANAYAegYAcIZAggB&ae=1&gclid=EAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASAEEgJXfPD_BwE&num=1&cid=CAQShgIAEQoqgaY0yabUKKsLhlwlpkzSPHk2kchltrk8-I8I2YxZcvhoRMVERUwlmaD0vDrdb8n-Q6mc5_-eJZAHpmbX64MSTpsEB6sCDsr6XLjKeOTU9YEwHRLYzGVf44WsfSAgGyXfrOUkcp-G05M9CDlD3q9IHs8Gav9YcOFcGItEKr0kXbdQ9KOxcyIiF9cNyrD_iS0xCikt1Y9lRDsJY0GL9oJiExf-cvK3-zPZU1OJa0jW6ToNznYYA3qkWX_BTQ3S2QsGWjzFvNX1QmdkkAf-eR4Jzwu1FV14P-ZK15jcgVEy8JA58Bh9MDKpBxQMhsXzI2cJ2xwkUGEi3HzN5IpDKkYng6uCGAE&sig=AOD64_3EsAm_3gMmOJPkc5K4NPov9dLWZA&client=ca-pub-2878895907861435&nb=9&adurl=https://www.halooglasi.com/nekretnine/prodaja-stanova/prodaja-uciteljsko-naselje-novogradnja-1-5-pr/5425646629866%3Fkid%3D1%26gad_source%3D5%26gad_campaignid%3D19993202871%26gclid%3DEAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASAEEgJXfPD_BwE
                  - generic [ref=f6e62]:
                    - generic [ref=f6e64]:
                      - generic [ref=f6e65]: Prodaja,Uciteljsko naselj
                      - generic [ref=f6e67]: €122,000
                    - generic [ref=f6e68]: Prikaži više
              - link "Tvoj idealni stan čeka na… Halo oglasi Nekretnine" [ref=f6e73] [cursor=pointer]:
                - /url: https://adclick.g.doubleclick.net/aclk?sa=l&ai=CUg_7BAF_avXRJ7zo-d8PvZ2_-A3X5JavhwHSoNufyRHZ5LGbzAgQASCn5pMjYLEFoAHI2I7fA8gBCakC6b_Hi7QlRT6oAwHIA8sEqgT1AU_QXNM2ojya-H9NXxxkaRpSDMMmdIG7C8MUnZFq2aroq7z9Ysr94l3vFABGouE64BEuq1uxynySDOZNTGbxo9TM_wprxIuXSpXT2uBNvzZ9NB_1RsLUxJe-aXaGhZpkRiKTR1TH6iYWko_V2Mh2Ugz8mxgNcgpjQ0-NMNrOoLCE5gJK3sVInQMBeRcz56fDDEf26_4zDrdbkvdKqKULdtsEZM5G79moRGQQrCusgjNBYeMEma9gk-EqkcCR-3OYaLcfeRVrBOsz5e04t4ZfmgG9faEAWmPjXnAZCNSWoNSg_b8mPusC5JRRC5m1Yg9yISuSQM8RwATiob-flgSIBbehwL1K-gUGCCUQARgAoAYugAegp_EgqAenzLECqAfi2LECqAemvhuoB8zOsQKoB_PRG6gHltgbqAeqm7ECqAf-6LECqAeOzhuoB5PYG6gH8OAbqAfulrECqAf-nrECqAevvrECqAef4bECqAem67ECqAfZtrECqAeaBqgH_56xAqgH35-xAqgH-MKxAqgH4tixAqgH4tixAqgH4tixAqgH4tixAqgH4tixAtgHAMAIAdIIMwiAYRABGJ8DMgiKgoCAgICACDoPgECAwICAgICogAKog4AQSL39wTpYhZWk6oaglgNgAYAKAZALA5gLAcgLAYAMAaIMIEgBYgIKAGoQCg5jb20uaGFsb29nbGFzaXgBiAEBkAEBqg0CUlPIDQHqDRMIt-mk6oaglgMVPHT-BR29zg_f8A0CiA4J2BMKiBQD0BUBmBYByhYCCgD4FgGAFwGyFxAYASoKNTcxODk4MTMwOFAGuhcCOAGqGBcJAAAAAADqukASCjU3MTg5ODEzMDgYAbIYCRICk04YLiIBANAYAegYAcIZAggB&ae=1&gclid=EAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASABEgJe_vD_BwE&num=1&cid=CAQShgIAEQoqgaY0yabUKKsLhlwlpkzSPHk2kchltrk8-I8I2YxZcvhoRMVERUwlmaD0vDrdb8n-Q6mc5_-eJZAHpmbX64MSTpsEB6sCDsr6XLjKeOTU9YEwHRLYzGVf44WsfSAgGyXfrOUkcp-G05M9CDlD3q9IHs8Gav9YcOFcGItEKr0kXbdQ9KOxcyIiF9cNyrD_iS0xCikt1Y9lRDsJY0GL9oJiExf-cvK3-zPZU1OJa0jW6ToNznYYA3qkWX_BTQ3S2QsGWjzFvNX1QmdkkAf-eR4Jzwu1FV14P-ZK15jcgVEy8JA58Bh9MDKpBxQMhsXzI2cJ2xwkUGEi3HzN5IpDKkYng6uCGAE&sig=AOD64_1g-wW01JhgXDEdFtU90_Bv9OepCg&client=ca-pub-2878895907861435&nb=19&adurl=https://www.halooglasi.com/nekretnine/prodaja-stanova/jednoiposoban-stan-na-novoj-detelinari/5425647231245%3Fkid%3D1%26gad_source%3D5%26gad_campaignid%3D19993202871%26gclid%3DEAIaIQobChMI9eOk6oaglgMVPHT-BR29zg_fEAEYASABEgJe_vD_BwE
                - generic [ref=f6e77]:
                  - generic [ref=f6e78]: Tvoj idealni stan čeka na…
                  - generic [ref=f6e79]: Halo oglasi Nekretnine
            - generic [ref=f6e81] [cursor=pointer]
            - button [ref=f6e86] [cursor=pointer]
            - iframe
        - generic [ref=e106]:
          - heading "These are topics related to the article that might interest you" [level=2] [ref=e108]: Discover more
          - link "Draggable Box Testing" [ref=e109] [cursor=pointer]
          - link "Progress Bar Widgets" [ref=e114] [cursor=pointer]
          - link "Calendar & Scheduling Software" [ref=e119] [cursor=pointer]
          - link "Software" [ref=e124] [cursor=pointer]
          - link "Testing Site Access" [ref=e129] [cursor=pointer]
          - link "User Interface Design" [ref=e134] [cursor=pointer]
          - link "Online Image Galleries" [ref=e139] [cursor=pointer]
          - link "Demo Site Hosting" [ref=e144] [cursor=pointer]
      - generic [ref=e150]:
        - list [ref=e151]:
          - tab "Photo Manager" [ref=e152] [cursor=pointer]
          - tab "Accepted Elements" [ref=e153] [cursor=pointer]
          - tab "Propagation" [ref=e154] [cursor=pointer]
        - paragraph [ref=e157]:
          - iframe [ref=e158]:
            - generic [ref=f1e1]:
              - generic [ref=f1e2]:
                - list [ref=f1e3]:
                  - listitem [ref=f1e4]:
                    - heading "High Tatras" [level=5] [ref=f1e5]
                    - img "The peaks of High Tatras" [ref=f1e6]
                    - link "View larger" [ref=f1e7] [cursor=pointer]:
                      - /url: images/high_tatras.jpg
                    - link "Delete image" [ref=f1e8] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                  - listitem [ref=f1e9]:
                    - heading "High Tatras 2" [level=5] [ref=f1e10]
                    - img "The chalet at the Green mountain lake" [ref=f1e11]
                    - link "View larger" [ref=f1e12] [cursor=pointer]:
                      - /url: images/high_tatras2.jpg
                    - link "Delete image" [ref=f1e13] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                  - listitem [ref=f1e14]:
                    - heading "High Tatras 3" [level=5] [ref=f1e15]
                    - img "Planning the ascent" [ref=f1e16]
                    - link "View larger" [ref=f1e17] [cursor=pointer]:
                      - /url: images/high_tatras3.jpg
                    - link "Delete image" [ref=f1e18] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                  - listitem [ref=f1e19]:
                    - heading "High Tatras 4" [level=5] [ref=f1e20]
                    - img "On top of Kozi kopka" [ref=f1e21]
                    - link "View larger" [ref=f1e22] [cursor=pointer]:
                      - /url: images/high_tatras4.jpg
                    - link "Delete image" [ref=f1e23] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                - heading "Trash Trash" [level=4] [ref=f1e25]:
                  - generic [ref=f1e26]: Trash
                  - text: Trash
              - generic [ref=f1e27]:
                - paragraph [ref=f1e28]: You can delete an image either by dragging it to the Trash or by clicking the trash icon.
                - paragraph [ref=f1e29]: You can "recycle" an image by dragging it back to the gallery or by clicking the recycle icon.
                - paragraph [ref=f1e30]: You can view larger image by clicking the zoom icon. Selenium Practice dialog widget is used for the modal window.
          - insertion [ref=e159]
  - generic [ref=e160]:
    - generic:
      - insertion:
        - iframe [ref=e162]:
          
    - generic [ref=e164]:
      - generic [ref=e165]:
        - heading "Footer Widget Area 1" [level=3] [ref=e166]
        - paragraph [ref=e167]:
          - link "Assign a widget to this area now." [ref=e168] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=e169]:
        - heading "Footer Widget Area 2" [level=3] [ref=e170]
        - paragraph [ref=e171]:
          - link "Assign a widget to this area now." [ref=e172] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=e173]:
        - heading "Footer Widget Area 3" [level=3] [ref=e174]
        - paragraph [ref=e175]:
          - link "Assign a widget to this area now." [ref=e176] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=e177]:
        - heading "Footer Widget Area 4" [level=3] [ref=e178]
        - paragraph [ref=e179]:
          - link "Assign a widget to this area now." [ref=e180] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
    - generic [ref=e185]:
      - link "pinterest" [ref=e186] [cursor=pointer]:
        - /url: https://in.pinterest.com/globalsqa/
      - link "twitter" [ref=e187] [cursor=pointer]:
        - /url: https://twitter.com/Global_SQA
      - link "linkedin" [ref=e188] [cursor=pointer]:
        - /url: https://www.linkedin.com/company/globalsqa
      - link "google" [ref=e189] [cursor=pointer]:
        - /url: https://plus.google.com/103761557396023531439/posts
      - link "facebook" [ref=e190] [cursor=pointer]:
        - /url: https://facebook.com/globalsqa
      - generic [ref=e191]:
        - text: "Website Designed & Developed by :"
        - link "GlobalSQA" [ref=e192] [cursor=pointer]:
          - /url: https://www.globalsqa.com
```

# Test source

```ts
  1  | import {expect} from '@playwright/test'
  2  | import {test} from '../test-options'
  3  | 
  4  | test('drag and drop with iframe', async ({ page, globalsQaURL }) => {
> 5  |     await page.goto(globalsQaURL)
     |                ^ TimeoutError: page.goto: Timeout 5000ms exceeded.
  6  |     const frame = page.frameLocator('[rel-title="Photo Manager"] iframe')
  7  |     
  8  |     await frame.locator('li', { hasText: "High Tatras 2" }).dragTo(frame.locator('#trash'))
  9  |     await frame.locator('li', { hasText: "High Tatras 4" }).dragTo(frame.locator('#trash'))
  10 | 
  11 |     await expect(frame.locator('#trash li h5')).toHaveText(["High Tatras 2", "High Tatras 4"])
  12 | })
```