


{
    
    "name": "faashion speed",
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
                "200px": ".http://www.fashiononline.com.ng/wp-content/uploads/2013/12/AB-2new1.png",
                "132px": ".http://www.fashiononline.com.ng/wp-content/uploads/2013/12/AB-2new1.png"
            },
            "detail_page" : [
                "http://www.fashiononline.com.ng/wp-content/uploads/2013/12/AB-2new1.png"
            ],
            "images" : [
                ".http://www.fashiononline.com.ng/wp-content/uploads/2013/12/AB-2new1.png
            ]
        },
        "interface": [
            {
                "type": "string",
                "id": "clothes",
                "name": "Favorite dress",
                "description": "Please tell us your favorite dress.",
                "domain_request": true,
                "private": true
            },
            {
                "type": "select",
                "id": "shopping",
                "name": "Do you shop?",
                "description": "Choose whether to buy a shopping voucher",
                "options": [
                    {
                        "label": "Yes, buy a shopping voucher!",
                        "value": "true"
                    },
                    {
                        "label": "yes i want one.",
                        "value": ""
                    }
                ]
            }
        ]
    },
    "account": {
        "callback_url": "http://faashiononline.com.ng/api",
        "user_fields": ["fashiononline.com.ng"]
    },
    "billing": {
        "type": "zone",
        "plans":[
            {
                "name" : "fashion applet",
                "price": "3.20"
            },
            {
                "name" : "fashion app",
                "price" : "6.55"
            }
        ]
    }
}

