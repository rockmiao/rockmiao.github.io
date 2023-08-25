# rockmiao.github.io

## Environment setup

1. 把這個repo放在跟Pure-HTML-Calendar repo 資料夾相同層級中
2. 到Github->Settings->Developer settings->Personal access tokens->Tokens->Generate new token( Classic )
3. Note隨便打，自己看得懂就好; Exprations如果不想要一直換這個token, 就選不會過期的選項
4. 下面就全部勾選即可-> Generate token
5. 把新增的token複製下來 
6. ```git config --global credential.helper store```
7. ```git credential approve <<< "url=https://github.com username=<YOUR-USERNAME> password=<YOUR-TOKEN>"```
8. 這樣才可以在算完calendar之後直接把結果push到git page網頁上

    *And you are all set*

## Current Work Flow

1. 每當執行完 ```processOnlineReservation.sh``` 後，電腦會自動將calendar的變更push到git page上

## Notice