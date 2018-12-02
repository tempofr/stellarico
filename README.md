
## Getting Started

To build and run locally:

    git clone https://github.com/antb123/stellarico.git \
    && cd stellarico \


## How to add a new ico
  1. Go to content folder
  
   - copy an existing ico and paste in the same folder 
   - rename it with new ico name that you want to submit 
    
    e.g : cp content/ico/tempocrypto.md content/ico/<new_iconame>.md
    mkdir /static/img/ico/<new_iconame>
    mkdir /static/img/ico/<new_iconame>/screenshots
    
  2. update the variables.
  
  [**Variables**](#variables)
  
  3. Add images
   - logo : /static/img/ico/<new_iconame>/logo.png 
   - banner : /static/img/ico/<new_iconame>/banner.png 
   - screenshots : 
     - /static/img/ico/tempocrypto/<new_iconame>/screenshots/1.png
     - /static/img/ico/tempocrypto/<new_iconame>/screenshots/2.png
     - /static/img/ico/tempocrypto/<new_iconame>/screenshots/3.png
     

## images size 
    logo 150x150 px
    banner 800x300 px 
    screenshot 350x200 px


## variables

  - title : < title/name of the ico>
  - date : "2018-11-08T00:00:00Z"
    - when ico is created
  - tags : ["upcoming","Payments","airdrop"] 
    - add tags here
  - categories : ["upcoming", "Payments","airdrop"]
    - add categories it must contain one of these ( "active", "upcoming",   "ended" ) otherwise ico will not display on home page
  - ticket : "Payments"
  - banner : "img/ico/tempocrpto/background.jpg"
    - banner path
  - logo : "img/ico/tempo/Tempo_logo_white150x150.jpg"
    - logo path
  - image : ""
    -this is optional  
  - description : "The easiest, fastest and most secure bridge between cash and crypto!"
  - long_description: "Blah blah blah....Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit"
 - money_goal : "1,000,000" 
 - goal : "7,000,000 (13%)"
 - start_date: "2018-11-08T00:00:00Z"
 - end_date : "2018-11-18T00:00:00Z"
 - rating : 3
 - ticker : TEMPO
 - token_type : STELLAR
 - token_price: "1 TEMPO = 0.1200 EUR"
 - softcap_goal: 1,500,000 EUR
 - fundraising_goal: 7,000,000 EUR
 - available_for_token_sale: 20%
 - kyc: YES (1 JAN - AUG – 7 SEP)
 - accepted_currency :  BTC, ETH, XRP, XLM, EURT, EUR, JPY
 - non_participate: NORTH KOREA, CUBA, Syria, Crimea/Sevastopol, USA (limited)
 - airdrop : YES
 - airdrop_live : NO
 - country: FR
 - bounty : "https://ico.tempo.eu.com/bounty"
 - additional_links : ["https://stellar.org/",
        "https://tempo.eu.com/"] 
 - screenshots : 
            [ "/img/ico/tempocrypto/screenshots/1.jpg",
              "/img/ico/tempocrypto/screenshots/2.jpg",
              "/img/ico/tempocrypto/screenshots/3.jpg",
              "/img/ico/tempocrypto/screenshots/4.jpg",] 
   - screenshot path
 - website : "https://ico.tempo.eu.com"
 - whitepaper_url : "https://irp-cdn.multiscreensite.com/d3d3962e/files/uploaded/TEMPO-Whitepaper-pre-release-v27.a.pdf.pdf"
 - twitter_url : "https://twitter.com/tempo_eu"
 - telegram_url : "https://t.me/joinchat/Cl6wihECcZFcv2tJcFEY5Q"
 - github_url: "https://github.com/tempofr"
 - reddit_url: "https://www.reddit.com/user/TempoMoneyTransfer"
 - facebook_url: "https://www.facebook.com/TEMPOMoneyTransfer/"
 - bitcointalk_url : "https://bitcointalk.org/index.php?topic=5025231.msg45455624#msg45455624"
 - youtube_url : "https://www.youtube.com/channel/UC-MI1jnOA1T1ublc6QoJ71w"
 - linkedin_url : "https://fr.linkedin.com/company/tempo-france-sas"
 - og_png: "img/ico/tempocrypto/Tempo-Main.jpg"
 - tw_png: "img/ico/tempocrypto/Tempo-Main.jpg"
 - weight: 5 
   - give the weight to ICO 0 (zero is minimum ) on the basis of this weight ico will show on home page 
   
  Push any changes and they will automatically be accepted once reviewed and pushed to the website. 



