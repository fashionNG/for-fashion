# for-fashion



{
    
    "name": "fashion speed",
    "description": "will be used to speed up website",
    "version": "0.7",
    "category": "analytics",
    "main": "public/javascripts/app_module.js",
    "config":{
        "details":{
            "Language": "English",
            "Price": "Free",
            "Restrictions": "None",
            "TOS":"http://www.cloudflare.com/terms",
            "has_js": true
        }, 
        "assets":{
            "logos" : {
                "200px": "./public/images/logo-200.png",
                "132px": "./public/images/logo-132.png"
            },
            "detail_page" : [
                "./public/images/example.png"
            ],
            "images" : [
                "./public/images/counter.png"
            ]
        },
        "interface": [
            {
                "type": "string",
                "id": "food",
                "name": "Favorite Food",
                "description": "Please tell us your favorite food.",
                "domain_request": true,
                "private": true
            },
            {
                "type": "select",
                "id": "lottery",
                "name": "Do you Lotto?",
                "description": "Choose whether to buy a ticket",
                "options": [
                    {
                        "label": "Yes, buy a ticket!",
                        "value": "true"
                    },
                    {
                        "label": "No, I am scared.",
                        "value": ""
                    }
                ]
            }
        ]
    },
    "account": {
        "callback_url": "http://countersback.herokuapp.com/api",
        "user_fields": ["email"]
    },
    "billing": {
        "type": "zone",
        "plans":[
            {
                "name" : "Chowder",
                "price": "3.20"
            },
            {
                "name" : "Minestrone",
                "price" : "6.55"
            }
        ]
    }
}



