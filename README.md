# Instructions
These tests shouldn't take more than 120 minutes. If you don't want to finish it then submit what you have done after 120 minutes.

Please do not fork this repo on github or open a pull request. Submit your solution in an archive to your HR.

## Test #1: Base on below context, develop the structure for automation script using any language revolving around Selenium with your best ideology. 

*Our client covid-rox is developing an application to track how many people are infected by it worldwide.  It will be available in three different platform (iOS,Android and Web); fast forward, below will be the pseudo application just enough for you to code*

### User stories
 * As a user, I would like to reach landing screen after login successfully with a valid credential.

 * As a user, I would like to be prompt with error message if I enter password and username length greater than 8 and invalid credential entere.

 * As a user, I would like to see submit button disable if either one of the fields(username/password) is empty.

**iOS element IDs**
```
username field: ios_username
password field: ios_password
error message field: ios_error_message
login button: ios_login_button
```

**Android element IDs**
```
username field: android_username
password field: android_password
error message field: android_error_message
login button: android_login_button
```

**Web app element IDs**
```
username field: web_username
password field: web_password
error message field: web_error_message
login button: web_login_button
```

## Test #2: Write a short function to retrieve all key values in the below JSON. 
```
{
    "total_rows": 184,
    "offset": 0,
    "rows": [
        {
            "id": "SIT/DRA/2020/001",
            "key": "SIT/DRA/2020/001",
            "value": {
                "rev": "645-2f3611a220ac5cc86186764304f2e4b5"
            }
        },
        {
            "id": "SIT/DRA/2020/002",
            "key": "SIT/DRA/2020/002",
            "value": {
                "rev": "630-19697a00a20857b46406c9ed55fa75da"
            },
            "counter1": [
                {
                    "id": "1234",
                    "counter2": [
	                        {
                            "id": "1234"
                        }
                    ]
                }
	            ]
        }
	    ],
    "date": "12/12/2001"
}
```
