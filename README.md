<!-- All the folder structure information -->
=> Before you start:
   - I have already created all the folders which you will need during journey.

   - Dont use any other folder to make files if you are doing please inform the
     team members that you have created a folder with name.

   - I have already setup all the things related to `redux`, `.env`, `Chakra UI` and `react-router-dom` 
     You guys have to just start developments.

   - Also given you sample `Navbar` and `Footer` components so that you get 
     comfortable about folder components export.

   - You will get all the routing files in `routes` folder.

   - You can also use context-api if needed.

   - All the end-points and base-url should be in env files.

   - Use `assets` folder for images,pdf,video..etc
   - Use `components` folder for making components either in folder or without folder 
     just be sure naming should not match with other folder/file to avoid collision
   - Use `pages` folder to create all the pages
   - Use `routes`  folder to all the routing related stuffs
   - Use `scripts` folder for any js script you wanna write.(this folder helps you to 
     keep jsx and js folder separate)
   - Use `styles` folder to keep your all css files.
   - Use `constants` folder to create all the constants (Helps you reducing hard-coding)(Most recommended)

<!-- Cloning related and Getting started related stuffs -->
=> Clone the directory to start work `$git clone  https://github.com/dev-Imsaurabh/third-ice-7307.git`

=> Ok guys here are the some basic instruction before you start , If you are here you are successfully pulled the code and you are ready to type you first command in terminal.

Step-1- Navigate to proeject directory using `$cd third-ice-7307`

Step-2- install node_modules using `$cd npm install`

Step-3- install some common dependencies:- <br />
            - `$npm install react-router-dom redux react-redux redux-thunk axios`<br />
            - `$npm install @chakra-ui/react @emotion/react @emotion/styled framer-motion`

<!-- Git related stuffs -->
=> Some basic requirements(Mandatory):
       1- You have to work in daily branches manner, so you have to create
          new branch everyday . So you have make branch using your student_code 
          followed the day in which you working. below is the eg for my branches.

               - branch-naming style: fw21_XXXX_day-x

            -for day-2 branch name should be: fw21_1003_day-2
            -for day-3 branch name should be: fw21_1003_day-3
            -for day-4 branch name should be: fw21_1003_day-4
            -for day-5 branch name should be: fw21_1003_day-5

        2- How to create branches:
            - $git branch <branch-name> (without angle brackets)
        
        3- How to switch branches:
            -$git switch <branch-name>  (without angle brackets)
        
        4- How to pull:
            -$git pull origin <branch-name>    (without angle brackets)


=> Some helpful Tools during development :<br />
    - Chakra-UI - https://chakra-ui.com/<br />
    - Chakra-Templets - https://chakra-templates.dev/#<br />
    - String Builder - https://codebeautify.org/string-builder<br />
    - Chat-gpt - https://chat.openai.com/chat<br />
    - Your-Team-members- https://chat.whatsapp.com/KR80RM0zbWi6agJVFL66Z9<br />



************************************* All the best guys ************************************************ 


# Work Flow Chart

*Note:- Bhavnesh will do all the backend and admin panel so you will get apis and endpoint on day-2 morning.

# Endpoints
`/users`
`/products`


# Schemas

  `Product Schema`
```
{   
    "id":0,
    "images":["" , ""],
    "name":"",
    "short_desc":"",
    "long_desc":"",
    "category":"",
    "price":0,
    "strike_price":0,
    "ratings":0,
    "color":"green",
    "delivery_time":3,
    "size":""

} 
```



  `User Schema`
  
```
{
   "id":0,   
  "name": "",
  "email": "",
  "password": "",
  "account": {
    "cart": [
      {"id":0,
        "images": ["", ""],
        "name": "",
        "short_desc": "",
        "long_desc": "",
        "price": 0,
        "category":"",
        "strike_price": 0,
        "ratings": 0,
        "color":"",
        "delivery_time": 0,
        "size":"",
        "quantity":0
      },
      {
        "id":1,
        "images": ["", ""],
        "name": "",
        "short_desc": "",
        "long_desc": "",
        "price": 0,
        "category":"",
        "strike_price": 0,
        "ratings": 0,
        "color":"",
        "delivery_time": 0,
        "size":"",
        "quantity":0
      }
    ],
    "orders": [{
        "id":0,
        "images": ["", ""],
        "name": "",
        "short_desc": "",
        "long_desc": "",
        "price": 0,
        "category":"",
        "strike_price": 0,
        "ratings": 0,
        "color":"",
        "delivery_time": 0,
        "size":"",
        "quantity":0,
        "address":""
    }]
  }
}
```
- Whole  `db.json` Database look

