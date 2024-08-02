![DEMO](https://github.com/kunz398/FlakesApiV2/blob/main/ss_1.jpeg?raw=true)
> How to use Api:

**Get EFL Bill**

> http://API_LINK/get_efl

    {
    "username":"efl_username", 
    "password":"password",
    "account_number":"account#"
    }
*type: POST*

**Get Connect Bill**

> http://API_LINK/get_connect

  

      {
        "username":"connect_username" ,
        "password":"password"
        }

*type: POST*

**Get Water authority bill**

> http://API_LINK/get_waf

    {"account_number":  "waf_acc_num"}

*type: POST*