```
 
 {
  "users": [
    {
     "id":0,   
    "name": "user-1",
    "email": "",
    "password": "",
    "account": {
      "cart": [
        {"id":0,
          "images": ["", ""],
          "name": "",
          "short_desc": "",
          "long_desc": "",
          "price": 0,
          "category":"",
          "strike_price": 0,
          "ratings": 0,
          "color":"",
          "delivery_time": 0,
          "size":"",
          "quantity":0
        },
        {
          "id":1,
          "images": ["", ""],
          "name": "",
          "short_desc": "",
          "long_desc": "",
          "price": 0,
          "category":"",
          "strike_price": 0,
          "ratings": 0,
          "color":"",
          "delivery_time": 0,
          "size":"",
          "quantity":0
        }
      ],
      "orders": [{
          "id":0,
          "images": ["", ""],
          "name": "",
          "short_desc": "",
          "long_desc": "",
          "price": 0,
          "category":"",
          "strike_price": 0,
          "ratings": 0,
          "color":"",
          "delivery_time": 0,
          "size":"",
          "quantity":0,
          "address":""
      }]
    }
  },{
    "id":1,   
    "name": "user-2",
    "email": "",
    "password": "",
    "account": {
      "cart": [
        {"id":0,
          "images": ["", ""],
          "name": "",
          "short_desc": "",
          "long_desc": "",
          "price": 0,
          "category":"",
          "strike_price": 0,
          "ratings": 0,
          "color":"",
          "delivery_time": 0,
          "size":"",
          "quantity":0
        },
        {
          "id":1,
          "images": ["", ""],
          "name": "",
          "short_desc": "",
          "long_desc": "",
          "price": 0,
          "category":"",
          "strike_price": 0,
          "ratings": 0,
          "color":"",
          "delivery_time": 0,
          "size":"",
          "quantity":0
        }
      ],
      "orders": [{
          "id":0,
          "images": ["", ""],
          "name": "",
          "short_desc": "",
          "long_desc": "",
          "price": 0,
          "category":"",
          "strike_price": 0,
          "ratings": 0,
          "color":"",
          "delivery_time": 0,
          "size":"",
          "quantity":0,
          "address":""
      }]
    }
  }
  
  ],


  "products": [

    {
      "id": "category-name-1",
      "items": [
        {
          "id": 0,
          "images": ["", ""],
          "name": "",
          "short_desc": "",
          "long_desc": "",
          "price": 0,
          "category":"",
          "strike_price": 0,
          "ratings": 0,
          "color": "",
          "delivery_time": 0,
          "size": ""
        },
        {
          "id": 1,
          "images": ["", ""],
          "name": "",
          "short_desc": "",
          "long_desc": "",
          "price": 0,
          "category":"",
          "strike_price": 0,
          "ratings": 0,
          "color": "",
          "delivery_time": 0,
          "size": ""
        }
      ]
    },

    {
        "id": "category-name-2",
        "items": [
          {
            "id": 0,
            "images": ["", ""],
            "name": "",
            "short_desc": "",
            "long_desc": "",
            "price": 0,
            "category":"",
            "strike_price": 0,
            "ratings": 0,
            "color": "",
            "delivery_time": 0,
            "size": ""
          },
          {
            "id": 1,
            "images": ["", ""],
            "name": "",
            "short_desc": "",
            "long_desc": "",
            "price": 0,
            "category":"",
            "strike_price": 0,
            "ratings": 0,
            "color": "",
            "delivery_time": 0,
            "size": ""
          }
        ]
      }

  ]

  
}

```


# Pages  
  These are the pages we need in this project.

   //Tinkle
   - `HomePage`-------------------->Saurabh/ Tinkle (Day1-Day2)

   - `ViewProductPage`-------------------> Tinkle / Anyone(Help if needed) (Day1-Day2)

   //Farhaz
   - `SignupPage`------------------------->Farhaz (Day1-Day2) 

   - `LoginPage`--------------------------->Farhaz (Day2) //with API connected


   //Saurabh
   - `SearchPage`------------------------> Saurabh (Day3)
   
   - `ProductPage`------------------------> Saurabh (Day3-Day4)

   - `OtpPage`------------------------------>Saurabh / Anyone(Help if needed)


   //Surya
   - `AccountPage`------------------------->Surya / Anyone(Help if needed) (Day-1) (day-2)
   
   - `CartPage`----------------------------> Surya (Day3-Day4) 

   - `Checkout-Page`----------------------------> Surya (Day3-Day4) 

   # Components
     These are the components we need in this project.

   //HomePage
   - `Navbar`----------Tinkle (Day-1)
   - `Footer`----------Tinkle (Day-1)
   - `carousel` ------------Surya (Day-1)
   - `Category-circular-Card`------Saurabh (Day-1)
   - `Category-rectangular-Card`--------Saurabh (Day-1)
   - `brands-Card`-----------Saurabh (Day-1)
   - `banner-Card`-------saurabh (Day-1)
   - `Trending-Card`---------Saurabh (Day-1)

   //ProdcutPage
   - `Filter-box`------Saurabh (Day-2)
   - `Product-Card`---------Saurabh (Day-2)
   - `Sort-Box`---------Saurabh (Day-2)
   
   //SearchBar
   - `Search bar`------Tinkle--> Comes with Navbar (Day-1)
